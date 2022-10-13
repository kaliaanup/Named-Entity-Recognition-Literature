# Nested Named Entity Recognition

1. [**ACL 2022**]: [Nested Named Entity Recognition as Latent Lexicalized Constituency Parsing](https://aclanthology.org/2022.acl-long.428.pdf)
	- Authors: Chao Lou, Songlin Yang, Kewei Tu
	- Baseline Methods: SH, Pyramid, PO-TreeCRF, Seq2set, Locate&Label
	- Datasets: ACE2004, ACE2005, GENIA
	- Approach: **NNER-AS-PARSING**[Code](https://github.com/LouChao98/nner_as_parsing)

2. [**ACL 2022**]: [Nested Named Entity Recognition with Span-level Graphs](https://aclanthology.org/2022.acl-long.63/)
	- Authors: Juncheng Wan, Dongyu Ru, Weinan Zhang, Yong Yu
	- Baseline Methods: HyperGraph, Stack-LSTM, Seg-Graph, ARN, Seq2seq, Path-BERT, ML, Pyramid, SpERT, BENSC,  BERTMRC, NER-DP, DYGIE
	- Datasets: ACE2004, ACE2005, GENIA
	- Approach: **SLG-NER**
	
3. [**ACL 2022**]: [Bottom-Up Constituency Parsing and Nested Named Entity Recognition with Pointer Networks](https://aclanthology.org/2022.acl-long.171/)
	- Authors: Songlin Yang, Kewei Tu
	- Baseline Methods: Seq2set, Locate & Label, BARTNER-Word, MHSA-BERT, W, Pyramid, SH
	- Datasets: ACE 2004, ACE 2005, GENIA
	- Approach: **PointerNNER**[Code](https://github.com/sustcsonglin/pointer-net-for-nested)

4. [**IJCAI 2022**]: [Propose-and-Refine: A Two-Stage Set Prediction Network for Nested Named Entity Recognition](https://www.ijcai.org/proceedings/2022/0613.pdf)
	- Authors: Shuhui Wu, Yongliang Shen, Zeqi Tan, Weiming Lu
	- Baseline Methods: Seq2set, Locate & Label, 
	- Datasets: ACE 2004, ACE 2005, GENIA, KBP 2017
	- Approach: **PnRNet**

	
5. [**COLING 2022**]: [Nested Named Entity Recognition as Corpus Aware Holistic Structure Parsing](https://arxiv.org/abs/2204.08006)
	- Authors: Yifei Yang, Zuchao Li, Hai Zhao
	- Baseline Methods: Hyper-Graph, Seg-Graph, ARN, Merge-BERT, DYGIE, Seq2seq-BERT, Path-BERT, BERT-MRC, Seq2seq-BART, Seq2set-BERT 
	- Datasets: ACE2005, GENIA, KBP2017
	- Approach: **HSPNER**
	
6. [**COLING 2022**]: [Simple yet Powerful: An Overlooked Architecture for Nested Named Entity Recognition](https://aclanthology.org/2022.coling-1.184/)
	- Authors: Matias Rojas, Felipe Bravo-Marquez, Jocelyn Dunstan
	- Baseline Methods: Pyramid, Recursive-CRF, Layered, Exhaustive, Boundary, Biaffine
	- Datasets: GENIA, GermEval, Chilean Waiting List (performs best)
	- Approach: **MLC**[Code](https://github.com/matirojasg/nested-ner-mlc)
	
7. [**AAAI 2021**]: [A Supervised Multi-Head Self-Attention Network for Nested Named Entity Recognition](https://ojs.aaai.org/index.php/AAAI/article/view/17669)
	- Authors: Yongxiu Xu, Heyan Huang, Chong Feng, Yue Hu
	- Baseline Methods: sequence labeling-based models, span-based models
	- Datasets: ACE20042, ACE20053, GENIA, JNLPBA, CoNLL03
	- Approach: MHSA-BERT 
	
8. [**AAAI 2021**]: [Nested Named Entity Recognition with Partially-Observed TreeCRFs](https://arxiv.org/abs/2012.08478)
	- Authors: Yao Fu, Chuanqi Tan, Mosha Chen, Songfang Huang, Fei Huang
	- Baseline Methods: LSTM-CRF, FOFE, Transition, Cascaded-CRF, SH, MGNER, Merge and Label, Seq2seq, BENSC, Pyramid
	- Datasets: ACE2004, ACE2005, GENIA
	- Approach: **PO-TreeCRF**[Code](https://github.com/FranxYao/Partially-Observed-TreeCRFs)

9. [**ACL 2021**]: [A Unified Generative Framework for Various NER Subtasks](https://aclanthology.org/2021.acl-long.451/)
	- Authors: Hang Yan, Tao Gui, Junqi Dai, Qipeng Guo, Zheng Zhang, Xipeng Qiu
	- Baseline Methods: SH, Pyramid, a few more flat ner baselines
	- Datasets: ACE2004, ACE2005, GENIA
	- Approach: **BARTNER**[Code](https://github.com/yhcc/BARTNER)


10. [**ACL 2021**]: [Nested Named Entity Recognition via Explicitly Excluding the Influence of the Best Path](https://aclanthology.org/2021.acl-long.275/)
	- Authors: Yiran Wang, Hiroyuki Shindo, Yuji Matsumoto, Taro Watanabe
	- Baseline Methods:layered-CRF, Transition, SH (Segm. hyp), Anchor-Region, Seq2seq, (a few more..)
	- Datasets:ACE2004, ACE2005, GENIA
	- Approach: **W**[Code](https://github.com/speedcell4/nersted)

11. [**IJCAI 2021**]: [A Sequence-to-Set Network for Nested Named Entity Recognition](https://arxiv.org/pdf/2105.08901.pdf)
	- Authors: Zeqi Tan, Yongliang Shen, Shuai Zhang, Weiming Lu, Yueting Zhuang
	- Baseline Methods: Biaffine, Pyramid, BiFlaG, Seq2seq, Second-best, ARN, Hyper-Graph, KBP17-Best
	- Datasets: ACE 2004,  ACE 2005, GENIA, KBP 2017 
	- Approach: **Seq2set** [Code](https://github.com/zqtan1024/sequence-to-set)
	
12. [**ACL 2021**]: [Locate and Label: A Two-stage Identifier for Nested Named Entity Recognition](https://aclanthology.org/2021.acl-long.216/)
	- Authors: Yongliang Shen, Xinyin Ma, Zeqi Tan, Shuai Zhang, Wen Wang, Weiming Lu
	- Baseline Methods: SH, Pyramid, few more  ..
	- Datasets: ACE 2004,  ACE 2005, GENIA, KBP 2017 
	- Approach: **Locate & Label**[Code](https://github.com/tricktreat/locate-and-label)

13. [**ACL 2020**]: [Bipartite Flat-Graph Network for Nested Named Entity Recognition](https://aclanthology.org/2020.acl-main.571/)
	- Authors: Ying Luo, Hai Zhao
	- Baseline Methods: LSTM-CRF, Multi-CRF, layered-CRF, LH (LSTM. hyp), SH (Segm. hyp), Exhaustive, Anchor-Region, Merge & Label, Boundary-aware, GEANN, KBP2017 Overview
	- Datasets: ACE2005, GENIA, KBP2017
	- Approach: [Code](https://github.com/cslydia/BiFlaG)
	
14. [**ACL 2020**]: [Pyramid: A Layered Model for Nested Named Entity Recognition](https://aclanthology.org/2020.acl-main.525.pdf)
	- Authors: Jue Wang, Lidan Shou, Ke Chen, Gang Chen
	- Baseline Methods: Non-LM based (Transition, SH, FOFE, Merge & Label, Anchor-Region, LH, Cascaded-CRF), LM based (ELMO, BERT, BERT+Flair)
	- Datasets:ACE-2004, ACE-2005, GENIA, NNE
	- Approach: **Pyramid**[Code](https://github.com/LorrinWWW/Pyramid)
	
15. [**AAAI 2020**]: [Boundary Enhanced Neural Span Classification for Nested Named Entity Recognition](https://ojs.aaai.org/index.php/AAAI/article/view/6434)
	- Authors: Chuanqi Tan, Wei Qiu, Mosha Chen, Rui Wang, Fei Huang
	- Baseline Methods: LSTM-CRF, Multi-CRF, FOFE, Transition, Cascaded-CRF, MH, LH, SH, ARNs, MGNER, Merge and Label
	- Datasets: ACE2004, ACE2005, GENIA
	- Approach:
	
16. [**EMNLP 2020**]: [HIT: Nested Named Entity Recognition via Head-Tail Pair and Token Interaction](https://aclanthology.org/2020.emnlp-main.486/)
	- Authors: Yu Wang, Yun Li, Hanghang Tong, Ziye Zhu
	- Baseline Methods: Sequence-based methods, Hypergraph-based methods.
	- Datasets: GENIA, GermEval, JNLPBA
	-
17. [**TACL 2020**]: [Nested Named Entity Recognition via Second-best Sequence Learning and Decoding](https://aclanthology.org/2020.tacl-1.39.pdf)
	- Authors: Takashi Shibuya, Eduard Hovy
	- Baseline Methods: LSTM. hyp, layered-CRF, SH (Segm. hyp), Exhaustive, Boundary-aware, GEANN, Merge & Label, Seq2seq
	- Datasets: ACE-2005, GENIA
	- Approach: **SH**[Code](https://github.com/yahshibu/nested-ner-tacl2020)
## Danish

1. [**COLING 2020**]: [DaN+: Danish Nested Named Entities and Lexical Normalization](https://aclanthology.org/2020.coling-main.583/)
	- Authors: Barbara Plank, Kristian Nørgaard Jensen, Rob van der Goot
	- Datasets: German News, DAN+: News (UD-DDT), Reddit, Twitter, Arto
	- Approach: [Code & Datasets](https://github.com/bplank/DaNplus)
	
## Frequent Baseline Methods

| Methods	|ACE-2004 (F1)	|	ACE-2005 (F1) | GENIA (F1)	| NNE (F1) | KBP-2017 (F1)| Time Complexity|
|:----------|:--------------|:-------------:|:-------------:|:-------------:|:-------------:|:-------------:|
|[PnRNet (Wu et al., 2022))](https://www.ijcai.org/proceedings/2022/0613.pdf)|88.12|87.63|81.85||85.27||
|[HSPNER (Yang et al., 2022)](https://arxiv.org/pdf/2204.08006.pdf)| | 87.75|  77.70||87.67|O(N^3)|
|[NNER-AS-PARSING (Lou et al., 2022)](https://aclanthology.org/2022.acl-long.428.pdf)| 87.90|  86.91|  78.44|94.64||O(N^4)|
|[SLG-NER (Wan et al., 2022)](https://aclanthology.org/2022.acl-long.63/)| 86.31|  85.11|  79.30|||O(N^2*d)|
|[Locate & Label(Shen et al., 2021) + BERT](https://aclanthology.org/2021.acl-long.216/)| 87.41|  86.67|  80.54||  84.05|O(N^2+ck)|
|[Seq2set(Tan et al., 2021) + BERT](https://arxiv.org/pdf/2105.08901.pdf)| 87.26| 87.05| 80.50|| 83.96||
|[PointerNNER (Yang and Tu, 2022)](https://aclanthology.org/2022.acl-long.171.pdf)|86.94|85.53|78.16|||O(N^2)|
|[BARTNER-Word(Yan et al., 2021)+ BART-Large](https://aclanthology.org/2021.acl-long.451/)| 86.84| 84.74|  78.93||||
|[PO-TreeCRF(Fu et al., 2021) + BERT](https://arxiv.org/abs/2012.08478)| 86.6| 85.4|78.2|||O(N^3)|
|[W-naive(Wang et al., 2021)](https://aclanthology.org/2021.acl-long.275/)|79.38|78.32|77.03|||O(n+mlogn)|
|[W-max(Wang et al., 2021)](https://aclanthology.org/2021.acl-long.275/)|79.92|78.81|77.22|||O(n+mlogn)|
|[W-logsumexp(Wang et al., 2021)](https://aclanthology.org/2021.acl-long.275/)|80.08|78.55|77.37|||O(n+mlogn)|
|[W-naive(Wang et al., 2021) + BERT](https://aclanthology.org/2021.acl-long.275/)|85.73|84.20|78.45|||O(n+mlogn)|
|[W-max(Wang et al., 2021) + BERT](https://aclanthology.org/2021.acl-long.275/)|85.68|84.71|78.67|||O(n+mlogn)|
|[W-logsumexp(Wang et al., 2021) + BERT](https://aclanthology.org/2021.acl-long.275/)|86.06|84.30|78.54|||O(n+mlogn)|
|[W-naive(Wang et al., 2021) + BERT + FLAIR](https://aclanthology.org/2021.acl-long.275/)|86.11|84.52|78.79|||O(n+mlogn)|
|[W-max(Wang et al., 2021) + BERT + FLAIR](https://aclanthology.org/2021.acl-long.275/)|86.19|84.73|78.87|||O(n+mlogn)|
|[W-logsumexp(Wang et al., 2021) + BERT + FLAIR](https://aclanthology.org/2021.acl-long.275/)|86.42|84.93|78.93|||O(n+mlogn)|
|[Pyramid-Basic (Wang et al., 2020)](https://aclanthology.org/2020.acl-main.525.pdf)|79.83|79.32|77.55|93.64||O(TL)|
|[Pyramid-Full (Wang et al., 2020)](https://aclanthology.org/2020.acl-main.525.pdf)|80.27|79.42|77.78|93.70||O(TL)|
|[Pyramid-Basic (Wang et al., 2020) + BERT](https://aclanthology.org/2020.acl-main.525.pdf)|86.28|84.66|79.19|94.37||O(TL)|
|[Pyramid-Basic (Wang et al., 2020) + BERT + FLAIR](https://aclanthology.org/2020.acl-main.525.pdf)| 86.78| 85.49|79.24|94.47||O(TL)|
|[Pyramid-Basic (Wang et al., 2020) + ALBERT](https://aclanthology.org/2020.acl-main.525.pdf)|86.99| 85.87| 78.82|94.51||O(TL)|
|[Pyramid-Basic (Wang et al., 2020) + ALBERT + FLAIR](https://aclanthology.org/2020.acl-main.525.pdf)|86.89| 86.15|78.93| 94.48||O(TL)|
|[Pyramid-Basic (Wang et al., 2020) + ALBERT + BERT](https://aclanthology.org/2020.acl-main.525.pdf)| 87.70|86.27| 78.95| 94.63||O(TL)|
|[Pyramid-Full (Wang et al., 2020) + BERT + FLAIR](https://aclanthology.org/2020.acl-main.525.pdf)|||79.31 |||O(TL)|
|[Pyramid-Full (Wang et al., 2020) + ALBERT + BERT](https://aclanthology.org/2020.acl-main.525.pdf)|87.74|86.34||94.68||O(TL)|
|[SH (Shibuya & Hovy, 2020)](https://aclanthology.org/2020.tacl-1.39.pdf)|77.44|76.83|77.19|||O(mn^2)|
|[SH (Shibuya & Hovy, 2020) + BERT](https://aclanthology.org/2020.tacl-1.39.pdf)|84.97|83.99|77.05|||O(mn^2)|
|[SH (Shibuya & Hovy, 2020) + BERT + FLAIR](https://aclanthology.org/2020.tacl-1.39.pdf)|85.82|84.34|77.36|||O(mn^2)|