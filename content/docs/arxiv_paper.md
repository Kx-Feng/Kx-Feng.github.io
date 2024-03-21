---
weight: 10
bookFlatSection: true
title: "Arxiv Paper"
---
 <!--more-->
# Arxiv Papers: LLM meets Copyright

>**_2024-03-18_**

[**TPLLM: A Traffic Prediction Framework Based on Pretrained Large Language Models**](http://arxiv.org/abs/2403.02221v2)

*Yilong Ren, Yue Chen, Shuai Liu, Boyue Wang, Haiyang Yu, Zhiyong Cui*

{{< details "abstract" >}} abstract: Traffic prediction constitutes a pivotal facet within the purview ofIntelligent Transportation Systems (ITS), and the attainment of highly precisepredictions holds profound significance for efficacious traffic management. Theprecision of prevailing deep learning-driven traffic prediction modelstypically sees an upward trend with a rise in the volume of training data.However, the procurement of comprehensive spatiotemporal datasets for trafficis often fraught with challenges, primarily stemming from the substantial costsassociated with data collection and retention. Consequently, developing a modelthat can achieve accurate predictions and good generalization ability in areaswith limited historical traffic data is a challenging problem. It is noteworthythat the rapidly advancing pretrained Large Language Models (LLMs) of recentyears have demonstrated exceptional proficiency in cross-modality knowledgetransfer and few-shot learning. Recognizing the sequential nature of trafficdata, similar to language, we introduce TPLLM, a novel traffic predictionframework leveraging LLMs. In this framework, we construct a sequence embeddinglayer based on Convolutional Neural Networks (CNNs) and a graph embedding layerbased on Graph Convolutional Networks (GCNs) to extract sequence features andspatial features, respectively. These are subsequently integrated to forminputs that are suitable for LLMs. A Low-Rank Adaptation (LoRA) fine-tuningapproach is applied to TPLLM, thereby facilitating efficient learning andminimizing computational demands. Experiments on two real-world datasetsdemonstrate that TPLLM exhibits commendable performance in both full-sample andfew-shot prediction scenarios, effectively supporting the development of ITS inregions with scarce historical traffic data.
{{< /details >}}

[**Automated data processing and feature engineering for deep learning and big data applications: a survey**](http://arxiv.org/abs/2403.11395v1)

*Alhassan Mumuni amd Fuseini Mumuni*

{{< details "abstract" >}} abstract: Modern approach to artificial intelligence (AI) aims to design algorithmsthat learn directly from data. This approach has achieved impressive resultsand has contributed significantly to the progress of AI, particularly in thesphere of supervised deep learning. It has also simplified the design ofmachine learning systems as the learning process is highly automated. However,not all data processing tasks in conventional deep learning pipelines have beenautomated. In most cases data has to be manually collected, preprocessed andfurther extended through data augmentation before they can be effective fortraining. Recently, special techniques for automating these tasks have emerged.The automation of data processing tasks is driven by the need to utilize largevolumes of complex, heterogeneous data for machine learning and big dataapplications. Today, end-to-end automated data processing systems based onautomated machine learning (AutoML) techniques are capable of taking raw dataand transforming them into useful features for Big Data tasks by automating allintermediate processing stages. In this work, we present a thorough review ofapproaches for automating data processing tasks in deep learning pipelines,including automated data preprocessing--e.g., data cleaning, labeling, missingdata imputation, and categorical data encoding--as well as data augmentation(including synthetic data generation using generative AI methods) and featureengineering--specifically, automated feature extraction, feature constructionand feature selection. In addition to automating specific data processingtasks, we discuss the use of AutoML methods and tools to simultaneouslyoptimize all stages of the machine learning pipeline.
{{< /details >}}

>**_2024-03-17_**

[**ProgGen: Generating Named Entity Recognition Datasets Step-by-step with Self-Reflexive Large Language Models**](http://arxiv.org/abs/2403.11103v1)

*Yuzhao Heng, Chunyuan Deng, Yitong Li, Yue Yu, Yinghao Li, Rongzhi Zhang, Chao Zhang*

{{< details "abstract" >}} abstract: Although Large Language Models (LLMs) exhibit remarkable adaptability acrossdomains, these models often fall short in structured knowledge extraction taskssuch as named entity recognition (NER). This paper explores an innovative,cost-efficient strategy to harness LLMs with modest NER capabilities forproducing superior NER datasets. Our approach diverges from the basicclass-conditional prompts by instructing LLMs to self-reflect on the specificdomain, thereby generating domain-relevant attributes (such as category andemotions for movie reviews), which are utilized for creating attribute-richtraining data. Furthermore, we preemptively generate entity terms and thendevelop NER context data around these entities, effectively bypassing the LLMs'challenges with complex structures. Our experiments across both general andniche domains reveal significant performance enhancements over conventionaldata generation methods while being more cost-effective than existingalternatives.
{{< /details >}}

[**Forging the Forger: An Attempt to Improve Authorship Verification via Data Augmentation**](http://arxiv.org/abs/2403.11265v1)

*Silvia Corbara, Alejandro Moreo*

{{< details "abstract" >}} abstract: Authorship Verification (AV) is a text classification task concerned withinferring whether a candidate text has been written by one specific author orby someone else. It has been shown that many AV systems are vulnerable toadversarial attacks, where a malicious author actively tries to fool theclassifier by either concealing their writing style, or by imitating the styleof another author. In this paper, we investigate the potential benefits ofaugmenting the classifier training set with (negative) synthetic examples.These synthetic examples are generated to imitate the style of the author ofinterest. We analyze the improvements in classifier prediction that thisaugmentation brings to bear in the task of AV in an adversarial setting. Inparticular, we experiment with three different generator architectures (onebased on Recurrent Neural Networks, another based on small-scale transformers,and another based on the popular GPT model) and with two training strategies(one inspired by standard Language Models, and another inspired by WassersteinGenerative Adversarial Networks). We evaluate our hypothesis on five datasets(three of which have been specifically collected to represent an adversarialsetting) and using two learning algorithms for the AV classifier (SupportVector Machines and Convolutional Neural Networks). This experimentation hasyielded negative results, revealing that, although our methodology proveseffective in many adversarial settings, its benefits are too sporadic for apragmatical application.
{{< /details >}}

>**_2024-03-16_**

[**VLLaVO: Mitigating Visual Gap through LLMs**](http://arxiv.org/abs/2401.03253v2)

*Shuhao Chen, Yulong Zhang, Weisen Jiang, Jiangang Lu, Yu Zhang*

{{< details "abstract" >}} abstract: Recent advances achieved by deep learning models rely on the independent andidentically distributed assumption, hindering their applications in real-worldscenarios with domain shifts. To tackle this issue, cross-domain learning aimsat extracting domain-invariant knowledge to reduce the domain shift betweentraining and testing data. However, in visual cross-domain learning,traditional methods concentrate solely on the image modality, disregarding thepotential benefits of incorporating the text modality. In this work, we proposeVLLaVO, combining Vision language models and Large Language models as Visualcross-dOmain learners. VLLaVO uses vision-language models to convert imagesinto detailed textual descriptions. A large language model is then finetuned ontextual descriptions of the source/target domain generated by a designedinstruction template. Extensive experimental results under domaingeneralization and unsupervised domain adaptation settings demonstrate theeffectiveness of the proposed method.
{{< /details >}}

>**_2024-03-15_**

[**Generative AI in EU Law: Liability, Privacy, Intellectual Property, and Cybersecurity**](http://arxiv.org/abs/2401.07348v4)

*Claudio Novelli, Federico Casolari, Philipp Hacker, Giorgio Spedicato, Luciano Floridi*

{{< details "abstract" >}} abstract: The advent of Generative AI, particularly through Large Language Models(LLMs) like ChatGPT and its successors, marks a paradigm shift in the AIlandscape. Advanced LLMs exhibit multimodality, handling diverse data formats,thereby broadening their application scope. However, the complexity andemergent autonomy of these models introduce challenges in predictability andlegal compliance. This paper delves into the legal and regulatory implicationsof Generative AI and LLMs in the European Union context, analyzing aspects ofliability, privacy, intellectual property, and cybersecurity. It criticallyexamines the adequacy of the existing and proposed EU legislation, includingthe Artificial Intelligence Act (AIA) draft, in addressing the uniquechallenges posed by Generative AI in general and LLMs in particular. The paperidentifies potential gaps and shortcomings in the legislative framework andproposes recommendations to ensure the safe and compliant deployment ofgenerative models, ensuring they align with the EU's evolving digital landscapeand legal standards.
{{< /details >}}

[**Lost in Overlap: Exploring Watermark Collision in LLMs**](http://arxiv.org/abs/2403.10020v1)

*Yiyang Luo, Ke Lin, Chao Gu*

{{< details "abstract" >}} abstract: The proliferation of large language models (LLMs) in generating contentraises concerns about text copyright. Watermarking methods, particularlylogit-based approaches, embed imperceptible identifiers into text to addressthese challenges. However, the widespread use of watermarking across diverseLLMs has led to an inevitable issue known as watermark collision during commontasks like question answering and paraphrasing. This study focuses on dualwatermark collisions, where two watermarks are present simultaneously in thesame text. The research demonstrates that watermark collision poses a threat todetection performance for detectors of both upstream and downstream watermarkalgorithms.
{{< /details >}}

>**_2024-03-12_**

[**Motifs, Phrases, and Beyond: The Modelling of Structure in Symbolic Music Generation**](http://arxiv.org/abs/2403.07995v1)

*Keshav Bhandari, Simon Colton*

{{< details "abstract" >}} abstract: Modelling musical structure is vital yet challenging for artificialintelligence systems that generate symbolic music compositions. This literaturereview dissects the evolution of techniques for incorporating coherentstructure, from symbolic approaches to foundational and transformative deeplearning methods that harness the power of computation and data across a widevariety of training paradigms. In the later stages, we review an emergingtechnique which we refer to as "sub-task decomposition" that involvesdecomposing music generation into separate high-level structural planning andcontent creation stages. Such systems incorporate some form of musicalknowledge or neuro-symbolic methods by extracting melodic skeletons orstructural templates to guide the generation. Progress is evident in capturingmotifs and repetitions across all three eras reviewed, yet modelling thenuanced development of themes across extended compositions in the style ofhuman composers remains difficult. We outline several key future directions torealize the synergistic benefits of combining approaches from all erasexamined.
{{< /details >}}

>**_2024-03-11_**

[**Beyond Finite Data: Towards Data-free Out-of-distribution Generalization via Extrapolation**](http://arxiv.org/abs/2403.05523v2)

*Yijiang Li, Sucheng Ren, Weipeng Deng, Yuzhi Xu, Ying Gao, Edith Ngai, Haohan Wang*

{{< details "abstract" >}} abstract: Out-of-distribution (OOD) generalization is a favorable yet challengingproperty for deep neural networks. The core challenges lie in the limitedavailability of source domains that help models learn an invariantrepresentation from the spurious features. Various domain augmentation havebeen proposed but largely rely on interpolating existing domains and frequentlyface difficulties in creating truly "novel" domains. Humans, on the other hand,can easily extrapolate novel domains, thus, an intriguing question arises: Howcan neural networks extrapolate like humans and achieve OOD generalization?  We introduce a novel approach to domain extrapolation that leveragesreasoning ability and the extensive knowledge encapsulated within largelanguage models (LLMs) to synthesize entirely new domains. Starting with theclass of interest, we query the LLMs to extract relevant knowledge for thesenovel domains. We then bridge the gap between the text-centric knowledgederived from LLMs and the pixel input space of the model using text-to-imagegeneration techniques. By augmenting the training set of domain generalizationdatasets with high-fidelity, photo-realistic images of these new domains, weachieve significant improvements over all existing methods, as demonstrated inboth single and multi-domain generalization across various benchmarks.  With the ability to extrapolate any domains for any class, our method has thepotential to learn a generalized model for any task without any data. Toillustrate, we put forth a much more difficult setting termed, data-free domaingeneralization, that aims to learn a generalized model in the absence of anycollected data. Our empirical findings support the above argument and ourmethods exhibit commendable performance in this setting, even surpassing thesupervised setting by approximately 1-2\% on datasets such as VLCS.
{{< /details >}}

[**Authorship and the Politics and Ethics of LLM Watermarks**](http://arxiv.org/abs/2403.06593v1)

*Tim Räz*

{{< details "abstract" >}} abstract: Recently, watermarking schemes for large language models (LLMs) have beenproposed to distinguish text generated by machines and by humans. The presentpaper explores philosophical, political, and ethical ramifications ofimplementing and using watermarking schemes. A definition of authorship thatincludes both machines (LLMs) and humans is proposed to serve as a backdrop. Itis argued that private watermarks may provide private companies with sweepingrights to determine authorship, which is incompatible with traditionalstandards of authorship determination. Then, possible ramifications of theso-called entropy dependence of watermarking mechanisms are explored. It isargued that entropy may vary for different, socially salient groups. This couldlead to group dependent rates at which machine generated text is detected.Specifically, groups more interested in low entropy text may face the challengethat it is harder to detect machine generated text that is of interest to them.
{{< /details >}}

>**_2024-03-10_**

[**Generalizing Graph Neural Networks on Out-Of-Distribution Graphs**](http://arxiv.org/abs/2111.10657v4)

*Shaohua Fan, Xiao Wang, Chuan Shi, Peng Cui, Bai Wang*

{{< details "abstract" >}} abstract: Graph Neural Networks (GNNs) are proposed without considering the agnosticdistribution shifts between training and testing graphs, inducing thedegeneration of the generalization ability of GNNs on Out-Of-Distribution (OOD)settings. The fundamental reason for such degeneration is that most GNNs aredeveloped based on the I.I.D hypothesis. In such a setting, GNNs tend toexploit subtle statistical correlations existing in the training set forpredictions, even though it is a spurious correlation. However, such spuriouscorrelations may change in testing environments, leading to the failure ofGNNs. Therefore, eliminating the impact of spurious correlations is crucial forstable GNNs. To this end, we propose a general causal representation framework,called StableGNN. The main idea is to extract high-level representations fromgraph data first and resort to the distinguishing ability of causal inferenceto help the model get rid of spurious correlations. Particularly, we exploit agraph pooling layer to extract subgraph-based representations as high-levelrepresentations. Furthermore, we propose a causal variable distinguishingregularizer to correct the biased training distribution. Hence, GNNs wouldconcentrate more on the stable correlations. Extensive experiments on bothsynthetic and real-world OOD graph datasets well verify the effectiveness,flexibility and interpretability of the proposed framework.
{{< /details >}}

[**FedPIT: Towards Privacy-preserving and Few-shot Federated Instruction Tuning**](http://arxiv.org/abs/2403.06131v1)

*Zhuo Zhang, Jingyuan Zhang, Jintao Huang, Lizhen Qu, Hongzhi Zhang, Zenglin Xu*

{{< details "abstract" >}} abstract: Instruction tuning has proven essential for enhancing the performance oflarge language models (LLMs) in generating human-aligned responses. However,collecting diverse, high-quality instruction data for tuning poses challenges,particularly in privacy-sensitive domains. Federated instruction tuning (FedIT)has emerged as a solution, leveraging federated learning from multiple dataowners while preserving privacy. Yet, it faces challenges due to limitedinstruction data and vulnerabilities to training data extraction attacks. Toaddress these issues, we propose a novel federated algorithm, FedPIT, whichutilizes LLMs' in-context learning capability to self-generate task-specificsynthetic data for training autonomously. Our method employs parameter-isolatedtraining to maintain global parameters trained on synthetic data and localparameters trained on augmented local data, effectively thwarting dataextraction attacks. Extensive experiments on real-world medical datademonstrate the effectiveness of FedPIT in improving federated few-shotperformance while preserving privacy and robustness against data heterogeneity.
{{< /details >}}

>**_2024-03-08_**

[**Be Careful What You Smooth For: Label Smoothing Can Be a Privacy Shield but Also a Catalyst for Model Inversion Attacks**](http://arxiv.org/abs/2310.06549v4)

*Lukas Struppek, Dominik Hintersdorf, Kristian Kersting*

{{< details "abstract" >}} abstract: Label smoothing -- using softened labels instead of hard ones -- is a widelyadopted regularization method for deep learning, showing diverse benefits suchas enhanced generalization and calibration. Its implications for preservingmodel privacy, however, have remained unexplored. To fill this gap, weinvestigate the impact of label smoothing on model inversion attacks (MIAs),which aim to generate class-representative samples by exploiting the knowledgeencoded in a classifier, thereby inferring sensitive information about itstraining data. Through extensive analyses, we uncover that traditional labelsmoothing fosters MIAs, thereby increasing a model's privacy leakage. Evenmore, we reveal that smoothing with negative factors counters this trend,impeding the extraction of class-related information and leading to privacypreservation, beating state-of-the-art defenses. This establishes a practicaland powerful novel way for enhancing model resilience against MIAs.
{{< /details >}}

[**CLIP-Gaze: Towards General Gaze Estimation via Visual-Linguistic Model**](http://arxiv.org/abs/2403.05124v1)

*Pengwei Yin, Guanzhong Zeng, Jingjing Wang, Di Xie*

{{< details "abstract" >}} abstract: Gaze estimation methods often experience significant performance degradationwhen evaluated across different domains, due to the domain gap between thetesting and training data. Existing methods try to address this issue usingvarious domain generalization approaches, but with little success because ofthe limited diversity of gaze datasets, such as appearance, wearable, and imagequality. To overcome these limitations, we propose a novel framework calledCLIP-Gaze that utilizes a pre-trained vision-language model to leverage itstransferable knowledge. Our framework is the first to leverage thevision-and-language cross-modality approach for gaze estimation task.Specifically, we extract gaze-relevant feature by pushing it away fromgaze-irrelevant features which can be flexibly constructed via languagedescriptions. To learn more suitable prompts, we propose a personalized contextoptimization method for text prompt tuning. Furthermore, we utilize therelationship among gaze samples to refine the distribution of gaze-relevantfeatures, thereby improving the generalization capability of the gazeestimation model. Extensive experiments demonstrate the excellent performanceof CLIP-Gaze over existing methods on four cross-domain evaluations.
{{< /details >}}

>**_2024-03-06_**

[**K-Link: Knowledge-Link Graph from LLMs for Enhanced Representation Learning in Multivariate Time-Series Data**](http://arxiv.org/abs/2403.03645v1)

*Yucheng Wang, Ruibing Jin, Min Wu, Xiaoli Li, Lihua Xie, Zhenghua Chen*

{{< details "abstract" >}} abstract: Sourced from various sensors and organized chronologically, MultivariateTime-Series (MTS) data involves crucial spatial-temporal dependencies, e.g.,correlations among sensors. To capture these dependencies, Graph NeuralNetworks (GNNs) have emerged as powerful tools, yet their effectiveness isrestricted by the quality of graph construction from MTS data. Typically,existing approaches construct graphs solely from MTS signals, which mayintroduce bias due to a small training dataset and may not accurately representunderlying dependencies. To address this challenge, we propose a novelframework named K-Link, leveraging Large Language Models (LLMs) to encodeextensive general knowledge and thereby providing effective solutions to reducethe bias. Leveraging the knowledge embedded in LLMs, such as physicalprinciples, we extract a \textit{Knowledge-Link graph}, capturing vast semanticknowledge of sensors and the linkage of the sensor-level knowledge. To harnessthe potential of the knowledge-link graph in enhancing the graph derived fromMTS data, we propose a graph alignment module, facilitating the transfer ofsemantic knowledge within the knowledge-link graph into the MTS-derived graph.By doing so, we can improve the graph quality, ensuring effectiverepresentation learning with GNNs for MTS data. Extensive experimentsdemonstrate the efficacy of our approach for superior performance acrossvarious MTS-related downstream tasks.
{{< /details >}}

>**_2024-03-05_**

[**False Claims against Model Ownership Resolution**](http://arxiv.org/abs/2304.06607v6)

*Jian Liu, Rui Zhang, Sebastian Szyller, Kui Ren, N. Asokan*

{{< details "abstract" >}} abstract: Deep neural network (DNN) models are valuable intellectual property of modelowners, constituting a competitive advantage. Therefore, it is crucial todevelop techniques to protect against model theft. Model ownership resolution(MOR) is a class of techniques that can deter model theft. A MOR scheme enablesan accuser to assert an ownership claim for a suspect model by presentingevidence, such as a watermark or fingerprint, to show that the suspect modelwas stolen or derived from a source model owned by the accuser. Most of theexisting MOR schemes prioritize robustness against malicious suspects, ensuringthat the accuser will win if the suspect model is indeed a stolen model.  In this paper, we show that common MOR schemes in the literature arevulnerable to a different, equally important but insufficiently explored,robustness concern: a malicious accuser. We show how malicious accusers cansuccessfully make false claims against independent suspect models that were notstolen. Our core idea is that a malicious accuser can deviate (withoutdetection) from the specified MOR process by finding (transferable) adversarialexamples that successfully serve as evidence against independent suspectmodels. To this end, we first generalize the procedures of common MOR schemesand show that, under this generalization, defending against false claims is aschallenging as preventing (transferable) adversarial examples. Via systematicempirical evaluation, we show that our false claim attacks always succeed inthe MOR schemes that follow our generalization, including in a real-worldmodel: Amazon's Rekognition API.
{{< /details >}}

[**SATBA: An Invisible Backdoor Attack Based On Spatial Attention**](http://arxiv.org/abs/2302.13056v3)

*Huasong Zhou, Xiaowei Xu, Xiaodong Wang, Leon Bevan Bullock*

{{< details "abstract" >}} abstract: Backdoor attack has emerged as a novel and concerning threat to AI security.These attacks involve the training of Deep Neural Network (DNN) on datasetsthat contain hidden trigger patterns. Although the poisoned model behavesnormally on benign samples, it exhibits abnormal behavior on samples containingthe trigger pattern. However, most existing backdoor attacks suffer from twosignificant drawbacks: their trigger patterns are visible and easy to detect bybackdoor defense or even human inspection, and their injection process resultsin the loss of natural sample features and trigger patterns, thereby reducingthe attack success rate and model accuracy. In this paper, we propose a novelbackdoor attack named SATBA that overcomes these limitations using spatialattention and an U-net based model. The attack process begins by using spatialattention to extract meaningful data features and generate trigger patternsassociated with clean images. Then, an U-shaped model is used to embed thesetrigger patterns into the original data without causing noticeable featureloss. We evaluate our attack on three prominent image classification DNN acrossthree standard datasets. The results demonstrate that SATBA achieves highattack success rate while maintaining robustness against backdoor defenses.Furthermore, we conduct extensive image similarity experiments to emphasize thestealthiness of our attack strategy. Overall, SATBA presents a promisingapproach to backdoor attack, addressing the shortcomings of previous methodsand showcasing its effectiveness in evading detection and maintaining highattack success rate.
{{< /details >}}

[**Improving Android Malware Detection Through Data Augmentation Using Wasserstein Generative Adversarial Networks**](http://arxiv.org/abs/2403.00890v2)

*Kawana Stalin, Mikias Berhanu Mekoya*

{{< details "abstract" >}} abstract: Generative Adversarial Networks (GANs) have demonstrated their versatilityacross various applications, including data augmentation and malware detection.This research explores the effectiveness of utilizing GAN-generated data totrain a model for the detection of Android malware. Given the considerablestorage requirements of Android applications, the study proposes a method tosynthetically represent data using GANs, thereby reducing storage demands. Theproposed methodology involves creating image representations of featuresextracted from an existing dataset. A GAN model is then employed to generate amore extensive dataset consisting of realistic synthetic grayscale images.Subsequently, this synthetic dataset is utilized to train a ConvolutionalNeural Network (CNN) designed to identify previously unseen Android malwareapplications. The study includes a comparative analysis of the CNN'sperformance when trained on real images versus synthetic images generated bythe GAN. Furthermore, the research explores variations in performance betweenthe Wasserstein Generative Adversarial Network (WGAN) and the DeepConvolutional Generative Adversarial Network (DCGAN). The investigation extendsto studying the impact of image size and malware obfuscation on theclassification model's effectiveness. The data augmentation approachimplemented in this study resulted in a notable performance enhancement of theclassification model, ranging from 1.5% to 7%, depending on the dataset. Thehighest achieved F1 score reached 0.975.  Keywords--Generative Adversarial Networks, Android Malware, DataAugmentation, Wasserstein Generative Adversarial Network
{{< /details >}}

>**_2024-03-02_**

[**Knowledge Sanitization of Large Language Models**](http://arxiv.org/abs/2309.11852v2)

*Yoichi Ishibashi, Hidetoshi Shimodaira*

{{< details "abstract" >}} abstract: We explore a knowledge sanitization approach to mitigate the privacy concernsassociated with large language models (LLMs). LLMs trained on a large corpus ofWeb data can memorize and potentially reveal sensitive or confidentialinformation, raising critical security concerns. Our technique efficientlyfine-tunes these models using the Low-Rank Adaptation (LoRA) method, promptingthem to generate harmless responses such as ``I don't know'' when queried aboutspecific information. Experimental results in a closed-book question-answeringtask show that our straightforward method not only minimizes particularknowledge leakage but also preserves the overall performance of LLMs. These twoadvantages strengthen the defense against extraction attacks and reduces theemission of harmful content such as hallucinations.
{{< /details >}}

>**_2024-02-29_**

[**PRSA: Prompt Reverse Stealing Attacks against Large Language Models**](http://arxiv.org/abs/2402.19200v1)

*Yong Yang, Xuhong Zhang, Yi Jiang, Xi Chen, Haoyu Wang, Shouling Ji, Zonghui Wang*

{{< details "abstract" >}} abstract: Prompt, recognized as crucial intellectual property, enables large languagemodels (LLMs) to perform specific tasks without the need of fine-tuning,underscoring their escalating importance. With the rise of prompt-basedservices, such as prompt marketplaces and LLM applications, providers oftendisplay prompts' capabilities through input-output examples to attract users.However, this paradigm raises a pivotal security concern: does the exposure ofinput-output pairs pose the risk of potential prompt leakage, infringing on theintellectual property rights of the developers? To our knowledge, this problemstill has not been comprehensively explored yet. To remedy this gap, in thispaper, we perform the first in depth exploration and propose a novel attackframework for reverse-stealing prompts against commercial LLMs, namely PRSA.The main idea of PRSA is that by analyzing the critical features of theinput-output pairs, we mimic and gradually infer (steal) the target prompts. Indetail, PRSA mainly consists of two key phases: prompt mutation and promptpruning. In the mutation phase, we propose a prompt attention algorithm basedon differential feedback to capture these critical features for effectivelyinferring the target prompts. In the prompt pruning phase, we identify and maskthe words dependent on specific inputs, enabling the prompts to accommodatediverse inputs for generalization. Through extensive evaluation, we verify thatPRSA poses a severe threat in real world scenarios. We have reported thesefindings to prompt service providers and actively collaborate with them to takeprotective measures for prompt copyright.
{{< /details >}}

[**An Unforgeable Publicly Verifiable Watermark for Large Language Models**](http://arxiv.org/abs/2307.16230v5)

*Aiwei Liu, Leyi Pan, Xuming Hu, Shu'ang Li, Lijie Wen, Irwin King, Philip S. Yu*

{{< details "abstract" >}} abstract: Recently, text watermarking algorithms for large language models (LLMs) havebeen proposed to mitigate the potential harms of text generated by LLMs,including fake news and copyright issues. However, current watermark detectionalgorithms require the secret key used in the watermark generation process,making them susceptible to security breaches and counterfeiting during publicdetection. To address this limitation, we propose an unforgeable publiclyverifiable watermark algorithm that uses two different neural networks forwatermark generation and detection, instead of using the same key at bothstages. Meanwhile, the token embedding parameters are shared between thegeneration and detection networks, which makes the detection network achieve ahigh accuracy very efficiently. Experiments demonstrate that our algorithmattains high detection accuracy and computational efficiency through neuralnetworks with a minimized number of parameters. Subsequent analysis confirmsthe high complexity involved in forging the watermark from the detectionnetwork. Our code and data are available at\href{https://github.com/THU-BPM/unforgeable_watermark}{https://github.com/THU-BPM/unforgeable\_watermark}.
{{< /details >}}

>**_2024-02-26_**

[**AttackGNN: Red-Teaming GNNs in Hardware Security Using Reinforcement Learning**](http://arxiv.org/abs/2402.13946v2)

*Vasudev Gohil, Satwik Patnaik, Dileep Kalathil, Jeyavijayan Rajendran*

{{< details "abstract" >}} abstract: Machine learning has shown great promise in addressing several criticalhardware security problems. In particular, researchers have developed novelgraph neural network (GNN)-based techniques for detecting intellectual property(IP) piracy, detecting hardware Trojans (HTs), and reverse engineeringcircuits, to name a few. These techniques have demonstrated outstandingaccuracy and have received much attention in the community. However, sincethese techniques are used for security applications, it is imperative toevaluate them thoroughly and ensure they are robust and do not compromise thesecurity of integrated circuits.  In this work, we propose AttackGNN, the first red-team attack on GNN-basedtechniques in hardware security. To this end, we devise a novel reinforcementlearning (RL) agent that generates adversarial examples, i.e., circuits,against the GNN-based techniques. We overcome three challenges related toeffectiveness, scalability, and generality to devise a potent RL agent. Wetarget five GNN-based techniques for four crucial classes of problems inhardware security: IP piracy, detecting/localizing HTs, reverse engineering,and hardware obfuscation. Through our approach, we craft circuits that fool allGNNs considered in this work. For instance, to evade IP piracy detection, wegenerate adversarial pirated circuits that fool the GNN-based defense intoclassifying our crafted circuits as not pirated. For attacking HT localizationGNN, our attack generates HT-infested circuits that fool the defense on alltested circuits. We obtain a similar 100% success rate against GNNs for allclasses of problems.
{{< /details >}}

[**Investigating Deep Watermark Security: An Adversarial Transferability Perspective**](http://arxiv.org/abs/2402.16397v1)

*Biqing Qi, Junqi Gao, Yiang Luo, Jianxing Liu, Ligang Wu, Bowen Zhou*

{{< details "abstract" >}} abstract: The rise of generative neural networks has triggered an increased demand forintellectual property (IP) protection in generated content. Deep watermarkingtechniques, recognized for their flexibility in IP protection, have garneredsignificant attention. However, the surge in adversarial transferable attacksposes unprecedented challenges to the security of deep watermarkingtechniques-an area currently lacking systematic investigation. This study fillsthis gap by introducing two effective transferable attackers to assess thevulnerability of deep watermarks against erasure and tampering risks.Specifically, we initially define the concept of local sample density,utilizing it to deduce theorems on the consistency of model outputs. Upondiscovering that perturbing samples towards high sample density regions (HSDR)of the target class enhances targeted adversarial transferability, we proposethe Easy Sample Selection (ESS) mechanism and the Easy Sample Matching Attack(ESMA) method. Additionally, we propose the Bottleneck Enhanced Mixup (BEM)that integrates information bottleneck theory to reduce the generator'sdependence on irrelevant noise. Experiments show a significant enhancement inthe success rate of targeted transfer attacks for both ESMA and BEM-ESMAmethods. We further conduct a comprehensive evaluation using ESMA and BEM-ESMAas measurements, considering model architecture and watermark encoding length,and achieve some impressive findings.
{{< /details >}}

[**Privacy-Preserved Neural Graph Databases**](http://arxiv.org/abs/2312.15591v4)

*Qi Hu, Haoran Li, Jiaxin Bai, Zihao Wang, Yangqiu Song*

{{< details "abstract" >}} abstract: In the era of large language models (LLMs), efficient and accurate dataretrieval has become increasingly crucial for the use of domain-specific orprivate data in the retrieval augmented generation (RAG). Neural graphdatabases (NGDBs) have emerged as a powerful paradigm that combines thestrengths of graph databases (GDBs) and neural networks to enable efficientstorage, retrieval, and analysis of graph-structured data which can beadaptively trained with LLMs. The usage of neural embedding storage and Complexneural logical Query Answering (CQA) provides NGDBs with generalizationability. When the graph is incomplete, by extracting latent patterns andrepresentations, neural graph databases can fill gaps in the graph structure,revealing hidden relationships and enabling accurate query answering.Nevertheless, this capability comes with inherent trade-offs, as it introducesadditional privacy risks to the domain-specific or private databases. Maliciousattackers can infer more sensitive information in the database usingwell-designed queries such as from the answer sets of where Turing Awardwinners born before 1950 and after 1940 lived, the living places of TuringAward winner Hinton are probably exposed, although the living places may havebeen deleted in the training stage due to the privacy concerns. In this work,we propose a privacy-preserved neural graph database (P-NGDB) framework toalleviate the risks of privacy leakage in NGDBs. We introduce adversarialtraining techniques in the training stage to enforce the NGDBs to generateindistinguishable answers when queried with private information, enhancing thedifficulty of inferring sensitive information through combinations of multipleinnocuous queries.
{{< /details >}}

>**_2024-02-23_**

[**Who Wrote this Code? Watermarking for Code Generation**](http://arxiv.org/abs/2305.15060v3)

*Taehyun Lee, Seokhee Hong, Jaewoo Ahn, Ilgee Hong, Hwaran Lee, Sangdoo Yun, Jamin Shin, Gunhee Kim*

{{< details "abstract" >}} abstract: With the remarkable generation performance of large language models, ethicaland legal concerns about using them have been raised, such as plagiarism andcopyright issues. For such concerns, several approaches to watermark and detectLLM-generated text have been proposed very recently. However, we discover thatthe previous methods fail to function appropriately with code generation tasksbecause of the syntactic and semantic characteristics of code. Based on\citet{Kirchenbauer2023watermark}, we propose a new watermarking method,Selective WatErmarking via Entropy Thresholding (SWEET), that promotes "green"tokens only at the position with high entropy of the token distribution duringgeneration, thereby preserving the correctness of the generated code. Thewatermarked code is detected by the statistical test and Z-score based on theentropy information. Our experiments on HumanEval and MBPP show that SWEETsignificantly improves the Pareto Frontier between the code correctness andwatermark detection performance. We also show that notable post-hoc detectionmethods (e.g. DetectGPT) fail to work well in this task. Finally, we show thatsetting a reasonable entropy threshold is not much of a challenge. Code isavailable at https://github.com/hongcheki/sweet-watermark.
{{< /details >}}

[**Adversarial Feature Map Pruning for Backdoor**](http://arxiv.org/abs/2307.11565v2)

*Dong Huang, Qingwen Bu*

{{< details "abstract" >}} abstract: Deep neural networks have been widely used in many critical applications,such as autonomous vehicles and medical diagnosis. However, their security isthreatened by backdoor attacks, which are achieved by adding artificialpatterns to specific training data. Existing defense strategies primarily focuson using reverse engineering to reproduce the backdoor trigger generated byattackers and subsequently repair the DNN model by adding the trigger intoinputs and fine-tuning the model with ground-truth labels. However, once thetrigger generated by the attackers is complex and invisible, the defendercannot reproduce the trigger successfully then the DNN model will not berepaired, as the trigger is not effectively removed.  In this work, we propose Adversarial Feature Map Pruning for Backdoor (FMP)to mitigate backdoor from the DNN. Unlike existing defense strategies, whichfocus on reproducing backdoor triggers, FMP attempts to prune backdoor featuremaps, which are trained to extract backdoor information from inputs. Afterpruning these backdoor feature maps, FMP will fine-tune the model with a securesubset of training data. Our experiments demonstrate that, compared to existingdefense strategies, FMP can effectively reduce the Attack Success Rate (ASR)even against the most complex and invisible attack triggers (e.g., FMPdecreases the ASR to 2.86\% in CIFAR10, which is 19.2\% to 65.41\% lower thanbaselines). Second, unlike conventional defense methods that tend to exhibitlow robust accuracy (that is, the accuracy of the model on poisoned data), FMPachieves a higher RA, indicating its superiority in maintaining modelperformance while mitigating the effects of backdoor attacks (e.g., FMP obtains87.40\% RA in CIFAR10). Our code is publicly available at:https://github.com/retsuh-bqw/FMP.
{{< /details >}}

>**_2024-02-22_**

[**ParaGuide: Guided Diffusion Paraphrasers for Plug-and-Play Textual Style Transfer**](http://arxiv.org/abs/2308.15459v3)

*Zachary Horvitz, Ajay Patel, Chris Callison-Burch, Zhou Yu, Kathleen McKeown*

{{< details "abstract" >}} abstract: Textual style transfer is the task of transforming stylistic properties oftext while preserving meaning. Target "styles" can be defined in numerous ways,ranging from single attributes (e.g, formality) to authorship (e.g,Shakespeare). Previous unsupervised style-transfer approaches generally rely onsignificant amounts of labeled data for only a fixed set of styles or requirelarge language models. In contrast, we introduce a novel diffusion-basedframework for general-purpose style transfer that can be flexibly adapted toarbitrary target styles at inference time. Our parameter-efficient approach,ParaGuide, leverages paraphrase-conditioned diffusion models alongsidegradient-based guidance from both off-the-shelf classifiers and strong existingstyle embedders to transform the style of text while preserving semanticinformation. We validate the method on the Enron Email Corpus, with both humanand automatic evaluations, and find that it outperforms strong baselines onformality, sentiment, and even authorship style transfer.
{{< /details >}}

>**_2024-02-21_**

[**The Effect of Intrinsic Dataset Properties on Generalization: Unraveling Learning Differences Between Natural and Medical Images**](http://arxiv.org/abs/2401.08865v3)

*Nicholas Konz, Maciej A. Mazurowski*

{{< details "abstract" >}} abstract: This paper investigates discrepancies in how neural networks learn fromdifferent imaging domains, which are commonly overlooked when adopting computervision techniques from the domain of natural images to other specializeddomains such as medical images. Recent works have found that the generalizationerror of a trained network typically increases with the intrinsic dimension($d_{data}$) of its training set. Yet, the steepness of this relationshipvaries significantly between medical (radiological) and natural imagingdomains, with no existing theoretical explanation. We address this gap inknowledge by establishing and empirically validating a generalization scalinglaw with respect to $d_{data}$, and propose that the substantial scalingdiscrepancy between the two considered domains may be at least partiallyattributed to the higher intrinsic ``label sharpness'' ($K_\mathcal{F}$) ofmedical imaging datasets, a metric which we propose. Next, we demonstrate anadditional benefit of measuring the label sharpness of a training set: it isnegatively correlated with the trained model's adversarial robustness, whichnotably leads to models for medical images having a substantially highervulnerability to adversarial attack. Finally, we extend our $d_{data}$formalism to the related metric of learned representation intrinsic dimension($d_{repr}$), derive a generalization scaling law with respect to $d_{repr}$,and show that $d_{data}$ serves as an upper bound for $d_{repr}$. Ourtheoretical results are supported by thorough experiments with six models andeleven natural and medical imaging datasets over a range of training set sizes.Our findings offer insights into the influence of intrinsic dataset propertieson generalization, representation learning, and robustness in deep neuralnetworks. Code link: https://github.com/mazurowski-lab/intrinsic-properties
{{< /details >}}

>**_2024-02-20_**

[**Large Language Models: A Survey**](http://arxiv.org/abs/2402.06196v2)

*Shervin Minaee, Tomas Mikolov, Narjes Nikzad, Meysam Chenaghlu, Richard Socher, Xavier Amatriain, Jianfeng Gao*

{{< details "abstract" >}} abstract: Large Language Models (LLMs) have drawn a lot of attention due to theirstrong performance on a wide range of natural language tasks, since the releaseof ChatGPT in November 2022. LLMs' ability of general-purpose languageunderstanding and generation is acquired by training billions of model'sparameters on massive amounts of text data, as predicted by scaling laws\cite{kaplan2020scaling,hoffmann2022training}. The research area of LLMs, whilevery recent, is evolving rapidly in many different ways. In this paper, wereview some of the most prominent LLMs, including three popular LLM families(GPT, LLaMA, PaLM), and discuss their characteristics, contributions andlimitations. We also give an overview of techniques developed to build, andaugment LLMs. We then survey popular datasets prepared for LLM training,fine-tuning, and evaluation, review widely used LLM evaluation metrics, andcompare the performance of several popular LLMs on a set of representativebenchmarks. Finally, we conclude the paper by discussing open challenges andfuture research directions.
{{< /details >}}

[**Double machine learning for causal hybrid modeling -- applications in the Earth sciences**](http://arxiv.org/abs/2402.13332v1)

*Kai-Hendrik Cohrs, Gherardo Varando, Nuno Carvalhais, Markus Reichstein, Gustau Camps-Valls*

{{< details "abstract" >}} abstract: Hybrid modeling integrates machine learning with scientific knowledge withthe goal of enhancing interpretability, generalization, and adherence tonatural laws. Nevertheless, equifinality and regularization biases posechallenges in hybrid modeling to achieve these purposes. This paper introducesa novel approach to estimating hybrid models via a causal inference framework,specifically employing Double Machine Learning (DML) to estimate causaleffects. We showcase its use for the Earth sciences on two problems related tocarbon dioxide fluxes. In the $Q_{10}$ model, we demonstrate that DML-basedhybrid modeling is superior in estimating causal parameters over end-to-enddeep neural network (DNN) approaches, proving efficiency, robustness to biasfrom regularization methods, and circumventing equifinality. Our approach,applied to carbon flux partitioning, exhibits flexibility in accommodatingheterogeneous causal effects. The study emphasizes the necessity of explicitlydefining causal graphs and relationships, advocating for this as a general bestpractice. We encourage the continued exploration of causality in hybrid modelsfor more interpretable and trustworthy results in knowledge-guided machinelearning.
{{< /details >}}

>**_2024-02-19_**

[**A Lightweight Parallel Framework for Blind Image Quality Assessment**](http://arxiv.org/abs/2402.12043v1)

*Qunyue Huang, Bin Fang*

{{< details "abstract" >}} abstract: Existing blind image quality assessment (BIQA) methods focus on designingcomplicated networks based on convolutional neural networks (CNNs) ortransformer. In addition, some BIQA methods enhance the performance of themodel in a two-stage training manner. Despite the significant advancements,these methods remarkably raise the parameter count of the model, thus requiringmore training time and computational resources. To tackle the above issues, wepropose a lightweight parallel framework (LPF) for BIQA. First, we extract thevisual features using a pre-trained feature extraction network. Furthermore, weconstruct a simple yet effective feature embedding network (FEN) to transformthe visual features, aiming to generate the latent representations that containsalient distortion information. To improve the robustness of the latentrepresentations, we present two novel self-supervised subtasks, including asample-level category prediction task and a batch-level quality comparisontask. The sample-level category prediction task is presented to help the modelwith coarse-grained distortion perception. The batch-level quality comparisontask is formulated to enhance the training data and thus improve the robustnessof the latent representations. Finally, the latent representations are fed intoa distortion-aware quality regression network (DaQRN), which simulates thehuman vision system (HVS) and thus generates accurate quality scores.Experimental results on multiple benchmark datasets demonstrate that theproposed method achieves superior performance over state-of-the-art approaches.Moreover, extensive analyses prove that the proposed method has lowercomputational complexity and faster convergence speed.
{{< /details >}}

>**_2024-02-18_**

[**Deep-Lock: Secure Authorization for Deep Neural Networks**](http://arxiv.org/abs/2008.05966v2)

*Manaar Alam, Sayandeep Saha, Debdeep Mukhopadhyay, Sandip Kundu*

{{< details "abstract" >}} abstract: Trained Deep Neural Network (DNN) models are considered valuable IntellectualProperties (IP) in several business models. Prevention of IP theft andunauthorized usage of such DNN models has been raised as of significant concernby industry. In this paper, we address the problem of preventing unauthorizedusage of DNN models by proposing a generic and lightweight key-basedmodel-locking scheme, which ensures that a locked model functions correctlyonly upon applying the correct secret key. The proposed scheme, known asDeep-Lock, utilizes S-Boxes with good security properties to encrypt eachparameter of a trained DNN model with secret keys generated from a master keyvia a key scheduling algorithm. The resulting dense network of encryptedweights is found robust against model fine-tuning attacks. Finally, Deep-Lockdoes not require any intervention in the structure and training of the DNNmodels, making it applicable for all existing software and hardwareimplementations of DNN.
{{< /details >}}

>**_2024-02-14_**

[**Neural Operators Meet Energy-based Theory: Operator Learning for Hamiltonian and Dissipative PDEs**](http://arxiv.org/abs/2402.09018v1)

*Yusuke Tanaka, Takaharu Yaguchi, Tomoharu Iwata, Naonori Ueda*

{{< details "abstract" >}} abstract: The operator learning has received significant attention in recent years,with the aim of learning a mapping between function spaces. Prior works haveproposed deep neural networks (DNNs) for learning such a mapping, enabling thelearning of solution operators of partial differential equations (PDEs).However, these works still struggle to learn dynamics that obeys the laws ofphysics. This paper proposes Energy-consistent Neural Operators (ENOs), ageneral framework for learning solution operators of PDEs that follows theenergy conservation or dissipation law from observed solution trajectories. Weintroduce a novel penalty function inspired by the energy-based theory ofphysics for training, in which the energy functional is modeled by another DNN,allowing one to bias the outputs of the DNN-based solution operators to ensureenergetic consistency without explicit PDEs. Experiments on multiple physicalsystems show that ENO outperforms existing DNN models in predicting solutionsfrom data, especially in super-resolution settings.
{{< /details >}}

[**A Study of Fairness Concerns in AI-based Mobile App Reviews**](http://arxiv.org/abs/2401.08097v2)

*Ali Rezaei Nasab, Maedeh Dashti, Mojtaba Shahin, Mansooreh Zahedi, Hourieh Khalajzadeh, Chetan Arora, Peng Liang*

{{< details "abstract" >}} abstract: Fairness is one of the socio-technical concerns that must be addressed inAI-based systems. Unfair AI-based systems, particularly unfair AI-based mobileapps, can pose difficulties for a significant proportion of the globalpopulation. This paper aims to analyze fairness concerns in AI-based appreviews.We first manually constructed a ground-truth dataset, including astatistical sample of fairness and non-fairness reviews. Leveraging theground-truth dataset, we developed and evaluated a set of machine learning anddeep learning classifiers that distinguish fairness reviews from non-fairnessreviews. Our experiments show that our best-performing classifier can detectfairness reviews with a precision of 94%. We then applied the best-performingclassifier on approximately 9.5M reviews collected from 108 AI-based apps andidentified around 92K fairness reviews. Next, applying the K-means clusteringtechnique to the 92K fairness reviews, followed by manual analysis, led to theidentification of six distinct types of fairness concerns (e.g., 'receivingdifferent quality of features and services in different platforms and devices'and 'lack of transparency and fairness in dealing with user-generatedcontent'). Finally, the manual analysis of 2,248 app owners' responses to thefairness reviews identified six root causes (e.g., 'copyright issues') that appowners report to justify fairness concerns.
{{< /details >}}

>**_2024-02-12_**

[**Game Agent Driven by Free-Form Text Command: Using LLM-based Code Generation and Behavior Branch**](http://arxiv.org/abs/2402.07442v1)

*Ray Ito, Junichiro Takahashi*

{{< details "abstract" >}} abstract: Several attempts have been made to implement text command control for gameagents. However, current technologies are limited to processing predefinedformat commands. This paper proposes a pioneering text command control systemfor a game agent that can understand natural language commands expressed infree-form. The proposed system uses a large language model (LLM) for codegeneration to interpret and transform natural language commands into behaviorbranch, a proposed knowledge expression based on behavior trees, whichfacilitates execution by the game agent. This study conducted empiricalvalidation within a game environment that simulates a Pok\'emon game andinvolved multiple participants. The results confirmed the system's ability tounderstand and carry out natural language commands, representing a noteworthyin the realm of real-time language interactive game agents.  Notice for the use of this material. The copyright of this material isretained by the Japanese Society for Artificial Intelligence (JSAI). Thismaterial is published here with the agreement of JSAI. Please be complied withCopyright Law of Japan if any users wish to reproduce, make derivative work,distribute or make available to the public any part or whole thereof. AllRights Reserved, Copyright (C) The Japanese Society for ArtificialIntelligence.
{{< /details >}}

>**_2024-02-06_**

[**Self-supervised visual learning for analyzing firearms trafficking activities on the Web**](http://arxiv.org/abs/2310.07975v2)

*Sotirios Konstantakos, Despina Ioanna Chalkiadaki, Ioannis Mademlis, Adamantia Anna Rebolledo Chrysochoou, Georgios Th. Papadopoulos*

{{< details "abstract" >}} abstract: Automated visual firearms classification from RGB images is an importantreal-world task with applications in public space security, intelligencegathering and law enforcement investigations. When applied to images massivelycrawled from the World Wide Web (including social media and dark Web sites), itcan serve as an important component of systems that attempt to identifycriminal firearms trafficking networks, by analyzing Big Data from open-sourceintelligence. Deep Neural Networks (DNN) are the state-of-the-art methodologyfor achieving this, with Convolutional Neural Networks (CNN) being typicallyemployed. The common transfer learning approach consists of pretraining on alarge-scale, generic annotated dataset for whole-image classification, such asImageNet-1k, and then finetuning the DNN on a smaller, annotated,task-specific, downstream dataset for visual firearms classification. NeitherVisual Transformer (ViT) neural architectures nor Self-Supervised Learning(SSL) approaches have been so far evaluated on this critical task..
{{< /details >}}

[**Foregrounding Artist Opinions: A Survey Study on Transparency, Ownership, and Fairness in AI Generative Art**](http://arxiv.org/abs/2401.15497v3)

*Juniper Lovato, Julia Zimmerman, Isabelle Smith, Peter Dodds, Jennifer Karson*

{{< details "abstract" >}} abstract: Generative Artificial Intelligence (AI) tools are used to create art-likeoutputs and aid in the creative process. While these tools have potentialbenefits for artists, they also have the potential to harm the art workforceand infringe upon artistic and intellectual property rights. Without explicitconsent from artists, Generative AI creators scrape artists' digital work totrain Generative AI models and produce art-like model outputs at scale. Theseoutputs are now being used to compete with human artists in the marketplace aswell as being used by some artists in their generative processes to create art.We surveyed 459 artists to investigate the tension between artists' opinions onGenerative AI art's potential utility and harm. This study surveys artists'opinions on the utility and threat of Generative AI art models, fair practicesin the disclosure of artistic works in AI art training models, ownership andrights of AI art derivatives, and fair compensation. We find that artists, byand large, think that model creators should be required to disclose in detailwhat art and images they use to train their AI models. We also find thatartists' opinions vary by professional status and practice, demographics,whether they have purchased art, and familiarity with and use of Generative AI.We hope the results of this work will further more meaningful collaboration andalignment between the art community and Generative AI researchers anddevelopers.
{{< /details >}}

[**PreGIP: Watermarking the Pretraining of Graph Neural Networks for Deep Intellectual Property Protection**](http://arxiv.org/abs/2402.04435v1)

*Enyan Dai, Minhua Lin, Suhang Wang*

{{< details "abstract" >}} abstract: Pretraining on Graph Neural Networks (GNNs) has shown great power infacilitating various downstream tasks. As pretraining generally requires hugeamount of data and computational resources, the pretrained GNNs are high-valueIntellectual Properties (IP) of the legitimate owner. However, adversaries mayillegally copy and deploy the pretrained GNN models for their downstream tasks.Though initial efforts have been made to watermark GNN classifiers for IPprotection, these methods require the target classification task forwatermarking, and thus are not applicable to self-supervised pretraining of GNNmodels. Hence, in this work, we propose a novel framework named PreGIP towatermark the pretraining of GNN encoder for IP protection while maintain thehigh-quality of the embedding space. PreGIP incorporates a task-freewatermarking loss to watermark the embedding space of pretrained GNN encoder. Afinetuning-resistant watermark injection is further deployed. Theoreticalanalysis and extensive experiments show the effectiveness of {\method} in IPprotection and maintaining high-performance for downstream tasks.
{{< /details >}}

>**_2024-02-02_**

[**Neuro-Symbolic Learning of Answer Set Programs from Raw Data**](http://arxiv.org/abs/2205.12735v8)

*Daniel Cunnington, Mark Law, Jorge Lobo, Alessandra Russo*

{{< details "abstract" >}} abstract: One of the ultimate goals of Artificial Intelligence is to assist humans incomplex decision making. A promising direction for achieving this goal isNeuro-Symbolic AI, which aims to combine the interpretability of symbolictechniques with the ability of deep learning to learn from raw data. However,most current approaches require manually engineered symbolic knowledge, andwhere end-to-end training is considered, such approaches are either restrictedto learning definite programs, or are restricted to training binary neuralnetworks. In this paper, we introduce Neuro-Symbolic Inductive Learner (NSIL),an approach that trains a general neural network to extract latent conceptsfrom raw data, whilst learning symbolic knowledge that maps latent concepts totarget labels. The novelty of our approach is a method for biasing the learningof symbolic knowledge, based on the in-training performance of both neural andsymbolic components. We evaluate NSIL on three problem domains of differentcomplexity, including an NP-complete problem. Our results demonstrate that NSILlearns expressive knowledge, solves computationally complex problems, andachieves state-of-the-art performance in terms of accuracy and data efficiency.Code and technical appendix: https://github.com/DanCunnington/NSIL
{{< /details >}}

>**_2024-01-30_**

[**TeG-DG: Textually Guided Domain Generalization for Face Anti-Spoofing**](http://arxiv.org/abs/2311.18420v2)

*Lianrui Mu, Jianhong Bai, Xiaoxuan He, Jiangnan Ye, Xiaoyu Liang, Yuchen Yang, Jiedong Zhuang, Haoji Hu*

{{< details "abstract" >}} abstract: Enhancing the domain generalization performance of Face Anti-Spoofing (FAS)techniques has emerged as a research focus. Existing methods are dedicated toextracting domain-invariant features from various training domains. Despite thepromising performance, the extracted features inevitably contain residual stylefeature bias (e.g., illumination, capture device), resulting in inferiorgeneralization performance. In this paper, we propose an alternative andeffective solution, the Textually Guided Domain Generalization (TeG-DG)framework, which can effectively leverage text information for cross-domainalignment. Our core insight is that text, as a more abstract and universal formof expression, can capture the commonalities and essential characteristicsacross various attacks, bridging the gap between different image domains.Contrary to existing vision-language models, the proposed framework iselaborately designed to enhance the domain generalization ability of the FAStask. Concretely, we first design a Hierarchical Attention Fusion (HAF) moduleto enable adaptive aggregation of visual features at different levels; Then, aTextual-Enhanced Visual Discriminator (TEVD) is proposed for not only betteralignment between the two modalities but also to regularize the classifier withunbiased text features. TeG-DG significantly outperforms previous approaches,especially in situations with extremely limited source domain data (~14% and~12% improvements on HTER and AUC respectively), showcasing impressive few-shotperformance.
{{< /details >}}

>**_2024-01-29_**

[**SSL-WM: A Black-Box Watermarking Approach for Encoders Pre-trained by Self-supervised Learning**](http://arxiv.org/abs/2209.03563v2)

*Peizhuo Lv, Pan Li, Shenchen Zhu, Shengzhi Zhang, Kai Chen, Ruigang Liang, Chang Yue, Fan Xiang, Yuling Cai, Hualong Ma, Yingjun Zhang, Guozhu Meng*

{{< details "abstract" >}} abstract: Recent years have witnessed tremendous success in Self-Supervised Learning(SSL), which has been widely utilized to facilitate various downstream tasks inComputer Vision (CV) and Natural Language Processing (NLP) domains. However,attackers may steal such SSL models and commercialize them for profit, makingit crucial to verify the ownership of the SSL models. Most existing ownershipprotection solutions (e.g., backdoor-based watermarks) are designed forsupervised learning models and cannot be used directly since they require thatthe models' downstream tasks and target labels be known and available duringwatermark embedding, which is not always possible in the domain of SSL. Toaddress such a problem, especially when downstream tasks are diverse andunknown during watermark embedding, we propose a novel black-box watermarkingsolution, named SSL-WM, for verifying the ownership of SSL models. SSL-WM mapswatermarked inputs of the protected encoders into an invariant representationspace, which causes any downstream classifier to produce expected behavior,thus allowing the detection of embedded watermarks. We evaluate SSL-WM onnumerous tasks, such as CV and NLP, using different SSL models bothcontrastive-based and generative-based. Experimental results demonstrate thatSSL-WM can effectively verify the ownership of stolen SSL models in variousdownstream tasks. Furthermore, SSL-WM is robust against model fine-tuning,pruning, and input preprocessing attacks. Lastly, SSL-WM can also evadedetection from evaluated watermark detection approaches, demonstrating itspromising application in protecting the ownership of SSL models.
{{< /details >}}

>**_2024-01-28_**

[**Data-Free Generalized Zero-Shot Learning**](http://arxiv.org/abs/2401.15657v1)

*Bowen Tang, Long Yan, Jing Zhang, Qian Yu, Lu Sheng, Dong Xu*

{{< details "abstract" >}} abstract: Deep learning models have the ability to extract rich knowledge fromlarge-scale datasets. However, the sharing of data has become increasinglychallenging due to concerns regarding data copyright and privacy. Consequently,this hampers the effective transfer of knowledge from existing data to noveldownstream tasks and concepts. Zero-shot learning (ZSL) approaches aim torecognize new classes by transferring semantic knowledge learned from baseclasses. However, traditional generative ZSL methods often require access toreal images from base classes and rely on manually annotated attributes, whichpresents challenges in terms of data restrictions and model scalability. Tothis end, this paper tackles a challenging and practical problem dubbed asdata-free zero-shot learning (DFZSL), where only the CLIP-based base classesdata pre-trained classifier is available for zero-shot classification.Specifically, we propose a generic framework for DFZSL, which consists of threemain components. Firstly, to recover the virtual features of the base data, wemodel the CLIP features of base class images as samples from a von Mises-Fisher(vMF) distribution based on the pre-trained classifier. Secondly, we leveragethe text features of CLIP as low-cost semantic information and propose afeature-language prompt tuning (FLPT) method to further align the virtual imagefeatures and textual features. Thirdly, we train a conditional generative modelusing the well-aligned virtual image features and corresponding semantic textfeatures, enabling the generation of new classes features and achieve betterzero-shot generalization. Our framework has been evaluated on five commonlyused benchmarks for generalized ZSL, as well as 11 benchmarks for thebase-to-new ZSL. The results demonstrate the superiority and effectiveness ofour approach. Our code is available in https://github.com/ylong4/DFZSL
{{< /details >}}

>**_2024-01-27_**

[**Style-News: Incorporating Stylized News Generation and Adversarial Verification for Neural Fake News Detection**](http://arxiv.org/abs/2401.15509v1)

*Wei-Yao Wang, Yu-Chieh Chang, Wen-Chih Peng*

{{< details "abstract" >}} abstract: With the improvements in generative models, the issues of producinghallucinations in various domains (e.g., law, writing) have been brought topeople's attention due to concerns about misinformation. In this paper, wefocus on neural fake news, which refers to content generated by neural networksaiming to mimic the style of real news to deceive people. To prevent harmfuldisinformation spreading fallaciously from malicious social media (e.g.,content farms), we propose a novel verification framework, Style-News, usingpublisher metadata to imply a publisher's template with the corresponding texttypes, political stance, and credibility. Based on threat modeling aspects, astyle-aware neural news generator is introduced as an adversary for generatingnews content conditioning for a specific publisher, and style and sourcediscriminators are trained to defend against this attack by identifying whichpublisher the style corresponds with, and discriminating whether the source ofthe given news is human-written or machine-generated. To evaluate the qualityof the generated content, we integrate various dimensional metrics (languagefluency, content preservation, and style adherence) and demonstrate thatStyle-News significantly outperforms the previous approaches by a margin of0.35 for fluency, 15.24 for content, and 0.38 for style at most. Moreover, ourdiscriminative model outperforms state-of-the-art baselines in terms ofpublisher prediction (up to 4.64%) and neural fake news detection (+6.94%$\sim$ 31.72%).
{{< /details >}}

>**_2024-01-23_**

[**A Survey of Text Watermarking in the Era of Large Language Models**](http://arxiv.org/abs/2312.07913v4)

*Aiwei Liu, Leyi Pan, Yijian Lu, Jingjing Li, Xuming Hu, Xi Zhang, Lijie Wen, Irwin King, Hui Xiong, Philip S. Yu*

{{< details "abstract" >}} abstract: Text watermarking algorithms play a crucial role in the copyright protectionof textual content, yet their capabilities and application scenarios have beenlimited historically. The recent developments in large language models (LLMs)have opened new opportunities for the advancement of text watermarkingtechniques. LLMs not only enhance the capabilities of text watermarkingalgorithms through their text understanding and generation abilities but alsonecessitate the use of text watermarking algorithms for their own copyrightprotection. This paper conducts a comprehensive survey of the current state oftext watermarking technology, covering four main aspects: (1) an overview andcomparison of different text watermarking techniques; (2) evaluation methodsfor text watermarking algorithms, including their success rates, impact on textquality, robustness, and unforgeability; (3) potential application scenariosfor text watermarking technology; (4) current challenges and future directionsfor development. This survey aims to provide researchers with a thoroughunderstanding of text watermarking technology, thereby promoting its furtheradvancement.
{{< /details >}}

>**_2024-01-21_**

[**Instructional Fingerprinting of Large Language Models**](http://arxiv.org/abs/2401.12255v1)

*Jiashu Xu, Fei Wang, Mingyu Derek Ma, Pang Wei Koh, Chaowei Xiao, Muhao Chen*

{{< details "abstract" >}} abstract: The exorbitant cost of training Large language models (LLMs) from scratchmakes it essential to fingerprint the models to protect intellectual propertyvia ownership authentication and to ensure downstream users and developerscomply with their license terms (e.g. restricting commercial use). In thisstudy, we present a pilot study on LLM fingerprinting as a form of verylightweight instruction tuning. Model publisher specifies a confidentialprivate key and implants it as an instruction backdoor that causes the LLM togenerate specific text when the key is present. Results on 11 popularly-usedLLMs showed that this approach is lightweight and does not affect the normalbehavior of the model. It also prevents publisher overclaim, maintainsrobustness against fingerprint guessing and parameter-efficient training, andsupports multi-stage fingerprinting akin to MIT License. Code is available inhttps://cnut1648.github.io/Model-Fingerprint/.
{{< /details >}}

>**_2024-01-19_**

[**RAD-DINO: Exploring Scalable Medical Image Encoders Beyond Text Supervision**](http://arxiv.org/abs/2401.10815v1)

*Fernando Pérez-García, Harshita Sharma, Sam Bond-Taylor, Kenza Bouzid, Valentina Salvatelli, Maximilian Ilse, Shruthi Bannur, Daniel C. Castro, Anton Schwaighofer, Matthew P. Lungren, Maria Wetscherek, Noel Codella, Stephanie L. Hyland, Javier Alvarez-Valle, Ozan Oktay*

{{< details "abstract" >}} abstract: Language-supervised pre-training has proven to be a valuable method forextracting semantically meaningful features from images, serving as afoundational element in multimodal systems within the computer vision andmedical imaging domains. However, resulting features are limited by theinformation contained within the text. This is particularly problematic inmedical imaging, where radiologists' written findings focus on specificobservations; a challenge compounded by the scarcity of paired imaging-textdata due to concerns over leakage of personal health information. In this work,we fundamentally challenge the prevailing reliance on language supervision forlearning general purpose biomedical imaging encoders. We introduce RAD-DINO, abiomedical image encoder pre-trained solely on unimodal biomedical imaging datathat obtains similar or greater performance than state-of-the-art biomedicallanguage supervised models on a diverse range of benchmarks. Specifically, thequality of learned representations is evaluated on standard imaging tasks(classification and semantic segmentation), and a vision-language alignmenttask (text report generation from images). To further demonstrate the drawbackof language supervision, we show that features from RAD-DINO correlate withother medical records (e.g., sex or age) better than language-supervisedmodels, which are generally not mentioned in radiology reports. Finally, weconduct a series of ablations determining the factors in RAD-DINO'sperformance; notably, we observe that RAD-DINO's downstream performance scaleswell with the quantity and diversity of training data, demonstrating thatimage-only supervision is a scalable approach for training a foundationalbiomedical image encoder.
{{< /details >}}

>**_2024-01-18_**

[**Artwork Protection Against Neural Style Transfer Using Locally Adaptive Adversarial Color Attack**](http://arxiv.org/abs/2401.09673v1)

*Zhongliang Guo, Kaixuan Wang, Weiye Li, Yifei Qian, Ognjen Arandjelović, Lei Fang*

{{< details "abstract" >}} abstract: Neural style transfer (NST) is widely adopted in computer vision to generatenew images with arbitrary styles. This process leverages neural networks tomerge aesthetic elements of a style image with the structural aspects of acontent image into a harmoniously integrated visual result. However,unauthorized NST can exploit artwork. Such misuse raises socio-technicalconcerns regarding artists' rights and motivates the development of technicalapproaches for the proactive protection of original creations. Adversarialattack is a concept primarily explored in machine learning security. Our workintroduces this technique to protect artists' intellectual property. In thispaper Locally Adaptive Adversarial Color Attack (LAACA), a method for alteringimages in a manner imperceptible to the human eyes but disruptive to NST.Specifically, we design perturbations targeting image areas rich inhigh-frequency content, generated by disrupting intermediate features. Ourexperiments and user study confirm that by attacking NST using the proposedmethod results in visually worse neural style transfer, thus making it aneffective solution for visual artwork protection.
{{< /details >}}

>**_2024-01-17_**

[**Explain Thyself Bully: Sentiment Aided Cyberbullying Detection with Explanation**](http://arxiv.org/abs/2401.09023v1)

*Krishanu Maity, Prince Jha, Raghav Jain, Sriparna Saha, Pushpak Bhattacharyya*

{{< details "abstract" >}} abstract: Cyberbullying has become a big issue with the popularity of different socialmedia networks and online communication apps. While plenty of research is goingon to develop better models for cyberbullying detection in monolinguallanguage, there is very little research on the code-mixed languages andexplainability aspect of cyberbullying. Recent laws like "right toexplanations" of General Data Protection Regulation, have spurred research indeveloping interpretable models rather than focusing on performance. Motivatedby this we develop the first interpretable multi-task model called {\em mExCB}for automatic cyberbullying detection from code-mixed languages which cansimultaneously solve several tasks, cyberbullying detection,explanation/rationale identification, target group detection and sentimentanalysis. We have introduced {\em BullyExplain}, the first benchmark datasetfor explainable cyberbullying detection in code-mixed language. Each post in{\em BullyExplain} dataset is annotated with four labels, i.e., {\em bullylabel, sentiment label, target and rationales (explainability)}, i.e., whichphrases are being responsible for annotating the post as a bully. The proposedmultitask framework (mExCB) based on CNN and GRU with word and sub-sentence(SS) level attention is able to outperform several baselines and state of theart models when applied on {\em BullyExplain} dataset.
{{< /details >}}

[**GraphCare: Enhancing Healthcare Predictions with Personalized Knowledge Graphs**](http://arxiv.org/abs/2305.12788v3)

*Pengcheng Jiang, Cao Xiao, Adam Cross, Jimeng Sun*

{{< details "abstract" >}} abstract: Clinical predictive models often rely on patients' electronic health records(EHR), but integrating medical knowledge to enhance predictions anddecision-making is challenging. This is because personalized predictionsrequire personalized knowledge graphs (KGs), which are difficult to generatefrom patient EHR data. To address this, we propose \textsc{GraphCare}, anopen-world framework that uses external KGs to improve EHR-based predictions.Our method extracts knowledge from large language models (LLMs) and externalbiomedical KGs to build patient-specific KGs, which are then used to train ourproposed Bi-attention AugmenTed (BAT) graph neural network (GNN) for healthcarepredictions. On two public datasets, MIMIC-III and MIMIC-IV, \textsc{GraphCare}surpasses baselines in four vital healthcare prediction tasks: mortality,readmission, length of stay (LOS), and drug recommendation. On MIMIC-III, itboosts AUROC by 17.6\% and 6.6\% for mortality and readmission, and F1-score by7.9\% and 10.8\% for LOS and drug recommendation, respectively. Notably,\textsc{GraphCare} demonstrates a substantial edge in scenarios with limiteddata availability. Our findings highlight the potential of using external KGsin healthcare prediction tasks and demonstrate the promise of\textsc{GraphCare} in generating personalized KGs for promoting personalizedmedicine.
{{< /details >}}

>**_2024-01-16_**

[**Adversarial Masking Contrastive Learning for vein recognition**](http://arxiv.org/abs/2401.08079v1)

*Huafeng Qin, Yiquan Wu, Mounim A. El-Yacoubi, Jun Wang, Guangxiang Yang*

{{< details "abstract" >}} abstract: Vein recognition has received increasing attention due to its high securityand privacy. Recently, deep neural networks such as Convolutional neuralnetworks (CNN) and Transformers have been introduced for vein recognition andachieved state-of-the-art performance. Despite the recent advances, however,existing solutions for finger-vein feature extraction are still not optimal dueto scarce training image samples. To overcome this problem, in this paper, wepropose an adversarial masking contrastive learning (AMCL) approach, thatgenerates challenging samples to train a more robust contrastive learning modelfor the downstream palm-vein recognition task, by alternatively optimizing theencoder in the contrastive learning model and a set of latent variables. First,a huge number of masks are generated to train a robust generative adversarialnetwork (GAN). The trained generator transforms a latent variable from thelatent variable space into a mask space. Then, we combine the trained generatorwith a contrastive learning model to obtain our AMCL, where the generatorproduces challenging masking images to increase the contrastive loss and thecontrastive learning model is trained based on the harder images to learn amore robust feature representation. After training, the trained encoder in thecontrastive learning model is combined with a classification layer to build aclassifier, which is further fine-tuned on labeled training data for veinrecognition. The experimental results on three databases demonstrate that ourapproach outperforms existing contrastive learning approaches in terms ofimproving identification accuracy of vein classifiers and achievesstate-of-the-art recognition results.
{{< /details >}}

[**Physics-informed Meta-instrument for eXperiments (PiMiX) with applications to fusion energy**](http://arxiv.org/abs/2401.08390v1)

*Zhehui Wang, Shanny Lin, Miles Teng-Levy, Pinghan Chu, Bradley T. Wolfe, Chun-Shang Wong, Christopher S. Campbell, Xin Yue, Liyuan Zhang, Derek Aberle, Mariana Alvarado Alvarez, David Broughton, Ray T. Chen, Baolian Cheng, Feng Chu, Eric R. Fossum, Mark A. Foster, Chengkun Huang, Velat Kilic, Karl Krushelnick, Wenting Li, Eric Loomis, Thomas Schmidt Jr., Sky K. Sjue, Chris Tomkins, Dmitry A. Yarotski, Renyuan Zhu*

{{< details "abstract" >}} abstract: Data-driven methods (DDMs), such as deep neural networks, offer a genericapproach to integrated data analysis (IDA), integrated diagnostic-to-control(IDC) workflows through data fusion (DF), which includes multi-instrument datafusion (MIDF), multi-experiment data fusion (MXDF), and simulation-experimentdata fusion (SXDF). These features make DDMs attractive to nuclear fusionenergy and power plant applications, leveraging accelerated workflows throughmachine learning and artificial intelligence. Here we describe Physics-informedMeta-instrument for eXperiments (PiMiX) that integrates X-ray (includinghigh-energy photons such as $\gamma$-rays from nuclear fusion), neutron andothers (such as proton radiography) measurements for nuclear fusion. PiMiXsolves multi-domain high-dimensional optimization problems and integratesmulti-modal measurements with multiphysics modeling through neural networks.Super-resolution for neutron detection and energy resolved X-ray detection havebeen demonstrated. Multi-modal measurements through MIDF can extract moreinformation than individual or uni-modal measurements alone. Furtheroptimization schemes through DF are possible towards empirical fusion scalinglaws discovery and new fusion reactor designs.
{{< /details >}}

>**_2024-01-15_**

[**Traces of Memorisation in Large Language Models for Code**](http://arxiv.org/abs/2312.11658v2)

*Ali Al-Kaswan, Maliheh Izadi, Arie van Deursen*

{{< details "abstract" >}} abstract: Large language models have gained significant popularity because of theirability to generate human-like text and potential applications in variousfields, such as Software Engineering. Large language models for code arecommonly trained on large unsanitised corpora of source code scraped from theinternet. The content of these datasets is memorised and can be extracted byattackers with data extraction attacks. In this work, we explore memorisationin large language models for code and compare the rate of memorisation withlarge language models trained on natural language. We adopt an existingbenchmark for natural language and construct a benchmark for code byidentifying samples that are vulnerable to attack. We run both benchmarksagainst a variety of models, and perform a data extraction attack. We find thatlarge language models for code are vulnerable to data extraction attacks, liketheir natural language counterparts. From the training data that was identifiedto be potentially extractable we were able to extract 47% from aCodeGen-Mono-16B code completion model. We also observe that models memorisemore, as their parameter count grows, and that their pre-training data are alsovulnerable to attack. We also find that data carriers are memorised at a higherrate than regular code or documentation and that different model architecturesmemorise different samples. Data leakage has severe outcomes, so we urge theresearch community to further investigate the extent of this phenomenon using awider range of models and extraction techniques in order to build safeguards tomitigate this issue.
{{< /details >}}

[**Authorship Obfuscation in Multilingual Machine-Generated Text Detection**](http://arxiv.org/abs/2401.07867v1)

*Dominik Macko, Robert Moro, Adaku Uchendu, Ivan Srba, Jason Samuel Lucas, Michiharu Yamashita, Nafis Irtiza Tripto, Dongwon Lee, Jakub Simko, Maria Bielikova*

{{< details "abstract" >}} abstract: High-quality text generation capability of latest Large Language Models(LLMs) causes concerns about their misuse (e.g., in massive generation/spreadof disinformation). Machine-generated text (MGT) detection is important to copewith such threats. However, it is susceptible to authorship obfuscation (AO)methods, such as paraphrasing, which can cause MGTs to evade detection. So far,this was evaluated only in monolingual settings. Thus, the susceptibility ofrecently proposed multilingual detectors is still unknown. We fill this gap bycomprehensively benchmarking the performance of 10 well-known AO methods,attacking 37 MGT detection methods against MGTs in 11 languages (i.e., 10$\times$ 37 $\times$ 11 = 4,070 combinations). We also evaluate the effect ofdata augmentation on adversarial robustness using obfuscated texts. The resultsindicate that all tested AO methods can cause detection evasion in all testedlanguages, where homoglyph attacks are especially successful.
{{< /details >}}

>**_2024-01-12_**

[**Stylometry Analysis of Multi-authored Documents for Authorship and Author Style Change Detection**](http://arxiv.org/abs/2401.06752v1)

*Muhammad Tayyab Zamir, Muhammad Asif Ayub, Asma Gul, Nasir Ahmad, Kashif Ahmad*

{{< details "abstract" >}} abstract: In recent years, the increasing use of Artificial Intelligence based textgeneration tools has posed new challenges in document provenance,authentication, and authorship detection. However, advancements in stylometryhave provided opportunities for automatic authorship and author changedetection in multi-authored documents using style analysis techniques. Styleanalysis can serve as a primary step toward document provenance andauthentication through authorship detection. This paper investigates three keytasks of style analysis: (i) classification of single and multi-authoreddocuments, (ii) single change detection, which involves identifying the pointwhere the author switches, and (iii) multiple author-switching detection inmulti-authored documents. We formulate all three tasks as classificationproblems and propose a merit-based fusion framework that integrates severalstate-of-the-art natural language processing (NLP) algorithms and weightoptimization techniques. We also explore the potential of special characters,which are typically removed during pre-processing in NLP applications, on theperformance of the proposed methods for these tasks by conducting extensiveexperiments on both cleaned and raw datasets. Experimental results demonstratesignificant improvements over existing solutions for all three tasks on abenchmark dataset.
{{< /details >}}

>**_2024-01-11_**

[**Navigating Privacy and Copyright Challenges Across the Data Lifecycle of Generative AI**](http://arxiv.org/abs/2311.18252v2)

*Dawen Zhang, Boming Xia, Yue Liu, Xiwei Xu, Thong Hoang, Zhenchang Xing, Mark Staples, Qinghua Lu, Liming Zhu*

{{< details "abstract" >}} abstract: The advent of Generative AI has marked a significant milestone in artificialintelligence, demonstrating remarkable capabilities in generating realisticimages, texts, and data patterns. However, these advancements come withheightened concerns over data privacy and copyright infringement, primarily dueto the reliance on vast datasets for model training. Traditional approacheslike differential privacy, machine unlearning, and data poisoning only offerfragmented solutions to these complex issues. Our paper delves into themultifaceted challenges of privacy and copyright protection within the datalifecycle. We advocate for integrated approaches that combines technicalinnovation with ethical foresight, holistically addressing these concerns byinvestigating and devising solutions that are informed by the lifecycleperspective. This work aims to catalyze a broader discussion and inspireconcerted efforts towards data privacy and copyright integrity in GenerativeAI.
{{< /details >}}

>**_2024-01-07_**

[**The Stronger the Diffusion Model, the Easier the Backdoor: Data Poisoning to Induce Copyright Breaches Without Adjusting Finetuning Pipeline**](http://arxiv.org/abs/2401.04136v1)

*Haonan Wang, Qianli Shen, Yao Tong, Yang Zhang, Kenji Kawaguchi*

{{< details "abstract" >}} abstract: The commercialization of diffusion models, renowned for their ability togenerate high-quality images that are often indistinguishable from real ones,brings forth potential copyright concerns. Although attempts have been made toimpede unauthorized access to copyrighted material during training and tosubsequently prevent DMs from generating copyrighted images, the effectivenessof these solutions remains unverified. This study explores the vulnerabilitiesassociated with copyright protection in DMs by introducing a backdoor datapoisoning attack (SilentBadDiffusion) against text-to-image diffusion models.Our attack method operates without requiring access to or control over thediffusion model's training or fine-tuning processes; it merely involves theinsertion of poisoning data into the clean training dataset. This data,comprising poisoning images equipped with prompts, is generated by leveragingthe powerful capabilities of multimodal large language models and text-guidedimage inpainting techniques. Our experimental results and analysis confirm themethod's effectiveness. By integrating a minor portion ofnon-copyright-infringing stealthy poisoning data into the cleandataset-rendering it free from suspicion-we can prompt the finetuned diffusionmodels to produce copyrighted content when activated by specific triggerprompts. These findings underline potential pitfalls in the prevailingcopyright protection strategies and underscore the necessity for increasedscrutiny and preventative measures against the misuse of DMs.
{{< /details >}}

>**_2024-01-04_**

[**DeepTaster: Adversarial Perturbation-Based Fingerprinting to Identify Proprietary Dataset Use in Deep Neural Networks**](http://arxiv.org/abs/2211.13535v2)

*Seonhye Park, Alsharif Abuadbba, Shuo Wang, Kristen Moore, Yansong Gao, Hyoungshick Kim, Surya Nepal*

{{< details "abstract" >}} abstract: Training deep neural networks (DNNs) requires large datasets and powerfulcomputing resources, which has led some owners to restrict redistributionwithout permission. Watermarking techniques that embed confidential data intoDNNs have been used to protect ownership, but these can degrade modelperformance and are vulnerable to watermark removal attacks. Recently,DeepJudge was introduced as an alternative approach to measuring the similaritybetween a suspect and a victim model. While DeepJudge shows promise inaddressing the shortcomings of watermarking, it primarily addresses situationswhere the suspect model copies the victim's architecture. In this study, weintroduce DeepTaster, a novel DNN fingerprinting technique, to addressscenarios where a victim's data is unlawfully used to build a suspect model.DeepTaster can effectively identify such DNN model theft attacks, even when thesuspect model's architecture deviates from the victim's. To accomplish this,DeepTaster generates adversarial images with perturbations, transforms theminto the Fourier frequency domain, and uses these transformed images toidentify the dataset used in a suspect model. The underlying premise is thatadversarial images can capture the unique characteristics of DNNs built with aspecific dataset. To demonstrate the effectiveness of DeepTaster, we evaluatedthe effectiveness of DeepTaster by assessing its detection accuracy on threedatasets (CIFAR10, MNIST, and Tiny-ImageNet) across three model architectures(ResNet18, VGG16, and DenseNet161). We conducted experiments under variousattack scenarios, including transfer learning, pruning, fine-tuning, and dataaugmentation. Specifically, in the Multi-Architecture Attack scenario,DeepTaster was able to identify all the stolen cases across all datasets, whileDeepJudge failed to detect any of the cases.
{{< /details >}}

>**_2023-12-28_**

[**AI Content Self-Detection for Transformer-based Large Language Models**](http://arxiv.org/abs/2312.17289v1)

*Antônio Junior Alves Caiado, Michael Hahsler*

{{< details "abstract" >}} abstract: $ $The usage of generative artificial intelligence (AI) tools based on largelanguage models, including ChatGPT, Bard, and Claude, for text generation hasmany exciting applications with the potential for phenomenal productivitygains. One issue is authorship attribution when using AI tools. This isespecially important in an academic setting where the inappropriate use ofgenerative AI tools may hinder student learning or stifle research by creatinga large amount of automatically generated derivative work. Existing plagiarismdetection systems can trace the source of submitted text but are not yetequipped with methods to accurately detect AI-generated text. This paperintroduces the idea of direct origin detection and evaluates whether generativeAI systems can recognize their output and distinguish it from human-writtentexts. We argue why current transformer-based models may be able to self-detecttheir own generated text and perform a small empirical study using zero-shotlearning to investigate if that is the case. Results reveal varyingcapabilities of AI systems to identify their generated text. Google's Bardmodel exhibits the largest capability of self-detection with an accuracy of94\%, followed by OpenAI's ChatGPT with 83\%. On the other hand, Anthropic'sClaude model seems to be not able to self-detect.
{{< /details >}}

[**The Utility of Feature Reuse: Transfer Learning in Data-Starved Regimes**](http://arxiv.org/abs/2003.04117v2)

*Rashik Shadman, M. G. Sarwar Murshed, Edward Verenich, Alvaro Velasquez, Faraz Hussain*

{{< details "abstract" >}} abstract: The use of transfer learning with deep neural networks has increasinglybecome widespread for deploying well-tested computer vision systems to newerdomains, especially those with limited datasets. We describe a transferlearning use case for a domain with a data-starved regime, having fewer than100 labeled target samples. We evaluate the effectiveness of convolutionalfeature extraction and fine-tuning of overparameterized models with respect tothe size of target training data, as well as their generalization performanceon data with covariate shift, or out-of-distribution (OOD) data. Ourexperiments demonstrate that both overparameterization and feature reusecontribute to the successful application of transfer learning in training imageclassifiers in data-starved regimes. We provide visual explanations to supportour findings and conclude that transfer learning enhances the performance ofCNN architectures in data-starved regimes.
{{< /details >}}

>**_2023-12-21_**

[**Data Transformation to Construct a Dataset for Generating Entity-Relationship Model from Natural Language**](http://arxiv.org/abs/2312.13694v1)

*Zhenwen Li, Jian-Guang Lou, Tao Xie*

{{< details "abstract" >}} abstract: In order to reduce the manual cost of designing ER models, recent approacheshave been proposed to address the task of NL2ERM, i.e., automaticallygenerating entity-relationship (ER) models from natural language (NL)utterances such as software requirements. These approaches are typicallyrule-based ones, which rely on rigid heuristic rules; these approaches cannotgeneralize well to various linguistic ways of describing the same requirement.Despite having better generalization capability than rule-based approaches,deep-learning-based models are lacking for NL2ERM due to lacking a large-scaledataset. To address this issue, in this paper, we report our insight that thereexists a high similarity between the task of NL2ERM and the increasinglypopular task of text-to-SQL, and propose a data transformation algorithm thattransforms the existing data of text-to-SQL into the data of NL2ERM. We applyour data transformation algorithm on Spider, one of the most populartext-to-SQL datasets, and we also collect some data entries with different NLtypes, to obtain a large-scale NL2ERM dataset. Because NL2ERM can be seen as aspecial information extraction (IE) task, we train two state-of-the-art IEmodels on our dataset. The experimental results show that both the two modelsachieve high performance and outperform existing baselines.
{{< /details >}}

>**_2023-12-16_**

[**CoCoGen: Physically-Consistent and Conditioned Score-based Generative Models for Forward and Inverse Problems**](http://arxiv.org/abs/2312.10527v1)

*Christian Jacobsen, Yilin Zhuang, Karthik Duraisamy*

{{< details "abstract" >}} abstract: Recent advances in generative artificial intelligence have had a significantimpact on diverse domains spanning computer vision, natural languageprocessing, and drug discovery. This work extends the reach of generativemodels into physical problem domains, particularly addressing the efficientenforcement of physical laws and conditioning for forward and inverse problemsinvolving partial differential equations (PDEs). Our work introduces two keycontributions: firstly, we present an efficient approach to promote consistencywith the underlying PDE. By incorporating discretized information intoscore-based generative models, our method generates samples closely alignedwith the true data distribution, showcasing residuals comparable to datagenerated through conventional PDE solvers, significantly enhancing fidelity.Secondly, we showcase the potential and versatility of score-based generativemodels in various physics tasks, specifically highlighting surrogate modelingas well as probabilistic field reconstruction and inversion from sparsemeasurements. A robust foundation is laid by designing unconditionalscore-based generative models that utilize reversible probability flow ordinarydifferential equations. Leveraging conditional models that require minimaltraining, we illustrate their flexibility when combined with a frozenunconditional model. These conditional models generate PDE solutions byincorporating parameters, macroscopic quantities, or partial field measurementsas guidance. The results illustrate the inherent flexibility of score-basedgenerative models and explore the synergy between unconditional score-basedgenerative models and the present physically-consistent sampling approach,emphasizing the power and flexibility in solving for and inverting physicalfields governed by differential equations, and in other scientific machinelearning tasks.
{{< /details >}}

>**_2023-12-11_**

[**Quantum-enhanced neural networks in the neural tangent kernel framework**](http://arxiv.org/abs/2109.03786v3)

*Kouhei Nakaji, Hiroyuki Tezuka, Naoki Yamamoto*

{{< details "abstract" >}} abstract: Recently, quantum neural networks or quantum-classical neural networks (qcNN)have been actively studied, as a possible alternative to the conventionalclassical neural network (cNN), but their practical andtheoretically-guaranteed performance is still to be investigated. In contrast,cNNs and especially deep cNNs, have acquired several solid theoretical basis;one of those basis is the neural tangent kernel (NTK) theory, which cansuccessfully explain the mechanism of various desirable properties of cNNs,particularly the global convergence in the training process. In this paper, westudy a class of qcNN composed of a quantum data-encoder followed by a cNN. Thequantum part is randomly initialized according to unitary 2-designs, which isan effective feature extraction process for quantum states, and the classicalpart is also randomly initialized according to Gaussian distributions; then, inthe NTK regime where the number of nodes of the cNN becomes infinitely large,the output of the entire qcNN becomes a nonlinear function of the so-calledprojected quantum kernel. That is, the NTK theory is used to construct aneffective quantum kernel, which is in general nontrivial to design. Moreover,NTK defined for the qcNN is identical to the covariance matrix of a Gaussianprocess, which allows us to analytically study the learning process. Theseproperties are investigated in thorough numerical experiments; particularly, wedemonstrate that the qcNN shows a clear advantage over fully classical NNs andqNNs for the problem of learning the quantum data-generating process.
{{< /details >}}

[**Performance-lossless Black-box Model Watermarking**](http://arxiv.org/abs/2312.06488v1)

*Na Zhao, Kejiang Chen, Weiming Zhang, Nenghai Yu*

{{< details "abstract" >}} abstract: With the development of deep learning, high-value and high-cost models havebecome valuable assets, and related intellectual property protectiontechnologies have become a hot topic. However, existing model watermarking workin black-box scenarios mainly originates from training-based backdoor methods,which probably degrade original task performance. To address this, we propose abranch backdoor-based model watermarking protocol to protect model intellectualproperty, where a construction based on a message authentication scheme isadopted as the branch indicator. We prove the lossless performance of theprotocol by reduction. Taking the language generation task as an instance, weshow the effectiveness of the proposed protocol.
{{< /details >}}

>**_2023-12-09_**

[**I-AI: A Controllable & Interpretable AI System for Decoding Radiologists' Intense Focus for Accurate CXR Diagnoses**](http://arxiv.org/abs/2309.13550v4)

*Trong Thang Pham, Jacob Brecheisen, Anh Nguyen, Hien Nguyen, Ngan Le*

{{< details "abstract" >}} abstract: In the field of chest X-ray (CXR) diagnosis, existing works often focussolely on determining where a radiologist looks, typically through tasks suchas detection, segmentation, or classification. However, these approaches areoften designed as black-box models, lacking interpretability. In this paper, weintroduce Interpretable Artificial Intelligence (I-AI) a novel and unifiedcontrollable interpretable pipeline for decoding the intense focus ofradiologists in CXR diagnosis. Our I-AI addresses three key questions: where aradiologist looks, how long they focus on specific areas, and what findingsthey diagnose. By capturing the intensity of the radiologist's gaze, we providea unified solution that offers insights into the cognitive process underlyingradiological interpretation. Unlike current methods that rely on black-boxmachine learning models, which can be prone to extracting erroneous informationfrom the entire input image during the diagnosis process, we tackle this issueby effectively masking out irrelevant information. Our proposed I-AI leveragesa vision-language model, allowing for precise control over the interpretationprocess while ensuring the exclusion of irrelevant features. To train our I-AImodel, we utilize an eye gaze dataset to extract anatomical gaze informationand generate ground truth heatmaps. Through extensive experimentation, wedemonstrate the efficacy of our method. We showcase that the attentionheatmaps, designed to mimic radiologists' focus, encode sufficient and relevantinformation, enabling accurate classification tasks using only a portion ofCXR. The code, checkpoints, and data are at https://github.com/UARK-AICV/IAI
{{< /details >}}

>**_2023-12-07_**

[**Defense against ML-based Power Side-channel Attacks on DNN Accelerators with Adversarial Attacks**](http://arxiv.org/abs/2312.04035v1)

*Xiaobei Yan, Chip Hong Chang, Tianwei Zhang*

{{< details "abstract" >}} abstract: Artificial Intelligence (AI) hardware accelerators have been widely adoptedto enhance the efficiency of deep learning applications. However, they alsoraise security concerns regarding their vulnerability to power side-channelattacks (SCA). In these attacks, the adversary exploits unintendedcommunication channels to infer sensitive information processed by theaccelerator, posing significant privacy and copyright risks to the models.Advanced machine learning algorithms are further employed to facilitate theside-channel analysis and exacerbate the privacy issue of AI accelerators.Traditional defense strategies naively inject execution noise to the runtime ofAI models, which inevitably introduce large overheads.  In this paper, we present AIAShield, a novel defense methodology to safeguardFPGA-based AI accelerators and mitigate model extraction threats viapower-based SCAs. The key insight of AIAShield is to leverage the prominentadversarial attack technique from the machine learning community to craftdelicate noise, which can significantly obfuscate the adversary's side-channelobservation while incurring minimal overhead to the execution of the protectedmodel. At the hardware level, we design a new module based on ring oscillatorsto achieve fine-grained noise generation. At the algorithm level, we repurposeNeural Architecture Search to worsen the adversary's extraction results.Extensive experiments on the Nvidia Deep Learning Accelerator (NVDLA)demonstrate that AIAShield outperforms existing solutions with excellenttransferability.
{{< /details >}}

>**_2023-12-04_**

[**A Generative Self-Supervised Framework using Functional Connectivity in fMRI Data**](http://arxiv.org/abs/2312.01994v1)

*Jungwon Choi, Seongho Keum, EungGu Yun, Byung-Hoon Kim, Juho Lee*

{{< details "abstract" >}} abstract: Deep neural networks trained on Functional Connectivity (FC) networksextracted from functional Magnetic Resonance Imaging (fMRI) data have gainedpopularity due to the increasing availability of data and advances in modelarchitectures, including Graph Neural Network (GNN). Recent research on theapplication of GNN to FC suggests that exploiting the time-varying propertiesof the FC could significantly improve the accuracy and interpretability of themodel prediction. However, the high cost of acquiring high-quality fMRI dataand corresponding phenotypic labels poses a hurdle to their application inreal-world settings, such that a model na\"ively trained in a supervisedfashion can suffer from insufficient performance or a lack of generalization ona small number of data. In addition, most Self-Supervised Learning (SSL)approaches for GNNs to date adopt a contrastive strategy, which tends to loseappropriate semantic information when the graph structure is perturbed or doesnot leverage both spatial and temporal information simultaneously. In light ofthese challenges, we propose a generative SSL approach that is tailored toeffectively harness spatio-temporal information within dynamic FC. Ourempirical results, experimented with large-scale (>50,000) fMRI datasets,demonstrate that our approach learns valuable representations and enables theconstruction of accurate and robust models when fine-tuned for downstreamtasks.
{{< /details >}}

>**_2023-12-03_**

[**Deep Learning Assisted Raman Spectroscopy for Rapid Identification of 2D Materials**](http://arxiv.org/abs/2312.01389v1)

*Yaping Qi, Dan Hu, Zhenping Wu, Ming Zheng, Guanghui Cheng, Yucheng Jiang, Yong P. Chen*

{{< details "abstract" >}} abstract: Two-dimensional (2D) materials have attracted extensive attention due totheir unique characteristics and application potentials. Raman spectroscopy, asa rapid and non-destructive probe, exhibits distinct features and holds notableadvantages in the structural characterization of 2D materials. However,traditional data analysis of Raman spectra relies on manual interpretation andfeature extraction, which are both time-consuming and subjective. In this work,we employ deep learning techniques, including classificatory and generativedeep learning, to assist the analysis of Raman spectra of typical 2D materials.For the limited and unevenly distributed Raman spectral data, we propose a dataaugmentation approach based on Denoising Diffusion Probabilistic Models (DDPM)to augment the training dataset and construct a four-layer Convolutional NeuralNetwork (CNN) for 2D material classification. Experimental results illustratethe effectiveness of DDPM in addressing data limitations and significantlyimproved classification model performance. The proposed DDPM-CNN method showshigh reliability, with 100%classification accuracy. Our work demonstrates thepracticality of deep learning-assisted Raman spectroscopy for high-precisionrecognition and classification of 2D materials, offering a promising avenue forrapid and automated spectral analysis.
{{< /details >}}

>**_2023-12-01_**

[**Symplectic Structure-Aware Hamiltonian (Graph) Embeddings**](http://arxiv.org/abs/2309.04885v3)

*Jiaxu Liu, Xinping Yi, Tianle Zhang, Xiaowei Huang*

{{< details "abstract" >}} abstract: In traditional Graph Neural Networks (GNNs), the assumption of a fixedembedding manifold often limits their adaptability to diverse graph geometries.Recently, Hamiltonian system-inspired GNNs have been proposed to address thedynamic nature of such embeddings by incorporating physical laws into nodefeature updates. We present Symplectic Structure-Aware Hamiltonian GNN(SAH-GNN), a novel approach that generalizes Hamiltonian dynamics for moreflexible node feature updates. Unlike existing Hamiltonian approaches, SAH-GNNemploys Riemannian optimization on the symplectic Stiefel manifold toadaptively learn the underlying symplectic structure, circumventing thelimitations of existing Hamiltonian GNNs that rely on a pre-defined form ofstandard symplectic structure. This innovation allows SAH-GNN to automaticallyadapt to various graph datasets without extensive hyperparameter tuning.Moreover, it conserves energy during training meaning the implicit Hamiltoniansystem is physically meaningful. Finally, we empirically validate SAH-GNN'ssuperiority and adaptability in node classification tasks across multiple typesof graph datasets.
{{< /details >}}

[**Generalized Label-Efficient 3D Scene Parsing via Hierarchical Feature Aligned Pre-Training and Region-Aware Fine-tuning**](http://arxiv.org/abs/2312.00663v1)

*Kangcheng Liu, Yong-Jin Liu, Kai Tang, Ming Liu, Baoquan Chen*

{{< details "abstract" >}} abstract: Deep neural network models have achieved remarkable progress in 3D sceneunderstanding while trained in the closed-set setting and with full labels.However, the major bottleneck for current 3D recognition approaches is thatthey do not have the capacity to recognize any unseen novel classes beyond thetraining categories in diverse kinds of real-world applications. In themeantime, current state-of-the-art 3D scene understanding approaches primarilyrequire high-quality labels to train neural networks, which merely perform wellin a fully supervised manner. This work presents a generalized and simpleframework for dealing with 3D scene understanding when the labeled scenes arequite limited. To extract knowledge for novel categories from the pre-trainedvision-language models, we propose a hierarchical feature-aligned pre-trainingand knowledge distillation strategy to extract and distill meaningfulinformation from large-scale vision-language models, which helps benefit theopen-vocabulary scene understanding tasks. To leverage the boundaryinformation, we propose a novel energy-based loss with boundary awarenessbenefiting from the region-level boundary predictions. To encourage latentinstance discrimination and to guarantee efficiency, we propose theunsupervised region-level semantic contrastive learning scheme for pointclouds, using confident predictions of the neural network to discriminate theintermediate feature embeddings at multiple stages. Extensive experiments withboth indoor and outdoor scenes demonstrated the effectiveness of our approachin both data-efficient learning and open-world few-shot learning. All codes,models, and data are made publicly available at:https://drive.google.com/drive/folders/1M58V-PtR8DBEwD296zJkNg_m2qq-MTAP?usp=sharing.
{{< /details >}}

[**The Efficiency Spectrum of Large Language Models: An Algorithmic Survey**](http://arxiv.org/abs/2312.00678v1)

*Tianyu Ding, Tianyi Chen, Haidong Zhu, Jiachen Jiang, Yiqi Zhong, Jinxin Zhou, Guangzhi Wang, Zhihui Zhu, Ilya Zharkov, Luming Liang*

{{< details "abstract" >}} abstract: The rapid growth of Large Language Models (LLMs) has been a driving force intransforming various domains, reshaping the artificial general intelligencelandscape. However, the increasing computational and memory demands of thesemodels present substantial challenges, hindering both academic research andpractical applications. To address these issues, a wide array of methods,including both algorithmic and hardware solutions, have been developed toenhance the efficiency of LLMs. This survey delivers a comprehensive review ofalgorithmic advancements aimed at improving LLM efficiency. Unlike othersurveys that typically focus on specific areas such as training or modelcompression, this paper examines the multi-faceted dimensions of efficiencyessential for the end-to-end algorithmic development of LLMs. Specifically, itcovers various topics related to efficiency, including scaling laws, datautilization, architectural innovations, training and tuning strategies, andinference techniques. This paper aims to serve as a valuable resource forresearchers and practitioners, laying the groundwork for future innovations inthis critical research area. Our repository of relevant references ismaintained at url{https://github.com/tding1/Efficient-LLM-Survey}.
{{< /details >}}

>**_2023-11-30_**

[**Situating the social issues of image generation models in the model life cycle: a sociotechnical approach**](http://arxiv.org/abs/2311.18345v1)

*Amelia Katirai, Noa Garcia, Kazuki Ide, Yuta Nakashima, Atsuo Kishimoto*

{{< details "abstract" >}} abstract: The race to develop image generation models is intensifying, with a rapidincrease in the number of text-to-image models available. This is coupled withgrowing public awareness of these technologies. Though other generative AImodels--notably, large language models--have received recent critical attentionfor the social and other non-technical issues they raise, there has beenrelatively little comparable examination of image generation models. This paperreports on a novel, comprehensive categorization of the social issuesassociated with image generation models. At the intersection of machinelearning and the social sciences, we report the results of a survey of theliterature, identifying seven issue clusters arising from image generationmodels: data issues, intellectual property, bias, privacy, and the impacts onthe informational, cultural, and natural environments. We situate these socialissues in the model life cycle, to aid in considering where potential issuesarise, and mitigation may be needed. We then compare these issue clusters withwhat has been reported for large language models. Ultimately, we argue that therisks posed by image generation models are comparable in severity to the risksposed by large language models, and that the social impact of image generationmodels must be urgently considered.
{{< /details >}}

>**_2023-11-29_**

[**Towards out-of-distribution generalization in large-scale astronomical surveys: robust networks learn similar representations**](http://arxiv.org/abs/2311.18007v1)

*Yash Gondhalekar, Sultan Hassan, Naomi Saphra, Sambatra Andrianomena*

{{< details "abstract" >}} abstract: The generalization of machine learning (ML) models to out-of-distribution(OOD) examples remains a key challenge in extracting information from upcomingastronomical surveys. Interpretability approaches are a natural way to gaininsights into the OOD generalization problem. We use Centered Kernel Alignment(CKA), a similarity measure metric of neural network representations, toexamine the relationship between representation similarity and performance ofpre-trained Convolutional Neural Networks (CNNs) on the CAMELS MultifieldDataset. We find that when models are robust to a distribution shift, theyproduce substantially different representations across their layers on OODdata. However, when they fail to generalize, these representations change lessfrom layer to layer on OOD data. We discuss the potential application ofsimilarity representation in guiding model design, training strategy, andmitigating the OOD problem by incorporating CKA as an inductive bias duringtraining.
{{< /details >}}

[**Intellectual Property Protection of Diffusion Models via the Watermark Diffusion Process**](http://arxiv.org/abs/2306.03436v2)

*Sen Peng, Yufei Chen, Cong Wang, Xiaohua Jia*

{{< details "abstract" >}} abstract: Diffusion models have rapidly become a vital part of deep generativearchitectures, given today's increasing demands. Obtaining large,high-performance diffusion models demands significant resources, highlightingtheir importance as intellectual property worth protecting. However, existingwatermarking techniques for ownership verification are insufficient whenapplied to diffusion models. Very recent research in watermarking diffusionmodels either exposes watermarks during task generation, which harms theimperceptibility, or is developed for conditional diffusion models that requireprompts to trigger the watermark. This paper introduces WDM, a novelwatermarking solution for diffusion models without imprinting the watermarkduring task generation. It involves training a model to concurrently learn aWatermark Diffusion Process (WDP) for embedding watermarks alongside thestandard diffusion process for task generation. We provide a detailedtheoretical analysis of WDP training and sampling, relating it to a shiftedGaussian diffusion process via the same reverse noise. Extensive experimentsare conducted to validate the effectiveness and robustness of our approach invarious trigger and watermark data configurations.
{{< /details >}}

>**_2023-11-28_**

[**PCPT and ACPT: Copyright Protection and Traceability Scheme for DNN Models**](http://arxiv.org/abs/2206.02541v2)

*Xuefeng Fan, Dahao Fu, Hangyu Gui, Xinpeng Zhang, Xiaoyi Zhou*

{{< details "abstract" >}} abstract: Deep neural networks (DNNs) have achieved tremendous success in artificialintelligence (AI) fields. However, DNN models can be easily illegally copied,redistributed, or abused by criminals, seriously damaging the interests ofmodel inventors. The copyright protection of DNN models by neural networkwatermarking has been studied, but the establishment of a traceabilitymechanism for determining the authorized users of a leaked model is a newproblem driven by the demand for AI services. Because the existing traceabilitymechanisms are used for models without watermarks, a small number offalse-positives are generated. Existing black-box active protection schemeshave loose authorization control and are vulnerable to forgery attacks.Therefore, based on the idea of black-box neural network watermarking with thevideo framing and image perceptual hash algorithm, a passive copyrightprotection and traceability framework PCPT is proposed that uses an additionalclass of DNN models, improving the existing traceability mechanism that yieldsa small number of false-positives. Based on an authorization control strategyand image perceptual hash algorithm, a DNN model active copyright protectionand traceability framework ACPT is proposed. This framework uses theauthorization control center constructed by the detector and verifier. Thisapproach realizes stricter authorization control, which establishes a strongconnection between users and model owners, improves the framework security, andsupports traceability verification.
{{< /details >}}

[**Scalable Extraction of Training Data from (Production) Language Models**](http://arxiv.org/abs/2311.17035v1)

*Milad Nasr, Nicholas Carlini, Jonathan Hayase, Matthew Jagielski, A. Feder Cooper, Daphne Ippolito, Christopher A. Choquette-Choo, Eric Wallace, Florian Tramèr, Katherine Lee*

{{< details "abstract" >}} abstract: This paper studies extractable memorization: training data that an adversarycan efficiently extract by querying a machine learning model without priorknowledge of the training dataset. We show an adversary can extract gigabytesof training data from open-source language models like Pythia or GPT-Neo,semi-open models like LLaMA or Falcon, and closed models like ChatGPT. Existingtechniques from the literature suffice to attack unaligned models; in order toattack the aligned ChatGPT, we develop a new divergence attack that causes themodel to diverge from its chatbot-style generations and emit training data at arate 150x higher than when behaving properly. Our methods show practicalattacks can recover far more data than previously thought, and reveal thatcurrent alignment techniques do not eliminate memorization.
{{< /details >}}

>**_2023-11-27_**

[**Tokenized Model: A Blockchain-Empowered Decentralized Model Ownership Verification Platform**](http://arxiv.org/abs/2312.00048v1)

*Yihao Li, Yanyi Lai, Tianchi Liao, Chuan Chen, Zibin Zheng*

{{< details "abstract" >}} abstract: With the development of practical deep learning models like generative AI,their excellent performance has brought huge economic value. For instance,ChatGPT has attracted more than 100 million users in three months. Since themodel training requires a lot of data and computing power, a well-performingdeep learning model is behind a huge effort and cost. Facing various modelattacks, unauthorized use and abuse from the network that threaten theinterests of model owners, in addition to considering legal and otheradministrative measures, it is equally important to protect the model'scopyright from the technical means. By using the model watermarking technology,we point out the possibility of building a unified platform for model ownershipverification. Given the application history of blockchain in copyrightverification and the drawbacks of a centralized third-party, this paperconsiders combining model watermarking technology and blockchain to build aunified model copyright protection platform. By a new solution we calledTokenized Model, it protects the model's copyright by reliable ownership recordand verification mechanism. It also promotes the financial value of model byconstructing the model's transaction process and contribution shares of amodel. In the typical case study, we also study the various performance underusual scenario to verify the effectiveness of this platform.
{{< /details >}}

>**_2023-11-22_**

[**RemovalNet: DNN Fingerprint Removal Attacks**](http://arxiv.org/abs/2308.12319v3)

*Hongwei Yao, Zheng Li, Kunzhe Huang, Jian Lou, Zhan Qin, Kui Ren*

{{< details "abstract" >}} abstract: With the performance of deep neural networks (DNNs) remarkably improving,DNNs have been widely used in many areas. Consequently, the DNN model hasbecome a valuable asset, and its intellectual property is safeguarded byownership verification techniques (e.g., DNN fingerprinting). However, thefeasibility of the DNN fingerprint removal attack and its potential influenceremains an open problem. In this paper, we perform the first comprehensiveinvestigation of DNN fingerprint removal attacks. Generally, the knowledgecontained in a DNN model can be categorized into general semantic andfingerprint-specific knowledge. To this end, we propose a min-max bileveloptimization-based DNN fingerprint removal attack named RemovalNet, to evademodel ownership verification. The lower-level optimization is designed toremove fingerprint-specific knowledge. While in the upper-level optimization,we distill the victim model's general semantic knowledge to maintain thesurrogate model's performance. We conduct extensive experiments to evaluate thefidelity, effectiveness, and efficiency of the RemovalNet against four advanceddefense methods on six metrics. The empirical results demonstrate that (1) theRemovalNet is effective. After our DNN fingerprint removal attack, the modeldistance between the target and surrogate models is x100 times higher than thatof the baseline attacks, (2) the RemovalNet is efficient. It uses only 0.2%(400 samples) of the substitute dataset and 1,000 iterations to conduct ourattack. Besides, compared with advanced model stealing attacks, the RemovalNetsaves nearly 85% of computational resources at most, (3) the RemovalNetachieves high fidelity that the created surrogate model maintains high accuracyafter the DNN fingerprint removal process. Our code is available at:https://github.com/grasses/RemovalNet.
{{< /details >}}

>**_2023-11-21_**

[**Domain Adaptive Graph Neural Networks for Constraining Cosmological Parameters Across Multiple Data Sets**](http://arxiv.org/abs/2311.01588v2)

*Andrea Roncoli, Aleksandra Ćiprijanović, Maggie Voetberg, Francisco Villaescusa-Navarro, Brian Nord*

{{< details "abstract" >}} abstract: Deep learning models have been shown to outperform methods that rely onsummary statistics, like the power spectrum, in extracting information fromcomplex cosmological data sets. However, due to differences in the subgridphysics implementation and numerical approximations across different simulationsuites, models trained on data from one cosmological simulation show a drop inperformance when tested on another. Similarly, models trained on any of thesimulations would also likely experience a drop in performance when applied toobservational data. Training on data from two different suites of the CAMELShydrodynamic cosmological simulations, we examine the generalizationcapabilities of Domain Adaptive Graph Neural Networks (DA-GNNs). By utilizingGNNs, we capitalize on their capacity to capture structured scale-freecosmological information from galaxy distributions. Moreover, by includingunsupervised domain adaptation via Maximum Mean Discrepancy (MMD), we enableour models to extract domain-invariant features. We demonstrate that DA-GNNachieves higher accuracy and robustness on cross-dataset tasks (up to $28\%$better relative error and up to almost an order of magnitude better $\chi^2$).Using data visualizations, we show the effects of domain adaptation on properlatent space data alignment. This shows that DA-GNNs are a promising method forextracting domain-independent cosmological information, a vital step towardrobust deep learning for real cosmic survey data.
{{< /details >}}

>**_2023-11-17_**

[**GAN-supervised Seismic Data Reconstruction: An Enhanced-Learning for Improved Generalization**](http://arxiv.org/abs/2311.10910v1)

*Paul Goyes-Penafiel, Leon Suarez-Rodriguez, Claudia Correa, Henry Arguello*

{{< details "abstract" >}} abstract: Seismic data interpolation plays a crucial role in subsurface imaging,enabling accurate analysis and interpretation throughout the seismic processingworkflow. Despite the widespread exploration of deep supervised learningmethods for seismic data reconstruction, several challenges still remain open.Particularly, the requirement of extensive training data and poor domaingeneralization due to the seismic survey's variability poses significantissues. To overcome these limitations, this paper introduces adeep-learning-based seismic data reconstruction approach that leverages dataredundancy. This method involves a two-stage training process. First, anadversarial generative network (GAN) is trained using synthetic seismic data,enabling the extraction and learning of their primary and local seismiccharacteristics. Second, a reconstruction network is trained with syntheticdata generated by the GAN, which dynamically adjusts the noise and distortionlevel at each epoch to promote feature diversity. This approach enhances thegeneralization capabilities of the reconstruction network by allowing controlover the generation of seismic patterns from the latent space of the GAN,thereby reducing the dependency on large seismic databases. Experimentalresults on field and synthetic seismic datasets both pre-stack and post-stackshow that the proposed method outperforms the baseline supervised learning andunsupervised approaches such as deep seismic prior and internal learning, by upto 8 dB of PSNR.
{{< /details >}}

>**_2023-11-07_**

[**Using Sum-Product Networks to Assess Uncertainty in Deep Active Learning**](http://arxiv.org/abs/2206.09798v2)

*Mohamadsadegh Khosravani, Sandra Zilles*

{{< details "abstract" >}} abstract: The success of deep active learning hinges on the choice of an effectiveacquisition function, which ranks not yet labeled data points according totheir expected informativeness. Many acquisition functions are (partly) basedon the uncertainty that the current model has about the class label of a point,yet there is no generally agreed upon strategy for computing such uncertainty.This paper proposes a new and very simple approach to computing uncertainty indeep active learning with a Convolutional Neural Network (CNN). The main ideais to use the feature representation extracted by the CNN as data for traininga Sum-Product Network (SPN). Since SPNs are typically used for estimating thedistribution of a dataset, they are well suited to the task of estimating classprobabilities that can be used directly by standard acquisition functions suchas max entropy and variational ratio. The effectiveness of our method isdemonstrated in an experimental study on several standard benchmark datasetsfor image classification, where we compare it to various state-of-the-artmethods for assessing uncertainty in deep active learning.
{{< /details >}}

>**_2023-11-05_**

[**CT-GAT: Cross-Task Generative Adversarial Attack based on Transferability**](http://arxiv.org/abs/2310.14265v2)

*Minxuan Lv, Chengwei Dai, Kun Li, Wei Zhou, Songlin Hu*

{{< details "abstract" >}} abstract: Neural network models are vulnerable to adversarial examples, and adversarialtransferability further increases the risk of adversarial attacks. Currentmethods based on transferability often rely on substitute models, which can beimpractical and costly in real-world scenarios due to the unavailability oftraining data and the victim model's structural details. In this paper, wepropose a novel approach that directly constructs adversarial examples byextracting transferable features across various tasks. Our key insight is thatadversarial transferability can extend across different tasks. Specifically, wetrain a sequence-to-sequence generative model named CT-GAT using adversarialsample data collected from multiple tasks to acquire universal adversarialfeatures and generate adversarial examples for different tasks. We conductexperiments on ten distinct datasets, and the results demonstrate that ourmethod achieves superior attack performance with small cost.
{{< /details >}}

>**_2023-11-03_**

[**AntifakePrompt: Prompt-Tuned Vision-Language Models are Fake Image Detectors**](http://arxiv.org/abs/2310.17419v2)

*You-Ming Chang, Chen Yeh, Wei-Chen Chiu, Ning Yu*

{{< details "abstract" >}} abstract: Deep generative models can create remarkably photorealistic fake images whileraising concerns about misinformation and copyright infringement, known asdeepfake threats. Deepfake detection technique is developed to distinguishbetween real and fake images, where the existing methods typically trainclassifiers in the image domain or various feature domains. However, thegeneralizability of deepfake detection against emerging and more advancedgenerative models remains challenging. In this paper, inspired by the zero-shotadvantages of Vision-Language Models (VLMs), we propose a novel approach usingVLMs (e.g. InstructBLIP) and prompt tuning techniques to improve the deepfakedetection accuracy over unseen data. We formulate deepfake detection as avisual question answering problem, and tune soft prompts for InstructBLIP todistinguish a query image is real or fake. We conduct full-spectrum experimentson datasets from 3 held-in and 13 held-out generative models, covering moderntext-to-image generation, image editing and image attacks. Results demonstratethat (1) the deepfake detection accuracy can be significantly and consistentlyimproved (from 54.6% to 91.31%, in average accuracy over unseen data) usingpretrained vision-language models with prompt tuning; (2) our superiorperformance is at less cost of trainable parameters, resulting in an effectiveand efficient solution for deepfake detection. Code and models can be found athttps://github.com/nctu-eva-lab/AntifakePrompt.
{{< /details >}}

[**3-Dimensional residual neural architecture search for ultrasonic defect detection**](http://arxiv.org/abs/2311.01867v1)

*Shaun McKnight, Christopher MacKinnon, S. Gareth Pierce, Ehsan Mohseni, Vedran Tunukovic, Charles N. MacLeod, Randika K. W. Vithanage, Tom OHare*

{{< details "abstract" >}} abstract: This study presents a deep learning methodology using 3-dimensional (3D)convolutional neural networks to detect defects in carbon fiber reinforcedpolymer composites through volumetric ultrasonic testing data. Acquiring largeamounts of ultrasonic training data experimentally is expensive andtime-consuming. To address this issue, a synthetic data generation method wasextended to incorporate volumetric data. By preserving the complete volumetricdata, complex preprocessing is reduced, and the model can utilize spatial andtemporal information that is lost during imaging. This enables the model toutilise important features that might be overlooked otherwise. The performanceof three architectures were compared. The first two architectures werehand-designed to address the high aspect ratios between the spatial andtemporal dimensions. The first architecture reduced dimensionality in the timedomain and used cubed kernels for feature extraction. The second architectureused cuboidal kernels to account for the large aspect ratios. The evaluationincluded comparing the use of max pooling and convolutional layers fordimensionality reduction, with the fully convolutional layers consistentlyoutperforming the models using max pooling. The third architecture wasgenerated through neural architecture search from a modified 3D Residual NeuralNetwork (ResNet) search space. Additionally, domain-specific augmentationmethods were incorporated during training, resulting in significantimprovements in model performance for all architectures. The mean accuracyimprovements ranged from 8.2% to 22.4%. The best performing models achievedmean accuracies of 91.8%, 92.2%, and 100% for the reduction, constant, anddiscovered architectures, respectively. Whilst maintaining a model size smallerthan most 2-dimensional (2D) ResNets.
{{< /details >}}

>**_2023-11-02_**

[**Sequential Subset Matching for Dataset Distillation**](http://arxiv.org/abs/2311.01570v1)

*Jiawei Du, Qin Shi, Joey Tianyi Zhou*

{{< details "abstract" >}} abstract: Dataset distillation is a newly emerging task that synthesizes a small-sizedataset used in training deep neural networks (DNNs) for reducing data storageand model training costs. The synthetic datasets are expected to capture theessence of the knowledge contained in real-world datasets such that the formeryields a similar performance as the latter. Recent advancements in distillationmethods have produced notable improvements in generating synthetic datasets.However, current state-of-the-art methods treat the entire synthetic dataset asa unified entity and optimize each synthetic instance equally. This staticoptimization approach may lead to performance degradation in datasetdistillation. Specifically, we argue that static optimization can give rise toa coupling issue within the synthetic data, particularly when a larger amountof synthetic data is being optimized. This coupling issue, in turn, leads tothe failure of the distilled dataset to extract the high-level features learnedby the deep neural network (DNN) in the latter epochs.  In this study, we propose a new dataset distillation strategy calledSequential Subset Matching (SeqMatch), which tackles this problem by adaptivelyoptimizing the synthetic data to encourage sequential acquisition of knowledgeduring dataset distillation. Our analysis indicates that SeqMatch effectivelyaddresses the coupling issue by sequentially generating the syntheticinstances, thereby enhancing its performance significantly. Our proposedSeqMatch outperforms state-of-the-art methods in various datasets, includingSVNH, CIFAR-10, CIFAR-100, and Tiny ImageNet. Our code is available athttps://github.com/shqii1j/seqmatch.
{{< /details >}}

>**_2023-11-01_**

[**Are These the Same Apple? Comparing Images Based on Object Intrinsics**](http://arxiv.org/abs/2311.00750v1)

*Klemen Kotar, Stephen Tian, Hong-Xing Yu, Daniel L. K. Yamins, Jiajun Wu*

{{< details "abstract" >}} abstract: The human visual system can effortlessly recognize an object under differentextrinsic factors such as lighting, object poses, and background, yet currentcomputer vision systems often struggle with these variations. An important stepto understanding and improving artificial vision systems is to measure imagesimilarity purely based on intrinsic object properties that define objectidentity. This problem has been studied in the computer vision literature asre-identification, though mostly restricted to specific object categories suchas people and cars. We propose to extend it to general object categories,exploring an image similarity metric based on object intrinsics. To benchmarksuch measurements, we collect the Common paired objects Under differenTExtrinsics (CUTE) dataset of $18,000$ images of $180$ objects under differentextrinsic factors such as lighting, poses, and imaging conditions. Whileexisting methods such as LPIPS and CLIP scores do not measure object intrinsicswell, we find that combining deep features learned from contrastiveself-supervised learning with foreground filtering is a simple yet effectiveapproach to approximating the similarity. We conduct an extensive survey ofpre-trained features and foreground extraction methods to arrive at a strongbaseline that best measures intrinsic object-centric image similarity amongcurrent methods. Finally, we demonstrate that our approach can aid indownstream applications such as acting as an analog for human subjects andimproving generalizable re-identification. Please see our project website athttps://s-tian.github.io/projects/cute/ for visualizations of the data anddemos of our metric.
{{< /details >}}

[**Learning to optimize by multi-gradient for multi-objective optimization**](http://arxiv.org/abs/2311.00559v1)

*Linxi Yang, Xinmin Yang, Liping Tang*

{{< details "abstract" >}} abstract: The development of artificial intelligence (AI) for science has led to theemergence of learning-based research paradigms, necessitating a compellingreevaluation of the design of multi-objective optimization (MOO) methods. Thenew generation MOO methods should be rooted in automated learning rather thanmanual design. In this paper, we introduce a new automatic learning paradigmfor optimizing MOO problems, and propose a multi-gradient learning to optimize(ML2O) method, which automatically learns a generator (or mappings) frommultiple gradients to update directions. As a learning-based method, ML2Oacquires knowledge of local landscapes by leveraging information from thecurrent step and incorporates global experience extracted from historicaliteration trajectory data. By introducing a new guarding mechanism, we proposea guarded multi-gradient learning to optimize (GML2O) method, and prove thatthe iterative sequence generated by GML2O converges to a Pareto critical point.The experimental results demonstrate that our learned optimizer outperformshand-designed competitors on training multi-task learning (MTL) neural network.
{{< /details >}}

[**Towards Legally Enforceable Hate Speech Detection for Public Forums**](http://arxiv.org/abs/2305.13677v2)

*Chu Fei Luo, Rohan Bhambhoria, Xiaodan Zhu, Samuel Dahan*

{{< details "abstract" >}} abstract: Hate speech causes widespread and deep-seated societal issues. Properenforcement of hate speech laws is key for protecting groups of people againstharmful and discriminatory language. However, determining what constitutes hatespeech is a complex task that is highly open to subjective interpretations.Existing works do not align their systems with enforceable definitions of hatespeech, which can make their outputs inconsistent with the goals of regulators.This research introduces a new perspective and task for enforceable hate speechdetection centred around legal definitions, and a dataset annotated onviolations of eleven possible definitions by legal experts. Given the challengeof identifying clear, legally enforceable instances of hate speech, we augmentthe dataset with expert-generated samples and an automatically mined challengeset. We experiment with grounding the model decision in these definitions usingzero-shot and few-shot prompting. We then report results on several largelanguage models (LLMs). With this task definition, automatic hate speechdetection can be more closely aligned to enforceable laws, and hence assist inmore rigorous enforcement of legal protections against harmful speech in publicforums.
{{< /details >}}

>**_2023-10-31_**

[**On Extracting Specialized Code Abilities from Large Language Models: A Feasibility Study**](http://arxiv.org/abs/2303.03012v4)

*Zongjie Li, Chaozheng Wang, Pingchuan Ma, Chaowei Liu, Shuai Wang, Daoyuan Wu, Cuiyun Gao, Yang Liu*

{{< details "abstract" >}} abstract: Recent advances in large language models (LLMs) significantly boost theirusage in software engineering. However, training a well-performing LLM demandsa substantial workforce for data collection and annotation. Moreover, trainingdatasets may be proprietary or partially open, and the process often requires acostly GPU cluster. The intellectual property value of commercial LLMs makesthem attractive targets for imitation attacks, but creating an imitation modelwith comparable parameters still incurs high costs. This motivates us toexplore a practical and novel direction: slicing commercial black-box LLMsusing medium-sized backbone models. In this paper, we explore the feasibilityof launching imitation attacks on LLMs to extract their specialized codeabilities, such as"code synthesis" and "code translation." We systematicallyinvestigate the effectiveness of launching code ability extraction attacksunder different code-related tasks with multiple query schemes, includingzero-shot, in-context, and Chain-of-Thought. We also design response checks torefine the outputs, leading to an effective imitation training process. Ourresults show promising outcomes, demonstrating that with a reasonable number ofqueries, attackers can train a medium-sized backbone model to replicatespecialized code behaviors similar to the target LLMs. We summarize ourfindings and insights to help researchers better understand the threats posedby imitation attacks, including revealing a practical attack surface forgenerating adversarial code examples against LLMs.
{{< /details >}}

>**_2023-10-29_**

[**Multi-task deep learning for large-scale building detail extraction from high-resolution satellite imagery**](http://arxiv.org/abs/2310.18899v1)

*Zhen Qian, Min Chen, Zhuo Sun, Fan Zhang, Qingsong Xu, Jinzhao Guo, Zhiwei Xie, Zhixin Zhang*

{{< details "abstract" >}} abstract: Understanding urban dynamics and promoting sustainable development requirescomprehensive insights about buildings. While geospatial artificialintelligence has advanced the extraction of such details from Earthobservational data, existing methods often suffer from computationalinefficiencies and inconsistencies when compiling unified building-relateddatasets for practical applications. To bridge this gap, we introduce theMulti-task Building Refiner (MT-BR), an adaptable neural network tailored forsimultaneous extraction of spatial and attributional building details fromhigh-resolution satellite imagery, exemplified by building rooftops, urbanfunctional types, and roof architectural types. Notably, MT-BR can befine-tuned to incorporate additional building details, extending itsapplicability. For large-scale applications, we devise a novel spatial samplingscheme that strategically selects limited but representative image samples.This process optimizes both the spatial distribution of samples and the urbanenvironmental characteristics they contain, thus enhancing extractioneffectiveness while curtailing data preparation expenditures. We furtherenhance MT-BR's predictive performance and generalization capabilities throughthe integration of advanced augmentation techniques. Our quantitative resultshighlight the efficacy of the proposed methods. Specifically, networks trainedwith datasets curated via our sampling method demonstrate improved predictiveaccuracy relative to those using alternative sampling approaches, with noalterations to network architecture. Moreover, MT-BR consistently outperformsother state-of-the-art methods in extracting building details across variousmetrics. The real-world practicality is also demonstrated in an applicationacross Shanghai, generating a unified dataset that encompasses both the spatialand attributional details of buildings.
{{< /details >}}

>**_2023-10-25_**

[**RAEDiff: Denoising Diffusion Probabilistic Models Based Reversible Adversarial Examples Self-Generation and Self-Recovery**](http://arxiv.org/abs/2311.12858v1)

*Fan Xing, Xiaoyi Zhou, Xuefeng Fan, Zhuo Tian, Yan Zhao*

{{< details "abstract" >}} abstract: Collected and annotated datasets, which are obtained through extensiveefforts, are effective for training Deep Neural Network (DNN) models. However,these datasets are susceptible to be misused by unauthorized users, resultingin infringement of Intellectual Property (IP) rights owned by the datasetcreators. Reversible Adversarial Exsamples (RAE) can help to solve the issuesof IP protection for datasets. RAEs are adversarial perturbed images that canbe restored to the original. As a cutting-edge approach, RAE scheme can servethe purposes of preventing unauthorized users from engaging in malicious modeltraining, as well as ensuring the legitimate usage of authorized users.Nevertheless, in the existing work, RAEs still rely on the embedded auxiliaryinformation for restoration, which may compromise their adversarial abilities.In this paper, a novel self-generation and self-recovery method, named asRAEDiff, is introduced for generating RAEs based on a Denoising DiffusionProbabilistic Models (DDPM). It diffuses datasets into a Biased GaussianDistribution (BGD) and utilizes the prior knowledge of the DDPM for generatingand recovering RAEs. The experimental results demonstrate that RAEDiffeffectively self-generates adversarial perturbations for DNN models, includingArtificial Intelligence Generated Content (AIGC) models, while also exhibitingsignificant self-recovery capabilities.
{{< /details >}}

[**HANSEN: Human and AI Spoken Text Benchmark for Authorship Analysis**](http://arxiv.org/abs/2310.16746v1)

*Nafis Irtiza Tripto, Adaku Uchendu, Thai Le, Mattia Setzu, Fosca Giannotti, Dongwon Lee*

{{< details "abstract" >}} abstract: Authorship Analysis, also known as stylometry, has been an essential aspectof Natural Language Processing (NLP) for a long time. Likewise, the recentadvancement of Large Language Models (LLMs) has made authorship analysisincreasingly crucial for distinguishing between human-written and AI-generatedtexts. However, these authorship analysis tasks have primarily been focused onwritten texts, not considering spoken texts. Thus, we introduce the largestbenchmark for spoken texts - HANSEN (Human ANd ai Spoken tExt beNchmark).HANSEN encompasses meticulous curation of existing speech datasets accompaniedby transcripts, alongside the creation of novel AI-generated spoken textdatasets. Together, it comprises 17 human datasets, and AI-generated spokentexts created using 3 prominent LLMs: ChatGPT, PaLM2, and Vicuna13B. Toevaluate and demonstrate the utility of HANSEN, we perform AuthorshipAttribution (AA) & Author Verification (AV) on human-spoken datasets andconducted Human vs. AI spoken text detection using state-of-the-art (SOTA)models. While SOTA methods, such as, character ngram or Transformer-basedmodel, exhibit similar AA & AV performance in human-spoken datasets compared towritten ones, there is much room for improvement in AI-generated spoken textdetection. The HANSEN benchmark is available at:https://huggingface.co/datasets/HANSEN-REPO/HANSEN.
{{< /details >}}

[**Wide Flat Minimum Watermarking for Robust Ownership Verification of GANs**](http://arxiv.org/abs/2310.16919v1)

*Jianwei Fei, Zhihua Xia, Benedetta Tondi, Mauro Barni*

{{< details "abstract" >}} abstract: We propose a novel multi-bit box-free watermarking method for the protectionof Intellectual Property Rights (IPR) of GANs with improved robustness againstwhite-box attacks like fine-tuning, pruning, quantization, and surrogate modelattacks. The watermark is embedded by adding an extra watermarking loss termduring GAN training, ensuring that the images generated by the GAN contain aninvisible watermark that can be retrieved by a pre-trained watermark decoder.In order to improve the robustness against white-box model-level attacks, wemake sure that the model converges to a wide flat minimum of the watermarkingloss term, in such a way that any modification of the model parameters does noterase the watermark. To do so, we add random noise vectors to the parameters ofthe generator and require that the watermarking loss term is as invariant aspossible with respect to the presence of noise. This procedure forces thegenerator to converge to a wide flat minimum of the watermarking loss. Theproposed method is architectureand dataset-agnostic, thus being applicable tomany different generation tasks and models, as well as to CNN-based imageprocessing architectures. We present the results of extensive experimentsshowing that the presence of the watermark has a negligible impact on thequality of the generated images, and proving the superior robustness of thewatermark against model modification and surrogate model attacks.
{{< /details >}}

>**_2023-10-20_**

[**On the Overlooked Structure of Stochastic Gradients**](http://arxiv.org/abs/2212.02083v3)

*Zeke Xie, Qian-Yuan Tang, Mingming Sun, Ping Li*

{{< details "abstract" >}} abstract: Stochastic gradients closely relate to both optimization and generalizationof deep neural networks (DNNs). Some works attempted to explain the success ofstochastic optimization for deep learning by the arguably heavy-tail propertiesof gradient noise, while other works presented theoretical and empiricalevidence against the heavy-tail hypothesis on gradient noise. Unfortunately,formal statistical tests for analyzing the structure and heavy tails ofstochastic gradients in deep learning are still under-explored. In this paper,we mainly make two contributions. First, we conduct formal statistical tests onthe distribution of stochastic gradients and gradient noise across bothparameters and iterations. Our statistical tests reveal that dimension-wisegradients usually exhibit power-law heavy tails, while iteration-wise gradientsand stochastic gradient noise caused by minibatch training usually do notexhibit power-law heavy tails. Second, we further discover that the covariancespectra of stochastic gradients have the power-law structures overlooked byprevious studies and present its theoretical implications for training of DNNs.While previous studies believed that the anisotropic structure of stochasticgradients matters to deep learning, they did not expect the gradient covariancecan have such an elegant mathematical structure. Our work challenges theexisting belief and provides novel insights on the structure of stochasticgradients in deep learning.
{{< /details >}}

>**_2023-10-19_**

[**Privacy Preserving Large Language Models: ChatGPT Case Study Based Vision and Framework**](http://arxiv.org/abs/2310.12523v1)

*Imdad Ullah, Najm Hassan, Sukhpal Singh Gill, Basem Suleiman, Tariq Ahamed Ahanger, Zawar Shah, Junaid Qadir, Salil S. Kanhere*

{{< details "abstract" >}} abstract: The generative Artificial Intelligence (AI) tools based on Large LanguageModels (LLMs) use billions of parameters to extensively analyse large datasetsand extract critical private information such as, context, specific details,identifying information etc. This have raised serious threats to user privacyand reluctance to use such tools. This article proposes the conceptual modelcalled PrivChatGPT, a privacy-preserving model for LLMs that consists of twomain components i.e., preserving user privacy during the datacuration/pre-processing together with preserving private context and theprivate training process for large-scale data. To demonstrate itsapplicability, we show how a private mechanism could be integrated into theexisting model for training LLMs to protect user privacy; specifically, weemployed differential privacy and private training using Reinforcement Learning(RL). We measure the privacy loss and evaluate the measure of uncertainty orrandomness once differential privacy is applied. It further recursivelyevaluates the level of privacy guarantees and the measure of uncertainty ofpublic database and resources, during each update when new information is addedfor training purposes. To critically evaluate the use of differential privacyfor private LLMs, we hypothetically compared other mechanisms e..g, Blockchain,private information retrieval, randomisation, for various performance measuressuch as the model performance and accuracy, computational complexity, privacyvs. utility etc. We conclude that differential privacy, randomisation, andobfuscation can impact utility and performance of trained models, conversely,the use of ToR, Blockchain, and PIR may introduce additional computationalcomplexity and high training latency. We believe that the proposed model couldbe used as a benchmark for proposing privacy preserving LLMs for generative AItools.
{{< /details >}}

>**_2023-10-17_**

[**An Embarrassingly Simple Approach for Wafer Feature Extraction and Defect Pattern Recognition**](http://arxiv.org/abs/2303.11632v2)

*Nitish Shukla*

{{< details "abstract" >}} abstract: Identifying defect patterns in a wafer map during manufacturing is crucial tofind the root cause of the underlying issue and provides valuable insights onimproving yield in the foundry. Currently used methods use deep neural networksto identify the defects. These methods are generally very huge and havesignificant inference time. They also require GPU support to efficientlyoperate. All these issues make these models not fit for on-line prediction inthe manufacturing foundry. In this paper, we propose an extremely simple yeteffective technique to extract features from wafer images. The proposed methodis extremely fast, intuitive, and non-parametric while being explainable. Theexperiment results show that the proposed pipeline outperforms conventionaldeep learning models. Our feature extraction requires no training orfine-tuning while preserving the relative shape and location of data points asrevealed by our interpretability analysis.
{{< /details >}}

[**PAXQA: Generating Cross-lingual Question Answering Examples at Training Scale**](http://arxiv.org/abs/2304.12206v2)

*Bryan Li, Chris Callison-Burch*

{{< details "abstract" >}} abstract: Existing question answering (QA) systems owe much of their success to large,high-quality training data. Such annotation efforts are costly, and thedifficulty compounds in the cross-lingual setting. Therefore, priorcross-lingual QA work has focused on releasing evaluation datasets, and thenapplying zero-shot methods as baselines. This work proposes a synthetic datageneration method for cross-lingual QA which leverages indirect supervisionfrom existing parallel corpora. Our method termed PAXQA (Projecting annotationsfor cross-lingual (x) QA) decomposes cross-lingual QA into two stages. First,we apply a question generation (QG) model to the English side. Second, we applyannotation projection to translate both the questions and answers. To bettertranslate questions, we propose a novel use of lexically-constrained machinetranslation, in which constrained entities are extracted from the parallelbitexts.  We apply PAXQA to generate cross-lingual QA examples in 4 languages (662Kexamples total), and perform human evaluation on a subset to create validationand test splits. We then show that models fine-tuned on these datasetsoutperform prior synthetic data generation models over several extractive QAdatasets. The largest performance gains are for directions with non-Englishquestions and English contexts. Ablation studies show that our datasetgeneration method is relatively robust to noise from automatic word alignments,showing the sufficient quality of our generations. To facilitate follow-upwork, we release our code and datasets at https://github.com/manestay/paxqa .
{{< /details >}}

>**_2023-10-15_**

[**Empower Text-Attributed Graphs Learning with Large Language Models (LLMs)**](http://arxiv.org/abs/2310.09872v1)

*Jianxiang Yu, Yuxiang Ren, Chenghua Gong, Jiaqi Tan, Xiang Li, Xuecang Zhang*

{{< details "abstract" >}} abstract: Text-attributed graphs have recently garnered significant attention due totheir wide range of applications in web domains. Existing methodologies employword embedding models for acquiring text representations as node features,which are subsequently fed into Graph Neural Networks (GNNs) for training.Recently, the advent of Large Language Models (LLMs) has introduced theirpowerful capabilities in information retrieval and text generation, which cangreatly enhance the text attributes of graph data. Furthermore, the acquisitionand labeling of extensive datasets are both costly and time-consumingendeavors. Consequently, few-shot learning has emerged as a crucial problem inthe context of graph learning tasks. In order to tackle this challenge, wepropose a lightweight paradigm called ENG, which adopts a plug-and-playapproach to empower text-attributed graphs through node generation using LLMs.Specifically, we utilize LLMs to extract semantic information from the labelsand generate samples that belong to these categories as exemplars.Subsequently, we employ an edge predictor to capture the structural informationinherent in the raw dataset and integrate the newly generated samples into theoriginal graph. This approach harnesses LLMs for enhancing class-levelinformation and seamlessly introduces labeled nodes and edges without modifyingthe raw dataset, thereby facilitating the node classification task in few-shotscenarios. Extensive experiments demonstrate the outstanding performance of ourproposed paradigm, particularly in low-shot scenarios. For instance, in the1-shot setting of the ogbn-arxiv dataset, ENG achieves a 76% improvement overthe baseline model.
{{< /details >}}

>**_2023-10-14_**

[**Unified High-binding Watermark for Unconditional Image Generation Models**](http://arxiv.org/abs/2310.09479v1)

*Ruinan Ma, Yu-an Tan, Shangbo Wu, Tian Chen, Yajie Wang, Yuanzhang Li*

{{< details "abstract" >}} abstract: Deep learning techniques have implemented many unconditional image generation(UIG) models, such as GAN, Diffusion model, etc. The extremely realistic images(also known as AI-Generated Content, AIGC for short) produced by these modelsbring urgent needs for intellectual property protection such as datatraceability and copyright certification. An attacker can steal the outputimages of the target model and use them as part of the training data to train aprivate surrogate UIG model. The implementation mechanisms of UIG models arediverse and complex, and there is no unified and effective protection andverification method at present. To address these issues, we propose a two-stageunified watermark verification mechanism with high-binding effects for suchmodels. In the first stage, we use an encoder to invisibly write the watermarkimage into the output images of the original AIGC tool, and reversely extractthe watermark image through the corresponding decoder. In the second stage, wedesign the decoder fine-tuning process, and the fine-tuned decoder can makecorrect judgments on whether the suspicious model steals the original AIGC tooldata. Experiments demonstrate our method can complete the verification workwith almost zero false positive rate under the condition of only using themodel output images. Moreover, the proposed method can achieve data stealverification across different types of UIG models, which further increases thepracticality of the method.
{{< /details >}}

[**RoadScan: A Novel and Robust Transfer Learning Framework for Autonomous Pothole Detection in Roads**](http://arxiv.org/abs/2308.03467v2)

*Guruprasad Parasnis, Anmol Chokshi, Vansh Jain, Kailas Devadkar*

{{< details "abstract" >}} abstract: This research paper presents a novel approach to pothole detection using DeepLearning and Image Processing techniques. The proposed system leverages theVGG16 model for feature extraction and utilizes a custom Siamese network withtriplet loss, referred to as RoadScan. The system aims to address the criticalissue of potholes on roads, which pose significant risks to road users.Accidents due to potholes on the roads have led to numerous accidents. Althoughit is necessary to completely remove potholes, it is a time-consuming process.Hence, a general road user should be able to detect potholes from a safedistance in order to avoid damage. Existing methods for pothole detectionheavily rely on object detection algorithms which tend to have a high chance offailure owing to the similarity in structures and textures of a road and apothole. Additionally, these systems utilize millions of parameters therebymaking the model difficult to use in small-scale applications for the generalcitizen. By analyzing diverse image processing methods and varioushigh-performing networks, the proposed model achieves remarkable performance inaccurately detecting potholes. Evaluation metrics such as accuracy, EER,precision, recall, and AUROC validate the effectiveness of the system.Additionally, the proposed model demonstrates computational efficiency andcost-effectiveness by utilizing fewer parameters and data for training. Theresearch highlights the importance of technology in the transportation sectorand its potential to enhance road safety and convenience. The network proposedin this model performs with a 96.12 % accuracy, 3.89 % EER, and a 0.988 AUROCvalue, which is highly competitive with other state-of-the-art works.
{{< /details >}}

>**_2023-10-11_**

[**Deep Aramaic: Towards a Synthetic Data Paradigm Enabling Machine Learning in Epigraphy**](http://arxiv.org/abs/2310.07310v1)

*Andrei C. Aioanei, Regine Hunziker-Rodewald, Konstantin Klein, Dominik L. Michels*

{{< details "abstract" >}} abstract: Epigraphy increasingly turns to modern artificial intelligence (AI)technologies such as machine learning (ML) for extracting insights from ancientinscriptions. However, scarce labeled data for training ML algorithms severelylimits current techniques, especially for ancient scripts like Old Aramaic. Ourresearch pioneers an innovative methodology for generating synthetic trainingdata tailored to Old Aramaic letters. Our pipeline synthesizes photo-realisticAramaic letter datasets, incorporating textural features, lighting, damage, andaugmentations to mimic real-world inscription diversity. Despite minimal realexamples, we engineer a dataset of 250,000 training and 25,000 validationimages covering the 22 letter classes in the Aramaic alphabet. Thiscomprehensive corpus provides a robust volume of data for training a residualneural network (ResNet) to classify highly degraded Aramaic letters. The ResNetmodel demonstrates high accuracy in classifying real images from the 8thcentury BCE Hadad statue inscription. Additional experiments validateperformance on varying materials and styles, proving effective generalization.Our results validate the model's capabilities in handling diverse real-worldscenarios, proving the viability of our synthetic data approach and avoidingthe dependence on scarce training data that has constrained epigraphicanalysis. Our innovative framework elevates interpretation accuracy on damagedinscriptions, thus enhancing knowledge extraction from these historicalresources.
{{< /details >}}

>**_2023-10-10_**

[**Memorization of Named Entities in Fine-tuned BERT Models**](http://arxiv.org/abs/2212.03749v2)

*Andor Diera, Nicolas Lell, Aygul Garifullina, Ansgar Scherp*

{{< details "abstract" >}} abstract: Privacy preserving deep learning is an emerging field in machine learningthat aims to mitigate the privacy risks in the use of deep neural networks. Onesuch risk is training data extraction from language models that have beentrained on datasets, which contain personal and privacy sensitive information.In our study, we investigate the extent of named entity memorization infine-tuned BERT models. We use single-label text classification asrepresentative downstream task and employ three different fine-tuning setups inour experiments, including one with Differentially Privacy (DP). We create alarge number of text samples from the fine-tuned BERT models utilizing a customsequential sampling strategy with two prompting strategies. We search in thesesamples for named entities and check if they are also present in thefine-tuning datasets. We experiment with two benchmark datasets in the domainsof emails and blogs. We show that the application of DP has a detrimentaleffect on the text generation capabilities of BERT. Furthermore, we show that afine-tuned BERT does not generate more named entities specific to thefine-tuning dataset than a BERT model that is pre-trained only. This suggeststhat BERT is unlikely to emit personal or privacy sensitive named entities.Overall, our results are important to understand to what extent BERT-basedservices are prone to training data extraction attacks.
{{< /details >}}

>**_2023-10-07_**

[**PaperCard for Reporting Machine Assistance in Academic Writing**](http://arxiv.org/abs/2310.04824v1)

*Won Ik Cho, Eunjung Cho, Kyunghyun Cho*

{{< details "abstract" >}} abstract: Academic writing process has benefited from various technologicaldevelopments over the years including search engines, automatic translators,and editing tools that review grammar and spelling mistakes. They have enabledhuman writers to become more efficient in writing academic papers, for exampleby helping with finding relevant literature more effectively and polishingtexts. While these developments have so far played a relatively assistive role,recent advances in large-scale language models (LLMs) have enabled LLMs to playa more major role in the writing process, such as coming up with researchquestions and generating key contents. This raises critical questionssurrounding the concept of authorship in academia. ChatGPT, aquestion-answering system released by OpenAI in November 2022, has demonstrateda range of capabilities that could be utilised in producing academic papers.The academic community will have to address relevant pressing questions,including whether Artificial Intelligence (AI) should be merited authorship ifit made significant contributions in the writing process, or whether its useshould be restricted such that human authorship would not be undermined. Inthis paper, we aim to address such questions, and propose a framework we name"PaperCard", a documentation for human authors to transparently declare the useof AI in their writing process.
{{< /details >}}

>**_2023-10-03_**

[**FT-Shield: A Watermark Against Unauthorized Fine-tuning in Text-to-Image Diffusion Models**](http://arxiv.org/abs/2310.02401v1)

*Yingqian Cui, Jie Ren, Yuping Lin, Han Xu, Pengfei He, Yue Xing, Wenqi Fan, Hui Liu, Jiliang Tang*

{{< details "abstract" >}} abstract: Text-to-image generative models based on latent diffusion models (LDM) havedemonstrated their outstanding ability in generating high-quality andhigh-resolution images according to language prompt. Based on these powerfullatent diffusion models, various fine-tuning methods have been proposed toachieve the personalization of text-to-image diffusion models such as artisticstyle adaptation and human face transfer. However, the unauthorized usage ofdata for model personalization has emerged as a prevalent concern in relationto copyright violations. For example, a malicious user may use the fine-tuningtechnique to generate images which mimic the style of a painter without his/herpermission. In light of this concern, we have proposed FT-Shield, awatermarking approach specifically designed for the fine-tuning oftext-to-image diffusion models to aid in detecting instances of infringement.We develop a novel algorithm for the generation of the watermark to ensure thatthe watermark on the training images can be quickly and accurately transferredto the generated images of text-to-image diffusion models. A watermark will bedetected on an image by a binary watermark detector if the image is generatedby a model that has been fine-tuned using the protected watermarked images.Comprehensive experiments were conducted to validate the effectiveness ofFT-Shield.
{{< /details >}}

[**An evaluation of pre-trained models for feature extraction in image classification**](http://arxiv.org/abs/2310.02037v1)

*Erick da Silva Puls, Matheus V. Todescato, Joel L. Carbonera*

{{< details "abstract" >}} abstract: In recent years, we have witnessed a considerable increase in performance inimage classification tasks. This performance improvement is mainly due to theadoption of deep learning techniques. Generally, deep learning techniquesdemand a large set of annotated data, making it a challenge when applying it tosmall datasets. In this scenario, transfer learning strategies have become apromising alternative to overcome these issues. This work aims to compare theperformance of different pre-trained neural networks for feature extraction inimage classification tasks. We evaluated 16 different pre-trained models infour image datasets. Our results demonstrate that the best general performancealong the datasets was achieved by CLIP-ViT-B and ViT-H-14, where theCLIP-ResNet50 model had similar performance but with less variability.Therefore, our study provides evidence supporting the choice of models forfeature extraction in image classification tasks.
{{< /details >}}

>**_2023-09-30_**

[**Enhancing Representation Generalization in Authorship Identification**](http://arxiv.org/abs/2310.00436v1)

*Haining Wang*

{{< details "abstract" >}} abstract: Authorship identification ascertains the authorship of texts whose originsremain undisclosed. That authorship identification techniques work as reliablyas they do has been attributed to the fact that authorial style is properlycaptured and represented. Although modern authorship identification methodshave evolved significantly over the years and have proven effective indistinguishing authorial styles, the generalization of stylistic featuresacross domains has not been systematically reviewed. The presented workaddresses the challenge of enhancing the generalization of stylisticrepresentations in authorship identification, particularly when there arediscrepancies between training and testing samples. A comprehensive review ofempirical studies was conducted, focusing on various stylistic features andtheir effectiveness in representing an author's style. The influencing factorssuch as topic, genre, and register on writing style were also explored, alongwith strategies to mitigate their impact. While some stylistic features, likecharacter n-grams and function words, have proven to be robust anddiscriminative, others, such as content words, can introduce biases and hindercross-domain generalization. Representations learned using deep learningmodels, especially those incorporating character n-grams and syntacticinformation, show promise in enhancing representation generalization. Thefindings underscore the importance of selecting appropriate stylistic featuresfor authorship identification, especially in cross-domain scenarios. Therecognition of the strengths and weaknesses of various linguistic featurespaves the way for more accurate authorship identification in diverse contexts.
{{< /details >}}

[**Learning Informative Latent Representation for Quantum State Tomography**](http://arxiv.org/abs/2310.00518v1)

*Hailan Ma, Zhenhong Sun, Daoyi Dong, Dong Gong*

{{< details "abstract" >}} abstract: Quantum state tomography (QST) is the process of reconstructing the completestate of a quantum system (mathematically described as a density matrix)through a series of different measurements. These measurements are performed ona number of identical copies of the quantum system, with outcomes gathered asfrequencies. QST aims to recover the density matrix and the correspondingproperties of the quantum state from the measured frequencies. Although aninformationally complete set of measurements can specify quantum stateaccurately in an ideal scenario with a large number of identical copies, bothmeasurements and identical copies are restricted and imperfect in practicalscenarios, making QST highly ill-posed. The conventional QST methods usuallyassume adequate or accurate measured frequencies or rely on manually designedregularizers to handle the ill-posed reconstruction problem, suffering fromlimited applications in realistic scenarios. Recent advances in deep neuralnetworks (DNNs) led to the emergence of deep learning (DL) in QST. However,existing DL-based QST approaches often employ generic DNN models that are notoptimized for imperfect conditions of QST. In this paper, we propose atransformer-based autoencoder architecture tailored for QST with imperfectmeasurement data. Our method leverages a transformer-based encoder to extractan informative latent representation (ILR) from imperfect measurement data andemploys a decoder to predict the quantum states based on the ILR. We anticipatethat the high-dimensional ILR will capture more comprehensive information aboutquantum states. To achieve this, we conduct pre-training of the encoder using apretext task that involves reconstructing high-quality frequencies frommeasured frequencies. Extensive simulations and experiments demonstrate theremarkable ability of the ILR in dealing with imperfect measurement data inQST.
{{< /details >}}

>**_2023-09-29_**

[**Synthetic Data Generation and Deep Learning for the Topological Analysis of 3D Data**](http://arxiv.org/abs/2309.16968v1)

*Dylan Peek, Matt P. Skerritt, Stephan Chalup*

{{< details "abstract" >}} abstract: This research uses deep learning to estimate the topology of manifoldsrepresented by sparse, unordered point cloud scenes in 3D. A new labelleddataset was synthesised to train neural networks and evaluate their ability toestimate the genus of these manifolds. This data used random homeomorphicdeformations to provoke the learning of visual topological features. Wedemonstrate that deep learning models could extract these features and discusssome advantages over existing topological data analysis tools that are based onpersistent homology. Semantic segmentation was used to provide additionalgeometric information in conjunction with topological labels. Common pointcloud multi-layer perceptron and transformer networks were both used to comparethe viability of these methods. The experimental results of this pilot studysupport the hypothesis that, with the aid of sophisticated synthetic datageneration, neural networks can perform segmentation-based topological dataanalysis. While our study focused on simulated data, the accuracy achievedsuggests a potential for future applications using real data.
{{< /details >}}

>**_2023-09-24_**

[**Data-Driven Modeling of an Unsaturated Bentonite Buffer Model Test Under High Temperatures Using an Enhanced Axisymmetric Reproducing Kernel Particle Method**](http://arxiv.org/abs/2309.13519v1)

*Jonghyuk Baek, Yanran Wang, Xiaolong He, Yu Lu, John S. McCartney, J. S. Chen*

{{< details "abstract" >}} abstract: In deep geological repositories for high level nuclear waste with closecanister spacings, bentonite buffers can experience temperatures higher than100 {\deg}C. In this range of extreme temperatures, phenomenologicalconstitutive laws face limitations in capturing the thermo-hydro-mechanical(THM) behavior of the bentonite, since the pre-defined functional constitutivelaws often lack generality and flexibility to capture a wide range of complexcoupling phenomena as well as the effects of stress state and path dependency.In this work, a deep neural network (DNN)-based soil-water retention curve(SWRC) of bentonite is introduced and integrated into a Reproducing KernelParticle Method (RKPM) for conducting THM simulations of the bentonite buffer.The DNN-SWRC model incorporates temperature as an additional input variable,allowing it to learn the relationship between suction and degree of saturationunder the general non-isothermal condition, which is difficult to representusing a phenomenological SWRC. For effective modeling of the tank-scale test,new axisymmetric Reproducing Kernel basis functions enriched with singularDirichlet enforcement representing heater placement and an effective convectiveheat transfer coefficient representing thin-layer composite tank constructionare developed. The proposed method is demonstrated through the modeling of atank-scale experiment involving a cylindrical layer of MX-80 bentonite exposedto central heating.
{{< /details >}}

>**_2023-09-22_**

[**Random Word Data Augmentation with CLIP for Zero-Shot Anomaly Detection**](http://arxiv.org/abs/2308.11119v2)

*Masato Tamura*

{{< details "abstract" >}} abstract: This paper presents a novel method that leverages a visual-language model,CLIP, as a data source for zero-shot anomaly detection. Tremendous efforts havebeen put towards developing anomaly detectors due to their potential industrialapplications. Considering the difficulty in acquiring various anomalous samplesfor training, most existing methods train models with only normal samples andmeasure discrepancies from the distribution of normal samples during inference,which requires training a model for each object category. The problem of thisinefficient training requirement has been tackled by designing a CLIP-basedanomaly detector that applies prompt-guided classification to each part of animage in a sliding window manner. However, the method still suffers from thelabor of careful prompt ensembling with known object categories. To overcomethe issues above, we propose leveraging CLIP as a data source for training. Ourmethod generates text embeddings with the text encoder in CLIP with typicalprompts that include words of normal and anomaly. In addition to these words,we insert several randomly generated words into prompts, which enables theencoder to generate a diverse set of normal and anomalous samples. Using thegenerated embeddings as training data, a feed-forward neural network learns toextract features of normal and anomaly from CLIP's embeddings, and as a result,a category-agnostic anomaly detector can be obtained without any trainingimages. Experimental results demonstrate that our method achievesstate-of-the-art performance without laborious prompt ensembling in zero-shotsetups.
{{< /details >}}

>**_2023-09-21_**

[**DeepTheft: Stealing DNN Model Architectures through Power Side Channel**](http://arxiv.org/abs/2309.11894v1)

*Yansong Gao, Huming Qiu, Zhi Zhang, Binghui Wang, Hua Ma, Alsharif Abuadbba, Minhui Xue, Anmin Fu, Surya Nepal*

{{< details "abstract" >}} abstract: Deep Neural Network (DNN) models are often deployed in resource-sharingclouds as Machine Learning as a Service (MLaaS) to provide inferenceservices.To steal model architectures that are of valuable intellectualproperties, a class of attacks has been proposed via different side-channelleakage, posing a serious security challenge to MLaaS.  Also targeting MLaaS, we propose a new end-to-end attack, DeepTheft, toaccurately recover complex DNN model architectures on general processors viathe RAPL-based power side channel. However, an attacker can acquire only a lowsampling rate (1 KHz) of the time-series energy traces from the RAPL interface,rendering existing techniques ineffective in stealing large and deep DNNmodels. To this end, we design a novel and generic learning-based frameworkconsisting of a set of meta-models, based on which DeepTheft is demonstrated tohave high accuracy in recovering a large number (thousands) of modelsarchitectures from different model families including the deepest ResNet152.Particularly, DeepTheft has achieved a Levenshtein Distance Accuracy of 99.75%in recovering network structures, and a weighted average F1 score of 99.60% inrecovering diverse layer-wise hyperparameters. Besides, our proposed learningframework is general to other time-series side-channel signals. To validate itsgeneralization, another existing side channel is exploited, i.e., CPUfrequency. Different from RAPL, CPU frequency is accessible to unprivilegedusers in bare-metal OSes. By using our generic learning framework trainedagainst CPU frequency traces, DeepTheft has shown similarly high attackperformance in stealing model architectures.
{{< /details >}}

[**MarkNerf:Watermarking for Neural Radiance Field**](http://arxiv.org/abs/2309.11747v1)

*Lifeng Chen, Jia Liu, Yan Ke, Wenquan Sun, Weina Dong, Xiaozhong Pan*

{{< details "abstract" >}} abstract: A watermarking algorithm is proposed in this paper to address the copyrightprotection issue of implicit 3D models. The algorithm involves embeddingwatermarks into the images in the training set through an embedding network,and subsequently utilizing the NeRF model for 3D modeling. A copyright verifieris employed to generate a backdoor image by providing a secret perspective asinput to the neural radiation field. Subsequently, a watermark extractor isdevised using the hyperparameterization method of the neural network to extractthe embedded watermark image from that perspective. In a black box scenario, ifthere is a suspicion that the 3D model has been used without authorization, theverifier can extract watermarks from a secret perspective to verify networkcopyright. Experimental results demonstrate that the proposed algorithmeffectively safeguards the copyright of 3D models. Furthermore, the extractedwatermarks exhibit favorable visual effects and demonstrate robust resistanceagainst various types of noise attacks.
{{< /details >}}

>**_2023-09-20_**

[**Improving Article Classification with Edge-Heterogeneous Graph Neural Networks**](http://arxiv.org/abs/2309.11341v1)

*Khang Ly, Yury Kashnitsky, Savvas Chamezopoulos, Valeria Krzhizhanovskaya*

{{< details "abstract" >}} abstract: Classifying research output into context-specific label taxonomies is achallenging and relevant downstream task, given the volume of existing andnewly published articles. We propose a method to enhance the performance ofarticle classification by enriching simple Graph Neural Networks (GNN)pipelines with edge-heterogeneous graph representations. SciBERT is used fornode feature generation to capture higher-order semantics within the articles'textual metadata. Fully supervised transductive node classification experimentsare conducted on the Open Graph Benchmark (OGB) ogbn-arxiv dataset and thePubMed diabetes dataset, augmented with additional metadata from MicrosoftAcademic Graph (MAG) and PubMed Central, respectively. The results demonstratethat edge-heterogeneous graphs consistently improve the performance of all GNNmodels compared to the edge-homogeneous graphs. The transformed data enablesimple and shallow GNN pipelines to achieve results on par with more complexarchitectures. On ogbn-arxiv, we achieve a top-15 result in the OGB competitionwith a 2-layer GCN (accuracy 74.61%), being the highest-scoring solution withsub-1 million parameters. On PubMed, we closely trail SOTA GNN architecturesusing a 2-layer GraphSAGE by including additional co-authorship edges in thegraph (accuracy 89.88%). The implementation is available at:$\href{https://github.com/lyvykhang/edgehetero-nodeproppred}{\text{https://github.com/lyvykhang/edgehetero-nodeproppred}}$.
{{< /details >}}

>**_2023-09-18_**

[**AGIEval: A Human-Centric Benchmark for Evaluating Foundation Models**](http://arxiv.org/abs/2304.06364v2)

*Wanjun Zhong, Ruixiang Cui, Yiduo Guo, Yaobo Liang, Shuai Lu, Yanlin Wang, Amin Saied, Weizhu Chen, Nan Duan*

{{< details "abstract" >}} abstract: Evaluating the general abilities of foundation models to tackle human-leveltasks is a vital aspect of their development and application in the pursuit ofArtificial General Intelligence (AGI). Traditional benchmarks, which rely onartificial datasets, may not accurately represent human-level capabilities. Inthis paper, we introduce AGIEval, a novel benchmark specifically designed toassess foundation model in the context of human-centric standardized exams,such as college entrance exams, law school admission tests, math competitions,and lawyer qualification tests. We evaluate several state-of-the-art foundationmodels, including GPT-4, ChatGPT, and Text-Davinci-003, using this benchmark.Impressively, GPT-4 surpasses average human performance on SAT, LSAT, and mathcompetitions, attaining a 95% accuracy rate on the SAT Math test and a 92.5%accuracy on the English test of the Chinese national college entrance exam.This demonstrates the extraordinary performance of contemporary foundationmodels. In contrast, we also find that GPT-4 is less proficient in tasks thatrequire complex reasoning or specific domain knowledge. Our comprehensiveanalyses of model capabilities (understanding, knowledge, reasoning, andcalculation) reveal these models' strengths and limitations, providing valuableinsights into future directions for enhancing their general capabilities. Byconcentrating on tasks pertinent to human cognition and decision-making, ourbenchmark delivers a more meaningful and robust evaluation of foundationmodels' performance in real-world scenarios. The data, code, and all modeloutputs are released in https://github.com/ruixiangcui/AGIEval.
{{< /details >}}

>**_2023-09-16_**

[**Tightening Classification Boundaries in Open Set Domain Adaptation through Unknown Exploitation**](http://arxiv.org/abs/2309.08964v1)

*Lucas Fernando Alvarenga e Silva, Nicu Sebe, Jurandy Almeida*

{{< details "abstract" >}} abstract: Convolutional Neural Networks (CNNs) have brought revolutionary advances tomany research areas due to their capacity of learning from raw data. However,when those methods are applied to non-controllable environments, many differentfactors can degrade the model's expected performance, such as unlabeleddatasets with different levels of domain shift and category shift.Particularly, when both issues occur at the same time, we tackle thischallenging setup as Open Set Domain Adaptation (OSDA) problem. In general,existing OSDA approaches focus their efforts only on aligning known classes or,if they already extract possible negative instances, use them as a new categorylearned with supervision during the course of training. We propose a novel wayto improve OSDA approaches by extracting a high-confidence set of unknowninstances and using it as a hard constraint to tighten the classificationboundaries of OSDA methods. Especially, we adopt a new loss constraintevaluated in three different means, (1) directly with the pristine negativeinstances; (2) with randomly transformed negatives using data augmentationtechniques; and (3) with synthetically generated negatives containingadversarial features. We assessed all approaches in an extensive set ofexperiments based on OVANet, where we could observe consistent improvements fortwo public benchmarks, the Office-31 and Office-Home datasets, yieldingabsolute gains of up to 1.3% for both Accuracy and H-Score on Office-31 and5.8% for Accuracy and 4.7% for H-Score on Office-Home.
{{< /details >}}

>**_2023-09-14_**

[**Detecting ChatGPT: A Survey of the State of Detecting ChatGPT-Generated Text**](http://arxiv.org/abs/2309.07689v1)

*Mahdi Dhaini, Wessel Poelman, Ege Erdogan*

{{< details "abstract" >}} abstract: While recent advancements in the capabilities and widespread accessibility ofgenerative language models, such as ChatGPT (OpenAI, 2022), have brought aboutvarious benefits by generating fluent human-like text, the task ofdistinguishing between human- and large language model (LLM) generated text hasemerged as a crucial problem. These models can potentially deceive bygenerating artificial text that appears to be human-generated. This issue isparticularly significant in domains such as law, education, and science, whereensuring the integrity of text is of the utmost importance. This surveyprovides an overview of the current approaches employed to differentiatebetween texts generated by humans and ChatGPT. We present an account of thedifferent datasets constructed for detecting ChatGPT-generated text, thevarious methods utilized, what qualitative analyses into the characteristics ofhuman versus ChatGPT-generated text have been performed, and finally, summarizeour findings into general insights
{{< /details >}}

[**An Adaptive Federated Relevance Framework for Spatial Temporal Graph Learning**](http://arxiv.org/abs/2206.03420v3)

*Tiehua Zhang, Yuze Liu, Zhishu Shen, Rui Xu, Xin Chen, Xiaowei Huang, Xi Zheng*

{{< details "abstract" >}} abstract: Spatial-temporal data contains rich information and has been widely studiedin recent years due to the rapid development of relevant applications in manyfields. For instance, medical institutions often use electrodes attached todifferent parts of a patient to analyse the electorencephal data rich withspatial and temporal features for health assessment and disease diagnosis.Existing research has mainly used deep learning techniques such asconvolutional neural network (CNN) or recurrent neural network (RNN) to extracthidden spatial-temporal features. Yet, it is challenging to incorporate bothinter-dependencies spatial information and dynamic temporal changessimultaneously. In reality, for a model that leverages these spatial-temporalfeatures to fulfil complex prediction tasks, it often requires a colossalamount of training data in order to obtain satisfactory model performance.Considering the above-mentioned challenges, we propose an adaptive federatedrelevance framework, namely FedRel, for spatial-temporal graph learning in thispaper. After transforming the raw spatial-temporal data into high qualityfeatures, the core Dynamic Inter-Intra Graph (DIIG) module in the framework isable to use these features to generate the spatial-temporal graphs capable ofcapturing the hidden topological and long-term temporal correlation informationin these graphs. To improve the model generalization ability and performancewhile preserving the local data privacy, we also design a relevance-drivenfederated learning module in our framework to leverage diverse datadistributions from different participants with attentive aggregations of theirmodels.
{{< /details >}}

[**Preventing Unauthorized AI Over-Analysis by Medical Image Adversarial Watermarking**](http://arxiv.org/abs/2303.09858v3)

*Xingxing Wei, Bangzheng Pu, Shiji Zhao, Chen Chi, Huazhu Fu*

{{< details "abstract" >}} abstract: The advancement of deep learning has facilitated the integration ofArtificial Intelligence (AI) into clinical practices, particularly incomputer-aided diagnosis. Given the pivotal role of medical images in variousdiagnostic procedures, it becomes imperative to ensure the responsible andsecure utilization of AI techniques. However, the unauthorized utilization ofAI for image analysis raises significant concerns regarding patient privacy andpotential infringement on the proprietary rights of data custodians.Consequently, the development of pragmatic and cost-effective strategies thatsafeguard patient privacy and uphold medical image copyrights emerges as acritical necessity. In direct response to this pressing demand, we present apioneering solution named Medical Image Adversarial watermarking (MIAD-MARK).Our approach introduces watermarks that strategically mislead unauthorized AIdiagnostic models, inducing erroneous predictions without compromising theintegrity of the visual content. Importantly, our method integrates anauthorization protocol tailored for legitimate users, enabling the removal ofthe MIAD-MARK through encryption-generated keys. Through extensive experiments,we validate the efficacy of MIAD-MARK across three prominent medical imagedatasets. The empirical outcomes demonstrate the substantial impact of ourapproach, notably reducing the accuracy of standard AI diagnostic models to amere 8.57% under white box conditions and 45.83% in the more challenging blackbox scenario. Additionally, our solution effectively mitigates unauthorizedexploitation of medical images even in the presence of sophisticated watermarkremoval networks. Notably, those AI diagnosis networks exhibit a meager averageaccuracy of 38.59% when applied to images protected by MIAD-MARK, underscoringthe robustness of our safeguarding mechanism.
{{< /details >}}

>**_2023-09-11_**

[**Preventing Verbatim Memorization in Language Models Gives a False Sense of Privacy**](http://arxiv.org/abs/2210.17546v3)

*Daphne Ippolito, Florian Tramèr, Milad Nasr, Chiyuan Zhang, Matthew Jagielski, Katherine Lee, Christopher A. Choquette-Choo, Nicholas Carlini*

{{< details "abstract" >}} abstract: Studying data memorization in neural language models helps us understand therisks (e.g., to privacy or copyright) associated with models regurgitatingtraining data and aids in the development of countermeasures. Many prior works-- and some recently deployed defenses -- focus on "verbatim memorization",defined as a model generation that exactly matches a substring from thetraining set. We argue that verbatim memorization definitions are toorestrictive and fail to capture more subtle forms of memorization.Specifically, we design and implement an efficient defense that perfectlyprevents all verbatim memorization. And yet, we demonstrate that this "perfect"filter does not prevent the leakage of training data. Indeed, it is easilycircumvented by plausible and minimally modified "style-transfer" prompts --and in some cases even the non-modified original prompts -- to extractmemorized information. We conclude by discussing potential alternativedefinitions and why defining memorization is a difficult yet crucial openquestion for neural language models.
{{< /details >}}

[**Black-Box Analysis: GPTs Across Time in Legal Textual Entailment Task**](http://arxiv.org/abs/2309.05501v1)

*Ha-Thanh Nguyen, Randy Goebel, Francesca Toni, Kostas Stathis, Ken Satoh*

{{< details "abstract" >}} abstract: The evolution of Generative Pre-trained Transformer (GPT) models has led tosignificant advancements in various natural language processing applications,particularly in legal textual entailment. We present an analysis of GPT-3.5(ChatGPT) and GPT-4 performances on COLIEE Task 4 dataset, a prominentbenchmark in this domain. The study encompasses data from Heisei 18 (2006) toReiwa 3 (2021), exploring the models' abilities to discern entailmentrelationships within Japanese statute law across different periods. Ourpreliminary experimental results unveil intriguing insights into the models'strengths and weaknesses in handling legal textual entailment tasks, as well asthe patterns observed in model performance. In the context of proprietarymodels with undisclosed architectures and weights, black-box analysis becomescrucial for evaluating their capabilities. We discuss the influence of trainingdata distribution and the implications on the models' generalizability. Thisanalysis serves as a foundation for future research, aiming to optimizeGPT-based models and enable their successful adoption in legal informationextraction and entailment applications.
{{< /details >}}

>**_2023-09-07_**

[**VeriDIP: Verifying Ownership of Deep Neural Networks through Privacy Leakage Fingerprints**](http://arxiv.org/abs/2310.10656v1)

*Aoting Hu, Zhigang Lu, Renjie Xie, Minhui Xue*

{{< details "abstract" >}} abstract: Deploying Machine Learning as a Service gives rise to model plagiarism,leading to copyright infringement. Ownership testing techniques are designed toidentify model fingerprints for verifying plagiarism. However, previous worksoften rely on overfitting or robustness features as fingerprints, lackingtheoretical guarantees and exhibiting under-performance on generalized models.In this paper, we propose a novel ownership testing method called VeriDIP,which verifies a DNN model's intellectual property. VeriDIP makes two majorcontributions. (1) It utilizes membership inference attacks to estimate thelower bound of privacy leakage, which reflects the fingerprint of a givenmodel. The privacy leakage fingerprints highlight the unique patterns throughwhich the models memorize sensitive training datasets. (2) We introduce a novelapproach using less private samples to enhance the performance of ownershiptesting.  Extensive experimental results confirm that VeriDIP is effective andefficient in validating the ownership of deep learning models trained on bothimage and tabular datasets. VeriDIP achieves comparable performance tostate-of-the-art methods on image datasets while significantly reducingcomputation and communication costs. Enhanced VeriDIP demonstrates superiorverification performance on generalized deep learning models, particularly ontable-trained models. Additionally, VeriDIP exhibits similar effectiveness onutility-preserving differentially private models compared to non-differentiallyprivate baselines.
{{< /details >}}

[**MIRA: Cracking Black-box Watermarking on Deep Neural Networks via Model Inversion-based Removal Attacks**](http://arxiv.org/abs/2309.03466v1)

*Yifan Lu, Wenxuan Li, Mi Zhang, Xudong Pan, Min Yang*

{{< details "abstract" >}} abstract: To protect the intellectual property of well-trained deep neural networks(DNNs), black-box DNN watermarks, which are embedded into the predictionbehavior of DNN models on a set of specially-crafted samples, have gainedincreasing popularity in both academy and industry. Watermark robustness isusually implemented against attackers who steal the protected model andobfuscate its parameters for watermark removal. Recent studies empiricallyprove the robustness of most black-box watermarking schemes against knownremoval attempts.  In this paper, we propose a novel Model Inversion-based Removal Attack(\textsc{Mira}), which is watermark-agnostic and effective against most ofmainstream black-box DNN watermarking schemes. In general, our attack pipelineexploits the internals of the protected model to recover and unlearn thewatermark message. We further design target class detection and recoveredsample splitting algorithms to reduce the utility loss caused by \textsc{Mira}and achieve data-free watermark removal on half of the watermarking schemes. Weconduct comprehensive evaluation of \textsc{Mira} against ten mainstreamblack-box watermarks on three benchmark datasets and DNN architectures.Compared with six baseline removal attacks, \textsc{Mira} achieves strongwatermark removal effects on the covered watermarks, preserving at least $90\%$of the stolen model utility, under more relaxed or even no assumptions on thedataset availability.
{{< /details >}}

>**_2023-09-05_**

[**Boosting the Adversarial Transferability of Surrogate Models with Dark Knowledge**](http://arxiv.org/abs/2206.08316v2)

*Dingcheng Yang, Zihao Xiao, Wenjian Yu*

{{< details "abstract" >}} abstract: Deep neural networks (DNNs) are vulnerable to adversarial examples. And, theadversarial examples have transferability, which means that an adversarialexample for a DNN model can fool another model with a non-trivial probability.This gave birth to the transfer-based attack where the adversarial examplesgenerated by a surrogate model are used to conduct black-box attacks. There aresome work on generating the adversarial examples from a given surrogate modelwith better transferability. However, training a special surrogate model togenerate adversarial examples with better transferability is relativelyunder-explored. This paper proposes a method for training a surrogate modelwith dark knowledge to boost the transferability of the adversarial examplesgenerated by the surrogate model. This trained surrogate model is named darksurrogate model (DSM). The proposed method for training a DSM consists of twokey components: a teacher model extracting dark knowledge, and the mixingaugmentation skill enhancing dark knowledge of training data. We conductedextensive experiments to show that the proposed method can substantiallyimprove the adversarial transferability of surrogate models across differentarchitectures of surrogate models and optimizers for generating adversarialexamples, and it can be applied to other scenarios of transfer-based attackthat contain dark knowledge, like face verification. Our code is publiclyavailable at \url{https://github.com/ydc123/Dark_Surrogate_Model}.
{{< /details >}}

[**Incorporating Dictionaries into a Neural Network Architecture to Extract COVID-19 Medical Concepts From Social Media**](http://arxiv.org/abs/2309.02188v1)

*Abul Hasan, Mark Levene, David Weston*

{{< details "abstract" >}} abstract: We investigate the potential benefit of incorporating dictionary informationinto a neural network architecture for natural language processing. Inparticular, we make use of this architecture to extract several conceptsrelated to COVID-19 from an on-line medical forum. We use a sample from theforum to manually curate one dictionary for each concept. In addition, we useMetaMap, which is a tool for extracting biomedical concepts, to identify asmall number of semantic concepts. For a supervised concept extraction task onthe forum data, our best model achieved a macro $F_1$ score of 90\%. A majordifficulty in medical concept extraction is obtaining labelled data from whichto build supervised models. We investigate the utility of our models totransfer to data derived from a different source in two ways. First forproducing labels via weak learning and second to perform concept extraction.The dataset we use in this case comprises COVID-19 related tweets and weachieve an $F_1$ score 81\% for symptom concept extraction trained on weaklylabelled data. The utility of our dictionaries is compared with a COVID-19symptom dictionary that was constructed directly from Twitter. Furtherexperiments that incorporate BERT and a COVID-19 version of BERTweetdemonstrate that the dictionaries provide a commensurate result. Our resultsshow that incorporating small domain dictionaries to deep learning models canimprove concept extraction tasks. Moreover, models built using dictionariesgeneralize well and are transferable to different datasets on a similar task.
{{< /details >}}

>**_2023-09-01_**

[**GrOVe: Ownership Verification of Graph Neural Networks using Embeddings**](http://arxiv.org/abs/2304.08566v2)

*Asim Waheed, Vasisht Duddu, N. Asokan*

{{< details "abstract" >}} abstract: Graph neural networks (GNNs) have emerged as a state-of-the-art approach tomodel and draw inferences from large scale graph-structured data in variousapplication settings such as social networking. The primary goal of a GNN is tolearn an embedding for each graph node in a dataset that encodes both the nodefeatures and the local graph structure around the node. Embeddings generated bya GNN for a graph node are unique to that GNN. Prior work has shown that GNNsare prone to model extraction attacks. Model extraction attacks and defenseshave been explored extensively in other non-graph settings. While detecting orpreventing model extraction appears to be difficult, deterring them viaeffective ownership verification techniques offer a potential defense. Innon-graph settings, fingerprinting models, or the data used to build them, haveshown to be a promising approach toward ownership verification. We presentGrOVe, a state-of-the-art GNN model fingerprinting scheme that, given a targetmodel and a suspect model, can reliably determine if the suspect model wastrained independently of the target model or if it is a surrogate of the targetmodel obtained via model extraction. We show that GrOVe can distinguish betweensurrogate and independent models even when the independent model uses the sametraining dataset and architecture as the original target model. Using sixbenchmark datasets and three model architectures, we show that consistentlyachieves low false-positive and false-negative rates. We demonstrate that isrobust against known fingerprint evasion techniques while remainingcomputationally efficient.
{{< /details >}}

>**_2023-08-30_**

[**iWarpGAN: Disentangling Identity and Style to Generate Synthetic Iris Images**](http://arxiv.org/abs/2305.12596v2)

*Shivangi Yadav, Arun Ross*

{{< details "abstract" >}} abstract: Generative Adversarial Networks (GANs) have shown success in approximatingcomplex distributions for synthetic image generation. However, currentGAN-based methods for generating biometric images, such as iris, have certainlimitations: (a) the synthetic images often closely resemble images in thetraining dataset; (b) the generated images lack diversity in terms of thenumber of unique identities represented in them; and (c) it is difficult togenerate multiple images pertaining to the same identity. To overcome theseissues, we propose iWarpGAN that disentangles identity and style in the contextof the iris modality by using two transformation pathways: IdentityTransformation Pathway to generate unique identities from the training set, andStyle Transformation Pathway to extract the style code from a reference imageand output an iris image using this style. By concatenating the transformedidentity code and reference style code, iWarpGAN generates iris images withboth inter- and intra-class variations. The efficacy of the proposed method ingenerating such iris DeepFakes is evaluated both qualitatively andquantitatively using ISO/IEC 29794-6 Standard Quality Metrics and the VeriEyeiris matcher. Further, the utility of the synthetically generated images isdemonstrated by improving the performance of deep learning based iris matchersthat augment synthetic data with real data during the training process.
{{< /details >}}

>**_2023-08-29_**

[**EquiDiff: A Conditional Equivariant Diffusion Model For Trajectory Prediction**](http://arxiv.org/abs/2308.06564v2)

*Kehua Chen, Xianda Chen, Zihan Yu, Meixin Zhu, Hai Yang*

{{< details "abstract" >}} abstract: Accurate trajectory prediction is crucial for the safe and efficientoperation of autonomous vehicles. The growing popularity of deep learning hasled to the development of numerous methods for trajectory prediction. Whiledeterministic deep learning models have been widely used, deep generativemodels have gained popularity as they learn data distributions from trainingdata and account for trajectory uncertainties. In this study, we proposeEquiDiff, a deep generative model for predicting future vehicle trajectories.EquiDiff is based on the conditional diffusion model, which generates futuretrajectories by incorporating historical information and random Gaussian noise.The backbone model of EquiDiff is an SO(2)-equivariant transformer that fullyutilizes the geometric properties of location coordinates. In addition, weemploy Recurrent Neural Networks and Graph Attention Networks to extract socialinteractions from historical trajectories. To evaluate the performance ofEquiDiff, we conduct extensive experiments on the NGSIM dataset. Our resultsdemonstrate that EquiDiff outperforms other baseline models in short-termprediction, but has slightly higher errors for long-term prediction.Furthermore, we conduct an ablation study to investigate the contribution ofeach component of EquiDiff to the prediction accuracy. Additionally, we presenta visualization of the generation process of our diffusion model, providinginsights into the uncertainty of the prediction.
{{< /details >}}

>**_2023-08-27_**

[**Can GitHub Issues Help in the App Review Classifications?**](http://arxiv.org/abs/2308.14211v1)

*Yasaman Abedini, Abbas Heydarnoori*

{{< details "abstract" >}} abstract: App reviews reflect various user requirements that can aid in planningmaintenance tasks. Recently, proposed approaches for automatically classifyinguser reviews rely on machine learning algorithms. Devine et al. demonstratedthat models trained on existing labeled datasets exhibit poor performance whenpredicting new ones. Although integrating datasets improves the results to someextent, there is still a need for greater generalizability to be taken intoconsideration. Therefore, a comprehensive labeled dataset is essential to traina more precise model. This paper introduces an approach to train a moregeneralizable model by leveraging information from an additional source, suchas the GitHub issue tracking system, that contains valuable information aboutuser requirements. We propose an approach that assists in augmenting labeleddatasets by utilizing information extracted from GitHub issues. First, weidentify issues concerning review intentions (bug reports, feature requests,and others) by examining the issue labels. Then, we analyze issue bodies anddefine 19 language patterns for extracting targeted information. Finally, weaugment the manually labeled review dataset with a subset of processed issuesthrough the Within-App, Within-Context, and Between-App Analysis methods. Thefirst two methods train the app-specific models, and the last suits thegeneral-purpose models. We conducted several experiments to evaluate theproposed approach. Our results demonstrate that using labeled issues for dataaugmentation can improve the F1-score and recall to 13.9 and 29.9 in the bugreports, respectively, and to 7.5 and 13.5 for feature requests. Furthermore,we identify an effective volume range of 0.3 to 0.7, which provides betterperformance improvements.
{{< /details >}}

[**Protecting Language Generation Models via Invisible Watermarking**](http://arxiv.org/abs/2302.03162v3)

*Xuandong Zhao, Yu-Xiang Wang, Lei Li*

{{< details "abstract" >}} abstract: Language generation models have been an increasingly powerful enabler formany applications. Many such models offer free or affordable API access, whichmakes them potentially vulnerable to model extraction attacks throughdistillation. To protect intellectual property (IP) and ensure fair use ofthese models, various techniques such as lexical watermarking and synonymreplacement have been proposed. However, these methods can be nullified byobvious countermeasures such as "synonym randomization". To address this issue,we propose GINSEW, a novel method to protect text generation models from beingstolen through distillation. The key idea of our method is to inject secretsignals into the probability vector of the decoding steps for each targettoken. We can then detect the secret message by probing a suspect model to tellif it is distilled from the protected one. Experimental results show thatGINSEW can effectively identify instances of IP infringement with minimalimpact on the generation quality of protected APIs. Our method demonstrates anabsolute improvement of 19 to 29 points on mean average precision (mAP) indetecting suspects compared to previous methods against watermark removalattacks.
{{< /details >}}

>**_2023-08-23_**

[**How to Protect Copyright Data in Optimization of Large Language Models?**](http://arxiv.org/abs/2308.12247v1)

*Timothy Chu, Zhao Song, Chiwun Yang*

{{< details "abstract" >}} abstract: Large language models (LLMs) and generative AI have played a transformativerole in computer research and applications. Controversy has arisen as towhether these models output copyrighted data, which can occur if the data themodels are trained on is copyrighted. LLMs are built on the transformer neuralnetwork architecture, which in turn relies on a mathematical computation calledAttention that uses the softmax function.  In this paper, we show that large language model training and optimizationcan be seen as a softmax regression problem. We then establish a method ofefficiently performing softmax regression, in a way that prevents theregression function from generating copyright data. This establishes atheoretical method of training large language models in a way that avoidsgenerating copyright data.
{{< /details >}}

>**_2023-08-22_**

[**Adversarial Attacks on Code Models with Discriminative Graph Patterns**](http://arxiv.org/abs/2308.11161v1)

*Thanh-Dat Nguyen, Yang Zhou, Xuan Bach D. Le, Patanamon, Thongtanunam, David Lo*

{{< details "abstract" >}} abstract: Pre-trained language models of code are now widely used in various softwareengineering tasks such as code generation, code completion, vulnerabilitydetection, etc. This, in turn, poses security and reliability risks to thesemodels. One of the important threats is \textit{adversarial attacks}, which canlead to erroneous predictions and largely affect model performance ondownstream tasks. Current adversarial attacks on code models usually adoptfixed sets of program transformations, such as variable renaming and dead codeinsertion, leading to limited attack effectiveness. To address theaforementioned challenges, we propose a novel adversarial attack framework,GraphCodeAttack, to better evaluate the robustness of code models. Given atarget code model, GraphCodeAttack automatically mines important code patterns,which can influence the model's decisions, to perturb the structure of inputcode to the model. To do so, GraphCodeAttack uses a set of input source codesto probe the model's outputs and identifies the \textit{discriminative} ASTspatterns that can influence the model decisions. GraphCodeAttack then selectsappropriate AST patterns, concretizes the selected patterns as attacks, andinserts them as dead code into the model's input program. To effectivelysynthesize attacks from AST patterns, GraphCodeAttack uses a separatepre-trained code model to fill in the ASTs with concrete code snippets. Weevaluate the robustness of two popular code models (e.g., CodeBERT andGraphCodeBERT) against our proposed approach on three tasks: AuthorshipAttribution, Vulnerability Prediction, and Clone Detection. The experimentalresults suggest that our proposed approach significantly outperformsstate-of-the-art approaches in attacking code models such as CARROT and ALERT.
{{< /details >}}

>**_2023-08-21_**

[**Learning in Dynamic Systems and Its Application to Adaptive PID Control**](http://arxiv.org/abs/2308.10851v1)

*Omar Makke, Feng Lin*

{{< details "abstract" >}} abstract: Deep learning using neural networks has revolutionized machine learning andput artificial intelligence into everyday life. In order to introduceself-learning to dynamic systems other than neural networks, we extend theBrandt-Lin learning algorithm of neural networks to a large class of dynamicsystems. This extension is possible because the Brandt-Lin algorithm does notrequire a dedicated step to back-propagate the errors in neural networks. Tothis end, we first generalize signal-flow graphs so that they can be used tomodel nonlinear systems as well as linear systems. We then derive the extendedBrandt-Lin algorithm that can be used to adapt the weights of branches ingeneralized signal-flow graphs. We show the applications of the new algorithmby applying it to adaptive PID control. In particular, we derive a newadaptation law for PID controllers. We verify the effectiveness of the methodusing simulations for linear and nonlinear plants, stable as well as unstableplants.
{{< /details >}}

>**_2023-08-19_**

[**DUAW: Data-free Universal Adversarial Watermark against Stable Diffusion Customization**](http://arxiv.org/abs/2308.09889v1)

*Xiaoyu Ye, Hao Huang, Jiaqi An, Yongtao Wang*

{{< details "abstract" >}} abstract: Stable Diffusion (SD) customization approaches enable users to personalize SDmodel outputs, greatly enhancing the flexibility and diversity of AI art.However, they also allow individuals to plagiarize specific styles or subjectsfrom copyrighted images, which raises significant concerns about potentialcopyright infringement. To address this issue, we propose an invisibledata-free universal adversarial watermark (DUAW), aiming to protect a myriad ofcopyrighted images from different customization approaches across variousversions of SD models. First, DUAW is designed to disrupt the variationalautoencoder during SD customization. Second, DUAW operates in a data-freecontext, where it is trained on synthetic images produced by a Large LanguageModel (LLM) and a pretrained SD model. This approach circumvents the necessityof directly handling copyrighted images, thereby preserving theirconfidentiality. Once crafted, DUAW can be imperceptibly integrated intomassive copyrighted images, serving as a protective measure by inducingsignificant distortions in the images generated by customized SD models.Experimental results demonstrate that DUAW can effectively distort the outputsof fine-tuned SD models, rendering them discernible to both human observers anda simple classifier.
{{< /details >}}

>**_2023-08-16_**

[**Graph Out-of-Distribution Generalization with Controllable Data Augmentation**](http://arxiv.org/abs/2308.08344v1)

*Bin Lu, Xiaoying Gan, Ze Zhao, Shiyu Liang, Luoyi Fu, Xinbing Wang, Chenghu Zhou*

{{< details "abstract" >}} abstract: Graph Neural Network (GNN) has demonstrated extraordinary performance inclassifying graph properties. However, due to the selection bias of trainingand testing data (e.g., training on small graphs and testing on large graphs,or training on dense graphs and testing on sparse graphs), distributiondeviation is widespread. More importantly, we often observe \emph{hybridstructure distribution shift} of both scale and density, despite of one-sidedbiased data partition. The spurious correlations over hybrid distributiondeviation degrade the performance of previous GNN methods and show largeinstability among different datasets. To alleviate this problem, we propose\texttt{OOD-GMixup} to jointly manipulate the training distribution with\emph{controllable data augmentation} in metric space. Specifically, we firstextract the graph rationales to eliminate the spurious correlations due toirrelevant information. Secondly, we generate virtual samples with perturbationon graph rationale representation domain to obtain potential OOD trainingsamples. Finally, we propose OOD calibration to measure the distributiondeviation of virtual samples by leveraging Extreme Value Theory, and furtheractively control the training distribution by emphasizing the impact of virtualOOD samples. Extensive studies on several real-world datasets on graphclassification demonstrate the superiority of our proposed method overstate-of-the-art baselines.
{{< /details >}}

>**_2023-08-14_**

[**Knowledge Prompt-tuning for Sequential Recommendation**](http://arxiv.org/abs/2308.08459v1)

*Jianyang Zhai, Xiawu Zheng, Chang-Dong Wang, Hui Li, Yonghong Tian*

{{< details "abstract" >}} abstract: Pre-trained language models (PLMs) have demonstrated strong performance insequential recommendation (SR), which are utilized to extract generalknowledge. However, existing methods still lack domain knowledge and struggleto capture users' fine-grained preferences. Meanwhile, many traditional SRmethods improve this issue by integrating side information while suffering frominformation loss. To summarize, we believe that a good recommendation systemshould utilize both general and domain knowledge simultaneously. Therefore, weintroduce an external knowledge base and propose Knowledge Prompt-tuning forSequential Recommendation (\textbf{KP4SR}). Specifically, we construct a set ofrelationship templates and transform a structured knowledge graph (KG) intoknowledge prompts to solve the problem of the semantic gap. However, knowledgeprompts disrupt the original data structure and introduce a significant amountof noise. We further construct a knowledge tree and propose a knowledge treemask, which restores the data structure in a mask matrix form, thus mitigatingthe noise problem. We evaluate KP4SR on three real-world datasets, andexperimental results show that our approach outperforms state-of-the-artmethods on multiple evaluation metrics. Specifically, compared with PLM-basedmethods, our method improves NDCG@5 and HR@5 by \textcolor{red}{40.65\%} and\textcolor{red}{36.42\%} on the books dataset, \textcolor{red}{11.17\%} and\textcolor{red}{11.47\%} on the music dataset, and \textcolor{red}{22.17\%} and\textcolor{red}{19.14\%} on the movies dataset, respectively. Our code ispublicly available at the link:\href{https://github.com/zhaijianyang/KP4SR}{\textcolor{blue}{https://github.com/zhaijianyang/KP4SR}.}
{{< /details >}}

[**Neural Authorship Attribution: Stylometric Analysis on Large Language Models**](http://arxiv.org/abs/2308.07305v1)

*Tharindu Kumarage, Huan Liu*

{{< details "abstract" >}} abstract: Large language models (LLMs) such as GPT-4, PaLM, and Llama havesignificantly propelled the generation of AI-crafted text. With rising concernsabout their potential misuse, there is a pressing need for AI-generated-textforensics. Neural authorship attribution is a forensic effort, seeking to traceAI-generated text back to its originating LLM. The LLM landscape can be dividedinto two primary categories: proprietary and open-source. In this work, wedelve into these emerging categories of LLMs, focusing on the nuances of neuralauthorship attribution. To enrich our understanding, we carry out an empiricalanalysis of LLM writing signatures, highlighting the contrasts betweenproprietary and open-source models, and scrutinizing variations within eachgroup. By integrating stylometric features across lexical, syntactic, andstructural aspects of language, we explore their potential to yieldinterpretable results and augment pre-trained language model-based classifiersutilized in neural authorship attribution. Our findings, based on a range ofstate-of-the-art LLMs, provide empirical insights into neural authorshipattribution, paving the way for future investigations aimed at mitigating thethreats posed by AI-generated misinformation.
{{< /details >}}

>**_2023-08-09_**

[**DiverseVul: A New Vulnerable Source Code Dataset for Deep Learning Based Vulnerability Detection**](http://arxiv.org/abs/2304.00409v2)

*Yizheng Chen, Zhoujie Ding, Lamya Alowain, Xinyun Chen, David Wagner*

{{< details "abstract" >}} abstract: We propose and release a new vulnerable source code dataset. We curate thedataset by crawling security issue websites, extracting vulnerability-fixingcommits and source codes from the corresponding projects. Our new datasetcontains 18,945 vulnerable functions spanning 150 CWEs and 330,492non-vulnerable functions extracted from 7,514 commits. Our dataset covers 295more projects than all previous datasets combined.  Combining our new dataset with previous datasets, we present an analysis ofthe challenges and promising research directions of using deep learning fordetecting software vulnerabilities. We study 11 model architectures belongingto 4 families. Our results show that deep learning is still not ready forvulnerability detection, due to high false positive rate, low F1 score, anddifficulty of detecting hard CWEs. In particular, we demonstrate an importantgeneralization challenge for the deployment of deep learning-based models. Weshow that increasing the volume of training data may not further improve theperformance of deep learning models for vulnerability detection, but might beuseful to improve the generalization ability to unseen projects.  We also identify hopeful future research directions. We demonstrate thatlarge language models (LLMs) are a promising research direction for ML-basedvulnerability detection, outperforming Graph Neural Networks (GNNs) withcode-structure features in our experiments. Moreover, developing source codespecific pre-training objectives is a promising research direction to improvethe vulnerability detection performance.
{{< /details >}}

>**_2023-08-06_**

[**Semantic-Guided Feature Distillation for Multimodal Recommendation**](http://arxiv.org/abs/2308.03113v1)

*Fan Liu, Huilin Chen, Zhiyong Cheng, Liqiang Nie, Mohan Kankanhalli*

{{< details "abstract" >}} abstract: Multimodal recommendation exploits the rich multimodal information associatedwith users or items to enhance the representation learning for betterperformance. In these methods, end-to-end feature extractors (e.g.,shallow/deep neural networks) are often adopted to tailor the genericmultimodal features that are extracted from raw data by pre-trained models forrecommendation. However, compact extractors, such as shallow neural networks,may find it challenging to extract effective information from complex andhigh-dimensional generic modality features. Conversely, DNN-based extractorsmay encounter the data sparsity problem in recommendation. To address thisproblem, we propose a novel model-agnostic approach called Semantic-guidedFeature Distillation (SGFD), which employs a teacher-student framework toextract feature for multimodal recommendation. The teacher model first extractsrich modality features from the generic modality feature by considering boththe semantic information of items and the complementary information of multiplemodalities. SGFD then utilizes response-based and feature-based distillationloss to effectively transfer the knowledge encoded in the teacher model to thestudent model. To evaluate the effectiveness of our SGFD, we integrate SGFDinto three backbone multimodal recommendation models. Extensive experiments onthree public real-world datasets demonstrate that SGFD-enhanced models canachieve substantial improvement over their counterparts.
{{< /details >}}

>**_2023-08-03_**

[**MusicLDM: Enhancing Novelty in Text-to-Music Generation Using Beat-Synchronous Mixup Strategies**](http://arxiv.org/abs/2308.01546v1)

*Ke Chen, Yusong Wu, Haohe Liu, Marianna Nezhurina, Taylor Berg-Kirkpatrick, Shlomo Dubnov*

{{< details "abstract" >}} abstract: Diffusion models have shown promising results in cross-modal generationtasks, including text-to-image and text-to-audio generation. However,generating music, as a special type of audio, presents unique challenges due tolimited availability of music data and sensitive issues related to copyrightand plagiarism. In this paper, to tackle these challenges, we first construct astate-of-the-art text-to-music model, MusicLDM, that adapts Stable Diffusionand AudioLDM architectures to the music domain. We achieve this by retrainingthe contrastive language-audio pretraining model (CLAP) and the Hifi-GANvocoder, as components of MusicLDM, on a collection of music data samples.Then, to address the limitations of training data and to avoid plagiarism, weleverage a beat tracking model and propose two different mixup strategies fordata augmentation: beat-synchronous audio mixup and beat-synchronous latentmixup, which recombine training audio directly or via a latent embeddingsspace, respectively. Such mixup strategies encourage the model to interpolatebetween musical training samples and generate new music within the convex hullof the training data, making the generated music more diverse while stillstaying faithful to the corresponding style. In addition to popular evaluationmetrics, we design several new evaluation metrics based on CLAP score todemonstrate that our proposed MusicLDM and beat-synchronous mixup strategiesimprove both the quality and novelty of generated music, as well as thecorrespondence between input text and generated music.
{{< /details >}}

>**_2023-07-28_**

[**RAWIW: RAW Image Watermarking Robust to ISP Pipeline**](http://arxiv.org/abs/2307.15443v1)

*Kang Fu, Xiaohong Liu, Jun Jia, Zicheng Zhang, Yicong Peng, Jia Wang, Guangtao Zhai*

{{< details "abstract" >}} abstract: Invisible image watermarking is essential for image copyright protection.Compared to RGB images, RAW format images use a higher dynamic range to capturethe radiometric characteristics of the camera sensor, providing greaterflexibility in post-processing and retouching. Similar to the master recordingin the music industry, RAW images are considered the original format fordistribution and image production, thus requiring copyright protection.Existing watermarking methods typically target RGB images, leaving a gap forRAW images. To address this issue, we propose the first deep learning-based RAWImage Watermarking (RAWIW) framework for copyright protection. Unlike RGB imagewatermarking, our method achieves cross-domain copyright protection. Wedirectly embed copyright information into RAW images, which can be laterextracted from the corresponding RGB images generated by differentpost-processing methods. To achieve end-to-end training of the framework, weintegrate a neural network that simulates the ISP pipeline to handle theRAW-to-RGB conversion process. To further validate the generalization of ourframework to traditional ISP pipelines and its robustness to transmissiondistortion, we adopt a distortion network. This network simulates various typesof noises introduced during the traditional ISP pipeline and transmission.Furthermore, we employ a three-stage training strategy to strike a balancebetween robustness and concealment of watermarking. Our extensive experimentsdemonstrate that RAWIW successfully achieves cross-domain copyright protectionfor RAW images while maintaining their visual quality and robustness to ISPpipeline distortions.
{{< /details >}}

>**_2023-07-24_**

[**Broken Neural Scaling Laws**](http://arxiv.org/abs/2210.14891v17)

*Ethan Caballero, Kshitij Gupta, Irina Rish, David Krueger*

{{< details "abstract" >}} abstract: We present a smoothly broken power law functional form (that we refer to as aBroken Neural Scaling Law (BNSL)) that accurately models & extrapolates thescaling behaviors of deep neural networks (i.e. how the evaluation metric ofinterest varies as amount of compute used for training (or inference), numberof model parameters, training dataset size, model input size, number oftraining steps, or upstream performance varies) for various architectures & foreach of various tasks within a large & diverse set of upstream & downstreamtasks, in zero-shot, prompted, & finetuned settings. This set includeslarge-scale vision, language, audio, video, diffusion, generative modeling,multimodal learning, contrastive learning, AI alignment, AI capabilities,robotics, out-of-distribution (OOD) generalization, continual learning,transfer learning, uncertainty estimation / calibration, OOD detection,adversarial robustness, distillation, sparsity, retrieval, quantization,pruning, fairness, molecules, computer programming/coding, math word problems,"emergent phase transitions", arithmetic, supervised learning,unsupervised/self-supervised learning, & reinforcement learning (single agent &multi-agent). When compared to other functional forms for neural scaling, thisfunctional form yields extrapolations of scaling behavior that are considerablymore accurate on this set. Moreover, this functional form accurately models &extrapolates scaling behavior that other functional forms are incapable ofexpressing such as the nonmonotonic transitions present in the scaling behaviorof phenomena such as double descent & the delayed, sharp inflection pointspresent in the scaling behavior of tasks such as arithmetic. Lastly, we usethis functional form to glean insights about the limit of the predictability ofscaling behavior. Code is available athttps://github.com/ethancaballero/broken_neural_scaling_laws
{{< /details >}}

>**_2023-07-21_**

[**On Provable Copyright Protection for Generative Models**](http://arxiv.org/abs/2302.10870v2)

*Nikhil Vyas, Sham Kakade, Boaz Barak*

{{< details "abstract" >}} abstract: There is a growing concern that learned conditional generative models mayoutput samples that are substantially similar to some copyrighted data $C$ thatwas in their training set. We give a formal definition of $\textit{nearaccess-freeness (NAF)}$ and prove bounds on the probability that a modelsatisfying this definition outputs a sample similar to $C$, even if $C$ isincluded in its training set. Roughly speaking, a generative model $p$ is$\textit{$k$-NAF}$ if for every potentially copyrighted data $C$, the output of$p$ diverges by at most $k$-bits from the output of a model $q$ that$\textit{did not access $C$ at all}$. We also give generative model learningalgorithms, which efficiently modify the original generative model learningalgorithm in a black box manner, that output generative models with strongbounds on the probability of sampling protected content. Furthermore, weprovide promising experiments for both language (transformers) and image(diffusion) generative models, showing minimal degradation in output qualitywhile ensuring strong protections against sampling protected content.
{{< /details >}}

>**_2023-07-20_**

[**Exploring Perspectives on the Impact of Artificial Intelligence on the Creativity of Knowledge Work: Beyond Mechanised Plagiarism and Stochastic Parrots**](http://arxiv.org/abs/2307.10751v1)

*Advait Sarkar*

{{< details "abstract" >}} abstract: Artificial Intelligence (AI), and in particular generative models, aretransformative tools for knowledge work. They problematise notions ofcreativity, originality, plagiarism, the attribution of credit, and copyrightownership. Critics of generative models emphasise the reliance on large amountsof training data, and view the output of these models as no more thanrandomised plagiarism, remix, or collage of the source data. On these grounds,many have argued for stronger regulations on the deployment, use, andattribution of the output of these models. However, these issues are not new orunique to artificial intelligence. In this position paper, using examples fromliterary criticism, the history of art, and copyright law, I show howcreativity and originality resist definition as a notatable orinformation-theoretic property of an object, and instead can be seen as theproperty of a process, an author, or a viewer. Further alternative views holdthat all creative work is essentially reuse (mostly without attribution), orthat randomness itself can be creative. I suggest that creativity is ultimatelydefined by communities of creators and receivers, and the deemed sources ofcreativity in a workflow often depend on which parts of the workflow can beautomated. Using examples from recent studies of AI in creative knowledge work,I suggest that AI shifts knowledge work from material production to criticalintegration. This position paper aims to begin a conversation around a morenuanced approach to the problems of creativity and credit assignment forgenerative models, one which more fully recognises the importance of thecreative and curatorial voice of the users of these models and moves away fromsimpler notational or information-theoretic views.
{{< /details >}}

>**_2023-07-17_**

[**Image Captions are Natural Prompts for Text-to-Image Models**](http://arxiv.org/abs/2307.08526v1)

*Shiye Lei, Hao Chen, Sen Zhang, Bo Zhao, Dacheng Tao*

{{< details "abstract" >}} abstract: With the rapid development of Artificial Intelligence Generated Content(AIGC), it has become common practice in many learning tasks to train orfine-tune large models on synthetic data due to the data-scarcity and privacyleakage problems. Albeit promising with unlimited data generation, owing tomassive and diverse information conveyed in real images, it is challenging fortext-to-image generative models to synthesize informative training data withhand-crafted prompts, which usually leads to inferior generalizationperformance when training downstream models. In this paper, we theoreticallyanalyze the relationship between the training effect of synthetic data and thesynthetic data distribution induced by prompts. Then we correspondingly proposea simple yet effective method that prompts text-to-image generative models tosynthesize more informative and diverse training data. Specifically, we captioneach real image with the advanced captioning model to obtain informative andfaithful prompts that extract class-relevant information and clarify thepolysemy of class names. The image captions and class names are concatenated toprompt generative models for training image synthesis. Extensive experiments onImageNette, ImageNet-100, and ImageNet-1K verify that our method significantlyimproves the performance of models trained on synthetic training data, i.e.,10% classification accuracy improvements on average.
{{< /details >}}

>**_2023-07-11_**

[**GPT4Graph: Can Large Language Models Understand Graph Structured Data ? An Empirical Evaluation and Benchmarking**](http://arxiv.org/abs/2305.15066v2)

*Jiayan Guo, Lun Du, Hengyu Liu, Mengyu Zhou, Xinyi He, Shi Han*

{{< details "abstract" >}} abstract: Large language models~(LLM) like ChatGPT have become indispensable toartificial general intelligence~(AGI), demonstrating excellent performance invarious natural language processing tasks. In the real world, graph data isubiquitous and an essential part of AGI and prevails in domains like socialnetwork analysis, bioinformatics and recommender systems. The training corpusof large language models often includes some algorithmic components, whichallows them to achieve certain effects on some graph data-related problems.However, there is still little research on their performance on a broader rangeof graph-structured data. In this study, we conduct an extensive investigationto assess the proficiency of LLMs in comprehending graph data, employing adiverse range of structural and semantic-related tasks. Our analysisencompasses 10 distinct tasks that evaluate the LLMs' capabilities in graphunderstanding. Through our study, we not only uncover the current limitationsof language models in comprehending graph structures and performing associatedreasoning tasks but also emphasize the necessity for further advancements andnovel approaches to enhance their graph processing capabilities. Our findingscontribute valuable insights towards bridging the gap between language modelsand graph understanding, paving the way for more effective graph mining andknowledge extraction.
{{< /details >}}

>**_2023-07-10_**

[**Approach to the cellular automaton interpretation with deep learning**](http://arxiv.org/abs/2012.06441v6)

*Hyunju Go*

{{< details "abstract" >}} abstract: In this paper, we will consider the deep learning systems that can learnfundamental physics theory based on cellular automaton interpretation (CAI).First, assuming that we can map quantum states to cellular automaton (CA) andcalculate the time-evolved CA for any initial CA by knowing the time-evolutionlaw of the given system, we will show that there exists a convolutional neuralnetwork (CNN) architecture that can learn the time-evolution law of this systemwith only the calculated data set for a time-reversible CA. Mathematically,finding a CNN architecture that can learn CA rule is equivalent to showing thata time-evolution operator can be approximated as a finite composition oftime-independent linear functions and ReLU type non-linear functions, as thepossible associated generator of approximation may absorbs the informationabout the dynamics. Going one step further, we will discuss the correspondencebetween the quantum system and deep learning architecture and relate theconcept of moduli space of Riemann surfaces to deep learning parameters whenconsidering interactions. Finally, for the CA model in which the dimensionalreduction in quantum gravity was first presented, we will discuss the CNNarchitecture that can find the non-trivial evolution law for holographicdirection in a deductive way without the label. It is suggested that the limitsto this effort can be improved through AdS/CFT correspondance.
{{< /details >}}

[**DBFed: Debiasing Federated Learning Framework based on Domain-Independent**](http://arxiv.org/abs/2307.05582v1)

*Jiale Li, Zhixin Li, Yibo Wang, Yao Li, Lei Wang*

{{< details "abstract" >}} abstract: As digital transformation continues, enterprises are generating, managing,and storing vast amounts of data, while artificial intelligence technology israpidly advancing. However, it brings challenges in information security anddata security. Data security refers to the protection of digital informationfrom unauthorized access, damage, theft, etc. throughout its entire life cycle.With the promulgation and implementation of data security laws and the emphasison data security and data privacy by organizations and users,Privacy-preserving technology represented by federated learning has a widerange of application scenarios. Federated learning is a distributed machinelearning computing framework that allows multiple subjects to train jointmodels without sharing data to protect data privacy and solve the problem ofdata islands. However, the data among multiple subjects are independent of eachother, and the data differences in quality may cause fairness issues infederated learning modeling, such as data bias among multiple subjects,resulting in biased and discriminatory models. Therefore, we propose DBFed, adebiasing federated learning framework based on domain-independent, whichmitigates model bias by explicitly encoding sensitive attributes duringclient-side training. This paper conducts experiments on three real datasetsand uses five evaluation metrics of accuracy and fairness to quantify theeffect of the model. Most metrics of DBFed exceed those of the other threecomparative methods, fully demonstrating the debiasing effect of DBFed.
{{< /details >}}

[**Ethicist: Targeted Training Data Extraction Through Loss Smoothed Soft Prompting and Calibrated Confidence Estimation**](http://arxiv.org/abs/2307.04401v1)

*Zhexin Zhang, Jiaxin Wen, Minlie Huang*

{{< details "abstract" >}} abstract: Large pre-trained language models achieve impressive results across manytasks. However, recent works point out that pre-trained language models maymemorize a considerable fraction of their training data, leading to the privacyrisk of information leakage. In this paper, we propose a method named Ethicistfor targeted training data extraction through loss smoothed soft prompting andcalibrated confidence estimation, investigating how to recover the suffix inthe training data when given a prefix. To elicit memorization in the attackedmodel, we tune soft prompt embeddings while keeping the model fixed. We furtherpropose a smoothing loss that smooths the loss distribution of the suffixtokens to make it easier to sample the correct suffix. In order to select themost probable suffix from a collection of sampled suffixes and estimate theprediction confidence, we propose a calibrated confidence estimation method,which normalizes the confidence of the generated suffixes with a localestimation. We show that Ethicist significantly improves the extractionperformance on a recently proposed public benchmark. We also investigateseveral factors influencing the data extraction performance, including decodingstrategy, model scale, prefix length, and suffix length. Our code is availableat https://github.com/thu-coai/Targeted-Data-Extraction.
{{< /details >}}

>**_2023-07-08_**

[**A Physics-Informed Low-Shot Learning For sEMG-Based Estimation of Muscle Force and Joint Kinematics**](http://arxiv.org/abs/2307.05361v1)

*Yue Shi, Shuhao Ma, Yihui Zhao, Zhiqiang Zhang*

{{< details "abstract" >}} abstract: Muscle force and joint kinematics estimation from surface electromyography(sEMG) are essential for real-time biomechanical analysis of the dynamicinterplay among neural muscle stimulation, muscle dynamics, and kinetics.Recent advances in deep neural networks (DNNs) have shown the potential toimprove biomechanical analysis in a fully automated and reproducible manner.However, the small sample nature and physical interpretability of biomechanicalanalysis limit the applications of DNNs. This paper presents a novelphysics-informed low-shot learning method for sEMG-based estimation of muscleforce and joint kinematics. This method seamlessly integrates Lagrange'sequation of motion and inverse dynamic muscle model into the generativeadversarial network (GAN) framework for structured feature decoding andextrapolated estimation from the small sample data. Specifically, Lagrange'sequation of motion is introduced into the generative model to restrain thestructured decoding of the high-level features following the laws of physics.And a physics-informed policy gradient is designed to improve the adversariallearning efficiency by rewarding the consistent physical representation of theextrapolated estimations and the physical references. Experimental validationsare conducted on two scenarios (i.e. the walking trials and wrist motiontrials). Results indicate that the estimations of the muscle forces and jointkinematics are unbiased compared to the physics-based inverse dynamics, whichoutperforms the selected benchmark methods, including physics-informedconvolution neural network (PI-CNN), vallina generative adversarial network(GAN), and multi-layer extreme learning machine (ML-ELM).
{{< /details >}}

[**Towards The Ultimate Brain: Exploring Scientific Discovery with ChatGPT AI**](http://arxiv.org/abs/2308.12400v1)

*Gerardo Adesso*

{{< details "abstract" >}} abstract: This paper presents a novel approach to scientific discovery using anartificial intelligence (AI) environment known as ChatGPT, developed by OpenAI.This is the first paper entirely generated with outputs from ChatGPT. Wedemonstrate how ChatGPT can be instructed through a gamification environment todefine and benchmark hypothetical physical theories. Through this environment,ChatGPT successfully simulates the creation of a new improved model, calledGPT$^4$, which combines the concepts of GPT in AI (generative pretrainedtransformer) and GPT in physics (generalized probabilistic theory). We showthat GPT$^4$ can use its built-in mathematical and statistical capabilities tosimulate and analyze physical laws and phenomena. As a demonstration of itslanguage capabilities, GPT$^4$ also generates a limerick about itself. Overall,our results demonstrate the promising potential for human-AI collaboration inscientific discovery, as well as the importance of designing systems thateffectively integrate AI's capabilities with human intelligence.
{{< /details >}}

[**Measuring the Success of Diffusion Models at Imitating Human Artists**](http://arxiv.org/abs/2307.04028v1)

*Stephen Casper, Zifan Guo, Shreya Mogulothu, Zachary Marinov, Chinmay Deshpande, Rui-Jie Yew, Zheng Dai, Dylan Hadfield-Menell*

{{< details "abstract" >}} abstract: Modern diffusion models have set the state-of-the-art in AI image generation.Their success is due, in part, to training on Internet-scale data which oftenincludes copyrighted work. This prompts questions about the extent to whichthese models learn from, imitate, or copy the work of human artists. This worksuggests that tying copyright liability to the capabilities of the model may beuseful given the evolving ecosystem of generative models. Specifically, much ofthe legal analysis of copyright and generative systems focuses on the use ofprotected data for training. As a result, the connections between data,training, and the system are often obscured. In our approach, we considersimple image classification techniques to measure a model's ability to imitatespecific artists. Specifically, we use Contrastive Language-Image Pretrained(CLIP) encoders to classify images in a zero-shot fashion. Our process firstprompts a model to imitate a specific artist. Then, we test whether CLIP can beused to reclassify the artist (or the artist's work) from the imitation. Ifthese tests match the imitation back to the original artist, this suggests themodel can imitate that artist's expression. Our approach is simple andquantitative. Furthermore, it uses standard techniques and does not requireadditional training. We demonstrate our approach with an audit of StableDiffusion's capacity to imitate 70 professional digital artists withcopyrighted work online. When Stable Diffusion is prompted to imitate an artistfrom this set, we find that the artist can be identified from the imitationwith an average accuracy of 81.0%. Finally, we also show that a sample of theartist's work can be matched to these imitation images with a high degree ofstatistical reliability. Overall, these results suggest that Stable Diffusionis broadly successful at imitating individual human artists.
{{< /details >}}

>**_2023-07-01_**

[**Metric Learning-Based Timing Synchronization by Using Lightweight Neural Network**](http://arxiv.org/abs/2307.00217v1)

*Chaojin Qing, Na Yang, Shuhai Tang, Chuangui Rao, Jiafan Wang, Hui Lin*

{{< details "abstract" >}} abstract: Timing synchronization (TS) is one of the key tasks in orthogonal frequencydivision multiplexing (OFDM) systems. However, multi-path uncertainty corruptsthe TS correctness, making OFDM systems suffer from a severeinter-symbol-interference (ISI). To tackle this issue, we propose atiming-metric learning-based TS method assisted by a lightweightone-dimensional convolutional neural network (1-D CNN). Specifically, thereceptive field of 1-D CNN is specifically designed to extract the metricfeatures from the classic synchronizer. Then, to combat the multi-pathuncertainty, we employ the varying delays and gains of multi-path (thecharacteristics of multi-path uncertainty) to design the timing-metricobjective, and thus form the training labels. This is typically different fromthe existing timing-metric objectives with respect to the timingsynchronization point. Our method substantively increases the completeness oftraining data against the multi-path uncertainty due to the completepreservation of metric information. By this mean, the TS correctness isimproved against the multi-path uncertainty. Numerical results demonstrate theeffectiveness and generalization of the proposed TS method against themulti-path uncertainty.
{{< /details >}}

>**_2023-06-30_**

[**Leveraging Ensembles and Self-Supervised Learning for Fully-Unsupervised Person Re-Identification and Text Authorship Attribution**](http://arxiv.org/abs/2202.03126v4)

*Gabriel Bertocco, Antônio Theophilo, Fernanda Andaló, Anderson Rocha*

{{< details "abstract" >}} abstract: Learning from fully-unlabeled data is challenging in Multimedia Forensicsproblems, such as Person Re-Identification and Text Authorship Attribution.Recent self-supervised learning methods have shown to be effective when dealingwith fully-unlabeled data in cases where the underlying classes havesignificant semantic differences, as intra-class distances are substantiallylower than inter-class distances. However, this is not the case for forensicapplications in which classes have similar semantics and the training and testsets have disjoint identities. General self-supervised learning methods mightfail to learn discriminative features in this scenario, thus requiring morerobust strategies. We propose a strategy to tackle Person Re-Identification andText Authorship Attribution by enabling learning from unlabeled data even whensamples from different classes are not prominently diverse. We propose a novelensemble-based clustering strategy whereby clusters derived from differentconfigurations are combined to generate a better grouping for the data samplesin a fully-unsupervised way. This strategy allows clusters with differentdensities and higher variability to emerge, reducing intra-class discrepancieswithout requiring the burden of finding an optimal configuration per dataset.We also consider different Convolutional Neural Networks for feature extractionand subsequent distance computations between samples. We refine these distancesby incorporating context and grouping them to capture complementaryinformation. Our method is robust across both tasks, with different datamodalities, and outperforms state-of-the-art methods with a fully-unsupervisedsolution without any labeling or human intervention.
{{< /details >}}

>**_2023-06-28_**

[**A deep learning approach to the measurement of long-lived memory kernels from Generalised Langevin Dynamics**](http://arxiv.org/abs/2302.13682v2)

*Max Kerr Winter, Ilian Pihlajamaa, Vincent E. Debets, Liesbeth M. C. Janssen*

{{< details "abstract" >}} abstract: Memory effects are ubiquitous in a wide variety of complex physicalphenomena, ranging from glassy dynamics and metamaterials to climate models.The Generalised Langevin Equation (GLE) provides a rigorous way to describememory effects via the so-called memory kernel in an integro-differentialequation. However, the memory kernel is often unknown, and accuratelypredicting or measuring it via e.g. a numerical inverse Laplace transformremains a herculean task. Here we describe a novel method using deep neuralnetworks (DNNs) to measure memory kernels from dynamical data. Asproof-of-principle, we focus on the notoriously long-lived memory effects ofglassy systems, which have proved a major challenge to existing methods.Specifically, we learn a training set generated with the Mode-Coupling Theory(MCT) of hard spheres. Our DNNs are remarkably robust against noise, incontrast to conventional techniques which require ensemble averaging over manyindependent trajectories. Finally, we demonstrate that a network trained ondata generated from analytic theory (hard-sphere MCT) generalises well to datafrom simulations of a different system (Brownian Weeks-Chandler-Andersenparticles). We provide a general pipeline, KernelLearner, for training networksto extract memory kernels from any non-Markovian system described by a GLE. Thesuccess of our DNN method applied to glassy systems suggests deep learning canplay an important role in the study of dynamical systems that exhibit memoryeffects.
{{< /details >}}

>**_2023-06-24_**

[**MeWEHV: Mel and Wave Embeddings for Human Voice Tasks**](http://arxiv.org/abs/2209.14078v2)

*Andrés Carofilis, Laura Fernández-Robles, Enrique Alegre, Eduardo Fidalgo*

{{< details "abstract" >}} abstract: A recent trend in speech processing is the use of embeddings created throughmachine learning models trained on a specific task with large datasets. Byleveraging the knowledge already acquired, these models can be reused in newtasks where the amount of available data is small. This paper proposes apipeline to create a new model, called Mel and Wave Embeddings for Human VoiceTasks (MeWEHV), capable of generating robust embeddings for speech processing.MeWEHV combines the embeddings generated by a pre-trained raw audio waveformencoder model, and deep features extracted from Mel Frequency CepstralCoefficients (MFCCs) using Convolutional Neural Networks (CNNs). We evaluatethe performance of MeWEHV on three tasks: speaker, language, and accentidentification. For the first one, we use the VoxCeleb1 dataset and presentYouSpeakers204, a new and publicly available dataset for English speakeridentification that contains 19607 audio clips from 204 persons speaking in sixdifferent accents, allowing other researchers to work with a very balanceddataset, and to create new models that are robust to multiple accents. Forevaluating the language identification task, we use the VoxForge and CommonLanguage datasets. Finally, for accent identification, we use the LatinAmerican Spanish Corpora (LASC) and Common Voice datasets. Our approach allowsa significant increase in the performance of state-of-the-art models on all thetested datasets, with a low additional computational cost.
{{< /details >}}

>**_2023-06-23_**

[**Deconstructing Classifiers: Towards A Data Reconstruction Attack Against Text Classification Models**](http://arxiv.org/abs/2306.13789v1)

*Adel Elmahdy, Ahmed Salem*

{{< details "abstract" >}} abstract: Natural language processing (NLP) models have become increasingly popular inreal-world applications, such as text classification. However, they arevulnerable to privacy attacks, including data reconstruction attacks that aimto extract the data used to train the model. Most previous studies on datareconstruction attacks have focused on LLM, while classification models wereassumed to be more secure. In this work, we propose a new targeted datareconstruction attack called the Mix And Match attack, which takes advantage ofthe fact that most classification models are based on LLM. The Mix And Matchattack uses the base model of the target model to generate candidate tokens andthen prunes them using the classification head. We extensively demonstrate theeffectiveness of the attack using both random and organic canaries. This workhighlights the importance of considering the privacy risks associated with datareconstruction attacks in classification models and offers insights intopossible leakages.
{{< /details >}}

>**_2023-06-21_**

[**SNAP: Efficient Extraction of Private Properties with Poisoning**](http://arxiv.org/abs/2208.12348v2)

*Harsh Chaudhari, John Abascal, Alina Oprea, Matthew Jagielski, Florian Tramèr, Jonathan Ullman*

{{< details "abstract" >}} abstract: Property inference attacks allow an adversary to extract global properties ofthe training dataset from a machine learning model. Such attacks have privacyimplications for data owners sharing their datasets to train machine learningmodels. Several existing approaches for property inference attacks against deepneural networks have been proposed, but they all rely on the attacker traininga large number of shadow models, which induces a large computational overhead.  In this paper, we consider the setting of property inference attacks in whichthe attacker can poison a subset of the training dataset and query the trainedtarget model. Motivated by our theoretical analysis of model confidences underpoisoning, we design an efficient property inference attack, SNAP, whichobtains higher attack success and requires lower amounts of poisoning than thestate-of-the-art poisoning-based property inference attack by Mahloujifar etal. For example, on the Census dataset, SNAP achieves 34% higher success ratethan Mahloujifar et al. while being 56.5x faster. We also extend our attack toinfer whether a certain property was present at all during training andestimate the exact proportion of a property of interest efficiently. Weevaluate our attack on several properties of varying proportions from fourdatasets and demonstrate SNAP's generality and effectiveness. An open-sourceimplementation of SNAP can be found at https://github.com/johnmath/snap-sp23.
{{< /details >}}

>**_2023-06-20_**

[**Deep neural network techniques for monaural speech enhancement: state of the art analysis**](http://arxiv.org/abs/2212.00369v2)

*Peter Ochieng*

{{< details "abstract" >}} abstract: Deep neural networks (DNN) techniques have become pervasive in domains suchas natural language processing and computer vision. They have achieved greatsuccess in these domains in task such as machine translation and imagegeneration. Due to their success, these data driven techniques have beenapplied in audio domain. More specifically, DNN models have been applied inspeech enhancement domain to achieve denosing, dereverberation andmulti-speaker separation in monaural speech enhancement. In this paper, wereview some dominant DNN techniques being employed to achieve speechseparation. The review looks at the whole pipeline of speech enhancement fromfeature extraction, how DNN based tools are modelling both global and localfeatures of speech and model training (supervised and unsupervised). We alsoreview the use of speech-enhancement pre-trained models to boost speechenhancement process. The review is geared towards covering the dominant trendswith regards to DNN application in speech enhancement in speech obtained via asingle speaker.
{{< /details >}}

>**_2023-06-18_**

[**Should ChatGPT and Bard Share Revenue with Their Data Providers? A New Business Model for the AI Era**](http://arxiv.org/abs/2305.02555v2)

*Dong Zhang*

{{< details "abstract" >}} abstract: With various AI tools such as ChatGPT becoming increasingly popular, we areentering a true AI era. We can foresee that exceptional AI tools will soon reapconsiderable profits. A crucial question arise: should AI tools share revenuewith their training data providers in additional to traditional stakeholdersand shareholders? The answer is Yes. Large AI tools, such as large languagemodels, always require more and better quality data to continuously improve,but current copyright laws limit their access to various types of data. Sharingrevenue between AI tools and their data providers could transform the currenthostile zero-sum game relationship between AI tools and a majority ofcopyrighted data owners into a collaborative and mutually beneficial one, whichis necessary to facilitate the development of a virtuous cycle among AI tools,their users and data providers that drives forward AI technology and builds ahealthy AI ecosystem. However, current revenue-sharing business models do notwork for AI tools in the forthcoming AI era, since the most widely used metricsfor website-based traffic and action, such as clicks, will be replaced by newmetrics such as prompts and cost per prompt for generative AI tools. Acompletely new revenue-sharing business model, which must be almost independentof AI tools and be easily explained to data providers, needs to establish aprompt-based scoring system to measure data engagement of each data provider.This paper systematically discusses how to build such a scoring system for alldata providers for AI tools based on classification and content similaritymodels, and outlines the requirements for AI tools or third parties to buildit. Sharing revenue with data providers using such a scoring system wouldencourage more data owners to participate in the revenue-sharing program. Thiswill be a utilitarian AI era where all parties benefit.
{{< /details >}}

>**_2023-06-11_**

[**DeepfakeArt Challenge: A Benchmark Dataset for Generative AI Art Forgery and Data Poisoning Detection**](http://arxiv.org/abs/2306.01272v2)

*Hossein Aboutalebi, Dayou Mao, Carol Xu, Alexander Wong*

{{< details "abstract" >}} abstract: The tremendous recent advances in generative artificial intelligencetechniques have led to significant successes and promise in a wide range ofdifferent applications ranging from conversational agents and textual contentgeneration to voice and visual synthesis. Amid the rise in generative AI andits increasing widespread adoption, there has been significant growing concernover the use of generative AI for malicious purposes. In the realm of visualcontent synthesis using generative AI, key areas of significant concern hasbeen image forgery (e.g., generation of images containing or derived fromcopyright content), and data poisoning (i.e., generation of adversariallycontaminated images). Motivated to address these key concerns to encourageresponsible generative AI, we introduce the DeepfakeArt Challenge, alarge-scale challenge benchmark dataset designed specifically to aid in thebuilding of machine learning algorithms for generative AI art forgery and datapoisoning detection. Comprising of over 32,000 records across a variety ofgenerative forgery and data poisoning techniques, each entry consists of a pairof images that are either forgeries / adversarially contaminated or not. Eachof the generated images in the DeepfakeArt Challenge benchmark dataset has beenquality checked in a comprehensive manner. The DeepfakeArt Challenge is a corepart of GenAI4Good, a global open source initiative for accelerating machinelearning for promoting responsible creation and deployment of generative AI forgood.
{{< /details >}}

>**_2023-06-10_**

[**MARS: Meta-Learning as Score Matching in the Function Space**](http://arxiv.org/abs/2210.13319v3)

*Krunoslav Lehman Pavasovic, Jonas Rothfuss, Andreas Krause*

{{< details "abstract" >}} abstract: Meta-learning aims to extract useful inductive biases from a set of relateddatasets. In Bayesian meta-learning, this is typically achieved by constructinga prior distribution over neural network parameters. However, specifyingfamilies of computationally viable prior distributions over thehigh-dimensional neural network parameters is difficult. As a result, existingapproaches resort to meta-learning restrictive diagonal Gaussian priors,severely limiting their expressiveness and performance. To circumvent theseissues, we approach meta-learning through the lens of functional Bayesianneural network inference, which views the prior as a stochastic process andperforms inference in the function space. Specifically, we view themeta-training tasks as samples from the data-generating process and formalizemeta-learning as empirically estimating the law of this stochastic process. Ourapproach can seamlessly acquire and represent complex prior knowledge bymeta-learning the score function of the data-generating process marginalsinstead of parameter space priors. In a comprehensive benchmark, we demonstratethat our method achieves state-of-the-art performance in terms of predictiveaccuracy and substantial improvements in the quality of uncertainty estimates.
{{< /details >}}

>**_2023-06-02_**

[**Are You Copying My Model? Protecting the Copyright of Large Language Models for EaaS via Backdoor Watermark**](http://arxiv.org/abs/2305.10036v3)

*Wenjun Peng, Jingwei Yi, Fangzhao Wu, Shangxi Wu, Bin Zhu, Lingjuan Lyu, Binxing Jiao, Tong Xu, Guangzhong Sun, Xing Xie*

{{< details "abstract" >}} abstract: Large language models (LLMs) have demonstrated powerful capabilities in bothtext understanding and generation. Companies have begun to offer Embedding as aService (EaaS) based on these LLMs, which can benefit various natural languageprocessing (NLP) tasks for customers. However, previous studies have shown thatEaaS is vulnerable to model extraction attacks, which can cause significantlosses for the owners of LLMs, as training these models is extremely expensive.To protect the copyright of LLMs for EaaS, we propose an Embedding Watermarkmethod called EmbMarker that implants backdoors on embeddings. Our methodselects a group of moderate-frequency words from a general text corpus to forma trigger set, then selects a target embedding as the watermark, and inserts itinto the embeddings of texts containing trigger words as the backdoor. Theweight of insertion is proportional to the number of trigger words included inthe text. This allows the watermark backdoor to be effectively transferred toEaaS-stealer's model for copyright verification while minimizing the adverseimpact on the original embeddings' utility. Our extensive experiments onvarious datasets show that our method can effectively protect the copyright ofEaaS models without compromising service quality.
{{< /details >}}

>**_2023-06-01_**

[**Bag of Tricks for Training Data Extraction from Language Models**](http://arxiv.org/abs/2302.04460v2)

*Weichen Yu, Tianyu Pang, Qian Liu, Chao Du, Bingyi Kang, Yan Huang, Min Lin, Shuicheng Yan*

{{< details "abstract" >}} abstract: With the advance of language models, privacy protection is receiving moreattention. Training data extraction is therefore of great importance, as it canserve as a potential tool to assess privacy leakage. However, due to thedifficulty of this task, most of the existing methods are proof-of-concept andstill not effective enough. In this paper, we investigate and benchmark tricksfor improving training data extraction using a publicly available dataset.Because most existing extraction methods use a pipeline ofgenerating-then-ranking, i.e., generating text candidates as potential trainingdata and then ranking them based on specific criteria, our research focuses onthe tricks for both text generation (e.g., sampling strategy) and text ranking(e.g., token-level criteria). The experimental results show that severalpreviously overlooked tricks can be crucial to the success of training dataextraction. Based on the GPT-Neo 1.3B evaluation results, our proposed tricksoutperform the baseline by a large margin in most cases, providing a muchstronger baseline for future research. The code is available athttps://github.com/weichen-yu/LM-Extraction.
{{< /details >}}

[**Challenges and Remedies to Privacy and Security in AIGC: Exploring the Potential of Privacy Computing, Blockchain, and Beyond**](http://arxiv.org/abs/2306.00419v1)

*Chuan Chen, Zhenpeng Wu, Yanyi Lai, Wenlin Ou, Tianchi Liao, Zibin Zheng*

{{< details "abstract" >}} abstract: Artificial Intelligence Generated Content (AIGC) is one of the latestachievements in AI development. The content generated by related applications,such as text, images and audio, has sparked a heated discussion. Variousderived AIGC applications are also gradually entering all walks of life,bringing unimaginable impact to people's daily lives. However, the rapiddevelopment of such generative tools has also raised concerns about privacy andsecurity issues, and even copyright issues in AIGC. We note that advancedtechnologies such as blockchain and privacy computing can be combined with AIGCtools, but no work has yet been done to investigate their relevance andprospect in a systematic and detailed way. Therefore it is necessary toinvestigate how they can be used to protect the privacy and security of data inAIGC by fully exploring the aforementioned technologies. In this paper, wefirst systematically review the concept, classification and underlyingtechnologies of AIGC. Then, we discuss the privacy and security challengesfaced by AIGC from multiple perspectives and purposefully list thecountermeasures that currently exist. We hope our survey will help researchersand industry to build a more secure and robust AIGC system.
{{< /details >}}

>**_2023-05-31_**

[**Synthetic Pre-Training Tasks for Neural Machine Translation**](http://arxiv.org/abs/2212.09864v2)

*Zexue He, Graeme Blackwood, Rameswar Panda, Julian McAuley, Rogerio Feris*

{{< details "abstract" >}} abstract: Pre-training models with large crawled corpora can lead to issues such astoxicity and bias, as well as copyright and privacy concerns. A promising wayof alleviating such concerns is to conduct pre-training with synthetic tasksand data, since no real-world information is ingested by the model. Our goal inthis paper is to understand the factors that contribute to the effectiveness ofpre-training models when using synthetic resources, particularly in the contextof neural machine translation. We propose several novel approaches topre-training translation models that involve different levels of lexical andstructural knowledge, including: 1) generating obfuscated data from a largeparallel corpus 2) concatenating phrase pairs extracted from a smallword-aligned corpus, and 3) generating synthetic parallel data without realhuman language corpora. Our experiments on multiple language pairs reveal thatpre-training benefits can be realized even with high levels of obfuscation orpurely synthetic parallel data. We hope the findings from our comprehensiveempirical analysis will shed light on understanding what matters for NMTpre-training, as well as pave the way for the development of more efficient andless toxic models.
{{< /details >}}

>**_2023-05-29_**

[**Fingerprinting Generative Adversarial Networks**](http://arxiv.org/abs/2106.11760v3)

*Guanlin Li, Guowen Xu, Han Qiu, Shangwei Guo, Run Wang, Jiwei Li, Tianwei Zhang, Rongxing Lu*

{{< details "abstract" >}} abstract: Generative Adversarial Networks (GANs) have been widely used in variousapplication scenarios. Since the production of a commercial GAN requiressubstantial computational and human resources, the copyright protection of GANsis urgently needed. In this paper, we present the first fingerprinting schemefor the Intellectual Property (IP) protection of GANs. We break through thestealthiness and robustness bottlenecks suffered by previous fingerprintingmethods for classification models being naively transferred to GANs.Specifically, we innovatively construct a composite deep learning model fromthe target GAN and a classifier. Then we generate fingerprint samples from thiscomposite model, and embed them in the classifier for effective ownershipverification. This scheme inspires some concrete methodologies to practicallyprotect the modern GAN models. Theoretical analysis proves that these methodscan satisfy different security requirements necessary for IP protection. Wealso conduct extensive experiments to show that our solutions outperformexisting strategies.
{{< /details >}}

[**NaturalFinger: Generating Natural Fingerprint with Generative Adversarial Networks**](http://arxiv.org/abs/2305.17868v1)

*Kang Yang, Kunhao Lai*

{{< details "abstract" >}} abstract: Deep neural network (DNN) models have become a critical asset of the modelowner as training them requires a large amount of resource (i.e. labeled data).Therefore, many fingerprinting schemes have been proposed to safeguard theintellectual property (IP) of the model owner against model extraction andillegal redistribution. However, previous schemes adopt unnatural images as thefingerprint, such as adversarial examples and noisy images, which can be easilyperceived and rejected by the adversary. In this paper, we proposeNaturalFinger which generates natural fingerprint with generative adversarialnetworks (GANs). Besides, our proposed NaturalFinger fingerprints the decisiondifference areas rather than the decision boundary, which is more robust. Theapplication of GAN not only allows us to generate more imperceptible samples,but also enables us to generate unrestricted samples to explore the decisionboundary.To demonstrate the effectiveness of our fingerprint approach, weevaluate our approach against four model modification attacks includingadversarial training and two model extraction attacks. Experiments show thatour approach achieves 0.91 ARUC value on the FingerBench dataset (154 models),exceeding the optimal baseline (MetaV) over 17\%.
{{< /details >}}

>**_2023-05-22_**

[**Mist: Towards Improved Adversarial Examples for Diffusion Models**](http://arxiv.org/abs/2305.12683v1)

*Chumeng Liang, Xiaoyu Wu*

{{< details "abstract" >}} abstract: Diffusion Models (DMs) have empowered great success inartificial-intelligence-generated content, especially in artwork creation, yetraising new concerns in intellectual properties and copyright. For example,infringers can make profits by imitating non-authorized human-created paintingswith DMs. Recent researches suggest that various adversarial examples fordiffusion models can be effective tools against these copyright infringements.However, current adversarial examples show weakness in transferability overdifferent painting-imitating methods and robustness under straightforwardadversarial defense, for example, noise purification. We surprisingly find thatthe transferability of adversarial examples can be significantly enhanced byexploiting a fused and modified adversarial loss term under consistentparameters. In this work, we comprehensively evaluate the cross-methodtransferability of adversarial examples. The experimental observation showsthat our method generates more transferable adversarial examples with evenstronger robustness against the simple adversarial defense.
{{< /details >}}

>**_2023-05-21_**

[**Generative Model Watermarking Suppressing High-Frequency Artifacts**](http://arxiv.org/abs/2305.12391v1)

*Li Zhang, Yong Liu, Xinpeng Zhang, Hanzhou Wu*

{{< details "abstract" >}} abstract: Protecting deep neural networks (DNNs) against intellectual property (IP)infringement has attracted an increasing attention in recent years. Recentadvances focus on IP protection of generative models, which embed the watermarkinformation into the image generated by the model to be protected. Although thegenerated marked image has good visual quality, it introduces noticeableartifacts to the marked image in high-frequency area, which severely impairsthe imperceptibility of the watermark and thereby reduces the security of thewatermarking system. To deal with this problem, in this paper, we propose anovel framework for generative model watermarking that can suppress thosehigh-frequency artifacts. The main idea of the proposed framework is to designa new watermark embedding network that can suppress high-frequency artifacts byapplying anti-aliasing. To realize anti-aliasing, we use low-pass filtering forthe internal sampling layers of the new watermark embedding network. Meanwhile,joint loss optimization and adversarial training are applied to enhance theeffectiveness and robustness. Experimental results indicate that the markedmodel not only maintains the performance very well on the original task, butalso demonstrates better imperceptibility and robustness on the watermarkingtask. This work reveals the importance of suppressing high-frequency artifactsfor enhancing imperceptibility and security of generative model watermarking.
{{< /details >}}

>**_2023-05-16_**

[**Boosting Event Extraction with Denoised Structure-to-Text Augmentation**](http://arxiv.org/abs/2305.09598v1)

*bo wang, Heyan Huang, Xiaochi Wei, Ge Shi, Xiao Liu, Chong Feng, Tong Zhou, Shuaiqiang Wang, Dawei Yin*

{{< details "abstract" >}} abstract: Event extraction aims to recognize pre-defined event triggers and argumentsfrom texts, which suffer from the lack of high-quality annotations. In most NLPapplications, involving a large scale of synthetic training data is a practicaland effective approach to alleviate the problem of data scarcity. However, whenapplying to the task of event extraction, recent data augmentation methodsoften neglect the problem of grammatical incorrectness, structure misalignment,and semantic drifting, leading to unsatisfactory performances. In order tosolve these problems, we propose a denoised structure-to-text augmentationframework for event extraction DAEE, which generates additional training datathrough the knowledge-based structure-to-text generation model and selects theeffective subset from the generated data iteratively with a deep reinforcementlearning agent. Experimental results on several datasets demonstrate that theproposed method generates more diverse text representations for eventextraction and achieves comparable results with the state-of-the-art.
{{< /details >}}

>**_2023-05-11_**

[**ReMark: Receptive Field based Spatial WaterMark Embedding Optimization using Deep Network**](http://arxiv.org/abs/2305.06786v1)

*Natan Semyonov, Rami Puzis, Asaf Shabtai, Gilad Katz*

{{< details "abstract" >}} abstract: Watermarking is one of the most important copyright protection tools fordigital media. The most challenging type of watermarking is the imperceptibleone, which embeds identifying information in the data while retaining thelatter's original quality. To fulfill its purpose, watermarks need to withstandvarious distortions whose goal is to damage their integrity. In this study, weinvestigate a novel deep learning-based architecture for embeddingimperceptible watermarks. The key insight guiding our architecture design isthe need to correlate the dimensions of our watermarks with the sizes ofreceptive fields (RF) of modules of our architecture. This adaptation makes ourwatermarks more robust, while also enabling us to generate them in a way thatbetter maintains image quality. Extensive evaluations on a wide variety ofdistortions show that the proposed method is robust against most commondistortions on watermarks including collusive distortion.
{{< /details >}}

>**_2023-05-07_**

[**AUTOLYCUS: Exploiting Explainable AI (XAI) for Model Extraction Attacks against White-Box Models**](http://arxiv.org/abs/2302.02162v2)

*Abdullah Caglar Oksuz, Anisa Halimi, Erman Ayday*

{{< details "abstract" >}} abstract: Explainable Artificial Intelligence (XAI) encompasses a range of techniquesand procedures aimed at elucidating the decision-making processes of AI models.While XAI is valuable in understanding the reasoning behind AI models, the dataused for such revelations poses potential security and privacy vulnerabilities.Existing literature has identified privacy risks targeting machine learningmodels, including membership inference, model inversion, and model extractionattacks. Depending on the settings and parties involved, such attacks maytarget either the model itself or the training data used to create the model.  We have identified that tools providing XAI can particularly increase thevulnerability of model extraction attacks, which can be a significant issuewhen the owner of an AI model prefers to provide only black-box access ratherthan sharing the model parameters and architecture with other parties. Toexplore this privacy risk, we propose AUTOLYCUS, a model extraction attack thatleverages the explanations provided by popular explainable AI tools. Weparticularly focus on white-box machine learning (ML) models such as decisiontrees and logistic regression models.  We have evaluated the performance of AUTOLYCUS on 5 machine learningdatasets, in terms of the surrogate model's accuracy and its similarity to thetarget model. We observe that the proposed attack is highly effective; itrequires up to 60x fewer queries to the target model compared to thestate-of-the-art attack, while providing comparable accuracy and similarity. Wefirst validate the performance of the proposed algorithm on decision trees, andthen show its performance on logistic regression models as an indicator thatthe proposed algorithm performs well on white-box ML models in general.Finally, we show that the existing countermeasures remain ineffective for theproposed attack.
{{< /details >}}

>**_2023-04-23_**

[**Robust and Imperceptible Black-box DNN Watermarking Based on Fourier Perturbation Analysis and Frequency Sensitivity Clustering**](http://arxiv.org/abs/2208.03944v2)

*Yong Liu, Hanzhou Wu, Xinpeng Zhang*

{{< details "abstract" >}} abstract: Recently, more and more attention has been focused on the intellectualproperty protection of deep neural networks (DNNs), promoting DNN watermarkingto become a hot research topic. Compared with embedding watermarks directlyinto DNN parameters, inserting trigger-set watermarks enables us to verify theownership without knowing the internal details of the DNN, which is moresuitable for application scenarios. The cost is we have to carefully craft thetrigger samples. Mainstream methods construct the trigger samples by insertinga noticeable pattern to the clean samples in the spatial domain, which does notconsider sample imperceptibility, sample robustness and model robustness, andtherefore has limited the watermarking performance and the modelgeneralization. It has motivated the authors in this paper to propose a novelDNN watermarking method based on Fourier perturbation analysis and frequencysensitivity clustering. First, we analyze the perturbation impact of differentfrequency components of the input sample on the task functionality of the DNNby applying random perturbation. Then, by K-means clustering, we determine thefrequency components that result in superior watermarking performance forcrafting the trigger samples. Our experiments show that the proposed work notonly maintains the performance of the DNN on its original task, but alsoprovides better watermarking performance compared with related works.
{{< /details >}}

>**_2023-04-17_**

[**Learning To Rank Resources with GNN**](http://arxiv.org/abs/2304.07946v1)

*Ulugbek Ergashev, Eduard C. Dragut, Weiyi Meng*

{{< details "abstract" >}} abstract: As the content on the Internet continues to grow, many new dynamicallychanging and heterogeneous sources of data constantly emerge. A conventionalsearch engine cannot crawl and index at the same pace as the expansion of theInternet. Moreover, a large portion of the data on the Internet is notaccessible to traditional search engines. Distributed Information Retrieval(DIR) is a viable solution to this as it integrates multiple shards (resources)and provides a unified access to them. Resource selection is a key component ofDIR systems. There is a rich body of literature on resource selectionapproaches for DIR. A key limitation of the existing approaches is that theyprimarily use term-based statistical features and do not generally modelresource-query and resource-resource relationships. In this paper, we propose agraph neural network (GNN) based approach to learning-to-rank that is capableof modeling resource-query and resource-resource relationships. Specifically,we utilize a pre-trained language model (PTLM) to obtain semantic informationfrom queries and resources. Then, we explicitly build a heterogeneous graph topreserve structural information of query-resource relationships and employ GNNto extract structural information. In addition, the heterogeneous graph isenriched with resource-resource type of edges to further enhance the rankingaccuracy. Extensive experiments on benchmark datasets show that our proposedapproach is highly effective in resource selection. Our method outperforms thestate-of-the-art by 6.4% to 42% on various performance metrics.
{{< /details >}}

[**CyFormer: Accurate State-of-Health Prediction of Lithium-Ion Batteries via Cyclic Attention**](http://arxiv.org/abs/2304.08502v1)

*Zhiqiang Nie, Jiankun Zhao, Qicheng Li, Yong Qin*

{{< details "abstract" >}} abstract: Predicting the State-of-Health (SoH) of lithium-ion batteries is afundamental task of battery management systems on electric vehicles. It aims atestimating future SoH based on historical aging data. Most existing deeplearning methods rely on filter-based feature extractors (e.g., CNN or Kalmanfilters) and recurrent time sequence models. Though efficient, they generallyignore cyclic features and the domain gap between training and testingbatteries. To address this problem, we present CyFormer, a transformer-basedcyclic time sequence model for SoH prediction. Instead of the conventionalCNN-RNN structure, we adopt an encoder-decoder architecture. In the encoder,row-wise and column-wise attention blocks effectively capture intra-cycle andinter-cycle connections and extract cyclic features. In the decoder, the SoHqueries cross-attend to these features to form the final predictions. Wefurther utilize a transfer learning strategy to narrow the domain gap betweenthe training and testing set. To be specific, we use fine-tuning to shift themodel to a target working condition. Finally, we made our model more efficientby pruning. The experiment shows that our method attains an MAE of 0.75\% withonly 10\% data for fine-tuning on a testing battery, surpassing prior methodsby a large margin. Effective and robust, our method provides a potentialsolution for all cyclic time sequence prediction tasks.
{{< /details >}}

>**_2023-04-15_**

[**Single-round Self-supervised Distributed Learning using Vision Transformer**](http://arxiv.org/abs/2301.02064v3)

*Sangjoon Park, Ik-Jae Lee, Jun Won Kim, Jong Chul Ye*

{{< details "abstract" >}} abstract: Despite the recent success of deep learning in the field of medicine, theissue of data scarcity is exacerbated by concerns about privacy and dataownership. Distributed learning approaches, including federated learning, havebeen investigated to address these issues. However, they are hindered by theneed for cumbersome communication overheads and weaknesses in privacyprotection. To tackle these challenges, we propose a self-supervised maskedsampling distillation method for the vision transformer. This method can beimplemented without continuous communication and can enhance privacy byutilizing a vision transformer-specific encryption technique. We conductedextensive experiments on two different tasks, which demonstrated theeffectiveness of our method. We achieved superior performance compared to theexisting distributed learning strategy as well as the fine-tuning onlybaseline. Furthermore, since the self-supervised model created using ourproposed method can achieve a general semantic understanding of the image, wedemonstrate its potential as a task-agnostic self-supervised foundation modelfor various downstream tasks, thereby expanding its applicability in themedical domain.
{{< /details >}}

>**_2023-03-28_**

[**Synthetically generated text for supervised text analysis**](http://arxiv.org/abs/2303.16028v1)

*Andrew Halterman*

{{< details "abstract" >}} abstract: Supervised text models are a valuable tool for political scientists butpresent several obstacles to their use, including the expense of hand-labelingdocuments, the difficulty of retrieving rare relevant documents for annotation,and copyright and privacy concerns involved in sharing annotated documents.This article proposes a partial solution to these three issues, in the form ofcontrolled generation of synthetic text with large language models. I provide aconceptual overview of text generation, guidance on when researchers shouldprefer different techniques for generating synthetic text, a discussion ofethics, and a simple technique for improving the quality of synthetic text. Idemonstrate the usefulness of synthetic text with three applications:generating synthetic tweets describing the fighting in Ukraine, synthetic newsarticles describing specified political events for training an event detectionsystem, and a multilingual corpus of populist manifesto statements for traininga sentence-level populism classifier.
{{< /details >}}

>**_2023-03-24_**

[**PoisonedGNN: Backdoor Attack on Graph Neural Networks-based Hardware Security Systems**](http://arxiv.org/abs/2303.14009v1)

*Lilas Alrahis, Satwik Patnaik, Muhammad Abdullah Hanif, Muhammad Shafique, Ozgur Sinanoglu*

{{< details "abstract" >}} abstract: Graph neural networks (GNNs) have shown great success in detectingintellectual property (IP) piracy and hardware Trojans (HTs). However, themachine learning community has demonstrated that GNNs are susceptible to datapoisoning attacks, which result in GNNs performing abnormally on graphs withpre-defined backdoor triggers (realized using crafted subgraphs). Thus, it isimperative to ensure that the adoption of GNNs should not introduce securityvulnerabilities in critical security frameworks.  Existing backdoor attacks on GNNs generate random subgraphs with specificsizes/densities to act as backdoor triggers. However, for Boolean circuits,backdoor triggers cannot be randomized since the added structures should notaffect the functionality of a design.  We explore this threat and develop PoisonedGNN as the first backdoor attackon GNNs in the context of hardware design. We design and inject backdoortriggers into the register-transfer- or the gate-level representation of agiven design without affecting the functionality to evade some GNN-baseddetection procedures. To demonstrate the effectiveness of PoisonedGNN, weconsider two case studies: (i) Hiding HTs and (ii) IP piracy. Our experimentson TrustHub datasets demonstrate that PoisonedGNN can hide HTs and IP piracyfrom advanced GNN-based detection platforms with an attack success rate of upto 100%.
{{< /details >}}

>**_2023-03-23_**

[**Edge Deep Learning Model Protection via Neuron Authorization**](http://arxiv.org/abs/2303.12397v2)

*Jinyin Chen, Haibin Zheng, Tao Liu, Rongchang Li, Yao Cheng, Xuhong Zhang, Shouling Ji*

{{< details "abstract" >}} abstract: With the development of deep learning processors and accelerators, deeplearning models have been widely deployed on edge devices as part of theInternet of Things. Edge device models are generally considered as valuableintellectual properties that are worth for careful protection. Unfortunately,these models have a great risk of being stolen or illegally copied. Theexisting model protections using encryption algorithms are suffered from highcomputation overhead which is not practical due to the limited computingcapacity on edge devices. In this work, we propose a light-weight, practical,and general Edge device model Pro tection method at neuron level, denoted asEdgePro. Specifically, we select several neurons as authorization neurons andset their activation values to locking values and scale the neuron outputs asthe "asswords" during training. EdgePro protects the model by ensuring it canonly work correctly when the "passwords" are met, at the cost of encrypting andstoring the information of the "passwords" instead of the whole model.Extensive experimental results indicate that EdgePro can work well on the taskof protecting on datasets with different modes. The inference time increase ofEdgePro is only 60% of state-of-the-art methods, and the accuracy loss is lessthan 1%. Additionally, EdgePro is robust against adaptive attacks includingfine-tuning and pruning, which makes it more practical in real-worldapplications. EdgePro is also open sourced to facilitate future research:https://github.com/Leon022/Edg
{{< /details >}}

>**_2023-03-21_**

[**Effective Ambiguity Attack Against Passport-based DNN Intellectual Property Protection Schemes through Fully Connected Layer Substitution**](http://arxiv.org/abs/2303.11595v1)

*Yiming Chen, Jinyu Tian, Xiangyu Chen, Jiantao Zhou*

{{< details "abstract" >}} abstract: Since training a deep neural network (DNN) is costly, the well-trained deepmodels can be regarded as valuable intellectual property (IP) assets. The IPprotection associated with deep models has been receiving increasing attentionsin recent years. Passport-based method, which replaces normalization layerswith passport layers, has been one of the few protection solutions that areclaimed to be secure against advanced attacks. In this work, we tackle theissue of evaluating the security of passport-based IP protection methods. Wepropose a novel and effective ambiguity attack against passport-based method,capable of successfully forging multiple valid passports with a small trainingdataset. This is accomplished by inserting a specially designed accessory blockahead of the passport parameters. Using less than 10% of training data, withthe forged passport, the model exhibits almost indistinguishable performancedifference (less than 2%) compared with that of the authorized passport. Inaddition, it is shown that our attack strategy can be readily generalized toattack other IP protection methods based on watermark embedding. Directions forpotential remedy solutions are also given.
{{< /details >}}

>**_2023-03-17_**

[**Rethinking White-Box Watermarks on Deep Learning Models under Neural Structural Obfuscation**](http://arxiv.org/abs/2303.09732v1)

*Yifan Yan, Xudong Pan, Mi Zhang, Min Yang*

{{< details "abstract" >}} abstract: Copyright protection for deep neural networks (DNNs) is an urgent need for AIcorporations. To trace illegally distributed model copies, DNN watermarking isan emerging technique for embedding and verifying secret identity messages inthe prediction behaviors or the model internals. Sacrificing less functionalityand involving more knowledge about the target DNN, the latter branch called\textit{white-box DNN watermarking} is believed to be accurate, credible andsecure against most known watermark removal attacks, with emerging researchefforts in both the academy and the industry.  In this paper, we present the first systematic study on how the mainstreamwhite-box DNN watermarks are commonly vulnerable to neural structuralobfuscation with \textit{dummy neurons}, a group of neurons which can be addedto a target model but leave the model behavior invariant. Devising acomprehensive framework to automatically generate and inject dummy neurons withhigh stealthiness, our novel attack intensively modifies the architecture ofthe target model to inhibit the success of watermark verification. Withextensive evaluation, our work for the first time shows that nine publishedwatermarking schemes require amendments to their verification procedures.
{{< /details >}}

>**_2023-03-12_**

[**DNN-Alias: Deep Neural Network Protection Against Side-Channel Attacks via Layer Balancing**](http://arxiv.org/abs/2303.06746v1)

*Mahya Morid Ahmadi, Lilas Alrahis, Ozgur Sinanoglu, Muhammad Shafique*

{{< details "abstract" >}} abstract: Extracting the architecture of layers of a given deep neural network (DNN)through hardware-based side channels allows adversaries to steal itsintellectual property and even launch powerful adversarial attacks on thetarget system. In this work, we propose DNN-Alias, an obfuscation method forDNNs that forces all the layers in a given network to have similar executiontraces, preventing attack models from differentiating between the layers.Towards this, DNN-Alias performs various layer-obfuscation operations, e.g.,layer branching, layer deepening, etc, to alter the run-time traces whilemaintaining the functionality. DNN-Alias deploys an evolutionary algorithm tofind the best combination of obfuscation operations in terms of maximizing thesecurity level while maintaining a user-provided latency overhead budget. Wedemonstrate the effectiveness of our DNN-Alias technique by obfuscating thearchitecture of 700 randomly generated and obfuscated DNNs running on multipleNvidia RTX 2080 TI GPU-based machines. Our experiments show thatstate-of-the-art side-channel architecture stealing attacks cannot extract theoriginal DNN accurately. Moreover, we obfuscate the architecture of variousDNNs, such as the VGG-11, VGG-13, ResNet-20, and ResNet-32 networks. Trainingthe DNNs using the standard CIFAR10 dataset, we show that our DNN-Aliasmaintains the functionality of the original DNNs by preserving the originalinference accuracy. Further, the experiments highlight that adversarial attackon obfuscated DNNs is unsuccessful.
{{< /details >}}

>**_2023-03-08_**

[**From Tensor Network Quantum States to Tensorial Recurrent Neural Networks**](http://arxiv.org/abs/2206.12363v2)

*Dian Wu, Riccardo Rossi, Filippo Vicentini, Giuseppe Carleo*

{{< details "abstract" >}} abstract: We show that any matrix product state (MPS) can be exactly represented by arecurrent neural network (RNN) with a linear memory update. We generalize thisRNN architecture to 2D lattices using a multilinear memory update. It supportsperfect sampling and wave function evaluation in polynomial time, and canrepresent an area law of entanglement entropy. Numerical evidence shows that itcan encode the wave function using a bond dimension lower by orders ofmagnitude when compared to MPS, with an accuracy that can be systematicallyimproved by increasing the bond dimension.
{{< /details >}}

>**_2023-03-06_**

[**HARDC : A novel ECG-based heartbeat classification method to detect arrhythmia using hierarchical attention based dual structured RNN with dilated CNN**](http://arxiv.org/abs/2303.06020v1)

*Md Shofiqul Islam, Khondokar Fida Hasan, Sunjida Sultana, Shahadat Uddin, Pietro Lio, Julian M. W. Quinn, Mohammad Ali Moni*

{{< details "abstract" >}} abstract: In this paper have developed a novel hybrid hierarchical attention-basedbidirectional recurrent neural network with dilated CNN (HARDC) method forarrhythmia classification. This solves problems that arise when traditionaldilated convolutional neural network (CNN) models disregard the correlationbetween contexts and gradient dispersion. The proposed HARDC fully exploits thedilated CNN and bidirectional recurrent neural network unit (BiGRU-BiLSTM)architecture to generate fusion features. As a result of incorporating bothlocal and global feature information and an attention mechanism, the model'sperformance for prediction is improved.By combining the fusion features with adilated CNN and a hierarchical attention mechanism, the trained HARDC modelshowed significantly improved classification results and interpretability offeature extraction on the PhysioNet 2017 challenge dataset. Sequential Z-Scorenormalization, filtering, denoising, and segmentation are used to prepare theraw data for analysis. CGAN (Conditional Generative Adversarial Network) isthen used to generate synthetic signals from the processed data. Theexperimental results demonstrate that the proposed HARDC model significantlyoutperforms other existing models, achieving an accuracy of 99.60\%, F1 scoreof 98.21\%, a precision of 97.66\%, and recall of 99.60\% using MIT-BIHgenerated ECG. In addition, this approach substantially reduces run time whenusing dilated CNN compared to normal convolution. Overall, this hybrid modeldemonstrates an innovative and cost-effective strategy for ECG signalcompression and high-performance ECG recognition. Our results indicate that anautomated and highly computed method to classify multiple types of arrhythmiasignals holds considerable promise.
{{< /details >}}

>**_2023-03-02_**

[**Learning General Audio Representations with Large-Scale Training of Patchout Audio Transformers**](http://arxiv.org/abs/2211.13956v2)

*Khaled Koutini, Shahed Masoudian, Florian Schmid, Hamid Eghbal-zadeh, Jan Schlüter, Gerhard Widmer*

{{< details "abstract" >}} abstract: The success of supervised deep learning methods is largely due to theirability to learn relevant features from raw data. Deep Neural Networks (DNNs)trained on large-scale datasets are capable of capturing a diverse set offeatures, and learning a representation that can generalize onto unseen tasksand datasets that are from the same domain. Hence, these models can be used aspowerful feature extractors, in combination with shallower models asclassifiers, for smaller tasks and datasets where the amount of training datais insufficient for learning an end-to-end model from scratch. During the pastyears, Convolutional Neural Networks (CNNs) have largely been the method ofchoice for audio processing. However, recently attention-based transformermodels have demonstrated great potential in supervised settings, outperformingCNNs. In this work, we investigate the use of audio transformers trained onlarge-scale datasets to learn general-purpose representations. We study how thedifferent setups in these audio transformers affect the quality of theirembeddings. We experiment with the models' time resolution, extracted embeddinglevel, and receptive fields in order to see how they affect performance on avariety of tasks and datasets, following the HEAR 2021 NeurIPS challengeevaluation setup. Our results show that representations extracted by audiotransformers outperform CNN representations. Furthermore, we will show thattransformers trained on Audioset can be extremely effective representationextractors for a wide range of downstream tasks.
{{< /details >}}

>**_2023-02-28_**

[**Good Artists Copy, Great Artists Steal: Model Extraction Attacks Against Image Translation Models**](http://arxiv.org/abs/2104.12623v2)

*Sebastian Szyller, Vasisht Duddu, Tommi Gröndahl, N. Asokan*

{{< details "abstract" >}} abstract: Machine learning models are typically made available to potential clientusers via inference APIs. Model extraction attacks occur when a maliciousclient uses information gleaned from queries to the inference API of a victimmodel $F_V$ to build a surrogate model $F_A$ with comparable functionality.Recent research has shown successful model extraction of image classification,and natural language processing models. In this paper, we show the first modelextraction attack against real-world generative adversarial network (GAN) imagetranslation models. We present a framework for conducting such attacks, andshow that an adversary can successfully extract functional surrogate models byquerying $F_V$ using data from the same domain as the training data for $F_V$.The adversary need not know $F_V$'s architecture or any other information aboutit beyond its intended task. We evaluate the effectiveness of our attacks usingthree different instances of two popular categories of image translation: (1)Selfie-to-Anime and (2) Monet-to-Photo (image style transfer), and (3)Super-Resolution (super resolution). Using standard performance metrics forGANs, we show that our attacks are effective. Furthermore, we conducted a largescale (125 participants) user study on Selfie-to-Anime and Monet-to-Photo toshow that human perception of the images produced by $F_V$ and $F_A$ can beconsidered equivalent, within an equivalence bound of Cohen's d = 0.3. Finally,we show that existing defenses against model extraction attacks (watermarking,adversarial examples, poisoning) do not extend to image translation models.
{{< /details >}}

>**_2023-02-27_**

[**MotifExplainer: a Motif-based Graph Neural Network Explainer**](http://arxiv.org/abs/2202.00519v2)

*Zhaoning Yu, Hongyang Gao*

{{< details "abstract" >}} abstract: We consider the explanation problem of Graph Neural Networks (GNNs). Mostexisting GNN explanation methods identify the most important edges or nodes butfail to consider substructures, which are more important for graph data. Theonly method that considers subgraphs tries to search all possible subgraphs andidentify the most significant subgraphs. However, the subgraphs identified maynot be recurrent or statistically important. In this work, we propose a novelmethod, known as MotifExplainer, to explain GNNs by identifying importantmotifs, recurrent and statistically significant patterns in graphs. Ourproposed motif-based methods can provide better human-understandableexplanations than methods based on nodes, edges, and regular subgraphs. Givenan input graph and a pre-trained GNN model, our method first extracts motifs inthe graph using well-designed motif extraction rules. Then we generate motifembedding by feeding motifs into the pre-trained GNN. Finally, we employ anattention-based method to identify the most influential motifs as explanationsfor the final prediction results. The empirical studies on both synthetic andreal-world datasets demonstrate the effectiveness of our method.
{{< /details >}}

>**_2023-02-20_**

[**Black Boxes, White Noise: Similarity Detection for Neural Functions**](http://arxiv.org/abs/2302.10005v1)

*Farima Farmahinifarahani, Cristina V. Lopes*

{{< details "abstract" >}} abstract: Similarity, or clone, detection has important applications in copyrightviolation, software theft, code search, and the detection of maliciouscomponents. There is now a good number of open source and proprietary clonedetectors for programs written in traditional programming languages. However,the increasing adoption of deep learning models in software poses a challengeto these tools: these models implement functions that are inscrutable blackboxes. As more software includes these DNN functions, new techniques are neededin order to assess the similarity between deep learning components of software.Previous work has unveiled techniques for comparing the representations learnedat various layers of deep neural network models by feeding canonical inputs tothe models. Our goal is to be able to compare DNN functions when canonicalinputs are not available -- because they may not be in many applicationscenarios. The challenge, then, is to generate appropriate inputs and toidentify a metric that, for those inputs, is capable of representing the degreeof functional similarity between two comparable DNN functions.  Our approach uses random input with values between -1 and 1, in a shape thatis compatible with what the DNN models expect. We then compare the outputs byperforming correlation analysis. Our study shows how it is possible to performsimilarity analysis even in the absence of meaningful canonical inputs. Theresponse to random inputs of two comparable DNN functions exposes thosefunctions' similarity, or lack thereof. Of all the metrics tried, we find thatSpearman's rank correlation coefficient is the most powerful and versatile,although in special cases other methods and metrics are more expressive. Wepresent a systematic empirical study comparing the effectiveness of severalsimilarity metrics using a dataset of 56,355 classifiers collected from GitHub.This is accompanied by a sensitivity analysis that reveals how certain models'training related properties affect the effectiveness of the similarity metrics.  To the best of our knowledge, this is the first work that shows howsimilarity of DNN functions can be detected by using random inputs. Our studyof correlation metrics, and the identification of Spearman correlationcoefficient as the most powerful among them for this purpose, establishes acomplete and practical method for DNN clone detection that can be used in thedesign of new tools. It may also serve as inspiration for other programanalysis tasks whose approaches break in the presence of DNN components.
{{< /details >}}

>**_2023-02-17_**

[**Learning from Noisy Labels with Decoupled Meta Label Purifier**](http://arxiv.org/abs/2302.06810v3)

*Yuanpeng Tu, Boshen Zhang, Yuxi Li, Liang Liu, Jian Li, Yabiao Wang, Chengjie Wang, Cai Rong Zhao*

{{< details "abstract" >}} abstract: Training deep neural networks(DNN) with noisy labels is challenging since DNNcan easily memorize inaccurate labels, leading to poor generalization ability.Recently, the meta-learning based label correction strategy is widely adoptedto tackle this problem via identifying and correcting potential noisy labelswith the help of a small set of clean validation data. Although training withpurified labels can effectively improve performance, solving the meta-learningproblem inevitably involves a nested loop of bi-level optimization betweenmodel weights and hyper-parameters (i.e., label distribution). As compromise,previous methods resort to a coupled learning process with alternating update.In this paper, we empirically find such simultaneous optimization over bothmodel weights and label distribution can not achieve an optimal routine,consequently limiting the representation ability of backbone and accuracy ofcorrected labels. From this observation, a novel multi-stage label purifiernamed DMLP is proposed. DMLP decouples the label correction process intolabel-free representation learning and a simple meta label purifier. In thisway, DMLP can focus on extracting discriminative feature and label correctionin two distinctive stages. DMLP is a plug-and-play label purifier, the purifiedlabels can be directly reused in naive end-to-end network retraining or otherrobust learning methods, where state-of-the-art results are obtained on severalsynthetic and real-world noisy datasets, especially under high noise levels.
{{< /details >}}

>**_2023-02-13_**

[**Targeted Attack on GPT-Neo for the SATML Language Model Data Extraction Challenge**](http://arxiv.org/abs/2302.07735v1)

*Ali Al-Kaswan, Maliheh Izadi, Arie van Deursen*

{{< details "abstract" >}} abstract: Previous work has shown that Large Language Models are susceptible toso-called data extraction attacks. This allows an attacker to extract a samplethat was contained in the training data, which has massive privacyimplications. The construction of data extraction attacks is challenging,current attacks are quite inefficient, and there exists a significant gap inthe extraction capabilities of untargeted attacks and memorization. Thus,targeted attacks are proposed, which identify if a given sample from thetraining data, is extractable from a model. In this work, we apply a targeteddata extraction attack to the SATML2023 Language Model Training Data ExtractionChallenge. We apply a two-step approach. In the first step, we maximise therecall of the model and are able to extract the suffix for 69% of the samples.In the second step, we use a classifier-based Membership Inference Attack onthe generations. Our AutoSklearn classifier achieves a precision of 0.841. Thefull approach reaches a score of 0.405 recall at a 10% false positive rate,which is an improvement of 34% over the baseline of 0.301.
{{< /details >}}

>**_2023-01-27_**

[**SplitGNN: Splitting GNN for Node Classification with Heterogeneous Attention**](http://arxiv.org/abs/2301.12885v1)

*Xiaolong Xu, Lingjuan Lyu, Yihong Dong, Yicheng Lu, Weiqiang Wang, Hong Jin*

{{< details "abstract" >}} abstract: With the frequent happening of privacy leakage and the enactment of privacylaws across different countries, data owners are reluctant to directly sharetheir raw data and labels with any other party. In reality, a lot of these rawdata are stored in the graph database, especially for finance. Forcollaboratively building graph neural networks(GNNs), federated learning(FL)may not be an ideal choice for the vertically partitioned setting where privacyand efficiency are the main concerns. Moreover, almost all the existingfederated GNNs are mainly designed for homogeneous graphs, which simplifyvarious types of relations as the same type, thus largely limits theirperformance. We bridge this gap by proposing a split learning-basedGNN(SplitGNN), where this model is divided into two sub-models: the local GNNmodel includes all the private data related computation to generate local nodeembeddings, whereas the global model calculates global embeddings byaggregating all the participants' local embeddings. Our SplitGNN allows theisolated heterogeneous neighborhood to be collaboratively utilized. To bettercapture representations, we propose a novel Heterogeneous Attention(HAT)algorithm and use both node-based and path-based attention mechanisms to learnvarious types of nodes and edges with multi-hop relation features. Wedemonstrate the effectiveness of our SplitGNN on node classification tasks fortwo standard public datasets and the real-world dataset. Extensive experimentalresults validate that our proposed SplitGNN significantly outperforms thestate-of-the-art(SOTA) methods.
{{< /details >}}

>**_2022-12-21_**

[**Device-Bind Key-Storageless Hardware AI Model IP Protection: A PUF and Permute-Diffusion Encryption-Enabled Approach**](http://arxiv.org/abs/2212.11133v1)

*Qianqian Pan, Mianxiong Dong, Kaoru Ota, Jun Wu*

{{< details "abstract" >}} abstract: Machine learning as a service (MLaaS) framework provides intelligent servicesor well-trained artificial intelligence (AI) models for local devices. However,in the process of model transmission and deployment, there are security issues,i.e. AI model leakage due to the unreliable transmission environments andillegal abuse at local devices without permission. Although existing worksstudy the intellectual property (IP) protection of AI models, they mainly focuson the watermark-based and encryption-based methods and have the followingproblems: (i) The watermark-based methods only provide passive verificationafterward rather than active protection. (ii) Encryption-based methods are lowefficiency in computation and low security in key storage. (iii) The existingmethods are not device-bind without the ability to avoid illegal abuse of AImodels. To deal with these problems, we propose a device-bind andkey-storageless hardware AI model IP protection mechanism. First, a physicalunclonable function (PUF) and permute-diffusion encryption-based AI modelprotection framework is proposed, including the PUF-based secret key generationand the geometric-value transformation-based weights encryption. Second, wedesign a PUF-based key generation protocol, where delay-based Anderson PUF isadopted to generate the derive-bind secret key. Besides, convolutional codingand convolutional interleaving technologies are combined to improve thestability of PUF-based key generation and reconstruction. Third, a permute anddiffusion-based intelligent model weights encryption/decryption method isproposed to achieve effective IP protection, where chaos theory is utilized toconvert the PUF-based secret key to encryption/decryption keys. Finally,experimental evaluation demonstrates the effectiveness of the proposedintelligent model IP protection mechanism.
{{< /details >}}

>**_2022-12-14_**

[**A Survey on Privacy of Personal and Non-Personal Data in B5G/6G Networks**](http://arxiv.org/abs/2212.06987v1)

*Chamara Sandeepa, Bartlomiej Siniarski, Nicolas Kourtellis, Shen Wang, Madhusanka Liyanage*

{{< details "abstract" >}} abstract: The upcoming Beyond 5G (B5G) and 6G networks are expected to provide enhancedcapabilities such as ultra-high data rates, dense connectivity, and highscalability. It opens many possibilities for a new generation of servicesdriven by Artificial Intelligence (AI) and billions of interconnected smartdevices. However, with this expected massive upgrade, the privacy of people,organizations, and states is becoming a rising concern. The recent introductionof privacy laws and regulations for personal and non-personal data signals thatglobal awareness is emerging in the current privacy landscape. Yet, many gapsneed to be identified in the case of two data types. If not detected, they canlead to significant privacy leakages and attacks that will affect billions ofpeople and organizations who utilize B5G/6G. This survey is a comprehensivestudy of personal and non-personal data privacy in B5G/6G to identify thecurrent progress and future directions to ensure data privacy. We provide adetailed comparison of the two data types and a set of related privacy goalsfor B5G/6G. Next, we bring data privacy issues with possible solutions. Thispaper also provides future directions to preserve personal and non-personaldata privacy in future networks.
{{< /details >}}

[**DR.BENCH: Diagnostic Reasoning Benchmark for Clinical Natural Language Processing**](http://arxiv.org/abs/2209.14901v2)

*Yanjun Gao, Dmitriy Dligach, Timothy Miller, John Caskey, Brihat Sharma, Matthew M Churpek, Majid Afshar*

{{< details "abstract" >}} abstract: The meaningful use of electronic health records (EHR) continues to progressin the digital era with clinical decision support systems augmented byartificial intelligence. A priority in improving provider experience is toovercome information overload and reduce the cognitive burden so fewer medicalerrors and cognitive biases are introduced during patient care. One major typeof medical error is diagnostic error due to systematic or predictable errors injudgment that rely on heuristics. The potential for clinical natural languageprocessing (cNLP) to model diagnostic reasoning in humans with forwardreasoning from data to diagnosis and potentially reduce the cognitive burdenand medical error has not been investigated. Existing tasks to advance thescience in cNLP have largely focused on information extraction and named entityrecognition through classification tasks. We introduce a novel suite of taskscoined as Diagnostic Reasoning Benchmarks, DR.BENCH, as a new benchmark fordeveloping and evaluating cNLP models with clinical diagnostic reasoningability. The suite includes six tasks from ten publicly available datasetsaddressing clinical text understanding, medical knowledge reasoning, anddiagnosis generation. DR.BENCH is the first clinical suite of tasks designed tobe a natural language generation framework to evaluate pre-trained languagemodels. Experiments with state-of-the-art pre-trained generative languagemodels using large general domain models and models that were continuallytrained on a medical corpus demonstrate opportunities for improvement whenevaluated in DR. BENCH. We share DR. BENCH as a publicly available GitLabrepository with a systematic approach to load and evaluate models for the cNLPcommunity.
{{< /details >}}

>**_2022-12-13_**

[**Attentive Deep Neural Networks for Legal Document Retrieval**](http://arxiv.org/abs/2212.13899v1)

*Ha-Thanh Nguyen, Manh-Kien Phi, Xuan-Bach Ngo, Vu Tran, Le-Minh Nguyen, Minh-Phuong Tu*

{{< details "abstract" >}} abstract: Legal text retrieval serves as a key component in a wide range of legal textprocessing tasks such as legal question answering, legal case entailment, andstatute law retrieval. The performance of legal text retrieval depends, to alarge extent, on the representation of text, both query and legal documents.Based on good representations, a legal text retrieval model can effectivelymatch the query to its relevant documents. Because legal documents oftencontain long articles and only some parts are relevant to queries, it is quitea challenge for existing models to represent such documents. In this paper, westudy the use of attentive neural network-based text representation for statutelaw document retrieval. We propose a general approach using deep neuralnetworks with attention mechanisms. Based on it, we develop two hierarchicalarchitectures with sparse attention to represent long sentences and articles,and we name them Attentive CNN and Paraformer. The methods are evaluated ondatasets of different sizes and characteristics in English, Japanese, andVietnamese. Experimental results show that: i) Attentive neural methodssubstantially outperform non-neural methods in terms of retrieval performanceacross datasets and languages; ii) Pretrained transformer-based models achievebetter accuracy on small datasets at the cost of high computational complexitywhile lighter weight Attentive CNN achieves better accuracy on large datasets;and iii) Our proposed Paraformer outperforms state-of-the-art methods on COLIEEdataset, achieving the highest recall and F2 scores in the top-N retrievaltask.
{{< /details >}}

[**PCRED: Zero-shot Relation Triplet Extraction with Potential Candidate Relation Selection and Entity Boundary Detection**](http://arxiv.org/abs/2211.14477v2)

*Yuquan Lan, Dongxu Li, Yunqi Zhang, Hui Zhao, Gang Zhao*

{{< details "abstract" >}} abstract: Zero-shot relation triplet extraction (ZeroRTE) aims to extract relationtriplets from unstructured texts under the zero-shot setting, where therelation sets at the training and testing stages are disjoint. Previousstate-of-the-art method handles this challenging task by leveraging pretrainedlanguage models to generate data as additional training samples, whichincreases the training cost and severely constrains the model performance. Toaddress the above issues, we propose a novel method named PCRED for ZeroRTEwith Potential Candidate Relation Selection and Entity Boundary Detection. Theremarkable characteristic of PCRED is that it does not rely on additional dataand still achieves promising performance. The model adopts a relation-firstparadigm, recognizing unseen relations through candidate relation selection.With this approach, the semantics of relations are naturally infused in thecontext. Entities are extracted based on the context and the semantics ofrelations subsequently. We evaluate our model on two ZeroRTE datasets. Theexperiment results show that our method consistently outperforms previousworks. Our code will be available at https://anonymous.4open.science/r/PCRED.
{{< /details >}}

>**_2022-12-08_**

[**Generating and Weighting Semantically Consistent Sample Pairs for Ultrasound Contrastive Learning**](http://arxiv.org/abs/2212.04097v1)

*Yixiong Chen, Chunhui Zhang, Chris H. Q. Ding, Li Liu*

{{< details "abstract" >}} abstract: Well-annotated medical datasets enable deep neural networks (DNNs) to gainstrong power in extracting lesion-related features. Building such large andwell-designed medical datasets is costly due to the need for high-levelexpertise. Model pre-training based on ImageNet is a common practice to gainbetter generalization when the data amount is limited. However, it suffers fromthe domain gap between natural and medical images. In this work, we pre-trainDNNs on ultrasound (US) domains instead of ImageNet to reduce the domain gap inmedical US applications. To learn US image representations based on unlabeledUS videos, we propose a novel meta-learning-based contrastive learning method,namely Meta Ultrasound Contrastive Learning (Meta-USCL). To tackle the keychallenge of obtaining semantically consistent sample pairs for contrastivelearning, we present a positive pair generation module along with an automaticsample weighting module based on meta-learning. Experimental results onmultiple computer-aided diagnosis (CAD) problems, including pneumoniadetection, breast cancer classification, and breast tumor segmentation, showthat the proposed self-supervised method reaches state-of-the-art (SOTA). Thecodes are available at https://github.com/Schuture/Meta-USCL.
{{< /details >}}

>**_2022-12-03_**

[**High-resolution and reliable automatic target recognition based on photonic ISAR imaging system with explainable deep learning**](http://arxiv.org/abs/2212.01560v1)

*Xiuting Zou, Anyi Deng, Yiheng Hu, Shiyu Hua, Linbo Zhang, Shaofu Xu, Weiwen Zou*

{{< details "abstract" >}} abstract: Automatic target recognition (ATR) based on inverse synthetic aperture radar(ISAR) images, which is extensively utilized to surveil environment in militaryand civil fields, must be high-precision and reliable. Photonic technologies'advantage of broad bandwidth enables ISAR systems to realize high-resolutionimaging, which is in favor of achieving high-performance ATR. Deep learning(DL) algorithms have achieved excellent recognition accuracies. However, thelack of interpretability of DL algorithms causes the head-scratching problem ofcredibility. In this paper, we exploit the inner relationship between aphotonic ISAR imaging system and behaviors of a convolutional neural network(CNN) to deeply comprehend the intelligent recognition. Specifically, wemanipulate imaging physical process and analyze network outputs, the relevancebetween the ISAR image and network output, and the visualization of features inthe network output layer. Consequently, the broader imaging bandwidths andappropriate imaging angles lead to more detailed structural and contourfeatures and the bigger discrepancy among ISAR images of different targets,which contributes to the CNN recognizing and distinguishing objects accordingto physical laws. Then, based on the photonic ISAR imaging system and theexplainable CNN, we accomplish a high-accuracy and reliable ATR. To the best ofour knowledge, there is no precedent of explaining the DL algorithms byexploring the influence of the physical process of data generation on networkbehaviors. It is anticipated that this work can not only inspire theaccomplishment of a high-performance ATR but also bring new insights to explorenetwork behaviors and thus achieve better intelligent abilities.
{{< /details >}}

>**_2022-11-28_**

[**Semi-Supervised Specific Emitter Identification Method Using Metric-Adversarial Training**](http://arxiv.org/abs/2211.15379v1)

*Xue Fu, Yang Peng, Yuchao Liu, Yun Lin, Guan Gui, Haris Gacanin, Fumiyuki Adachi*

{{< details "abstract" >}} abstract: Specific emitter identification (SEI) plays an increasingly crucial andpotential role in both military and civilian scenarios. It refers to a processto discriminate individual emitters from each other by analyzing extractedcharacteristics from given radio signals. Deep learning (DL) and deep neuralnetworks (DNNs) can learn the hidden features of data and build the classifierautomatically for decision making, which have been widely used in the SEIresearch. Considering the insufficiently labeled training samples and largeunlabeled training samples, semi-supervised learning-based SEI (SS-SEI) methodshave been proposed. However, there are few SS-SEI methods focusing onextracting the discriminative and generalized semantic features of radiosignals. In this paper, we propose an SS-SEI method using metric-adversarialtraining (MAT). Specifically, pseudo labels are innovatively introduced intometric learning to enable semi-supervised metric learning (SSML), and anobjective function alternatively regularized by SSML and virtual adversarialtraining (VAT) is designed to extract discriminative and generalized semanticfeatures of radio signals. The proposed MAT-based SS-SEI method is evaluated onan open-source large-scale real-world automatic-dependentsurveillance-broadcast (ADS-B) dataset and WiFi dataset and is compared withstate-of-the-art methods. The simulation results show that the proposed methodachieves better identification performance than existing state-of-the-artmethods. Specifically, when the ratio of the number of labeled training samplesto the number of all training samples is 10\%, the identification accuracy is84.80\% under the ADS-B dataset and 80.70\% under the WiFi dataset. Our codecan be downloaded from https://github.com/lovelymimola/MAT-based-SS-SEI.
{{< /details >}}

>**_2022-11-22_**

[**Boosting Personalised Musculoskeletal Modelling with Physics-informed Knowledge Transfer**](http://arxiv.org/abs/2211.12315v1)

*Jie Zhang, Yihui Zhao, Tianzhe Bao, Zhenhong Li, Kun Qian, Alejandro F. Frangi, Sheng Quan Xie, Zhi-Qiang Zhang*

{{< details "abstract" >}} abstract: Data-driven methods have become increasingly more prominent formusculoskeletal modelling due to their conceptually intuitive simple and fastimplementation. However, the performance of a pre-trained data-driven modelusing the data from specific subject(s) may be seriously degraded whenvalidated using the data from a new subject, hindering the utility of thepersonalised musculoskeletal model in clinical applications. This paperdevelops an active physics-informed deep transfer learning framework to enhancethe dynamic tracking capability of the musculoskeletal model on the unseendata. The salient advantages of the proposed framework are twofold: 1) For thegeneric model, physics-based domain knowledge is embedded into the lossfunction of the data-driven model as soft constraints to penalise/regularisethe data-driven model. 2) For the personalised model, the parameters relatingto the feature extraction will be directly inherited from the generic model,and only the parameters relating to the subject-specific inference will befinetuned by jointly minimising the conventional data prediction loss and themodified physics-based loss. In this paper, we use the synchronous muscleforces and joint kinematics prediction from surface electromyogram (sEMG) asthe exemplar to illustrate the proposed framework. Moreover, convolutionalneural network (CNN) is employed as the deep neural network to implement theproposed framework, and the physics law between muscle forces and jointkinematics is utilised as the soft constraints. Results of comprehensiveexperiments on a self-collected dataset from eight healthy subjects indicatethe effectiveness and great generalization of the proposed framework.
{{< /details >}}

>**_2022-11-13_**

[**Watermarking Graph Neural Networks based on Backdoor Attacks**](http://arxiv.org/abs/2110.11024v5)

*Jing Xu, Stefanos Koffas, Oguzhan Ersoy, Stjepan Picek*

{{< details "abstract" >}} abstract: Graph Neural Networks (GNNs) have achieved promising performance in variousreal-world applications. Building a powerful GNN model is not a trivial task,as it requires a large amount of training data, powerful computing resources,and human expertise in fine-tuning the model. Moreover, with the development ofadversarial attacks, e.g., model stealing attacks, GNNs raise challenges tomodel authentication. To avoid copyright infringement on GNNs, verifying theownership of the GNN models is necessary.  This paper presents a watermarking framework for GNNs for both graph and nodeclassification tasks. We 1) design two strategies to generate watermarked datafor the graph classification task and one for the node classification task, 2)embed the watermark into the host model through training to obtain thewatermarked GNN model, and 3) verify the ownership of the suspicious model in ablack-box setting. The experiments show that our framework can verify theownership of GNN models with a very high probability (up to $99\%$) for bothtasks. Finally, we experimentally show that our watermarking approach is robustagainst a state-of-the-art model extraction technique and four state-of-the-artdefenses against backdoor attacks.
{{< /details >}}

>**_2022-11-11_**

[**Harmonizing the object recognition strategies of deep neural networks with humans**](http://arxiv.org/abs/2211.04533v2)

*Thomas Fel, Ivan Felipe, Drew Linsley, Thomas Serre*

{{< details "abstract" >}} abstract: The many successes of deep neural networks (DNNs) over the past decade havelargely been driven by computational scale rather than insights from biologicalintelligence. Here, we explore if these trends have also carried concomitantimprovements in explaining the visual strategies humans rely on for objectrecognition. We do this by comparing two related but distinct properties ofvisual strategies in humans and DNNs: where they believe important visualfeatures are in images and how they use those features to categorize objects.Across 84 different DNNs trained on ImageNet and three independent datasetsmeasuring the where and the how of human visual strategies for objectrecognition on those images, we find a systematic trade-off between DNNcategorization accuracy and alignment with human visual strategies for objectrecognition. State-of-the-art DNNs are progressively becoming less aligned withhumans as their accuracy improves. We rectify this growing issue with ourneural harmonizer: a general-purpose training routine that both aligns DNN andhuman visual strategies and improves categorization accuracy. Our workrepresents the first demonstration that the scaling laws that are guiding thedesign of DNNs today have also produced worse models of human vision. Werelease our code and data at https://serre-lab.github.io/Harmonization to helpthe field build more human-like DNNs.
{{< /details >}}

>**_2022-10-27_**

[**DICTION: DynamIC robusT whIte bOx watermarkiNg scheme**](http://arxiv.org/abs/2210.15745v1)

*Reda Bellafqira, Gouenou Coatrieux*

{{< details "abstract" >}} abstract: Deep neural network (DNN) watermarking is a suitable method for protectingthe ownership of deep learning (DL) models derived from computationallyintensive processes and painstakingly compiled and annotated datasets. Itsecretly embeds an identifier (watermark) within the model, which can beretrieved by the owner to prove ownership. In this paper, we first provide aunified framework for white box DNN watermarking schemes. It includes currentstate-of-the art methods outlining their theoretical inter-connections. Insecond, we introduce DICTION, a new white-box Dynamic Robust watermarkingscheme, we derived from this framework. Its main originality stands on agenerative adversarial network (GAN) strategy where the watermark extractionfunction is a DNN trained as a GAN discriminator, and the target model towatermark as a GAN generator taking a GAN latent space as trigger set input.DICTION can be seen as a generalization of DeepSigns which, to the best ofknowledge, is the only other Dynamic white-box watermarking scheme from theliterature. Experiments conducted on the same model test set as Deepsignsdemonstrate that our scheme achieves much better performance. Especially, andcontrarily to DeepSigns, with DICTION one can increase the watermark capacitywhile preserving at best the model accuracy and ensuring simultaneously astrong robustness against a wide range of watermark removal and detectionattacks.
{{< /details >}}

>**_2022-10-25_**

[**BYOL-S: Learning Self-supervised Speech Representations by Bootstrapping**](http://arxiv.org/abs/2206.12038v4)

*Gasser Elbanna, Neil Scheidwasser-Clow, Mikolaj Kegler, Pierre Beckmann, Karl El Hajal, Milos Cernak*

{{< details "abstract" >}} abstract: Methods for extracting audio and speech features have been studied sincepioneering work on spectrum analysis decades ago. Recent efforts are guided bythe ambition to develop general-purpose audio representations. For example,deep neural networks can extract optimal embeddings if they are trained onlarge audio datasets. This work extends existing methods based onself-supervised learning by bootstrapping, proposes various encoderarchitectures, and explores the effects of using different pre-trainingdatasets. Lastly, we present a novel training framework to come up with ahybrid audio representation, which combines handcrafted and data-driven learnedaudio features. All the proposed representations were evaluated within the HEARNeurIPS 2021 challenge for auditory scene classification and timestampdetection tasks. Our results indicate that the hybrid model with aconvolutional transformer as the encoder yields superior performance in mostHEAR challenge tasks.
{{< /details >}}

>**_2022-10-19_**

[**Analysis of Ring Galaxies Detected Using Deep Learning with Real and Simulated Data**](http://arxiv.org/abs/2210.11428v1)

*Harish Krishnakumar, J. Bryce Kalmbach*

{{< details "abstract" >}} abstract: Understanding the formation and evolution of ring galaxies, galaxies with anatypical ring-like structure, will improve understanding of black holes andgalaxy dynamics as a whole. Current catalogs of rings are extremely limited:manual analysis takes months to accumulate an appreciable sample of rings andexisting computational methods are vastly limited in terms of accuracy anddetection rate. Without a sizable sample of rings, further research into theirproperties is severely restricted. This project investigates the usage of aconvolutional neural network (CNN) to identify rings from unclassified samplesof galaxies. A CNN was trained on a sample of 100,000 simulated galaxies,transfer learned to a sample of real galaxies and applied to a previouslyunclassified dataset to generate a catalog of rings which was then manuallyverified. Data augmentation with a generative adversarial network (GAN) tosimulate images of galaxies was also used. A catalog of 1151 rings wasextracted with 7.4 times the precision and 15.4 times the detection rate ofconventional algorithms. The properties of these galaxies were then estimatedfrom their photometry and compared to the Galaxy Zoo 2 catalog of rings. Withupcoming surveys such as the Vera Rubin Observatory Legacy Survey of Space andTime obtaining images of billions of galaxies, similar models could be crucialin classifying large populations of rings to better understand the peculiarmechanisms by which they form and evolve.
{{< /details >}}

>**_2022-10-18_**

[**A Deep Learning Approach to Infer Galaxy Cluster Masses from Planck Compton$-y$ parameter maps**](http://arxiv.org/abs/2209.10333v2)

*Daniel de Andres, Weiguang Cui, Florian Ruppin, Marco De Petris, Gustavo Yepes, Giulia Gianfagna, Ichraf Lahouli, Gianmarco Aversano, Romain Dupuis, Mahmoud Jarraya, Jesús Vega-Ferrero*

{{< details "abstract" >}} abstract: Galaxy clusters are useful laboratories to investigate the evolution of theUniverse, and accurately measuring their total masses allows us to constrainimportant cosmological parameters. However, estimating mass from observationsthat use different methods and spectral bands introduces various systematicerrors. This paper evaluates the use of a Convolutional Neural Network (CNN) toreliably and accurately infer the masses of galaxy clusters from the Compton-yparameter maps provided by the Planck satellite. The CNN is trained with mockimages generated from hydrodynamic simulations of galaxy clusters, withPlanck's observational limitations taken into account. We observe that the CNNapproach is not subject to the usual observational assumptions, and so is notaffected by the same biases. By applying the trained CNNs to the real Planckmaps, we find cluster masses compatible with Planck measurements within a 15%bias. Finally, we show that this mass bias can be explained by the well knownhydrostatic equilibrium assumption in Planck masses, and the differentparameters in the Y500-M500 scaling laws. This work highlights that CNNs,supported by hydrodynamic simulations, are a promising and independent tool forestimating cluster masses with high accuracy, which can be extended to othersurveys as well as to observations in other bands.
{{< /details >}}

>**_2022-10-17_**

[**Understanding CNN Fragility When Learning With Imbalanced Data**](http://arxiv.org/abs/2210.09465v1)

*Damien Dablain, Kristen N. Jacobson, Colin Bellinger, Mark Roberts, Nitesh Chawla*

{{< details "abstract" >}} abstract: Convolutional neural networks (CNNs) have achieved impressive results onimbalanced image data, but they still have difficulty generalizing to minorityclasses and their decisions are difficult to interpret. These problems arerelated because the method by which CNNs generalize to minority classes, whichrequires improvement, is wrapped in a blackbox. To demystify CNN decisions onimbalanced data, we focus on their latent features. Although CNNs embed thepattern knowledge learned from a training set in model parameters, the effectof this knowledge is contained in feature and classification embeddings (FE andCE). These embeddings can be extracted from a trained model and their global,class properties (e.g., frequency, magnitude and identity) can be analyzed. Wefind that important information regarding the ability of a neural network togeneralize to minority classes resides in the class top-K CE and FE. We showthat a CNN learns a limited number of class top-K CE per category, and thattheir number and magnitudes vary based on whether the same class is balanced orimbalanced. This calls into question whether a CNN has learned intrinsic classfeatures, or merely frequently occurring ones that happen to exist in thesampled class distribution. We also hypothesize that latent class diversity isas important as the number of class examples, which has important implicationsfor re-sampling and cost-sensitive methods. These methods generally focus onrebalancing model weights, class numbers and margins; instead of diversifyingclass latent features through augmentation. We also demonstrate that a CNN hasdifficulty generalizing to test data if the magnitude of its top-K latentfeatures do not match the training set. We use three popular image datasets andtwo cost-sensitive algorithms commonly employed in imbalanced learning for ourexperiments.
{{< /details >}}

>**_2022-10-05_**

[**Hiding Images in Deep Probabilistic Models**](http://arxiv.org/abs/2210.02257v1)

*Haoyu Chen, Linqi Song, Zhenxing Qian, Xinpeng Zhang, Kede Ma*

{{< details "abstract" >}} abstract: Data hiding with deep neural networks (DNNs) has experienced impressivesuccesses in recent years. A prevailing scheme is to train an autoencoder,consisting of an encoding network to embed (or transform) secret messages in(or into) a carrier, and a decoding network to extract the hidden messages.This scheme may suffer from several limitations regarding practicability,security, and embedding capacity. In this work, we describe a differentcomputational framework to hide images in deep probabilistic models.Specifically, we use a DNN to model the probability density of cover images,and hide a secret image in one particular location of the learned distribution.As an instantiation, we adopt a SinGAN, a pyramid of generative adversarialnetworks (GANs), to learn the patch distribution of one cover image. We hidethe secret image by fitting a deterministic mapping from a fixed set of noisemaps (generated by an embedding key) to the secret image during patchdistribution learning. The stego SinGAN, behaving as the original SinGAN, ispublicly communicated; only the receiver with the embedding key is able toextract the secret image. We demonstrate the feasibility of our SinGAN approachin terms of extraction accuracy and model security. Moreover, we show theflexibility of the proposed method in terms of hiding multiple images fordifferent receivers and obfuscating the secret image.
{{< /details >}}

[**DEGAN: Time Series Anomaly Detection using Generative Adversarial Network Discriminators and Density Estimation**](http://arxiv.org/abs/2210.02449v1)

*Yueyan Gu, Farrokh Jazizadeh*

{{< details "abstract" >}} abstract: Developing efficient time series anomaly detection techniques is important tomaintain service quality and provide early alarms. Generative neural networkmethods are one class of the unsupervised approaches that are achievingincreasing attention in recent years. In this paper, we have proposed anunsupervised Generative Adversarial Network (GAN)-based anomaly detectionframework, DEGAN. It relies solely on normal time series data as input to traina well-configured discriminator (D) into a standalone anomaly predictor. Inthis framework, time series data is processed by the sliding window method.Expected normal patterns in data are leveraged to develop a generator (G)capable of generating normal data patterns. Normal data is also utilized inhyperparameter tuning and D model selection steps. Validated D models are thenextracted and applied to evaluate unseen (testing) time series and identifypatterns that have anomalous characteristics. Kernel density estimation (KDE)is applied to data points that are likely to be anomalous to generateprobability density functions on the testing time series. The segments with thehighest relative probabilities are detected as anomalies. To evaluate theperformance, we tested on univariate acceleration time series for five miles ofa Class I railroad track. We implemented the framework to detect the realanomalous observations identified by operators. The results show thatleveraging the framework with a CNN D architecture results in average bestrecall and precision of 80% and 86%, respectively, which demonstrates that awell-trained standalone D model has the potential to be a reliable anomalydetector. Moreover, the influence of GAN hyperparameters, GAN architectures,sliding window sizes, clustering of time series, and model validation withlabeled/unlabeled data were also investigated.
{{< /details >}}

>**_2022-10-04_**

[**An Embarrassingly Simple Approach for Intellectual Property Rights Protection on Recurrent Neural Networks**](http://arxiv.org/abs/2210.00743v2)

*Zhi Qin Tan, Hao Shan Wong, Chee Seng Chan*

{{< details "abstract" >}} abstract: Capitalise on deep learning models, offering Natural Language Processing(NLP) solutions as a part of the Machine Learning as a Service (MLaaS) hasgenerated handsome revenues. At the same time, it is known that the creation ofthese lucrative deep models is non-trivial. Therefore, protecting theseinventions intellectual property rights (IPR) from being abused, stolen andplagiarized is vital. This paper proposes a practical approach for the IPRprotection on recurrent neural networks (RNN) without all the bells andwhistles of existing IPR solutions. Particularly, we introduce the Gatekeeperconcept that resembles the recurrent nature in RNN architecture to embed keys.Also, we design the model training scheme in a way such that the protected RNNmodel will retain its original performance iff a genuine key is presented.Extensive experiments showed that our protection scheme is robust and effectiveagainst ambiguity and removal attacks in both white-box and black-boxprotection schemes on different RNN variants. Code is available athttps://github.com/zhiqin1998/RecurrentIPR
{{< /details >}}

>**_2022-09-22_**

[**StyleTime: Style Transfer for Synthetic Time Series Generation**](http://arxiv.org/abs/2209.11306v1)

*Yousef El-Laham, Svitlana Vyetrenko*

{{< details "abstract" >}} abstract: Neural style transfer is a powerful computer vision technique that canincorporate the artistic "style" of one image to the "content" of another. Theunderlying theory behind the approach relies on the assumption that the styleof an image is represented by the Gram matrix of its features, which istypically extracted from pre-trained convolutional neural networks (e.g.,VGG-19). This idea does not straightforwardly extend to time series stylizationsince notions of style for two-dimensional images are not analogous to notionsof style for one-dimensional time series. In this work, a novel formulation oftime series style transfer is proposed for the purpose of synthetic datageneration and enhancement. We introduce the concept of stylized features fortime series, which is directly related to the time series realism properties,and propose a novel stylization algorithm, called StyleTime, that uses explicitfeature extraction techniques to combine the underlying content (trend) of onetime series with the style (distributional properties) of another. Further, wediscuss evaluation metrics, and compare our work to existing state-of-the-arttime series generation and augmentation schemes. To validate the effectivenessof our methods, we use stylized synthetic data as a means for data augmentationto improve the performance of recurrent neural network models on severalforecasting tasks.
{{< /details >}}

>**_2022-09-16_**

[**Anomaly Detection in Automatic Generation Control Systems Based on Traffic Pattern Analysis and Deep Transfer Learning**](http://arxiv.org/abs/2209.08099v1)

*Tohid Behdadnia, Geert Deconinck*

{{< details "abstract" >}} abstract: In modern highly interconnected power grids, automatic generation control(AGC) is crucial in maintaining the stability of the power grid. The dependenceof the AGC system on the information and communications technology (ICT) systemmakes it vulnerable to various types of cyber-attacks. Thus, information flow(IF) analysis and anomaly detection became paramount for preventing cyberattackers from driving the cyber-physical power system (CPPS) to instability.In this paper, the ICT network traffic rules in CPPSs are explored and thefrequency domain features of the ICT network traffic are extracted, basicallyfor developing a robust learning algorithm that can learn the normal trafficpattern based on the ResNeSt convolutional neural network (CNN). Furthermore,to overcome the problem of insufficient abnormal traffic labeled samples,transfer learning approach is used. In the proposed data-driven-based methodthe deep learning model is trained by traffic frequency features, which makesour model robust against AGC's parameters uncertainties and modelingnonlinearities.
{{< /details >}}

[**Stylized Adversarial Defense**](http://arxiv.org/abs/2007.14672v2)

*Muzammal Naseer, Salman Khan, Munawar Hayat, Fahad Shahbaz Khan, Fatih Porikli*

{{< details "abstract" >}} abstract: Deep Convolution Neural Networks (CNNs) can easily be fooled by subtle,imperceptible changes to the input images. To address this vulnerability,adversarial training creates perturbation patterns and includes them in thetraining set to robustify the model. In contrast to existing adversarialtraining methods that only use class-boundary information (e.g., using across-entropy loss), we propose to exploit additional information from thefeature space to craft stronger adversaries that are in turn used to learn arobust model. Specifically, we use the style and content information of thetarget sample from another class, alongside its class-boundary information tocreate adversarial perturbations. We apply our proposed multi-task objective ina deeply supervised manner, extracting multi-scale feature knowledge to createmaximally separating adversaries. Subsequently, we propose a max-marginadversarial training approach that minimizes the distance between source imageand its adversary and maximizes the distance between the adversary and thetarget image. Our adversarial training approach demonstrates strong robustnesscompared to state-of-the-art defenses, generalizes well to naturally occurringcorruptions and data distributional shifts, and retains the model accuracy onclean examples.
{{< /details >}}

>**_2022-09-14_**

[**Collaborative SQL-injections detection system with machine learning**](http://arxiv.org/abs/2209.06553v1)

*M Lodeiro-Santiago, C Caballero-Gil, P Caballero-Gil*

{{< details "abstract" >}} abstract: Data mining and information extraction from data is a field that has gainedrelevance in recent years thanks to techniques based on artificial intelligenceand use of machine and deep learning. The main aim of the present work is thedevelopment of a tool based on a previous behaviour study of security audittools (oriented to SQL pentesting) with the purpose of creating testing setscapable of performing an accurate detection of a SQL attack. The study is basedon the information collected through the generated web server logs in apentesting laboratory environment. Then, making use of the common extractedpatterns from the logs, each attack vector has been classified in risk levels(dangerous attack, normal attack, non-attack, etc.). Finally, a training withthe generated data was performed in order to obtain a classifier system thathas a variable performance between 97 and 99 percent in positive attackdetection. The training data is shared to other servers in order to create adistributed network capable of deciding if a query is an attack or is a realpetition and inform to connected clients in order to block the petitions fromthe attacker's IP.
{{< /details >}}

>**_2022-09-08_**

[**Simpler is better: Multilevel Abstraction with Graph Convolutional Recurrent Neural Network Cells for Traffic Prediction**](http://arxiv.org/abs/2209.03858v1)

*Naghmeh Shafiee Roudbari, Zachary Patterson, Ursula Eicker, Charalambos Poullis*

{{< details "abstract" >}} abstract: In recent years, graph neural networks (GNNs) combined with variants ofrecurrent neural networks (RNNs) have reached state-of-the-art performance inspatiotemporal forecasting tasks. This is particularly the case for trafficforecasting, where GNN models use the graph structure of road networks toaccount for spatial correlation between links and nodes. Recent solutions areeither based on complex graph operations or avoiding predefined graphs. Thispaper proposes a new sequence-to-sequence architecture to extract thespatiotemporal correlation at multiple levels of abstraction using GNN-RNNcells with sparse architecture to decrease training time compared to morecomplex designs. Encoding the same input sequence through multiple encoders,with an incremental increase in encoder layers, enables the network to learngeneral and detailed information through multilevel abstraction. We furtherpresent a new benchmark dataset of street-level segment traffic data fromMontreal, Canada. Unlike highways, urban road segments are cyclic andcharacterized by complicated spatial dependencies. Experimental results on theMETR-LA benchmark highway and our MSLTD street-level segment datasetsdemonstrate that our model improves performance by more than 7% for one-hourprediction compared to the baseline methods while reducing computing resourcerequirements by more than half compared to other competing methods.
{{< /details >}}

>**_2022-09-07_**

[**Supervised GAN Watermarking for Intellectual Property Protection**](http://arxiv.org/abs/2209.03466v1)

*Jianwei Fei, Zhihua Xia, Benedetta Tondi, Mauro Barni*

{{< details "abstract" >}} abstract: We propose a watermarking method for protecting the Intellectual Property(IP) of Generative Adversarial Networks (GANs). The aim is to watermark the GANmodel so that any image generated by the GAN contains an invisible watermark(signature), whose presence inside the image can be checked at a later stagefor ownership verification. To achieve this goal, a pre-trained CNNwatermarking decoding block is inserted at the output of the generator. Thegenerator loss is then modified by including a watermark loss term, to ensurethat the prescribed watermark can be extracted from the generated images. Thewatermark is embedded via fine-tuning, with reduced time complexity. Resultsshow that our method can effectively embed an invisible watermark inside thegenerated images. Moreover, our method is a general one and can work withdifferent GAN architectures, different tasks, and different resolutions of theoutput image. We also demonstrate the good robustness performance of theembedded watermark against several post-processing, among them, JPEGcompression, noise addition, blurring, and color transformations.
{{< /details >}}

>**_2022-09-04_**

[**Symplectically Integrated Symbolic Regression of Hamiltonian Dynamical Systems**](http://arxiv.org/abs/2209.01521v1)

*Daniel M. DiPietro, Bo Zhu*

{{< details "abstract" >}} abstract: Here we present Symplectically Integrated Symbolic Regression (SISR), a noveltechnique for learning physical governing equations from data. SISR employs adeep symbolic regression approach, using a multi-layer LSTM-RNN with mutationto probabilistically sample Hamiltonian symbolic expressions. Using symplecticneural networks, we develop a model-agnostic approach for extracting meaningfulphysical priors from the data that can be imposed on-the-fly into the RNNoutput, limiting its search space. Hamiltonians generated by the RNN areoptimized and assessed using a fourth-order symplectic integration scheme;prediction performance is used to train the LSTM-RNN to generate increasinglybetter functions via a risk-seeking policy gradients approach. Employing thesetechniques, we extract correct governing equations from oscillator, pendulum,two-body, and three-body gravitational systems with noisy and extremely smalldatasets.
{{< /details >}}

>**_2022-08-30_**

[**Solving the Capsulation Attack against Backdoor-based Deep Neural Network Watermarks by Reversing Triggers**](http://arxiv.org/abs/2208.14127v1)

*Fangqi Li, Shilin Wang, Yun Zhu*

{{< details "abstract" >}} abstract: Backdoor-based watermarking schemes were proposed to protect the intellectualproperty of artificial intelligence models, especially deep neural networks,under the black-box setting. Compared with ordinary backdoors, backdoor-basedwatermarks need to digitally incorporate the owner's identity, which fact addsextra requirements to the trigger generation and verification programs.Moreover, these concerns produce additional security risks after thewatermarking scheme has been published for as a forensics tool or the owner'sevidence has been eavesdropped on. This paper proposes the capsulation attack,an efficient method that can invalidate most established backdoor-basedwatermarking schemes without sacrificing the pirated model's functionality. Byencapsulating the deep neural network with a rule-based or Bayes filter, anadversary can block ownership probing and reject the ownership verification. Wepropose a metric, CAScore, to measure a backdoor-based watermarking scheme'ssecurity against the capsulation attack. This paper also proposes a newbackdoor-based deep neural network watermarking scheme that is secure againstthe capsulation attack by reversing the encoding process and randomizing theexposure of triggers.
{{< /details >}}

[**A deep learning-based remaining useful life prediction approach for bearings**](http://arxiv.org/abs/1812.03315v2)

*Cheng Cheng, Guijun Ma, Yong Zhang, Mingyang Sun, Fei Teng, Han Ding, Ye Yuan*

{{< details "abstract" >}} abstract: In industrial applications, nearly half the failures of motors are caused bythe degradation of rolling element bearings (REBs). Therefore, accuratelyestimating the remaining useful life (RUL) for REBs are of crucial importanceto ensure the reliability and safety of mechanical systems. To tackle thischallenge, model-based approaches are often limited by the complexity ofmathematical modeling. Conventional data-driven approaches, on the other hand,require massive efforts to extract the degradation features and constructhealth index. In this paper, a novel online data-driven framework is proposedto exploit the adoption of deep convolutional neural networks (CNN) inpredicting the RUL of bearings. More concretely, the raw vibrations of trainingbearings are first processed using the Hilbert-Huang transform (HHT) and anovel nonlinear degradation indicator is constructed as the label for learning.The CNN is then employed to identify the hidden pattern between the extracteddegradation indicator and the vibration of training bearings, which makes itpossible to estimate the degradation of the test bearings automatically.Finally, testing bearings' RULs are predicted by using a $\epsilon$-supportvector regression model. The superior performance of the proposed RULestimation framework, compared with the state-of-the-art approaches, isdemonstrated through the experimental results. The generality of the proposedCNN model is also validated by transferring to bearings undergoing differentoperating conditions.
{{< /details >}}

>**_2022-08-25_**

[**Semantic Preserving Adversarial Attack Generation with Autoencoder and Genetic Algorithm**](http://arxiv.org/abs/2208.12230v1)

*Xinyi Wang, Simon Yusuf Enoch, Dong Seong Kim*

{{< details "abstract" >}} abstract: Widely used deep learning models are found to have poor robustness. Littlenoises can fool state-of-the-art models into making incorrect predictions.While there is a great deal of high-performance attack generation methods, mostof them directly add perturbations to original data and measure them using L_pnorms; this can break the major structure of data, thus, creating invalidattacks. In this paper, we propose a black-box attack, which, instead ofmodifying original data, modifies latent features of data extracted by anautoencoder; then, we measure noises in semantic space to protect the semanticsof data. We trained autoencoders on MNIST and CIFAR-10 datasets and foundoptimal adversarial perturbations using a genetic algorithm. Our approachachieved a 100% attack success rate on the first 100 data of MNIST and CIFAR-10datasets with less perturbation than FGSM.
{{< /details >}}

>**_2022-08-21_**

[**MentorGNN: Deriving Curriculum for Pre-Training GNNs**](http://arxiv.org/abs/2208.09905v1)

*Dawei Zhou, Lecheng Zheng, Dongqi Fu, Jiawei Han, Jingrui He*

{{< details "abstract" >}} abstract: Graph pre-training strategies have been attracting a surge of attention inthe graph mining community, due to their flexibility in parameterizing graphneural networks (GNNs) without any label information. The key idea lies inencoding valuable information into the backbone GNNs, by predicting the maskedgraph signals extracted from the input graphs. In order to balance theimportance of diverse graph signals (e.g., nodes, edges, subgraphs), theexisting approaches are mostly hand-engineered by introducing hyperparametersto re-weight the importance of graph signals. However, human interventions withsub-optimal hyperparameters often inject additional bias and deteriorate thegeneralization performance in the downstream applications. This paper addressesthese limitations from a new perspective, i.e., deriving curriculum forpre-training GNNs. We propose an end-to-end model named MentorGNN that aims tosupervise the pre-training process of GNNs across graphs with diversestructures and disparate feature spaces. To comprehend heterogeneous graphsignals at different granularities, we propose a curriculum learning paradigmthat automatically re-weighs graph signals in order to ensure a goodgeneralization in the target domain. Moreover, we shed new light on the problemof domain adaption on relational data (i.e., graphs) by deriving a natural andinterpretable upper bound on the generalization error of the pre-trained GNNs.Extensive experiments on a wealth of real graphs validate and verify theperformance of MentorGNN.
{{< /details >}}

>**_2022-08-17_**

[**Data-Efficient Vision Transformers for Multi-Label Disease Classification on Chest Radiographs**](http://arxiv.org/abs/2208.08166v1)

*Finn Behrendt, Debayan Bhattacharya, Julia Krüger, Roland Opfer, Alexander Schlaefer*

{{< details "abstract" >}} abstract: Radiographs are a versatile diagnostic tool for the detection and assessmentof pathologies, for treatment planning or for navigation and localizationpurposes in clinical interventions. However, their interpretation andassessment by radiologists can be tedious and error-prone. Thus, a wide varietyof deep learning methods have been proposed to support radiologistsinterpreting radiographs. Mostly, these approaches rely on convolutional neuralnetworks (CNN) to extract features from images. Especially for the multi-labelclassification of pathologies on chest radiographs (Chest X-Rays, CXR), CNNshave proven to be well suited. On the Contrary, Vision Transformers (ViTs) havenot been applied to this task despite their high classification performance ongeneric images and interpretable local saliency maps which could add value toclinical interventions. ViTs do not rely on convolutions but on patch-basedself-attention and in contrast to CNNs, no prior knowledge of localconnectivity is present. While this leads to increased capacity, ViTs typicallyrequire an excessive amount of training data which represents a hurdle in themedical domain as high costs are associated with collecting large medical datasets. In this work, we systematically compare the classification performance ofViTs and CNNs for different data set sizes and evaluate more data-efficient ViTvariants (DeiT). Our results show that while the performance between ViTs andCNNs is on par with a small benefit for ViTs, DeiTs outperform the former if areasonably large data set is available for training.
{{< /details >}}

>**_2022-08-13_**

[**ACSGRegNet: A Deep Learning-based Framework for Unsupervised Joint Affine and Diffeomorphic Registration of Lumbar Spine CT via Cross- and Self-Attention Fusion**](http://arxiv.org/abs/2208.02642v2)

*Xiaoru Gao, GuoYan Zheng*

{{< details "abstract" >}} abstract: Registration plays an important role in medical image analysis. Deeplearning-based methods have been studied for medical image registration, whichleverage convolutional neural networks (CNNs) for efficiently regressing adense deformation field from a pair of images. However, CNNs are limited in itsability to extract semantically meaningful intra- and inter-image spatialcorrespondences, which are of importance for accurate image registration. Thisstudy proposes a novel end-to-end deep learning-based framework forunsupervised affine and diffeomorphic deformable registration, referred asACSGRegNet, which integrates a cross-attention module for establishinginter-image feature correspondences and a self-attention module for intra-imageanatomical structures aware. Both attention modules are built on transformerencoders. The output from each attention module is respectively fed to adecoder to generate a velocity field. We further introduce a gated fusionmodule to fuse both velocity fields. The fused velocity field is thenintegrated to a dense deformation field. Extensive experiments are conducted onlumbar spine CT images. Once the model is trained, pairs of unseen lumbarvertebrae can be registered in one shot. Evaluated on 450 pairs of vertebral CTdata, our method achieved an average Dice of 0.963 and an average distanceerror of 0.321mm, which are better than the state-of-the-art (SOTA).
{{< /details >}}

>**_2022-07-15_**

[**Trainable Joint Bilateral Filters for Enhanced Prediction Stability in Low-dose CT**](http://arxiv.org/abs/2207.07368v1)

*Fabian Wagner, Mareike Thies, Felix Denzinger, Mingxuan Gu, Mayank Patwari, Stefan Ploner, Noah Maul, Laura Pfaff, Yixing Huang, Andreas Maier*

{{< details "abstract" >}} abstract: Low-dose computed tomography (CT) denoising algorithms aim to enable reducedpatient dose in routine CT acquisitions while maintaining high image quality.Recently, deep learning~(DL)-based methods were introduced, outperformingconventional denoising algorithms on this task due to their high modelcapacity. However, for the transition of DL-based denoising to clinicalpractice, these data-driven approaches must generalize robustly beyond the seentraining data. We, therefore, propose a hybrid denoising approach consisting ofa set of trainable joint bilateral filters (JBFs) combined with a convolutionalDL-based denoising network to predict the guidance image. Our proposeddenoising pipeline combines the high model capacity enabled by DL-based featureextraction with the reliability of the conventional JBF. The pipeline's abilityto generalize is demonstrated by training on abdomen CT scans without metalimplants and testing on abdomen scans with metal implants as well as on head CTdata. When embedding two well-established DL-based denoisers (RED-CNN/QAE) inour pipeline, the denoising performance is improved by $10\,\%$/$82\,\%$ (RMSE)and $3\,\%$/$81\,\%$ (PSNR) in regions containing metal and by $6\,\%$/$78\,\%$(RMSE) and $2\,\%$/$4\,\%$ (PSNR) on head CT data, compared to the respectivevanilla model. Concluding, the proposed trainable JBFs limit the error bound ofdeep neural networks to facilitate the applicability of DL-based denoisers inlow-dose CT pipelines.
{{< /details >}}

>**_2022-07-05_**

[**Disentangling private classes through regularization**](http://arxiv.org/abs/2207.02000v1)

*Enzo Tartaglione, Francesca Gennari, Marco Grangetto*

{{< details "abstract" >}} abstract: Deep learning models are nowadays broadly deployed to solve an incrediblylarge variety of tasks. However, little attention has been devoted to connectedlegal aspects. In 2016, the European Union approved the General Data ProtectionRegulation which entered into force in 2018. Its main rationale was to protectthe privacy and data protection of its citizens by the way of operating of theso-called "Data Economy". As data is the fuel of modern ArtificialIntelligence, it is argued that the GDPR can be partly applicable to a seriesof algorithmic decision making tasks before a more structured AI Regulationenters into force. In the meantime, AI should not allow undesired informationleakage deviating from the purpose for which is created. In this work wepropose DisP, an approach for deep learning models disentangling theinformation related to some classes we desire to keep private, from the dataprocessed by AI. In particular, DisP is a regularization strategyde-correlating the features belonging to the same private class at trainingtime, hiding the information of private classes membership. Our experiments onstate-of-the-art deep learning models show the effectiveness of DisP,minimizing the risk of extraction for the classes we desire to keep private.
{{< /details >}}

>**_2022-06-28_**

[**NegDL: Privacy-Preserving Deep Learning Based on Negative Database**](http://arxiv.org/abs/2103.05854v5)

*Dongdong Zhao, Pingchuan Zhang, Jianwen Xiang, Jing Tian*

{{< details "abstract" >}} abstract: In the era of big data, deep learning has become an increasingly populartopic. It has outstanding achievements in the fields of image recognition,object detection, and natural language processing et al. The first priority ofdeep learning is exploiting valuable information from a large amount of data,which will inevitably induce privacy issues that are worthy of attention.Presently, several privacy-preserving deep learning methods have been proposed,but most of them suffer from a non-negligible degradation of either efficiencyor accuracy. Negative database (\textit{NDB}) is a new type of datarepresentation which can protect data privacy by storing and utilizing thecomplementary form of original data. In this paper, we propose aprivacy-preserving deep learning method named NegDL based on \textit{NDB}.Specifically, private data are first converted to \textit{NDB} as the input ofdeep learning models by a generation algorithm called \textit{QK}-hiddenalgorithm, and then the sketches of \textit{NDB} are extracted for training andinference. We demonstrate that the computational complexity of NegDL is thesame as the original deep learning model without privacy protection.Experimental results on Breast Cancer, MNIST, and CIFAR-10 benchmark datasetsdemonstrate that the accuracy of NegDL could be comparable to the original deeplearning model in most cases, and it performs better than the method based ondifferential privacy.
{{< /details >}}

>**_2022-06-19_**

[**Towards Continual, Online, Self-Supervised Depth**](http://arxiv.org/abs/2103.00369v3)

*Muhammad Umar Karim Khan*

{{< details "abstract" >}} abstract: Although depth extraction with passive sensors has seen remarkableimprovement with deep learning, these approaches may fail to obtain correctdepth if they are exposed to environments not observed during training. Onlineadaptation, where the neural network trains while deployed, withself-supervised learning provides a convenient solution as the network canlearn from the scene where it is deployed without external supervision.However, online adaptation causes a neural network to forget the past. Thus,past training is wasted and the network is not able to provide good results ifit observes past scenes. This work deals with practical online-adaptation wherethe input is online and temporally-correlated, and training is completelyself-supervised. Regularization and replay-based methods without taskboundaries are proposed to avoid catastrophic forgetting while adapting toonline data. Effort has been made to make the proposed approach suitable forpractical use. We apply our method to both structure-from-motion and stereodepth estimation. We evaluate our method on diverse public datasets thatinclude outdoor, indoor and synthetic scenes. Qualitative and quantitativeresults with both structure-from-motion and stereo show superior forgetting aswell as adaptation performance compared to recent methods. Furthermore, theproposed method incurs negligible overhead compared to fine-tuning for onlineadaptation, proving to be an adequate choice in terms of plasticity, stabilityand applicability. The proposed approach is more inline with the artificialgeneral intelligence paradigm as the neural network learns continually with nosupervision. Source code is available at https://github.com/umarKarim/cou_sfmand https://github.com/umarKarim/cou_stereo.
{{< /details >}}

>**_2022-06-16_**

[**Improved Gaussian-Bernoulli Restricted Boltzmann Machines for UAV-Ground Communication Systems**](http://arxiv.org/abs/2206.08209v1)

*Osamah A. Abdullah, Michael C. Batistatos, Hayder Al-Hraishawi*

{{< details "abstract" >}} abstract: Unmanned aerial vehicle (UAV) is steadily growing as a promising technologyfor next-generation communication systems due to their appealing features suchas wide coverage with high altitude, on-demand low-cost deployment, and fastresponses. UAV communications are fundamentally different from the conventionalterrestrial and satellite communications owing to the high mobility and theunique channel characteristics of air-ground links. However, obtainingeffective channel state information (CSI) is challenging because of the dynamicpropagation environment and variable transmission delay. In this paper, a deeplearning (DL)-based CSI prediction framework is proposed to address channelaging problem by extracting the most discriminative features from the UAVwireless signals. Specifically, we develop a procedure of multiple GaussianBernoulli restricted Boltzmann machines (GBRBM) for dimension reduction andpre-training utilization incorporated with an autoencoder-based deep neuralnetworks (DNNs). To evaluate the proposed approach, real data measurements froman UAV communicating with base-stations within a commercial cellular networkare obtained and used for training and validation. Numerical resultsdemonstrate that the proposed method is accurate in channel acquisition forvarious UAV flying scenarios and outperforms the conventional DNNs.
{{< /details >}}

>**_2022-06-01_**

[**NeuroUnlock: Unlocking the Architecture of Obfuscated Deep Neural Networks**](http://arxiv.org/abs/2206.00402v1)

*Mahya Morid Ahmadi, Lilas Alrahis, Alessio Colucci, Ozgur Sinanoglu, Muhammad Shafique*

{{< details "abstract" >}} abstract: The advancements of deep neural networks (DNNs) have led to their deploymentin diverse settings, including safety and security-critical applications. As aresult, the characteristics of these models have become sensitive intellectualproperties that require protection from malicious users. Extracting thearchitecture of a DNN through leaky side-channels (e.g., memory access) allowsadversaries to (i) clone the model, and (ii) craft adversarial attacks. DNNobfuscation thwarts side-channel-based architecture stealing (SCAS) attacks byaltering the run-time traces of a given DNN while preserving its functionality.In this work, we expose the vulnerability of state-of-the-art DNN obfuscationmethods to these attacks. We present NeuroUnlock, a novel SCAS attack againstobfuscated DNNs. Our NeuroUnlock employs a sequence-to-sequence model thatlearns the obfuscation procedure and automatically reverts it, therebyrecovering the original DNN architecture. We demonstrate the effectiveness ofNeuroUnlock by recovering the architecture of 200 randomly generated andobfuscated DNNs running on the Nvidia RTX 2080 TI graphics processing unit(GPU). Moreover, NeuroUnlock recovers the architecture of various otherobfuscated DNNs, such as the VGG-11, VGG-13, ResNet-20, and ResNet-32 networks.After recovering the architecture, NeuroUnlock automatically builds anear-equivalent DNN with only a 1.4% drop in the testing accuracy. We furthershow that launching a subsequent adversarial attack on the recovered DNNsboosts the success rate of the adversarial attack by 51.7% in average comparedto launching it on the obfuscated versions. Additionally, we propose a novelmethodology for DNN obfuscation, ReDLock, which eradicates the deterministicnature of the obfuscation and achieves 2.16X more resilience to the NeuroUnlockattack. We release the NeuroUnlock and the ReDLock as open-source frameworks.
{{< /details >}}

>**_2022-05-20_**

[**How to keep text private? A systematic review of deep learning methods for privacy-preserving natural language processing**](http://arxiv.org/abs/2205.10095v1)

*Samuel Sousa, Roman Kern*

{{< details "abstract" >}} abstract: Deep learning (DL) models for natural language processing (NLP) tasks oftenhandle private data, demanding protection against breaches and disclosures.Data protection laws, such as the European Union's General Data ProtectionRegulation (GDPR), thereby enforce the need for privacy. Although manyprivacy-preserving NLP methods have been proposed in recent years, nocategories to organize them have been introduced yet, making it hard to followthe progress of the literature. To close this gap, this article systematicallyreviews over sixty DL methods for privacy-preserving NLP published between 2016and 2020, covering theoretical foundations, privacy-enhancing technologies, andanalysis of their suitability for real-world scenarios. First, we introduce anovel taxonomy for classifying the existing methods into three categories: datasafeguarding methods, trusted methods, and verification methods. Second, wepresent an extensive summary of privacy threats, datasets for applications, andmetrics for privacy evaluation. Third, throughout the review, we describeprivacy issues in the NLP pipeline in a holistic view. Further, we discuss openchallenges in privacy-preserving NLP regarding data traceability, computationoverhead, dataset size, the prevalence of human biases in embeddings, and theprivacy-utility tradeoff. Finally, this review presents future researchdirections to guide successive research and development of privacy-preservingNLP models.
{{< /details >}}

[**Assessing Demographic Bias Transfer from Dataset to Model: A Case Study in Facial Expression Recognition**](http://arxiv.org/abs/2205.10049v1)

*Iris Dominguez-Catena, Daniel Paternain, Mikel Galar*

{{< details "abstract" >}} abstract: The increasing amount of applications of Artificial Intelligence (AI) has ledresearchers to study the social impact of these technologies and evaluate theirfairness. Unfortunately, current fairness metrics are hard to apply inmulti-class multi-demographic classification problems, such as FacialExpression Recognition (FER). We propose a new set of metrics to approach theseproblems. Of the three metrics proposed, two focus on the representational andstereotypical bias of the dataset, and the third one on the residual bias ofthe trained model. These metrics combined can potentially be used to study andcompare diverse bias mitigation methods. We demonstrate the usefulness of themetrics by applying them to a FER problem based on the popular Affectnetdataset. Like many other datasets for FER, Affectnet is a largeInternet-sourced dataset with 291,651 labeled images. Obtaining images from theInternet raises some concerns over the fairness of any system trained on thisdata and its ability to generalize properly to diverse populations. We firstanalyze the dataset and some variants, finding substantial racial bias andgender stereotypes. We then extract several subsets with different demographicproperties and train a model on each one, observing the amount of residual biasin the different setups. We also provide a second analysis on a differentdataset, FER+.
{{< /details >}}

>**_2022-05-17_**

[**Learning Meta Pattern for Face Anti-Spoofing**](http://arxiv.org/abs/2110.06753v2)

*Rizhao Cai, Zhi Li, Renjie Wan, Haoliang Li, Yongjian Hu, Alex Chichung Kot*

{{< details "abstract" >}} abstract: Face Anti-Spoofing (FAS) is essential to secure face recognition systems andhas been extensively studied in recent years. Although deep neural networks(DNNs) for the FAS task have achieved promising results in intra-datasetexperiments with similar distributions of training and testing data, the DNNs'generalization ability is limited under the cross-domain scenarios withdifferent distributions of training and testing data. To improve thegeneralization ability, recent hybrid methods have been explored to extracttask-aware handcrafted features (e.g., Local Binary Pattern) as discriminativeinformation for the input of DNNs. However, the handcrafted feature extractionrelies on experts' domain knowledge, and how to choose appropriate handcraftedfeatures is underexplored. To this end, we propose a learnable network toextract Meta Pattern (MP) in our learning-to-learn framework. By replacinghandcrafted features with the MP, the discriminative information from MP iscapable of learning a more generalized model. Moreover, we devise a two-streamnetwork to hierarchically fuse the input RGB image and the extracted MP byusing our proposed Hierarchical Fusion Module (HFM). We conduct comprehensiveexperiments and show that our MP outperforms the compared handcrafted features.Also, our proposed method with HFM and the MP can achieve state-of-the-artperformance on two different domain generalization evaluation benchmarks.
{{< /details >}}

[**Semi-Supervised Building Footprint Generation with Feature and Output Consistency Training**](http://arxiv.org/abs/2205.08416v1)

*Qingyu Li, Yilei Shi, Xiao Xiang Zhu*

{{< details "abstract" >}} abstract: Accurate and reliable building footprint maps are vital to urban planning andmonitoring, and most existing approaches fall back on convolutional neuralnetworks (CNNs) for building footprint generation. However, one limitation ofthese methods is that they require strong supervisory information from massiveannotated samples for network learning. State-of-the-art semi-supervisedsemantic segmentation networks with consistency training can help to deal withthis issue by leveraging a large amount of unlabeled data, which encourages theconsistency of model output on data perturbation. Considering that richinformation is also encoded in feature maps, we propose to integrate theconsistency of both features and outputs in the end-to-end network training ofunlabeled samples, enabling to impose additional constraints. Priorsemi-supervised semantic segmentation networks have established the clusterassumption, in which the decision boundary should lie in the vicinity of lowsample density. In this work, we observe that for building footprintgeneration, the low-density regions are more apparent at the intermediatefeature representations within the encoder than the encoder's input or output.Therefore, we propose an instruction to assign the perturbation to theintermediate feature representations within the encoder, which considers thespatial resolution of input remote sensing imagery and the mean size ofindividual buildings in the study area. The proposed method is evaluated onthree datasets with different resolutions: Planet dataset (3 m/pixel),Massachusetts dataset (1 m/pixel), and Inria dataset (0.3 m/pixel).Experimental results show that the proposed approach can well extract morecomplete building structures and alleviate omission errors.
{{< /details >}}

>**_2022-05-16_**

[**Prioritizing Corners in OoD Detectors via Symbolic String Manipulation**](http://arxiv.org/abs/2205.07736v1)

*Chih-Hong Cheng, Changshun Wu, Emmanouil Seferis, Saddek Bensalem*

{{< details "abstract" >}} abstract: For safety assurance of deep neural networks (DNNs), out-of-distribution(OoD) monitoring techniques are essential as they filter spurious input that isdistant from the training dataset. This paper studies the problem ofsystematically testing OoD monitors to avoid cases where an input data point istested as in-distribution by the monitor, but the DNN produces spurious outputpredictions. We consider the definition of "in-distribution" characterized inthe feature space by a union of hyperrectangles learned from the trainingdataset. Thus the testing is reduced to finding corners in hyperrectanglesdistant from the available training data in the feature space. Concretely, weencode the abstract location of every data point as a finite-length binarystring, and the union of all binary strings is stored compactly using binarydecision diagrams (BDDs). We demonstrate how to use BDDs to symbolicallyextract corners distant from all data points within the training set. Apartfrom test case generation, we explain how to use the proposed corners tofine-tune the DNN to ensure that it does not predict overly confidently. Theresult is evaluated over examples such as number and traffic sign recognition.
{{< /details >}}

>**_2022-05-01_**

[**Thermodynamically Consistent Machine-Learned Internal State Variable Approach for Data-Driven Modeling of Path-Dependent Materials**](http://arxiv.org/abs/2205.00578v1)

*Xiaolong He, Jiun-Shyan Chen*

{{< details "abstract" >}} abstract: Characterization and modeling of path-dependent behaviors of complexmaterials by phenomenological models remains challenging due to difficulties informulating mathematical expressions and internal state variables (ISVs)governing path-dependent behaviors. Data-driven machine learning models, suchas deep neural networks and recurrent neural networks (RNNs), have becomeviable alternatives. However, pure black-box data-driven models mapping inputsto outputs without considering the underlying physics suffer from unstable andinaccurate generalization performance. This study proposes a machine-learnedphysics-informed data-driven constitutive modeling approach for path-dependentmaterials based on the measurable material states. The proposed data-drivenconstitutive model is designed with the consideration of universalthermodynamics principles, where the ISVs essential to the materialpath-dependency are inferred automatically from the hidden state of RNNs. TheRNN describing the evolution of the data-driven machine-learned ISVs followsthe thermodynamics second law. To enhance the robustness and accuracy of RNNmodels, stochasticity is introduced to model training. The effects of thenumber of RNN history steps, the internal state dimension, the modelcomplexity, and the strain increment on model performances have beeninvestigated. The effectiveness of the proposed method is evaluated by modelingsoil material behaviors under cyclic shear loading using experimentalstress-strain data.
{{< /details >}}

>**_2022-04-26_**

[**You Don't Know My Favorite Color: Preventing Dialogue Representations from Revealing Speakers' Private Personas**](http://arxiv.org/abs/2205.10228v1)

*Haoran Li, Yangqiu Song, Lixin Fan*

{{< details "abstract" >}} abstract: Social chatbots, also known as chit-chat chatbots, evolve rapidly with largepretrained language models. Despite the huge progress, privacy concerns havearisen recently: training data of large language models can be extracted viamodel inversion attacks. On the other hand, the datasets used for trainingchatbots contain many private conversations between two individuals. In thiswork, we further investigate the privacy leakage of the hidden states ofchatbots trained by language modeling which has not been well studied yet. Weshow that speakers' personas can be inferred through a simple neural networkwith high accuracy. To this end, we propose effective defense objectives toprotect persona leakage from hidden states. We conduct extensive experiments todemonstrate that our proposed defense objectives can greatly reduce the attackaccuracy from 37.6% to 0.5%. Meanwhile, the proposed objectives preservelanguage models' powerful generation ability.
{{< /details >}}

[**Brain Tumor Detection and Classification Using a New Evolutionary Convolutional Neural Network**](http://arxiv.org/abs/2204.12297v1)

*Amin Abdollahi Dehkordi, Mina Hashemi, Mehdi Neshat, Seyedali Mirjalili, Ali Safaa Sadiq*

{{< details "abstract" >}} abstract: A definitive diagnosis of a brain tumour is essential for enhancing treatmentsuccess and patient survival. However, it is difficult to manually evaluatemultiple magnetic resonance imaging (MRI) images generated in a clinic.Therefore, more precise computer-based tumour detection methods are required.In recent years, many efforts have investigated classical machine learningmethods to automate this process. Deep learning techniques have recentlysparked interest as a means of diagnosing brain tumours more accurately androbustly. The goal of this study, therefore, is to employ brain MRI images todistinguish between healthy and unhealthy patients (including tumour tissues).As a result, an enhanced convolutional neural network is developed in thispaper for accurate brain image classification. The enhanced convolutionalneural network structure is composed of components for feature extraction andoptimal classification. Nonlinear L\'evy Chaotic Moth Flame Optimizer (NLCMFO)optimizes hyperparameters for training convolutional neural network layers.Using the BRATS 2015 data set and brain image datasets from Harvard MedicalSchool, the proposed model is assessed and compared with various optimizationtechniques. The optimized CNN model outperforms other models from theliterature by providing 97.4% accuracy, 96.0% sensitivity, 98.6% specificity,98.4% precision, and 96.6% F1-score, (the mean of the weighted harmonic valueof CNN precision and recall).
{{< /details >}}

>**_2022-04-21_**

[**Multi-task recommendation system for scientific papers with high-way networks**](http://arxiv.org/abs/2204.09930v1)

*Aram Karimi, Simon Dobnik*

{{< details "abstract" >}} abstract: Finding and selecting the most relevant scientific papers from a large numberof papers written in a research community is one of the key challenges forresearchers these days. As we know, much information around research interestfor scholars and academicians belongs to papers they read. Analysis andextracting contextual features from these papers could help us to suggest themost related paper to them. In this paper, we present a multi-taskrecommendation system (RS) that predicts a paper recommendation and generatesits meta-data such as keywords. The system is implemented as a three-stage deepneural network encoder that tries to maps longer sequences of text to anembedding vector and learns simultaneously to predict the recommendation ratefor a particular user and the paper's keywords. The motivation behind thisapproach is that the paper's topics expressed as keywords are a usefulpredictor of preferences of researchers. To achieve this goal, we use a systemcombination of RNNs, Highway and Convolutional Neural Networks to trainend-to-end a context-aware collaborative matrix. Our application uses Highwaynetworks to train the system very deep, combine the benefits of RNN and CNN tofind the most important factor and make latent representation. Highway Networksallow us to enhance the traditional RNN and CNN pipeline by learning moresophisticated semantic structural representations. Using this method we canalso overcome the cold start problem and learn latent features over largesequences of text.
{{< /details >}}

>**_2022-04-20_**

[**NetSentry: A Deep Learning Approach to Detecting Incipient Large-scale Network Attacks**](http://arxiv.org/abs/2202.09873v2)

*Haoyu Liu, Paul Patras*

{{< details "abstract" >}} abstract: Machine Learning (ML) techniques are increasingly adopted to tackleever-evolving high-profile network attacks, including DDoS, botnet, andransomware, due to their unique ability to extract complex patterns hidden indata streams. These approaches are however routinely validated with datacollected in the same environment, and their performance degrades when deployedin different network topologies and/or applied on previously unseen traffic, aswe uncover. This suggests malicious/benign behaviors are largely learnedsuperficially and ML-based Network Intrusion Detection System (NIDS) needrevisiting, to be effective in practice. In this paper we dive into themechanics of large-scale network attacks, with a view to understanding how touse ML for Network Intrusion Detection (NID) in a principled way. We revealthat, although cyberattacks vary significantly in terms of payloads, vectorsand targets, their early stages, which are critical to successful attackoutcomes, share many similarities and exhibit important temporal correlations.Therefore, we treat NID as a time-sensitive task and propose NetSentry, perhapsthe first of its kind NIDS that builds on Bidirectional Asymmetric LSTM(Bi-ALSTM), an original ensemble of sequential neural models, to detect networkthreats before they spread. We cross-evaluate NetSentry using two practicaldatasets, training on one and testing on the other, and demonstrate F1 scoregains above 33% over the state-of-the-art, as well as up to 3 times higherrates of detecting attacks such as XSS and web bruteforce. Further, we putforward a novel data augmentation technique that boosts the generalizationabilities of a broad range of supervised deep learning algorithms, leading toaverage F1 score gains above 35%.
{{< /details >}}

>**_2022-04-19_**

[**Seculator: A Fast and Secure Neural Processing Unit**](http://arxiv.org/abs/2204.08951v1)

*Nivedita Shrivastava, Smruti R. Sarangi*

{{< details "abstract" >}} abstract: Securing deep neural networks (DNNs) is a problem of significant interestsince an ML model incorporates high-quality intellectual property, features ofdata sets painstakingly collated by mechanical turks, and novel methods oftraining on large cluster computers. Sadly, attacks to extract model parametersare on the rise, and thus designers are being forced to create architecturesfor securing such models. State-of-the-art proposals in this field take thedeterministic memory access patterns of such networks into cognizance (albeitpartially), group a set of memory blocks into a tile, and maintain state at thelevel of tiles (to reduce storage space). For providing integrity guarantees(tamper avoidance), they don't propose any significant optimizations, and stillmaintain block-level state.  We observe that it is possible to exploit the deterministic memory accesspatterns of DNNs even further, and maintain state information for only thecurrent tile and current layer, which may comprise a large number of tiles.This reduces the storage space, reduces the number of memory accesses,increases performance, and simplifies the design without sacrificing anysecurity guarantees. The key techniques in our proposed acceleratorarchitecture, Seculator, are to encode memory access patterns to create a smallHW-based tile version number generator for a given layer, and to storelayer-level MACs. We completely eliminate the need for having a MAC cache and atile version number store (as used in related work). We show that usingintelligently-designed mathematical operations, these structures are notrequired. By reducing such overheads, we show a speedup of 16% over the closestcompeting work.
{{< /details >}}

>**_2022-04-11_**

[**A Generative Language Model for Few-shot Aspect-Based Sentiment Analysis**](http://arxiv.org/abs/2204.05356v1)

*Ehsan Hosseini-Asl, Wenhao Liu, Caiming Xiong*

{{< details "abstract" >}} abstract: Sentiment analysis is an important task in natural language processing. Inrecent works, pre-trained language models are often used to achievestate-of-the-art results, especially when training data is scarce. It is commonto fine-tune on the downstream task, usually by adding task-specific layers ontop of the model. In this paper, we focus on aspect-based sentiment analysis,which involves extracting aspect term, category, and predicting theircorresponding polarities. In particular, we are interested in few-shotsettings. We propose to reformulate the extraction and prediction tasks intothe sequence generation task, using a generative language model withunidirectional attention (GPT2 is used unless stated otherwise). This way, themodel learns to accomplish the tasks via language generation without the needof training task-specific layers. Our evaluation results on the single-taskpolarity prediction show that our approach outperforms the previousstate-of-the-art (based on BERT) on average performance by a large margins infew-shot and full-shot settings. More importantly, our generative approachsignificantly reduces the model variance caused by low-resource data. Wefurther demonstrate that the proposed generative language model can handlejoint and multi-task settings, unlike previous work. We observe that theproposed sequence generation method achieves further improved performances onpolarity prediction when the model is trained via joint and multi-tasksettings. Further evaluation on similar sentiment analysis datasets, SST-2,SST- and OOS intent detection validates the superiority and noise robustness ofgenerative language model in few-shot settings.
{{< /details >}}

>**_2022-04-09_**

[**Knowledge-Free Black-Box Watermark and Ownership Proof for Image Classification Neural Networks**](http://arxiv.org/abs/2204.04522v1)

*Fangqi Li, Shilin Wang*

{{< details "abstract" >}} abstract: Watermarking has become a plausible candidate for ownership verification andintellectual property protection of deep neural networks. Regarding imageclassification neural networks, current watermarking schemes uniformly resortto backdoor triggers. However, injecting a backdoor into a neural networkrequires knowledge of the training dataset, which is usually unavailable in thereal-world commercialization. Meanwhile, established watermarking schemesoversight the potential damage of exposed evidence during ownershipverification and the watermarking algorithms themselves. Those concerns declinecurrent watermarking schemes from industrial applications. To confront thesechallenges, we propose a knowledge-free black-box watermarking scheme for imageclassification neural networks. The image generator obtained from a data-freedistillation process is leveraged to stabilize the network's performance duringthe backdoor injection. A delicate encoding and verification protocol isdesigned to ensure the scheme's security against knowledgable adversaries. Wealso give a pioneering analysis of the capacity of the watermarking scheme.Experiment results proved the functionality-preserving capability and securityof the proposed watermarking scheme.
{{< /details >}}

>**_2022-04-06_**

[**Explainable Natural Language Processing with Matrix Product States**](http://arxiv.org/abs/2112.08628v2)

*Jirawat Tangpanitanon, Chanatip Mangkang, Pradeep Bhadola, Yuichiro Minato, Dimitris G. Angelakis, Thiparat Chotibut*

{{< details "abstract" >}} abstract: Despite empirical successes of recurrent neural networks (RNNs) in naturallanguage processing (NLP), theoretical understanding of RNNs is still limiteddue to intrinsically complex non-linear computations. We systematically analyzeRNNs' behaviors in a ubiquitous NLP task, the sentiment analysis of moviereviews, via the mapping between a class of RNNs called recurrent arithmeticcircuits (RACs) and a matrix product state (MPS). Using the von-Neumannentanglement entropy (EE) as a proxy for information propagation, we show thatsingle-layer RACs possess a maximum information propagation capacity, reflectedby the saturation of the EE. Enlarging the bond dimension beyond the EEsaturation threshold does not increase model prediction accuracies, so aminimal model that best estimates the data statistics can be inferred. Althoughthe saturated EE is smaller than the maximum EE allowed by the area law, ourminimal model still achieves ~99% training accuracies in realistic sentimentanalysis data sets. Thus, low EE is not a warrant against the adoption ofsingle-layer RACs for NLP. Contrary to a common belief that long-rangeinformation propagation is the main source of RNNs' successes, we show thatsingle-layer RACs harness high expressiveness from the subtle interplay betweenthe information propagation and the word vector embeddings. Our work shedslight on the phenomenology of learning in RACs, and more generally on theexplainability of RNNs for NLP, using tools from many-body quantum physics.
{{< /details >}}

>**_2022-03-27_**

[**Leveraging Pre-trained BERT for Audio Captioning**](http://arxiv.org/abs/2203.02838v2)

*Xubo Liu, Xinhao Mei, Qiushi Huang, Jianyuan Sun, Jinzheng Zhao, Haohe Liu, Mark D. Plumbley, Volkan Kılıç, Wenwu Wang*

{{< details "abstract" >}} abstract: Audio captioning aims at using natural language to describe the content of anaudio clip. Existing audio captioning systems are generally based on anencoder-decoder architecture, in which acoustic information is extracted by anaudio encoder and then a language decoder is used to generate the captions.Training an audio captioning system often encounters the problem of datascarcity. Transferring knowledge from pre-trained audio models such asPre-trained Audio Neural Networks (PANNs) have recently emerged as a usefulmethod to mitigate this issue. However, there is less attention on exploitingpre-trained language models for the decoder, compared with the encoder. BERT isa pre-trained language model that has been extensively used in Natural LanguageProcessing (NLP) tasks. Nevertheless, the potential of BERT as the languagedecoder for audio captioning has not been investigated. In this study, wedemonstrate the efficacy of the pre-trained BERT model for audio captioning.Specifically, we apply PANNs as the encoder and initialize the decoder from thepublic pre-trained BERT models. We conduct an empirical study on the use ofthese BERT models for the decoder in the audio captioning model. Our modelsachieve competitive results with the existing audio captioning methods on theAudioCaps dataset.
{{< /details >}}

>**_2022-03-25_**

[**Canary Extraction in Natural Language Understanding Models**](http://arxiv.org/abs/2203.13920v1)

*Rahil Parikh, Christophe Dupuy, Rahul Gupta*

{{< details "abstract" >}} abstract: Natural Language Understanding (NLU) models can be trained on sensitiveinformation such as phone numbers, zip-codes etc. Recent literature has focusedon Model Inversion Attacks (ModIvA) that can extract training data from modelparameters. In this work, we present a version of such an attack by extractingcanaries inserted in NLU training data. In the attack, an adversary withopen-box access to the model reconstructs the canaries contained in the model'straining set. We evaluate our approach by performing text completion oncanaries and demonstrate that by using the prefix (non-sensitive) tokens of thecanary, we can generate the full canary. As an example, our attack is able toreconstruct a four digit code in the training dataset of the NLU model with aprobability of 0.5 in its best configuration. As countermeasures, we identifyseveral defense mechanisms that, when combined, effectively eliminate the riskof ModIvA in our experiments.
{{< /details >}}

>**_2022-03-18_**

[**Are You Robert or RoBERTa? Deceiving Online Authorship Attribution Models Using Neural Text Generators**](http://arxiv.org/abs/2203.09813v1)

*Keenan Jones, Jason R. C. Nurse, Shujun Li*

{{< details "abstract" >}} abstract: Recently, there has been a rise in the development of powerful pre-trainednatural language models, including GPT-2, Grover, and XLM. These models haveshown state-of-the-art capabilities towards a variety of different NLP tasks,including question answering, content summarisation, and text generation.Alongside this, there have been many studies focused on online authorshipattribution (AA). That is, the use of models to identify the authors of onlinetexts. Given the power of natural language models in generating convincingtexts, this paper examines the degree to which these language models cangenerate texts capable of deceiving online AA models. Experimenting with bothblog and Twitter data, we utilise GPT-2 language models to generate texts usingthe existing posts of online users. We then examine whether these AI-based textgenerators are capable of mimicking authorial style to such a degree that theycan deceive typical AA models. From this, we find that current AI-based textgenerators are able to successfully mimic authorship, showing capabilitiestowards this on both datasets. Our findings, in turn, highlight the currentcapacity of powerful natural language models to generate original online postscapable of mimicking authorial style sufficiently to deceive popular AAmethods; a key finding given the proposed role of AA in real world applicationssuch as spam-detection and forensic investigation.
{{< /details >}}

>**_2022-03-16_**

[**Meta-Learning of NAS for Few-shot Learning in Medical Image Applications**](http://arxiv.org/abs/2203.08951v1)

*Viet-Khoa Vo-Ho, Kashu Yamazaki, Hieu Hoang, Minh-Triet Tran, Ngan Le*

{{< details "abstract" >}} abstract: Deep learning methods have been successful in solving tasks in machinelearning and have made breakthroughs in many sectors owing to their ability toautomatically extract features from unstructured data. However, theirperformance relies on manual trial-and-error processes for selecting anappropriate network architecture, hyperparameters for training, andpre-/post-procedures. Even though it has been shown that network architectureplays a critical role in learning feature representation feature from data andthe final performance, searching for the best network architecture iscomputationally intensive and heavily relies on researchers' experience.Automated machine learning (AutoML) and its advanced techniques i.e. NeuralArchitecture Search (NAS) have been promoted to address those limitations. Notonly in general computer vision tasks, but NAS has also motivated variousapplications in multiple areas including medical imaging. In medical imaging,NAS has significant progress in improving the accuracy of image classification,segmentation, reconstruction, and more. However, NAS requires the availabilityof large annotated data, considerable computation resources, and pre-definedtasks. To address such limitations, meta-learning has been adopted in thescenarios of few-shot learning and multiple tasks. In this book chapter, wefirst present a brief review of NAS by discussing well-known approaches insearch space, search strategy, and evaluation strategy. We then introducevarious NAS approaches in medical imaging with different applications such asclassification, segmentation, detection, reconstruction, etc. Meta-learning inNAS for few-shot learning and multiple tasks is then explained. Finally, wedescribe several open problems in NAS.
{{< /details >}}

>**_2022-03-15_**

[**Data-Efficient Graph Grammar Learning for Molecular Generation**](http://arxiv.org/abs/2203.08031v1)

*Minghao Guo, Veronika Thost, Beichen Li, Payel Das, Jie Chen, Wojciech Matusik*

{{< details "abstract" >}} abstract: The problem of molecular generation has received significant attentionrecently. Existing methods are typically based on deep neural networks andrequire training on large datasets with tens of thousands of samples. Inpractice, however, the size of class-specific chemical datasets is usuallylimited (e.g., dozens of samples) due to labor-intensive experimentation anddata collection. This presents a considerable challenge for the deep learninggenerative models to comprehensively describe the molecular design space.Another major challenge is to generate only physically synthesizable molecules.This is a non-trivial task for neural network-based generative models since therelevant chemical knowledge can only be extracted and generalized from thelimited training data. In this work, we propose a data-efficient generativemodel that can be learned from datasets with orders of magnitude smaller sizesthan common benchmarks. At the heart of this method is a learnable graphgrammar that generates molecules from a sequence of production rules. Withoutany human assistance, these production rules are automatically constructed fromtraining data. Furthermore, additional chemical knowledge can be incorporatedin the model by further grammar optimization. Our learned graph grammar yieldsstate-of-the-art results on generating high-quality molecules for three monomerdatasets that contain only ${\sim}20$ samples each. Our approach also achievesremarkable performance in a challenging polymer generation task with only $117$training samples and is competitive against existing methods using $81$k datapoints. Code is available at https://github.com/gmh14/data_efficient_grammar.
{{< /details >}}

[**Toward Improving Attentive Neural Networks in Legal Text Processing**](http://arxiv.org/abs/2203.08244v1)

*Ha-Thanh Nguyen*

{{< details "abstract" >}} abstract: In recent years, thanks to breakthroughs in neural network techniquesespecially attentive deep learning models, natural language processing has mademany impressive achievements. However, automated legal word processing is stilla difficult branch of natural language processing. Legal sentences are oftenlong and contain complicated legal terminologies. Hence, models that work wellon general documents still face challenges in dealing with legal documents. Wehave verified the existence of this problem with our experiments in this work.In this dissertation, we selectively present the main achievements in improvingattentive neural networks in automatic legal document processing. Languagemodels tend to grow larger and larger, though, without expert knowledge, thesemodels can still fail in domain adaptation, especially for specialized fieldslike law.
{{< /details >}}

>**_2022-03-13_**

[**Cold Brew: Distilling Graph Node Representations with Incomplete or Missing Neighborhoods**](http://arxiv.org/abs/2111.04840v3)

*Wenqing Zheng, Edward W Huang, Nikhil Rao, Sumeet Katariya, Zhangyang Wang, Karthik Subbian*

{{< details "abstract" >}} abstract: Graph Neural Networks (GNNs) have achieved state-of-the-art performance innode classification, regression, and recommendation tasks. GNNs work well whenrich and high-quality connections are available. However, their effectivenessis often jeopardized in many real-world graphs in which node degrees havepower-law distributions. The extreme case of this situation, where a node mayhave no neighbors, is called Strict Cold Start (SCS). SCS forces the predictionto rely completely on the node's own features. We propose Cold Brew, ateacher-student distillation approach to address the SCS and noisy-neighborchallenges for GNNs. We also introduce feature contribution ratio (FCR), ametric to quantify the behavior of inductive GNNs to solve SCS. Weexperimentally show that FCR disentangles the contributions of different graphdata components and helps select the best architecture for SCS generalization.We further demonstrate the superior performance of Cold Brew on several publicbenchmark and proprietary e-commerce datasets, where many nodes have eithervery few or noisy connections. Our source code is available athttps://github.com/amazon-research/gnn-tail-generalization.
{{< /details >}}

>**_2022-03-11_**

[**Evaluating U-net Brain Extraction for Multi-site and Longitudinal Preclinical Stroke Imaging**](http://arxiv.org/abs/2203.05716v1)

*Erendiz Tarakci, Joseph Mandeville, Fahmeed Hyder, Basavaraju G. Sanganahalli, Daniel R. Thedens, Ali Arbab, Shuning Huang, Adnan Bibic, Jelena Mihailovic, Andreia Morais, Jessica Lamb, Karisma Nagarkatti, Marcio A. Dinitz, Andre Rogatko, Arthur W. Toga, Patrick Lyden, Cenk Ayata, Ryan P. Cabeen*

{{< details "abstract" >}} abstract: Rodent stroke models are important for evaluating treatments andunderstanding the pathophysiology and behavioral changes of brain ischemia, andmagnetic resonance imaging (MRI) is a valuable tool for measuring outcome inpreclinical studies. Brain extraction is an essential first step in mostneuroimaging pipelines; however, it can be challenging in the presence ofsevere pathology and when dataset quality is highly variable. Convolutionalneural networks (CNNs) can improve accuracy and reduce operator time,facilitating high throughput preclinical studies. As part of an ongoingpreclinical stroke imaging study, we developed a deep-learning mouse brainextraction tool by using a U-net CNN. While previous studies have evaluatedU-net architectures, we sought to evaluate their practical performance acrossdata types. We ask how performance is affected with data across: six imagingcenters, two time points after experimental stroke, and across four MRIcontrasts. We trained, validated, and tested a typical U-net model on 240multimodal MRI datasets including quantitative multi-echo T2 and apparentdiffusivity coefficient (ADC) maps, and performed qualitative evaluation with alarge preclinical stroke database (N=1,368). We describe the design anddevelopment of this system, and report our findings linking datacharacteristics to segmentation performance. We consistently found highaccuracy and ability of the U-net architecture to generalize performance in arange of 95-97% accuracy, with only modest reductions in performance based onlower fidelity imaging hardware and brain pathology. This work can help informthe design of future preclinical rodent imaging studies and improve theirscalability and reliability.
{{< /details >}}

>**_2022-03-01_**

[**CLIP-GEN: Language-Free Training of a Text-to-Image Generator with CLIP**](http://arxiv.org/abs/2203.00386v1)

*Zihao Wang, Wei Liu, Qian He, Xinglong Wu, Zili Yi*

{{< details "abstract" >}} abstract: Training a text-to-image generator in the general domain (e.g., Dall.e,CogView) requires huge amounts of paired text-image data, which is tooexpensive to collect. In this paper, we propose a self-supervised scheme namedas CLIP-GEN for general text-to-image generation with the language-image priorsextracted with a pre-trained CLIP model. In our approach, we only require a setof unlabeled images in the general domain to train a text-to-image generator.Specifically, given an image without text labels, we first extract theembedding of the image in the united language-vision embedding space with theimage encoder of CLIP. Next, we convert the image into a sequence of discretetokens in the VQGAN codebook space (the VQGAN model can be trained with theunlabeled image dataset in hand). Finally, we train an autoregressivetransformer that maps the image tokens from its unified language-visionrepresentation. Once trained, the transformer can generate coherent imagetokens based on the text embedding extracted from the text encoder of CLIP uponan input text. Such a strategy enables us to train a strong and generaltext-to-image generator with large text-free image dataset such as ImageNet.Qualitative and quantitative evaluations verify that our method significantlyoutperforms optimization-based text-to-image methods in terms of image qualitywhile not compromising the text-image matching. Our method can even achievecomparable performance as flagship supervised models like CogView.
{{< /details >}}

>**_2022-02-27_**

[**Non-Transferable Learning: A New Approach for Model Ownership Verification and Applicability Authorization**](http://arxiv.org/abs/2106.06916v2)

*Lixu Wang, Shichao Xu, Ruiqi Xu, Xiao Wang, Qi Zhu*

{{< details "abstract" >}} abstract: As Artificial Intelligence as a Service gains popularity, protectingwell-trained models as intellectual property is becoming increasinglyimportant. There are two common types of protection methods: ownershipverification and usage authorization. In this paper, we proposeNon-Transferable Learning (NTL), a novel approach that captures the exclusivedata representation in the learned model and restricts the model generalizationability to certain domains. This approach provides effective solutions to bothmodel verification and authorization. Specifically: 1) For ownershipverification, watermarking techniques are commonly used but are oftenvulnerable to sophisticated watermark removal methods. By comparison, ourNTL-based ownership verification provides robust resistance to state-of-the-artwatermark removal methods, as shown in extensive experiments with 6 removalapproaches over the digits, CIFAR10 & STL10, and VisDA datasets. 2) For usageauthorization, prior solutions focus on authorizing specific users to accessthe model, but authorized users can still apply the model to any data withoutrestriction. Our NTL-based authorization approach instead provides data-centricprotection, which we call applicability authorization, by significantlydegrading the performance of the model on unauthorized data. Its effectivenessis also shown through experiments on the aforementioned datasets.
{{< /details >}}

[**Universal uncertainty estimation for nuclear detector signals with neural networks and ensemble learning**](http://arxiv.org/abs/2110.04975v4)

*Pengcheng Ai, Zhi Deng, Yi Wang, Chendi Shen*

{{< details "abstract" >}} abstract: Characterizing uncertainty is a common issue in nuclear measurement and hasimportant implications for reliable physical discovery. Traditional methods areeither insufficient to cope with the heterogeneous nature of uncertainty orinadequate to perform well with unknown mathematical models. In this paper, wepropose using multi-layer convolutional neural networks for empiricaluncertainty estimation and feature extraction of nuclear pulse signals. Thismethod is based on deep learning, a recent development of machine learningtechniques, which learns the desired mapping function from training data andgeneralizes to unseen test data. Furthermore, ensemble learning is utilized toestimate the uncertainty originating from trainable parameters of the networkand to improve the robustness of the whole model. To evaluate the performanceof the proposed method, simulation studies, in comparison with curve fitting,investigate extensive conditions and show its universal applicability. Finally,a case study is made using data from a NICA-MPD electromagnetic calorimetermodule exposed to a test beam at DESY, Germany. The uncertainty estimationmethod successfully detected out-of-distribution samples and also achieved goodaccuracy in time and energy measurements.
{{< /details >}}

>**_2022-02-25_**

[**Robust and Accurate Authorship Attribution via Program Normalization**](http://arxiv.org/abs/2007.00772v3)

*Yizhen Wang, Mohannad Alhanahnah, Ke Wang, Mihai Christodorescu, Somesh Jha*

{{< details "abstract" >}} abstract: Source code attribution approaches have achieved remarkable accuracy thanksto the rapid advances in deep learning. However, recent studies shed light ontheir vulnerability to adversarial attacks. In particular, they can be easilydeceived by adversaries who attempt to either create a forgery of anotherauthor or to mask the original author. To address these emerging issues, weformulate this security challenge into a general threat model, the$\textit{relational adversary}$, that allows an arbitrary number of thesemantics-preserving transformations to be applied to an input in any problemspace. Our theoretical investigation shows the conditions for robustness andthe trade-off between robustness and accuracy in depth. Motivated by theseinsights, we present a novel learning framework,$\textit{normalize-and-predict}$ ($\textit{N&P}$), that in theory guaranteesthe robustness of any authorship-attribution approach. We conduct an extensiveevaluation of $\textit{N&P}$ in defending two of the latestauthorship-attribution approaches against state-of-the-art attack methods. Ourevaluation demonstrates that $\textit{N&P}$ improves the accuracy onadversarial inputs by as much as 70% over the vanilla models. More importantly,$\textit{N&P}$ also increases robust accuracy to 45% higher than adversarialtraining while running over 40 times faster.
{{< /details >}}

>**_2022-02-24_**

[**Multivariate Deep Evidential Regression**](http://arxiv.org/abs/2104.06135v4)

*Nis Meinert, Alexander Lavin*

{{< details "abstract" >}} abstract: There is significant need for principled uncertainty reasoning in machinelearning systems as they are increasingly deployed in safety-critical domains.A new approach with uncertainty-aware neural networks (NNs), based on learningevidential distributions for aleatoric and epistemic uncertainties, showspromise over traditional deterministic methods and typical Bayesian NNs, yetseveral important gaps in the theory and implementation of these networksremain. We discuss three issues with a proposed solution to extract aleatoricand epistemic uncertainties from regression-based neural networks. The approachderives a technique by placing evidential priors over the original Gaussianlikelihood function and training the NN to infer the hyperparameters of theevidential distribution. Doing so allows for the simultaneous extraction ofboth uncertainties without sampling or utilization of out-of-distribution datafor univariate regression tasks. We describe the outstanding issues in detail,provide a possible solution, and generalize the deep evidential regressiontechnique for multivariate cases.
{{< /details >}}

[**A Self-supervised Representation Learning of Sentence Structure for Authorship Attribution**](http://arxiv.org/abs/2010.06786v2)

*Fereshteh Jafariakinabad, Kien A. Hua*

{{< details "abstract" >}} abstract: Syntactic structure of sentences in a document substantially informs aboutits authorial writing style. Sentence representation learning has been widelyexplored in recent years and it has been shown that it improves thegeneralization of different downstream tasks across many domains. Even thoughutilizing probing methods in several studies suggests that these learnedcontextual representations implicitly encode some amount of syntax, explicitsyntactic information further improves the performance of deep neural models inthe domain of authorship attribution. These observations have motivated us toinvestigate the explicit representation learning of syntactic structure ofsentences. In this paper, we propose a self-supervised framework for learningstructural representations of sentences. The self-supervised network containstwo components; a lexical sub-network and a syntactic sub-network which takethe sequence of words and their corresponding structural labels as the input,respectively. Due to the n-to-1 mapping of words to their structural labels,each word will be embedded into a vector representation which mainly carriesstructural information. We evaluate the learned structural representations ofsentences using different probing tasks, and subsequently utilize them in theauthorship attribution task. Our experimental results indicate that thestructural embeddings significantly improve the classification tasks whenconcatenated with the existing pre-trained word embeddings.
{{< /details >}}

>**_2022-02-21_**

[**A Tutorial on Adversarial Learning Attacks and Countermeasures**](http://arxiv.org/abs/2202.10377v1)

*Cato Pauling, Michael Gimson, Muhammed Qaid, Ahmad Kida, Basel Halak*

{{< details "abstract" >}} abstract: Machine learning algorithms are used to construct a mathematical model for asystem based on training data. Such a model is capable of making highlyaccurate predictions without being explicitly programmed to do so. Thesetechniques have a great many applications in all areas of the modern digitaleconomy and artificial intelligence. More importantly, these methods areessential for a rapidly increasing number of safety-critical applications suchas autonomous vehicles and intelligent defense systems. However, emergingadversarial learning attacks pose a serious security threat that greatlyundermines further such systems. The latter are classified into four types,evasion (manipulating data to avoid detection), poisoning (injection malicioustraining samples to disrupt retraining), model stealing (extraction), andinference (leveraging over-generalization on training data). Understanding thistype of attacks is a crucial first step for the development of effectivecountermeasures. The paper provides a detailed tutorial on the principles ofadversarial machining learning, explains the different attack scenarios, andgives an in-depth insight into the state-of-art defense mechanisms against thisrising threat .
{{< /details >}}

>**_2022-02-16_**

[**TUTOR: Training Neural Networks Using Decision Rules as Model Priors**](http://arxiv.org/abs/2010.05429v3)

*Shayan Hassantabar, Prerit Terway, Niraj K. Jha*

{{< details "abstract" >}} abstract: The human brain has the ability to carry out new tasks with limitedexperience. It utilizes prior learning experiences to adapt the solutionstrategy to new domains. On the other hand, deep neural networks (DNNs)generally need large amounts of data and computational resources for training.However, this requirement is not met in many settings. To address thesechallenges, we propose the TUTOR DNN synthesis framework. TUTOR targets tabulardatasets. It synthesizes accurate DNN models with limited available data andreduced memory/computational requirements. It consists of three sequentialsteps. The first step involves generation, verification, and labeling ofsynthetic data. The synthetic data generation module targets both thecategorical and continuous features. TUTOR generates the synthetic data fromthe same probability distribution as the real data. It then verifies theintegrity of the generated synthetic data using a semantic integrity classifiermodule. It labels the synthetic data based on a set of rules extracted from thereal dataset. Next, TUTOR uses two training schemes that combine synthetic andtraining data to learn the parameters of the DNN model. These two schemes focuson two different ways in which synthetic data can be used to derive a prior onthe model parameters and, hence, provide a better DNN initialization fortraining with real data. In the third step, TUTOR employs a grow-and-prunesynthesis paradigm to learn both the weights and the architecture of the DNN toreduce model size while ensuring its accuracy. We evaluate the performance ofTUTOR on nine datasets of various sizes. We show that in comparison to fullyconnected DNNs, TUTOR, on an average, reduces the need for data by 5.9x,improves accuracy by 3.4%, and reduces the number of parameters (fFLOPs) by4.7x (4.3x). Thus, TUTOR enables a less data-hungry, more accurate, and morecompact DNN synthesis.
{{< /details >}}

>**_2022-02-14_**

[**Explaining deep learning of galaxy morphology with saliency mapping**](http://arxiv.org/abs/2110.08288v2)

*Prabh Bhambra, Benjamin Joachimi, Ofer Lahav*

{{< details "abstract" >}} abstract: We successfully demonstrate the use of explainable artificial intelligence(XAI) techniques on astronomical datasets in the context of measuring galacticbar lengths. The method consists of training convolutional neural networks onhuman classified data from Galaxy Zoo in order to predict general galaxymorphologies, and then using SmoothGrad (a saliency mapping technique) toextract the bar for measurement by a bespoke algorithm. We contrast this toanother method of using a convolutional neural network to directly predictgalaxy bar lengths. These methods achieved correlation coefficients of 0.76 and0.59, and root mean squared errors of 1.69 and 2.10 respective to humanmeasurements. We conclude that XAI methods outperform conventional deeplearning in this case, which could be reasonably explained by the largerdatasets available when training the models. We suggest that our XAI method canbe used to extract other galactic features (such as the bulge-to-disk ratio)without needing to collect new datasets or train new models. We also suggestthat these techniques can be used to refine deep learning models as well asidentify and eliminate bias within training datasets.
{{< /details >}}

>**_2022-02-12_**

[**RoPGen: Towards Robust Code Authorship Attribution via Automatic Coding Style Transformation**](http://arxiv.org/abs/2202.06043v1)

*Zhen Li, Guenevere, Chen, Chen Chen, Yayi Zou, Shouhuai Xu*

{{< details "abstract" >}} abstract: Source code authorship attribution is an important problem often encounteredin applications such as software forensics, bug fixing, and software qualityanalysis. Recent studies show that current source code authorship attributionmethods can be compromised by attackers exploiting adversarial examples andcoding style manipulation. This calls for robust solutions to the problem ofcode authorship attribution. In this paper, we initiate the study on makingDeep Learning (DL)-based code authorship attribution robust. We propose aninnovative framework called Robust coding style Patterns Generation (RoPGen),which essentially learns authors' unique coding style patterns that are hardfor attackers to manipulate or imitate. The key idea is to combine dataaugmentation and gradient augmentation at the adversarial training phase. Thiseffectively increases the diversity of training examples, generates meaningfulperturbations to gradients of deep neural networks, and learns diversifiedrepresentations of coding styles. We evaluate the effectiveness of RoPGen usingfour datasets of programs written in C, C++, and Java. Experimental resultsshow that RoPGen can significantly improve the robustness of DL-based codeauthorship attribution, by respectively reducing 22.8% and 41.0% of the successrate of targeted and untargeted attacks on average.
{{< /details >}}

>**_2022-02-11_**

[**Privacy-preserving Generative Framework Against Membership Inference Attacks**](http://arxiv.org/abs/2202.05469v1)

*Ruikang Yang, Jianfeng Ma, Yinbin Miao, Xindi Ma*

{{< details "abstract" >}} abstract: Artificial intelligence and machine learning have been integrated into allaspects of our lives and the privacy of personal data has attracted more andmore attention. Since the generation of the model needs to extract theeffective information of the training data, the model has the risk of leakingthe privacy of the training data. Membership inference attacks can measure themodel leakage of source data to a certain degree. In this paper, we design aprivacy-preserving generative framework against membership inference attacks,through the information extraction and data generation capabilities of thegenerative model variational autoencoder (VAE) to generate synthetic data thatmeets the needs of differential privacy. Instead of adding noise to the modeloutput or tampering with the training process of the target model, we directlyprocess the original data. We first map the source data to the latent spacethrough the VAE model to get the latent code, then perform noise processsatisfying metric privacy on the latent code, and finally use the VAE model toreconstruct the synthetic data. Our experimental evaluation demonstrates thatthe machine learning model trained with newly generated synthetic data caneffectively resist membership inference attacks and still maintain highutility.
{{< /details >}}

>**_2022-02-08_**

[**Network Comparison Study of Deep Activation Feature Discriminability with Novel Objects**](http://arxiv.org/abs/2202.03695v1)

*Michael Karnes, Alper Yilmaz*

{{< details "abstract" >}} abstract: Feature extraction has always been a critical component of the computervision field. More recently, state-of-the-art computer visions algorithms haveincorporated Deep Neural Networks (DNN) in feature extracting roles, creatingDeep Convolutional Activation Features (DeCAF). The transferability of DNNknowledge domains has enabled the wide use of pretrained DNN feature extractionfor applications with novel object classes, especially those with limitedtraining data. This study analyzes the general discriminability of novel objectvisual appearances encoded into the DeCAF space of six of the leading visualrecognition DNN architectures. The results of this study characterize theMahalanobis distances and cosine similarities between DeCAF object manifoldsacross two visual object tracking benchmark data sets. The backgroundssurrounding each object are also included as an object classes in the manifoldanalysis, providing a wider range of novel classes. This study found thatdifferent network architectures led to different network feature focuses thatmust to be considered in the network selection process. These results aregenerated from the VOT2015 and UAV123 benchmark data sets; however, theproposed methods can be applied to efficiently compare estimated networkperformance characteristics for any labeled visual data set.
{{< /details >}}

>**_2022-01-12_**

[**Automatic Labeling to Generate Training Data for Online LiDAR-based Moving Object Segmentation**](http://arxiv.org/abs/2201.04501v1)

*Xieyuanli Chen, Benedikt Mersch, Lucas Nunes, Rodrigo Marcuzzi, Ignacio Vizzo, Jens Behley, Cyrill Stachniss*

{{< details "abstract" >}} abstract: Understanding the scene is key for autonomously navigating vehicles and theability to segment the surroundings online into moving and non-moving objectsis a central ingredient for this task. Often, deep learning-based methods areused to perform moving object segmentation (MOS). The performance of thesenetworks, however, strongly depends on the diversity and amount of labeledtraining data, information that may be costly to obtain. In this paper, wepropose an automatic data labeling pipeline for 3D LiDAR data to save theextensive manual labeling effort and to improve the performance of existinglearning-based MOS systems by automatically generating labeled training data.Our proposed approach achieves this by processing the data offline in batches.It first exploits an occupancy-based dynamic object removal to detect possibledynamic objects coarsely. Second, it extracts segments among the proposals andtracks them using a Kalman filter. Based on the tracked trajectories, it labelsthe actually moving objects such as driving cars and pedestrians as moving. Incontrast, the non-moving objects, e.g., parked cars, lamps, roads, orbuildings, are labeled as static. We show that this approach allows us to labelLiDAR data highly effectively and compare our results to those of other labelgeneration methods. We also train a deep neural network with our auto-generatedlabels and achieve similar performance compared to the one trained with manuallabels on the same data, and an even better performance when using additionaldatasets with labels generated by our approach. Furthermore, we evaluate ourmethod on multiple datasets using different sensors and our experimentsindicate that our method can generate labels in diverse environments.
{{< /details >}}

>**_2021-12-26_**

[**Killing One Bird with Two Stones: Model Extraction and Attribute Inference Attacks against BERT-based APIs**](http://arxiv.org/abs/2105.10909v2)

*Chen Chen, Xuanli He, Lingjuan Lyu, Fangzhao Wu*

{{< details "abstract" >}} abstract: The collection and availability of big data, combined with advances inpre-trained models (e.g., BERT, XLNET, etc), have revolutionized the predictiveperformance of modern natural language processing tasks, ranging from textclassification to text generation. This allows corporations to provide machinelearning as a service (MLaaS) by encapsulating fine-tuned BERT-based models asAPIs. However, BERT-based APIs have exhibited a series of security and privacyvulnerabilities. For example, prior work has exploited the security issues ofthe BERT-based APIs through the adversarial examples crafted by the extractedmodel. However, the privacy leakage problems of the BERT-based APIs through theextracted model have not been well studied. On the other hand, due to the highcapacity of BERT-based APIs, the fine-tuned model is easy to be overlearned,but what kind of information can be leaked from the extracted model remainsunknown. In this work, we bridge this gap by first presenting an effectivemodel extraction attack, where the adversary can practically steal a BERT-basedAPI (the target/victim model) by only querying a limited number of queries. Wefurther develop an effective attribute inference attack which can infer thesensitive attribute of the training data used by the BERT-based APIs. Ourextensive experiments on benchmark datasets under various realistic settingsvalidate the potential vulnerabilities of BERT-based APIs. Moreover, wedemonstrate that two promising defense methods become ineffective against ourattacks, which calls for more effective defense methods.
{{< /details >}}

>**_2021-12-21_**

[**A Scalable Deep Reinforcement Learning Model for Online Scheduling Coflows of Multi-Stage Jobs for High Performance Computing**](http://arxiv.org/abs/2112.11055v1)

*Xin Wang, Hong Shen*

{{< details "abstract" >}} abstract: Coflow is a recently proposed networking abstraction to help improve thecommunication performance of data-parallel computing jobs. In multi-stage jobs,each job consists of multiple coflows and is represented by a Directed AcyclicGraph (DAG). Efficiently scheduling coflows is critical to improve thedata-parallel computing performance in data centers. Compared with hand-tunedscheduling heuristics, existing work DeepWeave [1] utilizes ReinforcementLearning (RL) framework to generate highly-efficient coflow scheduling policiesautomatically. It employs a graph neural network (GNN) to encode the jobinformation in a set of embedding vectors, and feeds a flat embedding vectorcontaining the whole job information to the policy network. However, thismethod has poor scalability as it is unable to cope with jobs represented byDAGs of arbitrary sizes and shapes, which requires a large policy network forprocessing a high-dimensional embedding vector that is difficult to train. Inthis paper, we first utilize a directed acyclic graph neural network (DAGNN) toprocess the input and propose a novel Pipelined-DAGNN, which can effectivelyspeed up the feature extraction process of the DAGNN. Next, we feed theembedding sequence composed of schedulable coflows instead of a flat embeddingof all coflows to the policy network, and output a priority sequence, whichmakes the size of the policy network depend on only the dimension of featuresinstead of the product of dimension and number of nodes in the job'sDAG.Furthermore, to improve the accuracy of the priority scheduling policy, weincorporate the Self-Attention Mechanism into a deep RL model to capture theinteraction between different parts of the embedding sequence to make theoutput priority scores relevant. Based on this model, we then develop a coflowscheduling algorithm for online multi-stage jobs.
{{< /details >}}

>**_2021-12-17_**

[**Improving Fractal Pre-training**](http://arxiv.org/abs/2110.03091v2)

*Connor Anderson, Ryan Farrell*

{{< details "abstract" >}} abstract: The deep neural networks used in modern computer vision systems requireenormous image datasets to train them. These carefully-curated datasetstypically have a million or more images, across a thousand or more distinctcategories. The process of creating and curating such a dataset is a monumentalundertaking, demanding extensive effort and labelling expense and necessitatingcareful navigation of technical and social issues such as label accuracy,copyright ownership, and content bias.  What if we had a way to harness the power of large image datasets but withfew or none of the major issues and concerns currently faced? This paperextends the recent work of Kataoka et. al. (2020), proposing an improvedpre-training dataset based on dynamically-generated fractal images. Challengingissues with large-scale image datasets become points of elegance for fractalpre-training: perfect label accuracy at zero cost; no need to store/transmitlarge image archives; no privacy/demographic bias/concerns of inappropriatecontent, as no humans are pictured; limitless supply and diversity of images;and the images are free/open-source. Perhaps surprisingly, avoiding thesedifficulties imposes only a small penalty in performance. Leveraging anewly-proposed pre-training task -- multi-instance prediction -- ourexperiments demonstrate that fine-tuning a network pre-trained using fractalsattains 92.7-98.1% of the accuracy of an ImageNet pre-trained network.
{{< /details >}}

>**_2021-12-15_**

[**Model Stealing Attacks Against Inductive Graph Neural Networks**](http://arxiv.org/abs/2112.08331v1)

*Yun Shen, Xinlei He, Yufei Han, Yang Zhang*

{{< details "abstract" >}} abstract: Many real-world data come in the form of graphs. Graph neural networks(GNNs), a new family of machine learning (ML) models, have been proposed tofully leverage graph data to build powerful applications. In particular, theinductive GNNs, which can generalize to unseen data, become mainstream in thisdirection. Machine learning models have shown great potential in various tasksand have been deployed in many real-world scenarios. To train a good model, alarge amount of data as well as computational resources are needed, leading tovaluable intellectual property. Previous research has shown that ML models areprone to model stealing attacks, which aim to steal the functionality of thetarget models. However, most of them focus on the models trained with imagesand texts. On the other hand, little attention has been paid to models trainedwith graph data, i.e., GNNs. In this paper, we fill the gap by proposing thefirst model stealing attacks against inductive GNNs. We systematically definethe threat model and propose six attacks based on the adversary's backgroundknowledge and the responses of the target models. Our evaluation on sixbenchmark datasets shows that the proposed model stealing attacks against GNNsachieve promising performance.
{{< /details >}}

>**_2021-12-14_**

[**MuxLink: Circumventing Learning-Resilient MUX-Locking Using Graph Neural Network-based Link Prediction**](http://arxiv.org/abs/2112.07178v1)

*Lilas Alrahis, Satwik Patnaik, Muhammad Shafique, Ozgur Sinanoglu*

{{< details "abstract" >}} abstract: Logic locking has received considerable interest as a prominent technique forprotecting the design intellectual property from untrusted entities, especiallythe foundry. Recently, machine learning (ML)-based attacks have questioned thesecurity guarantees of logic locking, and have demonstrated considerablesuccess in deciphering the secret key without relying on an oracle, hence,proving to be very useful for an adversary in the fab. Such ML-based attackshave triggered the development of learning-resilient locking techniques. Themost advanced state-of-the-art deceptive MUX-based locking (D-MUX) and thesymmetric MUX-based locking techniques have recently demonstrated resilienceagainst existing ML-based attacks. Both defense techniques obfuscate the designby inserting key-controlled MUX logic, ensuring that all the secret inputs tothe MUXes are equiprobable.  In this work, we show that these techniques primarily introduce local andlimited changes to the circuit without altering the global structure of thedesign. By leveraging this observation, we propose a novel graph neural network(GNN)-based link prediction attack, MuxLink, that successfully breaks both theD-MUX and symmetric MUX-locking techniques, relying only on the underlyingstructure of the locked design, i.e., in an oracle-less setting. Our trainedGNN model learns the structure of the given circuit and the composition ofgates around the non-obfuscated wires, thereby generating meaningful linkembeddings that help decipher the secret inputs to the MUXes. The proposedMuxLink achieves key prediction accuracy and precision up to 100% on D-MUX andsymmetric MUX-locked ISCAS-85 and ITC-99 benchmarks, fully unlocking thedesigns. We open-source MuxLink [1].
{{< /details >}}

>**_2021-12-10_**

[**Copy, Right? A Testing Framework for Copyright Protection of Deep Learning Models**](http://arxiv.org/abs/2112.05588v1)

*Jialuo Chen, Jingyi Wang, Tinglan Peng, Youcheng Sun, Peng Cheng, Shouling Ji, Xingjun Ma, Bo Li, Dawn Song*

{{< details "abstract" >}} abstract: Deep learning (DL) models, especially those large-scale and high-performanceones, can be very costly to train, demanding a great amount of data andcomputational resources. Unauthorized reproduction of DL models can lead tocopyright infringement and cause huge economic losses to model owners. Existingcopyright protection techniques are mostly based on watermarking, which embedsan owner-specified watermark into the model. While being able to provide exactownership verification, these techniques are 1) invasive, as they need totamper with the training process, which may affect the utility or introduce newsecurity risks; 2) prone to adaptive attacks that attempt to remove thewatermark; and 3) not robust to the emerging model extraction attacks. Latestfingerprinting work, though being non-invasive, also falls short when facingthe diverse and ever-growing attack scenarios. In this paper, we propose anovel testing framework for DL copyright protection: DEEPJUDGE. DEEPJUDGEquantitatively tests the similarities between two DL models: a victim model anda suspect model. It leverages a diverse set of testing metrics and test casegeneration methods to produce a chain of supporting evidence to help determinewhether a suspect model is a copy of the victim model. Advantages of DEEPJUDGEinclude: 1) non-invasive, as it works directly on the model and does not tamperwith the training process; 2) efficient, as it only needs a small set of testcases and a quick scan of models; 3) flexible, as it can easily incorporate newmetrics or generation methods to obtain more confident judgement; and 4) fairlyrobust to model extraction and adaptive attacks. We verify the effectiveness ofDEEPJUDGE under typical copyright infringement scenarios, including modelfinetuning, pruning and extraction, via extensive experiments on both image andspeech datasets with a variety of model architectures.
{{< /details >}}

[**Protecting Your NLG Models with Semantic and Robust Watermarks**](http://arxiv.org/abs/2112.05428v1)

*Tao Xiang, Chunlong Xie, Shangwei Guo, Jiwei Li, Tianwei Zhang*

{{< details "abstract" >}} abstract: Natural language generation (NLG) applications have gained great popularitydue to the powerful deep learning techniques and large training corpus. Thedeployed NLG models may be stolen or used without authorization, whilewatermarking has become a useful tool to protect Intellectual Property (IP) ofdeep models. However, existing watermarking technologies using backdoors areeasily detected or harmful for NLG applications. In this paper, we propose asemantic and robust watermarking scheme for NLG models that utilize unharmfulphrase pairs as watermarks for IP protection. The watermarks give NLG modelspersonal preference for some special phrase combinations. Specifically, wegenerate watermarks by following a semantic combination pattern andsystematically augment the watermark corpus to enhance the robustness. Then, weembed these watermarks into an NLG model without misleading its originalattention mechanism. We conduct extensive experiments and the resultsdemonstrate the effectiveness, robustness, and undetectability of the proposedscheme.
{{< /details >}}

>**_2021-12-05_**

[**Protecting Intellectual Property of Language Generation APIs with Lexical Watermark**](http://arxiv.org/abs/2112.02701v1)

*Xuanli He, Qiongkai Xu, Lingjuan Lyu, Fangzhao Wu, Chenguang Wang*

{{< details "abstract" >}} abstract: Nowadays, due to the breakthrough in natural language generation (NLG),including machine translation, document summarization, image captioning, etcNLG models have been encapsulated in cloud APIs to serve over half a billionpeople worldwide and process over one hundred billion word generations per day.Thus, NLG APIs have already become essential profitable services in manycommercial companies. Due to the substantial financial and intellectualinvestments, service providers adopt a pay-as-you-use policy to promotesustainable market growth. However, recent works have shown that cloudplatforms suffer from financial losses imposed by model extraction attacks,which aim to imitate the functionality and utility of the victim services, thusviolating the intellectual property (IP) of cloud APIs. This work targets atprotecting IP of NLG APIs by identifying the attackers who have utilizedwatermarked responses from the victim NLG APIs. However, most existingwatermarking techniques are not directly amenable for IP protection of NLGAPIs. To bridge this gap, we first present a novel watermarking method for textgeneration APIs by conducting lexical modification to the original outputs.Compared with the competitive baselines, our watermark approach achieves betteridentifiable performance in terms of p-value, with fewer semantic losses. Inaddition, our watermarks are more understandable and intuitive to humans thanthe baselines. Finally, the empirical studies show our approach is alsoapplicable to queries from different domains, and is effective on the attackertrained on a mixture of the corpus which includes less than 10\% watermarkedsamples.
{{< /details >}}

[**A Deep-Learning Intelligent System Incorporating Data Augmentation for Short-Term Voltage Stability Assessment of Power Systems**](http://arxiv.org/abs/2112.03265v1)

*Yang Li, Meng Zhang, Chen Chen*

{{< details "abstract" >}} abstract: Facing the difficulty of expensive and trivial data collection andannotation, how to make a deep learning-based short-term voltage stabilityassessment (STVSA) model work well on a small training dataset is a challengingand urgent problem. Although a big enough dataset can be directly generated bycontingency simulation, this data generation process is usually cumbersome andinefficient; while data augmentation provides a low-cost and efficient way toartificially inflate the representative and diversified training datasets withlabel preserving transformations. In this respect, this paper proposes a noveldeep-learning intelligent system incorporating data augmentation for STVSA ofpower systems. First, due to the unavailability of reliable quantitativecriteria to judge the stability status for a specific power system,semi-supervised cluster learning is leveraged to obtain labeled samples in anoriginal small dataset. Second, to make deep learning applicable to the smalldataset, conditional least squares generative adversarial networks(LSGAN)-based data augmentation is introduced to expand the original datasetvia artificially creating additional valid samples. Third, to extract temporaldependencies from the post-disturbance dynamic trajectories of a system, abi-directional gated recurrent unit with attention mechanism based assessmentmodel is established, which bi-directionally learns the significant timedependencies and automatically allocates attention weights. The test resultsdemonstrate the presented approach manages to achieve better accuracy and afaster response time with original small datasets. Besides classificationaccuracy, this work employs statistical measures to comprehensively examine theperformance of the proposal.
{{< /details >}}

>**_2021-12-01_**

[**CondenseNeXt: An Ultra-Efficient Deep Neural Network for Embedded Systems**](http://arxiv.org/abs/2112.00698v1)

*Priyank Kalgaonkar, Mohamed El-Sharkawy*

{{< details "abstract" >}} abstract: Due to the advent of modern embedded systems and mobile devices withconstrained resources, there is a great demand for incredibly efficient deepneural networks for machine learning purposes. There is also a growing concernof privacy and confidentiality of user data within the general public whentheir data is processed and stored in an external server which has furtherfueled the need for developing such efficient neural networks for real-timeinference on local embedded systems. The scope of our work presented in thispaper is limited to image classification using a convolutional neural network.A Convolutional Neural Network (CNN) is a class of Deep Neural Network (DNN)widely used in the analysis of visual images captured by an image sensor,designed to extract information and convert it into meaningful representationsfor real-time inference of the input data. In this paper, we propose a neotericvariant of deep convolutional neural network architecture to ameliorate theperformance of existing CNN architectures for real-time inference on embeddedsystems. We show that this architecture, dubbed CondenseNeXt, is remarkablyefficient in comparison to the baseline neural network architecture,CondenseNet, by reducing trainable parameters and FLOPs required to train thenetwork whilst maintaining a balance between the trained model size of lessthan 3.0 MB and accuracy trade-off resulting in an unprecedented computationalefficiency.
{{< /details >}}

>**_2021-11-16_**

[**Radar Aided mmWave Vehicle-to-InfrastructureLink Configuration Using Deep Learning**](http://arxiv.org/abs/2111.08527v1)

*Yun Chen, Andrew Graff, Nuria González-Prelcic, Takayuki Shimizu*

{{< details "abstract" >}} abstract: The high overhead of the beam training process is the main challenge whenestablishing mmWave communication links, especially for vehicle-to-everything(V2X) scenarios where the channels are highly dynamic. In this paper, we obtainprior information to speed up the beam training process by implementing twodeep neural networks (DNNs) that realize radar-to-communication (R2C) channelinformation translation in a vehicle-to-infrastructure (V2I) system.Specifically, the first DNN is built to extract the information from the radarazimuth power spectrum (APS) to reconstruct the communication APS, while thesecond DNN exploits the information extracted from the spatial covariance ofthe radar channel to realize R2C covariance prediction. The achieved data rateand the similarity between the estimated and the true communication APS areused to evaluate the prediction performance. The covariance estimation methodgenerally provides higher similarity, as the APS predictions cannot alwayscapture the mismatch between the radar and communication APS. Compared to thebeam training method which exploits directly the radar APS without an attemptto translate it to the communication channel, our proposed deep learning (DL)aided methods remarkably reduce the beam training overhead, resulting in a13.3% and 21.9% rate increase when using the communication APS prediction andcovariance prediction, respectively.
{{< /details >}}

>**_2021-10-25_**

[**Generating Watermarked Adversarial Texts**](http://arxiv.org/abs/2110.12948v1)

*Mingjie Li, Hanzhou Wu, Xinpeng Zhang*

{{< details "abstract" >}} abstract: Adversarial example generation has been a hot spot in recent years because itcan cause deep neural networks (DNNs) to misclassify the generated adversarialexamples, which reveals the vulnerability of DNNs, motivating us to find goodsolutions to improve the robustness of DNN models. Due to the extensiveness andhigh liquidity of natural language over the social networks, various naturallanguage based adversarial attack algorithms have been proposed in theliterature. These algorithms generate adversarial text examples with highsemantic quality. However, the generated adversarial text examples may bemaliciously or illegally used. In order to tackle with this problem, we presenta general framework for generating watermarked adversarial text examples. Foreach word in a given text, a set of candidate words are determined to ensurethat all the words in the set can be used to either carry secret bits orfacilitate the construction of adversarial example. By applying a word-leveladversarial text generation algorithm, the watermarked adversarial text examplecan be finally generated. Experiments show that the adversarial text examplesgenerated by the proposed method not only successfully fool advanced DNNmodels, but also carry a watermark that can effectively verify the ownershipand trace the source of the adversarial examples. Moreover, the watermark canstill survive after attacked with adversarial example generation algorithms,which has shown the applicability and superiority.
{{< /details >}}

[**Scientific Machine Learning Benchmarks**](http://arxiv.org/abs/2110.12773v1)

*Jeyan Thiyagalingam, Mallikarjun Shankar, Geoffrey Fox, Tony Hey*

{{< details "abstract" >}} abstract: The breakthrough in Deep Learning neural networks has transformed the use ofAI and machine learning technologies for the analysis of very largeexperimental datasets. These datasets are typically generated by large-scaleexperimental facilities at national laboratories. In the context of science,scientific machine learning focuses on training machines to identify patterns,trends, and anomalies to extract meaningful scientific insights from suchdatasets. With a new generation of experimental facilities, the rate of datageneration and the scale of data volumes will increasingly require the use ofmore automated data analysis. At present, identifying the most appropriatemachine learning algorithm for the analysis of any given scientific dataset isstill a challenge for scientists. This is due to many different machinelearning frameworks, computer architectures, and machine learning models.Historically, for modelling and simulation on HPC systems such problems havebeen addressed through benchmarking computer applications, algorithms, andarchitectures. Extending such a benchmarking approach and identifying metricsfor the application of machine learning methods to scientific datasets is a newchallenge for both scientists and computer scientists. In this paper, wedescribe our approach to the development of scientific machine learningbenchmarks and review other approaches to benchmarking scientific machinelearning.
{{< /details >}}

>**_2021-10-24_**

[**Implementation paradigm for supervised flare forecasting studies: a deep learning application with video data**](http://arxiv.org/abs/2110.12554v1)

*Sabrina Guastavino, Francesco Marchetti, Federico Benvenuto, Cristina Campi, Michele Piana*

{{< details "abstract" >}} abstract: Solar flare forecasting can be realized by means of the analysis of magneticdata through artificial intelligence techniques. The aim is to predict whethera magnetic active region (AR) will originate solar flares above a certain classwithin a certain amount of time. A crucial issue is concerned with the way theadopted machine learning method is implemented, since forecasting resultsstrongly depend on the criterion with which training, validation, and test setsare populated. In this paper we propose a general paradigm to generate thesesets in such a way that they are independent from each other and internallywell-balanced in terms of AR flaring effectiveness. This set generation processprovides a ground for comparison for the performance assessment of machinelearning algorithms. Finally, we use this implementation paradigm in the caseof a deep neural network, which takes as input videos of magnetograms recordedby the Helioseismic and Magnetic Imager on-board the Solar Dynamics Observatory(SDO/HMI). To our knowledge, this is the first time that the solar flareforecasting problem is addressed by means of a deep neural network for videoclassification, which does not require any a priori extraction of features fromthe HMI magnetograms.
{{< /details >}}

>**_2021-10-18_**

[**Protecting Anonymous Speech: A Generative Adversarial Network Methodology for Removing Stylistic Indicators in Text**](http://arxiv.org/abs/2110.09495v1)

*Rishi Balakrishnan, Stephen Sloan, Anil Aswani*

{{< details "abstract" >}} abstract: With Internet users constantly leaving a trail of text, whether throughblogs, emails, or social media posts, the ability to write and protestanonymously is being eroded because artificial intelligence, when given asample of previous work, can match text with its author out of hundreds ofpossible candidates. Existing approaches to authorship anonymization, alsoknown as authorship obfuscation, often focus on protecting binary demographicattributes rather than identity as a whole. Even those that do focus onobfuscating identity require manual feedback, lose the coherence of theoriginal sentence, or only perform well given a limited subset of authors. Inthis paper, we develop a new approach to authorship anonymization byconstructing a generative adversarial network that protects identity andoptimizes for three different losses corresponding to anonymity, fluency, andcontent preservation. Our fully automatic method achieves comparable results toother methods in terms of content preservation and fluency, but greatlyoutperforms baselines in regards to anonymization. Moreover, our approach isable to generalize well to an open-set context and anonymize sentences fromauthors it has not encountered before.
{{< /details >}}

>**_2021-10-16_**

[**Motif-based Graph Self-Supervised Learning for Molecular Property Prediction**](http://arxiv.org/abs/2110.00987v2)

*Zaixi Zhang, Qi Liu, Hao Wang, Chengqiang Lu, Chee-Kong Lee*

{{< details "abstract" >}} abstract: Predicting molecular properties with data-driven methods has drawn muchattention in recent years. Particularly, Graph Neural Networks (GNNs) havedemonstrated remarkable success in various molecular generation and predictiontasks. In cases where labeled data is scarce, GNNs can be pre-trained onunlabeled molecular data to first learn the general semantic and structuralinformation before being fine-tuned for specific tasks. However, most existingself-supervised pre-training frameworks for GNNs only focus on node-level orgraph-level tasks. These approaches cannot capture the rich information insubgraphs or graph motifs. For example, functional groups (frequently-occurredsubgraphs in molecular graphs) often carry indicative information about themolecular properties. To bridge this gap, we propose Motif-based GraphSelf-supervised Learning (MGSSL) by introducing a novel self-supervised motifgeneration framework for GNNs. First, for motif extraction from moleculargraphs, we design a molecule fragmentation method that leverages aretrosynthesis-based algorithm BRICS and additional rules for controlling thesize of motif vocabulary. Second, we design a general motif-based generativepre-training framework in which GNNs are asked to make topological and labelpredictions. This generative framework can be implemented in two differentways, i.e., breadth-first or depth-first. Finally, to take the multi-scaleinformation in molecular graphs into consideration, we introduce a multi-levelself-supervised pre-training. Extensive experiments on various downstreambenchmark tasks show that our methods outperform all state-of-the-artbaselines.
{{< /details >}}

>**_2021-10-14_**

[**CNN-DST: ensemble deep learning based on Dempster-Shafer theory for vibration-based fault recognition**](http://arxiv.org/abs/2110.07191v1)

*Vahid Yaghoubi, Liangliang Cheng, Wim Van Paepegem, Mathias Kersemans*

{{< details "abstract" >}} abstract: Nowadays, using vibration data in conjunction with pattern recognitionmethods is one of the most common fault detection strategies for structures.However, their performances depend on the features extracted from vibrationdata, the features selected to train the classifier, and the classifier usedfor pattern recognition. Deep learning facilitates the fault detectionprocedure by automating the feature extraction and selection, andclassification procedure. Though, deep learning approaches have challenges indesigning its structure and tuning its hyperparameters, which may result in alow generalization capability. Therefore, this study proposes an ensemble deeplearning framework based on a convolutional neural network (CNN) andDempster-Shafer theory (DST), called CNN-DST. In this framework, several CNNswith the proposed structure are first trained, and then, the outputs of theCNNs selected by the proposed technique are combined by using an improvedDST-based method. To validate the proposed CNN-DST framework, it is applied toan experimental dataset created by the broadband vibrational responses ofpolycrystalline Nickel alloy first-stage turbine blades with different typesand severities of damage. Through statistical analysis, it is shown that theproposed CNN-DST framework classifies the turbine blades with an averageprediction accuracy of 97.19%. The proposed CNN-DST framework is benchmarkedwith other state-of-the-art classification methods, demonstrating its highperformance. The robustness of the proposed CNN-DST framework with respect tomeasurement noise is investigated, showing its high noise-resistance. Further,bandwidth analysis reveals that most of the required information for detectingfaulty samples is available in a small frequency range.
{{< /details >}}

>**_2021-10-13_**

[**Explaining Deep Neural Networks**](http://arxiv.org/abs/2010.01496v2)

*Oana-Maria Camburu*

{{< details "abstract" >}} abstract: Deep neural networks are becoming more and more popular due to theirrevolutionary success in diverse areas, such as computer vision, naturallanguage processing, and speech recognition. However, the decision-makingprocesses of these models are generally not interpretable to users. In variousdomains, such as healthcare, finance, or law, it is critical to know thereasons behind a decision made by an artificial intelligence system. Therefore,several directions for explaining neural models have recently been explored. Inthis thesis, I investigate two major directions for explaining deep neuralnetworks. The first direction consists of feature-based post-hoc explanatorymethods, that is, methods that aim to explain an already trained and fixedmodel (post-hoc), and that provide explanations in terms of input features,such as tokens for text and superpixels for images (feature-based). The seconddirection consists of self-explanatory neural models that generate naturallanguage explanations, that is, models that have a built-in module thatgenerates explanations for the predictions of the model.
{{< /details >}}

>**_2021-10-12_**

[**Sharing FANCI Features: A Privacy Analysis of Feature Extraction for DGA Detection**](http://arxiv.org/abs/2110.05849v1)

*Benedikt Holmes, Arthur Drichel, Ulrike Meyer*

{{< details "abstract" >}} abstract: The goal of Domain Generation Algorithm (DGA) detection is to recognizeinfections with bot malware and is often done with help of Machine Learningapproaches that classify non-resolving Domain Name System (DNS) traffic and aretrained on possibly sensitive data. In parallel, the rise of privacy researchin the Machine Learning world leads to privacy-preserving measures that aretightly coupled with a deep learning model's architecture or training routine,while non deep learning approaches are commonly better suited for theapplication of privacy-enhancing methods outside the actual classificationmodule. In this work, we aim to measure the privacy capability of the featureextractor of feature-based DGA detector FANCI (Feature-based Automated NxdomainClassification and Intelligence). Our goal is to assess whether a data-richadversary can learn an inverse mapping of FANCI's feature extractor and therebyreconstruct domain names from feature vectors. Attack success would pose aprivacy threat to sharing FANCI's feature representation, while the oppositewould enable this representation to be shared without privacy concerns. Usingthree real-world data sets, we train a recurrent Machine Learning model on thereconstruction task. Our approaches result in poor reconstruction performanceand we attempt to back our findings with a mathematical review of the featureextraction process. We thus reckon that sharing FANCI's feature representationdoes not constitute a considerable privacy leakage.
{{< /details >}}

[**Hiding Images into Images with Real-world Robustness**](http://arxiv.org/abs/2110.05689v1)

*Qichao Ying, Hang Zhou, Xianhan Zeng, Haisheng Xu, Zhenxing Qian, Xinpeng Zhang*

{{< details "abstract" >}} abstract: The existing image embedding networks are basically vulnerable to maliciousattacks such as JPEG compression and noise adding, not applicable forreal-world copyright protection tasks. To solve this problem, we introduce agenerative deep network based method for hiding images into images whileassuring high-quality extraction from the destructive synthesized images. Anembedding network is sequentially concatenated with an attack layer, adecoupling network and an image extraction network. The addition of decouplingnetwork learns to extract the embedded watermark from the attacked image. Wealso pinpoint the weaknesses of the adversarial training for robustness inprevious works and build our improved real-world attack simulator. Experimentalresults demonstrate the superiority of the proposed method against typicaldigital attacks by a large margin, as well as the performance boost of therecovered images with the aid of progressive recovery strategy. Besides, we arethe first to robustly hide three secret images.
{{< /details >}}

>**_2021-10-07_**

[**Fingerprinting Multi-exit Deep Neural Network Models via Inference Time**](http://arxiv.org/abs/2110.03175v1)

*Tian Dong, Han Qiu, Tianwei Zhang, Jiwei Li, Hewu Li, Jialiang Lu*

{{< details "abstract" >}} abstract: Transforming large deep neural network (DNN) models into the multi-exitarchitectures can overcome the overthinking issue and distribute a large DNNmodel on resource-constrained scenarios (e.g. IoT frontend devices and backendservers) for inference and transmission efficiency. Nevertheless, intellectualproperty (IP) protection for the multi-exit models in the wild is still anunsolved challenge. Previous efforts to verify DNN model ownership mainly relyon querying the model with specific samples and checking the responses, e.g.,DNN watermarking and fingerprinting. However, they are vulnerable toadversarial settings such as adversarial training and are not suitable for theIP verification for multi-exit DNN models. In this paper, we propose a novelapproach to fingerprint multi-exit models via inference time rather thaninference predictions. Specifically, we design an effective method to generatea set of fingerprint samples to craft the inference process with a unique androbust inference time cost as the evidence for model ownership. We conductextensive experiments to prove the uniqueness and robustness of our method onthree structures (ResNet-56, VGG-16, and MobileNet) and three datasets(CIFAR-10, CIFAR-100, and Tiny-ImageNet) under comprehensive adversarialsettings.
{{< /details >}}

>**_2021-09-23_**

[**DeepRare: Generic Unsupervised Visual Attention Models**](http://arxiv.org/abs/2109.11439v1)

*Phutphalla Kong, Matei Mancas, Bernard Gosselin, Kimtho Po*

{{< details "abstract" >}} abstract: Human visual system is modeled in engineering field providingfeature-engineered methods which detect contrasted/surprising/unusual data intoimages. This data is "interesting" for humans and leads to numerousapplications. Deep learning (DNNs) drastically improved the algorithmsefficiency on the main benchmark datasets. However, DNN-based models arecounter-intuitive: surprising or unusual data is by definition difficult tolearn because of its low occurrence probability. In reality, DNN-based modelsmainly learn top-down features such as faces, text, people, or animals whichusually attract human attention, but they have low efficiency in extractingsurprising or unusual data in the images. In this paper, we propose a newvisual attention model called DeepRare2021 (DR21) which uses the power of DNNsfeature extraction and the genericity of feature-engineered algorithms. Thisalgorithm is an evolution of a previous version called DeepRare2019 (DR19)based on a common framework. DR21 1) does not need any training and uses thedefault ImageNet training, 2) is fast even on CPU, 3) is tested on four verydifferent eye-tracking datasets showing that the DR21 is generic and is alwaysin the within the top models on all datasets and metrics while no other modelexhibits such a regularity and genericity. Finally DR21 4) is tested withseveral network architectures such as VGG16 (V16), VGG19 (V19) and MobileNetV2(MN2) and 5) it provides explanation and transparency on which parts of theimage are the most surprising at different levels despite the use of aDNN-based feature extractor. DeepRare2021 code can be found athttps://github.com/numediart/VisualAttention-RareFamil}.
{{< /details >}}

>**_2021-09-22_**

[**A deep neural network for multi-species fish detection using multiple acoustic cameras**](http://arxiv.org/abs/2109.10664v1)

*Guglielmo Fernandez Garcia, François Martignac, Marie Nevoux, Laurent Beaulaton, Thomas Corpetti*

{{< details "abstract" >}} abstract: Underwater acoustic cameras are high potential devices for many applicationsin ecology, notably for fisheries management and monitoring. However how toextract such data into high value information without a time-consuming entiredataset reading by an operator is still a challenge. Moreover the analysis ofacoustic imaging, due to its low signal-to-noise ratio, is a perfect trainingground for experimenting with new approaches, especially concerning DeepLearning techniques. We present hereby a novel approach that takes advantage ofboth CNN (Convolutional Neural Network) and classical CV (Computer Vision)techniques, able to detect a generic class ''fish'' in acoustic video streams.The pipeline pre-treats the acoustic images to extract 2 features, in order tolocalise the signals and improve the detection performances. To ensure theperformances from an ecological point of view, we propose also a two-stepvalidation, one to validate the results of the trainings and one to test themethod on a real-world scenario. The YOLOv3-based model was trained with dataof fish from multiple species recorded by the two common acoustic cameras,DIDSON and ARIS, including species of high ecological interest, as Atlanticsalmon or European eels. The model we developed provides satisfying resultsdetecting almost 80% of fish and minimizing the false positive rate, howeverthe model is much less efficient for eel detections on ARIS videos. The firstCNN pipeline for fish monitoring exploiting video data from two models ofacoustic cameras satisfies most of the required features. Many challenges arestill present, such as the automation of fish species identification through amulticlass model. 1 However the results point a new solution for dealing withcomplex data, such as sonar data, which can also be reapplied in other caseswhere the signal-to-noise ratio is a challenge.
{{< /details >}}

>**_2021-09-19_**

[**Navigating the Kaleidoscope of COVID-19 Misinformation Using Deep Learning**](http://arxiv.org/abs/2110.15703v1)

*Yuanzhi Chen, Mohammad Rashedul Hasan*

{{< details "abstract" >}} abstract: Irrespective of the success of the deep learning-based mixed-domain transferlearning approach for solving various Natural Language Processing tasks, itdoes not lend a generalizable solution for detecting misinformation fromCOVID-19 social media data. Due to the inherent complexity of this type ofdata, caused by its dynamic (context evolves rapidly), nuanced (misinformationtypes are often ambiguous), and diverse (skewed, fine-grained, and overlappingcategories) nature, it is imperative for an effective model to capture both thelocal and global context of the target domain. By conducting a systematicinvestigation, we show that: (i) the deep Transformer-based pre-trained models,utilized via the mixed-domain transfer learning, are only good at capturing thelocal context, thus exhibits poor generalization, and (ii) a combination ofshallow network-based domain-specific models and convolutional neural networkscan efficiently extract local as well as global context directly from thetarget data in a hierarchical fashion, enabling it to offer a moregeneralizable solution.
{{< /details >}}

>**_2021-09-10_**

[**Emerging AI Security Threats for Autonomous Cars -- Case Studies**](http://arxiv.org/abs/2109.04865v1)

*Shanthi Lekkala, Tanya Motwani, Manojkumar Parmar, Amit Phadke*

{{< details "abstract" >}} abstract: Artificial Intelligence has made a significant contribution to autonomousvehicles, from object detection to path planning. However, AI models require alarge amount of sensitive training data and are usually computationallyintensive to build. The commercial value of such models motivates attackers tomount various attacks. Adversaries can launch model extraction attacks formonetization purposes or step-ping-stone towards other attacks like modelevasion. In specific cases, it even results in destroying brand reputation,differentiation, and value proposition. In addition, IP laws and AI-relatedlegalities are still evolving and are not uniform across countries. We discussmodel extraction attacks in detail with two use-cases and a generic kill-chainthat can compromise autonomous cars. It is essential to investigate strategiesto manage and mitigate the risk of model theft.
{{< /details >}}

>**_2021-09-03_**

[**LG4AV: Combining Language Models and Graph Neural Networks for Author Verification**](http://arxiv.org/abs/2109.01479v1)

*Maximilian Stubbemann, Gerd Stumme*

{{< details "abstract" >}} abstract: The automatic verification of document authorships is important in varioussettings. Researchers are for example judged and compared by the amount andimpact of their publications and public figures are confronted by their postson social media platforms. Therefore, it is important that authorshipinformation in frequently used web services and platforms is correct. Thequestion whether a given document is written by a given author is commonlyreferred to as authorship verification (AV). While AV is a widely investigatedproblem in general, only few works consider settings where the documents areshort and written in a rather uniform style. This makes most approachesunpractical for online databases and knowledge graphs in the scholarly domain.Here, authorships of scientific publications have to be verified, often withjust abstracts and titles available. To this point, we present our novelapproach LG4AV which combines language models and graph neural networks forauthorship verification. By directly feeding the available texts in apre-trained transformer architecture, our model does not need any hand-craftedstylometric features that are not meaningful in scenarios where the writingstyle is, at least to some extent, standardized. By the incorporation of agraph neural network structure, our model can benefit from relations betweenauthors that are meaningful with respect to the verification process. Forexample, scientific authors are more likely to write about topics that areaddressed by their co-authors and twitter users tend to post about the samesubjects as people they follow. We experimentally evaluate our model and studyto which extent the inclusion of co-authorships enhances verification decisionsin bibliometric environments.
{{< /details >}}

>**_2021-09-02_**

[**Cross-lingual Transfer of Abstractive Summarizer to Less-resource Language**](http://arxiv.org/abs/2012.04307v2)

*Aleš Žagar, Marko Robnik-Šikonja*

{{< details "abstract" >}} abstract: Automatic text summarization extracts important information from texts andpresents the information in the form of a summary. Abstractive summarizationapproaches progressed significantly by switching to deep neural networks, butresults are not yet satisfactory, especially for languages where large trainingsets do not exist. In several natural language processing tasks, across-lingual model transfer is successfully applied in less-resourcelanguages. For summarization, the cross-lingual model transfer was notattempted due to a non-reusable decoder side of neural models that cannotcorrect target language generation. In our work, we use a pre-trained Englishsummarization model based on deep neural networks and sequence-to-sequencearchitecture to summarize Slovene news articles. We address the problem ofinadequate decoder by using an additional language model for the evaluation ofthe generated text in target language. We test several cross-lingualsummarization models with different amounts of target data for fine-tuning. Weassess the models with automatic evaluation measures and conduct a small-scalehuman evaluation. Automatic evaluation shows that the summaries of our bestcross-lingual model are useful and of quality similar to the model trained onlyin the target language. Human evaluation shows that our best model generatessummaries with high accuracy and acceptable readability. However, similar toother abstractive models, our models are not perfect and may occasionallyproduce misleading or absurd content.
{{< /details >}}

>**_2021-09-01_**

[**Pulmonary Disease Classification Using Globally Correlated Maximum Likelihood: an Auxiliary Attention mechanism for Convolutional Neural Networks**](http://arxiv.org/abs/2109.00573v1)

*Edward Verenich, Tobias Martin, Alvaro Velasquez, Nazar Khan, Faraz Hussain*

{{< details "abstract" >}} abstract: Convolutional neural networks (CNN) are now being widely used for classifyingand detecting pulmonary abnormalities in chest radiographs. Two complementarygeneralization properties of CNNs, translation invariance and equivariance, areparticularly useful in detecting manifested abnormalities associated withpulmonary disease, regardless of their spatial locations within the image.However, these properties also come with the loss of exact spatial informationand global relative positions of abnormalities detected in local regions.Global relative positions of such abnormalities may help distinguish similarconditions, such as COVID-19 and viral pneumonia. In such instances, a globalattention mechanism is needed, which CNNs do not support in their traditionalarchitectures that aim for generalization afforded by translation invarianceand equivariance. Vision Transformers provide a global attention mechanism, butlack translation invariance and equivariance, requiring significantly moretraining data samples to match generalization of CNNs. To address the loss ofspatial information and global relations between features, while preserving theinductive biases of CNNs, we present a novel technique that serves as anauxiliary attention mechanism to existing CNN architectures, in order toextract global correlations between salient features.
{{< /details >}}

>**_2021-08-28_**

[**A new rotating machinery fault diagnosis method based on the Time Series Transformer**](http://arxiv.org/abs/2108.12562v1)

*Yuhong Jin, Lei Hou, Yushu Chen*

{{< details "abstract" >}} abstract: Fault diagnosis of rotating machinery is an important engineering problem. Inrecent years, fault diagnosis methods based on the Convolutional Neural Network(CNN) and Recurrent Neural Network (RNN) have been mature, but Transformer hasnot been widely used in the field of fault diagnosis. To address thesedeficiencies, a new method based on the Time Series Transformer (TST) isproposed to recognize the fault mode of bearings. In this paper, ourcontributions include: Firstly, we designed a tokens sequences generationmethod which can handle data in 1D format, namely time series tokenizer. Then,the TST combining time series tokenizer and Transformer was introduced.Furthermore, the test results on the given dataset show that the proposedmethod has better fault identification capability than the traditional CNN andRNN models. Secondly, through the experiments, the effect of structuralhyperparameters such as subsequence length and embedding dimension on faultdiagnosis performance, computational complexity and parameters number of theTST is analyzed in detail. The influence laws of some hyperparameters areobtained. Finally, via t-Distributed Stochastic Neighbor Embedding (t-SNE)dimensionality reduction method, the feature vectors in the embedding space arevisualized. On this basis, the working pattern of TST has been explained to acertain extent. Moreover, by analyzing the distribution form of the featurevectors, we find that compared with the traditional CNN and RNN models, thefeature vectors extracted by the method in this paper show the best intra-classcompactness and inter-class separability. These results further demonstrate theeffectiveness of the proposed method.
{{< /details >}}

>**_2021-08-27_**

[**Offensive Language Identification in Low-resourced Code-mixed Dravidian languages using Pseudo-labeling**](http://arxiv.org/abs/2108.12177v1)

*Adeep Hande, Karthik Puranik, Konthala Yasaswini, Ruba Priyadharshini, Sajeetha Thavareesan, Anbukkarasi Sampath, Kogilavani Shanmugavadivel, Durairaj Thenmozhi, Bharathi Raja Chakravarthi*

{{< details "abstract" >}} abstract: Social media has effectively become the prime hub of communication anddigital marketing. As these platforms enable the free manifestation of thoughtsand facts in text, images and video, there is an extensive need to screen themto protect individuals and groups from offensive content targeted at them. Ourwork intends to classify codemixed social media comments/posts in the Dravidianlanguages of Tamil, Kannada, and Malayalam. We intend to improve offensivelanguage identification by generating pseudo-labels on the dataset. A customdataset is constructed by transliterating all the code-mixed texts into therespective Dravidian language, either Kannada, Malayalam, or Tamil and thengenerating pseudo-labels for the transliterated dataset. The two datasets arecombined using the generated pseudo-labels to create a custom dataset calledCMTRA. As Dravidian languages are under-resourced, our approach increases theamount of training data for the language models. We fine-tune several recentpretrained language models on the newly constructed dataset. We extract thepretrained language embeddings and pass them onto recurrent neural networks. Weobserve that fine-tuning ULMFiT on the custom dataset yields the best resultson the code-mixed test sets of all three languages. Our approach yields thebest results among the benchmarked models on Tamil-English, achieving aweighted F1-Score of 0.7934 while scoring competitive weighted F1-Scores of0.9624 and 0.7306 on the code-mixed test sets of Malayalam-English andKannada-English, respectively.
{{< /details >}}

>**_2021-08-20_**

[**A Hybrid System for Learning Classical Data in Quantum States**](http://arxiv.org/abs/2012.00256v2)

*Samuel A. Stein, Ryan L'Abbate, Wenrui Mu, Yue Liu, Betis Baheri, Ying Mao, Qiang Guan, Ang Li, Bo Fang*

{{< details "abstract" >}} abstract: Deep neural network powered artificial intelligence has rapidly changed ourdaily life with various applications. However, as one of the essential steps ofdeep neural networks, training a heavily weighted network requires a tremendousamount of computing resources. Especially in the post-Moore's Law era, thelimit of semiconductor fabrication technology has restricted the development oflearning algorithms to cope with the increasing high-intensity training data.Meanwhile, quantum computing has demonstrated its significant potential interms of speeding up the traditionally compute-intensive workloads. Forexample, Google illustrated quantum supremacy by completing a samplingcalculation task in 200 seconds, which is otherwise impracticable on theworld's largest supercomputers. To this end, quantum-based learning has becomean area of interest, with the potential of a quantum speedup. In this paper, wepropose GenQu, a hybrid and general-purpose quantum framework for learningclassical data through quantum states. We evaluate GenQu with real datasets andconduct experiments on both simulations and real quantum computer IBM-Q. Ourevaluation demonstrates that, compared with classical solutions, the proposedmodels running on GenQu framework achieve similar accuracy with a much smallernumber of qubits, while significantly reducing the parameter size by up to95.86% and converging speedup by 33.33% faster.
{{< /details >}}

>**_2021-08-11_**

[**Deep learning analysis of polaritonic waves images**](http://arxiv.org/abs/2108.07222v1)

*Suheng Xu, Alexander S. McLeod, Xinzhong Chen, Daniel J. Rizzo, Bjarke S. Jessen, Ziheng Yao, Zhiyuan Sun, Sara Shabani, Abhay N. Pasupathy, Andrew J. Millis, Cory R. Dean, James C. Hone, Mengkun Liu, D. N. Basov*

{{< details "abstract" >}} abstract: Deep learning (DL) is an emerging analysis tool across sciences andengineering. Encouraged by the successes of DL in revealing quantitative trendsin massive imaging data, we applied this approach to nano-scale deeplysub-diffractional images of propagating polaritonic waves in complex materials.We developed a practical protocol for the rapid regression of images thatquantifies the wavelength and the quality factor of polaritonic waves utilizingthe convolutional neural network (CNN). Using simulated near-field images astraining data, the CNN can be made to simultaneously extract polaritoniccharacteristics and materials parameters in a timescale that is at least threeorders of magnitude faster than common fitting/processing procedures. TheCNN-based analysis was validated by examining the experimental near-fieldimages of charge-transfer plasmon polaritons at Graphene/{\alpha}-RuCl3interfaces. Our work provides a general framework for extracting quantitativeinformation from images generated with a variety of scanning probe methods.
{{< /details >}}

>**_2021-08-10_**

[**A Generalizable Model-and-Data Driven Approach for Open-Set RFF Authentication**](http://arxiv.org/abs/2108.04436v1)

*Renjie Xie, Wei Xu, Yanzhi Chen, Jiabao Yu, Aiqun Hu, Derrick Wing Kwan Ng, A. Lee Swindlehurst*

{{< details "abstract" >}} abstract: Radio-frequency fingerprints~(RFFs) are promising solutions for realizinglow-cost physical layer authentication. Machine learning-based methods havebeen proposed for RFF extraction and discrimination. However, most existingmethods are designed for the closed-set scenario where the set of devices isremains unchanged. These methods can not be generalized to the RFFdiscrimination of unknown devices. To enable the discrimination of RFF fromboth known and unknown devices, we propose a new end-to-end deep learningframework for extracting RFFs from raw received signals. The proposed frameworkcomprises a novel preprocessing module, called neural synchronization~(NS),which incorporates the data-driven learning with signal processing priors as aninductive bias from communication-model based processing. Compared totraditional carrier synchronization techniques, which are static, this moduleestimates offsets by two learnable deep neural networks jointly trained by theRFF extractor. Additionally, a hypersphere representation is proposed tofurther improve the discrimination of RFF. Theoretical analysis shows that sucha data-and-model framework can better optimize the mutual information betweendevice identity and the RFF, which naturally leads to better performance.Experimental results verify that the proposed RFF significantly outperformspurely data-driven DNN-design and existing handcrafted RFF methods in terms ofboth discrimination and network generalizability.
{{< /details >}}

>**_2021-08-09_**

[**Combining a Convolutional Neural Network with Autoencoders to Predict the Survival Chance of COVID-19 Patients**](http://arxiv.org/abs/2104.08954v2)

*Fahime Khozeimeh, Danial Sharifrazi, Navid Hoseini Izadi, Javad Hassannataj Joloudari, Afshin Shoeibi, Roohallah Alizadehsani, Juan M. Gorriz, Sadiq Hussain, Zahra Alizadeh Sani, Hossein Moosaei, Abbas Khosravi, Saeid Nahavandi, Sheikh Mohammed Shariful Islam*

{{< details "abstract" >}} abstract: COVID-19 has caused many deaths worldwide. The automation of the diagnosis ofthis virus is highly desired. Convolutional neural networks (CNNs) have shownoutstanding classification performance on image datasets. To date, it appearsthat COVID computer-aided diagnosis systems based on CNNs and clinicalinformation have not yet been analysed or explored. We propose a novel method,named the CNN-AE, to predict the survival chance of COVID-19 patients using aCNN trained with clinical information. Notably, the required resources toprepare CT images are expensive and limited compared to those required tocollect clinical data, such as blood pressure, liver disease, etc. We evaluatedour method using a publicly available clinical dataset that we collected. Thedataset properties were carefully analysed to extract important features andcompute the correlations of features. A data augmentation procedure based onautoencoders (AEs) was proposed to balance the dataset. The experimentalresults revealed that the average accuracy of the CNN-AE (96.05%) was higherthan that of the CNN (92.49%). To demonstrate the generality of ouraugmentation method, we trained some existing mortality risk prediction methodson our dataset (with and without data augmentation) and compared theirperformances. We also evaluated our method using another dataset for furthergenerality verification. To show that clinical data can be used for COVID-19survival chance prediction, the CNN-AE was compared with multiple pre-traineddeep models that were tuned based on CT images.
{{< /details >}}

[**Identifying Wetland Areas in Historical Maps using Deep Convolutional Neural Networks**](http://arxiv.org/abs/2108.04107v1)

*Niclas Ståhl, Lisa Weimann*

{{< details "abstract" >}} abstract: 1) The local environment and land usages have changed a lot during the pastone hundred years. Historical documents and materials are crucial inunderstanding and following these changes. Historical documents are, therefore,an important piece in the understanding of the impact and consequences of landusage change. This, in turn, is important in the search of restoration projectsthat can be conducted to turn and reduce harmful and unsustainable effectsoriginating from changes in the land-usage.  2) This work extracts information on the historical location and geographicaldistribution of wetlands, from hand-drawn maps. This is achieved by using deeplearning (DL), and more specifically a convolutional neural network (CNN). TheCNN model is trained on a manually pre-labelled dataset on historical wetlandsin the area of J\"onk\"oping county in Sweden. These are all extracted from thehistorical map called "Generalstabskartan".  3) The presented CNN performs well and achieves a $F_1$-score of 0.886 whenevaluated using a 10-fold cross validation over the data. The trained modelsare additionally used to generate a GIS layer of the presumable historicalgeographical distribution of wetlands for the area that is depicted in thesouthern collection in Generalstabskartan, which covers the southern half ofSweden. This GIS layer is released as an open resource and can be freely used.  4) To summarise, the presented results show that CNNs can be a useful tool inthe extraction and digitalisation of non-textual information in historicaldocuments, such as historical maps. A modern GIS material that can be used tofurther understand the past land-usage change is produced within this research.
{{< /details >}}

>**_2021-08-08_**

[**Human-in-the-loop Extraction of Interpretable Concepts in Deep Learning Models**](http://arxiv.org/abs/2108.03738v1)

*Zhenge Zhao, Panpan Xu, Carlos Scheidegger, Liu Ren*

{{< details "abstract" >}} abstract: The interpretation of deep neural networks (DNNs) has become a key topic asmore and more people apply them to solve various problems and making criticaldecisions. Concept-based explanations have recently become a popular approachfor post-hoc interpretation of DNNs. However, identifying human-understandablevisual concepts that affect model decisions is a challenging task that is noteasily addressed with automatic approaches. We present a novelhuman-in-the-loop approach to generate user-defined concepts for modelinterpretation and diagnostics. Central to our proposal is the use of activelearning, where human knowledge and feedback are combined to train a conceptextractor with very little human labeling effort. We integrate this processinto an interactive system, ConceptExtract. Through two case studies, we showhow our approach helps analyze model behavior and extract human-friendlyconcepts for different machine learning tasks and datasets and how to use theseconcepts to understand the predictions, compare model performance and makesuggestions for model refinement. Quantitative experiments show that our activelearning approach can accurately extract meaningful visual concepts. Moreimportantly, by identifying visual concepts that negatively affect modelperformance, we develop the corresponding data augmentation strategy thatconsistently improves model performance.
{{< /details >}}

>**_2021-08-05_**

[**Exploring Structure Consistency for Deep Model Watermarking**](http://arxiv.org/abs/2108.02360v1)

*Jie Zhang, Dongdong Chen, Jing Liao, Han Fang, Zehua Ma, Weiming Zhang, Gang Hua, Nenghai Yu*

{{< details "abstract" >}} abstract: The intellectual property (IP) of Deep neural networks (DNNs) can be easily``stolen'' by surrogate model attack. There has been significant progress insolutions to protect the IP of DNN models in classification tasks. However,little attention has been devoted to the protection of DNNs in image processingtasks. By utilizing consistent invisible spatial watermarks, one recent workfirst considered model watermarking for deep image processing networks anddemonstrated its efficacy in many downstream tasks. Nevertheless, it highlydepends on the hypothesis that the embedded watermarks in the network outputsare consistent. When the attacker uses some common data augmentation attacks(e.g., rotate, crop, and resize) during surrogate model training, it willtotally fail because the underlying watermark consistency is destroyed. Tomitigate this issue, we propose a new watermarking methodology, namely``structure consistency'', based on which a new deep structure-aligned modelwatermarking algorithm is designed. Specifically, the embedded watermarks aredesigned to be aligned with physically consistent image structures, such asedges or semantic regions. Experiments demonstrate that our method is much morerobust than the baseline method in resisting data augmentation attacks formodel IP protection. Besides that, we further test the generalization abilityand robustness of our method to a broader range of circumvention attacks.
{{< /details >}}

>**_2021-07-25_**

[**Identifying the fragment structure of the organic compounds by deeply learning the original NMR data**](http://arxiv.org/abs/2107.11740v1)

*Chongcan Li, Yong Cong, Weihua Deng*

{{< details "abstract" >}} abstract: We preprocess the raw NMR spectrum and extract key characteristic features byusing two different methodologies, called equidistant sampling and peaksampling for subsequent substructure pattern recognition; meanwhile may providethe alternative strategy to address the imbalance issue of the NMR datasetfrequently encountered in dataset collection of statistical modeling andestablish two conventional SVM and KNN models to assess the capability of twofeature selection, respectively. Our results in this study show that the modelsusing the selected features of peak sampling outperform the ones using theother. Then we build the Recurrent Neural Network (RNN) model trained by Data Bcollected from peak sampling. Furthermore, we illustrate the easieroptimization of hyper parameters and the better generalization ability of theRNN deep learning model by comparison with traditional machine learning SVM andKNN models in detail.
{{< /details >}}

>**_2021-07-23_**

[**DeepLesionBrain: Towards a broader deep-learning generalization for multiple sclerosis lesion segmentation**](http://arxiv.org/abs/2012.07950v2)

*Reda Abdellah Kamraoui, Vinh-Thong Ta, Thomas Tourdias, Boris Mansencal, José V Manjon, Pierrick Coupé*

{{< details "abstract" >}} abstract: Recently, segmentation methods based on Convolutional Neural Networks (CNNs)showed promising performance in automatic Multiple Sclerosis (MS) lesionssegmentation. These techniques have even outperformed human experts incontrolled evaluation conditions such as Longitudinal MS Lesion SegmentationChallenge (ISBI Challenge). However state-of-the-art approaches trained toperform well on highly-controlled datasets fail to generalize on clinical datafrom unseen datasets. Instead of proposing another improvement of thesegmentation accuracy, we propose a novel method robust to domain shift andperforming well on unseen datasets, called DeepLesionBrain (DLB). Thisgeneralization property results from three main contributions. First, DLB isbased on a large group of compact 3D CNNs. This spatially distributed strategyensures a robust prediction despite the risk of generalization failure of someindividual networks. Second, DLB includes a new image quality data augmentationto reduce dependency to training data specificity (e.g., acquisition protocol).Finally, to learn a more generalizable representation of MS lesions, we proposea hierarchical specialization learning (HSL). HSL is performed by pre-traininga generic network over the whole brain, before using its weights asinitialization to locally specialized networks. By this end, DLB learns bothgeneric features extracted at global image level and specific featuresextracted at local image level. DLB generalization was validated incross-dataset experiments on MSSEG'16, ISBI challenge, and in-house datasets.During experiments, DLB showed higher segmentation accuracy, bettersegmentation consistency and greater generalization performance compared tostate-of-the-art methods. Therefore, DLB offers a robust framework well-suitedfor clinical practice.
{{< /details >}}

>**_2021-07-22_**

[**WAFFLE: Watermarking in Federated Learning**](http://arxiv.org/abs/2008.07298v3)

*Buse Gul Atli, Yuxi Xia, Samuel Marchal, N. Asokan*

{{< details "abstract" >}} abstract: Federated learning is a distributed learning technique where machine learningmodels are trained on client devices in which the local training data resides.The training is coordinated via a central server which is, typically,controlled by the intended owner of the resulting model. By avoiding the needto transport the training data to the central server, federated learningimproves privacy and efficiency. But it raises the risk of model theft byclients because the resulting model is available on every client device. Evenif the application software used for local training may attempt to preventdirect access to the model, a malicious client may bypass any such restrictionsby reverse engineering the application software. Watermarking is a well-knowndeterrence method against model theft by providing the means for model ownersto demonstrate ownership of their models. Several recent deep neural network(DNN) watermarking techniques use backdooring: training the models withadditional mislabeled data. Backdooring requires full access to the trainingdata and control of the training process. This is feasible when a single partytrains the model in a centralized manner, but not in a federated learningsetting where the training process and training data are distributed amongseveral client devices. In this paper, we present WAFFLE, the first approach towatermark DNN models trained using federated learning. It introduces aretraining step at the server after each aggregation of local models into theglobal model. We show that WAFFLE efficiently embeds a resilient watermark intomodels incurring only negligible degradation in test accuracy (-0.17%), anddoes not require access to training data. We also introduce a novel techniqueto generate the backdoor used as a watermark. It outperforms prior techniques,imposing no communication, and low computational (+3.2%) overhead.
{{< /details >}}

>**_2021-07-16_**

[**Towards Practical Watermark for Deep Neural Networks in Federated Learning**](http://arxiv.org/abs/2105.03167v3)

*Fang-Qi Li, Shi-Lin Wang, Alan Wee-Chung Liew*

{{< details "abstract" >}} abstract: With the wide application of deep neural networks, it is important to verifya host's possession over a deep neural network model and protect the model. Tomeet this goal, various mechanisms have been designed. By embedding extrainformation into a network and revealing it afterward, the watermark becomes acompetitive candidate in proving integrity for deep learning systems. However,concurrent watermarking schemes can hardly be adopted for emerging distributedlearning paradigms that raise extra requirements during the ownershipverification. A spearheading distributed learning paradigm is federatedlearning (FL) where many parties participate in training one single model. Eachauthor participating in the FL should be able to verify its ownershipindependently. Moreover, there are other potential threat and correspondingsecurity requirements under this scenario. To meet those requirements, in thispaper, we demonstrate a watermarking protocol for protecting deep neuralnetworks in the setting of FL. By incorporating the state-of-the-artwatermarking scheme and the cryptological primitive designed for distributedstorage, the protocol meets the need for ownership verification in the FLscenario without violating the privacy for each participant. This work pavesthe way for generalizing watermark as a practical security mechanism forprotecting deep learning models in distributed learning platforms.
{{< /details >}}

>**_2021-07-15_**

[**Algorithmic Concept-based Explainable Reasoning**](http://arxiv.org/abs/2107.07493v1)

*Dobrik Georgiev, Pietro Barbiero, Dmitry Kazhdan, Petar Veličković, Pietro Liò*

{{< details "abstract" >}} abstract: Recent research on graph neural network (GNN) models successfully appliedGNNs to classical graph algorithms and combinatorial optimisation problems.This has numerous benefits, such as allowing applications of algorithms whenpreconditions are not satisfied, or reusing learned models when sufficienttraining data is not available or can't be generated. Unfortunately, a keyhindrance of these approaches is their lack of explainability, since GNNs areblack-box models that cannot be interpreted directly. In this work, we addressthis limitation by applying existing work on concept-based explanations to GNNmodels. We introduce concept-bottleneck GNNs, which rely on a modification tothe GNN readout mechanism. Using three case studies we demonstrate that: (i)our proposed model is capable of accurately learning concepts and extractingpropositional formulas based on the learned concepts for each target class;(ii) our concept-based GNN models achieve comparative performance withstate-of-the-art models; (iii) we can derive global graph concepts, withoutexplicitly providing any supervision on graph-level concepts.
{{< /details >}}

>**_2021-07-08_**

[**Effectiveness of State-of-the-Art Super Resolution Algorithms in Surveillance Environment**](http://arxiv.org/abs/2107.04133v1)

*Muhammad Ali Farooq, Ammar Ali Khan, Ansar Ahmad, Rana Hammad Raza*

{{< details "abstract" >}} abstract: Image Super Resolution (SR) finds applications in areas where images need tobe closely inspected by the observer to extract enhanced information. One suchfocused application is an offline forensic analysis of surveillance feeds. Dueto the limitations of camera hardware, camera pose, limited bandwidth, varyingillumination conditions, and occlusions, the quality of the surveillance feedis significantly degraded at times, thereby compromising monitoring ofbehavior, activities, and other sporadic information in the scene. For theproposed research work, we have inspected the effectiveness of fourconventional yet effective SR algorithms and three deep learning-based SRalgorithms to seek the finest method that executes well in a surveillanceenvironment with limited training data op-tions. These algorithms generate anenhanced resolution output image from a sin-gle low-resolution (LR) inputimage. For performance analysis, a subset of 220 images from six surveillancedatasets has been used, consisting of individuals with varying distances fromthe camera, changing illumination conditions, and complex backgrounds. Theperformance of these algorithms has been evaluated and compared using bothqualitative and quantitative metrics. These SR algo-rithms have also beencompared based on face detection accuracy. By analyzing and comparing theperformance of all the algorithms, a Convolutional Neural Network (CNN) basedSR technique using an external dictionary proved to be best by achieving robustface detection accuracy and scoring optimal quantitative metric results underdifferent surveillance conditions. This is because the CNN layers progressivelylearn more complex features using an external dictionary.
{{< /details >}}

>**_2021-06-28_**

[**Deep Features for training Support Vector Machine**](http://arxiv.org/abs/2104.03488v2)

*Loris Nanni, Stefano Ghidoni, Sheryl Brahnam*

{{< details "abstract" >}} abstract: Features play a crucial role in computer vision. Initially designed to detectsalient elements by means of handcrafted algorithms, features are now oftenlearned by different layers in Convolutional Neural Networks (CNNs). This paperdevelops a generic computer vision system based on features extracted fromtrained CNNs. Multiple learned features are combined into a single structure towork on different image classification tasks. The proposed system wasexperimentally derived by testing several approaches for extracting featuresfrom the inner layers of CNNs and using them as inputs to SVMs that are thencombined by sum rule. Dimensionality reduction techniques are used to reducethe high dimensionality of inner layers. The resulting vision system is shownto significantly boost the performance of standard CNNs across a large anddiverse collection of image data sets. An ensemble of different topologiesusing the same approach obtains state-of-the-art results on a virus data set.
{{< /details >}}

>**_2021-06-20_**

[**Practical Assessment of Generalization Performance Robustness for Deep Networks via Contrastive Examples**](http://arxiv.org/abs/2106.10653v1)

*Xuanyu Wu, Xuhong Li, Haoyi Xiong, Xiao Zhang, Siyu Huang, Dejing Dou*

{{< details "abstract" >}} abstract: Training images with data transformations have been suggested as contrastiveexamples to complement the testing set for generalization performanceevaluation of deep neural networks (DNNs). In this work, we propose a practicalframework ContRE (The word "contre" means "against" or "versus" in French.)that uses Contrastive examples for DNN geneRalization performance Estimation.Specifically, ContRE follows the assumption in contrastive learning that robustDNN models with good generalization performance are capable of extracting aconsistent set of features and making consistent predictions from the sameimage under varying data transformations. Incorporating with a set ofrandomized strategies for well-designed data transformations over the trainingset, ContRE adopts classification errors and Fisher ratios on the generatedcontrastive examples to assess and analyze the generalization performance ofdeep models in complement with a testing set. To show the effectiveness and theefficiency of ContRE, extensive experiments have been done using various DNNmodels on three open source benchmark datasets with thorough ablation studiesand applicability analyses. Our experiment results confirm that (1) behaviorsof deep models on contrastive examples are strongly correlated to what on thetesting set, and (2) ContRE is a robust measure of generalization performancecomplementing to the testing set in various settings.
{{< /details >}}

>**_2021-06-15_**

[**Detect and remove watermark in deep neural networks via generative adversarial networks**](http://arxiv.org/abs/2106.08104v1)

*Haoqi Wang, Mingfu Xue, Shichang Sun, Yushu Zhang, Jian Wang, Weiqiang Liu*

{{< details "abstract" >}} abstract: Deep neural networks (DNN) have achieved remarkable performance in variousfields. However, training a DNN model from scratch requires a lot of computingresources and training data. It is difficult for most individual users toobtain such computing resources and training data. Model copyright infringementis an emerging problem in recent years. For instance, pre-trained models may bestolen or abuse by illegal users without the authorization of the model owner.Recently, many works on protecting the intellectual property of DNN models havebeen proposed. In these works, embedding watermarks into DNN based on backdooris one of the widely used methods. However, when the DNN model is stolen, thebackdoor-based watermark may face the risk of being detected and removed by anadversary. In this paper, we propose a scheme to detect and remove watermark indeep neural networks via generative adversarial networks (GAN). We demonstratethat the backdoor-based DNN watermarks are vulnerable to the proposed GAN-basedwatermark removal attack. The proposed attack method includes two phases. Inthe first phase, we use the GAN and few clean images to detect and reverse thewatermark in the DNN model. In the second phase, we fine-tune the watermarkedDNN based on the reversed backdoor images. Experimental evaluations on theMNIST and CIFAR10 datasets demonstrate that, the proposed method caneffectively remove about 98% of the watermark in DNN models, as the watermarkretention rate reduces from 100% to less than 2% after applying the proposedattack. In the meantime, the proposed attack hardly affects the model'sperformance. The test accuracy of the watermarked DNN on the MNIST and theCIFAR10 datasets drops by less than 1% and 3%, respectively.
{{< /details >}}

[**Robust Out-of-Distribution Detection on Deep Probabilistic Generative Models**](http://arxiv.org/abs/2106.07903v1)

*Jaemoo Choi, Changyeon Yoon, Jeongwoo Bae, Myungjoo Kang*

{{< details "abstract" >}} abstract: Out-of-distribution (OOD) detection is an important task in machine learningsystems for ensuring their reliability and safety. Deep probabilisticgenerative models facilitate OOD detection by estimating the likelihood of adata sample. However, such models frequently assign a suspiciously highlikelihood to a specific outlier. Several recent works have addressed thisissue by training a neural network with auxiliary outliers, which are generatedby perturbing the input data. In this paper, we discover that these approachesfail for certain OOD datasets. Thus, we suggest a new detection metric thatoperates without outlier exposure. We observe that our metric is robust todiverse variations of an image compared to the previous outlier-exposingmethods. Furthermore, our proposed score requires neither auxiliary models noradditional training. Instead, this paper utilizes the likelihood ratiostatistic in a new perspective to extract genuine properties from the givensingle deep probabilistic generative model. We also apply a novel numericalapproximation to enable fast implementation. Finally, we demonstratecomprehensive experiments on various probabilistic generative models and showthat our method achieves state-of-the-art performance.
{{< /details >}}

>**_2021-06-13_**

[**HistoTransfer: Understanding Transfer Learning for Histopathology**](http://arxiv.org/abs/2106.07068v1)

*Yash Sharma, Lubaina Ehsan, Sana Syed, Donald E. Brown*

{{< details "abstract" >}} abstract: Advancement in digital pathology and artificial intelligence has enabled deeplearning-based computer vision techniques for automated disease diagnosis andprognosis. However, WSIs present unique computational and algorithmicchallenges. WSIs are gigapixel-sized, making them infeasible to be useddirectly for training deep neural networks. Hence, for modeling, a two-stageapproach is adopted: Patch representations are extracted first, followed by theaggregation for WSI prediction. These approaches require detailed pixel-levelannotations for training the patch encoder. However, obtaining theseannotations is time-consuming and tedious for medical experts. Transferlearning is used to address this gap and deep learning architecturespre-trained on ImageNet are used for generating patch-level representation.Even though ImageNet differs significantly from histopathology data,pre-trained networks have been shown to perform impressively on histopathologydata. Also, progress in self-supervised and multi-task learning coupled withthe release of multiple histopathology data has led to the release ofhistopathology-specific networks. In this work, we compare the performance offeatures extracted from networks trained on ImageNet and histopathology data.We use an attention pooling network over these extracted features forslide-level aggregation. We investigate if features learned using more complexnetworks lead to gain in performance. We use a simple top-k sampling approachfor fine-tuning framework and study the representation similarity betweenfrozen and fine-tuned networks using Centered Kernel Alignment. Further, toexamine if intermediate block representation is better suited for featureextraction and ImageNet architectures are unnecessarily large forhistopathology, we truncate the blocks of ResNet18 and DenseNet121 and examinethe performance.
{{< /details >}}

>**_2021-06-11_**

[**A Framework to Enhance Generalization of Deep Metric Learning methods using General Discriminative Feature Learning and Class Adversarial Neural Networks**](http://arxiv.org/abs/2106.06420v1)

*Karrar Al-Kaabi, Reza Monsefi, Davood Zabihzadeh*

{{< details "abstract" >}} abstract: Metric learning algorithms aim to learn a distance function that brings thesemantically similar data items together and keeps dissimilar ones at adistance. The traditional Mahalanobis distance learning is equivalent to find alinear projection. In contrast, Deep Metric Learning (DML) methods are proposedthat automatically extract features from data and learn a non-lineartransformation from input space to a semantically embedding space. Recently,many DML methods are proposed focused to enhance the discrimination power ofthe learned metric by providing novel sampling strategies or loss functions.This approach is very helpful when both the training and test examples arecoming from the same set of categories. However, it is less effective in manyapplications of DML such as image retrieval and person-reidentification. Here,the DML should learn general semantic concepts from observed classes and employthem to rank or identify objects from unseen categories. Neglecting thegeneralization ability of the learned representation and just emphasizing tolearn a more discriminative embedding on the observed classes may lead to theoverfitting problem. To address this limitation, we propose a framework toenhance the generalization power of existing DML methods in a Zero-ShotLearning (ZSL) setting by general yet discriminative representation learningand employing a class adversarial neural network. To learn a more generalrepresentation, we propose to employ feature maps of intermediate layers in adeep neural network and enhance their discrimination power through an attentionmechanism. Besides, a class adversarial network is utilized to enforce the deepmodel to seek class invariant features for the DML task. We evaluate our workon widely used machine vision datasets in a ZSL setting.
{{< /details >}}

>**_2021-06-06_**

[**Adaptive Latent Space Tuning for Non-Stationary Distributions**](http://arxiv.org/abs/2105.03584v4)

*Alexander Scheinker, Frederick Cropp, Sergio Paiagua, Daniele Filippetto*

{{< details "abstract" >}} abstract: Powerful deep learning tools, such as convolutional neural networks (CNN),are able to learn the input-output relationships of large complicated systemsdirectly from data. Encoder-decoder deep CNNs are able to extract featuresdirectly from images, mix them with scalar inputs within a generallow-dimensional latent space, and then generate new complex 2D outputs whichrepresent complex physical phenomenon. One important challenge faced by deeplearning methods is large non-stationary systems whose characteristics changequickly with time for which re-training is not feasible. In this paper wepresent a method for adaptive tuning of the low-dimensional latent space ofdeep encoder-decoder style CNNs based on real-time feedback to quicklycompensate for unknown and fast distribution shifts. We demonstrate ourapproach for predicting the properties of a time-varying charged particle beamin a particle accelerator whose components (accelerating electric fields andfocusing magnetic fields) are also quickly changing with time.
{{< /details >}}

>**_2021-06-04_**

[**Ensembles of Convolutional Neural Networks models for pediatric pneumonia diagnosis**](http://arxiv.org/abs/2010.02007v6)

*Helena Liz, Manuel Sánchez-Montañés, Alfredo Tagarro, Sara Domínguez-Rodríguez, Ron Dagan, David Camacho*

{{< details "abstract" >}} abstract: Pneumonia is a lung infection that causes 15% of childhood mortality, over800,000 children under five every year, all over the world. This pathology ismainly caused by viruses or bacteria. X-rays imaging analysis is one of themost used methods for pneumonia diagnosis. These clinical images can beanalyzed using machine learning methods such as convolutional neural networks(CNN), which learn to extract critical features for the classification.However, the usability of these systems is limited in medicine due to the lackof interpretability, because of these models cannot be used to generate anunderstandable explanation (from a human-based perspective), about how theyhave reached those results. Another problem that difficults the impact of thistechnology is the limited amount of labeled data in many medicine domains. Themain contributions of this work are two fold: the first one is the design of anew explainable artificial intelligence (XAI) technique based on combining theindividual heatmaps obtained from each model in the ensemble. This allows toovercome the explainability and interpretability problems of the CNN "blackboxes", highlighting those areas of the image which are more relevant togenerate the classification. The second one is the development of new ensembledeep learning models to classify chest X-rays that allow highly competitiveresults using small datasets for training. We tested our ensemble model using asmall dataset of pediatric X-rays (950 samples) with low quality and anatomicalvariability (which represents one of the biggest challenges). We also testedother strategies such as single CNNs trained from scratch and transfer learningusing CheXNet. Our results show that our ensemble model outperforms thesestrategies obtaining highly competitive results. Finally, we confirmed therobustness of our approach using another pneumonia diagnosis dataset [1].
{{< /details >}}

>**_2021-05-31_**

[**A Protection Method of Trained CNN Model with Secret Key from Unauthorized Access**](http://arxiv.org/abs/2105.14756v1)

*AprilPyone MaungMaung, Hitoshi Kiya*

{{< details "abstract" >}} abstract: In this paper, we propose a novel method for protecting convolutional neuralnetwork (CNN) models with a secret key set so that unauthorized users withoutthe correct key set cannot access trained models. The method enables us toprotect not only from copyright infringement but also the functionality of amodel from unauthorized access without any noticeable overhead. We introducethree block-wise transformations with a secret key set to generate learnabletransformed images: pixel shuffling, negative/positive transformation, and FFXencryption. Protected models are trained by using transformed images. Theresults of experiments with the CIFAR and ImageNet datasets show that theperformance of a protected model was close to that of non-protected models whenthe key set was correct, while the accuracy severely dropped when an incorrectkey set was given. The protected model was also demonstrated to be robustagainst various attacks. Compared with the state-of-the-art model protectionwith passports, the proposed method does not have any additional layers in thenetwork, and therefore, there is no overhead during training and inferenceprocesses.
{{< /details >}}

[**Corpus-Based Paraphrase Detection Experiments and Review**](http://arxiv.org/abs/2106.00145v1)

*Tedo Vrbanec, Ana Mestrovic*

{{< details "abstract" >}} abstract: Paraphrase detection is important for a number of applications, includingplagiarism detection, authorship attribution, question answering, textsummarization, text mining in general, etc. In this paper, we give aperformance overview of various types of corpus-based models, especially deeplearning (DL) models, with the task of paraphrase detection. We report theresults of eight models (LSI, TF-IDF, Word2Vec, Doc2Vec, GloVe, FastText, ELMO,and USE) evaluated on three different public available corpora: MicrosoftResearch Paraphrase Corpus, Clough and Stevenson and Webis Crowd ParaphraseCorpus 2011. Through a great number of experiments, we decided on the mostappropriate approaches for text pre-processing: hyper-parameters, sub-modelselection-where they exist (e.g., Skipgram vs. CBOW), distance measures, andsemantic similarity/paraphrase detection threshold. Our findings and those ofother researchers who have used deep learning models show that DL models arevery competitive with traditional state-of-the-art approaches and havepotential that should be further developed.
{{< /details >}}

>**_2021-05-26_**

[**ViPTT-Net: Video pretraining of spatio-temporal model for tuberculosis type classification from chest CT scans**](http://arxiv.org/abs/2105.12810v1)

*Hasib Zunair, Aimon Rahman, Nabeel Mohammed*

{{< details "abstract" >}} abstract: Pretraining has sparked groundswell of interest in deep learning workflows tolearn from limited data and improve generalization. While this is common for 2Dimage classification tasks, its application to 3D medical imaging tasks likechest CT interpretation is limited. We explore the idea of whether pretraininga model on realistic videos could improve performance rather than training themodel from scratch, intended for tuberculosis type classification from chest CTscans. To incorporate both spatial and temporal features, we develop a hybridconvolutional neural network (CNN) and recurrent neural network (RNN) model,where the features are extracted from each axial slice of the CT scan by a CNN,these sequence of image features are input to a RNN for classification of theCT scan. Our model termed as ViPTT-Net, was trained on over 1300 video clipswith labels of human activities, and then fine-tuned on chest CT scans withlabels of tuberculosis type. We find that pretraining the model on videos leadto better representations and significantly improved model validationperformance from a kappa score of 0.17 to 0.35, especially forunder-represented class samples. Our best method achieved 2nd place in theImageCLEF 2021 Tuberculosis - TBT classification task with a kappa score of0.20 on the final test set with only image information (without using clinicalmeta-data). All codes and models are made available.
{{< /details >}}

>**_2021-05-25_**

[**AutoReCon: Neural Architecture Search-based Reconstruction for Data-free Compression**](http://arxiv.org/abs/2105.12151v1)

*Baozhou Zhu, Peter Hofstee, Johan Peltenburg, Jinho Lee, Zaid Alars*

{{< details "abstract" >}} abstract: Data-free compression raises a new challenge because the original trainingdataset for a pre-trained model to be compressed is not available due toprivacy or transmission issues. Thus, a common approach is to compute areconstructed training dataset before compression. The current reconstructionmethods compute the reconstructed training dataset with a generator byexploiting information from the pre-trained model. However, currentreconstruction methods focus on extracting more information from thepre-trained model but do not leverage network engineering. This work is thefirst to consider network engineering as an approach to design thereconstruction method. Specifically, we propose the AutoReCon method, which isa neural architecture search-based reconstruction method. In the proposedAutoReCon method, the generator architecture is designed automatically giventhe pre-trained model for reconstruction. Experimental results show that usinggenerators discovered by the AutoRecon method always improve the performance ofdata-free compression.
{{< /details >}}

>**_2021-05-23_**

[**DepressionNet: A Novel Summarization Boosted Deep Framework for Depression Detection on Social Media**](http://arxiv.org/abs/2105.10878v1)

*Hamad Zogan, Imran Razzak, Shoaib Jameel, Guandong Xu*

{{< details "abstract" >}} abstract: Twitter is currently a popular online social media platform which allowsusers to share their user-generated content. This publicly-generated user datais also crucial to healthcare technologies because the discovered patternswould hugely benefit them in several ways. One of the applications is inautomatically discovering mental health problems, e.g., depression. Previousstudies to automatically detect a depressed user on online social media havelargely relied upon the user behaviour and their linguistic patterns includinguser's social interactions. The downside is that these models are trained onseveral irrelevant content which might not be crucial towards detecting adepressed user. Besides, these content have a negative impact on the overallefficiency and effectiveness of the model. To overcome the shortcomings in theexisting automatic depression detection methods, we propose a novelcomputational framework for automatic depression detection that initiallyselects relevant content through a hybrid extractive and abstractivesummarization strategy on the sequence of all user tweets leading to a morefine-grained and relevant content. The content then goes to our novel deeplearning framework comprising of a unified learning machinery comprising ofConvolutional Neural Network (CNN) coupled with attention-enhanced GatedRecurrent Units (GRU) models leading to better empirical performance thanexisting strong baselines.
{{< /details >}}

>**_2021-05-21_**

[**Towards Automatic Comparison of Data Privacy Documents: A Preliminary Experiment on GDPR-like Laws**](http://arxiv.org/abs/2105.10117v1)

*Kornraphop Kawintiranon, Yaguang Liu*

{{< details "abstract" >}} abstract: General Data Protection Regulation (GDPR) becomes a standard law for dataprotection in many countries. Currently, twelve countries adopt the regulationand establish their GDPR-like regulation. However, to evaluate the differencesand similarities of these GDPR-like regulations is time-consuming and needs alot of manual effort from legal experts. Moreover, GDPR-like regulations fromdifferent countries are written in their languages leading to a more difficulttask since legal experts who know both languages are essential. In this paper,we investigate a simple natural language processing (NLP) approach to tacklethe problem. We first extract chunks of information from GDPR-like documentsand form structured data from natural language. Next, we use NLP methods tocompare documents to measure their similarity. Finally, we manually label asmall set of data to evaluate our approach. The empirical result shows that theBERT model with cosine similarity outperforms other baselines. Our data andcode are publicly available.
{{< /details >}}

[**TestRank: Bringing Order into Unlabeled Test Instances for Deep Learning Tasks**](http://arxiv.org/abs/2105.10113v1)

*Yu Li, Min Li, Qiuxia Lai, Yannan Liu, Qiang Xu*

{{< details "abstract" >}} abstract: Deep learning (DL) has achieved unprecedented success in a variety of tasks.However, DL systems are notoriously difficult to test and debug due to the lackof explainability of DL models and the huge test input space to cover.Generally speaking, it is relatively easy to collect a massive amount of testdata, but the labeling cost can be quite high. Consequently, it is essential toconduct test selection and label only those selected "high quality"bug-revealing test inputs for test cost reduction.  In this paper, we propose a novel test prioritization technique that bringsorder into the unlabeled test instances according to their bug-revealingcapabilities, namely TestRank. Different from existing solutions, TestRankleverages both intrinsic attributes and contextual attributes of test instanceswhen prioritizing them. To be specific, we first build a similarity graph ontest instances and training samples, and we conduct graph-based semi-supervisedlearning to extract contextual features. Then, for a particular test instance,the contextual features extracted from the graph neural network (GNN) and theintrinsic features obtained with the DL model itself are combined to predictits bug-revealing probability. Finally, TestRank prioritizes unlabeled testinstances in descending order of the above probability value. We evaluate theperformance of TestRank on a variety of image classification datasets.Experimental results show that the debugging efficiency of our methodsignificantly outperforms existing test prioritization techniques.
{{< /details >}}

>**_2021-05-18_**

[**Learning crystal field parameters using convolutional neural networks**](http://arxiv.org/abs/2011.12911v2)

*Noah F. Berthusen, Yuriy Sizyuk, Mathias S. Scheurer, Peter P. Orth*

{{< details "abstract" >}} abstract: We present a deep machine learning algorithm to extract crystal field (CF)Stevens parameters from thermodynamic data of rare-earth magnetic materials.The algorithm employs a two-dimensional convolutional neural network (CNN) thatis trained on magnetization, magnetic susceptibility and specific heat datathat is calculated theoretically within the single-ion approximation andfurther processed using a standard wavelet transformation. We apply the methodto crystal fields of cubic, hexagonal and tetragonal symmetry and for bothinteger and half-integer total angular momentum values $J$ of the ground statemultiplet. We evaluate its performance on both theoretically generatedsynthetic and previously published experimental data on CeAgSb$_2$, PrAgSb$_2$and PrMg$_2$Cu$_9$, and find that it can reliably and accurately extract the CFparameters for all site symmetries and values of $J$ considered. Thisdemonstrates that CNNs provide an unbiased approach to extracting CF parametersthat avoids tedious multi-parameter fitting procedures.
{{< /details >}}

>**_2021-05-13_**

[**High-level Intellectual Property Obfuscation via Decoy Constants**](http://arxiv.org/abs/2105.06122v1)

*Levent Aksoy, Quang-Linh Nguyen, Felipe Almeida, Jaan Raik, Marie-Lise Flottes, Sophie Dupuis, Samuel Pagliarini*

{{< details "abstract" >}} abstract: This paper presents a high-level circuit obfuscation technique to prevent thetheft of intellectual property (IP) of integrated circuits. In particular, ourtechnique protects a class of circuits that relies on constant multiplications,such as filters and neural networks, where the constants themselves are the IPto be protected. By making use of decoy constants and a key-based scheme, areverse engineer adversary at an untrusted foundry is rendered incapable ofdiscerning true constants from decoy constants. The time-multiplexed constantmultiplication (TMCM) block of such circuits, which realizes the multiplicationof an input variable by a constant at a time, is considered as our case studyfor obfuscation. Furthermore, two TMCM design architectures are taken intoaccount; an implementation using a multiplier and a multiplierless shift-addsimplementation. Optimization methods are also applied to reduce the hardwarecomplexity of these architectures. The well-known satisfiability (SAT) andautomatic test pattern generation (ATPG) attacks are used to determine thevulnerability of the obfuscated designs. It is observed that the proposedtechnique incurs small overheads in area, power, and delay that are comparableto the hardware complexity of prominent logic locking methods. Yet, theadvantage of our approach is in the insight that constants -- instead ofarbitrary circuit nodes -- become key-protected.
{{< /details >}}

>**_2021-04-17_**

[**Spirit Distillation: Precise Real-time Semantic Segmentation of Road Scenes with Insufficient Data**](http://arxiv.org/abs/2103.13733v2)

*Zhiyuan Wu, Yu Jiang, Chupeng Cui, Zongmin Yang, Xinhui Xue, Hong Qi*

{{< details "abstract" >}} abstract: Semantic segmentation of road scenes is one of the key technologies forrealizing autonomous driving scene perception, and the effectiveness of deepConvolutional Neural Networks(CNNs) for this task has been demonstrated.State-of-art CNNs for semantic segmentation suffer from excessive computationsas well as large-scale training data requirement. Inspired by the ideas ofFine-tuning-based Transfer Learning (FTT) and feature-based knowledgedistillation, we propose a new knowledge distillation method for cross-domainknowledge transference and efficient data-insufficient network training, namedSpirit Distillation(SD), which allow the student network to mimic the teachernetwork to extract general features, so that a compact and accurate studentnetwork can be trained for real-time semantic segmentation of road scenes.Then, in order to further alleviate the trouble of insufficient data andimprove the robustness of the student, an Enhanced Spirit Distillation (ESD)method is proposed, which commits to exploit a more comprehensive generalfeatures extraction capability by considering images from both the target andthe proximity domains as input. To our knowledge, this paper is a pioneeringwork on the application of knowledge distillation to few-shot learning.Persuasive experiments conducted on Cityscapes semantic segmentation with theprior knowledge transferred from COCO2017 and KITTI demonstrate that ourmethods can train a better student network (mIOU and high-precision accuracyboost by 1.4% and 8.2% respectively, with 78.2% segmentation variance) withonly 41.8% FLOPs (see Fig. 1).
{{< /details >}}

>**_2021-04-01_**

[**Watermarking Graph Neural Networks by Random Graphs**](http://arxiv.org/abs/2011.00512v2)

*Xiangyu Zhao, Hanzhou Wu, Xinpeng Zhang*

{{< details "abstract" >}} abstract: Many learning tasks require us to deal with graph data which contains richrelational information among elements, leading increasing graph neural network(GNN) models to be deployed in industrial products for improving the quality ofservice. However, they also raise challenges to model authentication. It isnecessary to protect the ownership of the GNN models, which motivates us topresent a watermarking method to GNN models in this paper. In the proposedmethod, an Erdos-Renyi (ER) random graph with random node feature vectors andlabels is randomly generated as a trigger to train the GNN to be protectedtogether with the normal samples. During model training, the secret watermarkis embedded into the label predictions of the ER graph nodes. During modelverification, by activating a marked GNN with the trigger ER graph, thewatermark can be reconstructed from the output to verify the ownership. Sincethe ER graph was randomly generated, by feeding it to a non-marked GNN, thelabel predictions of the graph nodes are random, resulting in a low false alarmrate (of the proposed work). Experimental results have also shown that, theperformance of a marked GNN on its original task will not be impaired.Moreover, it is robust against model compression and fine-tuning, which hasshown the superiority and applicability.
{{< /details >}}

>**_2021-03-30_**

[**Learnable Graph Matching: Incorporating Graph Partitioning with Deep Feature Learning for Multiple Object Tracking**](http://arxiv.org/abs/2103.16178v1)

*Jiawei He, Zehao Huang, Naiyan Wang, Zhaoxiang Zhang*

{{< details "abstract" >}} abstract: Data association across frames is at the core of Multiple Object Tracking(MOT) task. This problem is usually solved by a traditional graph-basedoptimization or directly learned via deep learning. Despite their popularity,we find some points worth studying in current paradigm: 1) Existing methodsmostly ignore the context information among tracklets and intra-framedetections, which makes the tracker hard to survive in challenging cases likesevere occlusion. 2) The end-to-end association methods solely rely on the datafitting power of deep neural networks, while they hardly utilize the advantageof optimization-based assignment methods. 3) The graph-based optimizationmethods mostly utilize a separate neural network to extract features, whichbrings the inconsistency between training and inference. Therefore, in thispaper we propose a novel learnable graph matching method to address theseissues. Briefly speaking, we model the relationships between tracklets and theintra-frame detections as a general undirected graph. Then the associationproblem turns into a general graph matching between tracklet graph anddetection graph. Furthermore, to make the optimization end-to-enddifferentiable, we relax the original graph matching into continuous quadraticprogramming and then incorporate the training of it into a deep graph networkwith the help of the implicit function theorem. Lastly, our method GMTracker,achieves state-of-the-art performance on several standard MOT datasets. Ourcode will be available at https://github.com/jiaweihe1996/GMTracker .
{{< /details >}}

>**_2021-03-24_**

[**Transfer Learning for Piano Sustain-Pedal Detection**](http://arxiv.org/abs/2103.13219v1)

*Beici Liang, György Fazekas, Mark Sandler*

{{< details "abstract" >}} abstract: Detecting piano pedalling techniques in polyphonic music remains achallenging task in music information retrieval. While other piano-relatedtasks, such as pitch estimation and onset detection, have seen improvementthrough applying deep learning methods, little work has been done to developdeep learning models to detect playing techniques. In this paper, we propose atransfer learning approach for the detection of sustain-pedal techniques, whichare commonly used by pianists to enrich the sound. In the source task, aconvolutional neural network (CNN) is trained for learning spectral andtemporal contexts when the sustain pedal is pressed using a large datasetgenerated by a physical modelling virtual instrument. The CNN is designed andexperimented through exploiting the knowledge of piano acoustics and physics.This can achieve an accuracy score of 0.98 in the validation results. In thetarget task, the knowledge learned from the synthesised data can be transferredto detect the sustain pedal in acoustic piano recordings. A concatenatedfeature vector using the activations of the trained convolutional layers isextracted from the recordings and classified into frame-wise pedal press orrelease. We demonstrate the effectiveness of our method in acoustic pianorecordings of Chopin's music. From the cross-validation results, the proposedtransfer learning method achieves an average F-measure of 0.89 and an overallperformance of 0.84 obtained using the micro-averaged F-measure. These resultsoutperform applying the pre-trained CNN model directly or the model with afine-tuned last layer.
{{< /details >}}

>**_2021-03-23_**

[**Watermark Faker: Towards Forgery of Digital Image Watermarking**](http://arxiv.org/abs/2103.12489v1)

*Ruowei Wang, Chenguo Lin, Qijun Zhao, Feiyu Zhu*

{{< details "abstract" >}} abstract: Digital watermarking has been widely used to protect the copyright andintegrity of multimedia data. Previous studies mainly focus on designingwatermarking techniques that are robust to attacks of destroying the embeddedwatermarks. However, the emerging deep learning based image generationtechnology raises new open issues that whether it is possible to generate fakewatermarked images for circumvention. In this paper, we make the first attemptto develop digital image watermark fakers by using generative adversariallearning. Suppose that a set of paired images of original and watermarkedimages generated by the targeted watermarker are available, we use them totrain a watermark faker with U-Net as the backbone, whose input is an originalimage, and after a domain-specific preprocessing, it outputs a fake watermarkedimage. Our experiments show that the proposed watermark faker can effectivelycrack digital image watermarkers in both spatial and frequency domains,suggesting the risk of such forgery attacks.
{{< /details >}}

>**_2021-03-19_**

[**MetaLabelNet: Learning to Generate Soft-Labels from Noisy-Labels**](http://arxiv.org/abs/2103.10869v1)

*Görkem Algan, Ilkay Ulusoy*

{{< details "abstract" >}} abstract: Real-world datasets commonly have noisy labels, which negatively affects theperformance of deep neural networks (DNNs). In order to address this problem,we propose a label noise robust learning algorithm, in which the baseclassifier is trained on soft-labels that are produced according to ameta-objective. In each iteration, before conventional training, themeta-objective reshapes the loss function by changing soft-labels, so thatresulting gradient updates would lead to model parameters with minimum loss onmeta-data. Soft-labels are generated from extracted features of data instances,and the mapping function is learned by a single layer perceptron (SLP) network,which is called MetaLabelNet. Following, base classifier is trained by usingthese generated soft-labels. These iterations are repeated for each batch oftraining data. Our algorithm uses a small amount of clean data as meta-data,which can be obtained effortlessly for many cases. We perform extensiveexperiments on benchmark datasets with both synthetic and real-world noises.Results show that our approach outperforms existing baselines.
{{< /details >}}

>**_2021-03-17_**

[**ScoreGAN: A Fraud Review Detector based on Multi Task Learning of Regulated GAN with Data Augmentation**](http://arxiv.org/abs/2006.06561v2)

*Saeedreza Shehnepoor, Roberto Togneri, Wei Liu, Mohammed Bennamoun*

{{< details "abstract" >}} abstract: The promising performance of Deep Neural Networks (DNNs) in textclassification, has attracted researchers to use them for fraud reviewdetection. However, the lack of trusted labeled data has limited theperformance of the current solutions in detecting fraud reviews. The GenerativeAdversarial Network (GAN) as a semi-supervised method has demonstrated to beeffective for data augmentation purposes. The state-of-the-art solutionsutilize GANs to overcome the data scarcity problem. However, they fail toincorporate the behavioral clues in fraud generation. Additionally,state-of-the-art approaches overlook the possible bot-generated reviews in thedataset. Finally, they also suffer from a common limitation in scalability andstability of the GAN, slowing down the training procedure. In this work, wepropose ScoreGAN for fraud review detection that makes use of both review textand review rating scores in the generation and detection process. Scores areincorporated through Information Gain Maximization (IGM) into the loss functionfor three reasons. One is to generate score-correlated reviews based on thescores given to the generator. Second, the generated reviews are employed totrain the discriminator, so the discriminator can correctly label the possiblebot-generated reviews through joint representations learned from theconcatenation of GLobal Vector for Word representation (GLoVe) extracted fromthe text and the score. Finally, it can be used to improve the stability andscalability of the GAN. Results show that the proposed framework outperformedthe existing state-of-the-art framework, namely FakeGAN, in terms of AP by 7\%,and 5\% on the Yelp and TripAdvisor datasets, respectively.
{{< /details >}}

>**_2021-03-12_**

[**An Overview of Deep-Learning-Based Audio-Visual Speech Enhancement and Separation**](http://arxiv.org/abs/2008.09586v2)

*Daniel Michelsanti, Zheng-Hua Tan, Shi-Xiong Zhang, Yong Xu, Meng Yu, Dong Yu, Jesper Jensen*

{{< details "abstract" >}} abstract: Speech enhancement and speech separation are two related tasks, whose purposeis to extract either one or more target speech signals, respectively, from amixture of sounds generated by several sources. Traditionally, these tasks havebeen tackled using signal processing and machine learning techniques applied tothe available acoustic signals. Since the visual aspect of speech isessentially unaffected by the acoustic environment, visual information from thetarget speakers, such as lip movements and facial expressions, has also beenused for speech enhancement and speech separation systems. In order toefficiently fuse acoustic and visual information, researchers have exploitedthe flexibility of data-driven approaches, specifically deep learning,achieving strong performance. The ceaseless proposal of a large number oftechniques to extract features and fuse multimodal information has highlightedthe need for an overview that comprehensively describes and discussesaudio-visual speech enhancement and separation based on deep learning. In thispaper, we provide a systematic survey of this research topic, focusing on themain elements that characterise the systems in the literature: acousticfeatures; visual features; deep learning methods; fusion techniques; trainingtargets and objective functions. In addition, we review deep-learning-basedmethods for speech reconstruction from silent videos and audio-visual soundsource separation for non-speech signals, since these methods can be more orless directly applied to audio-visual speech enhancement and separation.Finally, we survey commonly employed audio-visual speech datasets, given theircentral role in the development of data-driven approaches, and evaluationmethods, because they are generally used to compare different systems anddetermine their performance.
{{< /details >}}

>**_2021-03-11_**

[**Intraclass clustering: an implicit learning ability that regularizes DNNs**](http://arxiv.org/abs/2103.06733v1)

*Carbonnelle Simon, Christophe De Vleeschouwer*

{{< details "abstract" >}} abstract: Several works have shown that the regularization mechanisms underlying deepneural networks' generalization performances are still poorly understood. Inthis paper, we hypothesize that deep neural networks are regularized throughtheir ability to extract meaningful clusters among the samples of a class. Thisconstitutes an implicit form of regularization, as no explicit trainingmechanisms or supervision target such behaviour. To support our hypothesis, wedesign four different measures of intraclass clustering, based on the neuron-and layer-level representations of the training data. We then show that thesemeasures constitute accurate predictors of generalization performance acrossvariations of a large set of hyperparameters (learning rate, batch size,optimizer, weight decay, dropout rate, data augmentation, network depth andwidth).
{{< /details >}}

>**_2021-03-09_**

[**Robust Black-box Watermarking for Deep NeuralNetwork using Inverse Document Frequency**](http://arxiv.org/abs/2103.05590v1)

*Mohammad Mehdi Yadollahi, Farzaneh Shoeleh, Sajjad Dadkhah, Ali A. Ghorbani*

{{< details "abstract" >}} abstract: Deep learning techniques are one of the most significant elements of anyArtificial Intelligence (AI) services. Recently, these Machine Learning (ML)methods, such as Deep Neural Networks (DNNs), presented exceptional achievementin implementing human-level capabilities for various predicaments, such asNatural Processing Language (NLP), voice recognition, and image processing,etc. Training these models are expensive in terms of computational power andthe existence of enough labelled data. Thus, ML-based models such as DNNsestablish genuine business value and intellectual property (IP) for theirowners. Therefore the trained models need to be protected from any adversaryattacks such as illegal redistribution, reproducing, and derivation.Watermarking can be considered as an effective technique for securing a DNNmodel. However, so far, most of the watermarking algorithm focuses onwatermarking the DNN by adding noise to an image. To this end, we propose aframework for watermarking a DNN model designed for a textual domain. Thewatermark generation scheme provides a secure watermarking method by combiningTerm Frequency (TF) and Inverse Document Frequency (IDF) of a particular word.The proposed embedding procedure takes place in the model's training time,making the watermark verification stage straightforward by sending thewatermarked document to the trained model. The experimental results show thatwatermarked models have the same accuracy as the original ones. The proposedframework accurately verifies the ownership of all surrogate models withoutimpairing the performance. The proposed algorithm is robust against well-knownattacks such as parameter pruning and brute force attack.
{{< /details >}}

>**_2021-02-20_**

[**Spotting Silent Buffer Overflows in Execution Trace through Graph Neural Network Assisted Data Flow Analysis**](http://arxiv.org/abs/2102.10452v1)

*Zhilong Wang, Li Yu, Suhang Wang, Peng Liu*

{{< details "abstract" >}} abstract: A software vulnerability could be exploited without any visible symptoms.When no source code is available, although such silent program executions couldcause very serious damage, the general problem of analyzing silent yet harmfulexecutions is still an open problem. In this work, we propose a graph neuralnetwork (GNN) assisted data flow analysis method for spotting silent bufferoverflows in execution traces. The new method combines a novel graph structure(denoted DFG+) beyond data-flow graphs, a tool to extract {\tt DFG+} fromexecution traces, and a modified Relational Graph Convolutional Network as theGNN model to be trained. The evaluation results show that a well-trained modelcan be used to analyze vulnerabilities in execution traces (ofpreviously-unseen programs) without support of any source code. Our modelachieves 94.39\% accuracy on the test data and successfully locates 29 out of30 real-world silent buffer overflow vulnerabilities. Leveraging deep learning,the proposed method is, to our best knowledge, the first general-purposeanalysis method for silent buffer overflows. It is also the first method tospot silent buffer overflows in global variables, stack variables, or heapvariables without crossing the boundary of allocated chunks.
{{< /details >}}

>**_2021-02-19_**

[**Artificially Synthesising Data for Audio Classification and Segmentation to Improve Speech and Music Detection in Radio Broadcast**](http://arxiv.org/abs/2102.09959v1)

*Satvik Venkatesh, David Moffat, Alexis Kirke, Gözel Shakeri, Stephen Brewster, Jörg Fachner, Helen Odell-Miller, Alex Street, Nicolas Farina, Sube Banerjee, Eduardo Reck Miranda*

{{< details "abstract" >}} abstract: Segmenting audio into homogeneous sections such as music and speech helps usunderstand the content of audio. It is useful as a pre-processing step toindex, store, and modify audio recordings, radio broadcasts and TV programmes.Deep learning models for segmentation are generally trained on copyrightedmaterial, which cannot be shared. Annotating these datasets is time-consumingand expensive and therefore, it significantly slows down research progress. Inthis study, we present a novel procedure that artificially synthesises datathat resembles radio signals. We replicate the workflow of a radio DJ in mixingaudio and investigate parameters like fade curves and audio ducking. We traineda Convolutional Recurrent Neural Network (CRNN) on this synthesised data andoutperformed state-of-the-art algorithms for music-speech detection. This paperdemonstrates the data synthesis procedure as a highly effective technique togenerate large datasets to train deep neural networks for audio segmentation.
{{< /details >}}

>**_2021-02-18_**

[**Testing Lotka's Law and Pattern of Author Productivity in the Scholarly Publications of Artificial Intelligence**](http://arxiv.org/abs/2102.09182v1)

*Muneer Ahmad, Dr M Sadik Batcha, S Roselin Jahina*

{{< details "abstract" >}} abstract: Artificial intelligence has changed our day to day life in multitude ways. AItechnology is rearing itself as a driving force to be reckoned with in thelargest industries in the world. AI has already engulfed our educationalsystem, our businesses and our financial establishments. The future is definitethat machines with artificial intelligence will soon be captivating overtrained manual work that now is mostly cared by humans. Machines can carry outhuman-like tasks by new inputs as artificial intelligence makes it possible formachines to learn from experience. AI data from web of science database from2008 to 2017 have been mapped to depict the average growth rate, relativegrowth rate, contribution made by authors in the view of research productivity,authorship pattern and collaboration of AI literature. The Lotka's law onauthorship productivity of AI literature has been tested to confirm theapplicability of the law to the present data set. A K-S test was applied tomeasure the degree of agreement between the distribution of the observed set ofdata against the inverse general power relationship and the theoretical valueof {\alpha} =2. It is found that the inverse square law of Lotka follow assuch.
{{< /details >}}

>**_2021-02-14_**

[**Evolutionary Trigger Set Generation for DNN Black-Box Watermarking**](http://arxiv.org/abs/1906.04411v2)

*Jia Guo, Miodrag Potkonjak*

{{< details "abstract" >}} abstract: The commercialization of deep learning creates a compelling need forintellectual property (IP) protection. Deep neural network (DNN) watermarkinghas been proposed as a promising tool to help model owners prove ownership andfight piracy. A popular approach of watermarking is to train a DNN to recognizeimages with certain \textit{trigger} patterns. In this paper, we propose anovel evolutionary algorithm-based method to generate and optimize triggerpatterns. Our method brings a siginificant reduction in false positive rates,leading to compelling proof of ownership. At the same time, it maintains therobustness of the watermark against attacks. We compare our method with theprior art and demonstrate its effectiveness on popular models and datasets.
{{< /details >}}

>**_2021-02-03_**

[**Memorization vs. Generalization: Quantifying Data Leakage in NLP Performance Evaluation**](http://arxiv.org/abs/2102.01818v1)

*Aparna Elangovan, Jiayuan He, Karin Verspoor*

{{< details "abstract" >}} abstract: Public datasets are often used to evaluate the efficacy and generalizabilityof state-of-the-art methods for many tasks in natural language processing(NLP). However, the presence of overlap between the train and test datasets canlead to inflated results, inadvertently evaluating the model's ability tomemorize and interpreting it as the ability to generalize. In addition, suchdata sets may not provide an effective indicator of the performance of thesemethods in real world scenarios. We identify leakage of training data into testdata on several publicly available datasets used to evaluate NLP tasks,including named entity recognition and relation extraction, and study them toassess the impact of that leakage on the model's ability to memorize versusgeneralize.
{{< /details >}}

>**_2021-01-27_**

[**A Scalable Multilabel Classification to Deploy Deep Learning Architectures For Edge Devices**](http://arxiv.org/abs/1911.02098v3)

*Tolulope A. Odetola, Ogheneuriri Oderhohwo, Syed Rafay Hasan*

{{< details "abstract" >}} abstract: Convolution Neural Networks (CNN) have performed well in many applicationssuch as object detection, pattern recognition, video surveillance and so on.CNN carryout feature extraction on labelled data to perform classification.Multi-label classification assigns more than one label to a particular datasample in a data set. In multi-label classification, properties of a data pointthat are considered to be mutually exclusive are classified. However, existingmulti-label classification requires some form of data pre-processing thatinvolves image training data cropping or image tiling. The computation andmemory requirement of these multi-label CNN models makes their deployment onedge devices challenging. In this paper, we propose a methodology that solvesthis problem by extending the capability of existing multi-label classificationand provide models with lower latency that requires smaller memory size whendeployed on edge devices. We make use of a single CNN model designed withmultiple loss layers and multiple accuracy layers. This methodology is testedon state-of-the-art deep learning algorithms such as AlexNet, GoogleNet andSqueezeNet using the Stanford Cars Dataset and deployed on Raspberry Pi3. Fromthe results the proposed methodology achieves comparable accuracy with 1.8xless MACC operation, 0.97x reduction in latency and 0.5x, 0.84x and 0.97xreduction in size for the generated AlexNet, GoogleNet and SqueezeNet CNNmodels respectively when compared to conventional ways of achieving multi-labelclassification like hard-coding multi-label instances into single labels. Themethodology also yields CNN models that achieve 50\% less MACC operations, 50%reduction in latency and size of generated versions of AlexNet, GoogleNet andSqueezeNet respectively when compared to conventional ways using 2 differentsingle-labelled models to achieve multi-label classification.
{{< /details >}}

>**_2021-01-19_**

[**Analysis and evaluation of Deep Learning based Super-Resolution algorithms to improve performance in Low-Resolution Face Recognition**](http://arxiv.org/abs/2101.10845v1)

*Angelo G. Menezes*

{{< details "abstract" >}} abstract: Surveillance scenarios are prone to several problems since they usuallyinvolve low-resolution footage, and there is no control of how far the subjectsmay be from the camera in the first place. This situation is suitable for theapplication of upsampling (super-resolution) algorithms since they may be ableto recover the discriminant properties of the subjects involved. While generalsuper-resolution approaches were proposed to enhance image quality forhuman-level perception, biometrics super-resolution methods seek the best"computer perception" version of the image since their focus is on improvingautomatic recognition performance. Convolutional neural networks and deeplearning algorithms, in general, have been applied to computer vision tasks andare now state-of-the-art for several sub-domains, including imageclassification, restoration, and super-resolution. However, no work hasevaluated the effects that the latest proposed super-resolution methods mayhave upon the accuracy and face verification performance in low-resolution"in-the-wild" data. This project aimed at evaluating and adapting differentdeep neural network architectures for the task of face super-resolution drivenby face recognition performance in real-world low-resolution images. Theexperimental results in a real-world surveillance and attendance datasetsshowed that general super-resolution architectures might enhance faceverification performance of deep neural networks trained on high-resolutionfaces. Also, since neural networks are function approximators and can betrained based on specific objective functions, the use of a customized lossfunction optimized for feature extraction showed promising results forrecovering discriminant features in low-resolution face images.
{{< /details >}}

>**_2021-01-10_**

[**Activity Recognition with Moving Cameras and Few Training Examples: Applications for Detection of Autism-Related Headbanging**](http://arxiv.org/abs/2101.03478v1)

*Peter Washington, Aaron Kline, Onur Cezmi Mutlu, Emilie Leblanc, Cathy Hou, Nate Stockham, Kelley Paskov, Brianna Chrisman, Dennis P. Wall*

{{< details "abstract" >}} abstract: Activity recognition computer vision algorithms can be used to detect thepresence of autism-related behaviors, including what are termed "restricted andrepetitive behaviors", or stimming, by diagnostic instruments. The limited datathat exist in this domain are usually recorded with a handheld camera which canbe shaky or even moving, posing a challenge for traditional featurerepresentation approaches for activity detection which mistakenly capture thecamera's motion as a feature. To address these issues, we first document theadvantages and limitations of current feature representation techniques foractivity recognition when applied to head banging detection. We then propose afeature representation consisting exclusively of head pose keypoints. We createa computer vision classifier for detecting head banging in home videos using atime-distributed convolutional neural network (CNN) in which a single CNNextracts features from each frame in the input sequence, and these extractedfeatures are fed as input to a long short-term memory (LSTM) network. On thebinary task of predicting head banging and no head banging within videos fromthe Self Stimulatory Behaviour Dataset (SSBD), we reach a mean F1-score of90.77% using 3-fold cross validation (with individual fold F1-scores of 83.3%,89.0%, and 100.0%) when ensuring that no child who appeared in the train setwas in the test set for all folds. This work documents a successful techniquefor training a computer vision classifier which can detect human motion withfew training examples and even when the camera recording the source clips isunstable. The general methods described here can be applied by designers anddevelopers of interactive systems towards other human motion and poseclassification problems used in mobile and ubiquitous interactive systems.
{{< /details >}}

>**_2021-01-08_**

[**DeepPoison: Feature Transfer Based Stealthy Poisoning Attack**](http://arxiv.org/abs/2101.02562v2)

*Jinyin Chen, Longyuan Zhang, Haibin Zheng, Xueke Wang, Zhaoyan Ming*

{{< details "abstract" >}} abstract: Deep neural networks are susceptible to poisoning attacks by purposelypolluted training data with specific triggers. As existing episodes mainlyfocused on attack success rate with patch-based samples, defense algorithms caneasily detect these poisoning samples. We propose DeepPoison, a noveladversarial network of one generator and two discriminators, to address thisproblem. Specifically, the generator automatically extracts the target class'hidden features and embeds them into benign training samples. One discriminatorcontrols the ratio of the poisoning perturbation. The other discriminator worksas the target model to testify the poisoning effects. The novelty of DeepPoisonlies in that the generated poisoned training samples are indistinguishable fromthe benign ones by both defensive methods and manual visual inspection, andeven benign test samples can achieve the attack. Extensive experiments haveshown that DeepPoison can achieve a state-of-the-art attack success rate, ashigh as 91.74%, with only 7% poisoned samples on publicly available datasetsLFW and CASIA. Furthermore, we have experimented with high-performance defensealgorithms such as autodecoder defense and DBSCAN cluster detection and showedthe resilience of DeepPoison.
{{< /details >}}

>**_2021-01-07_**

[**Combining pretrained CNN feature extractors to enhance clustering of complex natural images**](http://arxiv.org/abs/2101.02767v1)

*Joris Guerin, Stephane Thiery, Eric Nyiri, Olivier Gibaru, Byron Boots*

{{< details "abstract" >}} abstract: Recently, a common starting point for solving complex unsupervised imageclassification tasks is to use generic features, extracted with deepConvolutional Neural Networks (CNN) pretrained on a large and versatile dataset(ImageNet). However, in most research, the CNN architecture for featureextraction is chosen arbitrarily, without justification. This paper aims atproviding insight on the use of pretrained CNN features for image clustering(IC). First, extensive experiments are conducted and show that, for a givendataset, the choice of the CNN architecture for feature extraction has a hugeimpact on the final clustering. These experiments also demonstrate that properextractor selection for a given IC task is difficult. To solve this issue, wepropose to rephrase the IC problem as a multi-view clustering (MVC) problemthat considers features extracted from different architectures as different"views" of the same data. This approach is based on the assumption thatinformation contained in the different CNN may be complementary, even whenpretrained on the same data. We then propose a multi-input neural networkarchitecture that is trained end-to-end to solve the MVC problem effectively.This approach is tested on nine natural image datasets, and producesstate-of-the-art results for IC.
{{< /details >}}

[**Practical Blind Membership Inference Attack via Differential Comparisons**](http://arxiv.org/abs/2101.01341v2)

*Bo Hui, Yuchen Yang, Haolin Yuan, Philippe Burlina, Neil Zhenqiang Gong, Yinzhi Cao*

{{< details "abstract" >}} abstract: Membership inference (MI) attacks affect user privacy by inferring whethergiven data samples have been used to train a target learning model, e.g., adeep neural network. There are two types of MI attacks in the literature, i.e.,these with and without shadow models. The success of the former heavily dependson the quality of the shadow model, i.e., the transferability between theshadow and the target; the latter, given only blackbox probing access to thetarget model, cannot make an effective inference of unknowns, compared with MIattacks using shadow models, due to the insufficient number of qualifiedsamples labeled with ground truth membership information.  In this paper, we propose an MI attack, called BlindMI, which probes thetarget model and extracts membership semantics via a novel approach, calleddifferential comparison. The high-level idea is that BlindMI first generates adataset with nonmembers via transforming existing samples into new samples, andthen differentially moves samples from a target dataset to the generated,non-member set in an iterative manner. If the differential move of a sampleincreases the set distance, BlindMI considers the sample as non-member and viceversa.  BlindMI was evaluated by comparing it with state-of-the-art MI attackalgorithms. Our evaluation shows that BlindMI improves F1-score by nearly 20%when compared to state-of-the-art on some datasets, such as Purchase-50 andBirds-200, in the blind setting where the adversary does not know the targetmodel's architecture and the target dataset's ground truth labels. We also showthat BlindMI can defeat state-of-the-art defenses.
{{< /details >}}

>**_2020-12-29_**

[**On Deep Learning Techniques to Boost Monocular Depth Estimation for Autonomous Navigation**](http://arxiv.org/abs/2010.06626v2)

*Raul de Queiroz Mendes, Eduardo Godinho Ribeiro, Nicolas dos Santos Rosa, Valdir Grassi Jr*

{{< details "abstract" >}} abstract: Inferring the depth of images is a fundamental inverse problem within thefield of Computer Vision since depth information is obtained through 2D images,which can be generated from infinite possibilities of observed real scenes.Benefiting from the progress of Convolutional Neural Networks (CNNs) to explorestructural features and spatial image information, Single Image DepthEstimation (SIDE) is often highlighted in scopes of scientific andtechnological innovation, as this concept provides advantages related to itslow implementation cost and robustness to environmental conditions. In thecontext of autonomous vehicles, state-of-the-art CNNs optimize the SIDE task byproducing high-quality depth maps, which are essential during the autonomousnavigation process in different locations. However, such networks are usuallysupervised by sparse and noisy depth data, from Light Detection and Ranging(LiDAR) laser scans, and are carried out at high computational cost, requiringhigh-performance Graphic Processing Units (GPUs). Therefore, we propose a newlightweight and fast supervised CNN architecture combined with novel featureextraction models which are designed for real-world autonomous navigation. Wealso introduce an efficient surface normals module, jointly with a simplegeometric 2.5D loss function, to solve SIDE problems. We also innovate byincorporating multiple Deep Learning techniques, such as the use ofdensification algorithms and additional semantic, surface normals and depthinformation to train our framework. The method introduced in this work focuseson robotic applications in indoor and outdoor environments and its results areevaluated on the competitive and publicly available NYU Depth V2 and KITTIDepth datasets.
{{< /details >}}

>**_2020-12-22_**

[**A Robust and Efficient Deep Learning Method for Dynamical Mass Measurements of Galaxy Clusters**](http://arxiv.org/abs/1902.05950v2)

*Matthew Ho, Markus Michael Rau, Michelle Ntampaka, Arya Farahi, Hy Trac, Barnabas Poczos*

{{< details "abstract" >}} abstract: We demonstrate the ability of convolutional neural networks (CNNs) tomitigate systematics in the virial scaling relation and produce dynamical massestimates of galaxy clusters with remarkably low bias and scatter. We presenttwo models, CNN$_\mathrm{1D}$ and CNN$_\mathrm{2D}$, which leverage this deeplearning tool to infer cluster masses from distributions of member galaxydynamics. Our first model, CNN$_\text{1D}$, infers cluster mass directly fromthe distribution of member galaxy line-of-sight velocities. Our second model,CNN$_\text{2D}$, extends the input space of CNN$_\text{1D}$ to learn on thejoint distribution of galaxy line-of-sight velocities and projected radialdistances. We train each model as a regression over cluster mass using alabeled catalog of realistic mock cluster observations generated from theMultiDark simulation and UniverseMachine catalog. We then evaluate theperformance of each model on an independent set of mock observations selectedfrom the same simulated catalog. The CNN models produce cluster masspredictions with lognormal residuals of scatter as low as $0.132$ dex, greaterthan a factor of 2 improvement over the classical $M$-$\sigma$ power-lawestimator. Furthermore, the CNN model reduces prediction scatter relative tosimilar machine learning approaches by up to $17\%$ while executing indrastically shorter training and evaluation times (by a factor of 30) andproducing considerably more robust mass predictions (improving predictionstability under variations in galaxy sampling rate by $30\%$).
{{< /details >}}

>**_2020-12-20_**

[**Color Channel Perturbation Attacks for Fooling Convolutional Neural Networks and A Defense Against Such Attacks**](http://arxiv.org/abs/2012.14456v1)

*Jayendra Kantipudi, Shiv Ram Dubey, Soumendu Chakraborty*

{{< details "abstract" >}} abstract: The Convolutional Neural Networks (CNNs) have emerged as a very powerful datadependent hierarchical feature extraction method. It is widely used in severalcomputer vision problems. The CNNs learn the important visual features fromtraining samples automatically. It is observed that the network overfits thetraining samples very easily. Several regularization methods have been proposedto avoid the overfitting. In spite of this, the network is sensitive to thecolor distribution within the images which is ignored by the existingapproaches. In this paper, we discover the color robustness problem of CNN byproposing a Color Channel Perturbation (CCP) attack to fool the CNNs. In CCPattack new images are generated with new channels created by combining theoriginal channels with the stochastic weights. Experiments were carried outover widely used CIFAR10, Caltech256 and TinyImageNet datasets in the imageclassification framework. The VGG, ResNet and DenseNet models are used to testthe impact of the proposed attack. It is observed that the performance of theCNNs degrades drastically under the proposed CCP attack. Result show the effectof the proposed simple CCP attack over the robustness of the CNN trained model.The results are also compared with existing CNN fooling approaches to evaluatethe accuracy drop. We also propose a primary defense mechanism to this problemby augmenting the training dataset with the proposed CCP attack. Thestate-of-the-art performance using the proposed solution in terms of the CNNrobustness under CCP attack is observed in the experiments. The code is madepublicly available at\url{https://github.com/jayendrakantipudi/Color-Channel-Perturbation-Attack}.
{{< /details >}}

>**_2020-12-14_**

[**The Open Brands Dataset: Unified brand detection and recognition at scale**](http://arxiv.org/abs/2012.07350v1)

*Xuan Jin, Wei Su, Rong Zhang, Yuan He, Hui Xue*

{{< details "abstract" >}} abstract: Intellectual property protection(IPP) have received more and more attentionrecently due to the development of the global e-commerce platforms. brandrecognition plays a significant role in IPP. Recent studies for brandrecognition and detection are based on small-scale datasets that are notcomprehensive enough when exploring emerging deep learning techniques.Moreover, it is challenging to evaluate the true performance of brand detectionmethods in realistic and open scenes. In order to tackle these problems, wefirst define the special issues of brand detection and recognition comparedwith generic object detection. Second, a novel brands benchmark called "OpenBrands" is established. The dataset contains 1,437,812 images which have brandsand 50,000 images without any brand. The part with brands in Open Brandscontains 3,113,828 instances annotated in 3 dimensions: 4 types, 559 brands and1216 logos. To the best of our knowledge, it is the largest dataset for branddetection and recognition with rich annotations. We provide in-depthcomprehensive statistics about the dataset, validate the quality of theannotations and study how the performance of many modern models evolves with anincreasing amount of training data. Third, we design a network called "BrandNet" to handle brand recognition. Brand Net gets state-of-art mAP on Open Brandcompared with existing detection methods.
{{< /details >}}

>**_2020-12-13_**

[**A journey in ESN and LSTM visualisations on a language task**](http://arxiv.org/abs/2012.01748v2)

*Alexandre Variengien, Xavier Hinaut*

{{< details "abstract" >}} abstract: Echo States Networks (ESN) and Long-Short Term Memory networks (LSTM) are twopopular architectures of Recurrent Neural Networks (RNN) to solve machinelearning task involving sequential data. However, little have been done tocompare their performances and their internal mechanisms on a common task. Inthis work, we trained ESNs and LSTMs on a Cross-Situationnal Learning (CSL)task. This task aims at modelling how infants learn language: they createassociations between words and visual stimuli in order to extract meaning fromwords and sentences. The results are of three kinds: performance comparison,internal dynamics analyses and visualization of latent space. (1) We found thatboth models were able to successfully learn the task: the LSTM reached thelowest error for the basic corpus, but the ESN was quicker to train.Furthermore, the ESN was able to outperform LSTMs on datasets more challengingwithout any further tuning needed. (2) We also conducted an analysis of theinternal units activations of LSTMs and ESNs. Despite the deep differencesbetween both models (trained or fixed internal weights), we were able touncover similar inner mechanisms: both put emphasis on the units encodingaspects of the sentence structure. (3) Moreover, we present Recurrent StatesSpace Visualisations (RSSviz), a method to visualize the structure of latentstate space of RNNs, based on dimension reduction (using UMAP). This techniqueenables us to observe a fractal embedding of sequences in the LSTM. RSSviz isalso useful for the analysis of ESNs (i) to spot difficult examples and (ii) togenerate animated plots showing the evolution of activations across learningstages. Finally, we explore qualitatively how the RSSviz could provide anintuitive visualisation to understand the influence of hyperparameters on thereservoir dynamics prior to ESN training.
{{< /details >}}

>**_2020-11-18_**

[**Discovering Symbolic Models from Deep Learning with Inductive Biases**](http://arxiv.org/abs/2006.11287v2)

*Miles Cranmer, Alvaro Sanchez-Gonzalez, Peter Battaglia, Rui Xu, Kyle Cranmer, David Spergel, Shirley Ho*

{{< details "abstract" >}} abstract: We develop a general approach to distill symbolic representations of alearned deep model by introducing strong inductive biases. We focus on GraphNeural Networks (GNNs). The technique works as follows: we first encouragesparse latent representations when we train a GNN in a supervised setting, thenwe apply symbolic regression to components of the learned model to extractexplicit physical relations. We find the correct known equations, includingforce laws and Hamiltonians, can be extracted from the neural network. We thenapply our method to a non-trivial cosmology example-a detailed dark mattersimulation-and discover a new analytic formula which can predict theconcentration of dark matter from the mass distribution of nearby cosmicstructures. The symbolic expressions extracted from the GNN using our techniquealso generalized to out-of-distribution data better than the GNN itself. Ourapproach offers alternative directions for interpreting neural networks anddiscovering novel physical principles from the representations they learn.
{{< /details >}}

>**_2020-11-10_**

[**Classification of Polarimetric SAR Images Using Compact Convolutional Neural Networks**](http://arxiv.org/abs/2011.05243v1)

*Mete Ahishali, Serkan Kiranyaz, Turker Ince, Moncef Gabbouj*

{{< details "abstract" >}} abstract: Classification of polarimetric synthetic aperture radar (PolSAR) images is anactive research area with a major role in environmental applications. Thetraditional Machine Learning (ML) methods proposed in this domain generallyfocus on utilizing highly discriminative features to improve the classificationperformance, but this task is complicated by the well-known "curse ofdimensionality" phenomena. Other approaches based on deep Convolutional NeuralNetworks (CNNs) have certain limitations and drawbacks, such as highcomputational complexity, an unfeasibly large training set with ground-truthlabels, and special hardware requirements. In this work, to address thelimitations of traditional ML and deep CNN based methods, a novel andsystematic classification framework is proposed for the classification ofPolSAR images, based on a compact and adaptive implementation of CNNs using asliding-window classification approach. The proposed approach has threeadvantages. First, there is no requirement for an extensive feature extractionprocess. Second, it is computationally efficient due to utilized compactconfigurations. In particular, the proposed compact and adaptive CNN model isdesigned to achieve the maximum classification accuracy with minimum trainingand computational complexity. This is of considerable importance consideringthe high costs involved in labelling in PolSAR classification. Finally, theproposed approach can perform classification using smaller window sizes thandeep CNNs. Experimental evaluations have been performed over the mostcommonly-used four benchmark PolSAR images: AIRSAR L-Band and RADARSAT-2 C-Banddata of San Francisco Bay and Flevoland areas. Accordingly, the best obtainedoverall accuracies range between 92.33 - 99.39% for these benchmark studysites.
{{< /details >}}

>**_2020-11-09_**

[**Automated Discovery of Mathematical Definitions in Text with Deep Neural Networks**](http://arxiv.org/abs/2011.04521v1)

*Natalia Vanetik, Marina Litvak, Sergey Shevchuk, Lior Reznik*

{{< details "abstract" >}} abstract: Automatic definition extraction from texts is an important task that hasnumerous applications in several natural language processing fields such assummarization, analysis of scientific texts, automatic taxonomy generation,ontology generation, concept identification, and question answering. Fordefinitions that are contained within a single sentence, this problem can beviewed as a binary classification of sentences into definitions andnon-definitions. In this paper, we focus on automatic detection of one-sentencedefinitions in mathematical texts, which are difficult to separate fromsurrounding text. We experiment with several data representations, whichinclude sentence syntactic structure and word embeddings, and apply deeplearning methods such as the Convolutional Neural Network (CNN) and the LongShort-Term Memory network (LSTM), in order to identify mathematicaldefinitions. Our experiments demonstrate the superiority of CNN and itscombination with LSTM, when applied on the syntactically-enriched inputrepresentation. We also present a new dataset for definition extraction frommathematical texts. We demonstrate that this dataset is beneficial for trainingsupervised models aimed at extraction of mathematical definitions. Ourexperiments with different domains demonstrate that mathematical definitionsrequire special treatment, and that using cross-domain learning is inefficientfor that task.
{{< /details >}}

>**_2020-11-03_**

[**Passport-aware Normalization for Deep Model Protection**](http://arxiv.org/abs/2010.15824v2)

*Jie Zhang, Dongdong Chen, Jing Liao, Weiming Zhang, Gang Hua, Nenghai Yu*

{{< details "abstract" >}} abstract: Despite tremendous success in many application scenarios, deep learning facesserious intellectual property (IP) infringement threats. Considering the costof designing and training a good model, infringements will significantlyinfringe the interests of the original model owner. Recently, many impressiveworks have emerged for deep model IP protection. However, they either arevulnerable to ambiguity attacks, or require changes in the target networkstructure by replacing its original normalization layers and hence causesignificant performance drops. To this end, we propose a new passport-awarenormalization formulation, which is generally applicable to most existingnormalization layers and only needs to add another passport-aware branch for IPprotection. This new branch is jointly trained with the target model butdiscarded in the inference stage. Therefore it causes no structure change inthe target model. Only when the model IP is suspected to be stolen by someone,the private passport-aware branch is added back for ownership verification.Through extensive experiments, we verify its effectiveness in both image and 3Dpoint recognition models. It is demonstrated to be robust not only to commonattack techniques like fine-tuning and model compression, but also to ambiguityattacks. By further combining it with trigger-set based methods, both black-boxand white-box verification can be achieved for enhanced security of deeplearning models deployed in real systems. Code can be found athttps://github.com/ZJZAC/Passport-aware-Normalization.
{{< /details >}}

>**_2020-10-21_**

[**Amnesiac Machine Learning**](http://arxiv.org/abs/2010.10981v1)

*Laura Graves, Vineel Nagisetty, Vijay Ganesh*

{{< details "abstract" >}} abstract: The Right to be Forgotten is part of the recently enacted General DataProtection Regulation (GDPR) law that affects any data holder that has data onEuropean Union residents. It gives EU residents the ability to request deletionof their personal data, including training records used to train machinelearning models. Unfortunately, Deep Neural Network models are vulnerable toinformation leaking attacks such as model inversion attacks which extract classinformation from a trained model and membership inference attacks whichdetermine the presence of an example in a model's training data. If a maliciousparty can mount an attack and learn private information that was meant to beremoved, then it implies that the model owner has not properly protected theiruser's rights and their models may not be compliant with the GDPR law. In thispaper, we present two efficient methods that address this question of how amodel owner or data holder may delete personal data from models in such a waythat they may not be vulnerable to model inversion and membership inferenceattacks while maintaining model efficacy. We start by presenting a real-worldthreat model that shows that simply removing training data is insufficient toprotect users. We follow that up with two data removal methods, namelyUnlearning and Amnesiac Unlearning, that enable model owners to protectthemselves against such attacks while being compliant with regulations. Weprovide extensive empirical analysis that show that these methods are indeedefficient, safe to apply, effectively remove learned information aboutsensitive data from trained models while maintaining model efficacy.
{{< /details >}}

[**Speculative Container Scheduling for Deep Learning Applications in a Kubernetes Cluster**](http://arxiv.org/abs/2010.11307v1)

*Ying Mao, Yuqi Fu, Wenjia Zheng, Long Cheng, Qingzhi Liu, Dingwen Tao*

{{< details "abstract" >}} abstract: In the past decade, we have witnessed a dramatically increasing volume ofdata collected from varied sources. The explosion of data has transformed theworld as more information is available for collection and analysis than everbefore. To maximize the utilization, various machine and deep learning modelshave been developed, e.g. CNN [1] and RNN [2], to study data and extractvaluable information from different perspectives. While data-drivenapplications improve countless products, training models for hyperparametertuning is still a time-consuming and resource-intensive process. Cloudcomputing provides infrastructure support for the training of deep learningapplications. The cloud service providers, such as Amazon Web Services [3],create an isolated virtual environment (virtual machines and containers) forclients, who share physical resources, e.g., CPU and memory. On the cloud,resource management schemes are implemented to enable better sharing amongusers and boost the system-wide performance. However, general schedulingapproaches, such as spread priority and balanced resource schedulers, do notwork well with deep learning workloads. In this project, we propose SpeCon, anovel container scheduler that is optimized for shortlived deep learningapplications. Based on virtualized containers, such as Kubernetes [4] andDocker [5], SpeCon analyzes the common characteristics of training processes.We design a suite of algorithms to monitor the progress of the training andspeculatively migrate the slow-growing models to release resources forfast-growing ones. Specifically, the extensive experiments demonstrate thatSpeCon improves the completion time of an individual job by up to 41.5%, 14.8%system-wide and 24.7% in terms of makespan.
{{< /details >}}

>**_2020-10-16_**

[**Modeling Token-level Uncertainty to Learn Unknown Concepts in SLU via Calibrated Dirichlet Prior RNN**](http://arxiv.org/abs/2010.08101v1)

*Yilin Shen, Wenhu Chen, Hongxia Jin*

{{< details "abstract" >}} abstract: One major task of spoken language understanding (SLU) in modern personalassistants is to extract semantic concepts from an utterance, called slotfilling. Although existing slot filling models attempted to improve extractingnew concepts that are not seen in training data, the performance in practice isstill not satisfied. Recent research collected question and answer annotateddata to learn what is unknown and should be asked, yet not practically scalabledue to the heavy data collection effort. In this paper, we incorporatesoftmax-based slot filling neural architectures to model the sequenceuncertainty without question supervision. We design a Dirichlet Prior RNN tomodel high-order uncertainty by degenerating as softmax layer for RNN modeltraining. To further enhance the uncertainty modeling robustness, we propose anovel multi-task training to calibrate the Dirichlet concentration parameters.We collect unseen concepts to create two test datasets from SLU benchmarkdatasets Snips and ATIS. On these two and another existing Concept Learningbenchmark datasets, we show that our approach significantly outperformsstate-of-the-art approaches by up to 8.18%. Our method is generic and can beapplied to any RNN or Transformer based slot filling models with a softmaxlayer.
{{< /details >}}

>**_2020-10-15_**

[**Research on AI Composition Recognition Based on Music Rules**](http://arxiv.org/abs/2010.07805v1)

*Yang Deng, Ziyao Xu, Li Zhou, Huanping Liu, Anqi Huang*

{{< details "abstract" >}} abstract: The development of artificial intelligent composition has resulted in theincreasing popularity of machine-generated pieces, with frequent copyrightdisputes consequently emerging. There is an insufficient amount of research onthe judgement of artificial and machine-generated works; the creation of amethod to identify and distinguish these works is of particular importance.Starting from the essence of the music, the article constructs amusic-rule-identifying algorithm through extracting modes, which will identifythe stability of the mode of machine-generated music, to judge whether it isartificial intelligent. The evaluation datasets used are provided by theConference on Sound and Music Technology(CSMT). Experimental resultsdemonstrate the algorithm to have a successful distinguishing ability betweendatasets with different source distributions. The algorithm will also providesome technological reference to the benign development of the music copyrightand artificial intelligent music.
{{< /details >}}

>**_2020-10-13_**

[**Automating App Review Response Generation Based on Contextual Knowledge**](http://arxiv.org/abs/2010.06301v1)

*Cuiyun Gao, Wenjie Zhou, Xin Xia, David Lo, Qi Xie, Michael R. Lyu*

{{< details "abstract" >}} abstract: User experience of mobile apps is an essential ingredient that can influencethe audience volumes and app revenue. To ensure good user experience and assistapp development, several prior studies resort to analysis of app reviews, atype of app repository that directly reflects user opinions about the apps.Accurately responding to the app reviews is one of the ways to relieve userconcerns and thus improve user experience. However, the response quality of theexisting method relies on the pre-extracted features from other tools,including manually-labelled keywords and predicted review sentiment, which mayhinder the generalizability and flexibility of the method. In this paper, wepropose a novel end-to-end neural network approach, named CoRe, with thecontextual knowledge naturally incorporated and without involving externaltools. Specifically, CoRe integrates two types of contextual knowledge in thetraining corpus, including official app descriptions from app store andresponses of the retrieved semantically similar reviews, for enhancing therelevance and accuracy of the generated review responses. Experiments onpractical review data show that CoRe can outperform the state-of-the-art methodby 11.53% in terms of BLEU-4, an accuracy metric that is widely used toevaluate text generation systems.
{{< /details >}}

>**_2020-10-06_**

[**Fast Mesh Data Augmentation via Chebyshev Polynomial of Spectral filtering**](http://arxiv.org/abs/2010.02811v1)

*Shih-Gu Huang, Moo K. Chung, Anqi Qiu, Alzheimer's Disease Neuroimaging Initiative*

{{< details "abstract" >}} abstract: Deep neural networks have recently been recognized as one of the powerfullearning techniques in computer vision and medical image analysis. Trained deepneural networks need to be generalizable to new data that was not seen before.In practice, there is often insufficient training data available andaugmentation is used to expand the dataset. Even though graph convolutionalneural network (graph-CNN) has been widely used in deep learning, there is alack of augmentation methods to generate data on graphs or surfaces. This studyproposes two unbiased augmentation methods, Laplace-Beltrami eigenfunction DataAugmentation (LB-eigDA) and Chebyshev polynomial Data Augmentation (C-pDA), togenerate new data on surfaces, whose mean is the same as that of real data.LB-eigDA augments data via the resampling of the LB coefficients. In parallelwith LB-eigDA, we introduce a fast augmentation approach, C-pDA, that employs apolynomial approximation of LB spectral filters on surfaces. We design LBspectral bandpass filters by Chebyshev polynomial approximation and resamplesignals filtered via these filters to generate new data on surfaces. We firstvalidate LB-eigDA and C-pDA via simulated data and demonstrate their use forimproving classification accuracy. We then employ the brain images ofAlzheimer's Disease Neuroimaging Initiative (ADNI) and extract corticalthickness that is represented on the cortical surface to illustrate the use ofthe two augmentation methods. We demonstrate that augmented cortical thicknesshas a similar pattern to real data. Second, we show that C-pDA is much fasterthan LB-eigDA. Last, we show that C-pDA can improve the AD classificationaccuracy of graph-CNN.
{{< /details >}}

>**_2020-10-03_**

[**Generating similes effortlessly like a Pro: A Style Transfer Approach for Simile Generation**](http://arxiv.org/abs/2009.08942v2)

*Tuhin Chakrabarty, Smaranda Muresan, Nanyun Peng*

{{< details "abstract" >}} abstract: Literary tropes, from poetry to stories, are at the crux of human imaginationand communication. Figurative language such as a simile go beyond plainexpressions to give readers new insights and inspirations. In this paper, wetackle the problem of simile generation. Generating a simile requires properunderstanding for effective mapping of properties between two concepts. To thisend, we first propose a method to automatically construct a parallel corpus bytransforming a large number of similes collected from Reddit to their literalcounterpart using structured common sense knowledge. We then propose tofine-tune a pretrained sequence to sequence model, BART~\cite{lewis2019bart},on the literal-simile pairs to gain generalizability, so that we can generatenovel similes given a literal sentence. Experiments show that our approachgenerates $88\%$ novel similes that do not share properties with the trainingdata. Human evaluation on an independent set of literal statements shows thatour model generates similes better than two literary experts\textit{37\%}\footnote{We average 32.6\% and 41.3\% for 2 humans.} of thetimes, and three baseline systems including a recent metaphor generation model\textit{71\%}\footnote{We average 82\% ,63\% and 68\% for three baselines.} ofthe times when compared pairwise.\footnote{The simile in the title is generatedby our best model. Input: Generating similes effortlessly, output: Generatingsimiles \textit{like a Pro}.} We also show how replacing literal sentences withsimiles from our best model in machine generated stories improves evocativenessand leads to better acceptance by human judges.
{{< /details >}}

>**_2020-09-30_**

[**Towards Improved Model Design for Authorship Identification: A Survey on Writing Style Understanding**](http://arxiv.org/abs/2009.14445v1)

*Weicheng Ma, Ruibo Liu, Lili Wang, Soroush Vosoughi*

{{< details "abstract" >}} abstract: Authorship identification tasks, which rely heavily on linguistic styles,have always been an important part of Natural Language Understanding (NLU)research. While other tasks based on linguistic style understanding benefitfrom deep learning methods, these methods have not behaved as well astraditional machine learning methods in many authorship-based tasks. With thesetasks becoming more and more challenging, however, traditional machine learningmethods based on handcrafted feature sets are already approaching theirperformance limits. Thus, in order to inspire future applications of deeplearning methods in authorship-based tasks in ways that benefit the extractionof stylistic features, we survey authorship-based tasks and other tasks relatedto writing style understanding. We first describe our survey results on thecurrent state of research in both sets of tasks and summarize existingachievements and problems in authorship-related tasks. We then describeoutstanding methods in style-related tasks in general and analyze how they areused in combination in the top-performing models. We are optimistic about theapplicability of these models to authorship-based tasks and hope our surveywill help advance research in this field.
{{< /details >}}

>**_2020-09-20_**

[**Deep Transparent Prediction through Latent Representation Analysis**](http://arxiv.org/abs/2009.07044v2)

*D. Kollias, N. Bouas, Y. Vlaxos, V. Brillakis, M. Seferis, I. Kollia, L. Sukissian, J. Wingate, S. Kollias*

{{< details "abstract" >}} abstract: The paper presents a novel deep learning approach, which extracts latentinformation from trained Deep Neural Networks (DNNs) and derives conciserepresentations that are analyzed in an effective, unified way for predictionpurposes. It is well known that DNNs are capable of analyzing complex data;however, they lack transparency in their decision making, in the sense that itis not straightforward to justify their prediction, or to visualize thefeatures on which the decision was based. Moreover, they generally requirelarge amounts of data in order to learn and become able to adapt to differentenvironments. This makes their use difficult in healthcare, where trust andpersonalization are key issues. Transparency combined with high predictionaccuracy are the targeted goals of the proposed approach. It includes bothsupervised DNN training and unsupervised learning of latent variables extractedfrom the trained DNNs. Domain Adaptation from multiple sources is alsopresented as an extension, where the extracted latent variable representationsare used to generate predictions in other, non-annotated, environments.Successful application is illustrated through a large experimental study invarious fields: prediction of Parkinson's disease from MRI and DaTScans;prediction of COVID-19 and pneumonia from CT scans and X-rays; opticalcharacter verification in retail food packaging.
{{< /details >}}

>**_2020-09-18_**

[**IDA: Improved Data Augmentation Applied to Salient Object Detection**](http://arxiv.org/abs/2009.08845v1)

*Daniel V. Ruiz, Bruno A. Krinski, Eduardo Todt*

{{< details "abstract" >}} abstract: In this paper, we present an Improved Data Augmentation (IDA) techniquefocused on Salient Object Detection (SOD). Standard data augmentationtechniques proposed in the literature, such as image cropping, rotation,flipping, and resizing, only generate variations of the existing examples,providing a limited generalization. Our method combines image inpainting,affine transformations, and the linear combination of different generatedbackground images with salient objects extracted from labeled data. Ourproposed technique enables more precise control of the object's position andsize while preserving background information. The background choice is based onan inter-image optimization, while object size follows a uniform randomdistribution within a specified interval, and the object position isintra-image optimal. We show that our method improves the segmentation qualitywhen used for training state-of-the-art neural networks on several famousdatasets of the SOD field. Combining our method with others surpassestraditional techniques such as horizontal-flip in 0.52% for F-measure and 1.19%for Precision. We also provide an evaluation in 7 different SOD datasets, with9 distinct evaluation metrics and an average ranking of the evaluated methods.
{{< /details >}}

>**_2020-09-17_**

[**ShapeAssembly: Learning to Generate Programs for 3D Shape Structure Synthesis**](http://arxiv.org/abs/2009.08026v1)

*R. Kenny Jones, Theresa Barton, Xianghao Xu, Kai Wang, Ellen Jiang, Paul Guerrero, Niloy J. Mitra, Daniel Ritchie*

{{< details "abstract" >}} abstract: Manually authoring 3D shapes is difficult and time consuming; generativemodels of 3D shapes offer compelling alternatives. Procedural representationsare one such possibility: they offer high-quality and editable results but aredifficult to author and often produce outputs with limited diversity. On theother extreme are deep generative models: given enough data, they can learn togenerate any class of shape but their outputs have artifacts and therepresentation is not editable. In this paper, we take a step towards achievingthe best of both worlds for novel 3D shape synthesis. We propose ShapeAssembly,a domain-specific "assembly-language" for 3D shape structures. ShapeAssemblyprograms construct shapes by declaring cuboid part proxies and attaching themto one another, in a hierarchical and symmetrical fashion. Its functions areparameterized with free variables, so that one program structure is able tocapture a family of related shapes. We show how to extract ShapeAssemblyprograms from existing shape structures in the PartNet dataset. Then we train adeep generative model, a hierarchical sequence VAE, that learns to write novelShapeAssembly programs. The program captures the subset of variability that isinterpretable and editable. The deep model captures correlations across shapecollections that are hard to express procedurally. We evaluate our approach bycomparing shapes output by our generated programs to those from other recentshape structure synthesis models. We find that our generated shapes are moreplausible and physically-valid than those of other methods. Additionally, weassess the latent spaces of these models, and find that ours is betterstructured and produces smoother interpolations. As an application, we use ourgenerative model and differentiable program interpreter to infer and fit shapeprograms to unstructured geometry, such as point clouds.
{{< /details >}}

>**_2020-09-16_**

[**Analysis of Generalizability of Deep Neural Networks Based on the Complexity of Decision Boundary**](http://arxiv.org/abs/2009.07974v1)

*Shuyue Guan, Murray Loew*

{{< details "abstract" >}} abstract: For supervised learning models, the analysis of generalization ability(generalizability) is vital because the generalizability expresses how well amodel will perform on unseen data. Traditional generalization methods, such asthe VC dimension, do not apply to deep neural network (DNN) models. Thus, newtheories to explain the generalizability of DNNs are required. In this study,we hypothesize that the DNN with a simpler decision boundary has bettergeneralizability by the law of parsimony (Occam's Razor). We create thedecision boundary complexity (DBC) score to define and measure the complexityof decision boundary of DNNs. The idea of the DBC score is to generate datapoints (called adversarial examples) on or near the decision boundary. Our newapproach then measures the complexity of the boundary using the entropy ofeigenvalues of these data. The method works equally well for high-dimensionaldata. We use training data and the trained model to compute the DBC score. And,the ground truth for model's generalizability is its test accuracy. Experimentsbased on the DBC score have verified our hypothesis. The DBC is shown toprovide an effective method to measure the complexity of a decision boundaryand gives a quantitative measure of the generalizability of DNNs.
{{< /details >}}

>**_2020-09-09_**

[**Gender Detection on Social Networks using Ensemble Deep Learning**](http://arxiv.org/abs/2004.06518v3)

*Kamran Kowsari, Mojtaba Heidarysafa, Tolu Odukoya, Philip Potter, Laura E. Barnes, Donald E. Brown*

{{< details "abstract" >}} abstract: Analyzing the ever-increasing volume of posts on social media sites such asFacebook and Twitter requires improved information processing methods forprofiling authorship. Document classification is central to this task, but theperformance of traditional supervised classifiers has degraded as the volume ofsocial media has increased. This paper addresses this problem in the context ofgender detection through ensemble classification that employs multi-model deeplearning architectures to generate specialized understanding from differentfeature spaces.
{{< /details >}}

>**_2020-09-01_**

[**Training Deep Neural Networks with Constrained Learning Parameters**](http://arxiv.org/abs/2009.00540v1)

*Prasanna Date, Christopher D. Carothers, John E. Mitchell, James A. Hendler, Malik Magdon-Ismail*

{{< details "abstract" >}} abstract: Today's deep learning models are primarily trained on CPUs and GPUs. Althoughthese models tend to have low error, they consume high power and utilize largeamount of memory owing to double precision floating point learning parameters.Beyond the Moore's law, a significant portion of deep learning tasks would runon edge computing systems, which will form an indispensable part of the entirecomputation fabric. Subsequently, training deep learning models for suchsystems will have to be tailored and adopted to generate models that have thefollowing desirable characteristics: low error, low memory, and low power. Webelieve that deep neural networks (DNNs), where learning parameters areconstrained to have a set of finite discrete values, running on neuromorphiccomputing systems would be instrumental for intelligent edge computing systemshaving these desirable characteristics. To this extent, we propose theCombinatorial Neural Network Training Algorithm (CoNNTrA), that leverages acoordinate gradient descent-based approach for training deep learning modelswith finite discrete learning parameters. Next, we elaborate on the theoreticalunderpinnings and evaluate the computational complexity of CoNNTrA. As a proofof concept, we use CoNNTrA to train deep learning models with ternary learningparameters on the MNIST, Iris and ImageNet data sets and compare theirperformance to the same models trained using Backpropagation. We use followingperformance metrics for the comparison: (i) Training error; (ii) Validationerror; (iii) Memory usage; and (iv) Training time. Our results indicate thatCoNNTrA models use 32x less memory and have errors at par with theBackpropagation models.
{{< /details >}}

[**Conditional Constrained Graph Variational Autoencoders for Molecule Design**](http://arxiv.org/abs/2009.00725v1)

*Davide Rigoni, Nicolò Navarin, Alessandro Sperduti*

{{< details "abstract" >}} abstract: In recent years, deep generative models for graphs have been used to generatenew molecules. These models have produced good results, leading to severalproposals in the literature. However, these models may have troubles learningsome of the complex laws governing the chemical world. In this work, we explorethe usage of the histogram of atom valences to drive the generation ofmolecules in such models. We present Conditional Constrained Graph VariationalAutoencoder (CCGVAE), a model that implements this key-idea in astate-of-the-art model, and shows improved results on several evaluationmetrics on two commonly adopted datasets for molecule generation.
{{< /details >}}

>**_2020-08-29_**

[**Adv-watermark: A Novel Watermark Perturbation for Adversarial Examples**](http://arxiv.org/abs/2008.01919v2)

*Xiaojun Jia, Xingxing Wei, Xiaochun Cao, Xiaoguang Han*

{{< details "abstract" >}} abstract: Recent research has demonstrated that adding some imperceptible perturbationsto original images can fool deep learning models. However, the currentadversarial perturbations are usually shown in the form of noises, and thushave no practical meaning. Image watermark is a technique widely used forcopyright protection. We can regard image watermark as a king of meaningfulnoises and adding it to the original image will not affect people'sunderstanding of the image content, and will not arouse people's suspicion.Therefore, it will be interesting to generate adversarial examples usingwatermarks. In this paper, we propose a novel watermark perturbation foradversarial examples (Adv-watermark) which combines image watermarkingtechniques and adversarial example algorithms. Adding a meaningful watermark tothe clean images can attack the DNN models. Specifically, we propose a noveloptimization algorithm, which is called Basin Hopping Evolution (BHE), togenerate adversarial watermarks in the black-box attack mode. Thanks to theBHE, Adv-watermark only requires a few queries from the threat models to finishthe attacks. A series of experiments conducted on ImageNet and CASIA-WebFacedatasets show that the proposed method can efficiently generate adversarialexamples, and outperforms the state-of-the-art attack methods. Moreover,Adv-watermark is more robust against image transformation defense methods.
{{< /details >}}

>**_2020-08-25_**

[**TIPRDC: Task-Independent Privacy-Respecting Data Crowdsourcing Framework for Deep Learning with Anonymized Intermediate Representations**](http://arxiv.org/abs/2005.11480v7)

*Ang Li, Yixiao Duan, Huanrui Yang, Yiran Chen, Jianlei Yang*

{{< details "abstract" >}} abstract: The success of deep learning partially benefits from the availability ofvarious large-scale datasets. These datasets are often crowdsourced fromindividual users and contain private information like gender, age, etc. Theemerging privacy concerns from users on data sharing hinder the generation oruse of crowdsourcing datasets and lead to hunger of training data for new deeplearning applications. One na\"{\i}ve solution is to pre-process the raw datato extract features at the user-side, and then only the extracted features willbe sent to the data collector. Unfortunately, attackers can still exploit theseextracted features to train an adversary classifier to infer privateattributes. Some prior arts leveraged game theory to protect privateattributes. However, these defenses are designed for known primary learningtasks, the extracted features work poorly for unknown learning tasks. To tacklethe case where the learning task may be unknown or changing, we present TIPRDC,a task-independent privacy-respecting data crowdsourcing framework withanonymized intermediate representation. The goal of this framework is to learna feature extractor that can hide the privacy information from the intermediaterepresentations; while maximally retaining the original information embedded inthe raw data for the data collector to accomplish unknown learning tasks. Wedesign a hybrid training method to learn the anonymized intermediaterepresentation: (1) an adversarial training process for hiding privateinformation from features; (2) maximally retain original information using aneural-network-based mutual information estimator.
{{< /details >}}

>**_2020-08-24_**

[**Unsupervised Multi-Modal Representation Learning for Affective Computing with Multi-Corpus Wearable Data**](http://arxiv.org/abs/2008.10726v1)

*Kyle Ross, Paul Hungler, Ali Etemad*

{{< details "abstract" >}} abstract: With recent developments in smart technologies, there has been a growingfocus on the use of artificial intelligence and machine learning for affectivecomputing to further enhance the user experience through emotion recognition.Typically, machine learning models used for affective computing are trainedusing manually extracted features from biological signals. Such features maynot generalize well for large datasets and may be sub-optimal in capturing theinformation from the raw input data. One approach to address this issue is touse fully supervised deep learning methods to learn latent representations ofthe biosignals. However, this method requires human supervision to label thedata, which may be unavailable or difficult to obtain. In this work we proposean unsupervised framework reduce the reliance on human supervision. Theproposed framework utilizes two stacked convolutional autoencoders to learnlatent representations from wearable electrocardiogram (ECG) and electrodermalactivity (EDA) signals. These representations are utilized within a randomforest model for binary arousal classification. This approach reduces humansupervision and enables the aggregation of datasets allowing for highergeneralizability. To validate this framework, an aggregated dataset comprisedof the AMIGOS, ASCERTAIN, CLEAS, and MAHNOB-HCI datasets is created. Theresults of our proposed method are compared with using convolutional neuralnetworks, as well as methods that employ manual extraction of hand-craftedfeatures. The methodology used for fusing the two modalities is alsoinvestigated. Lastly, we show that our method outperforms currentstate-of-the-art results that have performed arousal detection on the samedatasets using ECG and EDA biosignals. The results show the wide-spreadapplicability for stacked convolutional autoencoders to be used with machinelearning for affective computing.
{{< /details >}}

>**_2020-08-21_**

[**SG-VAE: Scene Grammar Variational Autoencoder to generate new indoor scenes**](http://arxiv.org/abs/1912.04554v2)

*Pulak Purkait, Christopher Zach, Ian Reid*

{{< details "abstract" >}} abstract: Deep generative models have been used in recent years to learn coherentlatent representations in order to synthesize high-quality images. In thiswork, we propose a neural network to learn a generative model for samplingconsistent indoor scene layouts. Our method learns the co-occurrences, andappearance parameters such as shape and pose, for different objects categoriesthrough a grammar-based auto-encoder, resulting in a compact and accuraterepresentation for scene layouts. In contrast to existing grammar-based methodswith a user-specified grammar, we construct the grammar automatically byextracting a set of production rules on reasoning about object co-occurrencesin training data. The extracted grammar is able to represent a scene by anaugmented parse tree. The proposed auto-encoder encodes these parse trees to alatent code, and decodes the latent code to a parse tree, thereby ensuring thegenerated scene is always valid. We experimentally demonstrate that theproposed auto-encoder learns not only to generate valid scenes (i.e. thearrangements and appearances of objects), but it also learns coherent latentrepresentations where nearby latent samples decode to similar scene outputs.The obtained generative model is applicable to several computer vision taskssuch as 3D pose and layout estimation from RGB-D data.
{{< /details >}}

>**_2020-08-18_**

[**Turing Test and the Practice of Law: The Role of Autonomous Levels of AI Legal Reasoning**](http://arxiv.org/abs/2008.07743v1)

*Lance Eliot*

{{< details "abstract" >}} abstract: Artificial Intelligence (AI) is increasingly being applied to law and amyriad of legal tasks amid attempts to bolster AI Legal Reasoning (AILR)autonomous capabilities. A major question that has generally been unaddressedinvolves how we will know when AILR has achieved autonomous capacities. Thefield of AI has grappled with similar quandaries over how to assess theattainment of Artificial General Intelligence (AGI), a persistently discussedissue among scholars since the inception of AI, with the Turing Test communallybeing considered as the bellwether for ascertaining such matters. This paperproposes a variant of the Turing Test that is customized for specific use inthe AILR realm, including depicting how this famous gold standard of AIfulfillment can be robustly applied across the autonomous levels of AI LegalReasoning.
{{< /details >}}

>**_2020-08-08_**

[**Removing Backdoor-Based Watermarks in Neural Networks with Limited Data**](http://arxiv.org/abs/2008.00407v2)

*Xuankai Liu, Fengting Li, Bihan Wen, Qi Li*

{{< details "abstract" >}} abstract: Deep neural networks have been widely applied and achieved great success invarious fields. As training deep models usually consumes massive data andcomputational resources, trading the trained deep models is highly demanded andlucrative nowadays. Unfortunately, the naive trading schemes typically involvespotential risks related to copyright and trustworthiness issues, e.g., a soldmodel can be illegally resold to others without further authorization to reaphuge profits. To tackle this problem, various watermarking techniques areproposed to protect the model intellectual property, amongst which thebackdoor-based watermarking is the most commonly-used one. However, therobustness of these watermarking approaches is not well evaluated underrealistic settings, such as limited in-distribution data availability andagnostic of watermarking patterns. In this paper, we benchmark the robustnessof watermarking, and propose a novel backdoor-based watermark removal frameworkusing limited data, dubbed WILD. The proposed WILD removes the watermarks ofdeep models with only a small portion of training data, and the output modelcan perform the same as models trained from scratch without watermarksinjected. In particular, a novel data augmentation method is utilized to mimicthe behavior of watermark triggers. Combining with the distribution alignmentbetween the normal and perturbed (e.g., occluded) data in the feature space,our approach generalizes well on all typical types of trigger contents. Theexperimental results demonstrate that our approach can effectively remove thewatermarks without compromising the deep model performance for the originaltask with the limited access to training data.
{{< /details >}}

>**_2020-08-06_**

[**Where Are We? Using Scopus to Map the Literature at the Intersection Between Artificial Intelligence and Research on Crime**](http://arxiv.org/abs/1912.11084v2)

*Gian Maria Campedelli*

{{< details "abstract" >}} abstract: Research on Artificial Intelligence (AI) applications has spread over manyscientific disciplines. Scientists have tested the power of intelligentalgorithms developed to predict (or learn from) natural, physical and socialphenomena. This also applies to crime-related research problems. Nonetheless,studies that map the current state of the art at the intersection between AIand crime are lacking. What are the current research trends in terms of topicsin this area? What is the structure of scientific collaboration whenconsidering works investigating criminal issues using machine learning, deeplearning, and AI in general? What are the most active countries in thisspecific scientific sphere? Using data retrieved from the Scopus database, thiswork quantitatively analyzes 692 published works at the intersection between AIand crime employing network science to respond to these questions. Results showthat researchers are mainly focusing on cyber-related criminal topics and thatrelevant themes such as algorithmic discrimination, fairness, and ethics areconsiderably overlooked. Furthermore, data highlight the extremely disconnectedstructure of co-authorship networks. Such disconnectedness may represent asubstantial obstacle to a more solid community of scientists interested inthese topics. Additionally, the graph of scientific collaboration indicatesthat countries that are more prone to engage in international partnerships aregenerally less central in the network. This means that scholars working inhighly productive countries (e.g. the United States, China) tend to mostlycollaborate domestically. Finally, current issues and future developmentswithin this scientific area are also discussed.
{{< /details >}}

>**_2020-08-03_**

[**Bias-based Universal Adversarial Patch Attack for Automatic Check-out**](http://arxiv.org/abs/2005.09257v3)

*Aishan Liu, Jiakai Wang, Xianglong Liu, Bowen Cao, Chongzhi Zhang, Hang Yu*

{{< details "abstract" >}} abstract: Adversarial examples are inputs with imperceptible perturbations that easilymisleading deep neural networks(DNNs). Recently, adversarial patch, with noiseconfined to a small and localized patch, has emerged for its easy feasibilityin real-world scenarios. However, existing strategies failed to generateadversarial patches with strong generalization ability. In other words, theadversarial patches were input-specific and failed to attack images from allclasses, especially unseen ones during training. To address the problem, thispaper proposes a bias-based framework to generate class-agnostic universaladversarial patches with strong generalization ability, which exploits both theperceptual and semantic bias of models. Regarding the perceptual bias, sinceDNNs are strongly biased towards textures, we exploit the hard examples whichconvey strong model uncertainties and extract a textural patch prior from themby adopting the style similarities. The patch prior is more close to decisionboundaries and would promote attacks. To further alleviate the heavy dependencyon large amounts of data in training universal attacks, we further exploit thesemantic bias. As the class-wise preference, prototypes are introduced andpursued by maximizing the multi-class margin to help universal training. TakingAutomaticCheck-out (ACO) as the typical scenario, extensive experimentsincluding white-box and black-box settings in both digital-world(RPC, thelargest ACO related dataset) and physical-world scenario(Taobao and JD, theworld' s largest online shopping platforms) are conducted. Experimental resultsdemonstrate that our proposed framework outperforms state-of-the-artadversarial patch attack methods.
{{< /details >}}

>**_2020-08-02_**

[**Backdoor Attacks and Countermeasures on Deep Learning: A Comprehensive Review**](http://arxiv.org/abs/2007.10760v3)

*Yansong Gao, Bao Gia Doan, Zhi Zhang, Siqi Ma, Jiliang Zhang, Anmin Fu, Surya Nepal, Hyoungshick Kim*

{{< details "abstract" >}} abstract: This work provides the community with a timely comprehensive review ofbackdoor attacks and countermeasures on deep learning. According to theattacker's capability and affected stage of the machine learning pipeline, theattack surfaces are recognized to be wide and then formalized into sixcategorizations: code poisoning, outsourcing, pretrained, data collection,collaborative learning and post-deployment. Accordingly, attacks under eachcategorization are combed. The countermeasures are categorized into fourgeneral classes: blind backdoor removal, offline backdoor inspection, onlinebackdoor inspection, and post backdoor removal. Accordingly, we reviewcountermeasures, and compare and analyze their advantages and disadvantages. Wehave also reviewed the flip side of backdoor attacks, which are explored for i)protecting intellectual property of deep learning models, ii) acting as ahoneypot to catch adversarial example attacks, and iii) verifying data deletionrequested by the data contributor.Overall, the research on defense is farbehind the attack, and there is no single defense that can prevent all types ofbackdoor attacks. In some cases, an attacker can intelligently bypass existingdefenses with an adaptive attack. Drawing the insights from the systematicreview, we also present key areas for future research on the backdoor, such asempirical security evaluations from physical trigger attacks, and inparticular, more efficient and practical countermeasures are solicited.
{{< /details >}}

>**_2020-07-14_**

[**Deep Transfer Learning for Source Code Modeling**](http://arxiv.org/abs/1910.05493v2)

*Yasir Hussain, Zhiqiu Huang, Yu Zhou, Senzhang Wang*

{{< details "abstract" >}} abstract: In recent years, deep learning models have shown great potential in sourcecode modeling and analysis. Generally, deep learning-based approaches areproblem-specific and data-hungry. A challenging issue of these approaches isthat they require training from starch for a different related problem. In thiswork, we propose a transfer learning-based approach that significantly improvesthe performance of deep learning-based source code models. In contrast totraditional learning paradigms, transfer learning can transfer the knowledgelearned in solving one problem into another related problem. First, we presenttwo recurrent neural network-based models RNN and GRU for the purpose oftransfer learning in the domain of source code modeling. Next, via transferlearning, these pre-trained (RNN and GRU) models are used as featureextractors. Then, these extracted features are combined into attention learnerfor different downstream tasks. The attention learner leverages from thelearned knowledge of pre-trained models and fine-tunes them for a specificdownstream task. We evaluate the performance of the proposed approach withextensive experiments with the source code suggestion task. The resultsindicate that the proposed approach outperforms the state-of-the-art models interms of accuracy, precision, recall, and F-measure without training the modelsfrom scratch.
{{< /details >}}

>**_2020-07-13_**

[**Nested Learning For Multi-Granular Tasks**](http://arxiv.org/abs/2007.06402v1)

*Raphaël Achddou, J. Matias di Martino, Guillermo Sapiro*

{{< details "abstract" >}} abstract: Standard deep neural networks (DNNs) are commonly trained in an end-to-endfashion for specific tasks such as object recognition, face identification, orcharacter recognition, among many examples. This specificity often leads tooverconfident models that generalize poorly to samples that are not from theoriginal training distribution. Moreover, such standard DNNs do not allow toleverage information from heterogeneously annotated training data, where forexample, labels may be provided with different levels of granularity.Furthermore, DNNs do not produce results with simultaneous different levels ofconfidence for different levels of detail, they are most commonly an all ornothing approach. To address these challenges, we introduce the concept ofnested learning: how to obtain a hierarchical representation of the input suchthat a coarse label can be extracted first, and sequentially refine thisrepresentation, if the sample permits, to obtain successively refinedpredictions, all of them with the corresponding confidence. We explicitlyenforce this behavior by creating a sequence of nested information bottlenecks.Looking at the problem of nested learning from an information theoryperspective, we design a network topology with two important properties. First,a sequence of low dimensional (nested) feature embeddings are enforced. Then weshow how the explicit combination of nested outputs can improve both therobustness and the accuracy of finer predictions. Experimental results onCifar-10, Cifar-100, MNIST, Fashion-MNIST, Dbpedia, and Plantvillagedemonstrate that nested learning outperforms the same network trained in thestandard end-to-end fashion.
{{< /details >}}

>**_2020-07-04_**

[**A New Channel Boosted Convolutional Neural Network using Transfer Learning**](http://arxiv.org/abs/1804.08528v5)

*Asifullah Khan, Anabia Sohail, Amna Ali*

{{< details "abstract" >}} abstract: We present a novel architectural enhancement of Channel Boosting in a deepconvolutional neural network (CNN). This idea of Channel Boosting exploits boththe channel dimension of CNN (learning from multiple input channels) andTransfer learning (TL). TL is utilized at two different stages; channelgeneration and channel exploitation. In the proposed methodology, a deep CNN isboosted by various channels available through TL from already trained DeepNeural Networks, in addition to its original channel. The deep architecture ofCNN then exploits the original and boosted channels down the stream forlearning discriminative patterns. Churn prediction in telecom is a challengingtask due to the high dimensionality and imbalanced nature of the data.Therefore, churn prediction data is used to evaluate the performance of theproposed Channel Boosted CNN (CB CNN). In the first phase, informativediscriminative features are being extracted using a stacked autoencoder, andthen in the second phase, these features are combined with the originalfeatures to form Channel Boosted images. Finally, the knowledge gained by apretrained CNN is exploited by employing TL. The results are promising and showthe ability of the Channel Boosting concept in learning complex classificationproblems by discerning even minute differences in churners and nonchurners. Theproposed work validates the concept observed from the evolution of recent CNNarchitectures that the innovative restructuring of a CNN architecture mayincrease the networks representative capacity.
{{< /details >}}

>**_2020-06-12_**

[**DeepCMB: Lensing Reconstruction of the Cosmic Microwave Background with Deep Neural Networks**](http://arxiv.org/abs/1810.01483v3)

*João Caldeira, W. L. Kimmy Wu, Brian Nord, Camille Avestruz, Shubhendu Trivedi, Kyle T. Story*

{{< details "abstract" >}} abstract: Next-generation cosmic microwave background (CMB) experiments will have lowernoise and therefore increased sensitivity, enabling improved constraints onfundamental physics parameters such as the sum of neutrino masses and thetensor-to-scalar ratio r. Achieving competitive constraints on these parametersrequires high signal-to-noise extraction of the projected gravitationalpotential from the CMB maps. Standard methods for reconstructing the lensingpotential employ the quadratic estimator (QE). However, the QE performssuboptimally at the low noise levels expected in upcoming experiments. Othermethods, like maximum likelihood estimators (MLE), are under activedevelopment. In this work, we demonstrate reconstruction of the CMB lensingpotential with deep convolutional neural networks (CNN) - ie, a ResUNet. Thenetwork is trained and tested on simulated data, and otherwise has no physicalparametrization related to the physical processes of the CMB and gravitationallensing. We show that, over a wide range of angular scales, ResUNets recoverthe input gravitational potential with a higher signal-to-noise ratio than theQE method, reaching levels comparable to analytic approximations of MLEmethods. We demonstrate that the network outputs quantifiably different lensingmaps when given input CMB maps generated with different cosmologies. We alsoshow we can use the reconstructed lensing map for cosmological parameterestimation. This application of CNN provides a few innovations at theintersection of cosmology and machine learning. First, while training andregressing on images, we predict a continuous-variable field rather thandiscrete classes. Second, we are able to establish uncertainty measures for thenetwork output that are analogous to standard methods. We expect this approachto excel in capturing hard-to-model non-Gaussian astrophysical foreground andnoise contributions.
{{< /details >}}

>**_2020-06-10_**

[**Interferometric Graph Transform: a Deep Unsupervised Graph Representation**](http://arxiv.org/abs/2006.05722v1)

*Edouard Oyallon*

{{< details "abstract" >}} abstract: We propose the Interferometric Graph Transform (IGT), which is a new class ofdeep unsupervised graph convolutional neural network for building graphrepresentations. Our first contribution is to propose a generic, complex-valuedspectral graph architecture obtained from a generalization of the EuclideanFourier transform. We show that our learned representation consists of bothdiscriminative and invariant features, thanks to a novel greedy concaveobjective. From our experiments, we conclude that our learning procedureexploits the topology of the spectral domain, which is normally a flaw ofspectral methods, and in particular our method can recover an analytic operatorfor vision tasks. We test our algorithm on various and challenging tasks suchas image classification (MNIST, CIFAR-10), community detection (Authorship,Facebook graph) and action recognition from 3D skeletons videos (SBU, NTU),exhibiting a new state-of-the-art in spectral graph unsupervised settings.
{{< /details >}}

>**_2020-05-25_**

[**Visual Attention: Deep Rare Features**](http://arxiv.org/abs/2005.12073v1)

*Matei Mancas, Phutphalla Kong, Bernard Gosselin*

{{< details "abstract" >}} abstract: Human visual system is modeled in engineering field providingfeature-engineered methods which detect contrasted/surprising/unusual data intoimages. This data is "interesting" for humans and leads to numerousapplications. Deep learning (DNNs) drastically improved the algorithmsefficiency on the main benchmark datasets. However, DNN-based models arecounter-intuitive: surprising or unusual data is by definition difficult tolearn because of its low occurrence probability. In reality, DNNs models mainlylearn top-down features such as faces, text, people, or animals which usuallyattract human attention, but they have low efficiency in extracting surprisingor unusual data in the images. In this paper, we propose a model calledDeepRare2019 (DR) which uses the power of DNNs feature extraction and thegenericity of feature-engineered algorithms. DR 1) does not need any training,2) it takes less than a second per image on CPU only and 3) our tests on threevery different eye-tracking datasets show that DR is generic and is always inthe top-3 models on all datasets and metrics while no other model exhibits sucha regularity and genericity. DeepRare2019 code can be found athttps://github.com/numediart/VisualAttention-RareFamily
{{< /details >}}

>**_2020-05-21_**

[**CAGFuzz: Coverage-Guided Adversarial Generative Fuzzing Testing of Deep Learning Systems**](http://arxiv.org/abs/1911.07931v2)

*Pengcheng Zhang, Qiyin Dai, Patrizio Pelliccione*

{{< details "abstract" >}} abstract: Deep Learning systems (DL) based on Deep Neural Networks (DNNs) are more andmore used in various aspects of our life, including unmanned vehicles, speechprocessing, and robotics. However, due to the limited dataset and thedependence on manual labeling data, DNNs often fail to detect their erroneousbehaviors, which may lead to serious problems. Several approaches have beenproposed to enhance the input examples for testing DL systems. However, theyhave the following limitations. First, they design and generate adversarialexamples from the perspective of model, which may cause low generalizationability when they are applied to other models. Second, they only use surfacefeature constraints to judge the difference between the adversarial examplegenerated and the original example. The deep feature constraints, which containhigh-level semantic information, such as image object category and scenesemantics are completely neglected. To address these two problems, in thispaper, we propose CAGFuzz, a Coverage-guided Adversarial Generative Fuzzingtesting approach, which generates adversarial examples for a targeted DNN todiscover its potential defects. First, we train an adversarial case generator(AEG) from the perspective of general data set. Second, we extract the depthfeatures of the original and adversarial examples, and constrain theadversarial examples by cosine similarity to ensure that the semanticinformation of adversarial examples remains unchanged. Finally, we retraineffective adversarial examples to improve neuron testing coverage rate. Basedon several popular data sets, we design a set of dedicated experiments toevaluate CAGFuzz. The experimental results show that CAGFuzz can improve theneuron coverage rate, detect hidden errors, and also improve the accuracy ofthe target DNN.
{{< /details >}}

>**_2020-05-14_**

[**RSVQA: Visual Question Answering for Remote Sensing Data**](http://arxiv.org/abs/2003.07333v2)

*Sylvain Lobry, Diego Marcos, Jesse Murray, Devis Tuia*

{{< details "abstract" >}} abstract: This paper introduces the task of visual question answering for remotesensing data (RSVQA). Remote sensing images contain a wealth of informationwhich can be useful for a wide range of tasks including land coverclassification, object counting or detection. However, most of the availablemethodologies are task-specific, thus inhibiting generic and easy access to theinformation contained in remote sensing data. As a consequence, accurate remotesensing product generation still requires expert knowledge. With RSVQA, wepropose a system to extract information from remote sensing data that isaccessible to every user: we use questions formulated in natural language anduse them to interact with the images. With the system, images can be queried toobtain high level information specific to the image content or relationaldependencies between objects visible in the images. Using an automatic methodintroduced in this article, we built two datasets (using low and highresolution data) of image/question/answer triplets. The information required tobuild the questions and answers is queried from OpenStreetMap (OSM). Thedatasets can be used to train (when using supervised methods) and evaluatemodels to solve the RSVQA task. We report the results obtained by applying amodel based on Convolutional Neural Networks (CNNs) for the visual part and ona Recurrent Neural Network (RNN) for the natural language part to this task.The model is trained on the two datasets, yielding promising results in bothcases.
{{< /details >}}

>**_2020-05-02_**

[**Comparing SNNs and RNNs on Neuromorphic Vision Datasets: Similarities and Differences**](http://arxiv.org/abs/2005.02183v1)

*Weihua He, YuJie Wu, Lei Deng, Guoqi Li, Haoyu Wang, Yang Tian, Wei Ding, Wenhui Wang, Yuan Xie*

{{< details "abstract" >}} abstract: Neuromorphic data, recording frameless spike events, have attractedconsiderable attention for the spatiotemporal information components and theevent-driven processing fashion. Spiking neural networks (SNNs) represent afamily of event-driven models with spatiotemporal dynamics for neuromorphiccomputing, which are widely benchmarked on neuromorphic data. Interestingly,researchers in the machine learning community can argue that recurrent(artificial) neural networks (RNNs) also have the capability to extractspatiotemporal features although they are not event-driven. Thus, the questionof "what will happen if we benchmark these two kinds of models together onneuromorphic data" comes out but remains unclear. In this work, we make asystematic study to compare SNNs and RNNs on neuromorphic data, taking thevision datasets as a case study. First, we identify the similarities anddifferences between SNNs and RNNs (including the vanilla RNNs and LSTM) fromthe modeling and learning perspectives. To improve comparability and fairness,we unify the supervised learning algorithm based on backpropagation throughtime (BPTT), the loss function exploiting the outputs at all timesteps, thenetwork structure with stacked fully-connected or convolutional layers, and thehyper-parameters during training. Especially, given the mainstream lossfunction used in RNNs, we modify it inspired by the rate coding scheme toapproach that of SNNs. Furthermore, we tune the temporal resolution of datasetsto test model robustness and generalization. At last, a series of contrastexperiments are conducted on two types of neuromorphic datasets: DVS-converted(N-MNIST) and DVS-captured (DVS Gesture).
{{< /details >}}

>**_2020-04-29_**

[**Domain Adaptive Transfer Attack (DATA)-based Segmentation Networks for Building Extraction from Aerial Images**](http://arxiv.org/abs/2004.11819v2)

*Younghwan Na, Jun Hee Kim, Kyungsu Lee, Juhum Park, Jae Youn Hwang, Jihwan P. Choi*

{{< details "abstract" >}} abstract: Semantic segmentation models based on convolutional neural networks (CNNs)have gained much attention in relation to remote sensing and have achievedremarkable performance for the extraction of buildings from high-resolutionaerial images. However, the issue of limited generalization for unseen imagesremains. When there is a domain gap between the training and test datasets,CNN-based segmentation models trained by a training dataset fail to segmentbuildings for the test dataset. In this paper, we propose segmentation networksbased on a domain adaptive transfer attack (DATA) scheme for buildingextraction from aerial images. The proposed system combines the domain transferand adversarial attack concepts. Based on the DATA scheme, the distribution ofthe input images can be shifted to that of the target images while turningimages into adversarial examples against a target network. Defendingadversarial examples adapted to the target domain can overcome the performancedegradation due to the domain gap and increase the robustness of thesegmentation model. Cross-dataset experiments and the ablation study areconducted for the three different datasets: the Inria aerial image labelingdataset, the Massachusetts building dataset, and the WHU East Asia dataset.Compared to the performance of the segmentation network without the DATAscheme, the proposed method shows improvements in the overall IoU. Moreover, itis verified that the proposed method outperforms even when compared to featureadaptation (FA) and output space adaptation (OSA).
{{< /details >}}

>**_2020-04-26_**

[**DeepSeg: Deep Neural Network Framework for Automatic Brain Tumor Segmentation using Magnetic Resonance FLAIR Images**](http://arxiv.org/abs/2004.12333v1)

*Ramy A. Zeineldin, Mohamed E. Karar, Jan Coburger, Christian R. Wirtz, Oliver Burgert*

{{< details "abstract" >}} abstract: Purpose: Gliomas are the most common and aggressive type of brain tumors dueto their infiltrative nature and rapid progression. The process ofdistinguishing tumor boundaries from healthy cells is still a challenging taskin the clinical routine. Fluid-Attenuated Inversion Recovery (FLAIR) MRImodality can provide the physician with information about tumor infiltration.Therefore, this paper proposes a new generic deep learning architecture; namelyDeepSeg for fully automated detection and segmentation of the brain lesionusing FLAIR MRI data.  Methods: The developed DeepSeg is a modular decoupling framework. It consistsof two connected core parts based on an encoding and decoding relationship. Theencoder part is a convolutional neural network (CNN) responsible for spatialinformation extraction. The resulting semantic map is inserted into the decoderpart to get the full resolution probability map. Based on modified U-Netarchitecture, different CNN models such as Residual Neural Network (ResNet),Dense Convolutional Network (DenseNet), and NASNet have been utilized in thisstudy.  Results: The proposed deep learning architectures have been successfullytested and evaluated on-line based on MRI datasets of Brain Tumor Segmentation(BraTS 2019) challenge, including s336 cases as training data and 125 cases forvalidation data. The dice and Hausdorff distance scores of obtainedsegmentation results are about 0.81 to 0.84 and 9.8 to 19.7 correspondingly.  Conclusion: This study showed successful feasibility and comparativeperformance of applying different deep learning models in a new DeepSegframework for automated brain tumor segmentation in FLAIR MR images. Theproposed DeepSeg is open-source and freely available athttps://github.com/razeineldin/DeepSeg/.
{{< /details >}}

>**_2020-04-15_**

[**Learning Furniture Compatibility with Graph Neural Networks**](http://arxiv.org/abs/2004.07268v1)

*Luisa F. Polania, Mauricio Flores, Yiran Li, Matthew Nokleby*

{{< details "abstract" >}} abstract: We propose a graph neural network (GNN) approach to the problem of predictingthe stylistic compatibility of a set of furniture items from images. While mostexisting results are based on siamese networks which evaluate pairwisecompatibility between items, the proposed GNN architecture exploits relationalinformation among groups of items. We present two GNN models, both of whichcomprise a deep CNN that extracts a feature representation for each image, agated recurrent unit (GRU) network that models interactions between thefurniture items in a set, and an aggregation function that calculates thecompatibility score. In the first model, a generalized contrastive lossfunction that promotes the generation of clustered embeddings for itemsbelonging to the same furniture set is introduced. Also, in the first model,the edge function between nodes in the GRU and the aggregation function arefixed in order to limit model complexity and allow training on smallerdatasets; in the second model, the edge function and aggregation function arelearned directly from the data. We demonstrate state-of-the art accuracy forcompatibility prediction and "fill in the blank" tasks on the Bonn andSingapore furniture datasets. We further introduce a new dataset, called theTarget Furniture Collections dataset, which contains over 6000 furniture itemsthat have been hand-curated by stylists to make up 1632 compatible sets. Wealso demonstrate superior prediction accuracy on this dataset.
{{< /details >}}

>**_2020-04-10_**

[**Artificial Intelligence in Glioma Imaging: Challenges and Advances**](http://arxiv.org/abs/1911.12886v3)

*Weina Jin, Mostafa Fatehi, Kumar Abhishek, Mayur Mallya, Brian Toyota, Ghassan Hamarneh*

{{< details "abstract" >}} abstract: Primary brain tumors including gliomas continue to pose significantmanagement challenges to clinicians. While the presentation, the pathology, andthe clinical course of these lesions are variable, the initial investigationsare usually similar. Patients who are suspected to have a brain tumor will beassessed with computed tomography (CT) and magnetic resonance imaging (MRI).The imaging findings are used by neurosurgeons to determine the feasibility ofsurgical resection and plan such an undertaking. Imaging studies are also anindispensable tool in tracking tumor progression or its response to treatment.As these imaging studies are non-invasive, relatively cheap and accessible topatients, there have been many efforts over the past two decades to increasethe amount of clinically-relevant information that can be extracted from brainimaging. Most recently, artificial intelligence (AI) techniques have beenemployed to segment and characterize brain tumors, as well as to detectprogression or treatment-response. However, the clinical utility of suchendeavours remains limited due to challenges in data collection and annotation,model training, and the reliability of AI-generated information.  We provide a review of recent advances in addressing the above challenges.First, to overcome the challenge of data paucity, different image imputationand synthesis techniques along with annotation collection efforts aresummarized. Next, various training strategies are presented to meet multipledesiderata, such as model performance, generalization ability, data privacyprotection, and learning with sparse annotations. Finally, standardizedperformance evaluation and model interpretability methods have been reviewed.We believe that these technical approaches will facilitate the development of afully-functional AI tool in the clinical care of patients with gliomas.
{{< /details >}}

>**_2020-04-04_**

[**Scaling Limits of Wide Neural Networks with Weight Sharing: Gaussian Process Behavior, Gradient Independence, and Neural Tangent Kernel Derivation**](http://arxiv.org/abs/1902.04760v3)

*Greg Yang*

{{< details "abstract" >}} abstract: Several recent trends in machine learning theory and practice, from thedesign of state-of-the-art Gaussian Process to the convergence analysis of deepneural nets (DNNs) under stochastic gradient descent (SGD), have found itfruitful to study wide random neural networks. Central to these approaches arecertain scaling limits of such networks. We unify these results by introducinga notion of a straightline \emph{tensor program} that can express most neuralnetwork computations, and we characterize its scaling limit when its tensorsare large and randomized. From our framework follows (1) the convergence ofrandom neural networks to Gaussian processes for architectures such asrecurrent neural networks, convolutional neural networks, residual networks,attention, and any combination thereof, with or without batch normalization;(2) conditions under which the \emph{gradient independence assumption} -- thatweights in backpropagation can be assumed to be independent from weights in theforward pass -- leads to correct computation of gradient dynamics, andcorrections when it does not; (3) the convergence of the Neural Tangent Kernel,a recently proposed kernel used to predict training dynamics of neural networksunder gradient descent, at initialization for all architectures in (1) withoutbatch normalization. Mathematically, our framework is general enough torederive classical random matrix results such as the semicircle and theMarchenko-Pastur laws, as well as recent results in neural network Jacobiansingular values. We hope our work opens a way toward design of even strongerGaussian Processes, initialization schemes to avoid gradientexplosion/vanishing, and deeper understanding of SGD dynamics in modernarchitectures.
{{< /details >}}

>**_2020-04-03_**

[**Binary Classification of Alzheimer Disease using sMRI Imaging modality and Deep Learning**](http://arxiv.org/abs/1809.06209v3)

*Ahsan Bin Tufail, Qiu-Na Zhang, Yong-Kui Ma*

{{< details "abstract" >}} abstract: Alzheimer's disease (AD) is an irreversible devastative neurodegenerativedisorder associated with progressive impairment of memory and cognitivefunctions. Its early diagnosis is crucial for the development of possiblefuture treatment option(s). Structural magnetic resonance images (sMRI) playsan important role to help in understanding the anatomical changes related to ADespecially in its early stages. Conventional methods require the expertise ofdomain experts and extract hand-picked features such as gray mattersubstructures and train a classifier to distinguish AD subjects from healthysubjects. Different from these methods, this paper proposes to constructmultiple deep 2D convolutional neural networks (2D-CNNs) to learn the variousfeatures from local brain images which are combined to make the finalclassification for AD diagnosis. The whole brain image was passed through twotransfer learning architectures; Inception version 3 and Xception; as well ascustom Convolutional Neural Network (CNN) built with the help of separableconvolutional layers which can automatically learn the generic features fromimaging data for classification. Our study is conducted using cross-sectionalT1-weighted structural MRI brain images from Open Access Series of ImagingStudies (OASIS) database to maintain the size and contrast over different MRIscans. Experimental results show that the transfer learning approaches exceedthe performance of non-transfer learning based approaches demonstrating theeffectiveness of these approaches for the binary AD classification task.
{{< /details >}}

>**_2020-03-12_**

[**Interpretable CNNs for Object Classification**](http://arxiv.org/abs/1901.02413v2)

*Quanshi Zhang, Xin Wang, Ying Nian Wu, Huilin Zhou, Song-Chun Zhu*

{{< details "abstract" >}} abstract: This paper proposes a generic method to learn interpretable convolutionalfilters in a deep convolutional neural network (CNN) for object classification,where each interpretable filter encodes features of a specific object part. Ourmethod does not require additional annotations of object parts or textures forsupervision. Instead, we use the same training data as traditional CNNs. Ourmethod automatically assigns each interpretable filter in a high conv-layerwith an object part of a certain category during the learning process. Suchexplicit knowledge representations in conv-layers of CNN help people clarifythe logic encoded in the CNN, i.e., answering what patterns the CNN extractsfrom an input image and uses for prediction. We have tested our method usingdifferent benchmark CNNs with various structures to demonstrate the broadapplicability of our method. Experiments have shown that our interpretablefilters are much more semantically meaningful than traditional filters.
{{< /details >}}

>**_2020-02-28_**

[**Constrained Generative Adversarial Network Ensembles for Sharable Synthetic Data Generation**](http://arxiv.org/abs/2003.00086v1)

*Engin Dikici, Luciano M. Prevedello, Matthew Bigelow, Richard D. White, Barbaros Selnur Erdal*

{{< details "abstract" >}} abstract: The sharing of medical imaging datasets between institutions, and even insidethe same institution, is limited by various regulations/legal barriers.Although these limitations are necessities for protecting patient privacy andsetting strict boundaries for data ownership, medical research projects thatrequire large datasets suffer considerably as a result. Machine learning hasbeen revolutionized with the emerging deep neural network approaches overrecent years, making the data-related limitations even a larger problem asthese novel techniques commonly require immense imaging datasets. This paperintroduces constrained Generative Adversarial Network ensembles (cGANe) toaddress this problem by altering the representation of the imaging data,whereas containing the significant information, enabling the reproduction ofsimilar research results elsewhere with the sharable data. Accordingly, aframework representing the generation of a cGANe is described, and the approachis validated for the generation of synthetic 3D brain metastatic region datafrom T1-weighted contrast-enhanced MRI studies. For 90% brain metastases (BM)detection sensitivity, our previously reported detection algorithm produced onaverage 9.12 false-positive BM detections per patient after training with theoriginal data, whereas producing 9.53 false-positives after training with thecGANe generated synthetic data. Although the applicability of the introducedapproach needs further validation studies with a range of medical imaging datatypes, the results suggest that the BM-detection algorithm can achievecomparable performance by using cGANe generated synthetic data. Hence, thegeneralization of the proposed approach for various modalities may occur in thenear future.
{{< /details >}}

>**_2020-02-25_**

[**Model Watermarking for Image Processing Networks**](http://arxiv.org/abs/2002.11088v1)

*Jie Zhang, Dongdong Chen, Jing Liao, Han Fang, Weiming Zhang, Wenbo Zhou, Hao Cui, Nenghai Yu*

{{< details "abstract" >}} abstract: Deep learning has achieved tremendous success in numerous industrialapplications. As training a good model often needs massive high-quality dataand computation resources, the learned models often have significant businessvalues. However, these valuable deep models are exposed to a huge risk ofinfringements. For example, if the attacker has the full information of onetarget model including the network structure and weights, the model can beeasily finetuned on new datasets. Even if the attacker can only access theoutput of the target model, he/she can still train another similar surrogatemodel by generating a large scale of input-output training pairs. How toprotect the intellectual property of deep models is a very important butseriously under-researched problem. There are a few recent attempts atclassification network protection only. In this paper, we propose the firstmodel watermarking framework for protecting image processing models. To achievethis goal, we leverage the spatial invisible watermarking mechanism.Specifically, given a black-box target model, a unified and invisible watermarkis hidden into its outputs, which can be regarded as a special task-agnosticbarrier. In this way, when the attacker trains one surrogate model by using theinput-output pairs of the target model, the hidden watermark will be learnedand extracted afterward. To enable watermarks from binary bits tohigh-resolution images, both traditional and deep spatial invisiblewatermarking mechanism are considered. Experiments demonstrate the robustnessof the proposed watermarking mechanism, which can resist surrogate modelslearned with different network structures and objective functions. Besides deepmodels, the proposed method is also easy to be extended to protect data andtraditional image processing algorithms.
{{< /details >}}

>**_2020-02-24_**

[**Deep Multi-Facial patches Aggregation Network for Expression Classification from Face Images**](http://arxiv.org/abs/1909.10305v2)

*Amine Djerghri, Ahmed Rachid Hazourli, Alice Othmani*

{{< details "abstract" >}} abstract: Emotional Intelligence in Human-Computer Interaction has attracted increasingattention from researchers in multidisciplinary research fields includingpsychology, computer vision, neuroscience, artificial intelligence, and relateddisciplines. Human prone to naturally interact with computers face-to-face.Human Expressions is an important key to better link human and computers. Thus,designing interfaces able to understand human expressions and emotions canimprove Human-Computer Interaction (HCI) for better communication. In thispaper, we investigate HCI via a deep multi-facial patches aggregation networkfor Face Expression Recognition (FER). Deep features are extracted from facialparts and aggregated for expression classification. Several problems may affectthe performance of the proposed framework like the small size of FER datasetsand the high number of parameters to learn. For That, two data augmentationtechniques are proposed for facial expression generation to expand the labeledtraining. The proposed framework is evaluated on the extended Cohn-Konadedataset (CK+) and promising results are achieved.
{{< /details >}}

>**_2020-02-19_**

[**Deep compositional robotic planners that follow natural language commands**](http://arxiv.org/abs/2002.05201v2)

*Yen-Ling Kuo, Boris Katz, Andrei Barbu*

{{< details "abstract" >}} abstract: We demonstrate how a sampling-based robotic planner can be augmented to learnto understand a sequence of natural language commands in a continuousconfiguration space to move and manipulate objects. Our approach combines adeep network structured according to the parse of a complex command thatincludes objects, verbs, spatial relations, and attributes, with asampling-based planner, RRT. A recurrent hierarchical deep network controls howthe planner explores the environment, determines when a planned path is likelyto achieve a goal, and estimates the confidence of each move to trade offexploitation and exploration between the network and the planner. Planners aredesigned to have near-optimal behavior when information about the task ismissing, while networks learn to exploit observations which are available fromthe environment, making the two naturally complementary. Combining the twoenables generalization to new maps, new kinds of obstacles, and more complexsentences that do not occur in the training set. Little data is required totrain the model despite it jointly acquiring a CNN that extracts features fromthe environment as it learns the meanings of words. The model provides a levelof interpretability through the use of attention maps allowing users to see itsreasoning steps despite being an end-to-end model. This end-to-end model allowsrobots to learn to follow natural language commands in challenging continuousenvironments.
{{< /details >}}

>**_2020-02-15_**

[**Embedding Hard Physical Constraints in Neural Network Coarse-Graining of 3D Turbulence**](http://arxiv.org/abs/2002.00021v2)

*Arvind T. Mohan, Nicholas Lubbers, Daniel Livescu, Michael Chertkov*

{{< details "abstract" >}} abstract: In the recent years, deep learning approaches have shown much promise inmodeling complex systems in the physical sciences. A major challenge in deeplearning of PDEs is enforcing physical constraints and boundary conditions. Inthis work, we propose a general framework to directly embed the notion of anincompressible fluid into Convolutional Neural Networks, and apply this tocoarse-graining of turbulent flow. These physics-embedded neural networksleverage interpretable strategies from numerical methods and computationalfluid dynamics to enforce physical laws and boundary conditions by takingadvantage the mathematical properties of the underlying equations. Wedemonstrate results on three-dimensional fully-developed turbulence, showingthat this technique drastically improves local conservation of mass, withoutsacrificing performance according to several other metrics characterizing thefluid flow.
{{< /details >}}

>**_2020-02-14_**

[**Learning from Explanations with Neural Execution Tree**](http://arxiv.org/abs/1911.01352v3)

*Ziqi Wang, Yujia Qin, Wenxuan Zhou, Jun Yan, Qinyuan Ye, Leonardo Neves, Zhiyuan Liu, Xiang Ren*

{{< details "abstract" >}} abstract: While deep neural networks have achieved impressive performance on a range ofNLP tasks, these data-hungry models heavily rely on labeled data, whichrestricts their applications in scenarios where data annotation is expensive.Natural language (NL) explanations have been demonstrated very usefuladditional supervision, which can provide sufficient domain knowledge forgenerating more labeled data over new instances, while the annotation time onlydoubles. However, directly applying them for augmenting model learningencounters two challenges: (1) NL explanations are unstructured and inherentlycompositional, which asks for a modularized model to represent their semantics,(2) NL explanations often have large numbers of linguistic variants, resultingin low recall and limited generalization ability. In this paper, we propose anovel Neural Execution Tree (NExT) framework to augment training data for textclassification using NL explanations. After transforming NL explanations intoexecutable logical forms by semantic parsing, NExT generalizes different typesof actions specified by the logical forms for labeling data instances, whichsubstantially increases the coverage of each NL explanation. Experiments on twoNLP tasks (relation extraction and sentiment analysis) demonstrate itssuperiority over baseline methods. Its extension to multi-hop questionanswering achieves performance gain with light annotation effort.
{{< /details >}}

>**_2020-02-07_**

[**Object-Adaptive LSTM Network for Real-time Visual Tracking with Adversarial Data Augmentation**](http://arxiv.org/abs/2002.02598v1)

*Yihan Du, Yan Yan, Si Chen, Yang Hua*

{{< details "abstract" >}} abstract: In recent years, deep learning based visual tracking methods have obtainedgreat success owing to the powerful feature representation ability ofConvolutional Neural Networks (CNNs). Among these methods, classification-basedtracking methods exhibit excellent performance while their speeds are heavilylimited by the expensive computation for massive proposal feature extraction.In contrast, matching-based tracking methods (such as Siamese networks) possessremarkable speed superiority. However, the absence of online updating rendersthese methods unadaptable to significant object appearance variations. In thispaper, we propose a novel real-time visual tracking method, which adopts anobject-adaptive LSTM network to effectively capture the video sequentialdependencies and adaptively learn the object appearance variations. For highcomputational efficiency, we also present a fast proposal selection strategy,which utilizes the matching-based tracking method to pre-estimate denseproposals and selects high-quality ones to feed to the LSTM network forclassification. This strategy efficiently filters out some irrelevant proposalsand avoids the redundant computation for feature extraction, which enables ourmethod to operate faster than conventional classification-based trackingmethods. In addition, to handle the problems of sample inadequacy and classimbalance during online tracking, we adopt a data augmentation technique basedon the Generative Adversarial Network (GAN) to facilitate the training of theLSTM network. Extensive experiments on four visual tracking benchmarksdemonstrate the state-of-the-art performance of our method in terms of bothtracking accuracy and speed, which exhibits great potentials of recurrentstructures for visual tracking.
{{< /details >}}

>**_2020-01-30_**

[**An automatic deep learning-based workflow for glioblastoma survival prediction using pre-operative multimodal MR images**](http://arxiv.org/abs/2001.11155v1)

*Jie Fu, Kamal Singhrao, Xinran Zhong, Yu Gao, Sharon Qi, Yingli Yang, Dan Ruan, John H Lewis*

{{< details "abstract" >}} abstract: We proposed a fully automatic workflow for glioblastoma (GBM) survivalprediction using deep learning (DL) methods. 285 glioma (210 GBM, 75 low-gradeglioma) patients were included. 163 of the GBM patients had overall survival(OS) data. Every patient had four pre-operative MR scans and manually drawntumor contours. For automatic tumor segmentation, a 3D convolutional neuralnetwork (CNN) was trained and validated using 122 glioma patients. The trainedmodel was applied to the remaining 163 GBM patients to generate tumor contours.The handcrafted and DL-based radiomic features were extracted fromauto-contours using explicitly designed algorithms and a pre-trained CNNrespectively. 163 GBM patients were randomly split into training (n=122) andtesting (n=41) sets for survival analysis. Cox regression models withregularization techniques were trained to construct the handcrafted andDL-based signatures. The prognostic power of the two signatures was evaluatedand compared. The 3D CNN achieved an average Dice coefficient of 0.85 across163 GBM patients for tumor segmentation. The handcrafted signature achieved aC-index of 0.64 (95% CI: 0.55-0.73), while the DL-based signature achieved aC-index of 0.67 (95% CI: 0.57-0.77). Unlike the handcrafted signature, theDL-based signature successfully stratified testing patients into twoprognostically distinct groups (p-value<0.01, HR=2.80, 95% CI: 1.26-6.24). Theproposed 3D CNN generated accurate GBM tumor contours from four MR images. TheDL-based signature resulted in better GBM survival prediction, in terms ofhigher C-index and significant patient stratification, than the handcraftedsignature. The proposed automatic radiomic workflow demonstrated the potentialof improving patient stratification and survival prediction in GBM patients.
{{< /details >}}

>**_2020-01-28_**

[**Algorithms of Data Development For Deep Learning and Feedback Design**](http://arxiv.org/abs/1912.00492v2)

*Wei Kang, Qi Gong, Tenavi Nakamura-Zimmerer*

{{< details "abstract" >}} abstract: Recent research reveals that deep learning is an effective way of solvinghigh dimensional Hamilton-Jacobi-Bellman equations. The resulting feedbackcontrol law in the form of a neural network is computationally efficient forreal-time applications of optimal control. A critical part of this designmethod is to generate data for training the neural network and validating itsaccuracy. In this paper, we provide a survey of existing algorithms that can beused to generate data. All the algorithms surveyed in this paper arecausality-free, i.e., the solution at a point is computed without using thevalue of the function at any other points. At the end of the paper, anillustrative example of optimal feedback design using deep learning is given.
{{< /details >}}

>**_2020-01-26_**

[**Analyzing the Noise Robustness of Deep Neural Networks**](http://arxiv.org/abs/2001.09395v1)

*Kelei Cao, Mengchen Liu, Hang Su, Jing Wu, Jun Zhu, Shixia Liu*

{{< details "abstract" >}} abstract: Adversarial examples, generated by adding small but intentionallyimperceptible perturbations to normal examples, can mislead deep neuralnetworks (DNNs) to make incorrect predictions. Although much work has been doneon both adversarial attack and defense, a fine-grained understanding ofadversarial examples is still lacking. To address this issue, we present avisual analysis method to explain why adversarial examples are misclassified.The key is to compare and analyze the datapaths of both the adversarial andnormal examples. A datapath is a group of critical neurons along with theirconnections. We formulate the datapath extraction as a subset selection problemand solve it by constructing and training a neural network. A multi-levelvisualization consisting of a network-level visualization of data flows, alayer-level visualization of feature maps, and a neuron-level visualization oflearned features, has been designed to help investigate how datapaths ofadversarial and normal examples diverge and merge in the prediction process. Aquantitative evaluation and a case study were conducted to demonstrate thepromise of our method to explain the misclassification of adversarial examples.
{{< /details >}}

>**_2019-12-17_**

[**Facial Synthesis from Visual Attributes via Sketch using Multi-Scale Generators**](http://arxiv.org/abs/1912.10479v1)

*Xing Di, Vishal M. Patel*

{{< details "abstract" >}} abstract: Automatic synthesis of faces from visual attributes is an important problemin computer vision and has wide applications in law enforcement andentertainment. With the advent of deep generative convolutional neural networks(CNNs), attempts have been made to synthesize face images from attributes andtext descriptions. In this paper, we take a different approach, where weformulate the original problem as a stage-wise learning problem. We firstsynthesize the facial sketch corresponding to the visual attributes and then wegenerate the face image based on the synthesized sketch. The proposedframework, is based on a combination of two different Generative AdversarialNetworks (GANs) - (1) a sketch generator network which synthesizes realisticsketch from the input attributes, and (2) a face generator network whichsynthesizes facial images from the synthesized sketch images with the help offacial attributes. Extensive experiments and comparison with recent methods areperformed to verify the effectiveness of the proposed attribute-based two-stageface synthesis method.
{{< /details >}}

>**_2019-12-09_**

[**Stealing Knowledge from Protected Deep Neural Networks Using Composite Unlabeled Data**](http://arxiv.org/abs/1912.03959v1)

*Itay Mosafi, Eli David, Nathan S. Netanyahu*

{{< details "abstract" >}} abstract: As state-of-the-art deep neural networks are deployed at the core of moreadvanced Al-based products and services, the incentive for copying them (i.e.,their intellectual properties) by rival adversaries is expected to increaseconsiderably over time. The best way to extract or steal knowledge from suchnetworks is by querying them using a large dataset of random samples andrecording their output, followed by training a student network to mimic theseoutputs, without making any assumption about the original networks. The mosteffective way to protect against such a mimicking attack is to provide only theclassification result, without confidence values associated with the softmaxlayer.In this paper, we present a novel method for generating composite imagesfor attacking a mentor neural network using a student model. Our method assumesno information regarding the mentor's training dataset, architecture, orweights. Further assuming no information regarding the mentor's softmax outputvalues, our method successfully mimics the given neural network and steals allof its knowledge. We also demonstrate that our student network (which copiesthe mentor) is impervious to watermarking protection methods, and thus wouldnot be detected as a stolen model.Our results imply, essentially, that allcurrent neural networks are vulnerable to mimicking attacks, even if they donot divulge anything but the most basic required output, and that the studentmodel which mimics them cannot be easily detected and singled out as a stolencopy using currently available techniques.
{{< /details >}}

>**_2019-12-04_**

[**Decoding and mapping task states of the human brain via deep learning**](http://arxiv.org/abs/1801.09858v3)

*Xiaoxiao Wang, Xiao Liang, Zhoufan Jiang, Benedictor Alexander Nguchu, Yawen Zhou, Yanming Wang, Huijuan Wang, Yu Li, Yuying Zhu, Feng Wu, Jia-Hong Gao, Benching Qiu*

{{< details "abstract" >}} abstract: Support vector machine (SVM) based multivariate pattern analysis (MVPA) hasdelivered promising performance in decoding specific task states based onfunctional magnetic resonance imaging (fMRI) of the human brain.Conventionally, the SVM-MVPA requires careful feature selection/extractionaccording to expert knowledge. In this study, we propose a deep neural network(DNN) for directly decoding multiple brain task states from fMRI signals of thebrain without any burden for feature handcrafts. We trained and tested the DNNclassifier using task fMRI data from the Human Connectome Project's S1200dataset (N=1034). In tests to verify its performance, the proposedclassification method identified seven tasks with an average accuracy of 93.7%.We also showed the general applicability of the DNN for transfer learning tosmall datasets (N=43), a situation encountered in typical neuroscienceresearch. The proposed method achieved an average accuracy of 89.0% and 94.7%on a working memory task and a motor classification task, respectively, higherthan the accuracy of 69.2% and 68.6% obtained by the SVM-MVPA. A networkvisualization analysis showed that the DNN automatically detected features fromareas of the brain related to each task. Without incurring the burden ofhandcrafting the features, the proposed deep decoding method can classify braintask states highly accurately, and is a powerful tool for fMRI researchers.
{{< /details >}}

>**_2019-11-29_**

[**Domain-invariant Stereo Matching Networks**](http://arxiv.org/abs/1911.13287v1)

*Feihu Zhang, Xiaojuan Qi, Ruigang Yang, Victor Prisacariu, Benjamin Wah, Philip Torr*

{{< details "abstract" >}} abstract: State-of-the-art stereo matching networks have difficulties in generalizingto new unseen environments due to significant domain differences, such ascolor, illumination, contrast, and texture. In this paper, we aim at designinga domain-invariant stereo matching network (DSMNet) that generalizes well tounseen scenes. To achieve this goal, we propose i) a novel "domainnormalization" approach that regularizes the distribution of learnedrepresentations to allow them to be invariant to domain differences, and ii) atrainable non-local graph-based filter for extracting robust structural andgeometric representations that can further enhance domain-invariantgeneralizations. When trained on synthetic data and generalized to real testsets, our model performs significantly better than all state-of-the-art models.It even outperforms some deep learning models (e.g. MC-CNN) fine-tuned withtest-domain data.
{{< /details >}}

>**_2019-11-25_**

[**Neural Random Forest Imitation**](http://arxiv.org/abs/1911.10829v1)

*Christoph Reinders, Bodo Rosenhahn*

{{< details "abstract" >}} abstract: We present Neural Random Forest Imitation - a novel approach for transformingrandom forests into neural networks. Existing methods produce very inefficientarchitectures and do not scale. In this paper, we introduce a new method forgenerating data from a random forest and learning a neural network thatimitates it. Without any additional training data, this transformation createsvery efficient neural networks that learn the decision boundaries of a randomforest. The generated model is fully differentiable and can be combined withthe feature extraction in a single pipeline enabling further end-to-endprocessing. Experiments on several real-world benchmark datasets demonstrateoutstanding performance in terms of scalability, accuracy, and learning withvery few training examples. Compared to state-of-the-art mappings, wesignificantly reduce the network size while achieving the same or even improvedaccuracy due to better generalization.
{{< /details >}}

>**_2019-11-23_**

[**On Functional Test Generation for Deep Neural Network IPs**](http://arxiv.org/abs/1911.11550v1)

*Bo Luo, Yu Li, Lingxiao Wei, Qiang Xu*

{{< details "abstract" >}} abstract: Machine learning systems based on deep neural networks (DNNs) producestate-of-the-art results in many applications. Considering the large amount oftraining data and know-how required to generate the network, it is morepractical to use third-party DNN intellectual property (IP) cores for manydesigns. No doubt to say, it is essential for DNN IP vendors to provide testcases for functional validation without leaking their parameters to IP users.To satisfy this requirement, we propose to effectively generate test cases thatactivate parameters as many as possible and propagate their perturbations tooutputs. Then the functionality of DNN IPs can be validated by only checkingtheir outputs. However, it is difficult considering large numbers of parametersand highly non-linearity of DNNs. In this paper, we tackle this problem byjudiciously selecting samples from the DNN training set and applying agradient-based method to generate new test cases. Experimental resultsdemonstrate the efficacy of our proposed solution.
{{< /details >}}

>**_2019-11-08_**

[**Regularized Deep Networks in Intelligent Transportation Systems: A Taxonomy and a Case Study**](http://arxiv.org/abs/1911.03010v1)

*Mohammad Mahdi Bejani, Mehdi Ghatee*

{{< details "abstract" >}} abstract: Intelligent Transportation Systems (ITS) are much correlated with datascience mechanisms. Among the different correlation branches, this paperfocuses on the neural network learning models. Some of the considered modelsare shallow and they get some user-defined features and learn the relationship,while deep models extract the necessary features before learning by themselves.Both of these paradigms are utilized in the recent intelligent transportationsystems (ITS) to support decision-making by the aid of different operationssuch as frequent patterns mining, regression, clustering, and classification.When these learners cannot generalize the results and just memorize thetraining samples, they fail to support the necessities. In these cases, thetesting error is bigger than the training error. This phenomenon is addressedas overfitting in the literature. Because, this issue decreases the reliabilityof learning systems, in ITS applications, we cannot use such over-fittedmachine learning models for different tasks such as traffic prediction, thesignal controlling, safety applications, emergency responses, mode detection,driving evaluation, etc. Besides, deep learning models use a great number ofhyper-parameters, the overfitting in deep models is more attention. To solvethis problem, the regularized learning models can be followed. The aim of thispaper is to review the approaches presented to regularize the overfitting indifferent categories of ITS studies. Then, we give a case study on drivingsafety that uses a regularized version of the convolutional neural network(CNN).
{{< /details >}}

>**_2019-11-07_**

[**How to Prove Your Model Belongs to You: A Blind-Watermark based Framework to Protect Intellectual Property of DNN**](http://arxiv.org/abs/1903.01743v4)

*Zheng Li, Chengyu Hu, Yang Zhang, Shanqing Guo*

{{< details "abstract" >}} abstract: Deep learning techniques have made tremendous progress in a variety ofchallenging tasks, such as image recognition and machine translation, duringthe past decade. Training deep neural networks is computationally expensive andrequires both human and intellectual resources. Therefore, it is necessary toprotect the intellectual property of the model and externally verify theownership of the model. However, previous studies either fail to defend againstthe evasion attack or have not explicitly dealt with fraudulent claims ofownership by adversaries. Furthermore, they can not establish a clearassociation between the model and the creator's identity.  To fill these gaps, in this paper, we propose a novel intellectual propertyprotection (IPP) framework based on blind-watermark for watermarking deepneural networks that meet the requirements of security and feasibility. Ourframework accepts ordinary samples and the exclusive logo as inputs, outputtingnewly generated samples as watermarks, which are almost indistinguishable fromthe origin, and infuses these watermarks into DNN models by assigning specificlabels, leaving the backdoor as the basis for our copyright claim. We evaluatedour IPP framework on two benchmark datasets and 15 popular deep learningmodels. The results show that our framework successfully verifies the ownershipof all the models without a noticeable impact on their primary task. Mostimportantly, we are the first to successfully design and implement ablind-watermark based framework, which can achieve state-of-art performances onundetectability against evasion attack and unforgeability against fraudulentclaims of ownership. Further, our framework shows remarkable robustness andestablishes a clear association between the model and the author's identity.
{{< /details >}}

>**_2019-11-05_**

[**Hierarchical Mixtures of Generators for Adversarial Learning**](http://arxiv.org/abs/1911.02069v1)

*Alper Ahmetoğlu, Ethem Alpaydın*

{{< details "abstract" >}} abstract: Generative adversarial networks (GANs) are deep neural networks that allow usto sample from an arbitrary probability distribution without explicitlyestimating the distribution. There is a generator that takes a latent vector asinput and transforms it into a valid sample from the distribution. There isalso a discriminator that is trained to discriminate such fake samples fromtrue samples of the distribution; at the same time, the generator is trained togenerate fakes that the discriminator cannot tell apart from the true samples.Instead of learning a global generator, a recent approach involves trainingmultiple generators each responsible from one part of the distribution. In thiswork, we review such approaches and propose the hierarchical mixture ofgenerators, inspired from the hierarchical mixture of experts model, thatlearns a tree structure implementing a hierarchical clustering with soft splitsin the decision nodes and local generators in the leaves. Since the generatorsare combined softly, the whole model is continuous and can be trained usinggradient-based optimization, just like the original GAN model. Our experimentson five image data sets, namely, MNIST, FashionMNIST, UTZap50K, Oxford Flowers,and CelebA, show that our proposed model generates samples of high quality anddiversity in terms of popular GAN evaluation metrics. The learned hierarchicalstructure also leads to knowledge extraction.
{{< /details >}}

>**_2019-10-28_**

[**Evaluating the Factual Consistency of Abstractive Text Summarization**](http://arxiv.org/abs/1910.12840v1)

*Wojciech Kryściński, Bryan McCann, Caiming Xiong, Richard Socher*

{{< details "abstract" >}} abstract: Currently used metrics for assessing summarization algorithms do not accountfor whether summaries are factually consistent with source documents. Wepropose a weakly-supervised, model-based approach for verifying factualconsistency and identifying conflicts between source documents and a generatedsummary. Training data is generated by applying a series of rule-basedtransformations to the sentences of source documents. The factual consistencymodel is then trained jointly for three tasks: 1) identify whether sentencesremain factually consistent after transformation, 2) extract a span in thesource documents to support the consistency prediction, 3) extract a span inthe summary sentence that is inconsistent if one exists. Transferring thismodel to summaries generated by several state-of-the art models reveals thatthis highly scalable approach substantially outperforms previous models,including those trained with strong supervision using standard datasets fornatural language inference and fact checking. Additionally, human evaluationshows that the auxiliary span extraction tasks provide useful assistance in theprocess of verifying factual consistency.
{{< /details >}}

>**_2019-10-20_**

[**Through-Wall Pose Imaging in Real-Time with a Many-to-Many Encoder/Decoder Paradigm**](http://arxiv.org/abs/1904.00739v2)

*Kevin Meng, Yu Meng*

{{< details "abstract" >}} abstract: Overcoming the visual barrier and developing "see-through vision" has beenone of mankind's long-standing dreams. Unlike visible light, Radio Frequency(RF) signals penetrate opaque obstructions and reflect highly off humans. Thispaper establishes a deep-learning model that can be trained to reconstructcontinuous video of a 15-point human skeleton even through visual occlusion.The training process adopts a student/teacher learning procedure inspired bythe Feynman learning technique, in which video frames and RF data are firstcollected simultaneously using a co-located setup containing an optical cameraand an RF antenna array transceiver. Next, the video frames are processed witha computer-vision-based gait analysis "teacher" module to generate ground-truthhuman skeletons for each frame. Then, the same type of skeleton is predictedfrom corresponding RF data using a "student" deep-learning model consisting ofa Residual Convolutional Neural Network (CNN), Region Proposal Network (RPN),and Recurrent Neural Network with Long-Short Term Memory (LSTM) that 1)extracts spatial features from RF images, 2) detects all people present in ascene, and 3) aggregates information over many time-steps, respectively. Themodel is shown to both accurately and completely predict the pose of humansbehind visual obstruction solely using RF signals. Primary academiccontributions include the novel many-to-many imaging methodology, uniqueintegration of RPN and LSTM networks, and original training pipeline.
{{< /details >}}

>**_2019-10-15_**

[**MUTE: Data-Similarity Driven Multi-hot Target Encoding for Neural Network Design**](http://arxiv.org/abs/1910.07042v1)

*Mayoore S. Jaiswal, Bumsoo Kang, Jinho Lee, Minsik Cho*

{{< details "abstract" >}} abstract: Target encoding is an effective technique to deliver better performance forconventional machine learning methods, and recently, for deep neural networksas well. However, the existing target encoding approaches require significantincrease in the learning capacity, thus demand higher computation power andmore training data. In this paper, we present a novel and efficient targetencoding scheme, MUTE to improve both generalizability and robustness of atarget model by understanding the inter-class characteristics of a targetdataset. By extracting the confusion level between the target classes in adataset, MUTE strategically optimizes the Hamming distances among targetencoding. Such optimized target encoding offers higher classification strengthfor neural network models with negligible computation overhead and withoutincreasing the model size. When MUTE is applied to the popular imageclassification networks and datasets, our experimental results show that MUTEoffers better generalization and defense against the noises and adversarialattacks over the existing solutions.
{{< /details >}}

>**_2019-10-01_**

[**Efficient Cyber Attacks Detection in Industrial Control Systems Using Lightweight Neural Networks and PCA**](http://arxiv.org/abs/1907.01216v2)

*Moshe Kravchik, Asaf Shabtai*

{{< details "abstract" >}} abstract: Industrial control systems (ICSs) are widely used and vital to industry andsociety. Their failure can have severe impact on both economics and human life.Hence, these systems have become an attractive target for attacks, bothphysical and cyber. A number of attack detection methods have been proposed,however they are characterized by a low detection rate, a substantial falsepositive rate, or are system specific. In this paper, we study an attackdetection method based on simple and lightweight neural networks, namely, 1Dconvolutions and autoencoders. We apply these networks to both the time andfrequency domains of the collected data and discuss pros and cons of eachapproach. We evaluate the suggested method on three popular public datasets andachieve detection rates matching or exceeding previously published detectionresults, while featuring small footprint, short training and detection times,and generality. We also demonstrate the effectiveness of PCA, which, givenproper data preprocessing and feature selection, can provide high attackdetection scores in many settings. Finally, we study the proposed method'srobustness against adversarial attacks, that exploit inherent blind spots ofneural networks to evade detection while achieving their intended physicaleffect. Our results show that the proposed method is robust to such evasionattacks: in order to evade detection, the attacker is forced to sacrifice thedesired physical impact on the system. This finding suggests that neuralnetworks trained under the constraints of the laws of physics can be trustedmore than networks trained under more flexible conditions.
{{< /details >}}

>**_2019-09-26_**

[**Self-Adaptive Soft Voice Activity Detection using Deep Neural Networks for Robust Speaker Verification**](http://arxiv.org/abs/1909.11886v1)

*Youngmoon Jung, Yeunju Choi, Hoirin Kim*

{{< details "abstract" >}} abstract: Voice activity detection (VAD), which classifies frames as speech ornon-speech, is an important module in many speech applications includingspeaker verification. In this paper, we propose a novel method, calledself-adaptive soft VAD, to incorporate a deep neural network (DNN)-based VADinto a deep speaker embedding system. The proposed method is a combination ofthe following two approaches. The first approach is soft VAD, which performs asoft selection of frame-level features extracted from a speaker featureextractor. The frame-level features are weighted by their corresponding speechposteriors estimated from the DNN-based VAD, and then aggregated to generate aspeaker embedding. The second approach is self-adaptive VAD, which fine-tunesthe pre-trained VAD on the speaker verification data to reduce the domainmismatch. Here, we introduce two unsupervised domain adaptation (DA) schemes,namely speech posterior-based DA (SP-DA) and joint learning-based DA (JL-DA).Experiments on a Korean speech database demonstrate that the verificationperformance is improved significantly in real-world environments by usingself-adaptive soft VAD.
{{< /details >}}

>**_2019-09-20_**

[**Writer-Aware CNN for Parsimonious HMM-Based Offline Handwritten Chinese Text Recognition**](http://arxiv.org/abs/1812.09809v2)

*Zi-Rui Wang, Jun Du, Jia-Ming Wang*

{{< details "abstract" >}} abstract: Recently, the hybrid convolutional neural network hidden Markov model(CNN-HMM) has been introduced for offline handwritten Chinese text recognition(HCTR) and has achieved state-of-the-art performance. However, modeling each ofthe large vocabulary of Chinese characters with a uniform and fixed number ofhidden states requires high memory and computational costs and makes the tensof thousands of HMM state classes confusing. Another key issue of CNN-HMM forHCTR is the diversified writing style, which leads to model strain and asignificant performance decline for specific writers. To address these issues,we propose a writer-aware CNN based on parsimonious HMM (WCNN-PHMM). First,PHMM is designed using a data-driven state-tying algorithm to greatly reducethe total number of HMM states, which not only yields a compact CNN by statesharing of the same or similar radicals among different Chinese characters butalso improves the recognition accuracy due to the more accurate modeling oftied states and the lower confusion among them. Second, WCNN integrates eachconvolutional layer with one adaptive layer fed by a writer-dependent vector,namely, the writer code, to extract the irrelevant variability in writerinformation to improve recognition performance. The parameters ofwriter-adaptive layers are jointly optimized with other network parameters inthe training stage, while a multiple-pass decoding strategy is adopted to learnthe writer code and generate recognition results. Validated on the ICDAR 2013competition of CASIA-HWDB database, the more compact WCNN-PHMM of a 7360-classvocabulary can achieve a relative character error rate (CER) reduction of 16.6%over the conventional CNN-HMM without considering language modeling. Byadopting a powerful hybrid language model (N-gram language model and recurrentneural network language model), the CER of WCNN-PHMM is reduced to 3.17%.
{{< /details >}}

>**_2019-09-17_**

[**A Data-Center FPGA Acceleration Platform for Convolutional Neural Networks**](http://arxiv.org/abs/1909.07973v1)

*Xiaoyu Yu, Yuwei Wang, Jie Miao, Ephrem Wu, Heng Zhang, Yu Meng, Bo Zhang, Biao Min, Dewei Chen, Jianlin Gao*

{{< details "abstract" >}} abstract: Intensive computation is entering data centers with multiple workloads ofdeep learning. To balance the compute efficiency, performance, and total costof ownership (TCO), the use of a field-programmable gate array (FPGA) withreconfigurable logic provides an acceptable acceleration capacity and iscompatible with diverse computation-sensitive tasks in the cloud. In thispaper, we develop an FPGA acceleration platform that leverages a unifiedframework architecture for general-purpose convolutional neural network (CNN)inference acceleration at a data center. To overcome the computation bound,4,096 DSPs are assembled and shaped as supertile units (SUs) for differenttypes of convolution, which provide up to 4.2 TOP/s 16-bit fixed-pointperformance at 500 MHz. The interleaved-task-dispatching method is proposed tomap the computation across the SUs, and the memory bound is solved by adispatching-assembling buffering model and broadcast caches. For variousnon-convolution operators, a filter processing unit is designed forgeneral-purpose filter-like/pointwise operators. In the experiment, theperformances of CNN models running on server-class CPUs, a GPU, and an FPGA arecompared. The results show that our design achieves the best FPGA peakperformance and a throughput at the same level as that of the state-of-the-artGPU in data centers, with more than 50 times lower latency.
{{< /details >}}

>**_2019-08-07_**

[**Is artificial data useful for biomedical Natural Language Processing algorithms?**](http://arxiv.org/abs/1907.01055v2)

*Zixu Wang, Julia Ive, Sumithra Velupillai, Lucia Specia*

{{< details "abstract" >}} abstract: A major obstacle to the development of Natural Language Processing (NLP)methods in the biomedical domain is data accessibility. This problem can beaddressed by generating medical data artificially. Most previous studies havefocused on the generation of short clinical text, and evaluation of the datautility has been limited. We propose a generic methodology to guide thegeneration of clinical text with key phrases. We use the artificial data asadditional training data in two key biomedical NLP tasks: text classificationand temporal relation extraction. We show that artificially generated trainingdata used in conjunction with real training data can lead to performance boostsfor data-greedy neural network algorithms. We also demonstrate the usefulnessof the generated data for NLP setups where it fully replaces real trainingdata.
{{< /details >}}

>**_2019-07-08_**

[**Stealing Neural Networks via Timing Side Channels**](http://arxiv.org/abs/1812.11720v4)

*Vasisht Duddu, Debasis Samanta, D Vijay Rao, Valentina E. Balas*

{{< details "abstract" >}} abstract: Deep learning is gaining importance in many applications. However, NeuralNetworks face several security and privacy threats. This is particularlysignificant in the scenario where Cloud infrastructures deploy a service withNeural Network model at the back end. Here, an adversary can extract the NeuralNetwork parameters, infer the regularization hyperparameter, identify if a datapoint was part of the training data, and generate effective transferableadversarial examples to evade classifiers. This paper shows how a NeuralNetwork model is susceptible to timing side channel attack. In this paper, ablack box Neural Network extraction attack is proposed by exploiting the timingside channels to infer the depth of the network. Although, constructing anequivalent architecture is a complex search problem, it is shown howReinforcement Learning with knowledge distillation can effectively reduce thesearch space to infer a target model. The proposed approach has been testedwith VGG architectures on CIFAR10 data set. It is observed that it is possibleto reconstruct substitute models with test accuracy close to the target modelsand the proposed approach is scalable and independent of type of Neural Networkarchitectures.
{{< /details >}}

>**_2019-06-27_**

[**Training Models to Extract Treatment Plans from Clinical Notes Using Contents of Sections with Headings**](http://arxiv.org/abs/1906.11930v1)

*Ananya Poddar, Bharath Dandala, Murthy Devarakonda*

{{< details "abstract" >}} abstract: Objective: Using natural language processing (NLP) to find sentences thatstate treatment plans in a clinical note, would automate plan extraction andwould further enable their use in tools that help providers and care managers.However, as in the most NLP tasks on clinical text, creating gold standard totrain and test NLP models is tedious and expensive. Fortuitously, sometimes butnot always clinical notes contain sections with a heading that identifies thesection as a plan. Leveraging contents of such labeled sections as a noisytraining data, we assessed accuracy of NLP models trained with the data.  Methods: We used common variations of plan headings and rule-based heuristicsto find plan sections with headings in clinical notes, and we extractedsentences from them and formed a noisy training data of plan sentences. Wetrained Support Vector Machine (SVM) and Convolutional Neural Network (CNN)models with the data. We measured accuracy of the trained models on the noisydataset using ten-fold cross validation and separately on a set-aside manuallyannotated dataset.  Results: About 13% of 117,730 clinical notes contained treatment planssections with recognizable headings in the 1001 longitudinal patient recordsthat were obtained from Cleveland Clinic under an IRB approval. We were able toextract and create a noisy training data of 13,492 plan sentences from theclinical notes. CNN achieved best F measures, 0.91 and 0.97 in thecross-validation and set-aside evaluation experiments respectively. SVMslightly underperformed with F measures of 0.89 and 0.96 in the sameexperiments.  Conclusion: Our study showed that the training supervised learning modelsusing noisy plan sentences was effective in identifying them in all clinicalnotes. More broadly, sections with informal headings in clinical notes can be agood source for generating effective training data.
{{< /details >}}

>**_2019-06-22_**

[**Evaluating Computational Language Models with Scaling Properties of Natural Language**](http://arxiv.org/abs/1906.09379v1)

*Shuntaro Takahashi, Kumiko Tanaka-Ishii*

{{< details "abstract" >}} abstract: In this article, we evaluate computational models of natural language withrespect to the universal statistical behaviors of natural language. Statisticalmechanical analyses have revealed that natural language text is characterizedby scaling properties, which quantify the global structure in the vocabularypopulation and the long memory of a text. We study whether five scalingproperties (given by Zipf's law, Heaps' law, Ebeling's method, Taylor's law,and long-range correlation analysis) can serve for evaluation of computationalmodels. Specifically, we test $n$-gram language models, a probabilisticcontext-free grammar (PCFG), language models based on Simon/Pitman-Yorprocesses, neural language models, and generative adversarial networks (GANs)for text generation. Our analysis reveals that language models based onrecurrent neural networks (RNNs) with a gating mechanism (i.e., long short-termmemory, LSTM; a gated recurrent unit, GRU; and quasi-recurrent neural networks,QRNNs) are the only computational models that can reproduce the long memorybehavior of natural language. Furthermore, through comparison with recentlyproposed model-based evaluation methods, we find that the exponent of Taylor'slaw is a good indicator of model quality.
{{< /details >}}

>**_2019-06-05_**

[**Efficient, Lexicon-Free OCR using Deep Learning**](http://arxiv.org/abs/1906.01969v1)

*Marcin Namysl, Iuliu Konya*

{{< details "abstract" >}} abstract: Contrary to popular belief, Optical Character Recognition (OCR) remains achallenging problem when text occurs in unconstrained environments, likenatural scenes, due to geometrical distortions, complex backgrounds, anddiverse fonts. In this paper, we present a segmentation-free OCR system thatcombines deep learning methods, synthetic training data generation, and dataaugmentation techniques. We render synthetic training data using large textcorpora and over 2000 fonts. To simulate text occurring in complex naturalscenes, we augment extracted samples with geometric distortions and with aproposed data augmentation technique - alpha-compositing with backgroundtextures. Our models employ a convolutional neural network encoder to extractfeatures from text images. Inspired by the recent progress in neural machinetranslation and language modeling, we examine the capabilities of bothrecurrent and convolutional neural networks in modeling the interactionsbetween input elements.
{{< /details >}}

>**_2019-05-30_**

[**Unsupervised Deep Learning by Neighbourhood Discovery**](http://arxiv.org/abs/1904.11567v3)

*Jiabo Huang, Qi Dong, Shaogang Gong, Xiatian Zhu*

{{< details "abstract" >}} abstract: Deep convolutional neural networks (CNNs) have demonstrated remarkablesuccess in computer vision by supervisedly learning strong visual featurerepresentations. However, training CNNs relies heavily on the availability ofexhaustive training data annotations, limiting significantly their deploymentand scalability in many application scenarios. In this work, we introduce ageneric unsupervised deep learning approach to training deep models without theneed for any manual label supervision. Specifically, we progressively discoversample anchored/centred neighbourhoods to reason and learn the underlying classdecision boundaries iteratively and accumulatively. Every single neighbourhoodis specially formulated so that all the member samples can share the sameunseen class labels at high probability for facilitating the extraction ofclass discriminative feature representations during training. Experiments onimage classification show the performance advantages of the proposed methodover the state-of-the-art unsupervised learning models on six benchmarksincluding both coarse-grained and fine-grained object image categorisation.
{{< /details >}}

>**_2019-05-11_**

[**Time-Contrastive Learning Based DNN Bottleneck Features for Text-Dependent Speaker Verification**](http://arxiv.org/abs/1704.02373v3)

*Achintya Kr. Sarkar, Zheng-Hua Tan*

{{< details "abstract" >}} abstract: In this paper, we present a time-contrastive learning (TCL) based bottleneck(BN)feature extraction method for speech signals with an application totext-dependent (TD) speaker verification (SV). It is well-known that speechsignals exhibit quasi-stationary behavior in and only in a short interval, andthe TCL method aims to exploit this temporal structure. More specifically, ittrains deep neural networks (DNNs) to discriminate temporal events obtained byuniformly segmenting speech signals, in contrast to existing DNN based BNfeature extraction methods that train DNNs using labeled data to discriminatespeakers or pass-phrases or phones or a combination of them. In the context ofspeaker verification, speech data of fixed pass-phrases are used for TCL-BNtraining, while the pass-phrases used for TCL-BN training are excluded frombeing used for SV, so that the learned features can be considered generic. Themethod is evaluated on the RedDots Challenge 2016 database. Experimentalresults show that TCL-BN is superior to the existing speaker and pass-phrasediscriminant BN features and the Mel-frequency cepstral coefficient feature fortext-dependent speaker verification.
{{< /details >}}

[**Time-Contrastive Learning Based Deep Bottleneck Features for Text-Dependent Speaker Verification**](http://arxiv.org/abs/1905.04554v1)

*Achintya kr. Sarkar, Zheng-Hua Tan, Hao Tang, Suwon Shon, James Glass*

{{< details "abstract" >}} abstract: There are a number of studies about extraction of bottleneck (BN) featuresfrom deep neural networks (DNNs)trained to discriminate speakers, pass-phrasesand triphone states for improving the performance of text-dependent speakerverification (TD-SV). However, a moderate success has been achieved. A recentstudy [1] presented a time contrastive learning (TCL) concept to explore thenon-stationarity of brain signals for classification of brain states. Speechsignals have similar non-stationarity property, and TCL further has theadvantage of having no need for labeled data. We therefore present a TCL basedBN feature extraction method. The method uniformly partitions each speechutterance in a training dataset into a predefined number of multi-framesegments. Each segment in an utterance corresponds to one class, and classlabels are shared across utterances. DNNs are then trained to discriminate allspeech frames among the classes to exploit the temporal structure of speech. Inaddition, we propose a segment-based unsupervised clustering algorithm tore-assign class labels to the segments. TD-SV experiments were conducted on theRedDots challenge database. The TCL-DNNs were trained using speech data offixed pass-phrases that were excluded from the TD-SV evaluation set, so thelearned features can be considered phrase-independent. We compare theperformance of the proposed TCL bottleneck (BN) feature with those ofshort-time cepstral features and BN features extracted from DNNs discriminatingspeakers, pass-phrases, speaker+pass-phrase, as well as monophones whose labelsand boundaries are generated by three different automatic speech recognition(ASR) systems. Experimental results show that the proposed TCL-BN outperformscepstral features and speaker+pass-phrase discriminant BN features, and itsperformance is on par with those of ASR derived BN features. Moreover,....
{{< /details >}}

>**_2019-05-04_**

[**Saliency for Fine-grained Object Recognition in Domains with Scarce Training Data**](http://arxiv.org/abs/1808.00262v3)

*Carola Figueroa Flores, Abel Gonzalez-García, Joost van de Weijer, Bogdan Raducanu*

{{< details "abstract" >}} abstract: This paper investigates the role of saliency to improve the classificationaccuracy of a Convolutional Neural Network (CNN) for the case when scarcetraining data is available. Our approach consists in adding a saliency branchto an existing CNN architecture which is used to modulate the standardbottom-up visual features from the original image input, acting as anattentional mechanism that guides the feature extraction process. The main aimof the proposed approach is to enable the effective training of a fine-grainedrecognition model with limited training samples and to improve the performanceon the task, thereby alleviating the need to annotate large dataset. % The vastmajority of saliency methods are evaluated on their ability to generatesaliency maps, and not on their functionality in a complete vision pipeline.Our proposed pipeline allows to evaluate saliency methods for the high-leveltask of object recognition. We perform extensive experiments on variousfine-grained datasets (Flowers, Birds, Cars, and Dogs) under differentconditions and show that saliency can considerably improve the network'sperformance, especially for the case of scarce training data. Furthermore, ourexperiments show that saliency methods that obtain improved saliency maps (asmeasured by traditional saliency benchmarks) also translate to saliency methodsthat yield improved performance gains when applied in an object recognitionpipeline.
{{< /details >}}

>**_2019-04-08_**

[**Diversity in Faces**](http://arxiv.org/abs/1901.10436v6)

*Michele Merler, Nalini Ratha, Rogerio S. Feris, John R. Smith*

{{< details "abstract" >}} abstract: Face recognition is a long standing challenge in the field of ArtificialIntelligence (AI). The goal is to create systems that accurately detect,recognize, verify, and understand human faces. There are significant technicalhurdles in making these systems accurate, particularly in unconstrainedsettings due to confounding factors related to pose, resolution, illumination,occlusion, and viewpoint. However, with recent advances in neural networks,face recognition has achieved unprecedented accuracy, largely built ondata-driven deep learning methods. While this is encouraging, a critical aspectthat is limiting facial recognition accuracy and fairness is inherent facialdiversity. Every face is different. Every face reflects something unique aboutus. Aspects of our heritage - including race, ethnicity, culture, geography -and our individual identify - age, gender, and other visible manifestations ofself-expression, are reflected in our faces. We expect face recognition to workequally accurately for every face. Face recognition needs to be fair. As werely on data-driven methods to create face recognition technology, we need toensure necessary balance and coverage in training data. However, there arestill scientific questions about how to represent and extract pertinent facialfeatures and quantitatively measure facial diversity. Towards this goal,Diversity in Faces (DiF) provides a data set of one million annotated humanface images for advancing the study of facial diversity. The annotations aregenerated using ten well-established facial coding schemes from the scientificliterature. The facial coding schemes provide human-interpretable quantitativemeasures of facial features. We believe that by making the extracted codingschemes available on a large set of faces, we can accelerate research anddevelopment towards creating more fair and accurate facial recognition systems.
{{< /details >}}

>**_2019-04-04_**

[**Active Transfer Learning Network: A Unified Deep Joint Spectral-Spatial Feature Learning Model For Hyperspectral Image Classification**](http://arxiv.org/abs/1904.02454v1)

*Cheng Deng, Yumeng Xue, Xianglong Liu, Chao Li, Dacheng Tao*

{{< details "abstract" >}} abstract: Deep learning has recently attracted significant attention in the field ofhyperspectral images (HSIs) classification. However, the construction of anefficient deep neural network (DNN) mostly relies on a large number of labeledsamples being available. To address this problem, this paper proposes a unifieddeep network, combined with active transfer learning that can be well-trainedfor HSIs classification using only minimally labeled training data. Morespecifically, deep joint spectral-spatial feature is first extracted throughhierarchical stacked sparse autoencoder (SSAE) networks. Active transferlearning is then exploited to transfer the pre-trained SSAE network and thelimited training samples from the source domain to the target domain, where theSSAE network is subsequently fine-tuned using the limited labeled samplesselected from both source and target domain by corresponding active learningstrategies. The advantages of our proposed method are threefold: 1) the networkcan be effectively trained using only limited labeled samples with the help ofnovel active learning strategies; 2) the network is flexible and scalableenough to function across various transfer situations, including cross-datasetand intra-image; 3) the learned deep joint spectral-spatial featurerepresentation is more generic and robust than many joint spectral-spatialfeature representation. Extensive comparative evaluations demonstrate that ourproposed method significantly outperforms many state-of-the-art approaches,including both traditional and deep network-based methods, on three populardatasets.
{{< /details >}}

>**_2019-03-31_**

[**BlackMarks: Blackbox Multibit Watermarking for Deep Neural Networks**](http://arxiv.org/abs/1904.00344v1)

*Huili Chen, Bita Darvish Rouhani, Farinaz Koushanfar*

{{< details "abstract" >}} abstract: Deep Neural Networks have created a paradigm shift in our ability tocomprehend raw data in various important fields ranging from computer visionand natural language processing to intelligence warfare and healthcare. WhileDNNs are increasingly deployed either in a white-box setting where the modelinternal is publicly known, or a black-box setting where only the model outputsare known, a practical concern is protecting the models against IntellectualProperty (IP) infringement. We propose BlackMarks, the first end-to-endmulti-bit watermarking framework that is applicable in the black-box scenario.BlackMarks takes the pre-trained unmarked model and the owner's binarysignature as inputs and outputs the corresponding marked model with a set ofwatermark keys. To do so, BlackMarks first designs a model-dependent encodingscheme that maps all possible classes in the task to bit '0' and bit '1' byclustering the output activations into two groups. Given the owner's watermarksignature (a binary string), a set of key image and label pairs are designedusing targeted adversarial attacks. The watermark (WM) is then embedded in theprediction behavior of the target DNN by fine-tuning the model with generatedWM key set. To extract the WM, the remote model is queried by the WM key imagesand the owner's signature is decoded from the corresponding predictionsaccording to the designed encoding scheme. We perform a comprehensiveevaluation of BlackMarks's performance on MNIST, CIFAR10, ImageNet datasets andcorroborate its effectiveness and robustness. BlackMarks preserves thefunctionality of the original DNN and incurs negligible WM embedding runtimeoverhead as low as 2.054%.
{{< /details >}}

>**_2019-02-25_**

[**Short-term Road Traffic Prediction based on Deep Cluster at Large-scale Networks**](http://arxiv.org/abs/1902.09601v1)

*Lingyi Han, Kan Zheng, Long Zhao, Xianbin Wang, Xuemin Shen*

{{< details "abstract" >}} abstract: Short-term road traffic prediction (STTP) is one of the most importantmodules in Intelligent Transportation Systems (ITS). However, network-levelSTTP still remains challenging due to the difficulties both in modeling thediverse traffic patterns and tacking high-dimensional time series with lowlatency. Therefore, a framework combining with a deep clustering (DeepCluster)module is developed for STTP at largescale networks in this paper. TheDeepCluster module is proposed to supervise the representation learning in avisualized way from the large unlabeled dataset. More specifically, to fullyexploit the traffic periodicity, the raw series is first split into a number ofsub-series for triplets generation. The convolutional neural networks (CNNs)with triplet loss are utilized to extract the features of shape by transferringthe series into visual images. The shape-based representations are then usedfor road segments clustering. Thereafter, motivated by the fact that the roadsegments in a group have similar patterns, a model sharing strategy is furtherproposed to build recurrent NNs (RNNs)-based predictions through a group-basedmodel (GM), instead of individual-based model (IM) in which one model are builtfor one road exclusively. Our framework can not only significantly reduce thenumber of models and cost, but also increase the number of training data andthe diversity of samples. In the end, we evaluate the proposed framework overthe network of Liuli Bridge in Beijing. Experimental results show that theDeepCluster can effectively cluster the road segments and GM can achievecomparable performance against the IM with less number of models.
{{< /details >}}

>**_2019-01-23_**

[**Predicting Parkinson's Disease using Latent Information extracted from Deep Neural Networks**](http://arxiv.org/abs/1901.07822v1)

*Ilianna Kollia, Andreas-Georgios Stafylopatis, Stefanos Kollias*

{{< details "abstract" >}} abstract: This paper presents a new method for medical diagnosis of neurodegenerativediseases, such as Parkinson's, by extracting and using latent information fromtrained Deep convolutional, or convolutional-recurrent Neural Networks (DNNs).In particular, our approach adopts a combination of transfer learning, k-meansclustering and k-Nearest Neighbour classification of deep neural networklearned representations to provide enriched prediction of the disease based onMRI and/or DaT Scan data. A new loss function is introduced and used in thetraining of the DNNs, so as to perform adaptation of the generated learnedrepresentations between data from different medical environments. Results arepresented using a recently published database of Parkinson's relatedinformation, which was generated and evaluated in a hospital environment.
{{< /details >}}

>**_2019-01-14_**

[**Predicting Video Saliency with Object-to-Motion CNN and Two-layer Convolutional LSTM**](http://arxiv.org/abs/1709.06316v3)

*Lai Jiang, Mai Xu, Zulin Wang*

{{< details "abstract" >}} abstract: Over the past few years, deep neural networks (DNNs) have exhibited greatsuccess in predicting the saliency of images. However, there are few works thatapply DNNs to predict the saliency of generic videos. In this paper, we proposea novel DNN-based video saliency prediction method. Specifically, we establisha large-scale eye-tracking database of videos (LEDOV), which providessufficient data to train the DNN models for predicting video saliency. Throughthe statistical analysis of our LEDOV database, we find that human attention isnormally attracted by objects, particularly moving objects or the moving partsof objects. Accordingly, we propose an object-to-motion convolutional neuralnetwork (OM-CNN) to learn spatio-temporal features for predicting theintra-frame saliency via exploring the information of both objectness andobject motion. We further find from our database that there exists a temporalcorrelation of human attention with a smooth saliency transition across videoframes. Therefore, we develop a two-layer convolutional long short-term memory(2C-LSTM) network in our DNN-based method, using the extracted features ofOM-CNN as the input. Consequently, the inter-frame saliency maps of videos canbe generated, which consider the transition of attention across video frames.Finally, the experimental results show that our method advances thestate-of-the-art in video saliency prediction.
{{< /details >}}

>**_2018-12-26_**

[**Deep Convolutional Generative Adversarial Network Based Food Recognition Using Partially Labeled Data**](http://arxiv.org/abs/1812.10179v1)

*Bappaditya Mandal, N. B. Puhan, Avijit Verma*

{{< details "abstract" >}} abstract: Traditional machine learning algorithms using hand-crafted feature extractiontechniques (such as local binary pattern) have limited accuracy because of highvariation in images of the same class (or intra-class variation) for foodrecognition task. In recent works, convolutional neural networks (CNN) havebeen applied to this task with better results than all previously reportedmethods. However, they perform best when trained with large amount of annotated(labeled) food images. This is problematic when obtained in large volume,because they are expensive, laborious and impractical. Our work aims atdeveloping an efficient deep CNN learning-based method for food recognitionalleviating these limitations by using partially labeled training data ongenerative adversarial networks (GANs). We make new enhancements to theunsupervised training architecture introduced by Goodfellow et al. (2014),which was originally aimed at generating new data by sampling a dataset. Inthis work, we make modifications to deep convolutional GANs to make them robustand efficient for classifying food images. Experimental results on benchmarkingdatasets show the superiority of our proposed method as compared to thecurrent-state-of-the-art methodologies even when trained with partially labeledtraining data.
{{< /details >}}

>**_2018-12-07_**

[**Convolutional Neural Network Architectures for Signals Supported on Graphs**](http://arxiv.org/abs/1805.00165v2)

*Fernando Gama, Antonio G. Marques, Geert Leus, Alejandro Ribeiro*

{{< details "abstract" >}} abstract: Two architectures that generalize convolutional neural networks (CNNs) forthe processing of signals supported on graphs are introduced. We start with theselection graph neural network (GNN), which replaces linear time invariantfilters with linear shift invariant graph filters to generate convolutionalfeatures and reinterprets pooling as a possibly nonlinear subsampling stagewhere nearby nodes pool their information in a set of preselected sample nodes.A key component of the architecture is to remember the position of samplednodes to permit computation of convolutional features at deeper layers. Thesecond architecture, dubbed aggregation GNN, diffuses the signal through thegraph and stores the sequence of diffused components observed by a designatednode. This procedure effectively aggregates all components into a stream ofinformation having temporal structure to which the convolution and poolingstages of regular CNNs can be applied. A multinode version of aggregation GNNsis further introduced for operation in large scale graphs. An importantproperty of selection and aggregation GNNs is that they reduce to conventionalCNNs when particularized to time signals reinterpreted as graph signals in acirculant graph. Comparative numerical analyses are performed in a sourcelocalization application over synthetic and real-world networks. Performance isalso evaluated for an authorship attribution problem and text categoryclassification. Multinode aggregation GNNs are consistently the best performingGNN architecture.
{{< /details >}}

>**_2018-12-05_**

[**Learning to generate filters for convolutional neural networks**](http://arxiv.org/abs/1812.01894v1)

*Wei Shen, Rujie Liu*

{{< details "abstract" >}} abstract: Conventionally, convolutional neural networks (CNNs) process different imageswith the same set of filters. However, the variations in images pose achallenge to this fashion. In this paper, we propose to generatesample-specific filters for convolutional layers in the forward pass. Since thefilters are generated on-the-fly, the model becomes more flexible and canbetter fit the training data compared to traditional CNNs. In order to obtainsample-specific features, we extract the intermediate feature maps from anautoencoder. As filters are usually high dimensional, we propose to learn a setof coefficients instead of a set of filters. These coefficients are used tolinearly combine the base filters from a filter repository to generate thefinal filters for a CNN. The proposed method is evaluated on MNIST, MTFL andCIFAR10 datasets. Experiment results demonstrate that the classificationaccuracy of the baseline model can be improved by using the proposed filtergeneration method.
{{< /details >}}

>**_2018-12-04_**

[**Inferring Remote Channel State Information: Cramér-Rao Lower Bound and Deep Learning Implementation**](http://arxiv.org/abs/1812.01223v1)

*Zhiyuan Jiang, Ziyan He, Sheng Chen, Andreas F. Molisch, Sheng Zhou, Zhisheng Niu*

{{< details "abstract" >}} abstract: Channel state information (CSI) is of vital importance in wirelesscommunication systems. Existing CSI acquisition methods usually rely on pilottransmissions, and geographically separated base stations (BSs) withnon-correlated CSI need to be assigned with orthogonal pilots which occupyexcessive system resources. Our previous work adopts a data-driven deeplearning based approach which leverages the CSI at a local BS to infer the CSIremotely, however the relevance of CSI between separated BSs is not specifiedexplicitly. In this paper, we exploit a model-based methodology to derive theCram\'er-Rao lower bound (CRLB) of remote CSI inference given the local CSI.Although the model is simplified, the derived CRLB explicitly illustrates therelationship between the inference performance and several key systemparameters, e.g., terminal distance and antenna array size. In particular, itshows that by leveraging multiple local BSs, the inference error exhibits alarger power-law decay rate (w.r.t. number of antennas), compared with a singlelocal BS; this explains and validates our findings in evaluating thedeep-neural-network-based (DNN-based) CSI inference. We further improve on theDNN-based method by employing dropout and deeper networks, and show aninference performance of approximately $90\%$ accuracy in a realistic scenariowith CSI generated by a ray-tracing simulator.
{{< /details >}}

>**_2018-11-30_**

[**Cosmological constraints from noisy convergence maps through deep learning**](http://arxiv.org/abs/1807.08732v2)

*Janis Fluri, Tomasz Kacprzak, Aurelien Lucchi, Alexandre Refregier, Adam Amara, Thomas Hofmann*

{{< details "abstract" >}} abstract: Deep learning is a powerful analysis technique that has recently beenproposed as a method to constrain cosmological parameters from weak lensingmass maps. Due to its ability to learn relevant features from the data, it isable to extract more information from the mass maps than the commonly usedpower spectrum, and thus achieve better precision for cosmological parametermeasurement. We explore the advantage of Convolutional Neural Networks (CNN)over the power spectrum for varying levels of shape noise and differentsmoothing scales applied to the maps. We compare the cosmological constraintsfrom the two methods in the $\Omega_M-\sigma_8$ plane for sets of 400 deg$^2$convergence maps. We find that, for a shape noise level corresponding to 8.53galaxies/arcmin$^2$ and the smoothing scale of $\sigma_s = 2.34$ arcmin, thenetwork is able to generate 45% tighter constraints. For smaller smoothingscale of $\sigma_s = 1.17$ the improvement can reach $\sim 50 \%$, while forlarger smoothing scale of $\sigma_s = 5.85$, the improvement decreases to 19%.The advantage generally decreases when the noise level and smoothing scalesincrease. We present a new training strategy to train the neural network withnoisy data, as well as considerations for practical applications of the deeplearning approach.
{{< /details >}}

>**_2018-11-27_**

[**AI Matrix - Synthetic Benchmarks for DNN**](http://arxiv.org/abs/1812.00886v1)

*Wei Wei, Lingjie Xu, Lingling Jin, Wei Zhang, Tianjun Zhang*

{{< details "abstract" >}} abstract: Deep neural network (DNN) architectures, such as convolutional neuralnetworks (CNN), involve heavy computation and require hardware, such as CPU,GPU, and AI accelerators, to provide the massive computing power. With the manyvarieties of AI hardware prevailing on the market, it is often hard to decidewhich one is the best to use. Thus, benchmarking AI hardware effectivelybecomes important and is of great help to select and optimize AI hardware.Unfortunately, there are few AI benchmarks available in both academia andindustry. Examples are BenchNN[1], DeepBench[2], and Dawn Bench[3], which areusually a collection of typical real DNN applications. While these benchmarksprovide performance comparison across different AI hardware, they suffer from anumber of drawbacks. First, they cannot adapt to the emerging changes of DNNalgorithms and are fixed once selected. Second, they contain tens to hundredsof applications and take very long time to finish running. Third, they aremainly selected from open sources, which are restricted by copyright and arenot representable to proprietary applications. In this work, a syntheticbenchmarks framework is firstly proposed to address the above drawbacks of AIbenchmarks. Instead of pre-selecting a set of open-sourced benchmarks andrunning all of them, the synthetic approach generates only a one or fewbenchmarks that best represent a broad range of applications using profiledworkload characteristics data of these applications. Thus, it can adapt toemerging changes of new DNN algorithms by re-profiling new applications andupdating itself, greatly reduce benchmark count and running time, and stronglyrepresent DNN applications of interests. The generated benchmarks are called AIMatrix, serving as a performance benchmarks matching the statistical workloadcharacteristics of a combination of applications of interests.
{{< /details >}}

>**_2018-11-12_**

[**Lunar Crater Identification via Deep Learning**](http://arxiv.org/abs/1803.02192v3)

*Ari Silburt, Mohamad Ali-Dib, Chenchong Zhu, Alan Jackson, Diana Valencia, Yevgeni Kissin, Daniel Tamayo, Kristen Menou*

{{< details "abstract" >}} abstract: Crater counting on the Moon and other bodies is crucial to constrain thedynamical history of the Solar System. This has traditionally been done byvisual inspection of images, thus limiting the scope, efficiency, and/oraccuracy of retrieval. In this paper we demonstrate the viability of usingconvolutional neural networks (CNNs) to determine the positions and sizes ofcraters from Lunar digital elevation maps (DEMs). We recover 92% of cratersfrom the human-generated test set and almost double the total number of craterdetections. Of these new craters, 15% are smaller in diameter than the minimumcrater size in the ground-truth dataset. Our median fractional longitude,latitude and radius errors are 11% or less, representing good agreement withthe human-generated datasets. From a manual inspection of 361 new craters weestimate the false positive rate of new craters to be 11%. Moreover, ourMoon-trained CNN performs well when tested on DEM images of Mercury, detectinga large fraction of craters in each map. Our results suggest that deep learningwill be a useful tool for rapidly and automatically extracting craters onvarious Solar System bodies. We make our code and data publicly available athttps://github.com/silburt/DeepMoon.git andhttps://doi.org/10.5281/zenodo.1133969 .
{{< /details >}}

>**_2018-09-05_**

[**Modified Diversity of Class Probability Estimation Co-training for Hyperspectral Image Classification**](http://arxiv.org/abs/1809.01436v1)

*Yan Ju, Lingling Li, Licheng Jiao, Zhongle Ren, Biao Hou, Shuyuan Yang*

{{< details "abstract" >}} abstract: Due to the limited amount and imbalanced classes of labeled training data,the conventional supervised learning can not ensure the discrimination of thelearned feature for hyperspectral image (HSI) classification. In this paper, wepropose a modified diversity of class probability estimation (MDCPE) with twodeep neural networks to learn spectral-spatial feature for HSI classification.In co-training phase, recurrent neural network (RNN) and convolutional neuralnetwork (CNN) are utilized as two learners to extract features from labeled andunlabeled data. Based on the extracted features, MDCPE selects most crediblesamples to update initial labeled data by combining k-means clustering with thetraditional diversity of class probability estimation (DCPE) co-training. Inthis way, MDCPE can keep new labeled data class-balanced and extractdiscriminative features for both the minority and majority classes. Duringtesting process, classification results are acquired by co-decision of the twolearners. Experimental results demonstrate that the proposed semi-supervisedco-training method can make full use of unlabeled information to enhancegenerality of the learners and achieve favorable accuracies on all three widelyused data sets: Salinas, Pavia University and Pavia Center.
{{< /details >}}

>**_2018-07-25_**

[**Supervised and Semi-Supervised Deep Neural Networks for CSI-Based Authentication**](http://arxiv.org/abs/1807.09469v1)

*Qian Wang, Hang Li, Zhi Chen, Dou Zhao, Shuang Ye, Jiansheng Cai*

{{< details "abstract" >}} abstract: From the viewpoint of physical-layer authentication, spoofing attacks can befoiled by checking channel state information (CSI). Existing CSI-basedauthentication algorithms mostly require a deep knowledge of the channel todeliver decent performance. In this paper, we investigate CSI-basedauthenticators that can spare the effort to predetermine channel properties byutilizing deep neural networks (DNNs). We first propose a convolutional neuralnetwork (CNN)-enabled authenticator that is able to extract the local featuresin CSI. Next, we employ the recurrent neural network (RNN) to capture thedependencies between different frequencies in CSI. In addition, we propose touse the convolutional recurrent neural network (CRNN)---a combination of theCNN and the RNN---to learn local and contextual information in CSI for userauthentication. To effectively train these DNNs, one needs a large amount oflabeled channel records. However, it is often expensive to label large channelobservations in the presence of a spoofer. In view of this, we further study acase in which only a small part of the the channel observations are labeled. Tohandle it, we extend these DNNs-enabled approaches into semi-supervised ones.This extension is based on a semi-supervised learning technique that employsboth the labeled and unlabeled data to train a DNN. To be specific, oursemi-supervised method begins by generating pseudo labels for the unlabeledchannel samples through implementing the K-means algorithm in a semi-supervisedmanner. Subsequently, both the labeled and pseudo labeled data are exploited topre-train a DNN, which is then fine-tuned based on the labeled channel records.
{{< /details >}}

[**Distinctive-attribute Extraction for Image Captioning**](http://arxiv.org/abs/1807.09434v1)

*Boeun Kim, Young Han Lee, Hyedong Jung, Choongsang Cho*

{{< details "abstract" >}} abstract: Image captioning, an open research issue, has been evolved with the progressof deep neural networks. Convolutional neural networks (CNNs) and recurrentneural networks (RNNs) are employed to compute image features and generatenatural language descriptions in the research. In previous works, a captioninvolving semantic description can be generated by applying additionalinformation into the RNNs. In this approach, we propose a distinctive-attributeextraction (DaE) which explicitly encourages significant meanings to generatean accurate caption describing the overall meaning of the image with theirunique situation. Specifically, the captions of training images are analyzed byterm frequency-inverse document frequency (TF-IDF), and the analyzed semanticinformation is trained to extract distinctive-attributes for inferringcaptions. The proposed scheme is evaluated on a challenge data, and it improvesan objective performance while describing images in more detail.
{{< /details >}}

>**_2018-07-04_**

[**Transfer Learning for Clinical Time Series Analysis using Recurrent Neural Networks**](http://arxiv.org/abs/1807.01705v1)

*Priyanka Gupta, Pankaj Malhotra, Lovekesh Vig, Gautam Shroff*

{{< details "abstract" >}} abstract: Deep neural networks have shown promising results for various clinicalprediction tasks such as diagnosis, mortality prediction, predicting durationof stay in hospital, etc. However, training deep networks -- such as thosebased on Recurrent Neural Networks (RNNs) -- requires large labeled data, highcomputational resources, and significant hyperparameter tuning effort. In thiswork, we investigate as to what extent can transfer learning address theseissues when using deep RNNs to model multivariate clinical time series. Weconsider transferring the knowledge captured in an RNN trained on severalsource tasks simultaneously using a large labeled dataset to build the modelfor a target task with limited labeled data. An RNN pre-trained on severaltasks provides generic features, which are then used to build simpler linearmodels for new target tasks without training task-specific RNNs. Forevaluation, we train a deep RNN to identify several patient phenotypes on timeseries from MIMIC-III database, and then use the features extracted using thatRNN to build classifiers for identifying previously unseen phenotypes, and alsofor a seemingly unrelated task of in-hospital mortality. We demonstrate that(i) models trained on features extracted using pre-trained RNN outperform or,in the worst case, perform as well as task-specific RNNs; (ii) the models usingfeatures from pre-trained models are more robust to the size of labeled datathan task-specific RNNs; and (iii) features extracted using pre-trained RNN aregeneric enough and perform better than typical statistical hand-craftedfeatures.
{{< /details >}}

>**_2018-06-11_**

[**Turning Your Weakness Into a Strength: Watermarking Deep Neural Networks by Backdooring**](http://arxiv.org/abs/1802.04633v3)

*Yossi Adi, Carsten Baum, Moustapha Cisse, Benny Pinkas, Joseph Keshet*

{{< details "abstract" >}} abstract: Deep Neural Networks have recently gained lots of success after enablingseveral breakthroughs in notoriously challenging problems. Training thesenetworks is computationally expensive and requires vast amounts of trainingdata. Selling such pre-trained models can, therefore, be a lucrative businessmodel. Unfortunately, once the models are sold they can be easily copied andredistributed. To avoid this, a tracking mechanism to identify models as theintellectual property of a particular vendor is necessary.  In this work, we present an approach for watermarking Deep Neural Networks ina black-box way. Our scheme works for general classification tasks and caneasily be combined with current learning algorithms. We show experimentallythat such a watermark has no noticeable impact on the primary task that themodel is designed for and evaluate the robustness of our proposal against amultitude of practical attacks. Moreover, we provide a theoretical analysis,relating our approach to previous work on backdooring.
{{< /details >}}

>**_2018-05-31_**

[**DeepSigns: A Generic Watermarking Framework for IP Protection of Deep Learning Models**](http://arxiv.org/abs/1804.00750v2)

*Bita Darvish Rouhani, Huili Chen, Farinaz Koushanfar*

{{< details "abstract" >}} abstract: Deep Learning (DL) models have caused a paradigm shift in our ability tocomprehend raw data in various important fields, ranging from intelligencewarfare and healthcare to autonomous transportation and automatedmanufacturing. A practical concern, in the rush to adopt DL models as aservice, is protecting the models against Intellectual Property (IP)infringement. The DL models are commonly built by allocating significantcomputational resources that process vast amounts of proprietary training data.The resulting models are therefore considered to be the IP of the model builderand need to be protected to preserve the owner's competitive advantage.  This paper proposes DeepSigns, a novel end-to-end IP protection frameworkthat enables insertion of coherent digital watermarks in contemporary DLmodels. DeepSigns, for the first time, introduces a generic watermarkingmethodology that can be used for protecting DL owner's IP rights in bothwhite-box and black-box settings, where the adversary may or may not have theknowledge of the model internals. The suggested methodology is based onembedding the owner's signature (watermark) in the probability density function(pdf) of the data abstraction obtained in different layers of a DL model.DeepSigns can demonstrably withstand various removal and transformationattacks, including model compression, model fine-tuning, and watermarkoverwriting. Proof-of-concept evaluations on MNIST, and CIFAR10 datasets, aswell as a wide variety of neural network architectures including Wide ResidualNetworks, Convolution Neural Networks, and Multi-Layer Perceptrons corroborateDeepSigns' effectiveness and applicability.
{{< /details >}}

>**_2018-05-18_**

[**Mixup-Based Acoustic Scene Classification Using Multi-Channel Convolutional Neural Network**](http://arxiv.org/abs/1805.07319v1)

*Kele Xu, Dawei Feng, Haibo Mi, Boqing Zhu, Dezhi Wang, Lilun Zhang, Hengxing Cai, Shuwen Liu*

{{< details "abstract" >}} abstract: Audio scene classification, the problem of predicting class labels of audioscenes, has drawn lots of attention during the last several years. However, itremains challenging and falls short of accuracy and efficiency. Recently,Convolutional Neural Network (CNN)-based methods have achieved betterperformance with comparison to the traditional methods. Nevertheless,conventional single channel CNN may fail to consider the fact that additionalcues may be embedded in the multi-channel recordings. In this paper, we explorethe use of Multi-channel CNN for the classification task, which aims to extractfeatures from different channels in an end-to-end manner. We conduct theevaluation compared with the conventional CNN and traditional Gaussian MixtureModel-based methods. Moreover, to improve the classification accuracy further,this paper explores the using of mixup method. In brief, mixup trains theneural network on linear combinations of pairs of the representation of audioscene examples and their labels. By employing the mixup approach for dataargumentation, the novel model can provide higher prediction accuracy androbustness in contrast with previous models, while the generalization error canalso be reduced on the evaluation data.
{{< /details >}}

>**_2018-05-16_**

[**Convolutional Neural Network Architecture for Recovering Watermark Synchronization**](http://arxiv.org/abs/1805.06199v1)

*Wook-Hyung Kim, Jong-Uk Hou, Seung-Min Mun, Heung-Kyu Lee*

{{< details "abstract" >}} abstract: Since real-time contents can be captured and downloaded very easily,copyright infringement has become a serious problem. In order to reduce theloss caused by copyright infringement, copyright owners insert a watermark inthe content to protect the copyright using illegal distribution route trackingand copyright authentication. However, whereas many existing watermarkingtechniques are robust to signal distortion such as compression, they arevulnerable to geometric distortion that causes synchronization errors. Inparticular, capturing real-time content in Internet browsers and smartphoneapplications is problematic because geometric distortion such as scaling andtranslation frequently occurs. In this paper, we propose a convolutional neuralnetwork-based template architecture that compensates for the disadvantages ofexisting watermarking techniques that are vulnerable to geometric distortion.The proposed template consists of a template generation network, a templateextraction network, and a template matching network. The template generationnetwork generates a template in the form of noise and the template is insertedinto certain pre-defined spatial locations of the image. The extraction networkdetects spatial locations where the template is inserted in the image. Finally,the template matching network estimates the parameters of the geometricdistortion by comparing the shape of spatial locations where the template wasinserted with the locations where the template was detected. It is possible torecover an image in its original geometrical form using the estimatedparameters, and as a result, watermarks applied using existing watermarkingtechniques that are vulnerable to geometric distortion can be decoded normally.
{{< /details >}}

>**_2018-04-20_**

[**A Deep Representation Empowered Distant Supervision Paradigm for Clinical Information Extraction**](http://arxiv.org/abs/1804.07814v1)

*Yanshan Wang, Sunghwan Sohn, Sijia Liu, Feichen Shen, Liwei Wang, Elizabeth J. Atkinson, Shreyasee Amin, Hongfang Liu*

{{< details "abstract" >}} abstract: Objective: To automatically create large labeled training datasets and reducethe efforts of feature engineering for training accurate machine learningmodels for clinical information extraction. Materials and Methods: We propose adistant supervision paradigm empowered by deep representation for extractinginformation from clinical text. In this paradigm, the rule-based NLP algorithmsare utilized to generate weak labels and create large training datasetsautomatically. Additionally, we use pre-trained word embeddings as deeprepresentation to eliminate the need of task-specific feature engineering formachine learning. We evaluated the effectiveness of the proposed paradigm ontwo clinical information extraction tasks: smoking status extraction andproximal femur (hip) fracture extraction. We tested three prevalent machinelearning models, namely, Convolutional Neural Networks (CNN), Support VectorMachine (SVM), and Random Forrest (RF). Results: The results indicate that CNNis the best fit to the proposed distant supervision paradigm. It outperformsthe rule-based NLP algorithms given large datasets by capturing additionalextraction patterns. We also verified the advantage of word embedding featurerepresentation in the paradigm over term frequency-inverse document frequency(tf-idf) and topic modeling representations. Discussion: In the clinicaldomain, the limited amount of labeled data is always a bottleneck for applyingmachine learning. Additionally, the performance of machine learning approacheshighly depends on task-specific feature engineering. The proposed paradigmcould alleviate those problems by leveraging rule-based NLP algorithms toautomatically assign weak labels and eliminating the need of task-specificfeature engineering using word embedding feature representation.
{{< /details >}}

[**Facial Attributes: Accuracy and Adversarial Robustness**](http://arxiv.org/abs/1801.02480v2)

*Andras Rozsa, Manuel Günther, Ethan M. Rudd, Terrance E. Boult*

{{< details "abstract" >}} abstract: Facial attributes, emerging soft biometrics, must be automatically andreliably extracted from images in order to be usable in stand-alone systems.While recent methods extract facial attributes using deep neural networks(DNNs) trained on labeled facial attribute data, the robustness of deepattribute representations has not been evaluated. In this paper, we examine therepresentational stability of several approaches that recently advanced thestate of the art on the CelebA benchmark by generating adversarial examplesformed by adding small, non-random perturbations to inputs yielding alteredclassifications. We show that our fast flipping attribute (FFA) techniquegenerates more adversarial examples than traditional algorithms, and that theadversarial robustness of DNNs varies highly between facial attributes. We alsotest the correlation of facial attributes and find that only for relatedattributes do the formed adversarial perturbations change the classification ofothers. Finally, we introduce the concept of natural adversarial samples, i.e.,misclassified images where predictions can be corrected via smallperturbations. We demonstrate that natural adversarial samples commonly occurand show that many of these images remain misclassified even with additionaltraining epochs, even though their correct classification may require only asmall adjustment to network parameters.
{{< /details >}}

>**_2018-03-29_**

[**Explanation Methods in Deep Learning: Users, Values, Concerns and Challenges**](http://arxiv.org/abs/1803.07517v2)

*Gabrielle Ras, Marcel van Gerven, Pim Haselager*

{{< details "abstract" >}} abstract: Issues regarding explainable AI involve four components: users, laws &regulations, explanations and algorithms. Together these components provide acontext in which explanation methods can be evaluated regarding their adequacy.The goal of this chapter is to bridge the gap between expert users and layusers. Different kinds of users are identified and their concerns revealed,relevant statements from the General Data Protection Regulation are analyzed inthe context of Deep Neural Networks (DNNs), a taxonomy for the classificationof existing explanation methods is introduced, and finally, the various classesof explanation methods are analyzed to verify if user concerns are justified.Overall, it is clear that (visual) explanations can be given about variousaspects of the influence of the input on the output. However, it is noted thatexplanation methods or interfaces for lay users are missing and we speculatewhich criteria these methods / interfaces should satisfy. Finally it is notedthat two important concerns are difficult to address with explanation methods:the concern about bias in datasets that leads to biased DNNs, as well as thesuspicion about unfair outcomes.
{{< /details >}}

>**_2018-03-20_**

[**Resolution and Relevance Trade-offs in Deep Learning**](http://arxiv.org/abs/1710.11324v2)

*Juyong Song, Matteo Marsili, Junghyo Jo*

{{< details "abstract" >}} abstract: Deep learning has been successfully applied to various tasks, but itsunderlying mechanism remains unclear. Neural networks associate similar inputsin the visible layer to the same state of hidden variables in deep layers. Thefraction of inputs that are associated to the same state is a natural measureof similarity and is simply related to the cost in bits required to representthese inputs. The degeneracy of states with the same information cost providesinstead a natural measure of noise and is simply related the entropy of thefrequency of states, that we call relevance. Representations with minimalnoise, at a given level of similarity (resolution), are those that maximise therelevance. A signature of such efficient representations is that frequencydistributions follow power laws. We show, in extensive numerical experiments,that deep neural networks extract a hierarchy of efficient representations fromdata, because they i) achieve low levels of noise (i.e. high relevance) and ii)exhibit power law distributions. We also find that the layer that is mostefficient to reliably generate patterns of training data is the one for whichrelevance and resolution are traded at the same price, which implies thatfrequency distribution follows Zipf's law.
{{< /details >}}

>**_2018-03-17_**

[**Experiments with Neural Networks for Small and Large Scale Authorship Verification**](http://arxiv.org/abs/1803.06456v1)

*Marjan Hosseinia, Arjun Mukherjee*

{{< details "abstract" >}} abstract: We propose two models for a special case of authorship verification problem.The task is to investigate whether the two documents of a given pair arewritten by the same author. We consider the authorship verification problem forboth small and large scale datasets. The underlying small-scale problem has twomain challenges: First, the authors of the documents are unknown to us becauseno previous writing samples are available. Second, the two documents are short(a few hundred to a few thousand words) and may differ considerably in thegenre and/or topic. To solve it we propose transformation encoder to transformone document of the pair into the other. This document transformation generatesa loss which is used as a recognizable feature to verify if the authors of thepair are identical. For the large scale problem where various authors areengaged and more examples are available with larger length, a parallelrecurrent neural network is proposed. It compares the language models of thetwo documents. We evaluate our methods on various types of datasets includingAuthorship Identification datasets of PAN competition, Amazon reviews, andmachine learning articles. Experiments show that both methods achieve stableand competitive performance compared to the baselines.
{{< /details >}}

>**_2018-02-22_**

[**A Spatial Mapping Algorithm with Applications in Deep Learning-Based Structure Classification**](http://arxiv.org/abs/1802.02532v2)

*Thomas Corcoran, Rafael Zamora-Resendiz, Xinlian Liu, Silvia Crivelli*

{{< details "abstract" >}} abstract: Convolutional Neural Network (CNN)-based machine learning systems have madebreakthroughs in feature extraction and image recognition tasks in twodimensions (2D). Although there is significant ongoing work to apply CNNtechnology to domains involving complex 3D data, the success of such effortshas been constrained, in part, by limitations in data representationtechniques. Most current approaches rely upon low-resolution 3D models,strategic limitation of scope in the 3D space, or the application of lossyprojection techniques to allow for the use of 2D CNNs. To address this issue,we present a mapping algorithm that converts 3D structures to 2D and 1D datagrids by mapping a traversal of a 3D space-filling curve to the traversal ofcorresponding 2D and 1D curves. We explore the performance of 2D and 1D CNNstrained on data encoded with our method versus comparable volumetric CNNsoperating upon raw 3D data from a popular benchmarking dataset. Our experimentsdemonstrate that both 2D and 1D representations of 3D data generated via ourmethod preserve a significant proportion of the 3D data's features in formslearnable by CNNs. Furthermore, we demonstrate that our method of encoding 3Ddata into lower-dimensional representations allows for decreased CNN trainingtime cost, increased original 3D model rendering resolutions, and supportsincreased numbers of data channels when compared to purely volumetricapproaches. This demonstration is accomplished in the context of a structuralbiology classification task wherein we train 3D, 2D, and 1D CNNs on examples oftwo homologous branches within the Ras protein family. The essentialcontribution of this paper is the introduction of a dimensionality-reductionmethod that may ease the application of powerful deep learning tools to domainscharacterized by complex structural data.
{{< /details >}}

>**_2018-02-06_**

[**Digital Watermarking for Deep Neural Networks**](http://arxiv.org/abs/1802.02601v1)

*Yuki Nagai, Yusuke Uchida, Shigeyuki Sakazawa, Shin'ichi Satoh*

{{< details "abstract" >}} abstract: Although deep neural networks have made tremendous progress in the area ofmultimedia representation, training neural models requires a large amount ofdata and time. It is well-known that utilizing trained models as initialweights often achieves lower training error than neural networks that are notpre-trained. A fine-tuning step helps to reduce both the computational cost andimprove performance. Therefore, sharing trained models has been very importantfor the rapid progress of research and development. In addition, trained modelscould be important assets for the owner(s) who trained them, hence we regardtrained models as intellectual property. In this paper, we propose a digitalwatermarking technology for ownership authorization of deep neural networks.First, we formulate a new problem: embedding watermarks into deep neuralnetworks. We also define requirements, embedding situations, and attack typeson watermarking in deep neural networks. Second, we propose a general frameworkfor embedding a watermark in model parameters, using a parameter regularizer.Our approach does not impair the performance of networks into which a watermarkis placed because the watermark is embedded while training the host network.Finally, we perform comprehensive experiments to reveal the potential ofwatermarking deep neural networks as the basis of this new research effort. Weshow that our framework can embed a watermark during the training of a deepneural network from scratch, and during fine-tuning and distilling, withoutimpairing its performance. The embedded watermark does not disappear even afterfine-tuning or parameter pruning; the watermark remains complete even after 65%of parameters are pruned.
{{< /details >}}

>**_2018-02-01_**

[**Automatic Pavement Crack Detection Based on Structured Prediction with the Convolutional Neural Network**](http://arxiv.org/abs/1802.02208v1)

*Zhun Fan, Yuming Wu, Jiewei Lu, Wenji Li*

{{< details "abstract" >}} abstract: Automated pavement crack detection is a challenging task that has beenresearched for decades due to the complicated pavement conditions in realworld. In this paper, a supervised method based on deep learning is proposed,which has the capability of dealing with different pavement conditions.Specifically, a convolutional neural network (CNN) is used to learn thestructure of the cracks from raw images, without any preprocessing. Smallpatches are extracted from crack images as inputs to generate a large trainingdatabase, a CNN is trained and crack detection is modeled as a multi-labelclassification problem. Typically, crack pixels are much fewer than non-crackpixels. To deal with the problem with severely imbalanced data, a strategy withmodifying the ratio of positive to negative samples is proposed. The method istested on two public databases and compared with five existing methods.Experimental results show that it outperforms the other methods.
{{< /details >}}

>**_2018-01-30_**

[**Object Detection on Dynamic Occupancy Grid Maps Using Deep Learning and Automatic Label Generation**](http://arxiv.org/abs/1802.02202v1)

*Stefan Hoermann, Philipp Henzler, Martin Bach, Klaus Dietmayer*

{{< details "abstract" >}} abstract: We tackle the problem of object detection and pose estimation in a sharedspace downtown environment. For perception multiple laser scanners with360{\deg} coverage were fused in a dynamic occupancy grid map (DOGMa). Asingle-stage deep convolutional neural network is trained to provide objecthypotheses comprising of shape, position, orientation and an existence scorefrom a single input DOGMa. Furthermore, an algorithm for offline objectextraction was developed to automatically label several hours of training data.The algorithm is based on a two-pass trajectory extraction, forward andbackward in time. Typical for engineered algorithms, the automatic labelgeneration suffers from misdetections, which makes hard negative miningimpractical. Therefore, we propose a loss function counteracting the highimbalance between mostly static background and extremely rare dynamic gridcells. Experiments indicate, that the trained network has good generalizationcapabilities since it detects objects occasionally lost by the label algorithm.Evaluation reaches an average precision (AP) of 75.9%
{{< /details >}}

>**_2018-01-29_**

[**On the Behavior of Convolutional Nets for Feature Extraction**](http://arxiv.org/abs/1703.01127v4)

*Dario Garcia-Gasulla, Ferran Parés, Armand Vilalta, Jonatan Moreno, Eduard Ayguadé, Jesús Labarta, Ulises Cortés, Toyotaro Suzumura*

{{< details "abstract" >}} abstract: Deep neural networks are representation learning techniques. During training,a deep net is capable of generating a descriptive language of unprecedentedsize and detail in machine learning. Extracting the descriptive language codedwithin a trained CNN model (in the case of image data), and reusing it forother purposes is a field of interest, as it provides access to the visualdescriptors previously learnt by the CNN after processing millions of images,without requiring an expensive training phase. Contributions to this field(commonly known as feature representation transfer or transfer learning) havebeen purely empirical so far, extracting all CNN features from a single layerclose to the output and testing their performance by feeding them to aclassifier. This approach has provided consistent results, although itsrelevance is limited to classification tasks. In a completely differentapproach, in this paper we statistically measure the discriminative power ofevery single feature found within a deep CNN, when used for characterizingevery class of 11 datasets. We seek to provide new insights into the behaviorof CNN features, particularly the ones from convolutional layers, as this canbe relevant for their application to knowledge representation and reasoning.Our results confirm that low and middle level features may behave differentlyto high level features, but only under certain conditions. We find that all CNNfeatures can be used for knowledge representation purposes both by theirpresence or by their absence, doubling the information a single CNN feature mayprovide. We also study how much noise these features may include, and propose athresholding approach to discard most of it. All these insights have a directapplication to the generation of CNN embedding spaces.
{{< /details >}}

[**Deep Reinforcement Learning using Capsules in Advanced Game Environments**](http://arxiv.org/abs/1801.09597v1)

*Per-Arne Andersen*

{{< details "abstract" >}} abstract: Reinforcement Learning (RL) is a research area that has blossomedtremendously in recent years and has shown remarkable potential for artificialintelligence based opponents in computer games. This success is primarily dueto vast capabilities of Convolutional Neural Networks (ConvNet), enablingalgorithms to extract useful information from noisy environments. CapsuleNetwork (CapsNet) is a recent introduction to the Deep Learning algorithm groupand has only barely begun to be explored. The network is an architecture forimage classification, with superior performance for classification of the MNISTdataset. CapsNets have not been explored beyond image classification.  This thesis introduces the use of CapsNet for Q-Learning based gamealgorithms. To successfully apply CapsNet in advanced game play, three maincontributions follow. First, the introduction of four new game environments asframeworks for RL research with increasing complexity, namely Flash RL, DeepLine Wars, Deep RTS, and Deep Maze. These environments fill the gap betweenrelatively simple and more complex game environments available for RL researchand are in the thesis used to test and explore the CapsNet behavior.  Second, the thesis introduces a generative modeling approach to produceartificial training data for use in Deep Learning models including CapsNets. Weempirically show that conditional generative modeling can successfully generategame data of sufficient quality to train a Deep Q-Network well.  Third, we show that CapsNet is a reliable architecture for Deep Q-Learningbased algorithms for game AI. A capsule is a group of neurons that determinethe presence of objects in the data and is in the literature shown to increasethe robustness of training and predictions while lowering the amount trainingdata needed. It should, therefore, be ideally suited for game plays.
{{< /details >}}

>**_2018-01-20_**

[**Deep Hidden Physics Models: Deep Learning of Nonlinear Partial Differential Equations**](http://arxiv.org/abs/1801.06637v1)

*Maziar Raissi*

{{< details "abstract" >}} abstract: A long-standing problem at the interface of artificial intelligence andapplied mathematics is to devise an algorithm capable of achieving human levelor even superhuman proficiency in transforming observed data into predictivemathematical models of the physical world. In the current era of abundance ofdata and advanced machine learning capabilities, the natural question arises:How can we automatically uncover the underlying laws of physics fromhigh-dimensional data generated from experiments? In this work, we put forth adeep learning approach for discovering nonlinear partial differential equationsfrom scattered and potentially noisy observations in space and time.Specifically, we approximate the unknown solution as well as the nonlineardynamics by two deep neural networks. The first network acts as a prior on theunknown solution and essentially enables us to avoid numerical differentiationswhich are inherently ill-conditioned and unstable. The second networkrepresents the nonlinear dynamics and helps us distill the mechanisms thatgovern the evolution of a given spatiotemporal data-set. We test theeffectiveness of our approach for several benchmark problems spanning a numberof scientific domains and demonstrate how the proposed framework can help usaccurately learn the underlying dynamics and forecast future states of thesystem. In particular, we study the Burgers', Korteweg-de Vries (KdV),Kuramoto-Sivashinsky, nonlinear Schr\"{o}dinger, and Navier-Stokes equations.
{{< /details >}}

>**_2017-12-30_**

[**Face Synthesis from Visual Attributes via Sketch using Conditional VAEs and GANs**](http://arxiv.org/abs/1801.00077v1)

*Xing Di, Vishal M. Patel*

{{< details "abstract" >}} abstract: Automatic synthesis of faces from visual attributes is an important problemin computer vision and has wide applications in law enforcement andentertainment. With the advent of deep generative convolutional neural networks(CNNs), attempts have been made to synthesize face images from attributes andtext descriptions. In this paper, we take a different approach, where weformulate the original problem as a stage-wise learning problem. We firstsynthesize the facial sketch corresponding to the visual attributes and then wereconstruct the face image based on the synthesized sketch. The proposedAttribute2Sketch2Face framework, which is based on a combination of deepConditional Variational Autoencoder (CVAE) and Generative Adversarial Networks(GANs), consists of three stages: (1) Synthesis of facial sketch fromattributes using a CVAE architecture, (2) Enhancement of coarse sketches toproduce sharper sketches using a GAN-based framework, and (3) Synthesis of facefrom sketch using another GAN-based network. Extensive experiments andcomparison with recent methods are performed to verify the effectiveness of theproposed attribute-based three stage face synthesis method.
{{< /details >}}

>**_2017-12-20_**

[**DeepFuse: A Deep Unsupervised Approach for Exposure Fusion with Extreme Exposure Image Pairs**](http://arxiv.org/abs/1712.07384v1)

*K. Ram Prabhakar, V. Sai Srikar, R. Venkatesh Babu*

{{< details "abstract" >}} abstract: We present a novel deep learning architecture for fusing staticmulti-exposure images. Current multi-exposure fusion (MEF) approaches usehand-crafted features to fuse input sequence. However, the weak hand-craftedrepresentations are not robust to varying input conditions. Moreover, theyperform poorly for extreme exposure image pairs. Thus, it is highly desirableto have a method that is robust to varying input conditions and capable ofhandling extreme exposure without artifacts. Deep representations have known tobe robust to input conditions and have shown phenomenal performance in asupervised setting. However, the stumbling block in using deep learning for MEFwas the lack of sufficient training data and an oracle to provide theground-truth for supervision. To address the above issues, we have gathered alarge dataset of multi-exposure image stacks for training and to circumvent theneed for ground truth images, we propose an unsupervised deep learningframework for MEF utilizing a no-reference quality metric as loss function. Theproposed approach uses a novel CNN architecture trained to learn the fusionoperation without reference ground truth image. The model fuses a set of commonlow level features extracted from each image to generate artifact-freeperceptually pleasing results. We perform extensive quantitative andqualitative evaluation and show that the proposed technique outperformsexisting state-of-the-art approaches for a variety of natural images.
{{< /details >}}

>**_2017-12-11_**

[**Scale Up Event Extraction Learning via Automatic Training Data Generation**](http://arxiv.org/abs/1712.03665v1)

*Ying Zeng, Yansong Feng, Rong Ma, Zheng Wang, Rui Yan, Chongde Shi, Dongyan Zhao*

{{< details "abstract" >}} abstract: The task of event extraction has long been investigated in a supervisedlearning paradigm, which is bound by the number and the quality of the traininginstances. Existing training data must be manually generated through acombination of expert domain knowledge and extensive human involvement.However, due to drastic efforts required in annotating text, the resultantdatasets are usually small, which severally affects the quality of the learnedmodel, making it hard to generalize. Our work develops an automatic approachfor generating training data for event extraction. Our approach allows us toscale up event extraction training instances from thousands to hundreds ofthousands, and it does this at a much lower cost than a manual approach. Weachieve this by employing distant supervision to automatically create eventannotations from unlabelled text using existing structured knowledge bases ortables.We then develop a neural network model with post inference to transferthe knowledge extracted from structured knowledge bases to automaticallyannotate typed events with corresponding arguments in text.We evaluate ourapproach by using the knowledge extracted from Freebase to label texts fromWikipedia articles. Experimental results show that our approach can generate alarge number of high quality training instances. We show that this large volumeof training data not only leads to a better event extractor, but also allows usto detect multiple typed events.
{{< /details >}}

>**_2017-12-07_**

[**A Deep Network Model for Paraphrase Detection in Short Text Messages**](http://arxiv.org/abs/1712.02820v1)

*Basant Agarwal, Heri Ramampiaro, Helge Langseth, Massimiliano Ruocco*

{{< details "abstract" >}} abstract: This paper is concerned with paraphrase detection. The ability to detectsimilar sentences written in natural language is crucial for severalapplications, such as text mining, text summarization, plagiarism detection,authorship authentication and question answering. Given two sentences, theobjective is to detect whether they are semantically identical. An importantinsight from this work is that existing paraphrase systems perform well whenapplied on clean texts, but they do not necessarily deliver good performanceagainst noisy texts. Challenges with paraphrase detection on user generatedshort texts, such as Twitter, include language irregularity and noise. To copewith these challenges, we propose a novel deep neural network-based approachthat relies on coarse-grained sentence modeling using a convolutional neuralnetwork and a long short-term memory model, combined with a specificfine-grained word-level similarity matching model. Our experimental resultsshow that the proposed approach outperforms existing state-of-the-artapproaches on user-generated noisy social media data, such as Twitter texts,and achieves highly competitive performance on a cleaner corpus.
{{< /details >}}

>**_2017-11-28_**

[**3D-A-Nets: 3D Deep Dense Descriptor for Volumetric Shapes with Adversarial Networks**](http://arxiv.org/abs/1711.10108v1)

*Mengwei Ren, Liang Niu, Yi Fang*

{{< details "abstract" >}} abstract: Recently researchers have been shifting their focus towards learned 3D shapedescriptors from hand-craft ones to better address challenging issues of thedeformation and structural variation inherently present in 3D objects. 3Dgeometric data are often transformed to 3D Voxel grids with regular format inorder to be better fed to a deep neural net architecture. However, thecomputational intractability of direct application of 3D convolutional nets to3D volumetric data severely limits the efficiency (i.e. slow processing) andeffectiveness (i.e. unsatisfied accuracy) in processing 3D geometric data. Inthis paper, powered with a novel design of adversarial networks (3D-A-Nets), wehave developed a novel 3D deep dense shape descriptor (3D-DDSD) to address thechallenging issues of efficient and effective 3D volumetric data processing. Wedeveloped new definition of 2D multilayer dense representation (MDR) of 3Dvolumetric data to extract concise but geometrically informative shapedescription and a novel design of adversarial networks that jointly train a setof convolution neural network (CNN), recurrent neural network (RNN) and anadversarial discriminator. More specifically, the generator network produces 3Dshape features that encourages the clustering of samples from the same categorywith correct class label, whereas the discriminator network discourages theclustering by assigning them misleading adversarial class labels. By addressingthe challenges posed by the computational inefficiency of direct application ofCNN to 3D volumetric data, 3D-A-Nets can learn high-quality 3D-DSDD whichdemonstrates superior performance on 3D shape classification and retrieval overother state-of-the-art techniques by a great margin.
{{< /details >}}

>**_2017-11-21_**

[**A Novel Convolutional Neural Network for Image Steganalysis with Shared Normalization**](http://arxiv.org/abs/1711.07306v2)

*Songtao Wu, Sheng-hua Zhong, Yan Liu*

{{< details "abstract" >}} abstract: Deep learning based image steganalysis has attracted increasing attentions inrecent years. Several Convolutional Neural Network (CNN) models have beenproposed and achieved state-of-the-art performances on detecting steganography.In this paper, we explore an important technique in deep learning, the batchnormalization, for the task of image steganalysis. Different from natural imageclassification, steganalysis is to discriminate cover images and stego imageswhich are the result of adding weak stego signals into covers. Thischaracteristic makes a cover image is more statistically similar to its stegothan other cover images, requiring steganalytic methods to use paired learningto extract effective features for image steganalysis. Our theoretical analysisshows that a CNN model with multiple normalization layers is hard to begeneralized to new data in the test set when it is well trained with pairedlearning. To hand this difficulty, we propose a novel normalization techniquecalled Shared Normalization (SN) in this paper. Unlike the batch normalizationlayer utilizing the mini-batch mean and standard deviation to normalize eachinput batch, SN shares same statistics for all training and test batches. Basedon the proposed SN layer, we further propose a novel neural network model forimage steganalysis. Extensive experiments demonstrate that the proposed networkwith SN layers is stable and can detect the state of the art steganography withbetter performances than previous methods.
{{< /details >}}

>**_2017-11-16_**

[**Probing Convolutional Neural Networks for Event Reconstruction in γ-Ray Astronomy with Cherenkov Telescopes**](http://arxiv.org/abs/1711.06298v1)

*Tim Lukas Holch, Idan Shilon, Matthias Büchele, Tobias Fischer, Stefan Funk, Nils Groeger, David Jankowsky, Thomas Lohse, Ullrich Schwanke, Philipp Wagner*

{{< details "abstract" >}} abstract: A dramatic progress in the field of computer vision has been made in recentyears by applying deep learning techniques. State-of-the-art performance inimage recognition is thereby reached with Convolutional Neural Networks (CNNs).CNNs are a powerful class of artificial neural networks, characterized byrequiring fewer connections and free parameters than traditional neuralnetworks and exploiting spatial symmetries in the input data. Moreover, CNNshave the ability to automatically extract general characteristic features fromdata sets and create abstract data representations which can perform veryrobust predictions. This suggests that experiments using Cherenkov telescopescould harness these powerful machine learning algorithms to improve theanalysis of particle-induced air-showers, where the properties of primaryshower particles are reconstructed from shower images recorded by thetelescopes. In this work, we present initial results of a CNN-based analysisfor background rejection and shower reconstruction, utilizing simulation datafrom the H.E.S.S. experiment. We concentrate on supervised training methods andoutline the influence of image sampling on the performance of the CNN-modelpredictions.
{{< /details >}}

>**_2017-10-23_**

[**Silver Standard Masks for Data Augmentation Applied to Deep-Learning-Based Skull-Stripping**](http://arxiv.org/abs/1710.08354v1)

*Oeslle Lucena, Roberto Souza, Letícia Rittner, Richard Frayne, Roberto Lotufo*

{{< details "abstract" >}} abstract: The bottleneck of convolutional neural networks (CNN) for medical imaging isthe number of annotated data required for training. Manual segmentation isconsidered to be the "gold-standard". However, medical imaging datasets withexpert manual segmentation are scarce as this step is time-consuming andexpensive. We propose in this work the use of what we refer to as silverstandard masks for data augmentation in deep-learning-based skull-strippingalso known as brain extraction. We generated the silver standard masks usingthe consensus algorithm Simultaneous Truth and Performance Level Estimation(STAPLE). We evaluated CNN models generated by the silver and gold standardmasks. Then, we validated the silver standard masks for CNNs training in onedataset, and showed its generalization to two other datasets. Our resultsindicated that models generated with silver standard masks are comparable tomodels generated with gold standard masks and have better generalizability.Moreover, our results also indicate that silver standard masks could be used toaugment the input dataset at training stage, reducing the need for manualsegmentation at this step.
{{< /details >}}

>**_2017-10-13_**

[**Simulating the Ising Model with a Deep Convolutional Generative Adversarial Network**](http://arxiv.org/abs/1710.04987v1)

*Zhaocheng Liu, Sean P. Rodrigues, Wenshan Cai*

{{< details "abstract" >}} abstract: The deep learning framework is witnessing expansive growth into diverseapplications such as biological systems, human cognition, robotics, and thesocial sciences, thanks to its immense ability to extract essential featuresfrom complicated systems. In particular, recent developments of the field haverevealed the unique faculty of deep learning to accurately approximate complexphysical systems in fluid dynamics, condensed matter physics, etc. Theconvolutional neural network (CNN) is an efficient approach to representcomplex systems with large degrees of freedom. On the other hand, thegenerative adversarial network (GAN), as an unsupervised learning algorithm, iscapable of efficiently imitating the distribution of training data. Here weleverage this unique property of GAN, in conjunction with CNN methodology, toestablish an Ising simulator whose generator can produce Ising states giventemperature T around the criticality. The generated Ising states well resemble,and essentially replicate, the data from conventional Monte Carlo simulations.Our results demonstrate the universality of GAN as a promising tool in thefield of computational and statistical physics.
{{< /details >}}

>**_2017-10-04_**

[**Content-Adaptive Sketch Portrait Generation by Decompositional Representation Learning**](http://arxiv.org/abs/1710.01453v1)

*Dongyu Zhang, Liang Lin, Tianshui Chen, Xian Wu, Wenwei Tan, Ebroul Izquierdo*

{{< details "abstract" >}} abstract: Sketch portrait generation benefits a wide range of applications such asdigital entertainment and law enforcement. Although plenty of efforts have beendedicated to this task, several issues still remain unsolved for generatingvivid and detail-preserving personal sketch portraits. For example, quite a fewartifacts may exist in synthesizing hairpins and glasses, and textural detailsmay be lost in the regions of hair or mustache. Moreover, the generalizationability of current systems is somewhat limited since they usually requireelaborately collecting a dictionary of examples or carefully tuningfeatures/components. In this paper, we present a novel representation learningframework that generates an end-to-end photo-sketch mapping through structureand texture decomposition. In the training stage, we first decompose the inputface photo into different components according to their representationalcontents (i.e., structural and textural parts) by using a pre-trainedConvolutional Neural Network (CNN). Then, we utilize a Branched FullyConvolutional Neural Network (BFCN) for learning structural and texturalrepresentations, respectively. In addition, we design a Sorted Matching MeanSquare Error (SM-MSE) metric to measure texture patterns in the loss function.In the stage of sketch rendering, our approach automatically generatesstructural and textural representations for the input photo and produces thefinal result via a probabilistic fusion scheme. Extensive experiments onseveral challenging benchmarks suggest that our approach outperformsexample-based synthesis algorithms in terms of both perceptual and objectivemetrics. In addition, the proposed method also has better generalizationability across dataset without additional training.
{{< /details >}}

>**_2017-09-26_**

[**First Steps Toward Camera Model Identification with Convolutional Neural Networks**](http://arxiv.org/abs/1603.01068v2)

*Luca Bondi, Luca Baroffio, David Güera, Paolo Bestagini, Edward J. Delp, Stefano Tubaro*

{{< details "abstract" >}} abstract: Detecting the camera model used to shoot a picture enables to solve a wideseries of forensic problems, from copyright infringement to ownershipattribution. For this reason, the forensic community has developed a set ofcamera model identification algorithms that exploit characteristic traces lefton acquired images by the processing pipelines specific of each camera model.In this paper, we investigate a novel approach to solve camera modelidentification problem. Specifically, we propose a data-driven algorithm basedon convolutional neural networks, which learns features characterizing eachcamera model directly from the acquired pictures. Results on a well-knowndataset of 18 camera models show that: (i) the proposed method outperformsup-to-date state-of-the-art algorithms on classification of 64x64 color imagepatches; (ii) features learned by the proposed network generalize to cameramodels never used for training.
{{< /details >}}

>**_2017-08-18_**

[**Assessing the Stylistic Properties of Neurally Generated Text in Authorship Attribution**](http://arxiv.org/abs/1708.05536v1)

*E. Manjavacas, J. de Gussem, W. Daelemans, M. Kestemont*

{{< details "abstract" >}} abstract: Recent applications of neural language models have led to an increasedinterest in the automatic generation of natural language. However impressive,the evaluation of neurally generated text has so far remained rather informaland anecdotal. Here, we present an attempt at the systematic assessment of oneaspect of the quality of neurally generated text. We focus on a specific aspectof neural language generation: its ability to reproduce authorial writingstyles. Using established models for authorship attribution, we empiricallyassess the stylistic qualities of neurally generated text. In comparison toconventional language models, neural models generate fuzzier text that isrelatively harder to attribute correctly. Nevertheless, our results alsosuggest that neurally generated text offers more valuable perspectives for theaugmentation of training data.
{{< /details >}}

>**_2017-08-04_**

[**Sensing Urban Land-Use Patterns By Integrating Google Tensorflow And Scene-Classification Models**](http://arxiv.org/abs/1708.01580v1)

*Yao Yao, Haolin Liang, Xia Li, Jinbao Zhang, Jialv He*

{{< details "abstract" >}} abstract: With the rapid progress of China's urbanization, research on the automaticdetection of land-use patterns in Chinese cities is of substantial importance.Deep learning is an effective method to extract image features. To takeadvantage of the deep-learning method in detecting urban land-use patterns, weapplied a transfer-learning-based remote-sensing image approach to extract andclassify features. Using the Google Tensorflow framework, a powerfulconvolution neural network (CNN) library was created. First, the transferredmodel was previously trained on ImageNet, one of the largest object-image datasets, to fully develop the model's ability to generate feature vectors ofstandard remote-sensing land-cover data sets (UC Merced and WHU-SIRI). Then, arandom-forest-based classifier was constructed and trained on these generatedvectors to classify the actual urban land-use pattern on the scale of trafficanalysis zones (TAZs). To avoid the multi-scale effect of remote-sensingimagery, a large random patch (LRP) method was used. The proposed method couldefficiently obtain acceptable accuracy (OA = 0.794, Kappa = 0.737) for thestudy area. In addition, the results show that the proposed method caneffectively overcome the multi-scale effect that occurs in urban land-useclassification at the irregular land-parcel level. The proposed method can helpplanners monitor dynamic urban land use and evaluate the impact ofurban-planning schemes.
{{< /details >}}

>**_2017-07-24_**

[**Auto-Encoding User Ratings via Knowledge Graphs in Recommendation Scenarios**](http://arxiv.org/abs/1706.07956v2)

*Vito Bellini, Vito Walter Anelli, Tommaso Di Noia, Eugenio Di Sciascio*

{{< details "abstract" >}} abstract: In the last decade, driven also by the availability of an unprecedentedcomputational power and storage capabilities in cloud environments we assistedto the proliferation of new algorithms, methods, and approaches in two areas ofartificial intelligence: knowledge representation and machine learning. On theone side, the generation of a high rate of structured data on the Web led tothe creation and publication of the so-called knowledge graphs. On the otherside, deep learning emerged as one of the most promising approaches in thegeneration and training of models that can be applied to a wide variety ofapplication fields. More recently, autoencoders have proven their strength invarious scenarios, playing a fundamental role in unsupervised learning. In thispaper, we instigate how to exploit the semantic information encoded in aknowledge graph to build connections between units in a Neural Network, thusleading to a new method, SEM-AUTO, to extract and weigh semantic features thatcan eventually be used to build a recommender system. As adding content-basedside information may mitigate the cold user problems, we tested how ourapproach behave in the presence of a few rating from a user on the Movielens 1Mdataset and compare results with BPRSLIM.
{{< /details >}}

>**_2017-07-18_**

[**Cosmological model discrimination with Deep Learning**](http://arxiv.org/abs/1707.05167v2)

*Jorit Schmelzle, Aurelien Lucchi, Tomasz Kacprzak, Adam Amara, Raphael Sgier, Alexandre Réfrégier, Thomas Hofmann*

{{< details "abstract" >}} abstract: We demonstrate the potential of Deep Learning methods for measurements ofcosmological parameters from density fields, focusing on the extraction ofnon-Gaussian information. We consider weak lensing mass maps as our dataset. Weaim for our method to be able to distinguish between five models, which werechosen to lie along the $\sigma_8$ - $\Omega_m$ degeneracy, and have nearly thesame two-point statistics. We design and implement a Deep Convolutional NeuralNetwork (DCNN) which learns the relation between five cosmological models andthe mass maps they generate. We develop a new training strategy which ensuresthe good performance of the network for high levels of noise. We compare theperformance of this approach to commonly used non-Gaussian statistics, namelythe skewness and kurtosis of the convergence maps. We find that ourimplementation of DCNN outperforms the skewness and kurtosis statistics,especially for high noise levels. The network maintains the mean discriminationefficiency greater than $85\%$ even for noise levels corresponding to groundbased lensing observations, while the other statistics perform worse in thissetting, achieving efficiency less than $70\%$. This demonstrates the abilityof CNN-based methods to efficiently break the $\sigma_8$ - $\Omega_m$degeneracy with weak lensing mass maps alone. We discuss the potential of thismethod to be applied to the analysis of real weak lensing data and otherdatasets.
{{< /details >}}

>**_2017-06-23_**

[**TimeNet: Pre-trained deep recurrent neural network for time series classification**](http://arxiv.org/abs/1706.08838v1)

*Pankaj Malhotra, Vishnu TV, Lovekesh Vig, Puneet Agarwal, Gautam Shroff*

{{< details "abstract" >}} abstract: Inspired by the tremendous success of deep Convolutional Neural Networks asgeneric feature extractors for images, we propose TimeNet: a deep recurrentneural network (RNN) trained on diverse time series in an unsupervised mannerusing sequence to sequence (seq2seq) models to extract features from timeseries. Rather than relying on data from the problem domain, TimeNet attemptsto generalize time series representation across domains by ingesting timeseries from several domains simultaneously. Once trained, TimeNet can be usedas a generic off-the-shelf feature extractor for time series. Therepresentations or embeddings given by a pre-trained TimeNet are found to beuseful for time series classification (TSC). For several publicly availabledatasets from UCR TSC Archive and an industrial telematics sensor data fromvehicles, we observe that a classifier learned over the TimeNet embeddingsyields significantly better performance compared to (i) a classifier learnedover the embeddings given by a domain-specific RNN, as well as (ii) a nearestneighbor classifier based on Dynamic Time Warping.
{{< /details >}}

>**_2017-05-15_**

[**Mosquito Detection with Neural Networks: The Buzz of Deep Learning**](http://arxiv.org/abs/1705.05180v1)

*Ivan Kiskin, Bernardo Pérez Orozco, Theo Windebank, Davide Zilli, Marianne Sinka, Kathy Willis, Stephen Roberts*

{{< details "abstract" >}} abstract: Many real-world time-series analysis problems are characterised by scarcedata. Solutions typically rely on hand-crafted features extracted from the timeor frequency domain allied with classification or regression engines whichcondition on this (often low-dimensional) feature vector. The huge advancesenjoyed by many application domains in recent years have been fuelled by theuse of deep learning architectures trained on large data sets. This paperpresents an application of deep learning for acoustic event detection in achallenging, data-scarce, real-world problem. Our candidate challenge is toaccurately detect the presence of a mosquito from its acoustic signature. Wedevelop convolutional neural networks (CNNs) operating on wavelettransformations of audio recordings. Furthermore, we interrogate the network'spredictive power by visualising statistics of network-excitatory samples. Thesevisualisations offer a deep insight into the relative informativeness ofcomponents in the detection problem. We include comparisons with conventionalclassifiers, conditioned on both hand-tuned and generic features, to stress thestrength of automatic deep feature learning. Detection is achieved withperformance metrics significantly surpassing those of existing algorithmicmethods, as well as marginally exceeding those attained by individual humanexperts.
{{< /details >}}

>**_2017-04-20_**

[**Embedding Watermarks into Deep Neural Networks**](http://arxiv.org/abs/1701.04082v2)

*Yusuke Uchida, Yuki Nagai, Shigeyuki Sakazawa, Shin'ichi Satoh*

{{< details "abstract" >}} abstract: Deep neural networks have recently achieved significant progress. Sharingtrained models of these deep neural networks is very important in the rapidprogress of researching or developing deep neural network systems. At the sametime, it is necessary to protect the rights of shared trained models. To thisend, we propose to use a digital watermarking technology to protectintellectual property or detect intellectual property infringement of trainedmodels. Firstly, we formulate a new problem: embedding watermarks into deepneural networks. We also define requirements, embedding situations, and attacktypes for watermarking to deep neural networks. Secondly, we propose a generalframework to embed a watermark into model parameters using a parameterregularizer. Our approach does not hurt the performance of networks into whicha watermark is embedded. Finally, we perform comprehensive experiments toreveal the potential of watermarking to deep neural networks as a basis of thisnew problem. We show that our framework can embed a watermark in the situationsof training a network from scratch, fine-tuning, and distilling without hurtingthe performance of a deep neural network. The embedded watermark does notdisappear even after fine-tuning or parameter pruning; the watermark completelyremains even after removing 65% of parameters were pruned. The implementationof this research is: https://github.com/yu4u/dnn-watermark
{{< /details >}}

>**_2017-02-04_**

[**Latent Hinge-Minimax Risk Minimization for Inference from a Small Number of Training Samples**](http://arxiv.org/abs/1702.01293v1)

*Dolev Raviv, Margarita Osadchy*

{{< details "abstract" >}} abstract: Deep Learning (DL) methods show very good performance when trained on large,balanced data sets. However, many practical problems involve imbalanced datasets, or/and classes with a small number of training samples. The performanceof DL methods as well as more traditional classifiers drops significantly insuch settings. Most of the existing solutions for imbalanced problems focus oncustomizing the data for training. A more principled solution is to use mixedHinge-Minimax risk [19] specifically designed to solve binary problems withimbalanced training sets. Here we propose a Latent Hinge Minimax (LHM) risk anda training algorithm that generalizes this paradigm to an ensemble ofhyperplanes that can form arbitrary complex, piecewise linear boundaries. Toextract good features, we combine LHM model with CNN via transfer learning. Tosolve multi-class problem we map pre-trained category-specific LHM classifiersto a multi-class neural network and adjust the weights with very fast tuning.LHM classifier enables the use of unlabeled data in its training and themapping allows for multi-class inference, resulting in a classifier thatperforms better than alternatives when trained on a small number of trainingsamples.
{{< /details >}}

>**_2016-11-01_**

[**Embedding Deep Metric for Person Re-identication A Study Against Large Variations**](http://arxiv.org/abs/1611.00137v1)

*Hailin Shi, Yang Yang, Xiangyu Zhu, Shengcai Liao, Zhen Lei, Weishi Zheng, Stan Z. Li*

{{< details "abstract" >}} abstract: Person re-identification is challenging due to the large variations of pose,illumination, occlusion and camera view. Owing to these variations, thepedestrian data is distributed as highly-curved manifolds in the feature space,despite the current convolutional neural networks (CNN)'s capability of featureextraction. However, the distribution is unknown, so it is difficult to use thegeodesic distance when comparing two samples. In practice, the current deepembedding methods use the Euclidean distance for the training and test. On theother hand, the manifold learning methods suggest to use the Euclidean distancein the local range, combining with the graphical relationship between samples,for approximating the geodesic distance. From this point of view, selectingsuitable positive i.e. intra-class) training samples within a local range iscritical for training the CNN embedding, especially when the data has largeintra-class variations. In this paper, we propose a novel moderate positivesample mining method to train robust CNN for person re-identification, dealingwith the problem of large variation. In addition, we improve the learning by ametric weight constraint, so that the learned metric has a bettergeneralization ability. Experiments show that these two strategies areeffective in learning robust deep metrics for person re-identification, andaccordingly our deep model significantly outperforms the state-of-the-artmethods on several benchmarks of person re-identification. Therefore, the studypresented in this paper may be useful in inspiring new designs of deep modelsfor person re-identification.
{{< /details >}}

>**_2016-09-26_**

[**3D Face Reconstruction by Learning from Synthetic Data**](http://arxiv.org/abs/1609.04387v2)

*Elad Richardson, Matan Sela, Ron Kimmel*

{{< details "abstract" >}} abstract: Fast and robust three-dimensional reconstruction of facial geometricstructure from a single image is a challenging task with numerous applications.Here, we introduce a learning-based approach for reconstructing athree-dimensional face from a single image. Recent face recovery methods relyon accurate localization of key characteristic points. In contrast, theproposed approach is based on a Convolutional-Neural-Network (CNN) whichextracts the face geometry directly from its image. Although such deeparchitectures outperform other models in complex computer vision problems,training them properly requires a large dataset of annotated examples. In thecase of three-dimensional faces, currently, there are no large volume datasets, while acquiring such big-data is a tedious task. As an alternative, wepropose to generate random, yet nearly photo-realistic, facial images for whichthe geometric form is known. The suggested model successfully recovers facialshapes from real images, even for faces with extreme expressions and undervarious lighting conditions.
{{< /details >}}

>**_2016-04-21_**

[**A Novel Approach to Dropped Pronoun Translation**](http://arxiv.org/abs/1604.06285v1)

*Longyue Wang, Zhaopeng Tu, Xiaojun Zhang, Hang Li, Andy Way, Qun Liu*

{{< details "abstract" >}} abstract: Dropped Pronouns (DP) in which pronouns are frequently dropped in the sourcelanguage but should be retained in the target language are challenge in machinetranslation. In response to this problem, we propose a semi-supervised approachto recall possibly missing pronouns in the translation. Firstly, we buildtraining data for DP generation in which the DPs are automatically labelledaccording to the alignment information from a parallel corpus. Secondly, webuild a deep learning-based DP generator for input sentences in decoding whenno corresponding references exist. More specifically, the generation istwo-phase: (1) DP position detection, which is modeled as a sequentiallabelling task with recurrent neural networks; and (2) DP prediction, whichemploys a multilayer perceptron with rich features. Finally, we integrate theabove outputs into our translation system to recall missing pronouns by bothextracting rules from the DP-labelled training data and translating theDP-generated input sentences. Experimental results show that our approachachieves a significant improvement of 1.58 BLEU points in translationperformance with 66% F-score for DP generation accuracy.
{{< /details >}}

>**_2016-02-17_**

[**Authorship Attribution Using a Neural Network Language Model**](http://arxiv.org/abs/1602.05292v1)

*Zhenhao Ge, Yufang Sun, Mark J. T. Smith*

{{< details "abstract" >}} abstract: In practice, training language models for individual authors is oftenexpensive because of limited data resources. In such cases, Neural NetworkLanguage Models (NNLMs), generally outperform the traditional non-parametricN-gram models. Here we investigate the performance of a feed-forward NNLM on anauthorship attribution problem, with moderate author set size and relativelylimited data. We also consider how the text topics impact performance. Comparedwith a well-constructed N-gram baseline method with Kneser-Ney smoothing, theproposed method achieves nearly 2:5% reduction in perplexity and increasesauthor classification accuracy by 3:43% on average, given as few as 5 testsentences. The performance is very competitive with the state of the art interms of accuracy and demand on test data. The source code, preprocesseddatasets, a detailed description of the methodology and results are availableat https://github.com/zge/authorship-attribution.
{{< /details >}}

>**_2016-02-01_**

[**An Iterative Deep Learning Framework for Unsupervised Discovery of Speech Features and Linguistic Units with Applications on Spoken Term Detection**](http://arxiv.org/abs/1602.00426v1)

*Cheng-Tao Chung, Cheng-Yu Tsai, Hsiang-Hung Lu, Chia-Hsiang Liu, Hung-yi Lee, Lin-shan Lee*

{{< details "abstract" >}} abstract: In this work we aim to discover high quality speech features and linguisticunits directly from unlabeled speech data in a zero resource scenario. Theresults are evaluated using the metrics and corpora proposed in the ZeroResource Speech Challenge organized at Interspeech 2015. A Multi-layeredAcoustic Tokenizer (MAT) was proposed for automatic discovery of multiple setsof acoustic tokens from the given corpus. Each acoustic token set is specifiedby a set of hyperparameters that describe the model configuration. These setsof acoustic tokens carry different characteristics fof the given corpus and thelanguage behind, thus can be mutually reinforced. The multiple sets of tokenlabels are then used as the targets of a Multi-target Deep Neural Network(MDNN) trained on low-level acoustic features. Bottleneck features extractedfrom the MDNN are then used as the feedback input to the MAT and the MDNNitself in the next iteration. We call this iterative deep learning frameworkthe Multi-layered Acoustic Tokenizing Deep Neural Network (MAT-DNN), whichgenerates both high quality speech features for the Track 1 of the Challengeand acoustic tokens for the Track 2 of the Challenge. In addition, we performedextra experiments on the same corpora on the application of query-by-examplespoken term detection. The experimental results showed the iterative deeplearning framework of MAT-DNN improved the detection performance due to betterunderlying speech features and acoustic tokens.
{{< /details >}}

>**_2015-11-17_**

[**When Naïve Bayes Nearest Neighbours Meet Convolutional Neural Networks**](http://arxiv.org/abs/1511.03853v2)

*Ilja Kuzborskij, Fabio Maria Carlucci, Barbara Caputo*

{{< details "abstract" >}} abstract: Since Convolutional Neural Networks (CNNs) have become the leading learningparadigm in visual recognition, Naive Bayes Nearest Neighbour (NBNN)-basedclassifiers have lost momentum in the community. This is because (1) suchalgorithms cannot use CNN activations as input features; (2) they cannot beused as final layer of CNN architectures for end-to-end training , and (3) theyare generally not scalable and hence cannot handle big data. This paperproposes a framework that addresses all these issues, thus bringing back NBNNson the map. We solve the first by extracting CNN activations from local patchesat multiple scale levels, similarly to [1]. We address simultaneously thesecond and third by proposing a scalable version of Naive Bayes Non-linearLearning (NBNL, [2]). Results obtained using pre-trained CNNs on standard sceneand domain adaptation databases show the strength of our approach, opening anew season for NBNNs.
{{< /details >}}

>**_2014-11-18_**

[**Do More Dropouts in Pool5 Feature Maps for Better Object Detection**](http://arxiv.org/abs/1409.6911v3)

*Zhiqiang Shen, Xiangyang Xue*

{{< details "abstract" >}} abstract: Deep Convolutional Neural Networks (CNNs) have gained great success in imageclassification and object detection. In these fields, the outputs of all layersof CNNs are usually considered as a high dimensional feature vector extractedfrom an input image and the correspondence between finer level feature vectorsand concepts that the input image contains is all-important. However, fewerstudies focus on this deserving issue. On considering the correspondence, wepropose a novel approach which generates an edited version for each originalCNN feature vector by applying the maximum entropy principle to abandonparticular vectors. These selected vectors correspond to the unfriendlyconcepts in each image category. The classifier trained from merged featuresets can significantly improve model generalization of individual categorieswhen training data is limited. The experimental results forclassification-based object detection on canonical datasets including VOC 2007(60.1%), 2010 (56.4%) and 2012 (56.3%) show obvious improvement in mean averageprecision (mAP) with simple linear support vector machines.
{{< /details >}}

>**_2014-09-30_**

[**An agent-driven semantical identifier using radial basis neural networks and reinforcement learning**](http://arxiv.org/abs/1409.8484v1)

*Christian Napoli, Giuseppe Pappalardo, Emiliano Tramontana*

{{< details "abstract" >}} abstract: Due to the huge availability of documents in digital form, and the deceptionpossibility raise bound to the essence of digital documents and the way theyare spread, the authorship attribution problem has constantly increased itsrelevance. Nowadays, authorship attribution,for both information retrieval andanalysis, has gained great importance in the context of security, trust andcopyright preservation. This work proposes an innovative multi-agent drivenmachine learning technique that has been developed for authorship attribution.By means of a preprocessing for word-grouping and time-period related analysisof the common lexicon, we determine a bias reference level for the recurrencefrequency of the words within analysed texts, and then train a Radial BasisNeural Networks (RBPNN)-based classifier to identify the correct author. Themain advantage of the proposed approach lies in the generality of the semanticanalysis, which can be applied to different contexts and lexical domains,without requiring any modification. Moreover, the proposed system is able toincorporate an external input, meant to tune the classifier, and thenself-adjust by means of continuous learning reinforcement.
{{< /details >}}

>**_2010-09-25_**

[**RGANN: An Efficient Algorithm to Extract Rules from ANNs**](http://arxiv.org/abs/1009.4962v1)

*S. M. Kamruzzaman*

{{< details "abstract" >}} abstract: This paper describes an efficient rule generation algorithm, called rulegeneration from artificial neural networks (RGANN) to generate symbolic rulesfrom ANNs. Classification rules are sought in many areas from automaticknowledge acquisition to data mining and ANN rule extraction. This is becauseclassification rules possess some attractive features. They are explicit,understandable and verifiable by domain experts, and can be modified, extendedand passed on as modular knowledge. A standard three-layer feedforward ANN isthe basis of the algorithm. A four-phase training algorithm is proposed forbackpropagation learning. Comparing them to the symbolic rules generated byother methods supports explicitness of the generated rules. Generated rules arecomparable with other methods in terms of number of rules, average number ofconditions for a rule, and predictive accuracy. Extensive experimental studieson several benchmarks classification problems, including breast cancer, wine,season, golf-playing, and lenses classification demonstrate the effectivenessof the proposed approach with good generalization ability.
{{< /details >}}

>**_2007-07-29_**

[**A Leaf Recognition Algorithm for Plant Classification Using Probabilistic Neural Network**](http://arxiv.org/abs/0707.4289v1)

*Stephen Gang Wu, Forrest Sheng Bao, Eric You Xu, Yu-Xuan Wang, Yi-Fan Chang, Qiao-Liang Xiang*

{{< details "abstract" >}} abstract: In this paper, we employ Probabilistic Neural Network (PNN) with image anddata processing techniques to implement a general purpose automated leafrecognition algorithm. 12 leaf features are extracted and orthogonalized into 5principal variables which consist the input vector of the PNN. The PNN istrained by 1800 leaves to classify 32 kinds of plants with an accuracy greaterthan 90%. Compared with other approaches, our algorithm is an accurateartificial intelligence approach which is fast in execution and easy inimplementation.
{{< /details >}}
