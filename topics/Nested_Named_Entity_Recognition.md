# Nested Named Entity Recognition

1. [**ACL 2022**]: [Nested Named Entity Recognition as Latent Lexicalized Constituency Parsing](https://aclanthology.org/2022.acl-long.428.pdf)
	- Authors: Chao Lou, Songlin Yang, Kewei Tu
	- Baseline Methods: SH, Pyramid, PO-TreeCRF, Seq2set, Locate&Label
	- Datasets: ACE2004, ACE2005, GENIA
	- Approach: [Code](https://github.com/LouChao98/nner_as_parsing)

2. [**ACL 2022**]: [Nested Named Entity Recognition with Span-level Graphs](https://aclanthology.org/2022.acl-long.63/)
	- Authors: Juncheng Wan, Dongyu Ru, Weinan Zhang, Yong Yu
	- Baseline Methods: HyperGraph, Stack-LSTM, Seg-Graph, ARN, Seq2seq, Path-BERT, ML, Pyramid, SpERT, BENSC,  BERTMRC, NER-DP, DYGIE
	- Datasets: ACE2004, ACE2005, GENIA
	
3. [**COLING 2022**]: [Nested Named Entity Recognition as Corpus Aware Holistic Structure Parsing](https://arxiv.org/abs/2204.08006)
	- Authors: Yifei Yang, Zuchao Li, Hai Zhao
	- Baseline Methods: Hyper-Graph, Seg-Graph, ARN, Merge-BERT, DYGIE, Seq2seq-BERT, Path-BERT, BERT-MRC, Seq2seq-BART, Seq2set-BERT 
	- Datasets: ACE2005, GENIA, KBP2017
	
4. [**COLING 2022**]: [Simple yet Powerful: An Overlooked Architecture for Nested Named Entity Recognition](https://openreview.net/pdf?id=cL4tgY1ZxS)
	- Baseline Methods: Pyramid, Recursive-CRF, Layered, Exhaustive, Boundary, Biaffine
	- Datasets: GENIA, GermEval, Chilean Waiting List 
	
5. [**AAAI 2021**]: [A Supervised Multi-Head Self-Attention Network for Nested Named Entity Recognition](https://ojs.aaai.org/index.php/AAAI/article/view/17669)
	- Authors: Yongxiu Xu, Heyan Huang, Chong Feng, Yue Hu
	- Baseline Methods: sequence labeling-based models, span-based models
	- Datasets: ACE20042, ACE20053, GENIA, JNLPBA, CoNLL03
	- Approach: MHSA-BERT 
	
6. [**AAAI 2021**]: [Nested Named Entity Recognition with Partially-Observed TreeCRFs](https://arxiv.org/abs/2012.08478)
	- Authors: Yao Fu, Chuanqi Tan, Mosha Chen, Songfang Huang, Fei Huang
	- Baseline Methods: LSTM-CRF, FOFE, Transition, Cascaded-CRF, SH, MGNER, Merge and Label, Seq2seq, BENSC, Pyramid
	- Datasets: ACE2004, ACE2005, GENIA
	- Approach: PO-Tree CRF [Code](https://github.com/FranxYao/Partially-Observed-TreeCRFs)
	
7. [**ACL 2021**]: [Nested Named Entity Recognition via Explicitly Excluding the Influence of the Best Path](https://aclanthology.org/2021.acl-long.275/)
	- Authors: Yiran Wang, Hiroyuki Shindo, Yuji Matsumoto, Taro Watanabe
	- Baseline Methods:layered-CRF, Transition, SH (Segm. hyp), Anchor-Region, Seq2seq, (a few more..)
	- Datasets:ACE2004, ACE2005, GENIA
	- Approach: [Code](https://github.com/speedcell4/nersted)
	
8. [**ACL 2020**]: [Bipartite Flat-Graph Network for Nested Named Entity Recognition](https://aclanthology.org/2020.acl-main.571/)
	- Authors: Ying Luo, Hai Zhao
	- Baseline Methods: LSTM-CRF, Multi-CRF, layered-CRF, LH (LSTM. hyp), SH (Segm. hyp), Exhaustive, Anchor-Region, Merge & Label, Boundary-aware, GEANN, KBP2017 Overview
	- Datasets: ACE2005, GENIA, KBP2017
	- Approach: [Code](https://github.com/cslydia/BiFlaG)
	
9. [**ACL 2020**]: [Pyramid: A Layered Model for Nested Named Entity Recognition](https://aclanthology.org/2020.acl-main.525.pdf)
	- Authors: Jue Wang, Lidan Shou, Ke Chen, Gang Chen
	- Baseline Methods: Non-LM based (Transition, SH, FOFE, Merge & Label, Anchor-Region, LH, Cascaded-CRF), LM based (ELMO, BERT, BERT+Flair)
	- Datasets:ACE-2004, ACE-2005, GENIA, NNE
	- Approach: [Code](https://github.com/LorrinWWW/Pyramid)
	
10. [**AAAI 2020**]: [Boundary Enhanced Neural Span Classification for Nested Named Entity Recognition](https://ojs.aaai.org/index.php/AAAI/article/view/6434)
	- Authors: Chuanqi Tan, Wei Qiu, Mosha Chen, Rui Wang, Fei Huang
	- Baseline Methods: LSTM-CRF, Multi-CRF, FOFE, Transition, Cascaded-CRF, MH, LH, SH, ARNs, MGNER, Merge and Label
	- Datasets: ACE2004, ACE2005, GENIA
	- Approach:
	
11. [**EMNLP 2020**]: [HIT: Nested Named Entity Recognition via Head-Tail Pair and Token Interaction](https://aclanthology.org/2020.emnlp-main.486/)
	- Authors: Yu Wang, Yun Li, Hanghang Tong, Ziye Zhu
	- Baseline Methods: Sequence-based methods, Hypergraph-based methods.
	- Datasets: GENIA, GermEval, JNLPBA
	-
12. [**TACL 2020**]: [Nested Named Entity Recognition via Second-best Sequence Learning and Decoding](https://aclanthology.org/2020.tacl-1.39.pdf)
	- Authors: Takashi Shibuya, Eduard Hovy
	- Baseline Methods: LSTM. hyp, layered-CRF, SH (Segm. hyp), Exhaustive, Boundary-aware, GEANN, Merge & Label, Seq2seq
	- Datasets: ACE-2005, GENIA
	- Approach: SH [Code](https://github.com/yahshibu/nested-ner-tacl2020)
## Danish

1. [**COLING 2020**]: [DaN+: Danish Nested Named Entities and Lexical Normalization](https://aclanthology.org/2020.coling-main.583/)
	- Authors: Barbara Plank, Kristian Nørgaard Jensen, Rob van der Goot
	- Datasets: German News, DAN+: News (UD-DDT), Reddit, Twitter, Arto
	- Approach: [Code & Datasets](https://github.com/bplank/DaNplus)
	
## Frequent Baseline Methods

| Methods	|ACE-2005 (F1)	|	GENIA (F1)	|
|:----------|:--------------|:-------------:|
|[SH](https://aclanthology.org/2020.tacl-1.39.pdf)[12]   |76.83			|77.19			|
	