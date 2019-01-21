This open-source project, referred to as **PTL2R** (Learning to Rank in PyTorch) aims to provide scalable and extendable implementations of typical learning-to-rank methods based on PyTorch. On one hand, this project enables a uniform comparison over several benchmark datasets leading to an in-depth understanding of previous learning-to-rank methods. On the other hand, this project makes it easy to develop and incorporate newly proposed models, so as to expand the territory of techniques on learning-to-rank. 

# Test Setting

PyTorch (1.0)

Python (3.6)

# Installation
This project is under construction, and is not formally released yet.

# Data
**[MQ2007](http://research.microsoft.com/en-us/um/beijing/projects/letor/LETOR4.0/Data/MQ2007.rar)**

**[MQ2008](http://research.microsoft.com/en-us/um/beijing/projects/letor/LETOR4.0/Data/MQ2008.rar)**

**[MSLR-WEB10K](https://www.microsoft.com/en-us/research/project/mslr/)**

**[MSLR-WEB30K](https://www.microsoft.com/en-us/research/project/mslr/)**


# Reference
[1] RankNet: Chris Burges, Tal Shaked, Erin Renshaw, Ari Lazier, Matt Deeds, Nicole Hamilton, and Greg Hullender. 2005. Learning to rank using gradient descent. In Proceedings of the 22nd ICML. 89–96.

[2] LambdaRank: Christopher J.C. Burges, Robert Ragno, and Quoc Viet Le. 2006. Learning to Rank with Nonsmooth Cost Functions. In Proceedings of NIPS conference. 193–200.

[3] ListNet: Zhe Cao, Tao Qin, Tie-Yan Liu, Ming-Feng Tsai, and Hang Li. 2007. Learning to Rank: From Pairwise Approach to Listwise Approach. In Proceedings of the 24th ICML. 129–136.

[4] ListMLE: Fen Xia, Tie-Yan Liu, Jue Wang, Wensheng Zhang, and Hang Li. 2008. Listwise Approach to Learning to Rank: Theory and Algorithm. In Proceedings of the 25th ICML. 1192–1199.

[5] RankCosine: Tao Qin, Xu-Dong Zhang, Ming-Feng Tsai, De-Sheng Wang, Tie-Yan Liu, and Hang Li. 2008. Query-level loss functions for information retrieval. Information Processing and Management 44, 2 (2008), 838–855.

[6] AppoxNDCG: Tao Qin, Tie-Yan Liu, and Hang Li. 2010. A general approximation framework for direct optimization of information retrieval measures. Journal of Information Retrieval 13, 4 (2010), 375–397.

[7] WassRank: Hai-Tao Yu, Adam Jatowt, Hideo Joho, Joemon Jose, Xiao Yang and Long Chen. WassRank: Listwise Document Ranking Using Optimal Transport Theory. Proceedings of the 12th International Conference on Web Search and Data Mining (WSDM), 2019.

# Community

**Slack**: [PTL2R group](https://ptl2r.slack.com)

**WeChat**:

![PTL2R](./img/wechat.png)

# Acknowledgements
This research is partially supported by JSPS KAKENHI Grant Number JP17K12784.

# Call for Contribution and/or Collaboration
Anyone who are interested in the following kinds of contributions and/or collaborations are warmly welcomed.

**Contribution**: Adding one or more implementations of learning-to-rank models based on the current code base.

**Collaboration**: Joint efforts in developping novel learning-to-rank models.

# Relevant Resources

| Name | Language | Deep Learning |
|---|---|---|
| [PTL2R](https://ptl2r.github.io/) | Python  |  [PyTorch](https://pytorch.org) | 
| [TF-Ranking](https://github.com/tensorflow/ranking)  |  Python | [TensorFlow](https://tensorflow.org) |
| [Shoelace](https://github.com/rjagerman/shoelace)  |  Python | [Chainer](https://chainer.org) |
| [LEROT](https://bitbucket.org/ilps/lerot) | Python  | x  |
| [Rank Lib](http://www.lemurproject.org/ranklib.php) |  Java | x  |
| [Propensity SVM^Rank](http://www.cs.cornell.edu/people/tj/svm_light/svm_proprank.html)  |  C | x  |
| [QuickRank](http://quickrank.isti.cnr.it)  |  C++ | x  |
