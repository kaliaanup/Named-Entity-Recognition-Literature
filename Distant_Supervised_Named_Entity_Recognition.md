# Distant Supervised Named Entity Recognition

1. [**ACL 2022**]: [Distantly Supervised Named Entity Recognition via Confidence-Based Multi-Class Positive and Unlabeled Learning](https://aclanthology.org/2022.acl-long.498/)
	- Baseline Methods: Dict/KB Matching, AutoNER, BERT-ES, BNPUL\_BiLSTM, MPU\_BERT, MPU\_LBiLSTM
	- Datasets: BC5CDR, CoNLL2003
	- Approach: Conf-MPUBERT, Conf-MPULBiLSTM[Code & Datasets](https://github.com/kangISU/Conf-MPU-DS-NER)
	
2. [**NAACL 2022**]: [Label Refinement via Contrastive Learning for Distantly-Supervised Named Entity Recognition](https://aclanthology.org/2022.findings-naacl.203/)
	- Baseline Methods: Dictionary Match, . Fully-supervised Methods (BiLSTM-CRF, RoBERTa), Distantly-supervised Methods (AutoNER, BOND, RoSTER)	
	- Datasets: BC5CDR, NCBI-Disease
	- Approach: [Code & Dataset](https://github.com/yinghy18/CReDEL)
	
3. [**EACL 2022**]: [GLaRA: Graph-based Labeling Rule Augmentation for Weakly Supervised Named Entity Recognition](https://aclanthology.org/2021.eacl-main.318.pdf)
	- Baseline Methods: AutoNER, Snorkel, SwellShark, LinkedHMM	
	- Datasets: NCBI, BC5CDR, LaptopReview
	- Approach: GLaRA [Code](https://github.com/zhaoxy92/GLaRA)
	
4. [**AAAI 2021**]: [Denoising Distantly Supervised Named Entity Recognition via a Hypergeometric Probabilistic Mode](https://ojs.aaai.org/index.php/AAAI/article/view/17702/17509)
	- Baseline: Supervised Learning, Naive Distant Supervision, Instance-level Expectation Maximization, XR-Loss, Positive-Unlabeled Learning	
	- Dataset: ACE2005
	- Approach: HGL
		
5. [**ACL 2021**]: [Named Entity Recognition with Small Strongly Labeled and Large Weakly Labeled Data](https://aclanthology.org/2021.acl-long.140.pdf)
	- Baseline Methods: Supervised (Query-RoBERTa-CRF), Semi-supervised (SST), Weakly Supervised (WSL, Weighted WSL, Partial WSL, Weighted Partial WSL, Robust WSL)	
	- Dataset: BC5CDR-Chem, BC5CDRDisease, NCBI-Disease
	- Approach: NEEDLE [Code](https://github.com/amzn/amazon-weak-ner-needle)
	
6. [**ACL 2021**]: [BERTifying the Hidden Markov Model for Multi-Source Weakly Supervised Named Entity Recognition](https://aclanthology.org/2021.acl-long.482.pdf)
	- Baseline Methods: Supervised (Query-RoBERTa-CRF, Query-mBERT-CRF, BioBERT-CRF), Semi-Supervised Self-Training, Weakly Supervised Learning, Weighted WSL, Robust WSL, Partial WSL
	- Dataset: E-commerce query NER, Biomedical NER (BC5CDR-Chem, BC5CDRDisease, NCBI-Disease)
	- Approach: CHMM-ALT [Code](https://github.com/Yinghao-Li/CHMM-ALT)
	
7. [**ACL 2021**]: [De-biasing Distantly Supervised Named Entity Recognition via Causal Intervention](https://aclanthology.org/2021.acl-long.371.pdf)
	- Baseline Methods: DictMatch, Fully-supervised (BiLSTM-CRF, RoBERTa-base), Naive Distant Supervision (DSNER), Positive-Unlabeled Learning, BOND	
	- Datasets: CoNLL2003, Twitter, Webpage, Wikigold
	- Approach: [Code](https://github.com/zwkatgithub/DSCAU)
	
8. [**ACL 2021**]: [Weakly Supervised Named Entity Tagging with Learnable Logical Rules](https://arxiv.org/abs/2107.02282)
	- Baseline Methods: Seed Rules, AutoNER, LinkedHMM, HMM-agg, Seed Rule + Neural Tagger, Self-training
	- Dataset: BC5CDR, CHEMDNER, CoNLL2003
	- Approach: [Code & Dataset](https://github.com/JiachengLi1995/TALLOR)
	
9. [**ACL 2021**]: [Named Entity Recognition through Deep Representation Learning and Weak Supervision](https://aclanthology.org/2021.findings-acl.335.pdf)
	- Baseline Methods: Snorkel, Fuzzy-LSTMCRF, HMM, Majority Vote, Unweighted Vote
	- Dataset: CoNLL2003, BC5CDR, NCBI-Disease, LaptopReview
	- Approach: DWS [Code & Dataset]
	
10. [**ACL 2021**]: [The Utility and Interplay of Gazetteers and Entity Segmentation for Named Entity Recognition in English](https://aclanthology.org/2021.findings-acl.349/)
	- Baseline Methods: Gazetteers (WORD GAZ, GAZ IOBES, GAZ FINE, PHRASE GAZ, LRN GAZ), Segmentation (SEG REG, SEG SUP, SAC, HSCRF)
	- Datasets: CoNLL2003, ON, Broad Twitter Corpus, Temporal Twitter Corpus
	- Approach: [Code](https://github.com/guillaumegenthial/tf_ner), [SAC](https://github.com/XiaoShiyuan/NCRF-SAC), [HSCRF](https://github.com/ZhixiuYe/HSCRF-pytorch)
	
11. [**EMNLP 2021**]: [Distantly-Supervised Named Entity Recognition with Noise-Robust Learning and Language Model Augmented Self-Training](https://aclanthology.org/2021.emnlp-main.810.pdf)
	- Baseline Methods: Distantly-supervised methods (Distant Match, Distant RoBERTa, AutoNER, BOND), Supervised methods (BiLSTM-CNN-CRF, RoBERTa)
	- Datasets: CoNLL03, OntoNotes5.0, Wikigold
	- Approach: [Code](https://github.com/yumeng5/RoSTER)
	
12. [**ACL 2020**]: [Named Entity Recognition without Labelled Data: A Weak Supervision Approach](https://aclanthology.org/2020.acl-main.139/)
	- Baseline Methods: Ontonotes-trained NER, Majority voting (MV), Snorkel model, mSDA, AdaptaBERT, Mixtures of multinomials
	- Datasets: CoNLL 2003, Reuters & Bloomberg
	
13. [**ACL 2020**]: [Soft Gazetteers for Low-Resource Named Entity Recognition](https://aclanthology.org/2020.acl-main.722/)
	- Baseline Methods: NOFEAT (CNN-LSTM-CRF), BINARYGAZ, WIKIMEN, PBELSUPERVISED, PBELZERO
	- Datasets: LORELEI, CoNLL-2003
	- Approach: [Code](https://github.com/shrutirij/soft-gazetteers)
	
14. [**AAAI 2020**]: [HAMNER: Headword Amplified Multi-span Distantly Supervised Method for Domain Specific Named Entity Recognition](https://ojs.aaai.org/index.php/AAAI/article/view/6358/6214)
	- Baseline Methods: Supervised model, SwellShark, Dictionary Match, AutoNER
	- Datasets: BC5CDR, NCBI-Disease, LaptopReview
	- Approach: HAMNER
	
15. [**EMNLP 2020**]: [Counterfactual Generator: A Weakly-Supervised Method for Named Entity Recognition](https://aclanthology.org/2020.emnlp-main.590/)
	- Baseline Methods: 
	- Datasets: CNER1, IDiag, CLUENER
	- Approach: LSTMTagger, BERTTagger