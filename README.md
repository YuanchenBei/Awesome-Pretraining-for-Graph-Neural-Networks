# Awesome-Pretraining-for-Graph-Neural-Networks
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-yellow.svg)](https://github.com/YuanchenBei/Awesome-Pretraining-for-Graph-Neural-Networks) 
![Stars](https://img.shields.io/github/stars/YuanchenBei/Awesome-Pretraining-for-Graph-Neural-Networks?color=green)

This repository contains a curated list of papers on (or related to) **pre-training for graph neural networks** (Pre-train4GNN), which are categorized based on their published years, graph types, pre-training strategies, tuning strategies, and applications.

*Continuously updating!*

-----
### Papers

| **Paper Title** | **Venue** | **Graph Type**  | **Pre-training Strategy** | **Tuning Strategy** | **Application** |**PDF Link** | **Code Link** |
| --------------- | :--------: | :--------: | :--------: | :--------: | :--------: | :--------: | :--------: | 
| GraphPrompt: Unifying Pre-Training and Downstream Tasks for Graph Neural Networks | _WWW 2023_ | Static | Contrastive | Prompt | General | [[PDF]](https://arxiv.org/pdf/2302.08043.pdf) | [[Code]](https://github.com/Starlien95/GraphPrompt) |
| GraphMAE2: A Decoding-Enhanced Masked Self-Supervised Graph Learner | _WWW 2023_ | Static | Generative | N/A | General |[[PDF]](https://arxiv.org/pdf/2304.04779.pdf) | [[Code]](https://github.com/THUDM/GraphMAE2) |
| Structure Pretraining and Prompt Tuning for Knowledge Graph Transfer | _WWW 2023_ | KG | Generative | Prompt | General | [[PDF]](https://dl.acm.org/doi/pdf/10.1145/3543507.3583301) | [[Code]](https://github.com/zjukg/KGTransformer) |
| GPPT: Graph Pre-training and Prompt Tuning to Generalize Graph Neural Networks | _KDD 2022_ | Static | Generative | Prompt | General | [[PDF]](https://dl.acm.org/doi/pdf/10.1145/3534678.3539249) | [[Code]](https://github.com/MingChen-Sun/GPPT) |
| GraphMAE: Self-Supervised Masked Graph Autoencoders | _KDD 2022_ | Static | Generative | N/A | General | [[PDF]](https://dl.acm.org/doi/pdf/10.1145/3534678.3539321) | [[Code]](https://github.com/THUDM/GraphMAE) |
| Mask and Reason: Pre-Training Knowledge Graph Transformers for Complex Logical Queries | _KDD 2022_ | KG | Generative | Generative | General | [[PDF]](https://dl.acm.org/doi/pdf/10.1145/3534678.3539472) | [[Code]](https://github.com/THUDM/kgTransformer) |
| Pre-training Enhanced Spatial-temporal Graph Neural Network for Multivariate Time Series Forecasting| _KDD 2022_ | ST-Graph | Generative | N/A |  Time Series Forecasting | [[PDF]](https://dl.acm.org/doi/pdf/10.1145/3534678.3539396) | [[Code]](https://github.com/zezhishao/STEP) |
| Self-supervised Heterogeneous Graph Pre-training Based on Structural Clustering | _NIPS 2022_ | Heterogeneous | Clustering | N/A | General | [[PDF]](https://openreview.net/pdf?id=fBU4qsM6Fkf) | [[Code]](https://github.com/kepsail/SHGP) | 
| Pre-training Molecular Graph Representation with 3D Geometry | _ICLR 2022_ | Static | Generative+Contrastive | N/A | Biology | [[PDF]](https://openreview.net/pdf?id=xQUe1pOKPam) | [[Code]](https://github.com/chao1224/GraphMVP) |
| Graph Pre-training for AMR Parsing and Generation | _ACL 2022_ | Semantic Graph | Generative | N/A | NLP (AMR) | [[PDF]](https://aclanthology.org/2022.acl-long.415.pdf) | [[Code]](https://github.com/goodbai-nlp/AMRBART) |
| Neural Graph Matching for Pre-training Graph Neural Networks | _SDM 2022_ | Static | Contrastive | N/A | General | [[PDF]](https://epubs.siam.org/doi/pdf/10.1137/1.9781611977172.20) | [[Code]](https://github.com/RUCAIBox/GMPT) |
| Pre-train Graph Neural Networks for Brain Network Analysis | _Big Data 2022_ | Static | Contrastive | N/A | Biology | [[PDF]](https://openreview.net/pdf?id=I1Mdyc2Bg5x) | N/A |
| GCCAD: Graph Contrastive Learning for Anomaly Detection | _TKDE 2022_ | Static | Contrastive | N/A | Anomaly Detection | [[PDF]](https://arxiv.org/pdf/2108.07516.pdf) | [[Code]](https://github.com/THUDM/GraphCAD) |
| An Adaptive Graph Pre-training Framework for Localized Collaborative Filtering | _TOIS 2022_ | Static | Contrastive | Meta-Learning | Recommendation | [[PDF]](https://dl.acm.org/doi/pdf/10.1145/3555372) | N/A |
| GCCAD: Graph Contrastive Learning for Anomaly Detection | _TKDE 2022_ | Static | Contrastive | N/A | Anomaly Detection | [[PDF]](https://arxiv.org/pdf/2108.07516.pdf) | [[Code]](https://github.com/THUDM/GraphCAD) |
| Pre-training Graph Neural Networks for Link Prediction in Biomedical Networks | _Bioinformatics 2022_ | Static | Generative | N/A |  Biology | [[PDF]](https://ink.library.smu.edu.sg/cgi/viewcontent.cgi?article=8161&context=sis_research) | [[Code]](https://github.com/longyahui/PT-GNN) |
| Pre-Training of Equivariant Graph Matching Networks with Conformation Flexibility for Drug Binding | _Advanced Science 2022_ | Dynamic | Generative | N/A | Biology | [[PDF]](https://onlinelibrary.wiley.com/doi/pdf/10.1002/advs.202203796) | [[Code]](https://github.com/smiles724/ProtMD) |
| Pre-training on Dynamic Graph Neural Networks | _Neurocomputing 2022_ | Dynamic | Generative | N/A | General | [[PDF]](https://arxiv.org/pdf/2102.12380.pdf) | [[Code]](https://github.com/Mobzhang/PT-DGNN) |
| Adaptive Transfer Learning on Graph Neural Networks | _KDD 2021_ | Static | N/A | Meta Learning | General | [[PDF]](https://dl.acm.org/doi/pdf/10.1145/3447548.3467450) | [[Code]](https://github.com/Sean-Huang65/AUX-TS) |
| Pre-training on Large-Scale Heterogeneous Graph | _KDD 2021_ | Heterogeneous | Contrastive | N/A | General | [[PDF]](https://dl.acm.org/doi/pdf/10.1145/3447548.3467396) | [[Code]](https://github.com/BUPT-GAMMA/PTHGNN) |
| Self-supervised Graph-level Representation Learning with Local and Global Structure | _ICML 2021_ | Static | Contrastive | N/A | Biology | [[PDF]](http://proceedings.mlr.press/v139/xu21g/xu21g.pdf) | [[Code]](https://github.com/DeepGraphLearning/GraphLoG) |
| Pairwise Half-graph Discrimination: A Simple Graph-level Self-supervised Strategy for Pre-training Graph Neural Networks | _IJCAI 2021_ | Static | Decomposition | N/A | General | [[PDF]](https://www.ijcai.org/proceedings/2021/0371.pdf) | N/A |
| Contrastive Pre-Training of GNNs on Heterogeneous Graphs | _CIKM 2021_ | Heterogeneous | Contrastive | N/A | General | [[PDF]](https://dl.acm.org/doi/pdf/10.1145/3447548.3467396) | [[Code]](https://github.com/BUPT-GAMMA/CPT-HG) |
| Pre-Training Graph Neural Networks for Cold-Start Users and Items Representation | _WSDM 2021_ | Static | Generative+RL | N/A | Recommendation | [[PDF]](https://dl.acm.org/doi/pdf/10.1145/3437963.3441738) | [[Code]](https://github.com/jerryhao66/Pretrain-Recsys) |
| Pre-training Graph Transformer with Multimodal Side Information for Recommendation | _MM 2021_ | Static | Generative | N/A | Recommendation | [[PDF]](https://dl.acm.org/doi/pdf/10.1145/3474085.3475709) | [[Code]](https://github.com/uoo723/PMGT) |
| Learning to Pre-train Graph Neural Networks | _AAAI 2021_ | Static | Contrastive | N/A | General | [[PDF]](https://ojs.aaai.org/index.php/AAAI/article/download/16552/16359) | [[Code]](https://github.com/rootlu/L2P-GNN) |
| GPT-GNN: Generative Pre-Training of Graph Neural Networks | _KDD 2020_ | Static | Generative | N/A | General | [[PDF]](https://dl.acm.org/doi/pdf/10.1145/3394486.3403237) | [[Code]](https://github.com/UCLA-DM/GPT-GNN) |
| GCC: Graph Contrastive Coding for Graph Neural Network Pre-Training | _KDD 2020_ | Static | Contrastive | N/A | General | [[PDF]](https://dl.acm.org/doi/pdf/10.1145/3394486.3403168) | [[Code]](https://github.com/THUDM/GCC) |
| Strategies for Pre-training Graph Neural Networks | _ICLR 2020_ | Static | Generative | N/A | Chemistry&Biology | [[PDF]](https://arxiv.org/pdf/1905.12265.pdf) | [[Code]](http://snap.stanford.edu/gnn-pretrain) |
| Pre-training of Graph Augmented Transformers for Medication Recommendation | _IJCAI 2019_ | Ontology Tree | Generative | N/A |  Recommendation | [[PDF]](https://www.ijcai.org/proceedings/2019/0825.pdf) | [[Code]](https://github.com/jshang123/G-Bert) |

---------

### Pre-print Papers
| **Paper Title** | **Venue** | **Graph Type**  | **Pre-training Strategy** | **Tuning Strategy** | **Application** |**PDF Link** | **Code Link** |
| --------------- | :--------: | :--------: | :--------: | :--------: | :--------: | :--------: | :--------: | 
| SGL-PT: A Strong Graph Learner with Graph Prompt Tuning | _Arxiv 2023_ | Static | Generative | Prompt | General | [[PDF]](https://arxiv.org/pdf/2302.12449.pdf) | N/A |
| DiP-GNN: Discriminative Pre-Training of Graph Neural Networks | _Arxiv 2022_ | Static | Generative | N/A | General | [[PDF]](https://arxiv.org/pdf/2209.07499.pdf) | N/A |
| Hypergraph Pre-training with Graph Neural Networks | _Arxiv 2021_ | Hypergraph | Contrastive | N/A | General | [[PDF]](https://arxiv.org/pdf/2302.08043.pdf) | N/A |
| GRAPH-BERT: Only Attention is Needed for Learning Graph Representations | _Arxiv 2020_ | Static | Generative | N/A | General | [[PDF]](http://www.ifmlab.org/files/paper/graph_bert.pdf) | [[Code]](https://github.com/jwzhanggy/Graph-Bert) |
| Pre-training Graph Neural Networks with Kernels | _Arxiv 2018_ | Static | Kernel | N/A | General | [[PDF]](https://arxiv.org/pdf/1811.06930.pdf) | N/A |

----------

### Survey Papers

| **Paper Title** | **Venue** | **PDF Link** | **Code Link** |
| --------------- | :--------: | :--------: | :--------: | 
| A Survey of Graph Prompting Methods: Techniques, Applications, and Challenges | _Arxiv 2023_ | [[PDF]](https://arxiv.org/pdf/2303.07275.pdf) | N/A |
| A Survey of Pre-training on Graphs: Taxonomy, Methods and Applications | _Arxiv 2022_ | [[PDF]](https://arxiv.org/pdf/2202.07893.pdf) | [[Code]](https://github.com/junxia97/awesome-pretrain-on-molecules) |
| Self-Supervised Learning of Graph Neural Networks: A Unified Review | _TPAMI 2022_ | [[PDF]](https://arxiv.org/pdf/2102.10757.pdf) | N/A |
| Graph Self-Supervised Learning: A Survey | _TKDE 2022_ |[[PDF]](https://arxiv.org/pdf/2103.00111.pdf) | N/A |
| Self-supervised Learning on Graphs: Contrastive, Generative,or Predictive | _TKDE 2021_ | [[PDF]](https://arxiv.org/pdf/2105.07342.pdf) | N/A |
| Self-supervised Learning on Graphs: Deep Insights and New Directions | _Arxiv 2020_ | [[PDF]](https://arxiv.org/pdf/2006.10141.pdf) | [[Code]](https://github.com/ChandlerBang/SelfTask-GNN) |

