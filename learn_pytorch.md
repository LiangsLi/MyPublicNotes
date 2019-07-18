# pyTorch 学习资源
## 教程
1. 官方教程
2. zergtant/pytorch-handbook: https://github.com/zergtant/pytorch-handbook
3. 等等
## 框架
强烈建议使用以下几个框架简化同时规范化NLP处理流程：
### TorchText：Data loaders and abstractions for text and NLP
torchtext是一个较为低级的框架，其不负责处理模型和训练部分，只抽象化数据加载部分，简化NLP任务的数据加载流程。

一般，NLP任务中的数据加载部分都是绝对的dirty work（多做几个任务就会发现数据加载可能是最令人烦心的工作），torchtext旨在简化同时规范化这一过程

官方文档：https://torchtext.readthedocs.io/en/latest/index.html

github地址：https://github.com/pytorch/text

教程 1：http://mlexplained.com/2018/02/08/a-comprehensive-tutorial-to-torchtext/

教程 2：http://anie.me/On-Torchtext/
### Allennlp

教程 1：[An In-Depth Tutorial to AllenNLP (From Basics to ELMo and BERT)](https://mlexplained.com/2019/01/30/an-in-depth-tutorial-to-allennlp-from-basics-to-elmo-and-bert/)

### PyText

### FairSeq
## FAQ