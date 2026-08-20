# Academic Homepage (Jekyll)

A one-page academic homepage. No theme gem, no submodules — every layout,
include and stylesheet lives in this repository.

The whole site is **one page** with four sections (`About Me`, `Research
Interests`, `Publications`, `Educations`), plus a fixed profile sidebar. The
top navigation scrolls to sections on that same page.

---

## Run it locally

Ruby is already installed. From this folder:

```bash
bundle exec jekyll serve --livereload
```

Open <http://127.0.0.1:4000>. Saving any file rebuilds and refreshes the page
automatically — **except `_config.yml`, which requires restarting the server**
(Ctrl-C, then run the command again).

---

## Where each thing lives

| You want to change | Edit this |
| --- | --- |
| Name, position, university, email, Scholar/GitHub/ORCID links | `_config.yml` → `author:` |
| Profile photo | drop a square image at `assets/img/profile.png` |
| The four section texts | `_pages/about.md` |
| A paper | one file per paper in `_publications/` |
| Navigation labels / order | `_data/navigation.yml` |
| Page background pattern | `_config.yml` → `background:` |
| Colours, fonts, spacing | `_sass/_main.scss` (tokens at the top) |

---

## 1. The sidebar — `_config.yml`

Everything under `author:` feeds the left sidebar.

```yaml
author:
  name           : "Your Name"        # also used to bold you in author lists
  name_zh        : "你的中文名"        # delete the line if you don't want it
  position       : "PhD Student"
  affiliation    : "Department of Computer Science"
  university     : "Your University"
  location       : "City, Country"
  email          : "you@example.edu"
  scholar        : "https://scholar.google.com/citations?user=XXXXXXX"
  github         : "https://github.com/yourname"
  twitter        : ""                 # "" hides the link entirely
  linkedin       : ""
  orcid          : ""
  semantic       : ""
  dblp           : ""
  bio            : >-
    One or two sentences shown under your name.
```

**Set a link to `""` to hide it.** Don't delete the key — the template checks it.

Restart the server after editing this file.

---

## 2. The four sections — `_pages/about.md`

Each section is a `<section>` block. Inside one, you write **normal Markdown**
(that is what `markdown="1"` on the tag enables):

```html
<section id="about" class="section" markdown="1">

## About Me

Write freely here. **Bold**, *italic*, and [links](https://example.com) work.

</section>
```

Rules that matter:

- **`id` must match `_data/navigation.yml`.** The nav links are `#about`,
  `#interests`, `#publications`, `#educations`. Change an `id` and you must
  change the nav entry too, or the link goes nowhere.
- **Keep the blank line after `<section …>` and before `</section>`.** Without
  it, kramdown stops treating the contents as Markdown and your `##` headings
  render as literal text.
- To **remove a section**, delete the whole `<section>…</section>` block *and*
  its entry in `_data/navigation.yml`.
- To **add a section**, copy an existing block, give it a new `id`, and add a
  matching entry to `_data/navigation.yml`.

### Educations entries

These are hand-written HTML (a two-column row: dates on the left, detail on the
right). Copy one `<li>` and edit:

```html
<li>
  <span class="when">2022 – present</span>
  <span class="what"><strong>Ph.D. in Computer Science</strong>
    <span>Your University · Advisor: Prof. Advisor Name</span></span>
</li>
```

`when` is the date range, the `<strong>` is the degree, the inner `<span>` is
the smaller grey line under it.

---

## 3. Papers — `_publications/`

**One Markdown file per paper.** The filename doesn't appear anywhere; use
`year-short-name.md` so the folder stays sorted. Copy an existing file:

```yaml
---
title:        "Robust Instruction Tuning Under Distribution Shift"
authors:      "Your Name, Coauthor One, Advisor Name"   # comma + space between names
venue_short:  "NeurIPS 2026"      # the small badge in front of the title
year:         2026
date:         2026-06-15          # sorting key — newest first
note:         "Spotlight (top 3%)"   # optional, shown in italics
paper:        "https://..."       # optional
arxiv:        "https://..."       # optional
code:         "https://..."       # optional
slides:       ""                  # optional
poster:       ""                  # optional
video:        ""                  # optional
---
```

- Papers are sorted by **`date`**, newest first. There are no year headings.
- Your own name is **bolded automatically** wherever it matches `author.name`
  in `_config.yml` — so spell it identically in both places.
- Any link field you leave out (or set to `""`) simply doesn't render.
- The body below the `---` is currently unused; you can leave it empty.

**Preprints** are different: that block is written by hand at the bottom of the
Publications section in `_pages/about.md`. Edit or delete it there.

---

## 4. Navigation — `_data/navigation.yml`

```yaml
main:
  - title: "About Me"          # the label shown
    id: about                  # must match a <section id="..."> in about.md
```

Reorder, rename, add or remove entries freely. `id` is the contract with
`about.md`.

---

## 5. Background

`_config.yml` → `background:`. Options, all pure CSS, all defined in
`_sass/_backgrounds.scss`:

`aurora` (current) · `go` (围棋) · `contour` (等高线) · `paper` (稿纸) ·
`staff` (五线谱) · `film` (胶片) · `pixel` (点阵) · `table` (球台) · `none`

Intensity for every pattern is controlled by `--pat` and `--pat-strong` at the
top of that file.

---

## 6. Colours, fonts, spacing — `_sass/_main.scss`

Design tokens sit at the very top; the dark-mode block right below overrides
them for readers whose system is in dark mode. Change `--accent` and `--link`
and the whole page follows.

One trap if you edit this file: rules for page components (`.pub`, `.timeline`,
`.news`, …) are written as `.prose .pub { … }`. The `.prose` prefix is
**required** — without it the generic `.prose p` / `.prose h3` / `.prose li`
rules win on specificity and silently override your margins.

---

## Deploying later

Nothing here is deployment-specific.

- **GitHub Pages** — add the standard `actions/jekyll-build-pages` workflow, and
  set `url` / `baseurl` in `_config.yml`.
- **Netlify / Vercel / Cloudflare Pages** — build `jekyll build`, publish `_site`.
- **Your own server** — `bundle exec jekyll build`, copy `_site/` to the web root.

## Unused leftovers

- `_talks/` — the section that displayed these was removed; the folder and the
  `talks` collection in `_config.yml` are currently inert. Safe to delete.
- `files/` — for `cv.pdf` and similar. Nothing links to it right now.
