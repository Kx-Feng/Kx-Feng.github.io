source "https://rubygems.org"

# Local development with a modern Jekyll.
gem "jekyll", "~> 4.3"
gem "webrick", "~> 1.8"          # needed on Ruby >= 3.0 to serve locally

# Windows has no system tzinfo database; Jekyll needs these when
# `timezone` is set in _config.yml.
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
  gem "wdm", "~> 0.2"            # faster file watching for --livereload
end

group :jekyll_plugins do
  gem "jekyll-feed",    "~> 0.17"
  gem "jekyll-sitemap", "~> 1.4"
  gem "jekyll-seo-tag", "~> 2.8"
  gem "jekyll-paginate", "~> 1.1"
end

# If you later deploy with GitHub Pages' own build (not Actions),
# comment out the block above and use this instead:
#   gem "github-pages", group: :jekyll_plugins
