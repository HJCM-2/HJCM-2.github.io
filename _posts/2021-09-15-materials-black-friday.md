---
title:  黑色星期五销售复盘分析
tags:
  - Tableau
  - Reports
---

从销售数据中，了解客户针对不同类别的各种产品的购买行为。通过数据分析，指导决策。

<!--more-->

## 业务背景

零售公司“ ABC有限公司”希望通过Z平台的黑色星期五的销售数据了解客户针对不同类别的各种产品的购买行为（特别是购买金额）。他们分享了上个月精选的大批量产品的各种客户的购买摘要。Z平台的黑色星期五销售数据主要包含三座城市的消费者对不同商品的购买情况。 

对企业来说，进行销售复盘分析十分重要，能够通过数据分析指导决策。

<br/>

## 数据来源

由XXXXX提供数据。

<br/>

## 数据清洗

查看该数据，分析规范范围内的数据。无空值，错误值。

<br/>

## 分析框架

通过分析历史的销售购买情况，了解客户的购买行为以及产品的售卖情况，为企业的销售提供决策帮助。

明确数据分析报告价值：

1. 通过分析历史的销售购买情况，帮助企业了解客户。（主要从性别，年龄，婚姻状况三个方面来分析）

2. 帮助企业了解产品售卖情况，了解产品在不同消费者群体中的受欢迎情况。

3. 通过对区域的分析，了解不同城市的用户分布及消费情况。为未来活动做准备。

   <br/>

## 分析过程

### 消费者分析

* **男性和女性的消费金额和消费结构是什么？**
  
  <img src="https://hj-1304143905.cos.ap-shanghai.myqcloud.com/blackfriday/01.png" alt="Tableau" style="zoom:55%;" />
  
  从数据中可以看到，男性是主要的消费群体。1，5，8是消费者重点消费的产品类别。
  
* **消费者不同年龄段消费是什么情况？**
  
  <img src="https://hj-1304143905.cos.ap-shanghai.myqcloud.com/blackfriday/02.png" alt="Tableau" style="zoom:60%;" />
  
  我们可以看到消费群体主要为18-36岁，其中26-35岁的年轻人是最核心的消费人群。
  
* **已婚和未婚的消费者消费情况是什么？**

  <img src="https://hj-1304143905.cos.ap-shanghai.myqcloud.com/blackfriday/03.png" alt="Tableau" style="zoom:18%;" />

  从分析中可以看出，约60%的消费者都是未婚。经过进一步分析，18-45岁的未婚消费者更多，与主要的消费者的年龄有一定关系。

  <br/>

### 商品分析

* **哪些商品和类别在黑色星期五的期间销量额最高？**
  
  <img src="https://hj-1304143905.cos.ap-shanghai.myqcloud.com/blackfriday/04.png" alt="Tableau" style="zoom:25%;" />
  
  从数据中可以看到，类别1的商品在黑色星期五的期间销量额最高。具体高销售额的商品如图所示。
  
* **消费者销量额前十的商品是什么？**
  
  <img src="https://hj-1304143905.cos.ap-shanghai.myqcloud.com/blackfriday/05.png" alt="Tableau" style="zoom:40%;" />
  
  <img src="https://hj-1304143905.cos.ap-shanghai.myqcloud.com/blackfriday/06.png" alt="Tableau" style="zoom:40%;" />
  
  <img src="https://hj-1304143905.cos.ap-shanghai.myqcloud.com/blackfriday/07.png" alt="Tableau" style="zoom:40%;" />
  
  通过对消费额进行分析，得出在最受消费者欢迎的前五名产品中，第1、2、4名分别是男性最喜爱的产品前三名；第3，5名分别是女性最喜爱的前两名。男性消费者的喜好更能影响到商品的受欢迎程度。
  
* **不同年龄段消费者中哪些商品类别比较受欢迎？**
  
  <img src="https://hj-1304143905.cos.ap-shanghai.myqcloud.com/blackfriday/08.png" alt="Tableau" style="zoom:50%;" />
  
  从分析中可以看出，1、5、8类型的产品在18-35岁消费者群体中销售额是最高的，这些类型的消费次数也相对较高。2，6类型的产品在主流年龄段的消费群体中销售次数高，但销售额并不乐观，可能与单价或折扣相关，有待进一步分析。
  
* **产品优化分析？**

  <img src="https://hj-1304143905.cos.ap-shanghai.myqcloud.com/blackfriday/09.png" alt="Tableau" style="zoom:40%;" />

  从中可以看出，可以稍微再强化一下头部产品。


* **已婚和未婚消费者中哪些商品比较受欢迎？**

  <img src="https://hj-1304143905.cos.ap-shanghai.myqcloud.com/blackfriday/10.png" alt="Tableau" style="zoom:30%;" />

  通过分析得出，从消费次数上看，P00112142与P00110742产品在已婚与未婚人士中均受欢迎；而从消费额上看，主要贡献消费额的是未婚人士。

  <br/>

### 区域分析

* **城市的用户分布的什么情况？**

  <img src="https://hj-1304143905.cos.ap-shanghai.myqcloud.com/blackfriday/11.png" alt="Tableau" style="zoom:35%;" />

  C城市的用户数最多，A城市的用户数最少。用户在A、B、C城市居住年限分布相似，居住1年的消费者最多，居住不满1年和4年以上的消费者较少。


* **城市消费金额、消费贡献、人均消费金额、用户平均购物频率是多少？**

  <img src="https://hj-1304143905.cos.ap-shanghai.myqcloud.com/blackfriday/12.png" alt="Tableau" style="zoom:35%;" />

  从分析来看，A城市人均消费金额和用户平均购物频率都最高，但消费金额最小。B城市消费金额最高，达到41.52%。C城市在人均消费金额和用户平均购物频率都少的情况下，消费金额比A城市高。这说明，城市用户数量对城市消费金额影响巨大。

* **哪些城市可以作为做活动的潜力城市？**
  
  <img src="https://hj-1304143905.cos.ap-shanghai.myqcloud.com/blackfriday/13.png" alt="Tableau" style="zoom:65%;" />
  
  考虑职位对消费者购买力的影响，从消费金额、人均消费金额、用户平均购物频率三个方面分析。
  
  可以看出，人均消费金额在各职位中没有太大差异。不同职业的用户平均购物频率对销售额影响不大。不同职业的人数对销售额影响较大：0、1、4、7、17职业的人数多，销售额也较大。
  
  <img src="https://hj-1304143905.cos.ap-shanghai.myqcloud.com/blackfriday/14.png" alt="Tableau" style="zoom:65%;" />
  
  因此，可以考虑用户多的C城市做活动，进一步增加收益；或是用户少的A城市做利于用户增长的活动。
  
  <br/>

## 分析结论

1. 消费者为年轻群体，主要是未婚人士和男性。

2. 类别1的产品更受消费者喜爱，可以重点关注头部产品。

3. 城市用户数量对销售额影响巨大。

   <br/>

## 提出建议

1. 对于A城市需要增加新客户数量，对C城市需要提高人均消费金额和购买频率，刺激消费

2. 需要重点关注带来主要销售额的1类产品。

   <br/>

   <br/>

   <br/>

   <br/>

