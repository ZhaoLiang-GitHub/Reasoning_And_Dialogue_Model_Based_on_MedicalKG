
# 项目介绍

本项目记录了有关***基于医疗知识图谱的自动问答系统***的相关情况。如果有做相关内容的同学可以邮件和我联系(zhaoliang19960421@outlook.com)

该项目的相关数据和代码由以下几部分拼接组成：

1. 本人在实习工作期间参与的基于知识图谱的医疗安全问答模型和基于知识图谱的开放领域对话模型；
2. 本人的硕士毕业论文《基于知识图谱的医疗资源推荐算法》；
3. [刘焕勇老师](https://github.com/liuhuanyong/QASystemOnMedicalKG)的基于知识图谱的问答模型;
4. 在网络上很多优秀的博客论文和公开知识图谱数据。

在此向借鉴学习的各位老师表示感谢！

本项目数据是由各部分的数据整合而来，其中部分数据来自于网络，如有侵权行为，请联系我删除。本项目的代码均由我二次开发修改而来，和所有的原始来源无关。


本项目将包括以下内容：
1. 爬虫爬取公开网站上的医疗数据，包括结构化数据和非结构化数据
2. 基于NER和NE算法实现从非结构数据中抽取出关键词作为实体，抽取实体之间关系作为图谱上的关系
3. 构建医药知识图谱
4. 基于图表征学习的实体消歧和图谱补全
5. 基于知识图谱的疾病病程推理
6. 基于医药知识图谱的自动问答
