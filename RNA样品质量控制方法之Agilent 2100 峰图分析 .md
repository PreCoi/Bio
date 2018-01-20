# RNA样品质量控制方法之Agilent 2100 峰图分析
![1](http://mmbiz.qpic.cn/mmbiz_png/d4n6H8VhWUMt67WnllQh8CzfAdlTaFwcLgGgpg9I50G8KwjXRkLm9eFmoWFGJxSvNzwdB4epGUlicjz0aX1rB7g/640?wx_fmt=png&wxfrom=5&wx_lazy=1)
- RNA样品进入实验室后，实验技术员会进行一系列的质检实验。其中Agilent 2100 Bioanalyzer 检测是非常重要的一个环节，会直接给出一份PDF格式的检测报告（如上图所示），报告上会有每一个样品的电子模拟图，并且包含三个重要参考参数：RIN值、基线、5S区，下面针对这三个参数，进一步讲解如何判定RNA样品的质量：
## 1）RIN值
- RIN (RNA Integrity Number)，即RNA完整性指标，一般为十分制。如果你的样品RIN为8分以上，基本的转录组分析是完全没有问题的；如果RIN为7分一下，表示样品的质量不满足后续实验要求，需要重新收集总RNA样品。上图所示的例子，出自于我们技术人员的实验结果。大家可以看到完美质量RNA的RIN值是可以达到满分10分的。大大👍
## 2）基线
- 基线，即信号峰起始位置，FU值（Fluorescent Unit，即荧光单元，也可以称为荧光值）为零。较好RNA样品基线是平整没有起伏的，如果基线位置出现抬高或起峰，均表示大片段RNA出现了降解，根据不同基线不平整，可以评估样品为严重降解或轻微降解。
## 3）5S
- 5S，即5S rRNA分子，是核糖体RNA大亚基的一部分，一般情况下5S rRNA峰型较矮宽。如果检测过程中，出现了5S峰型较高，可以考虑两种情况：
### a）样品降解，5S峰处聚集降解后的小片段RNA分子，造成峰型变高；
### b）样品本身5S较高，对样品评估造成影响，一般判定为风险样品；
- 以上三点是对峰图进行分析的重要参考点。而对总RNA样品总体评估，还需要结合Qubit定量分析和琼脂糖凝胶电泳质量分析。所以判断总RNA样品是否合格，是需要多个实验结果综合评估的。
小编为大家展示三张不同质量状态的Agilent 2100峰型图：

![](http://mmbiz.qpic.cn/mmbiz_png/d4n6H8VhWUMt67WnllQh8CzfAdlTaFwcEvpPqoU8giaROaNicBSGjxK67CsGW2wQTew6LDcUoRHroxKoJuvoKRZQ/640?wx_fmt=png&wxfrom=5&wx_lazy=1)

```合格样品```

![](http://mmbiz.qpic.cn/mmbiz_png/d4n6H8VhWUMt67WnllQh8CzfAdlTaFwcic3emQfGT4XufkMeodpQiaeFxbZ8krnJ68Tn66LZlywxBVmvk2l4tyibQ/640?wx_fmt=png&wxfrom=5&wx_lazy=1)

```降解样品```

![](http://mmbiz.qpic.cn/mmbiz_png/d4n6H8VhWUMt67WnllQh8CzfAdlTaFwc2L3R34Kw6frmBdhboibPZUPQiaxpicC5DtHEZwFkT3rjFeT7kAtTNvMPw/640?wx_fmt=png&wxfrom=5&wx_lazy=1)

```严重降解样品```

【选自公众号：allfrombionova】（一呼百诺）

