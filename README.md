# Awesome Graph Neural Network Privacy Attack and Preservation Papers and Datasets
[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com)
![License](https://img.shields.io/github/license/NDS-VU/awesome-gnn-privacy-papers.svg?color=blue)⠀[![NDS-VU](https://img.shields.io/twitter/follow/nds_vu?style=social&logo=twitter)](https://twitter.com/intent/follow?screen_name=nds_vu)⠀

This repository aims to provide links to works about privacy attacks and privacy preservation on graph data with Graph Neural Networks (GNNs). Additionally, this repository provides links to relevent datasets that have been used or can be potentially used for privacy study with graphs.

### Contents

* [1. Survey Papers](#1-survey-papers)
* [2. GNN Privacy Attack Papers](#2-gnn-privacy-attack-papers)
	* [2.1 Membership Inference Attack](#21-membership-inference-attack)
	* [2.2 Link Inference Attack](#22-link-inference-attack)
* [3. GNN Privacy Preservation Papers](#3-gnn-privacy-preservation-papers)
	* [3.1 Latent Factor Disentangling](#31-latent-factor-disentangling)
	* [3.2 Adversarial Training](#32-adversarial-training)
	* [3.3 Differentially Private Approaches](#33-differentially-private-approaches)
	* [3.4 Federated Learning](#34-federated-learning-approaches)
* [4. Datasets](#4-datasets)


## 1. Survey Papers
1. **A Survey on Privacy in Graph Neural Networks: Attacks, Preservation, and Applications (coming soon!).**
   *authors from NDS Lab and ORNL.* 
1. **GNN Surveys (to be added).**
1. **Privacy in ML (to be added).**
 

## 2. GNN Privacy Attack Papers
### 2.1 Membership Inference Attack
1. **Membership Inference Attack on Graph Neural Networks.** *Iyiola E. Olatunji,Wolfgang Nejdl, and Megha Khosla.* arXiv 2021. [[paper]](https://arxiv.org/pdf/2101.06570.pdf)
2. **Node-Level Membership Inference Attacks Against Graph Neural Networks.** *Xinlei He, Rui Wen, Yixin Wu, Michael Backes, Yun Shen, and Yang Zhang.* arXiv 2021. [[paper]](https://arxiv.org/pdf/2102.05429.pdf)
3. **Quantifying Privacy Leakage in Graph Embedding.** *Vasisht Duddu, Antoine Boutet, and Virat Shejwalkar.* arXiv 2021. [[paper]](https://arxiv.org/pdf/2010.00906.pdf)

### 2.2 Link Inference Attack
1. **Privacy Attacks on Network Embeddings.** *Michael Ellers, Michael Cochez, Tobias Schumacher, Markus Strohmaier, and Florian Lemmerich.* arXiv 2019. [[paper]](https://arxiv.org/pdf/1912.10979.pdf)[[code]](https://github.com/embedding-attack/embAttack)
2. **Stealing Links from Graph Neural Networks.** *Xinlei He, Jinyuan Jia, Michael Backes, Neil Zhenqiang Gong, and Yang Zhang.* USENIX Security 2021. [[paper]](https://www.usenix.org/system/files/sec21summer_he.pdf)
3. **Quantifying Privacy Leakage in Graph Embedding** *Vasisht Duddu, Antoine Boutet, and Virat Shejwalkar.* arXiv 2021. [[paper]](https://arxiv.org/pdf/2010.00906.pdf)
4. **GraphMI: Extracting Private Graph Data from Graph Neural Networks.** *Zaixi Zhang, Qi Liu, Zhenya Huang, Hao Wang, Chengqiang Lu, Chuanren Liu, and Enhong Chen.* arXiv 2021. [[paper]](https://arxiv.org/pdf/2106.02820.pdf)[[code]](https://github.com/zaixizhang/GraphMI)
5. **Inference Attacks Against Graph Neural Networks.** *Zhikun Zhang, Min Chen, Michael Backes, Yun Shen, and Yang Zhang.* USENIX Security 2022. [[paper]](https://arxiv.org/pdf/2110.02631.pdf)[[code]](https://github.com/Zhangzhk0819/GNN-Embedding-Leaks)

## 3. GNN Privacy Preservation Papers
### 3.1 Latent Factor Disentangling
1. **Adversarial Privacy Preserving Graph Embedding against Inference Attack.** *Kaiyang Li, Guangchun Luo, Yang Ye, Wei Li, Shihao Ji, and Zhipeng Cai.* IEEE IoT-J 2020. [[paper]](https://arxiv.org/pdf/2008.13072.pdf)[[code]](https://github.com/KaiyangLi1992/Privacy-Preserving-Social-Network-Embedding)
2. **Learning privacy-preserving graph embeddings against sensitive attributes inference.** *Wang, Chong Xiao, Zhao Kai, and Wee Peng Tay.* openreview.net. [[paper]](https://openreview.net/pdf?id=cRzIAw8Rem2)
3. **Learning privacy-preserving graph convolutional network with partially observed sensitive attribute.** *Hui Hu, Lu Cheng, Jayden Parker Vap, and Mike Borowczak.* Proceedings of the ACM Web Conference 2022. [[paper]](https://dl.acm.org/doi/pdf/10.1145/3485447.3511975?casa_token=cUalFoJkOogAAAAA:rHjhCZZqbHBCBd_5Ss2foVhmwTIkqC_eux_5e-qD4z5F5AbPwvOrztbn3vmD8ygnJeetWleZN7DD)[[code]](https://github.com/HuiHu1/Privacy-Preserving-Graph-Convolutional-Network)
4. **Disentangled Graph Collaborative Filtering.** *Xiang Wang, Hongye Jin, An Zhang, Xiangnan He, Tong Xu, and Tat-Seng Chua.* Proceedings of the 43rd international ACM SIGIR conference on research and development in information retrieval 2020. [[paper]](https://dl.acm.org/doi/pdf/10.1145/3397271.3401137?casa_token=F1WUzs00vQQAAAAA:XMcUhY-kzTZhC_fEB2-Ohks0RhvItlNQl-pzBMMW-keLnz0aSjmydzt_BHH8TgWCvMuSnIDfNIub)[[code]](https://github.com/xiangwang1223/disentangled_graph_collaborative_filtering)

### 3.2 Adversarial Training
1. **NetFense: Adversarial Defenses against Privacy Attacks on Neural Networks for Graph Data.** *I-Chung Hsieh and Cheng-Te Li.* IEEE-TKDE 2021. [[paper]](https://arxiv.org/pdf/2106.11865.pdf)[[code]](https://github.com/ICHproject/NetFense/)
2. **∊-k anonymization and adversarial training of graph neural networks for privacy preservation in social networks.** *Hu Tian, Xiaolong Zheng, Xingwei Zhang, and Daniel Dajun Zeng.* Electronic Commerce Research and Applications 50 (2021): 101105. [[paper]](https://www.sciencedirect.com/science/article/pii/S1567422321000776?casa_token=-qW4_RFc6GUAAAAA:P3_-plK7njrLwMBTnPQM6jI-Wtm-gjxB3SCFOWlYU_pVevQe4ktnJ15M57vEqpMqxxt71rAD)
3. **SecGNN: Privacy-preserving graph neural network training and inference as a cloud service.** *Songlei Wang, Yifeng Zheng, and Xiaohua Jia.* IEEE Transactions on Services Computing 2023.[[paper]](https://ieeexplore.ieee.org/iel7/4629386/4629387/10035510.pdf)[[Code]](https://github.com/songleiW/SecGNN)
4. **Dual constraints and adversarial learning for fair recommender.** *Haifeng Liu, Nan Zhao, Xiaokun Zhang, Hongfei Lin, Liang Yang, Bo Xu, Yuan Lin, and Wenqi Fan.* Knowledge-Based Systems 2022. [[paper]](https://www.sciencedirect.com/science/article/pii/S0950705121011424)
5. **Information Obfuscation of Graph Neural Networks.** *Peiyuan Liao, Han Zhao, Keyulu Xu, Tommi Jaakkola, Geoffrey Gordon, Stefanie Jegelka, and Ruslan Salakhutdinov.* ICML 2021. [[paper]](http://proceedings.mlr.press/v139/liao21a/liao21a.pdf)[[code]](https://github.com/liaopeiyuan/GAL)
6. **Privacy-preserving representation learning on graphs: A mutual information perspective.** *Wang, Binghui, Jiayi Guo, Ang Li, Yiran Chen, and Hai Li.*  Proceedings of the 27th ACM SIGKDD Conference on Knowledge Discovery & Data Mining 2021. [[paper]](https://dl.acm.org/doi/pdf/10.1145/3447548.3467273)
7. **Adversary for social good: Protecting familial privacy through joint adversarial attacks.** *Chetan Kumar, Riazat Ryan, and Ming Shao.*  AAAI conference on artificial intelligence 2020. [[paper]](https://ojs.aaai.org/index.php/AAAI/article/download/6791/6645)

### 3.3 Differentially Private Approaches
1. **Locally Private Graph Neural Networks.** *Sina Sajadmanesh and Daniel Gatica-Perez.* CCS 2021. [[paper]](https://arxiv.org/pdf/2006.05535.pdf)[[code]](https://github.com/sisaman/LPGNN)
2. **Releasing Graph Neural Networks with Differential Privacy Guarantees.** *Iyiola E. Olatunji, Thorben Funke, and Megha Khosla.* arXiv 2021. [[paper]](https://arxiv.org/pdf/2109.08907.pdf)
3. **Graph Embedding for Recommendation against Attribute Inference Attacks.** *Shijie Zhang, Hongzhi Yin, Tong Chen, Zi Huang, Lizhen Cui, Xiangliang Zhang.* WWW 2021. [[paper]](https://arxiv.org/pdf/2101.12549.pdf)
4. **“Differentially private graph neural networks for whole-graph classification.** *Tamara T. Mueller, Johannes C. Paetzold, Chinmay Prabhakar, Dmitrii Usynin, Daniel Rueckert, and Georgios Kaissis. * IEEE Transactions on Pattern Analysis and Machine Intelligence 2022. [[paper]](https://ieeexplore.ieee.org/iel7/34/4359286/09980390.pdf)[[code]](https://github.com/tamaramueller/DP-GNNs) 
5. **Gap: Differentially private graph neural networks with aggregation perturbation.** *Sina Sajadmanesh, Ali Shahin Shamsabadi, Aurélien Bellet, and Daniel Gatica-Perez.* arXiv preprint 2022. [[paper]](https://arxiv.org/pdf/2203.00949)[[code]](https://github.com/sisaman/GAP)
6. **Differentially private graph classification with gnns.** *Tamara T. Mueller, Johannes C. Paetzold, Chinmay Prabhakar, Dmitrii Usynin, Daniel Rueckert, and Georgios Kaissis.* arXiv preprint 2022. [[paper]](https://arxiv.org/pdf/2202.02575)
7. **Node-level differentially private graph neural networks.** *Ameya Daigavane, Gagan Madan, Aditya Sinha, Abhradeep Guha Thakurta, Gaurav Aggarwal, and Prateek Jain.* arXiv preprint 2021. [[paper]](https://arxiv.org/pdf/2111.15521)[[code]](https://github.com/google-research/google-research/tree/master/differentially_%20private_gnns)
8. **Towards private learning on decentralized graphs with local differential privacy.** *Wanyu Lin, Baochun Li, and Cong Wang* IEEE Transactions on Information Forensics and Security 2022. [[paper]](https://ieeexplore.ieee.org/iel7/10206/4358835/09855440.pdf)

### 3.4 Federated Learning Approaches
1. **Vertically Federated Graph Neural Network for Privacy-Preserving Node Classification.** *Jun Zhou, Chaochao Chen, Longfei Zheng, Huiwen Wu, Jia Wu, Xiaolin Zheng, Bingzhe Wu, Ziqi Liu, and Li Wang.* arXiv 2020. [[paper]](https://arxiv.org/pdf/2005.11903.pdf)
2. **FedGNN: Federated Graph Neural Network for Privacy-Preserving Recommendation.** *Chuhan Wu, Fangzhao Wu, Yang Cao , Yongfeng Huang, and Xing Xie.* arXiv 2021. [[paper]](https://arxiv.org/pdf/2102.04925.pdf)
3. **Fedgraphnn: A federated learning system and benchmark for graph neural networks.** *Chaoyang He, Keshav Balasubramanian, Emir Ceyani, Carl Yang, Han Xie, Lichao Sun, Lifang He.* arXiv preprint 2021. [[paper]](https://arxiv.org/pdf/2104.07145)[[code]](https://github.com/FedML-AI/FedML/tree/master/python/app/fedgraphnn)
4. **Fedgl: Federated graph learning framework with global self-supervision.** *Chuan Chen, Weibo Hu, Ziyue Xu, and Zibin Zheng.* arXiv preprint 2021. [[paper]](https://arxiv.org/pdf/2105.03170)
5. **Fedgcn: Federated learning-based graph convolutional networks for non-euclidean spatial data.** *Kai Hu, Jiasheng Wu, Yaogen Li, Meixia Lu, Liguo Weng, and Min Xia.* Mathematics 10.6 (2022): 1000. [[paper]](https://www.mdpi.com/2227-7390/10/6/1000/pdf)[[code]](https://github.com/yh-yao/FedGCN)
6. **Sgnn: A graph neural network based federated learning approach by hiding structure** *Guangxu Mei, Ziyu Guo, Shijun Liu, and Li Pan.*  2019 IEEE International Conference on Big Data (Big Data). [[paper]](https://ieeexplore.ieee.org/iel7/8986695/9005444/09005983.pdf?casa_token=mnd7xLktvaoAAAAA:6_ALgqxDV8TrHvkTzgIx_F4uX1x6LeRqugiAR5eEp8y6Ht_lAKUnHqXOauty3ZS_cbzRTatA)
7. **A vertical federated learning framework for graph convolutional network.** *Xiang Ni, Xiaolong Xu, Lingjuan Lyu, Changhua Meng, and Weiqiang Wang.* arXiv preprint 2021. [[paper]](https://arxiv.org/pdf/2106.11593)
8. **Decentralized federated graph neural networks.** *Yang Pei, Renxin Mao, Yang Liu, Chaoran Chen, Shifeng Xu, Feng Qiang, and Blue Elephant Tech.* International Workshop on Federated and Transfer Learning for Data Sparsity and Confidentiality in Conjunction with IJCAI 2021. [[paper]](https://federated-learning.org/fl-ijcai-2021/FTL-IJCAI21_paper_20.pdf)
9. **Spreadgnn: Serverless multi-task federated learning for graph neural networks.** *Chaoyang He, Emir Ceyani, Keshav Balasubramanian, Murali Annavaram, and Salman Avestimehr.* arXiv preprint 2021. [[paper]](https://arxiv.org/pdf/2106.02743)[[code]](https://github.com/FedML-AI/SpreadGNN) 
10. **A federated graph neural network framework for privacy-preserving personalization.** *Chuhan Wu, Fangzhao Wu, Lingjuan Lyu, Tao Qi, Yongfeng Huang, and Xing Xie.* Nature Communications 2022. [[paper]](https://www.nature.com/articles/s41467-022-30714-9)[[code]](https://github.com/wuch15/FedPerGNN)
11. **Federated learning of molecular properties with graph neural networks in a heterogeneous setting.** *Wei Zhu, Jiebo Luo, and Andrew D. White.* Patterns 2022. [[paper]](https://www.sciencedirect.com/science/article/pii/S2666389922001180)[[code]](https://github.com/ur-whitelab/fedchem)
12. **Grafehty: Graph neural network using federated learning for human activity recognition.** *Abhishek Sarkar, Tanmay Sen, and Ashis Kumar Roy.* ICMLA 2021. [[paper]](https://ieeexplore.ieee.org/iel7/9679834/9679948/09680185.pdf)

## 4. Datasets

The datasets that have been used or can be potentially used for privacy study with graphs are categorized into various domains, including social network, citation network, user-item, molecule, and protein. Their satistics are shown in the following table and the links to access each dataset are provided below.

<img width="571" alt="Screen Shot 2023-03-05 at 4 18 41 PM" src="https://user-images.githubusercontent.com/58016786/222989031-5fd7e56a-ef21-4a30-9a68-c9541f47eb7e.png">

**Social Network**: [Facebook](https://snap.stanford.edu/data/ego-Facebook.html), [Twitter](https://snap.stanford.edu/data/ego-Twitter.html), [LastFM](https://snap.stanford.edu/data/feather-lastfm-social.html), [Reddit](https://paperswithcode.com/dataset/reddit), [Computers](https://docs.dgl.ai/en/0.9.x/generated/dgl.data.AmazonCoBuyComputerDataset.html)

**Citation Network**: [Cora](https://paperswithcode.com/dataset/cora), [Citeseer](https://paperswithcode.com/dataset/citeseer), [PubMed](https://paperswithcode.com/dataset/pubmed), [DBLP](https://www.dropbox.com/s/yh4grpeks87ugr2/DBLP_processed.zip?dl=1), [ogbn-arxiv](https://ogb.stanford.edu/docs/nodeprop), [Aminer](https://www.aminer.org/data/)

**User-Item**: [Flixster](http://datasets.syr.edu/datasets/Flixster.html), [Douban](https://www.kaggle.com/datasets/utmhikari/doubanmovieshortcomments), [YahooMusic](https://webscope.sandbox.yahoo.com)

**Molecule**: [NCI1](https://paperswithcode.com/dataset/nci1), [AIDS](https://paperswithcode.com/dataset/aids), [OVCAR-8H](https://remap2022.univ-amu.fr/biotype_page/OVCAR-8:9606)

**Protein**: [PROTEINS](https://paperswithcode.com/dataset/proteins), [ENZYMES](https://paperswithcode.com/dataset/enzymes)



**License**

- [CC0 Universal](https://github.com/NDS-VU/awesome-gnn-privacy/blob/main/LICENSE)
