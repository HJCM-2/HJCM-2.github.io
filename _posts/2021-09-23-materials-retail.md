---
title:  零售公司毛利率数据异常追踪分析
tags:
  - Tableau
  - Reports

---

从理解业务开始，分析需求、建立指标、分析数据，建立可视化图表，最后定位数据异常。

<br/>

<!--more-->

## 业务背景

零售电商企业的业务人员得出公司的毛利率最近出现了严重下滑，但是找不到原因所在。根据系统日志相关的资料，解读数据波动、快速定位数据异常原因，帮助企业找到经营问题。

<br/>

## 数据来源

由 XXXXXX 提供数据。

<br/>

## 分析框架

<img src="https://hj-1304143905.cos.ap-shanghai.myqcloud.com/retails/01.png" alt="Tableau" style="zoom:45%;" />

## 分析过程

### 确认问题

* **是否存在下跌？**

  <img src="https://hj-1304143905.cos.ap-shanghai.myqcloud.com/retails/02.png" alt="Tableau" style="zoom:52%;" />

  分析各项指标随时间的变化趋势，可以看出，8月份在销售额，数量均上升的情况下，毛利和毛利率均下降，其主要原因为成本上升。

* **是否存在周期性？**

  <img src="https://hj-1304143905.cos.ap-shanghai.myqcloud.com/retails/03.png" alt="Tableau" style="zoom:38%;" />

  将6-8月的情况展开分析，发现并不具有周期性，且在8月17日各指标有强烈波动。

  <br/>

### 维度细分

* **各省份各城市的毛利率有什么特点？**

  <img src="https://hj-1304143905.cos.ap-shanghai.myqcloud.com/retails/04.png" alt="Tableau" style="zoom:40%;" />

  观察不同城市6-8月份毛利率情况，发现只有湖南省长沙市在8月份突然出现毛利率为负的情况。（最好去掉标签）

  <img src="https://hj-1304143905.cos.ap-shanghai.myqcloud.com/retails/05.png" alt="Tableau" style="zoom:40%;" />

  进一步分析得到，也是由于成本在8月17日突然上涨，导致毛利率大跌。

* **各商品类别的毛利率有什么特点？**

  <img src="https://hj-1304143905.cos.ap-shanghai.myqcloud.com/retails/06.png" alt="Tableau" style="zoom:40%;" />

  有图可得，零食、日用品、生鲜均有下降，且零食在8月突然剧烈下降。


* **部分商品的毛利率有什么特点？**

  <img src="https://hj-1304143905.cos.ap-shanghai.myqcloud.com/retails/07.png" alt="Tableau" style="zoom:40%;" />

  具体分析零食、日用品、生鲜类产品，查看商品名称可以得出，德芙巧克力在8月17日毛利润骤降。

  <img src="https://hj-1304143905.cos.ap-shanghai.myqcloud.com/retails/08.png" alt="Tableau" style="zoom:30%;" />

  对指标进行拆解，发现毛利率下降的原因是成本突然上升。

  <img src="https://hj-1304143905.cos.ap-shanghai.myqcloud.com/retails/09.png" alt="Tableau" style="zoom:40%;" />

  对地区进行匹配，发现只有湖南长沙市在当天有销售记录。与从地区分析得到的数据有相似性。

  <br/>

### 原因分析

* **是否有与时间相匹配的系统日志相关的资料？**

  <img src="https://hj-1304143905.cos.ap-shanghai.myqcloud.com/retails/10.png" alt="Tableau" style="zoom:33%;" />

  从系统日志可以查到，在8月17日系统升级3.0版本。

## 分析结果

虽然2018年8月17日是七夕节，考虑到成本一般不会波动过大，且成本在第二天恢复正常，初步确定是版本更新问题，导致湖南长沙德芙巧克力数据出现异常。

<br/>

## 提出建议

1. 在版本升级后需要及时关注是否出现了数据异常的状况。如果出现，需要及时排除异常数据，以免影响决策。

<br/><br/><br/><br/>
