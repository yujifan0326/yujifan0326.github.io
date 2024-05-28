---
permalink: /
title: "About Me"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am an Assistant Researcher at the [Institute of Education](https://www.ioe.tsinghua.edu.cn/) in Tsinghua University. I got my Ph.D degree in the [Knowledge Engineering Group (KEG)](https://keg.cs.tsinghua.edu.cn/), supervised by [Prof. Juanzi Li](http://keg.cs.tsinghua.edu.cn/persons/ljz/) and [Prof. Jie Tang](https://keg.cs.tsinghua.edu.cn/jietang/).
My research interests focus on Knowledge-driven AI in Education, especially Educational Large Models and Agents. I am looking for self-motivated, high-caliber collaborators, research assistants, and candidate master's students. Some of our publicly available resources for AI-Edu can be found here: [MOOCCube](https://github.com/THU-KEG/MOOCCubeX).

Invited Talk & Award
=====
* Our [Paper](https://aclanthology.org/2023.emnlp-main.360/) of Open IE won  <b>EMNLP Outstanding Paper</b>.
* [VisKop](https://aclanthology.org/2023.acl-demo.17/) won <b>ACL2023 Best Demo Paper Award</b>.
* [MOOCCubeX](https://github.com/THU-KEG/MOOCCubeX) won <b>CIKM2021 Best Resource Paper Nomination</b>.
* The Knowledgeable Intelligence in MOOCs. (AI Time 2020) [Sildes](https://cloud.tsinghua.edu.cn/f/6d97a85ca980409cab2f/)


What's New ?
=====
* We have two papers accepted by KDD 2024, Congrats to Fanjin and Shangqing!
* We have two papers accepted by ACL 2024, Congrats to Shangqing and Xiaokang!
* Our work, KoLA, a large-scale knowledge benchmark for carefully evaluting LLMs, was accepted by ICLR2024! [Website](https://kola.xlore.cn/)
* Our work of MOOC Cognitive Diagnosis dataset MOOC-Radar has been accepted by SIGIR 2023 !
* We propose the paper list of ChatGPT Detection as [EvaluationPapers4ChatGPT](https://github.com/THU-KEG/EvaluationPapers4ChatGPT) ! 

Selected Publications
======
<style>
td, th {
   border: none!important;
}
</style>

2024
-----

<table style="border: none!important;">
	  <tbody><tr><td style="width:230px; height:110px" valign="middle" align="middle">
	    <img src="http://yujifan0326.github.io/images/pub/kola.png" width="250">
	  </td>
	  <td style="width:10px">
	  </td>
	  <td valign="middle">
	    <div>
	    	<b>
        	KoLA: Carefully Benchmarking World Knowledge of Large Language Models
        </b>
        <br>
		<i>
        	ICLR 2024
        </i>
        <br>
	    	<b>Jifan Yu</b>*, Xiaozhi Wang*, Shangqing Tu, Shulin Cao, Daniel Zhang-Li, Xin Lv, Hao Peng, Zijun Yao, Xiaohan Zhang, Hanming Li, Chunyang Li, Zheyuan Zhang, Yushi Bai, Yantao Liu, Amy Xin, Nianyi Lin, Kaifeng Yun, Linlu Gong, Jianhui Chen, Zhili Wu, Yunjia Qi, Weikai Li, Yong Guan, Kaisheng Zeng, Ji Qi, Hailong Jin, Jinxi Liu, Yu Gu, Yuan Yao, Ning Ding, Lei Hou, Zhiyuan Liu, Bin Xu, Jie Tang, Juanzi Li
        <br>
        [<a href="https://kola.xlore.cn/">Platform</a>]
		[<a href="https://arxiv.org/pdf/2306.09296.pdf">PDF</a>]
		[<a href="https://github.com/THU-KEG/KoLA">Code</a>]
        <br>
			We construct a Knowledge-oriented LLM Assessment benchmark (KoLA), in which we carefully design three crucial factors: (1) Ability Modeling (2) Evolving Data, (3) Standardized Evaluation. We evaluate 21 open-source and commercial LLMs and obtain some intriguing findings. 
		</div>
	</td></tr></tbody>
</table>

<table style="border: none!important;">
	  <tbody><tr><td style="width:230px; height:110px" valign="middle" align="middle">
	    <img src="http://yujifan0326.github.io/images/pub/causal.png" width="250">
	  </td>
	  <td style="width:10px">
	  </td>
	  <td valign="middle">
	    <div>
	    	<b>
        	A Cause-Effect Look at Alleviating Hallucination of Knowledge-grounded Dialogue Generation
        </b>
        <br>
		<i>
        	COLING 2024
        </i>
        <br>
	    	<b>Jifan Yu</b>, Xiaohan Zhang, Yifan Xu, Xuanyu Lei, Zijun Yao, Jing Zhang, Lei Hou, Juanzi Li
        <br>
        [<a href="https://arxiv.org/pdf/2404.03491">PDF</a>]
        <br>
	    In this paper, we analyze the causal story behind this problem with counterfactual reasoning methods. Based on the causal effect analysis, we propose a possible solution for alleviating the hallucination in KGD by exploiting the dialogue-knowledge interaction.
		</div>
	</td></tr></tbody>
</table>


<table style="border: none!important;">
	  <tbody><tr><td style="width:230px; height:110px" valign="middle" align="middle">
	    <img src="http://yujifan0326.github.io/images/pub/Pinose.png" width="250">
	  </td>
	  <td style="width:10px">
	  </td>
	  <td valign="middle">
	    <div>
	    	<b>
        	Transferable and Efficient Non-Factual Content Detection via Probe Training with Offline Consistency Checking
        </b>
        <br>
		<i>
        	ACL 2024
        </i>
        <br>
	    	Xiaokang Zhang, Zijun Yao, Jing Zhang, Kaifeng Yun, <b>Jifan Yu</b>, Juanzi Li, Jie Tang
        <br>
        [<a href="https://arxiv.org/pdf/2404.06742">PDF</a>]
        <br>
	    This paper proposes PINOSE, which trains a probing model on offline self-consistency checking results, thereby circumventing the need for human-annotated data and achieving transferability across diverse data distributions.
		</div>
	</td></tr></tbody>
</table>


2023
-----


<table style="border: none!important;">
	  <tbody><tr><td style="width:230px; height:110px" valign="middle" align="middle">
	    <img src="http://yujifan0326.github.io/images/pub/moocradar.png" width="250">
	  </td>
	  <td style="width:10px">
	  </td>
	  <td valign="middle">
	    <div>
	    	<b>
        	MoocRadar: A Fine-grained and Multi-aspect Knowledge Repository for Improving Cognitive Student Modeling in MOOCs
        </b>
        <br>
		<i>
        	SIGIR 2023
        </i>
        <br>
	    	<b>Jifan Yu</b>, Mengying Lu, Qingyang Zhong, Zijun Yao, Shangqing Tu, Zhengshan Liao, Xiaoya Li, Manli Li, Lei Hou, Hai-Tao Zheng, Juanzi Li, Jie Tang
        <br>
        [<a href="https://arxiv.org/pdf/2304.02205.pdf">PDF</a>]
		[<a href="https://github.com/THU-KEG/MOOC-Radar">Repository</a>]
        <br>
			In this paper, we present MoocRadar, a fine-grained, multi-aspect knowledge repository consisting of 2,513 exercise questions, 5,600 knowledge concepts, and over 12 million behavioral records. Specifically, we propose a framework to guarantee a high-quality and comprehensive annotation of fine-grained concepts and cognitive labels.
		</div>
	</td></tr></tbody>
</table>

<table style="border: none!important;">
	  <tbody><tr><td style="width:230px; height:110px" valign="middle" align="middle">
	    <img src="http://yujifan0326.github.io/images/pub/mooc-ner.png" width="250">
	  </td>
	  <td style="width:10px">
	  </td>
	  <td valign="middle">
	    <div>
	    	<b>
        	Distantly Supervised Course Concept Extraction in MOOCs with Academic Discipline
        </b>
        <br>
		<i>
        	ACL 2023
        </i>
        <br>
	    	Mengying Lu, Yuquan Wang, <b>Jifan Yu</b> (Corresponding Author), Yexing Du, Lei Hou, Juanzi Li
        <br>
        [<a href="https://github.com/THU-KEG/MOOC-NER">Dataset & Code</a>]
        <br>
			We present a novel three-stage framework DS-MOCE, which leverages the power of pre-trained language models explicitly and implicitly and employs discipline-embedding models with a self-train strategy based on label generation refinement across different domains.
		</div>
	</td></tr></tbody>
</table>

<table style="border: none!important;">
	  <tbody><tr><td style="width:230px; height:110px" valign="middle" align="middle">
	    <img src="http://yujifan0326.github.io/images/pub/VisKop.png" width="250">
	  </td>
	  <td style="width:10px">
	  </td>
	  <td valign="middle">
	    <div>
	    	<b>
        	VisKoP: Visual Knowledge oriented Programming for Interactive Knowledge Base Question Answering  <font color=red><i>(Best Demo Paper Award)</i></font>
        </b>
        <br>
		<i>
        	ACL 2023 Demo 
        </i>
        <br>
	    	Zijun Yao, Yuanyong Chen, Xin Lv, Shulin Cao, Amy Xin, <b>Jifan Yu</b>, Hailong Jin, Jianjun Xu, Peng Zhang, Lei Hou, Juanzi Li
        <br>
        [<a href="https://arxiv.org/pdf/2307.03130">Paper</a>]
		[<a href="https://pypi.org/project/kopl-engine">Demo</a>]
        <br>
			We present Visual Knowledge oriented Programming platform (VisKoP), a knowledge base question answering (KBQA) system that integrates human into the loop to edit and debug the knowledge base (KB) queries.
		</div>
	</td></tr></tbody>
</table>

<table style="border: none!important;">
	  <tbody><tr><td style="width:230px; height:110px" valign="middle" align="middle">
	    <img src="http://yujifan0326.github.io/images/pub/Cog-Assess.png" width="250">
	  </td>
	  <td style="width:10px">
	  </td>
	  <td valign="middle">
	    <div>
	    	<b>
        	Exploring the Cognitive Knowledge Structure of Large Language Models: An Educational Diagnostic Assessment Approach
        </b>
        <br>
		<i>
        	EMNLP 2023
        </i>
        <br>
	    	Zheyuan Zhang*, <b>Jifan Yu</b>*, Juanzi Li, Lei Hou
        <br>
        [<a href="https://arxiv.org/pdf/2310.08172">Paper</a>]
        <br>
			In this paper, based on educational diagnostic assessment method, we conduct an evaluation using MoocRadar, a meticulously annotated human test dataset based on Bloom Taxonomy.
		</div>
	</td></tr></tbody>
</table>


<table style="border: none!important;">
	  <tbody><tr><td style="width:230px; height:110px" valign="middle" align="middle">
	    <img src="http://yujifan0326.github.io/images/pub/OIE.png" width="250">
	  </td>
	  <td style="width:10px">
	  </td>
	  <td valign="middle">
	    <div>
	    	<b>
        	Mastering the Task of Open Information Extraction with Large Language Models and Consistent Reasoning Environment <font color=red><i>(Outstanding Paper)</i></font>
        </b>
        <br>
		<i>
        	EMNLP 2023
        </i>
        <br>
	    	Ji Qi, Kaixuan Ji, Xiaozhi Wang, <b>Jifan Yu</b>, Kaisheng Zeng, Lei Hou, Juanzi Li, Bin Xu
        <br>
        [<a href="https://arxiv.org/pdf/2310.10590">Paper</a>]
        <br>
			As the large language models (LLMs) have exhibited remarkable in-context learning capabilities, a question arises as to whether the task of OIE can be effectively tackled with this paradigm? In this paper, we explore solving the OIE problem by constructing an appropriate reasoning environment for LLMs.
		</div>
	</td></tr></tbody>
</table>


<table style="border: none!important;">
	  <tbody><tr><td style="width:230px; height:110px" valign="middle" align="middle">
	    <img src="http://yujifan0326.github.io/images/pub/glm-dialog.png" width="250">
	  </td>
	  <td style="width:10px">
	  </td>
	  <td valign="middle">
	    <div>
	    	<b>
        	GLM-Dialog: Noise-tolerant Pre-training for Knowledge-grounded Dialogue Generation
        </b>
        <br>
		<i>
        	KDD 2023
        </i>
        <br>
	    	Jing Zhang*, Xiaokang Zhang*, Daniel Zhang-Li*, <b>Jifan Yu</b>*, Zijun Yao, Zeyao Ma, Yiqi Xu, Haohua Wang, Xiaohan Zhang, Nianyi Lin, Sunrui Lu, Juanzi Li, Jie Tang
        <br>
        [<a href="https://github.com/RUCKBReasoning/GLM-Dialog">Dataset & Code</a>]
		[<a href="https://arxiv.org/pdf/2302.14401.pdf">PDF</a>]
        <br>
			We present GLM-Dialog, a large-scale language model (LLM) with 10B parameters capable of knowledge-grounded conversation in Chinese using a search engine to access the Internet knowledge. GLM-Dialog offers a series of applicable techniques for exploiting various external knowledge including both helpful and noisy knowledge, enabling the creation of robust knowledge-grounded dialogue LLMs with limited proper datasets. 
		</div>
	</td></tr></tbody>
</table>

<table style="border: none!important;">
	  <tbody><tr><td style="width:230px; height:110px" valign="middle" align="middle">
	    <img src="http://yujifan0326.github.io/images/pub/LittleMu.png" width="250">
	  </td>
	  <td style="width:10px">
	  </td>
	  <td valign="middle">
	    <div>
	    	<b>
        	LittleMu: Deploying an Online Virtual Teaching Assistant via Heterogeneous Sources Integration and Chain of Teach Prompts
        </b>
        <br>
		<i>
        	CIKM 2023
        </i>
        <br>
	    	Shangqing Tu, Zheyuan Zhang, <b>Jifan Yu</b>, Chunyang Li, Siyu Zhang, Zijun Yao, Lei Hou, Juanzi Li
        <br>
        [<a href="https://dl.acm.org/doi/pdf/10.1145/3583780.3615484">PDF</a>]
        <br>
	    In this paper, we present a virtual MOOC teaching assistant, LittleMu with minimum labeled training data, to provide question answering and chit-chat services. 
		</div>
	</td></tr></tbody>
</table>

<table style="border: none!important;">
	  <tbody><tr><td style="width:230px; height:110px" valign="middle" align="middle">
	    <img src="http://yujifan0326.github.io/images/pub/goal.png" width="250">
	  </td>
	  <td style="width:10px">
	  </td>
	  <td valign="middle">
	    <div>
	    	<b>
        	GOAL: A Challenging Knowledge-grounded Video Captioning Benchmark for Real-time Soccer Commentary Generation
        </b>
        <br>
		<i>
        	CIKM 2023
        </i>
        <br>
	    	Ji Qi*, <b>Jifan Yu</b>*, Teng Tu, Kunyu Gao, Yifan Xu, Xinyu Guan, Xiaozhi Wang, Bin Xu, Lei Hou, Juanzi Li, Jie Tang
        <br>
		[<a href="https://arxiv.org/pdf/2303.14655v1.pdf">Paper</a>]
		[<a href="https://github.com/THU-KEG/goal">Repository</a>]
        <br>
			In this paper, we present GOAL, a benchmark of over 8.9k soccer video clips, 22k sentences, and 42k knowledge triples for proposing a challenging new task setting as Knowledge-grounded Video Captioning (KGVC).
		</div>
	</td></tr></tbody>
</table>

<table style="border: none!important;">
	  <tbody><tr><td style="width:230px; height:110px" valign="middle" align="middle">
	    <img src="http://yujifan0326.github.io/images/pub/llm-as-exam.png" width="250">
	  </td>
	  <td style="width:10px">
	  </td>
	  <td valign="middle">
	    <div>
	    	<b>
        	Benchmarking Foundation Models with Language-Model-as-an-Examiner
        </b>
        <br>
		<i>
        	NeuraIPS 2023 Benchmarking Track
        </i>
        <br>
	    	Yushi Bai, Jiahao Ying, Yixin Cao, Xin Lv, Yuze He, Xiaozhi Wang, <b>Jifan Yu</b>, Kaisheng Zeng, Yijia Xiao, Haozhe Lyu, Jiayin Zhang, Juanzi Li, Lei Hou
        <br>
        [<a href="https://proceedings.neurips.cc/paper_files/paper/2023/file/f64e55d03e2fe61aa4114e49cb654acb-Paper-Datasets_and_Benchmarks.pdf">PDF</a>]
		[<a href="http://lmexam.xlore.cn.">Repository</a>]
        <br>
			(1) We instruct the LM examiner to generate questions across a multitude of domains to probe for a broad acquisition, and raise follow-up questions to engage in a more in-depth assessment. (2) Upon evaluation, the examiner combines both scoring and ranking measurements, providing a reliable result as it aligns closely with human annotations. (3) We additionally propose a decentralized Peer-examination method to address the biases in a single examiner.
		</div>
	</td></tr></tbody>
</table>

<table style="border: none!important;">
	  <tbody><tr><td style="width:230px; height:110px" valign="middle" align="middle">
	    <img src="http://yujifan0326.github.io/images/pub/learn_to_not_link.png" width="250">
	  </td>
	  <td style="width:10px">
	  </td>
	  <td valign="middle">
	    <div>
	    	<b>
        	Learn to Not Link: Exploring NIL Prediction in Entity Linking
        </b>
        <br>
		<i>
        	Findings of ACL 2023
        </i>
        <br>
	    	Fangwei Zhu, <b>Jifan Yu</b>*, Hailong Jin, Juanzi Li, Lei Hou, Zhifang Sui
        <br>
		[<a href="https://github.com/solitaryzero/NIL_EL">Dataset & Code</a>]
		[<a href="https://arxiv.org/pdf/2305.15725.pdf">PDF</a>]
        <br>
			We propose an entity linking dataset NEL focuses on the NIL prediction problem. NEL takes entities that share an alias with other entities as seeds, collects relevant mention context in the Wikipedia corpus, and ensures the presence of mentions linking to NIL by human annotation and entity masking.
		</div>
	</td></tr></tbody>
</table>



2022
-----

<style>
td, th {
   border: none!important;
}
</style>

<table style="border: none!important;">
	  <tbody><tr><td style="width:230px; height:110px" valign="middle" align="middle">
	    <img src="http://yujifan0326.github.io/images/pub/xdai.png" width="250">
	  </td>
	  <td style="width:10px">
	  </td>
	  <td valign="middle">
	    <div>
	    	<b>
        	XDAI: A Tuning‑free Framework for Exploiting the Pre‑trained Language Models in Knowledge Grounded Dialogue Generation
        </b>
        <br>
		<i>
        	KDD 2022
        </i>
        <br>
	    	<b>Jifan Yu</b>, Xiaohan Zhang, Yifan Xu, Xuanyu Lei, Xinyu Guan, Jing Zhang, Lei Hou, Juanzi Li, Jie Tang
        <br>
        [<a href="https://github.com/THUDM/XDAI">Code</a>]
        <br>
			We propose XDAI, a knowledge-grounded dialogue system that is equipped with the prompt-aware tuning-free PLM exploitation and supported by the ready-to-use open-domain external knowledge resources plus the easy-to-change domain-specific mechanism.
		</div>
	</td></tr></tbody>
</table>

<table style="border: none!important;">
	  <tbody><tr><td style="width:230px; height:110px" valign="middle" align="middle">
	    <img src="http://yujifan0326.github.io/images/pub/program.png" width="250">
	  </td>
	  <td style="width:10px">
	  </td>
	  <td valign="middle">
	    <div>
	    	<b>
        	Program Transfer for Answering Complex Questions over Knowledge Bases
        </b>
        <br>
		<i>
        	ACL 2022
        </i>
        <br>
	    	Shulin Cao, Jiaxin Shi, Zijun Yao, Xin Lv, <b>Jifan Yu</b>, Lei Hou, Juanzi Li, Zhiyuan Liu, Jinghui Xiao
        <br>
		[<a href="https://aclanthology.org/2022.acl-long.559/">PDF</a>]
        [<a href="https://github.com/THU-KEG/ProgramTransfer">Code</a>]
        <br>
			In this paper, we propose the approach of program transfer, which aims to leverage the valuable program annotations on the rich-resourced KBs as external supervision signals to aid program induction for the low-resourced KBs that lack program annotations.
		</div>
	</td></tr></tbody>
</table>


<table style="border: none!important;">
	  <tbody><tr><td style="width:230px; height:110px" valign="middle" align="middle">
	    <img src="http://yujifan0326.github.io/images/pub/subgraph.png" width="250">
	  </td>
	  <td style="width:10px">
	  </td>
	  <td valign="middle">
	    <div>
	    	<b>
        	Subgraph Retrieval Enhanced Model for Multi-hop Knowledge Base Question Answering
        </b>
        <br>
		<i>
        	ACL 2022
        </i>
        <br>
	    	Jing Zhang, Xiaokang Zhang, <b>Jifan Yu</b>, Jian Tang, Jie Tang, Cuiping Li, Hong Chen
        <br>
		[<a href="https://aclanthology.org/2022.acl-long.396/">PDF</a>]
        [<a href="https://github.com/RUCKBReasoning/SubgraphRetrievalKBQA">Code</a>]
        <br>
			This paper proposes a trainable subgraph retriever (SR) decoupled from the subsequent reasoning process, which enables a plug-and-play framework to enhance any subgraph-oriented KBQA model. 
		</div>
	</td></tr></tbody>
</table>

<table style="border: none!important;">
	  <tbody><tr><td style="width:230px; height:110px" valign="middle" align="middle">
	    <img src="http://yujifan0326.github.io/images/pub/hosmel.png" width="250">
	  </td>
	  <td style="width:10px">
	  </td>
	  <td valign="middle">
	    <div>
	    	<b>
        	HOSMEL: A Hot-Swappable Modularized Entity Linking Toolkit for Chinese
        </b>
        <br>
		<i>
        	ACL 2022
        </i>
        <br>
	    	Daniel Zhang-Li, Jing Zhang, <b>Jifan Yu</b>, Xiaokang Zhang, Peng Zhang, Jie Tang, Juanzi Li
        <br>
		[<a href="https://aclanthology.org/2022.acl-demo.21/">PDF</a>]
        [<a href="https://github.com/THUDM/HOSMEL">Code</a>]
        <br>
			We investigate the usage of entity linking (EL) in downstream tasks and present the first modularized EL toolkit for easy task adaptation. Different from the existing EL methods that deal with all the features simultaneously, we modularize the whole model into separate parts with each feature.
		</div>
	</td></tr></tbody>
</table>

<table style="border: none!important;">
	  <tbody><tr><td style="width:230px; height:110px" valign="middle" align="middle">
	    <img src="http://yujifan0326.github.io/images/pub/UPER.png" width="250">
	  </td>
	  <td style="width:10px">
	  </td>
	  <td valign="middle">
	    <div>
	    	<b>
        	UPER: Boosting Multi-Document Summarization with an Unsupervised Prompt-based Extractor
        </b>
        <br>
		<i>
        	COLING 2022
        </i>
        <br>
	    	Shangqing Tu, <b>Jifan Yu</b>, Fangwei Zhu, Juanzi Li, Lei Hou and Jian-Yun Nie
        <br>
		[<a href="https://github.com/THU-KEG/UPER">code</a>]
        <br>
			To extract documents effectively, we construct prompting templates that invoke the underlying knowledge in Pre-trained Language Model (PLM) to calculate the document and keyword’s perplexity, which can assess the document’s semantic salience. Our unsupervised approach can be applied as a plug-in to boost other metrics for evaluating a document’s salience, thus improving the subsequent abstract generation.
		</div>
	</td></tr></tbody>
</table>

<table style="border: none!important;">
	  <tbody><tr><td style="width:230px; height:110px" valign="middle" align="middle">
	    <img src="http://yujifan0326.github.io/images/pub/storyline.png" width="250">
	  </td>
	  <td style="width:10px">
	  </td>
	  <td valign="middle">
	    <div>
	    	<b>
        	CStory: A Chinese Large-scale News Storyline Dataset
        </b>
        <br>
		<i>
        	CIKM 2022
        </i>
        <br>
	    	Kaijie Shi, Xiaozhi Wang, <b>Jifan Yu</b>, Lei Hou, Juanzi Li, Jingtong Wu, Dingyu Yong, Jinghui Xiao, Qun Liu
        <br>
		[<a href="https://github.com/THU-KEG/CStory">code</a>]
        <br>
			In this paper, we construct CStory, a large-scale Chinese news storyline dataset, which contains 11, 978 news articles, 112, 549 manually labeled storyline relation pairs, and 49, 832 evidence sentences for annotation judgment. We conduct extensive experiments on CStory using various algorithms and find that constructing news storylines is challenging even for pre-trained language models.
		</div>
	</td></tr></tbody>
</table>

<table style="border: none!important;">
	  <tbody><tr><td style="width:230px; height:110px" valign="middle" align="middle">
	    <img src="http://yujifan0326.github.io/images/pub/iclea.png" width="250">
	  </td>
	  <td style="width:10px">
	  </td>
	  <td valign="middle">
	    <div>
	    	<b>
        	ICLEA: Interactive Contrastive Learning for Self-supervised Entity Alignment
        </b>
        <br>
		<i>
        	CIKM 2022
        </i>
        <br>
	    	Kaisheng Zeng, Zhenhao Dong, Lei Hou, Yixin Cao, Minghao Hu, <b>Jifan Yu</b>, Xin Lv, Juanzi Li, Ling Feng
        <br>
		[<a href="https://arxiv.org/pdf/2201.06225">PDF</a>]
        <br>
			In this paper, we propose an interactive contrastive learning model for self-supervised EA. The model encodes not only structures and semantics of entities (including entity name, entity description, and entity neighborhood), but also conducts cross-KG contrastive learning by building pseudo-aligned entity pairs.
		</div>
	</td></tr></tbody>
</table>

<table style="border: none!important;">
	  <tbody><tr><td style="width:230px; height:110px" valign="middle" align="middle">
	    <img src="http://yujifan0326.github.io/images/pub/pretrain.png" width="250">
	  </td>
	  <td style="width:10px">
	  </td>
	  <td valign="middle">
	    <div>
	    	<b>
        	Towards a General Pre-training Framework for Adaptive Learning in MOOCs
        </b>
        <br>
		<i>
        	Arxiv
        </i>
        <br>
	    	Qingyang Zhong*, <b>Jifan Yu*</b>, Zheyuan Zhang, Yiming Mao, Yuquan Wang, Yankai Lin, Lei Hou, Juanzi Li, Jie Tang
        <br>
		[<a href="https://arxiv.org/pdf/2208.04708.pdf">PDF</a>]
        <br>
			To realize the idea of general adaptive systems proposed in pedagogical theory, with the emerging pre-training techniques in NLP, we try to conduct a practical exploration on applying pre-training to adaptive learning, to propose a unified framework based on data observation and learning style analysis, properly leveraging heterogeneous learning elements.
		</div>
	</td></tr></tbody>
</table>

2021
-----

<table style="border: none!important;">
	  <tbody><tr><td style="width:230px; height:110px" valign="middle" align="middle">
	    <img src="http://yujifan0326.github.io/images/pub/mooccubex.png" width="250">
	  </td>
	  <td style="width:10px">
	  </td>
	  <td valign="middle">
	    <div>
	    	<b>
        	MOOCCubeX: A Large Knowledge-centered Repository for Adaptive Learning in MOOCs <font color=red><i>(Best Resource Paper Nomination)</i></font>
        </b>
        <br>
		<i>
        	CIKM 2021
        </i>
        <br>
	    	<b>Jifan Yu</b>, Yuquan Wang, Qingyang Zhong, Gan Luo, Yiming Mao, Kai Sun, Wenzheng Feng, Wei Xu, Shulin Cao, Kaisheng Zeng, Zijun Yao, Lei Hou, Yankai Lin, Peng Li, Jie Zhou, Bin Xu, Juanzi Li, Jie Tang, Maosong Sun
        <br>
		[<a href="https://lfs.aminer.cn/misc/moocdata/publications/mooccubex.pdf">PDF</a>]
        [<a href="https://github.com/THU-KEG/MOOCCubeX">Code</a>]
        <br>
			We present MOOCCubeX, a large, knowledge-centered repository consisting of 4,216 courses, 230,263 videos, 358,265 exercises, 637,572 fine-grained concepts and over 296 million behavioral data of 3,330,294 students, for supporting the research topics on adaptive learning in MOOCs.
		</div>
	</td></tr></tbody>
</table>


<table style="border: none!important;">
	  <tbody><tr><td style="width:230px; height:110px" valign="middle" align="middle">
	    <img src="http://transirius.github.io/images/pub/kat.png" width="250">
	  </td>
	  <td style="width:10px">
	  </td>
	  <td valign="middle">
	    <div>
	    	<b>
        	Interpretable and Low-Resource Entity Matching via Decoupling Feature Learning from Decision Making
        </b>
        <br>
		<i>
        	ACL 2021
        </i>
        <br>
	    	Zijun Yao, Chengjiang Li, Tiansi Dong, Xin Lv, <b>Jifan Yu</b>, Lei Hou, Juanzi Li, Yichi Zhang and Zelin Dai
        <br>
		[<a href="https://arxiv.org/abs/2106.04174">PDF</a>]
        [<a href="https://github.com/THU-KEG/HIF-KAT">Code</a>]
		[<a href="http://transirius.github.io/files/kat.pdf">Slide</a>]
        <br>
			We propose to decouple the representation learning stage and the decision making stage to fully utilize unlabeled data for entity matching task.
		</div>
	</td></tr></tbody>
</table>

<table style="border: none!important;">
	  <tbody><tr><td style="width:230px; height:110px" valign="middle" align="middle">
	    <img src="http://yujifan0326.github.io/images/pub/crowd.png" width="250">
	  </td>
	  <td style="width:10px">
	  </td>
	  <td valign="middle">
	    <div>
	    	<b>
        	Expertise-Aware Crowdsourcing Taxonomy Enrichment
        </b>
        <br>
		<i>
        	WISE 2021
        </i>
        <br>
	    	Yuquan Wang, Yanpeng Wang, Yiming Mao, <b>Jifan Yu</b>, Kaisheng Zeng, Lei Hou, Juanzi Li, Jie Tang
        <br>
		[<a href="https://link.springer.com/chapter/10.1007/978-3-030-90888-1_2">PDF</a>]
        [<a href="https://github.com/THU-KEG/ECTE">Code</a>]
        <br>
			In this work, we propose a unified crowdsourcing framework to mitigate both challenges. It leverages the skill locality of workers with a Graph Gaussian Process model.
		</div>
	</td></tr></tbody>
</table>

<table style="border: none!important;">
	  <tbody><tr><td style="width:230px; height:110px" valign="middle" align="middle">
	    <img src="http://yujifan0326.github.io/images/pub/LKT.png" width="250">
	  </td>
	  <td style="width:10px">
	  </td>
	  <td valign="middle">
	    <div>
	    	<b>
        	Learning Behavior-Aware Cognitive Diagnosis for Online Education Systems
        </b>
        <br>
		<i>
        	ICPCSEE 2021
        </i>
        <br>
	    	Yiming Mao, Bin Xu, <b>Jifan Yu</b>, Yifan Fang, Jie Yuan, Juanzi Li, Lei Hou
        <br>
        <br>
			In this paper, a learning behavior-aware cognitive diagnosis (LCD) framework is proposed for students’ cognitive modeling with both learning behavior records and exercising records.
		</div>
	</td></tr></tbody>
</table>

2020
-----

<table style="border: none!important;">
	  <tbody><tr><td style="width:230px; height:110px" valign="middle" align="middle">
	    <img src="http://yujifan0326.github.io/images/pub/mooccube.png" width="250">
	  </td>
	  <td style="width:10px">
	  </td>
	  <td valign="middle">
	    <div>
	    	<b>
        	MOOCCube: A Large-scale Data Repository for NLP Applications in MOOCs
        </b>
        <br>
		<i>
        	ACL 2020
        </i>
        <br>
	    	<b>Jifan Yu</b>, Gan Luo, Tong Xiao, Qingyang Zhong, Yuquan Wang, Wenzheng Feng, Junyi Luo, Chenyu Wang, Lei Hou, Juanzi Li, Zhiyuan Liu, Jie Tang
        <br>
		[<a href="https://aclanthology.org/2020.acl-main.285/">PDF</a>]
        [<a href="http://moocdata.cn/data/MOOCCube">Code</a>]
        <br>
			We present MOOCCube, a large-scale data repository of over 700 MOOC courses, 100k concepts, 8 million student behaviors with an external resource. Moreover, we conduct a prerequisite discovery task as an example application to show the potential of MOOCCube in facilitating relevant research.
		</div>
	</td></tr></tbody>
</table>

<table style="border: none!important;">
	  <tbody><tr><td style="width:230px; height:110px" valign="middle" align="middle">
	    <img src="http://yujifan0326.github.io/images/pub/expanrl.png" width="250">
	  </td>
	  <td style="width:10px">
	  </td>
	  <td valign="middle">
	    <div>
	    	<b>
			Expanrl: Hierarchical Reinforcement Learning for Course Concept Expansion in MOOCs
        </b>
        <br>
		<i>
        	AACL 2020
        </i>
        <br>
	    	<b>Jifan Yu</b>, Chenyu Wang, Gan Luo, Lei Hou, Juanzi Li, Jie Tang, Minlie Huang, Zhiyuan Liu
        <br>
		[<a href="https://aclanthology.org/2020.aacl-main.77/">PDF</a>]
        <br>
			We present ExpanRL, an end-to-end hierarchical reinforcement learning (HRL) model for concept expansion in MOOCs. Employing a two-level HRL mechanism of seed selection and concept expansion, ExpanRL is more feasible to adjust the expansion strategy to find new concepts based on the students’ feedback on expansion results.
		</div>
	</td></tr></tbody>
</table>

<table style="border: none!important;">
	  <tbody><tr><td style="width:230px; height:110px" valign="middle" align="middle">
	    <img src="http://yujifan0326.github.io/images/pub/poi.png" width="250">
	  </td>
	  <td style="width:10px">
	  </td>
	  <td valign="middle">
	    <div>
	    	<b>
			Geographical Information Enhanced POI Hierarchical Classification
        </b>
        <br>
		<i>
        	AP-Web 2020
        </i>
        <br>
	    	Shaopeng Liu, <b>Jifan Yu</b>, Juanzi Li, Lei Hou
        <br>
		[<a href="https://link.springer.com/chapter/10.1007/978-3-030-60029-7_10">PDF</a>]
        <br>
			We propose an Ensemble POI Hierarchical Classification framework (EHC) consisting of three components: Textual and Geographic Feature Extraction, Hierarchical Classifier, and Soft Voting Ensemble Model.
		</div>
	</td></tr></tbody>
</table>

2019
-----

<table style="border: none!important;">
	  <tbody><tr><td style="width:230px; height:110px" valign="middle" align="middle">
	    <img src="http://yujifan0326.github.io/images/pub/cce.png" width="250">
	  </td>
	  <td style="width:10px">
	  </td>
	  <td valign="middle">
	    <div>
	    	<b>
        	Course Concept Expansion in MOOCs with External Knowledge and Interactive Game
        </b>
        <br>
		<i>
        	ACL 2019
        </i>
        <br>
	    	<b>Jifan Yu</b>, Chenyu Wang, Gan Luo, Lei Hou, Juanzi Li, Jie Tang, Zhiyuan Liu
        <br>
		[<a href="https://aclanthology.org/P19-1421/">PDF</a>]
        <br>
			In this paper, we first build a novel boundary during searching for new concepts via external knowledge base and then utilize heterogeneous features to verify the high-quality results. In addition, to involve human efforts in our model, we design an interactive optimization mechanism based on a game.
		</div>
	</td></tr></tbody>
</table>


2018
-----

<table style="border: none!important;">
	  <tbody><tr><td style="width:230px; height:110px" valign="middle" align="middle">
	    <img src="http://yujifan0326.github.io/images/pub/predict.png" width="250">
	  </td>
	  <td style="width:10px">
	  </td>
	  <td valign="middle">
	    <div>
	    	<b>
        	Predicting Concept-based Research Trends with Rhetorical Framing
        </b>
        <br>
		<i>
        	CCKS 2018
        </i>
        <br>
	    	<b>Jifan Yu</b>, Liangming Pan, Juanzi Li, Xiaoping Du
        <br>
		[<a href="http://www.liangmingpan.com/files/publications/CCKS18_Paper.pdf">PDF</a>]
        <br>
			The existing researches mainly use topics extracted from literatures as objects to build predicting model. To get more accurate results, we use concepts instead of topics constructing a model to predict their rise and fall trends, considering the rhetorical characteristics of them.
		</div>
	</td></tr></tbody>
</table>