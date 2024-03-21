---
weight: 10
bookFlatSection: true
title: "LLM with Copyright"
---
 <!--more-->
# Arxiv Papers: LLM with Copyright

>**_2024-03-15_**

[**Lost in Overlap: Exploring Watermark Collision in LLMs**](http://arxiv.org/abs/2403.10020v1)

*Yiyang Luo, Ke Lin, Chao Gu*

{{< details "abstract" >}} abstract: The proliferation of large language models (LLMs) in generating contentraises concerns about text copyright. Watermarking methods, particularlylogit-based approaches, embed imperceptible identifiers into text to addressthese challenges. However, the widespread use of watermarking across diverseLLMs has led to an inevitable issue known as watermark collision during commontasks like question answering and paraphrasing. This study focuses on dualwatermark collisions, where two watermarks are present simultaneously in thesame text. The research demonstrates that watermark collision poses a threat todetection performance for detectors of both upstream and downstream watermarkalgorithms.
{{< /details >}}

[**SciAssess: Benchmarking LLM Proficiency in Scientific Literature Analysis**](http://arxiv.org/abs/2403.01976v2)

*Hengxing Cai, Xiaochen Cai, Junhan Chang, Sihang Li, Lin Yao, Changxin Wang, Zhifeng Gao, Hongshuai Wang, Yongge Li, Mujie Lin, Shuwen Yang, Jiankun Wang, Yuqi Yin, Yaqi Li, Linfeng Zhang, Guolin Ke*

{{< details "abstract" >}} abstract: Recent breakthroughs in Large Language Models (LLMs) have revolutionizednatural language understanding and generation, igniting a surge of interest inleveraging these technologies in the field of scientific literature analysis.Existing benchmarks, however, inadequately evaluate the proficiency of LLMs inscientific literature analysis, especially in scenarios involving complexcomprehension and multimodal data. In response, we introduced SciAssess, abenchmark tailored for the in-depth analysis of scientific literature, craftedto provide a thorough assessment of LLMs' efficacy. SciAssess focuses onevaluating LLMs' abilities in memorization, comprehension, and analysis withinthe context of scientific literature analysis. It includes representative tasksfrom diverse scientific fields, such as general chemistry, organic materials,and alloy materials. And rigorous quality control measures ensure itsreliability in terms of correctness, anonymization, and copyright compliance.SciAssess evaluates leading LLMs, including GPT-4, GPT-3.5, and Gemini,identifying their strengths and aspects for improvement and supporting theongoing development of LLM applications in scientific literature analysis.SciAssess and its resources are made available at https://sci-assess.github.io,offering a valuable tool for advancing LLM capabilities in scientificliterature analysis.
{{< /details >}}

>**_2024-03-13_**

[**Second-Order Information Matters: Revisiting Machine Unlearning for Large Language Models**](http://arxiv.org/abs/2403.10557v1)

*Kang Gu, Md Rafi Ur Rashid, Najrin Sultana, Shagufta Mehnaz*

{{< details "abstract" >}} abstract: With the rapid development of Large Language Models (LLMs), we have witnessedintense competition among the major LLM products like ChatGPT, LLaMa, andGemini. However, various issues (e.g. privacy leakage and copyright violation)of the training corpus still remain underexplored. For example, the Times suedOpenAI and Microsoft for infringing on its copyrights by using millions of itsarticles for training. From the perspective of LLM practitioners, handling suchunintended privacy violations can be challenging. Previous work addressed the``unlearning" problem of LLMs using gradient information, while they mostlyintroduced significant overheads like data preprocessing or lacked robustness.In this paper, contrasting with the methods based on first-order information,we revisit the unlearning problem via the perspective of second-orderinformation (Hessian). Our unlearning algorithms, which are inspired by classicNewton update, are not only data-agnostic/model-agnostic but also proven to berobust in terms of utility preservation or privacy guarantee. Through acomprehensive evaluation with four NLP datasets as well as a case study onreal-world datasets, our methods consistently show superiority over thefirst-order methods.
{{< /details >}}

>**_2024-03-09_**

[**Detecting Pretraining Data from Large Language Models**](http://arxiv.org/abs/2310.16789v3)

*Weijia Shi, Anirudh Ajith, Mengzhou Xia, Yangsibo Huang, Daogao Liu, Terra Blevins, Danqi Chen, Luke Zettlemoyer*

{{< details "abstract" >}} abstract: Although large language models (LLMs) are widely deployed, the data used totrain them is rarely disclosed. Given the incredible scale of this data, up totrillions of tokens, it is all but certain that it includes potentiallyproblematic text such as copyrighted materials, personally identifiableinformation, and test data for widely reported reference benchmarks. However,we currently have no way to know which data of these types is included or inwhat proportions. In this paper, we study the pretraining data detectionproblem: given a piece of text and black-box access to an LLM without knowingthe pretraining data, can we determine if the model was trained on the providedtext? To facilitate this study, we introduce a dynamic benchmark WIKIMIA thatuses data created before and after model training to support gold truthdetection. We also introduce a new detection method Min-K% Prob based on asimple hypothesis: an unseen example is likely to contain a few outlier wordswith low probabilities under the LLM, while a seen example is less likely tohave words with such low probabilities. Min-K% Prob can be applied without anyknowledge about the pretraining corpus or any additional training, departingfrom previous detection methods that require training a reference model on datathat is similar to the pretraining data. Moreover, our experiments demonstratethat Min-K% Prob achieves a 7.4% improvement on WIKIMIA over these previousmethods. We apply Min-K% Prob to three real-world scenarios, copyrighted bookdetection, contaminated downstream example detection and privacy auditing ofmachine unlearning, and find it a consistently effective solution.
{{< /details >}}

>**_2024-02-29_**

[**An Unforgeable Publicly Verifiable Watermark for Large Language Models**](http://arxiv.org/abs/2307.16230v5)

*Aiwei Liu, Leyi Pan, Xuming Hu, Shu'ang Li, Lijie Wen, Irwin King, Philip S. Yu*

{{< details "abstract" >}} abstract: Recently, text watermarking algorithms for large language models (LLMs) havebeen proposed to mitigate the potential harms of text generated by LLMs,including fake news and copyright issues. However, current watermark detectionalgorithms require the secret key used in the watermark generation process,making them susceptible to security breaches and counterfeiting during publicdetection. To address this limitation, we propose an unforgeable publiclyverifiable watermark algorithm that uses two different neural networks forwatermark generation and detection, instead of using the same key at bothstages. Meanwhile, the token embedding parameters are shared between thegeneration and detection networks, which makes the detection network achieve ahigh accuracy very efficiently. Experiments demonstrate that our algorithmattains high detection accuracy and computational efficiency through neuralnetworks with a minimized number of parameters. Subsequent analysis confirmsthe high complexity involved in forging the watermark from the detectionnetwork. Our code and data are available at\href{https://github.com/THU-BPM/unforgeable_watermark}{https://github.com/THU-BPM/unforgeable\_watermark}.
{{< /details >}}

[**PRSA: Prompt Reverse Stealing Attacks against Large Language Models**](http://arxiv.org/abs/2402.19200v1)

*Yong Yang, Xuhong Zhang, Yi Jiang, Xi Chen, Haoyu Wang, Shouling Ji, Zonghui Wang*

{{< details "abstract" >}} abstract: Prompt, recognized as crucial intellectual property, enables large languagemodels (LLMs) to perform specific tasks without the need of fine-tuning,underscoring their escalating importance. With the rise of prompt-basedservices, such as prompt marketplaces and LLM applications, providers oftendisplay prompts' capabilities through input-output examples to attract users.However, this paradigm raises a pivotal security concern: does the exposure ofinput-output pairs pose the risk of potential prompt leakage, infringing on theintellectual property rights of the developers? To our knowledge, this problemstill has not been comprehensively explored yet. To remedy this gap, in thispaper, we perform the first in depth exploration and propose a novel attackframework for reverse-stealing prompts against commercial LLMs, namely PRSA.The main idea of PRSA is that by analyzing the critical features of theinput-output pairs, we mimic and gradually infer (steal) the target prompts. Indetail, PRSA mainly consists of two key phases: prompt mutation and promptpruning. In the mutation phase, we propose a prompt attention algorithm basedon differential feedback to capture these critical features for effectivelyinferring the target prompts. In the prompt pruning phase, we identify and maskthe words dependent on specific inputs, enabling the prompts to accommodatediverse inputs for generalization. Through extensive evaluation, we verify thatPRSA poses a severe threat in real world scenarios. We have reported thesefindings to prompt service providers and actively collaborate with them to takeprotective measures for prompt copyright.
{{< /details >}}

>**_2024-02-23_**

[**Who Wrote this Code? Watermarking for Code Generation**](http://arxiv.org/abs/2305.15060v3)

*Taehyun Lee, Seokhee Hong, Jaewoo Ahn, Ilgee Hong, Hwaran Lee, Sangdoo Yun, Jamin Shin, Gunhee Kim*

{{< details "abstract" >}} abstract: With the remarkable generation performance of large language models, ethicaland legal concerns about using them have been raised, such as plagiarism andcopyright issues. For such concerns, several approaches to watermark and detectLLM-generated text have been proposed very recently. However, we discover thatthe previous methods fail to function appropriately with code generation tasksbecause of the syntactic and semantic characteristics of code. Based on\citet{Kirchenbauer2023watermark}, we propose a new watermarking method,Selective WatErmarking via Entropy Thresholding (SWEET), that promotes "green"tokens only at the position with high entropy of the token distribution duringgeneration, thereby preserving the correctness of the generated code. Thewatermarked code is detected by the statistical test and Z-score based on theentropy information. Our experiments on HumanEval and MBPP show that SWEETsignificantly improves the Pareto Frontier between the code correctness andwatermark detection performance. We also show that notable post-hoc detectionmethods (e.g. DetectGPT) fail to work well in this task. Finally, we show thatsetting a reasonable entropy threshold is not much of a challenge. Code isavailable at https://github.com/hongcheki/sweet-watermark.
{{< /details >}}

>**_2024-02-22_**

[**Exploring Memorization in Fine-tuned Language Models**](http://arxiv.org/abs/2310.06714v2)

*Shenglai Zeng, Yaxin Li, Jie Ren, Yiding Liu, Han Xu, Pengfei He, Yue Xing, Shuaiqiang Wang, Jiliang Tang, Dawei Yin*

{{< details "abstract" >}} abstract: Large language models (LLMs) have shown great capabilities in various tasksbut also exhibited memorization of training data, raising tremendous privacyand copyright concerns. While prior works have studied memorization duringpre-training, the exploration of memorization during fine-tuning is ratherlimited. Compared to pre-training, fine-tuning typically involves moresensitive data and diverse objectives, thus may bring distinct privacy risksand unique memorization behaviors. In this work, we conduct the firstcomprehensive analysis to explore language models' (LMs) memorization duringfine-tuning across tasks. Our studies with open-sourced and our own fine-tunedLMs across various tasks indicate that memorization presents a strong disparityamong different fine-tuning tasks. We provide an intuitive explanation of thistask disparity via sparse coding theory and unveil a strong correlation betweenmemorization and attention score distribution.
{{< /details >}}

>**_2024-02-20_**

[**Privacy Issues in Large Language Models: A Survey**](http://arxiv.org/abs/2312.06717v3)

*Seth Neel, Peter Chang*

{{< details "abstract" >}} abstract: This is the first survey of the active area of AI research that focuses onprivacy issues in Large Language Models (LLMs). Specifically, we focus on workthat red-teams models to highlight privacy risks, attempts to build privacyinto the training or inference process, enables efficient data deletion fromtrained models to comply with existing privacy regulations, and tries tomitigate copyright issues. Our focus is on summarizing technical research thatdevelops algorithms, proves theorems, and runs empirical evaluations. Whilethere is an extensive body of legal and policy work addressing these challengesfrom a different angle, that is not the focus of our survey. Nevertheless,these works, along with recent legal developments do inform how these technicalproblems are formalized, and so we discuss them briefly in Section 1. While wehave made our best effort to include all the relevant work, due to the fastmoving nature of this research we may have missed some recent work. If we havemissed some of your work please contact us, as we will attempt to keep thissurvey relatively up to date. We are maintaining a repository with the list ofpapers covered in this survey and any relevant code that was publicly availableat https://github.com/safr-ml-lab/survey-llm.
{{< /details >}}

>**_2024-02-19_**

[**Purifying Large Language Models by Ensembling a Small Language Model**](http://arxiv.org/abs/2402.14845v1)

*Tianlin Li, Qian Liu, Tianyu Pang, Chao Du, Qing Guo, Yang Liu, Min Lin*

{{< details "abstract" >}} abstract: The emerging success of large language models (LLMs) heavily relies oncollecting abundant training data from external (untrusted) sources. Despitesubstantial efforts devoted to data cleaning and curation, well-constructedLLMs have been reported to suffer from copyright infringement, data poisoning,and/or privacy violations, which would impede practical deployment of LLMs. Inthis study, we propose a simple and easily implementable method for purifyingLLMs from the negative effects caused by uncurated data, namely, throughensembling LLMs with benign and small language models (SLMs). Aside fromtheoretical guarantees, we perform comprehensive experiments to empiricallyconfirm the efficacy of ensembling LLMs with SLMs, which can effectivelypreserve the performance of LLMs while mitigating issues such as copyrightinfringement, data poisoning, and privacy violations.
{{< /details >}}

[**HU at SemEval-2024 Task 8A: Can Contrastive Learning Learn Embeddings to Detect Machine-Generated Text?**](http://arxiv.org/abs/2402.11815v1)

*Shubhashis Roy Dipta, Sadat Shahriar*

{{< details "abstract" >}} abstract: This paper describes our system developed for SemEval-2024 Task 8,"Multigenerator, Multidomain, and Multilingual Black-Box Machine-Generated TextDetection." Machine-generated texts have been one of the main concerns due tothe use of large language models (LLM) in fake text generation, phishing,cheating in exams, or even plagiarizing copyright materials. A lot of systemshave been developed to detect machine-generated text. Nonetheless, the majorityof these systems rely on the text-generating model, a limitation that isimpractical in real-world scenarios, as it's often impossible to know whichspecific model the user has used for text generation. In this work, we proposea single model based on contrastive learning, which uses ~40% of the baseline'sparameters (149M vs. 355M) but shows a comparable performance on the testdataset (21st out of 137 participants). Our key finding is that even without anensemble of multiple models, a single base model can have comparableperformance with the help of data augmentation and contrastive learning.
{{< /details >}}

>**_2024-02-16_**

[**Large Language Model Unlearning**](http://arxiv.org/abs/2310.10683v2)

*Yuanshun Yao, Xiaojun Xu, Yang Liu*

{{< details "abstract" >}} abstract: We study how to perform unlearning, i.e. forgetting undesirable misbehaviors,on large language models (LLMs). We show at least three scenarios of aligningLLMs with human preferences can benefit from unlearning: (1) removing harmfulresponses, (2) erasing copyright-protected content as requested, and (3)reducing hallucinations. Unlearning, as an alignment technique, has threeadvantages. (1) It only requires negative (e.g. harmful) examples, which aremuch easier and cheaper to collect (e.g. via red teaming or user reporting)than positive (e.g. helpful and often human-written) examples required in RLHF(RL from human feedback). (2) It is computationally efficient. (3) It isespecially effective when we know which training samples cause the misbehavior.To the best of our knowledge, our work is among the first to explore LLMunlearning. We are also among the first to formulate the settings, goals, andevaluations in LLM unlearning. We show that if practitioners only have limitedresources, and therefore the priority is to stop generating undesirable outputsrather than to try to generate desirable outputs, unlearning is particularlyappealing. Despite only having negative samples, our ablation study shows thatunlearning can still achieve better alignment performance than RLHF with just2% of its computational time.
{{< /details >}}

>**_2024-02-15_**

[**Rethinking Machine Unlearning for Large Language Models**](http://arxiv.org/abs/2402.08787v2)

*Sijia Liu, Yuanshun Yao, Jinghan Jia, Stephen Casper, Nathalie Baracaldo, Peter Hase, Xiaojun Xu, Yuguang Yao, Hang Li, Kush R. Varshney, Mohit Bansal, Sanmi Koyejo, Yang Liu*

{{< details "abstract" >}} abstract: We explore machine unlearning (MU) in the domain of large language models(LLMs), referred to as LLM unlearning. This initiative aims to eliminateundesirable data influence (e.g., sensitive or illegal information) and theassociated model capabilities, while maintaining the integrity of essentialknowledge generation and not affecting causally unrelated information. Weenvision LLM unlearning becoming a pivotal element in the life-cycle managementof LLMs, potentially standing as an essential foundation for developinggenerative AI that is not only safe, secure, and trustworthy, but alsoresource-efficient without the need of full retraining. We navigate theunlearning landscape in LLMs from conceptual formulation, methodologies,metrics, and applications. In particular, we highlight the often-overlookedaspects of existing LLM unlearning research, e.g., unlearning scope, data-modelinteraction, and multifaceted efficacy assessment. We also draw connectionsbetween LLM unlearning and related areas such as model editing, influencefunctions, model explanation, adversarial training, and reinforcement learning.Furthermore, we outline an effective assessment framework for LLM unlearningand explore its applications in copyright and privacy safeguards andsociotechnical harm reduction.
{{< /details >}}

>**_2024-02-14_**

[**Copyright Traps for Large Language Models**](http://arxiv.org/abs/2402.09363v1)

*Matthieu Meeus, Igor Shilov, Manuel Faysse, Yves-Alexandre de Montjoye*

{{< details "abstract" >}} abstract: Questions of fair use of copyright-protected content to train Large LanguageModels (LLMs) are being very actively debated. Document-level inference hasbeen proposed as a new task: inferring from black-box access to the trainedmodel whether a piece of content has been seen during training. SOTA methodshowever rely on naturally occurring memorization of (part of) the content.While very effective against models that memorize a lot, we hypothesize--andlater confirm--that they will not work against models that do not naturallymemorize, e.g. medium-size 1B models. We here propose to use copyright traps,the inclusion of fictitious entries in original content, to detect the use ofcopyrighted materials in LLMs with a focus on models where memorization doesnot naturally occur. We carefully design an experimental setup, randomlyinserting traps into original content (books) and train a 1.3B LLM. We firstvalidate that the use of content in our target model would be undetectableusing existing methods. We then show, contrary to intuition, that evenmedium-length trap sentences repeated a significant number of times (100) arenot detectable using existing methods. However, we show that longer sequencesrepeated a large number of times can be reliably detected (AUC=0.75) and usedas copyright traps. We further improve these results by studying how the numberof times a sequence is seen improves detectability, how sequences with higherperplexity tend to be memorized more, and how taking context into accountfurther improves detectability.
{{< /details >}}

[**Trained Without My Consent: Detecting Code Inclusion In Language Models Trained on Code**](http://arxiv.org/abs/2402.09299v1)

*Vahid Majdinasab, Amin Nikanjam, Foutse Khomh*

{{< details "abstract" >}} abstract: Code auditing ensures that the developed code adheres to standards,regulations, and copyright protection by verifying that it does not containcode from protected sources. The recent advent of Large Language Models (LLMs)as coding assistants in the software development process poses new challengesfor code auditing. The dataset for training these models is mainly collectedfrom publicly available sources. This raises the issue of intellectual propertyinfringement as developers' codes are already included in the dataset.Therefore, auditing code developed using LLMs is challenging, as it isdifficult to reliably assert if an LLM used during development has been trainedon specific copyrighted codes, given that we do not have access to the trainingdatasets of these models. Given the non-disclosure of the training datasets,traditional approaches such as code clone detection are insufficient forasserting copyright infringement. To address this challenge, we propose a newapproach, TraWiC; a model-agnostic and interpretable method based on membershipinference for detecting code inclusion in an LLM's training dataset. We extractsyntactic and semantic identifiers unique to each program to train a classifierfor detecting code inclusion. In our experiments, we observe that TraWiC iscapable of detecting 83.87% of codes that were used to train an LLM. Incomparison, the prevalent clone detection tool NiCad is only capable ofdetecting 47.64%. In addition to its remarkable performance, TraWiC has lowresource overhead in contrast to pair-wise clone detection that is conductedduring the auditing process of tools like CodeWhisperer reference tracker,across thousands of code snippets.
{{< /details >}}

>**_2024-02-12_**

[**Game Agent Driven by Free-Form Text Command: Using LLM-based Code Generation and Behavior Branch**](http://arxiv.org/abs/2402.07442v1)

*Ray Ito, Junichiro Takahashi*

{{< details "abstract" >}} abstract: Several attempts have been made to implement text command control for gameagents. However, current technologies are limited to processing predefinedformat commands. This paper proposes a pioneering text command control systemfor a game agent that can understand natural language commands expressed infree-form. The proposed system uses a large language model (LLM) for codegeneration to interpret and transform natural language commands into behaviorbranch, a proposed knowledge expression based on behavior trees, whichfacilitates execution by the game agent. This study conducted empiricalvalidation within a game environment that simulates a Pok\'emon game andinvolved multiple participants. The results confirmed the system's ability tounderstand and carry out natural language commands, representing a noteworthyin the realm of real-time language interactive game agents.  Notice for the use of this material. The copyright of this material isretained by the Japanese Society for Artificial Intelligence (JSAI). Thismaterial is published here with the agreement of JSAI. Please be complied withCopyright Law of Japan if any users wish to reproduce, make derivative work,distribute or make available to the public any part or whole thereof. AllRights Reserved, Copyright (C) The Japanese Society for ArtificialIntelligence.
{{< /details >}}

[**Empowering Federated Learning for Massive Models with NVIDIA FLARE**](http://arxiv.org/abs/2402.07792v1)

*Holger R. Roth, Ziyue Xu, Yuan-Ting Hsieh, Adithya Renduchintala, Isaac Yang, Zhihong Zhang, Yuhong Wen, Sean Yang, Kevin Lu, Kristopher Kersten, Camir Ricketts, Daguang Xu, Chester Chen, Yan Cheng, Andrew Feng*

{{< details "abstract" >}} abstract: In the ever-evolving landscape of artificial intelligence (AI) and largelanguage models (LLMs), handling and leveraging data effectively has become acritical challenge. Most state-of-the-art machine learning algorithms aredata-centric. However, as the lifeblood of model performance, necessary datacannot always be centralized due to various factors such as privacy,regulation, geopolitics, copyright issues, and the sheer effort required tomove vast datasets. In this paper, we explore how federated learning enabled byNVIDIA FLARE can address these challenges with easy and scalable integrationcapabilities, enabling parameter-efficient and full supervised fine-tuning ofLLMs for natural language processing and biopharmaceutical applications toenhance their accuracy and robustness.
{{< /details >}}

[**Five ethical principles for generative AI in scientific research**](http://arxiv.org/abs/2401.15284v2)

*Zhicheng Lin*

{{< details "abstract" >}} abstract: Generative artificial intelligence tools like large language models arerapidly transforming academic research and real world applications. However,discussions on ethical guidelines for generative AI in science remainfragmented, underscoring the urgent need for consensus based standards. Thispaper offers an initial framework by developing analyses and mitigationstrategies across five key themes: understanding model limitations regardingtruthfulness and bias; respecting privacy, confidentiality, and copyright;avoiding plagiarism and policy violations when incorporating model output;ensuring applications provide overall benefit; and using AI transparently andreproducibly. Common scenarios are outlined to demonstrate potential ethicalviolations. We argue that global consensus coupled with professional trainingand reasonable enforcement are critical to promoting the benefits of AI whilesafeguarding research integrity.
{{< /details >}}

>**_2024-02-10_**

[**Data Contamination Quiz: A Tool to Detect and Estimate Contamination in Large Language Models**](http://arxiv.org/abs/2311.06233v5)

*Shahriar Golchin, Mihai Surdeanu*

{{< details "abstract" >}} abstract: We propose the Data Contamination Quiz (DCQ), a simple and effective approachto detect data contamination in large language models (LLMs) and estimate theamount of it. Specifically, we frame data contamination detection as a seriesof multiple-choice questions and devise a quiz format wherein three perturbedversions of each dataset instance are created. These changes only includeword-level perturbations. The generated perturbed versions, along with theoriginal instance, form the options in the DCQ, with an extra optionaccommodating the possibility that none of the provided choices is correct.Given that the only distinguishing signal among the choices is the exactwording relative to the original instance, an LLM, when tasked with identifyingthe original instance from the choices, gravitates towards the original one ifit has been exposed to it in its pre-training phase--a trait intrinsic to LLMs.Tested over several datasets with GPT-4/3.5, our findings--while fully lackingaccess to LLMs' pre-training data and internal parameters--suggest that DCQuncovers greater contamination levels compared to existing detection methodsand proficiently bypasses more safety filters, especially those set to avoidgenerating copyrighted contents.
{{< /details >}}

>**_2024-02-07_**

[**Human-Readable Fingerprint for Large Language Models**](http://arxiv.org/abs/2312.04828v2)

*Boyi Zeng, Chenghu Zhou, Xinbing Wang, Zhouhan Lin*

{{< details "abstract" >}} abstract: Protecting the copyright of large language models (LLMs) has become crucialdue to their resource-intensive training and accompanying carefully designedlicenses. However, identifying the original base model of an LLM is challengingdue to potential parameter alterations. In this study, we introduce ahuman-readable fingerprint for LLMs that uniquely identifies the base modelwithout exposing model parameters or interfering with training. We firstobserve that the vector direction of LLM parameters remains stable after themodel has converged during pretraining, showing negligible perturbationsthrough subsequent training steps, including continued pretraining, supervisedfine-tuning (SFT), and RLHF, which makes it a sufficient condition to identifythe base model. The necessity is validated by continuing to train an LLM withan extra term to drive away the model parameters' direction and the modelbecomes damaged. However, this direction is vulnerable to simple attacks likedimension permutation or matrix rotation, which significantly change it withoutaffecting performance. To address this, leveraging the Transformer structure,we systematically analyze potential attacks and define three invariant termsthat identify an LLM's base model. We make these invariant terms human-readableby mapping them to a Gaussian vector using a convolutional encoder and thenconverting it into a natural image with StyleGAN2. Our method generates a dogimage as an identity fingerprint for an LLM, where the dog's appearancestrongly indicates the LLM's base model. The fingerprint provides intuitiveinformation for qualitative discrimination, while the invariant terms can beemployed for quantitative and precise verification. Experimental results acrossvarious LLMs demonstrate the effectiveness of our method.
{{< /details >}}

>**_2024-01-28_**

[**Data-Free Generalized Zero-Shot Learning**](http://arxiv.org/abs/2401.15657v1)

*Bowen Tang, Long Yan, Jing Zhang, Qian Yu, Lu Sheng, Dong Xu*

{{< details "abstract" >}} abstract: Deep learning models have the ability to extract rich knowledge fromlarge-scale datasets. However, the sharing of data has become increasinglychallenging due to concerns regarding data copyright and privacy. Consequently,this hampers the effective transfer of knowledge from existing data to noveldownstream tasks and concepts. Zero-shot learning (ZSL) approaches aim torecognize new classes by transferring semantic knowledge learned from baseclasses. However, traditional generative ZSL methods often require access toreal images from base classes and rely on manually annotated attributes, whichpresents challenges in terms of data restrictions and model scalability. Tothis end, this paper tackles a challenging and practical problem dubbed asdata-free zero-shot learning (DFZSL), where only the CLIP-based base classesdata pre-trained classifier is available for zero-shot classification.Specifically, we propose a generic framework for DFZSL, which consists of threemain components. Firstly, to recover the virtual features of the base data, wemodel the CLIP features of base class images as samples from a von Mises-Fisher(vMF) distribution based on the pre-trained classifier. Secondly, we leveragethe text features of CLIP as low-cost semantic information and propose afeature-language prompt tuning (FLPT) method to further align the virtual imagefeatures and textual features. Thirdly, we train a conditional generative modelusing the well-aligned virtual image features and corresponding semantic textfeatures, enabling the generation of new classes features and achieve betterzero-shot generalization. Our framework has been evaluated on five commonlyused benchmarks for generalized ZSL, as well as 11 benchmarks for thebase-to-new ZSL. The results demonstrate the superiority and effectiveness ofour approach. Our code is available in https://github.com/ylong4/DFZSL
{{< /details >}}

>**_2024-01-23_**

[**A Survey of Text Watermarking in the Era of Large Language Models**](http://arxiv.org/abs/2312.07913v4)

*Aiwei Liu, Leyi Pan, Yijian Lu, Jingjing Li, Xuming Hu, Xi Zhang, Lijie Wen, Irwin King, Hui Xiong, Philip S. Yu*

{{< details "abstract" >}} abstract: Text watermarking algorithms play a crucial role in the copyright protectionof textual content, yet their capabilities and application scenarios have beenlimited historically. The recent developments in large language models (LLMs)have opened new opportunities for the advancement of text watermarkingtechniques. LLMs not only enhance the capabilities of text watermarkingalgorithms through their text understanding and generation abilities but alsonecessitate the use of text watermarking algorithms for their own copyrightprotection. This paper conducts a comprehensive survey of the current state oftext watermarking technology, covering four main aspects: (1) an overview andcomparison of different text watermarking techniques; (2) evaluation methodsfor text watermarking algorithms, including their success rates, impact on textquality, robustness, and unforgeability; (3) potential application scenariosfor text watermarking technology; (4) current challenges and future directionsfor development. This survey aims to provide researchers with a thoroughunderstanding of text watermarking technology, thereby promoting its furtheradvancement.
{{< /details >}}

>**_2024-01-18_**

[**Silent Guardian: Protecting Text from Malicious Exploitation by Large Language Models**](http://arxiv.org/abs/2312.09669v3)

*Jiawei Zhao, Kejiang Chen, Xiaojian Yuan, Yuang Qi, Weiming Zhang, Nenghai Yu*

{{< details "abstract" >}} abstract: The rapid development of large language models (LLMs) has yielded impressivesuccess in various downstream tasks. However, the vast potential and remarkablecapabilities of LLMs also raise new security and privacy concerns if they areexploited for nefarious purposes due to their open-endedness. For example, LLMsmay be used to plagiarize or imitate writing, thereby infringing the copyrightof the original content, or to create indiscriminate fake information based ona certain source text. In some cases, LLMs can even analyze text from theInternet to infer personal privacy. Unfortunately, previous text protectionresearch could not foresee the emergence of powerful LLMs, rendering it nolonger effective in this new context. To bridge this gap, we introduce SilentGuardian (SG), a text protection mechanism against LLMs, which allows LLMs torefuse to generate response when receiving protected text, preventing themalicious use of text from the source. Specifically, we first propose theconcept of Truncation Protection Examples (TPE). By carefully modifying thetext to be protected, TPE can induce LLMs to first sample the end token, thusdirectly terminating the interaction. In addition, to efficiently construct TPEin the discrete space of text data, we propose a novel optimization algorithmcalled Super Taliored Protection (STP), which is not only highly efficient butalso maintains the semantic consistency of the text during the optimizationprocess. The comprehensive experimental evaluation demonstrates that SG caneffectively protect the target text under various configurations and achievealmost 100% protection success rate in some cases. Notably, SG also exhibitsrelatively good transferability and robustness, making its application inpractical scenarios possible.
{{< /details >}}

>**_2024-01-07_**

[**The Stronger the Diffusion Model, the Easier the Backdoor: Data Poisoning to Induce Copyright Breaches Without Adjusting Finetuning Pipeline**](http://arxiv.org/abs/2401.04136v1)

*Haonan Wang, Qianli Shen, Yao Tong, Yang Zhang, Kenji Kawaguchi*

{{< details "abstract" >}} abstract: The commercialization of diffusion models, renowned for their ability togenerate high-quality images that are often indistinguishable from real ones,brings forth potential copyright concerns. Although attempts have been made toimpede unauthorized access to copyrighted material during training and tosubsequently prevent DMs from generating copyrighted images, the effectivenessof these solutions remains unverified. This study explores the vulnerabilitiesassociated with copyright protection in DMs by introducing a backdoor datapoisoning attack (SilentBadDiffusion) against text-to-image diffusion models.Our attack method operates without requiring access to or control over thediffusion model's training or fine-tuning processes; it merely involves theinsertion of poisoning data into the clean training dataset. This data,comprising poisoning images equipped with prompts, is generated by leveragingthe powerful capabilities of multimodal large language models and text-guidedimage inpainting techniques. Our experimental results and analysis confirm themethod's effectiveness. By integrating a minor portion ofnon-copyright-infringing stealthy poisoning data into the cleandataset-rendering it free from suspicion-we can prompt the finetuned diffusionmodels to produce copyrighted content when activated by specific triggerprompts. These findings underline potential pitfalls in the prevailingcopyright protection strategies and underscore the necessity for increasedscrutiny and preventative measures against the misuse of DMs.
{{< /details >}}

>**_2024-01-02_**

[**Towards Code Watermarking with Dual-Channel Transformations**](http://arxiv.org/abs/2309.00860v2)

*Borui Yang, Wei Li, Liyao Xiang, Bo Li*

{{< details "abstract" >}} abstract: The expansion of the open source community and the rise of large languagemodels have raised ethical and security concerns on the distribution of sourcecode, such as misconduct on copyrighted code, distributions without properlicenses, or misuse of the code for malicious purposes. Hence it is importantto track the ownership of source code, in which watermarking is a majortechnique. Yet, drastically different from natural languages, source codewatermarking requires far stricter and more complicated rules to ensure thereadability as well as the functionality of the source code. Hence we introduceSrcMarker, a watermarking system to unobtrusively encode ID bitstrings intosource code, without affecting the usage and semantics of the code. To thisend, SrcMarker performs transformations on an AST-based intermediaterepresentation that enables unified transformations across differentprogramming languages. The core of the system utilizes learning-based embeddingand extraction modules to select rule-based transformations for watermarking.In addition, a novel feature-approximation technique is designed to tackle theinherent non-differentiability of rule selection, thus seamlessly integratingthe rule-based transformations and learning-based networks into aninterconnected system to enable end-to-end training. Extensive experimentsdemonstrate the superiority of SrcMarker over existing methods in variouswatermarking requirements.
{{< /details >}}

>**_2024-01-01_**

[**Digger: Detecting Copyright Content Mis-usage in Large Language Model Training**](http://arxiv.org/abs/2401.00676v1)

*Haodong Li, Gelei Deng, Yi Liu, Kailong Wang, Yuekang Li, Tianwei Zhang, Yang Liu, Guoai Xu, Guosheng Xu, Haoyu Wang*

{{< details "abstract" >}} abstract: Pre-training, which utilizes extensive and varied datasets, is a criticalfactor in the success of Large Language Models (LLMs) across numerousapplications. However, the detailed makeup of these datasets is often notdisclosed, leading to concerns about data security and potential misuse. Thisis particularly relevant when copyrighted material, still under legalprotection, is used inappropriately, either intentionally or unintentionally,infringing on the rights of the authors.  In this paper, we introduce a detailed framework designed to detect andassess the presence of content from potentially copyrighted books within thetraining datasets of LLMs. This framework also provides a confidence estimationfor the likelihood of each content sample's inclusion. To validate ourapproach, we conduct a series of simulated experiments, the results of whichaffirm the framework's effectiveness in identifying and addressing instances ofcontent misuse in LLM training processes. Furthermore, we investigate thepresence of recognizable quotes from famous literary works within thesedatasets. The outcomes of our study have significant implications for ensuringthe ethical use of copyrighted materials in the development of LLMs,highlighting the need for more transparent and responsible data managementpractices in this field.
{{< /details >}}

>**_2023-12-31_**

[**Viz: A QLoRA-based Copyright Marketplace for Legally Compliant Generative AI**](http://arxiv.org/abs/2401.00503v1)

*Dipankar Sarkar*

{{< details "abstract" >}} abstract: This paper aims to introduce and analyze the Viz system in a comprehensiveway, a novel system architecture that integrates Quantized Low-Rank Adapters(QLoRA) to fine-tune large language models (LLM) within a legally compliant andresource efficient marketplace. Viz represents a significant contribution tothe field of artificial intelligence, particularly in addressing the challengesof computational efficiency, legal compliance, and economic sustainability inthe utilization and monetization of LLMs. The paper delineates the scholarlydiscourse and developments that have informed the creation of Viz, focusingprimarily on the advancements in LLM models, copyright issues in AI training(NYT case, 2023), and the evolution of model fine-tuning techniques,particularly low-rank adapters and quantized low-rank adapters, to create asustainable and economically compliant framework for LLM utilization. Theeconomic model it proposes benefits content creators, AI developers, andend-users, delineating a harmonious integration of technology, economy, andlaw, offering a comprehensive solution to the complex challenges of today's AIlandscape.
{{< /details >}}

>**_2023-12-21_**

[**Experimenting with Large Language Models and vector embeddings in NASA SciX**](http://arxiv.org/abs/2312.14211v1)

*Sergi Blanco-Cuaresma, Ioana Ciucă, Alberto Accomazzi, Michael J. Kurtz, Edwin A. Henneken, Kelly E. Lockhart, Felix Grezes, Thomas Allen, Golnaz Shapurian, Carolyn S. Grant, Donna M. Thompson, Timothy W. Hostetler, Matthew R. Templeton, Shinyi Chen, Jennifer Koch, Taylor Jacovich, Daniel Chivvis, Fernanda de Macedo Alves, Jean-Claude Paquin, Jennifer Bartlett, Mugdha Polimera, Stephanie Jarmak*

{{< details "abstract" >}} abstract: Open-source Large Language Models enable projects such as NASA SciX (i.e.,NASA ADS) to think out of the box and try alternative approaches forinformation retrieval and data augmentation, while respecting data copyrightand users' privacy. However, when large language models are directly promptedwith questions without any context, they are prone to hallucination. At NASASciX we have developed an experiment where we created semantic vectors for ourlarge collection of abstracts and full-text content, and we designed a promptsystem to ask questions using contextual chunks from our system. Based on anon-systematic human evaluation, the experiment shows a lower degree ofhallucination and better responses when using Retrieval Augmented Generation.Further exploration is required to design new features and data augmentationprocesses at NASA SciX that leverages this technology while respecting the highlevel of trust and quality that the project holds.
{{< /details >}}

>**_2023-12-18_**

[**Opportunities and Challenges of Applying Large Language Models in Building Energy Efficiency and Decarbonization Studies: An Exploratory Overview**](http://arxiv.org/abs/2312.11701v1)

*Liang Zhang, Zhelun Chen*

{{< details "abstract" >}} abstract: In recent years, the rapid advancement and impressive capabilities of LargeLanguage Models (LLMs) have been evident across various domains. This paperexplores the application, implications, and potential of LLMs in buildingenergy efficiency and decarbonization studies. The wide-ranging capabilities ofLLMs are examined in the context of the building energy field, includingintelligent control systems, code generation, data infrastructure, knowledgeextraction, and education. Despite the promising potential of LLMs, challengesincluding complex and expensive computation, data privacy, security andcopyright, complexity in fine-tuned LLMs, and self-consistency are discussed.The paper concludes with a call for future research focused on the enhancementof LLMs for domain-specific tasks, multi-modal LLMs, and collaborative researchbetween AI and energy experts.
{{< /details >}}

>**_2023-12-15_**

[**Privacy-Aware Document Visual Question Answering**](http://arxiv.org/abs/2312.10108v1)

*Rubèn Tito, Khanh Nguyen, Marlon Tobaben, Raouf Kerkouche, Mohamed Ali Souibgui, Kangsoo Jung, Lei Kang, Ernest Valveny, Antti Honkela, Mario Fritz, Dimosthenis Karatzas*

{{< details "abstract" >}} abstract: Document Visual Question Answering (DocVQA) is a fast growing branch ofdocument understanding. Despite the fact that documents contain sensitive orcopyrighted information, none of the current DocVQA methods offers strongprivacy guarantees.  In this work, we explore privacy in the domain of DocVQA for the first time.We highlight privacy issues in state of the art multi-modal LLM models used forDocVQA, and explore possible solutions.  Specifically, we focus on the invoice processing use case as a realistic,widely used scenario for document understanding, and propose a large scaleDocVQA dataset comprising invoice documents and associated questions andanswers. We employ a federated learning scheme, that reflects the real-lifedistribution of documents in different businesses, and we explore the use casewhere the ID of the invoice issuer is the sensitive information to beprotected.  We demonstrate that non-private models tend to memorise, behaviour that canlead to exposing private information. We then evaluate baseline trainingschemes employing federated learning and differential privacy in thismulti-modal scenario, where the sensitive information might be exposed throughany of the two input modalities: vision (document image) or language (OCRtokens).  Finally, we design an attack exploiting the memorisation effect of the model,and demonstrate its effectiveness in probing different DocVQA models.
{{< /details >}}

>**_2023-11-28_**

[**PromptCARE: Prompt Copyright Protection by Watermark Injection and Verification**](http://arxiv.org/abs/2308.02816v2)

*Hongwei Yao, Jian Lou, Kui Ren, Zhan Qin*

{{< details "abstract" >}} abstract: Large language models (LLMs) have witnessed a meteoric rise in popularityamong the general public users over the past few months, facilitating diversedownstream tasks with human-level accuracy and proficiency. Prompts play anessential role in this success, which efficiently adapt pre-trained LLMs totask-specific applications by simply prepending a sequence of tokens to thequery texts. However, designing and selecting an optimal prompt can be bothexpensive and demanding, leading to the emergence of Prompt-as-a-Serviceproviders who profit by providing well-designed prompts for authorized use.With the growing popularity of prompts and their indispensable role inLLM-based services, there is an urgent need to protect the copyright of promptsagainst unauthorized use.  In this paper, we propose PromptCARE, the first framework for promptcopyright protection through watermark injection and verification. Promptwatermarking presents unique challenges that render existing watermarkingtechniques developed for model and dataset copyright verification ineffective.PromptCARE overcomes these hurdles by proposing watermark injection andverification schemes tailor-made for prompts and NLP characteristics. Extensiveexperiments on six well-known benchmark datasets, using three prevalentpre-trained LLMs (BERT, RoBERTa, and Facebook OPT-1.3b), demonstrate theeffectiveness, harmlessness, robustness, and stealthiness of PromptCARE.
{{< /details >}}

>**_2023-11-23_**

[**MARBLE: Music Audio Representation Benchmark for Universal Evaluation**](http://arxiv.org/abs/2306.10548v4)

*Ruibin Yuan, Yinghao Ma, Yizhi Li, Ge Zhang, Xingran Chen, Hanzhi Yin, Le Zhuo, Yiqi Liu, Jiawen Huang, Zeyue Tian, Binyue Deng, Ningzhi Wang, Chenghua Lin, Emmanouil Benetos, Anton Ragni, Norbert Gyenge, Roger Dannenberg, Wenhu Chen, Gus Xia, Wei Xue, Si Liu, Shi Wang, Ruibo Liu, Yike Guo, Jie Fu*

{{< details "abstract" >}} abstract: In the era of extensive intersection between art and Artificial Intelligence(AI), such as image generation and fiction co-creation, AI for music remainsrelatively nascent, particularly in music understanding. This is evident in thelimited work on deep music representations, the scarcity of large-scaledatasets, and the absence of a universal and community-driven benchmark. Toaddress this issue, we introduce the Music Audio Representation Benchmark foruniversaL Evaluation, termed MARBLE. It aims to provide a benchmark for variousMusic Information Retrieval (MIR) tasks by defining a comprehensive taxonomywith four hierarchy levels, including acoustic, performance, score, andhigh-level description. We then establish a unified protocol based on 14 taskson 8 public-available datasets, providing a fair and standard assessment ofrepresentations of all open-sourced pre-trained models developed on musicrecordings as baselines. Besides, MARBLE offers an easy-to-use, extendable, andreproducible suite for the community, with a clear statement on copyrightissues on datasets. Results suggest recently proposed large-scale pre-trainedmusical language models perform the best in most tasks, with room for furtherimprovement. The leaderboard and toolkit repository are published athttps://marble-bm.shef.ac.uk to promote future music AI research.
{{< /details >}}

>**_2023-11-21_**

[**LyricWhiz: Robust Multilingual Zero-shot Lyrics Transcription by Whispering to ChatGPT**](http://arxiv.org/abs/2306.17103v3)

*Le Zhuo, Ruibin Yuan, Jiahao Pan, Yinghao Ma, Yizhi LI, Ge Zhang, Si Liu, Roger Dannenberg, Jie Fu, Chenghua Lin, Emmanouil Benetos, Wenhu Chen, Wei Xue, Yike Guo*

{{< details "abstract" >}} abstract: We introduce LyricWhiz, a robust, multilingual, and zero-shot automaticlyrics transcription method achieving state-of-the-art performance on variouslyrics transcription datasets, even in challenging genres such as rock andmetal. Our novel, training-free approach utilizes Whisper, a weakly supervisedrobust speech recognition model, and GPT-4, today's most performant chat-basedlarge language model. In the proposed method, Whisper functions as the "ear" bytranscribing the audio, while GPT-4 serves as the "brain," acting as anannotator with a strong performance for contextualized output selection andcorrection. Our experiments show that LyricWhiz significantly reduces WordError Rate compared to existing methods in English and can effectivelytranscribe lyrics across multiple languages. Furthermore, we use LyricWhiz tocreate the first publicly available, large-scale, multilingual lyricstranscription dataset with a CC-BY-NC-SA copyright license, based onMTG-Jamendo, and offer a human-annotated subset for noise level estimation andevaluation. We anticipate that our proposed method and dataset will advance thedevelopment of multilingual lyrics transcription, a challenging and emergingtask.
{{< /details >}}

>**_2023-11-17_**

[**FunctionMarker: Watermarking Language Datasets via Knowledge Injection**](http://arxiv.org/abs/2311.09535v2)

*Shuai Li, Kejiang Chen, Kunsheng Tang, Wen Huang, Jie Zhang, Weiming Zhang, Nenghai Yu*

{{< details "abstract" >}} abstract: Large Language Models (LLMs) have demonstrated superior performance invarious natural language processing tasks. Meanwhile, they require extensivetraining data, raising concerns related to dataset copyright protection.Backdoor-based watermarking is a viable approach to protect the copyright ofclassification datasets. However, these methods may introduce maliciousmisclassification behaviors into watermarked LLMs by attackers and also affectthe semantic information of the watermarked text. To address these issues, wepropose FunctionMarker, a novel copyright protection method for languagedatasets via knowledge injection. FunctionMarker enables LLMs to learn specificknowledge through fine-tuning on watermarked datasets, and we can extract theembedded watermark by obtaining the responses of LLMs to specificknowledge-related queries. Considering watermark capacity and stealthness, weselect customizable functions as specific knowledge for LLMs to learn and embedthe watermark into them. Moreover, FunctionMarker can embed multi-bitwatermarks while preserving the original semantic information, therebyincreasing the difficulty of adaptive attacks. We take mathematical functionsas an instance to evaluate the effectiveness of FunctionMarker, and experimentsshow that only 0.3% of watermarked text achieves a 90% watermark extractionaccuracy in most cases, validating our method's effectiveness.
{{< /details >}}

>**_2023-11-10_**

[**Watermarking Vision-Language Pre-trained Models for Multi-modal Embedding as a Service**](http://arxiv.org/abs/2311.05863v1)

*Yuanmin Tang, Jing Yu, Keke Gai, Xiangyan Qu, Yue Hu, Gang Xiong, Qi Wu*

{{< details "abstract" >}} abstract: Recent advances in vision-language pre-trained models (VLPs) havesignificantly increased visual understanding and cross-modal analysiscapabilities. Companies have emerged to provide multi-modal Embedding as aService (EaaS) based on VLPs (e.g., CLIP-based VLPs), which cost a large amountof training data and resources for high-performance service. However, existingstudies indicate that EaaS is vulnerable to model extraction attacks thatinduce great loss for the owners of VLPs. Protecting the intellectual propertyand commercial ownership of VLPs is increasingly crucial yet challenging. Amajor solution of watermarking model for EaaS implants a backdoor in the modelby inserting verifiable trigger embeddings into texts, but it is onlyapplicable for large language models and is unrealistic due to data and modelprivacy. In this paper, we propose a safe and robust backdoor-based embeddingwatermarking method for VLPs called VLPMarker. VLPMarker utilizes embeddingorthogonal transformation to effectively inject triggers into the VLPs withoutinterfering with the model parameters, which achieves high-quality copyrightverification and minimal impact on model performance. To enhance the watermarkrobustness, we further propose a collaborative copyright verification strategybased on both backdoor trigger and embedding distribution, enhancing resilienceagainst various attacks. We increase the watermark practicality via anout-of-distribution trigger selection approach, removing access to the modeltraining data and thus making it possible for many real-world scenarios. Ourextensive experiments on various datasets indicate that the proposedwatermarking approach is effective and safe for verifying the copyright of VLPsfor multi-modal EaaS and robust against model extraction attacks. Our code isavailable at https://github.com/Pter61/vlpmarker.
{{< /details >}}

>**_2023-10-24_**

[**SoK: Memorization in General-Purpose Large Language Models**](http://arxiv.org/abs/2310.18362v1)

*Valentin Hartmann, Anshuman Suri, Vincent Bindschaedler, David Evans, Shruti Tople, Robert West*

{{< details "abstract" >}} abstract: Large Language Models (LLMs) are advancing at a remarkable pace, with myriadapplications under development. Unlike most earlier machine learning models,they are no longer built for one specific application but are designed to excelin a wide range of tasks. A major part of this success is due to their hugetraining datasets and the unprecedented number of model parameters, which allowthem to memorize large amounts of information contained in the training data.This memorization goes beyond mere language, and encompasses information onlypresent in a few documents. This is often desirable since it is necessary forperforming tasks such as question answering, and therefore an important part oflearning, but also brings a whole array of issues, from privacy and security tocopyright and beyond. LLMs can memorize short secrets in the training data, butcan also memorize concepts like facts or writing styles that can be expressedin text in many different ways. We propose a taxonomy for memorization in LLMsthat covers verbatim text, facts, ideas and algorithms, writing styles,distributional properties, and alignment goals. We describe the implications ofeach type of memorization - both positive and negative - for model performance,privacy, security and confidentiality, copyright, and auditing, and ways todetect and prevent memorization. We further highlight the challenges that arisefrom the predominant way of defining memorization with respect to modelbehavior instead of model weights, due to LLM-specific phenomena such asreasoning capabilities or differences between decoding algorithms. Throughoutthe paper, we describe potential risks and opportunities arising frommemorization in LLMs that we hope will motivate new research directions.
{{< /details >}}

>**_2023-10-23_**

[**H2O Open Ecosystem for State-of-the-art Large Language Models**](http://arxiv.org/abs/2310.13012v2)

*Arno Candel, Jon McKinney, Philipp Singer, Pascal Pfeiffer, Maximilian Jeblick, Chun Ming Lee, Marcos V. Conde*

{{< details "abstract" >}} abstract: Large Language Models (LLMs) represent a revolution in AI. However, they alsopose many significant risks, such as the presence of biased, private,copyrighted or harmful text. For this reason we need open, transparent and safesolutions. We introduce a complete open-source ecosystem for developing andtesting LLMs. The goal of this project is to boost open alternatives toclosed-source approaches. We release h2oGPT, a family of fine-tuned LLMs ofdiverse sizes. We also introduce H2O LLM Studio, a framework and no-code GUIdesigned for efficient fine-tuning, evaluation, and deployment of LLMs usingthe most recent state-of-the-art techniques. Our code and models are fullyopen-source. We believe this work helps to boost AI development and make itmore accessible, efficient and trustworthy. The demo is available at:https://gpt.h2o.ai/
{{< /details >}}

[**Did the Neurons Read your Book? Document-level Membership Inference for Large Language Models**](http://arxiv.org/abs/2310.15007v1)

*Matthieu Meeus, Shubham Jain, Marek Rei, Yves-Alexandre de Montjoye*

{{< details "abstract" >}} abstract: With large language models (LLMs) poised to become embedded in our dailylives, questions are starting to be raised about the dataset(s) they learnedfrom. These questions range from potential bias or misinformation LLMs couldretain from their training data to questions of copyright and fair use ofhuman-generated text. However, while these questions emerge, developers of therecent state-of-the-art LLMs become increasingly reluctant to disclose detailson their training corpus. We here introduce the task of document-levelmembership inference for real-world LLMs, i.e. inferring whether the LLM hasseen a given document during training or not. First, we propose a procedure forthe development and evaluation of document-level membership inference for LLMsby leveraging commonly used data sources for training and the model releasedate. We then propose a practical, black-box method to predict document-levelmembership and instantiate it on OpenLLaMA-7B with both books and academicpapers. We show our methodology to perform very well, reaching an impressiveAUC of 0.856 for books and 0.678 for papers. We then show our approach tooutperform the sentence-level membership inference attacks used in the privacyliterature for the document-level membership task. We finally evaluate whethersmaller models might be less sensitive to document-level inference and showOpenLLaMA-3B to be approximately as sensitive as OpenLLaMA-7B to our approach.Taken together, our results show that accurate document-level membership can beinferred for LLMs, increasing the transparency of technology poised to changeour lives.
{{< /details >}}

>**_2023-10-20_**

[**Copyright Violations and Large Language Models**](http://arxiv.org/abs/2310.13771v1)

*Antonia Karamolegkou, Jiaang Li, Li Zhou, Anders Søgaard*

{{< details "abstract" >}} abstract: Language models may memorize more than just facts, including entire chunks oftexts seen during training. Fair use exemptions to copyright laws typicallyallow for limited use of copyrighted material without permission from thecopyright holder, but typically for extraction of information from copyrightedmaterials, rather than {\em verbatim} reproduction. This work explores theissue of copyright violations and large language models through the lens ofverbatim memorization, focusing on possible redistribution of copyrighted text.We present experiments with a range of language models over a collection ofpopular books and coding problems, providing a conservative characterization ofthe extent to which language models can redistribute these materials. Overall,this research highlights the need for further examination and the potentialimpact on future developments in natural language processing to ensureadherence to copyright regulations. Code is at\url{https://github.com/coastalcph/CopyrightLLMs}.
{{< /details >}}

>**_2023-10-10_**

[**Watermarking Classification Dataset for Copyright Protection**](http://arxiv.org/abs/2305.13257v3)

*Yixin Liu, Hongsheng Hu, Xun Chen, Xuyun Zhang, Lichao Sun*

{{< details "abstract" >}} abstract: Substantial research works have shown that deep models, e.g., pre-trainedmodels, on the large corpus can learn universal language representations, whichare beneficial for downstream NLP tasks. However, these powerful models arealso vulnerable to various privacy attacks, while much sensitive informationexists in the training dataset. The attacker can easily steal sensitiveinformation from public models, e.g., individuals' email addresses and phonenumbers. In an attempt to address these issues, particularly the unauthorizeduse of private data, we introduce a novel watermarking technique via abackdoor-based membership inference approach named TextMarker, which cansafeguard diverse forms of private information embedded in the training textdata. Specifically, TextMarker only requires data owners to mark a small numberof samples for data copyright protection under the black-box access assumptionto the target model. Through extensive evaluation, we demonstrate theeffectiveness of TextMarker on various real-world datasets, e.g., marking only0.1% of the training dataset is practically sufficient for effective membershipinference with negligible effect on model utility. We also discuss potentialcountermeasures and show that TextMarker is stealthy enough to bypass them.
{{< /details >}}

>**_2023-10-04_**

[**Who's Harry Potter? Approximate Unlearning in LLMs**](http://arxiv.org/abs/2310.02238v2)

*Ronen Eldan, Mark Russinovich*

{{< details "abstract" >}} abstract: Large language models (LLMs) are trained on massive internet corpora thatoften contain copyrighted content. This poses legal and ethical challenges forthe developers and users of these models, as well as the original authors andpublishers. In this paper, we propose a novel technique for unlearning a subsetof the training data from a LLM, without having to retrain it from scratch.  We evaluate our technique on the task of unlearning the Harry Potter booksfrom the Llama2-7b model (a generative language model recently open-sourced byMeta). While the model took over 184K GPU-hours to pretrain, we show that inabout 1 GPU hour of finetuning, we effectively erase the model's ability togenerate or recall Harry Potter-related content, while its performance oncommon benchmarks (such as Winogrande, Hellaswag, arc, boolq and piqa) remainsalmost unaffected. We make our fine-tuned model publicly available onHuggingFace for community evaluation. To the best of our knowledge, this is thefirst paper to present an effective technique for unlearning in generativelanguage models.  Our technique consists of three main components: First, we use a reinforcedmodel that is further trained on the target data to identify the tokens thatare most related to the unlearning target, by comparing its logits with thoseof a baseline model. Second, we replace idiosyncratic expressions in the targetdata with generic counterparts, and leverage the model's own predictions togenerate alternative labels for every token. These labels aim to approximatethe next-token predictions of a model that has not been trained on the targetdata. Third, we finetune the model on these alternative labels, whicheffectively erases the original text from the model's memory whenever it isprompted with its context.
{{< /details >}}

>**_2023-09-05_**

[**Large-scale Language Model Rescoring on Long-form Data**](http://arxiv.org/abs/2306.08133v2)

*Tongzhou Chen, Cyril Allauzen, Yinghui Huang, Daniel Park, David Rybach, W. Ronny Huang, Rodrigo Cabrera, Kartik Audhkhasi, Bhuvana Ramabhadran, Pedro J. Moreno, Michael Riley*

{{< details "abstract" >}} abstract: In this work, we study the impact of Large-scale Language Models (LLM) onAutomated Speech Recognition (ASR) of YouTube videos, which we use as a sourcefor long-form ASR. We demonstrate up to 8\% relative reduction in Word ErrorEate (WER) on US English (en-us) and code-switched Indian English (en-in)long-form ASR test sets and a reduction of up to 30\% relative on Salient TermError Rate (STER) over a strong first-pass baseline that uses a maximum-entropybased language model. Improved lattice processing that results in a latticewith a proper (non-tree) digraph topology and carrying context from the 1-besthypothesis of the previous segment(s) results in significant wins in rescoringwith LLMs. We also find that the gains in performance from the combination ofLLMs trained on vast quantities of available data (such as C4) and conventionalneural LMs is additive and significantly outperforms a strong first-passbaseline with a maximum entropy LM.  Copyright 2023 IEEE. Personal use of this material is permitted. Permissionfrom IEEE must be obtained for all other uses, in any current or future media,including reprinting/republishing this material for advertising or promotionalpurposes, creating new collective works, for resale or redistribution toservers or lists, or reuse of any copyrighted component of this work in otherworks.
{{< /details >}}

>**_2023-08-23_**

[**How to Protect Copyright Data in Optimization of Large Language Models?**](http://arxiv.org/abs/2308.12247v1)

*Timothy Chu, Zhao Song, Chiwun Yang*

{{< details "abstract" >}} abstract: Large language models (LLMs) and generative AI have played a transformativerole in computer research and applications. Controversy has arisen as towhether these models output copyrighted data, which can occur if the data themodels are trained on is copyrighted. LLMs are built on the transformer neuralnetwork architecture, which in turn relies on a mathematical computation calledAttention that uses the softmax function.  In this paper, we show that large language model training and optimizationcan be seen as a softmax regression problem. We then establish a method ofefficiently performing softmax regression, in a way that prevents theregression function from generating copyright data. This establishes atheoretical method of training large language models in a way that avoidsgenerating copyright data.
{{< /details >}}

>**_2023-08-19_**

[**DUAW: Data-free Universal Adversarial Watermark against Stable Diffusion Customization**](http://arxiv.org/abs/2308.09889v1)

*Xiaoyu Ye, Hao Huang, Jiaqi An, Yongtao Wang*

{{< details "abstract" >}} abstract: Stable Diffusion (SD) customization approaches enable users to personalize SDmodel outputs, greatly enhancing the flexibility and diversity of AI art.However, they also allow individuals to plagiarize specific styles or subjectsfrom copyrighted images, which raises significant concerns about potentialcopyright infringement. To address this issue, we propose an invisibledata-free universal adversarial watermark (DUAW), aiming to protect a myriad ofcopyrighted images from different customization approaches across variousversions of SD models. First, DUAW is designed to disrupt the variationalautoencoder during SD customization. Second, DUAW operates in a data-freecontext, where it is trained on synthetic images produced by a Large LanguageModel (LLM) and a pretrained SD model. This approach circumvents the necessityof directly handling copyrighted images, thereby preserving theirconfidentiality. Once crafted, DUAW can be imperceptibly integrated intomassive copyrighted images, serving as a protective measure by inducingsignificant distortions in the images generated by customized SD models.Experimental results demonstrate that DUAW can effectively distort the outputsof fine-tuned SD models, rendering them discernible to both human observers anda simple classifier.
{{< /details >}}

>**_2023-06-18_**

[**Should ChatGPT and Bard Share Revenue with Their Data Providers? A New Business Model for the AI Era**](http://arxiv.org/abs/2305.02555v2)

*Dong Zhang*

{{< details "abstract" >}} abstract: With various AI tools such as ChatGPT becoming increasingly popular, we areentering a true AI era. We can foresee that exceptional AI tools will soon reapconsiderable profits. A crucial question arise: should AI tools share revenuewith their training data providers in additional to traditional stakeholdersand shareholders? The answer is Yes. Large AI tools, such as large languagemodels, always require more and better quality data to continuously improve,but current copyright laws limit their access to various types of data. Sharingrevenue between AI tools and their data providers could transform the currenthostile zero-sum game relationship between AI tools and a majority ofcopyrighted data owners into a collaborative and mutually beneficial one, whichis necessary to facilitate the development of a virtuous cycle among AI tools,their users and data providers that drives forward AI technology and builds ahealthy AI ecosystem. However, current revenue-sharing business models do notwork for AI tools in the forthcoming AI era, since the most widely used metricsfor website-based traffic and action, such as clicks, will be replaced by newmetrics such as prompts and cost per prompt for generative AI tools. Acompletely new revenue-sharing business model, which must be almost independentof AI tools and be easily explained to data providers, needs to establish aprompt-based scoring system to measure data engagement of each data provider.This paper systematically discusses how to build such a scoring system for alldata providers for AI tools based on classification and content similaritymodels, and outlines the requirements for AI tools or third parties to buildit. Sharing revenue with data providers using such a scoring system wouldencourage more data owners to participate in the revenue-sharing program. Thiswill be a utilitarian AI era where all parties benefit.
{{< /details >}}

>**_2023-06-16_**

[**h2oGPT: Democratizing Large Language Models**](http://arxiv.org/abs/2306.08161v2)

*Arno Candel, Jon McKinney, Philipp Singer, Pascal Pfeiffer, Maximilian Jeblick, Prithvi Prabhu, Jeff Gambera, Mark Landry, Shivam Bansal, Ryan Chesler, Chun Ming Lee, Marcos V. Conde, Pasha Stetsenko, Olivier Grellier, SriSatish Ambati*

{{< details "abstract" >}} abstract: Applications built on top of Large Language Models (LLMs) such as GPT-4represent a revolution in AI due to their human-level capabilities in naturallanguage processing. However, they also pose many significant risks such as thepresence of biased, private, or harmful text, and the unauthorized inclusion ofcopyrighted material.  We introduce h2oGPT, a suite of open-source code repositories for thecreation and use of LLMs based on Generative Pretrained Transformers (GPTs).The goal of this project is to create the world's best truly open-sourcealternative to closed-source approaches. In collaboration with and as part ofthe incredible and unstoppable open-source community, we open-source severalfine-tuned h2oGPT models from 7 to 40 Billion parameters, ready for commercialuse under fully permissive Apache 2.0 licenses. Included in our release is100\% private document search using natural language.  Open-source language models help boost AI development and make it moreaccessible and trustworthy. They lower entry hurdles, allowing people andgroups to tailor these models to their needs. This openness increasesinnovation, transparency, and fairness. An open-source strategy is needed toshare AI benefits fairly, and H2O.ai will continue to democratize AI and LLMs.
{{< /details >}}

>**_2023-06-15_**

[**Matching Pairs: Attributing Fine-Tuned Models to their Pre-Trained Large Language Models**](http://arxiv.org/abs/2306.09308v1)

*Myles Foley, Ambrish Rawat, Taesung Lee, Yufang Hou, Gabriele Picco, Giulio Zizzo*

{{< details "abstract" >}} abstract: The wide applicability and adaptability of generative large language models(LLMs) has enabled their rapid adoption. While the pre-trained models canperform many tasks, such models are often fine-tuned to improve theirperformance on various downstream applications. However, this leads to issuesover violation of model licenses, model theft, and copyright infringement.Moreover, recent advances show that generative technology is capable ofproducing harmful content which exacerbates the problems of accountabilitywithin model supply chains. Thus, we need a method to investigate how a modelwas trained or a piece of text was generated and what their pre-trained basemodel was. In this paper we take the first step to address this open problem bytracing back the origin of a given fine-tuned LLM to its correspondingpre-trained base model. We consider different knowledge levels and attributionstrategies, and find that we can correctly trace back 8 out of the 10 finetuned models with our best method.
{{< /details >}}

>**_2023-06-09_**

[**Robust Multi-bit Natural Language Watermarking through Invariant Features**](http://arxiv.org/abs/2305.01904v2)

*KiYoon Yoo, Wonhyuk Ahn, Jiho Jang, Nojun Kwak*

{{< details "abstract" >}} abstract: Recent years have witnessed a proliferation of valuable original naturallanguage contents found in subscription-based media outlets, web novelplatforms, and outputs of large language models. However, these contents aresusceptible to illegal piracy and potential misuse without proper securitymeasures. This calls for a secure watermarking system to guarantee copyrightprotection through leakage tracing or ownership identification. To effectivelycombat piracy and protect copyrights, a multi-bit watermarking framework shouldbe able to embed adequate bits of information and extract the watermarks in arobust manner despite possible corruption. In this work, we explore ways toadvance both payload and robustness by following a well-known proposition fromimage watermarking and identify features in natural language that are invariantto minor corruption. Through a systematic analysis of the possible sources oferrors, we further propose a corruption-resistant infill model. Our full methodimproves upon the previous work on robustness by +16.8% point on average onfour datasets, three corruption types, and two corruption ratios. Codeavailable at https://github.com/bangawayoo/nlp-watermarking.
{{< /details >}}

>**_2023-06-02_**

[**Are You Copying My Model? Protecting the Copyright of Large Language Models for EaaS via Backdoor Watermark**](http://arxiv.org/abs/2305.10036v3)

*Wenjun Peng, Jingwei Yi, Fangzhao Wu, Shangxi Wu, Bin Zhu, Lingjuan Lyu, Binxing Jiao, Tong Xu, Guangzhong Sun, Xing Xie*

{{< details "abstract" >}} abstract: Large language models (LLMs) have demonstrated powerful capabilities in bothtext understanding and generation. Companies have begun to offer Embedding as aService (EaaS) based on these LLMs, which can benefit various natural languageprocessing (NLP) tasks for customers. However, previous studies have shown thatEaaS is vulnerable to model extraction attacks, which can cause significantlosses for the owners of LLMs, as training these models is extremely expensive.To protect the copyright of LLMs for EaaS, we propose an Embedding Watermarkmethod called EmbMarker that implants backdoors on embeddings. Our methodselects a group of moderate-frequency words from a general text corpus to forma trigger set, then selects a target embedding as the watermark, and inserts itinto the embeddings of texts containing trigger words as the backdoor. Theweight of insertion is proportional to the number of trigger words included inthe text. This allows the watermark backdoor to be effectively transferred toEaaS-stealer's model for copyright verification while minimizing the adverseimpact on the original embeddings' utility. Our extensive experiments onvarious datasets show that our method can effectively protect the copyright ofEaaS models without compromising service quality.
{{< /details >}}

>**_2023-05-31_**

[**Synthetic Pre-Training Tasks for Neural Machine Translation**](http://arxiv.org/abs/2212.09864v2)

*Zexue He, Graeme Blackwood, Rameswar Panda, Julian McAuley, Rogerio Feris*

{{< details "abstract" >}} abstract: Pre-training models with large crawled corpora can lead to issues such astoxicity and bias, as well as copyright and privacy concerns. A promising wayof alleviating such concerns is to conduct pre-training with synthetic tasksand data, since no real-world information is ingested by the model. Our goal inthis paper is to understand the factors that contribute to the effectiveness ofpre-training models when using synthetic resources, particularly in the contextof neural machine translation. We propose several novel approaches topre-training translation models that involve different levels of lexical andstructural knowledge, including: 1) generating obfuscated data from a largeparallel corpus 2) concatenating phrase pairs extracted from a smallword-aligned corpus, and 3) generating synthetic parallel data without realhuman language corpora. Our experiments on multiple language pairs reveal thatpre-training benefits can be realized even with high levels of obfuscation orpurely synthetic parallel data. We hope the findings from our comprehensiveempirical analysis will shed light on understanding what matters for NMTpre-training, as well as pave the way for the development of more efficient andless toxic models.
{{< /details >}}

>**_2023-05-08_**

[**Differentially Private Attention Computation**](http://arxiv.org/abs/2305.04701v1)

*Yeqi Gao, Zhao Song, Xin Yang*

{{< details "abstract" >}} abstract: Large language models (LLMs) have had a profound impact on numerous aspectsof daily life including natural language processing, content generation,research methodologies and so on. However, one crucial issue concerning theinference results of large language models is security and privacy. In manyscenarios, the results generated by LLMs could possibly leak many confidentialor copyright information. A recent beautiful and breakthrough work [Vyas,Kakade and Barak 2023] focus on such privacy issue of the LLMs from theoreticalperspective. It is well-known that computing the attention matrix is one of themajor task during the LLMs computation. Thus, how to give a provable privatelyguarantees of computing the attention matrix is an important researchdirection.  Previous work [Alman and Song 2023, Brand, Song and Zhou 2023] have proposedprovable tight result for fast computation of attention without consideringprivacy concerns. One natural mathematical formulation to quantity the privacyin theoretical computer science graduate school textbook is differentialprivacy. Inspired by [Vyas, Kakade and Barak 2023], in this work, we provide aprovable result for showing how to differentially private approximate theattention matrix.  From technique perspective, our result replies on a pioneering work in thearea of differential privacy by [Alabi, Kothari, Tankala, Venkat and Zhang2022].
{{< /details >}}

>**_2023-04-06_**

[**Whose Text Is It Anyway? Exploring BigCode, Intellectual Property, and Ethics**](http://arxiv.org/abs/2304.02839v1)

*Madiha Zahrah Choksi, David Goedicke*

{{< details "abstract" >}} abstract: Intelligent or generative writing tools rely on large language models thatrecognize, summarize, translate, and predict content. This position paperprobes the copyright interests of open data sets used to train large languagemodels (LLMs). Our paper asks, how do LLMs trained on open data sets circumventthe copyright interests of the used data? We start by defining softwarecopyright and tracing its history. We rely on GitHub Copilot as a modern casestudy challenging software copyright. Our conclusion outlines obstacles thatgenerative writing assistants create for copyright, and offers a practical roadmap for copyright analysis for developers, software law experts, and generalusers to consider in the context of intelligent LLM-powered writing tools.
{{< /details >}}

>**_2023-03-28_**

[**Synthetically generated text for supervised text analysis**](http://arxiv.org/abs/2303.16028v1)

*Andrew Halterman*

{{< details "abstract" >}} abstract: Supervised text models are a valuable tool for political scientists butpresent several obstacles to their use, including the expense of hand-labelingdocuments, the difficulty of retrieving rare relevant documents for annotation,and copyright and privacy concerns involved in sharing annotated documents.This article proposes a partial solution to these three issues, in the form ofcontrolled generation of synthetic text with large language models. I provide aconceptual overview of text generation, guidance on when researchers shouldprefer different techniques for generating synthetic text, a discussion ofethics, and a simple technique for improving the quality of synthetic text. Idemonstrate the usefulness of synthetic text with three applications:generating synthetic tweets describing the fighting in Ukraine, synthetic newsarticles describing specified political events for training an event detectionsystem, and a multilingual corpus of populist manifesto statements for traininga sentence-level populism classifier.
{{< /details >}}

>**_2022-11-29_**

[**Pile of Law: Learning Responsible Data Filtering from the Law and a 256GB Open-Source Legal Dataset**](http://arxiv.org/abs/2207.00220v2)

*Peter Henderson, Mark S. Krass, Lucia Zheng, Neel Guha, Christopher D. Manning, Dan Jurafsky, Daniel E. Ho*

{{< details "abstract" >}} abstract: One concern with the rise of large language models lies with their potentialfor significant harm, particularly from pretraining on biased, obscene,copyrighted, and private information. Emerging ethical approaches haveattempted to filter pretraining material, but such approaches have been ad hocand failed to take context into account. We offer an approach to filteringgrounded in law, which has directly addressed the tradeoffs in filteringmaterial. First, we gather and make available the Pile of Law, a 256GB (andgrowing) dataset of open-source English-language legal and administrative data,covering court opinions, contracts, administrative rules, and legislativerecords. Pretraining on the Pile of Law may help with legal tasks that have thepromise to improve access to justice. Second, we distill the legal norms thatgovernments have developed to constrain the inclusion of toxic or privatecontent into actionable lessons for researchers and discuss how our datasetreflects these norms. Third, we show how the Pile of Law offers researchers theopportunity to learn such filtering rules directly from the data, providing anexciting new research direction in model-based processing.
{{< /details >}}

>**_2022-08-03_**

[**A Feature-space Multimodal Data Augmentation Technique for Text-video Retrieval**](http://arxiv.org/abs/2208.02080v1)

*Alex Falcon, Giuseppe Serra, Oswald Lanz*

{{< details "abstract" >}} abstract: Every hour, huge amounts of visual contents are posted on social media anduser-generated content platforms. To find relevant videos by means of a naturallanguage query, text-video retrieval methods have received increased attentionover the past few years. Data augmentation techniques were introduced toincrease the performance on unseen test examples by creating new trainingsamples with the application of semantics-preserving techniques, such as colorspace or geometric transformations on images. Yet, these techniques are usuallyapplied on raw data, leading to more resource-demanding solutions and alsorequiring the shareability of the raw data, which may not always be true, e.g.copyright issues with clips from movies or TV series. To address thisshortcoming, we propose a multimodal data augmentation technique which works inthe feature space and creates new videos and captions by mixing semanticallysimilar samples. We experiment our solution on a large scale public dataset,EPIC-Kitchens-100, and achieve considerable improvements over a baselinemethod, improved state-of-the-art performance, while at the same timeperforming multiple ablation studies. We release code and pretrained models onGithub at https://github.com/aranciokov/FSMMDA_VideoRetrieval.
{{< /details >}}

>**_2022-05-29_**

[**CPED: A Large-Scale Chinese Personalized and Emotional Dialogue Dataset for Conversational AI**](http://arxiv.org/abs/2205.14727v1)

*Yirong Chen, Weiquan Fan, Xiaofen Xing, Jianxin Pang, Minlie Huang, Wenjing Han, Qianfeng Tie, Xiangmin Xu*

{{< details "abstract" >}} abstract: Human language expression is based on the subjective construal of thesituation instead of the objective truth conditions, which means that speakers'personalities and emotions after cognitive processing have an importantinfluence on conversation. However, most existing datasets for conversationalAI ignore human personalities and emotions, or only consider part of them. It'sdifficult for dialogue systems to understand speakers' personalities andemotions although large-scale pre-training language models have been widelyused. In order to consider both personalities and emotions in the process ofconversation generation, we propose CPED, a large-scale Chinese personalizedand emotional dialogue dataset, which consists of multi-source knowledgerelated to empathy and personal characteristic. These knowledge covers gender,Big Five personality traits, 13 emotions, 19 dialogue acts and 10 scenes. CPEDcontains more than 12K dialogues of 392 speakers from 40 TV shows. We releasethe textual dataset with audio features and video features according to thecopyright claims, privacy issues, terms of service of video platforms. Weprovide detailed description of the CPED construction process and introducethree tasks for conversational AI, including personality recognition, emotionrecognition in conversations as well as personalized and emotional conversationgeneration. Finally, we provide baseline systems for these tasks and considerthe function of speakers' personalities and emotions on conversation. Ourmotivation is to propose a dataset to be widely adopted by the NLP community asa new open benchmark for conversational AI research. The full dataset isavailable at https://github.com/scutcyr/CPED.
{{< /details >}}

>**_2021-11-02_**

[**KLUE: Korean Language Understanding Evaluation**](http://arxiv.org/abs/2105.09680v4)

*Sungjoon Park, Jihyung Moon, Sungdong Kim, Won Ik Cho, Jiyoon Han, Jangwon Park, Chisung Song, Junseong Kim, Yongsook Song, Taehwan Oh, Joohong Lee, Juhyun Oh, Sungwon Lyu, Younghoon Jeong, Inkwon Lee, Sangwoo Seo, Dongjun Lee, Hyunwoo Kim, Myeonghwa Lee, Seongbo Jang, Seungwon Do, Sunkyoung Kim, Kyungtae Lim, Jongwon Lee, Kyumin Park, Jamin Shin, Seonghyun Kim, Lucy Park, Alice Oh, Jung-Woo Ha, Kyunghyun Cho*

{{< details "abstract" >}} abstract: We introduce Korean Language Understanding Evaluation (KLUE) benchmark. KLUEis a collection of 8 Korean natural language understanding (NLU) tasks,including Topic Classification, SemanticTextual Similarity, Natural LanguageInference, Named Entity Recognition, Relation Extraction, Dependency Parsing,Machine Reading Comprehension, and Dialogue State Tracking. We build all of thetasks from scratch from diverse source corpora while respecting copyrights, toensure accessibility for anyone without any restrictions. With ethicalconsiderations in mind, we carefully design annotation protocols. Along withthe benchmark tasks and data, we provide suitable evaluation metrics andfine-tuning recipes for pretrained language models for each task. Wefurthermore release the pretrained language models (PLM), KLUE-BERT andKLUE-RoBERTa, to help reproducing baseline models on KLUE and therebyfacilitate future research. We make a few interesting observations from thepreliminary experiments using the proposed KLUE benchmark suite, alreadydemonstrating the usefulness of this new benchmark suite. First, we findKLUE-RoBERTa-large outperforms other baselines, including multilingual PLMs andexisting open-source Korean PLMs. Second, we see minimal degradation inperformance even when we replace personally identifiable information from thepretraining corpus, suggesting that privacy and NLU capability are not at oddswith each other. Lastly, we find that using BPE tokenization in combinationwith morpheme-level pre-tokenization is effective in tasks involvingmorpheme-level tagging, detection and generation. In addition to acceleratingKorean NLP research, our comprehensive documentation on creating KLUE willfacilitate creating similar resources for other languages in the future. KLUEis available at https://klue-benchmark.com.
{{< /details >}}

>**_2021-05-11_**

[**Addressing "Documentation Debt" in Machine Learning Research: A Retrospective Datasheet for BookCorpus**](http://arxiv.org/abs/2105.05241v1)

*Jack Bandy, Nicholas Vincent*

{{< details "abstract" >}} abstract: Recent literature has underscored the importance of dataset documentationwork for machine learning, and part of this work involves addressing"documentation debt" for datasets that have been used widely but documentedsparsely. This paper aims to help address documentation debt for BookCorpus, apopular text dataset for training large language models. Notably, researchershave used BookCorpus to train OpenAI's GPT-N models and Google's BERT models,even though little to no documentation exists about the dataset's motivation,composition, collection process, etc. We offer a preliminary datasheet thatprovides key context and information about BookCorpus, highlighting severalnotable deficiencies. In particular, we find evidence that (1) BookCorpuslikely violates copyright restrictions for many books, (2) BookCorpus containsthousands of duplicated books, and (3) BookCorpus exhibits significant skews ingenre representation. We also find hints of other potential deficiencies thatcall for future research, including problematic content, potential skews inreligious representation, and lopsided author contributions. While more workremains, this initial effort to provide a datasheet for BookCorpus adds togrowing literature that urges more careful and systematic documentation formachine learning datasets.
{{< /details >}}