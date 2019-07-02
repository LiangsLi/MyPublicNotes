# 依存分析相关资料整理
## 快速入门
- **Natural Language Processing**（Jacob Eisenstein）第13章，
- **Speech and Language Processing 3E** (Daniel Jurafsky)第11章，
- **Deep Learning in Natural Language Processing** (邓力)第4章
## 基于转移的依存分析论文列表
- Nivre, Joakim. "An efficient algorithm for projective dependency parsing." Proceedings of the Eighth International Conference on Parsing Technologies. 2003.
  This paper presents a deterministic parsing algorithm for projective dependency grammar. The running time of the algorithm is linear in the length of the input string, and the dependency graph produced is guaranteed to be projective and acyclic. The algorithm has been experimentally evaluated in parsing unrestricted Swedish text, achieving an accuracy above 85% with a very simple grammar. 
- Nivre, Joakim. "Algorithms for deterministic incremental dependency parsing." Computational Linguistics 34.4 (2008): 513-553.
- Yue Zhang and Joakim Nivre. 2011. Transition-based dependency parsing with rich non-local features. In Proceedings of the 49th Annual Meeting of the Asso-ciation for Computational Linguistics: Human Lan-guage Technologies. Portland, Oregon, USA, pages 188–193.
- Choi, J. D., and McCallum, A. 2013. Transition-based de-pendency parsing with selectional branching. In Proc. of ACL, 1052–1062. 
- Danqi Chen and Christopher Manning. 2014. A fast and accurate dependency parser using neural net-works. In Proceedings of EMNLP-2014. Doha, Qatar, pages 740–750. 
- Dyer, Chris, et al. "Transition-Based Dependency Parsing with Stack Long Short-Term Memory." Proceedings of the 53rd Annual Meeting of the Association for Computational Linguistics and the 7th International Joint Conference on Natural Language Processing (Volume 1: Long Papers). Vol. 1. 2015.
- Cross, J., and Huang, L. 2016a. Incremental parsing with minimal features using bi-directional lstm. In Proc. of ACL, 32–37. 
- Andor, D.; Alberti, C.; Weiss, D.; Severyn, A.; Presta, A.; Ganchev, K.; Petrov, S.; and Collins, M. 2016. Globally nor-malized transition-based neural networks. InProc. of ACL, 2442–2452. 
- Kiperwasser, Eliyahu, and Yoav Goldberg. "Simple and Accurate Dependency Parsing Using Bidirectional LSTM Feature Representations." Transactions of the Association for Computational Linguistics 4.1 (2016): 313-327.
- Wang, Yuxuan, et al. "A neural transition-based approach for semantic dependency graph parsing." Thirty-Second AAAI Conference on Artificial Intelligence. 2018.
## 基于图算法的依存分析论文列表
- Kiperwasser, Eliyahu, and Yoav Goldberg. "Simple and Accurate Dependency Parsing Using Bidirectional LSTM Feature Representations." Transactions of the Association for Computational Linguistics 4.1 (2016): 313-327.
- Dozat, Timothy, and Christopher D. Manning. "Deep biaffine attention for neural dependency parsing." arXiv preprint arXiv:1611.01734 (2016).
- Dozat, Timothy, and Christopher D. Manning. "Simpler but more accurate semantic dependency parsing." arXiv preprint arXiv:1807.01396 (2018).
- Wang, Xinyu, Jingxian Huang, and Kewei Tu. "Second-Order Semantic Dependency Parsing with End-to-End Neural Networks." arXiv preprint arXiv:1906.07880 (2019).
## 中文语义依存图分析论文列表
- Ding, Y.; Shao, Y.; Che, W.; and Liu, T. 2014. Dependency graph based chinese semantic parsing. In Chinese Computa-tional Linguistics and Natural Language Processing Based on Naturally Annotated Big Data. Springer. 58–69. 
- Che, W.; Shao, Y.; Liu, T.; and Ding, Y. 2016. Semeval-2016 task 9: Chinese semantic dependency parsing. In Proc. of SemEval, 1074–1080. 
- Wang, Yuxuan, et al. “A neural transition-based approach for semantic dependency graph parsing.” Thirty-Second AAAI Conference on Artificial Intelligence. 2018.
- Dependency-Gated Cascade Biaffine Network for Chinese Semantic Dependency Graph Parsing
- Adversarial Domain Adaptation for Chinese Semantic Dependency Graph Parsing 
