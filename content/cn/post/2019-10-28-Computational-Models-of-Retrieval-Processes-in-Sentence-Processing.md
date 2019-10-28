---
title: "句子加工中的提取过程"
author: "战立侃"
date: '2019-10-28'
show_toc: true
---

- 基本现象

句子理解过程中要解决的重要问题是 ''谁对谁干了什么''，其中不同句子成分之间的长距离约束关系（Long-Distance Dependencies）非常重要。例如要理解句子(1a)，读者需要解决动词短语 ''was complaining'' 和动物性名词短语 ''the resident'' 的关系。

语言学理论和相关记忆研究认为，单词和短语在记忆中的存储方式是通过一系列特征-特征值束（feature-value bundles）实现的。例如，''the resident''的特征值束为：+ 名词，+主语，+单数，+动物。相关约束理解理论（dependency completion）假定动词短语将触发一个搜索过程，在记忆系统中搜索具有相关特征的名词。例如，动词将触发一个包含下述特征的名词的搜索过程： +名词，+主语，+单数，+动物。这些被用于搜索的特征束通常被称作提取线索（retrieval cues）。

前人研究发现，如果搜索过程包含多个提取线索，当记忆中多个名词都与提取线索相契合时，就会出现加工上的困难，即提取干扰效应（retrieval interference），有时又被称作抑制性干扰效应（inhibitory interference）。

如何解释这一现象呢？目前有两个常见理论：激活模型（Activation Model）和直接获取模型（Direct-Access Model）。

- 激活模型（Activation Model）

三个基本假设：假设1：记忆系统中，项目的激活水平会随时间消逝而成指数水平降低；假设2：记忆系统中，激活水平最高的项目将被提取，而且项目的激活水平越高提取速度越快，提取越准确；假设3：激活水平还有一个高斯噪音成分，该噪音成分将影响每个试验项目的提取水平。

除了上述一般化假设，抑制性干扰还依赖于基于线索的提取过程（cue-based retrieval）的工作机制。记忆系统中，特征与所有提取线索均匹配的该项目将被激活。但如果记忆系统中另有一项目，其特征与一部分提取线索匹配，则无论是完全匹配项目还是部分匹配项目，其激活水平都会产生衰减。这被称作线索过载（cue overload）：一个提取线索指向两个项目，使得不同项目难以区分。这将导致（1a）的阅读时间比（1b）长（图1上半部分）。

赛跑过程（race process）：记忆系统中，一个过程是试图通达一个项目，而另外一个过程则是试图通达另外一个过程；这两个过程在时间上是同时展开的。首先结束的过程将导致相应项目被提取，搜索过程中止（图2）。这叫做平行-自我结束的搜索过程（parallel self-terminating search）。激活模型认为，如果项目一匹配了一部分提取线索，而项目二匹配了另一部分不同的提取线索，那么提取时间将会变快，如例2和图1下半部分。

- 直接获取模型（Direct-Access Model）

模型假定，记忆搜寻过程直接通达的是记忆系统中与提取线索相匹配的项目。完成一个提取过程所需要的时间是固定的，不管这个项目之前有没有接触过。这种搜索过程被称作内容上可通达的基于线索的搜索过程（content-addressable cue-based search）。

具体到例1，线索过载会导致在大部分试次中，''resident'' 会被提取；但在其中一部分试次中，错误名词 ''neighbor'' 也会被提取。无论哪种情况，提取过程所需要的时间是一样的，都是 $\beta$ 。但是当提取错误发生时，系统会进行第二次提取尝试，即在分析过程（reanalysis），该过程将会产生额外的加工时间， $\delta$ （图3）。最终会导致提取干扰现象的产生。

激活模型和直接获取模型对抑制性干扰效应预测相同；但对被试错误反应的反应时间则产生了不同的预测：激活模型认为在抑制性干扰实验设计中，对错误组块的提取时间应该长于对正确组块的提取时间。但是研究发现，对错误组块的提取时间实际上短于对正确组块的提取时间（图I），从而支持直接提取模型。

- 应用前景

上述计算机化的提取模型可被用来研究语言障碍，如失语症（aphasia）（图4）、个体差异（图5）等。

- 原始文献

Vasishth, S., Nicenboim, B., Engelmann, F., & Burchert, F. (2019). Computational Models of Retrieval Processes in Sentence Processing. *Trends in Cognitive Sciences*. doi:10.1016/j.tics.2019.09.003