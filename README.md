# 自然语言处理学习

本文尝试罗列学习自然语言处理（Natural Language Processing，NLP）的几大要点，包括：研究方向确定、数学基础、深度学习基础、编程基础、文献阅读和写作练习等。

> 注：该文不全面，仅个人观点，仅供学习组内部参考，可能会持续更新，若存在错误观点，望指出。

## 其他资源（建议优先且仔细阅读前两点）

- （重要）复旦大学邱锡鹏老师的 **自然语言处理入门练习** [NLP-Beginner：自然语言处理入门练习](https://github.com/FudanNLP/nlp-beginner/blob/master/README.md)

- （重要）清华大学刘知远老师的 **自然语言处理入门建议** [NLP研究入门之道](https://github.com/zibuyu/research_tao)

- 斯坦福大学开设的 **自然语言处理课程** [CS224n: Natural Language Processing with Deep Learning](http://web.stanford.edu/class/cs224n/)，内有课程 ppt 以及视频。
- 卡内基梅隆大学的 **自然语言处理课程** [Neural Networks for NLP](http://phontron.com/class/nn4nlp2020/schedule/class-introduction.html) ，在 Youtube 上有 [课程视频](https://www.youtube.com/watch?v=D7o2Z1tAuQc)

前面两点极具指导价值，甚至可以只看前两点而忽略本文。

## 研究方向的确定

NLP 领域包含不少研究方向，比如，文本生成、文本分类、序列标注、关系抽取、事件抽取和知识图谱等。因此，在从事具体研究前最好先确定自己的研究方向，可先广泛阅读各个方向的论文寻找自己感兴趣的方向，或是找到一个较为新颖且存在大量细节未被学界探索的方向。当然，最主要的可能还是看导师的安排。

## 数学基础

解决 NLP 领域的任务需要使用到机器学习和深度学习方法，所以对数学基础也具有一定要求。

- 线性代数基础
- 概率论基础
- 信息论基础
- ...

也不是要将上述数学基础打牢才开始研究 NLP，可先对 NLP 展开研究，等遇到具体的数学问题再认真学习了解，或者同步进行（不一定对）。

## 深度学习基础

现今 NLP 领域的研究热点与深度学习密不可分，打好这方面的基础没啥好说的，需要先具备一定的机器学习基础，在这推荐几本书籍与视频教程：

- Andrew Ng 在 Coursera的公开课 [机器学习](https://www.coursera.org/learn/machine-learning)

- 周志华老师的《机器学习》（西瓜书），此书有相应的较为详细的[公式推导解析](https://github.com/datawhalechina/pumpkin-book)
- Chris Bishop 所著的[《Machine Learning and Pattern Recognition》](http://users.isr.ist.utl.pt/~wurmd/Livros/school/Bishop - Pattern Recognition And Machine Learning - Springer  2006.pdf)
- 邱锡鹏老师的 [《神经网络与深度学习》](https://nndl.github.io/)
- Ian Goodfellow 和 Yoshua Bengio 所著的 [《Deep Learning》](https://www.deeplearningbook.org/)，也有对应的[中文版](https://github.com/exacity/deeplearningbook-chinese)

## 编程基础

<!--业内普遍任务自然语言处理研究难以落地，而且落地往往也需要大量工程方面的辅助。-->

编程基础极为重要，但研究 NLP 又不能只会编程，需要结合具体的 NLP 任务，所以提高编程基础可从两个方向同时进行：

- 基础编程：熟悉基础算法和编程技巧，可日常刷 [LeetCode](https://leetcode-cn.com/).
- NLP 任务：多参加网络上举行的 NLP 相关比赛，多尝试不同的 NLP 任务（文本分类、序列标注、关系抽取和事件抽取等），想了解 NLP 领域的知名比赛平台可参考这篇[总结](https://mp.weixin.qq.com/s/a4oNMCrHnjW6OOZyp6NJuQ
  )。

## 文献阅读

对于初学者，可先查阅国内的**中文**期刊文献或博士论文，以较快地了解领域内的基础概念和方法思想，等到对该领域有了初步了解后便可多多查阅**英文**顶会文章，从中可以了解当前的研究热点和最新技术。

看论文也要有所选择，一篇论文并不应该按顺序从头到尾看完，比如可以采用[这篇文章](https://web.stanford.edu/class/cs244/papers/HowtoReadPaper.pdf)里介绍的**三遍阅读法**。

## 写作练习

平常养成写作习惯，逐步提高自己的写作能力，为此，可**多写博客**（在 CSDN，简书或知乎等博客平台上均可），记录自己的学习过程，一方面通过写作加深自己对知识点的理解，另一方面可引发讨论及时纠正自己的错误理解。

## 其他

- 统一深度学习框架，目前为 Pytorch

