# 二、cBot 仪器操作过程
## 1、试剂盒
&emsp;&emsp;Illumina TruSeq PE Cluster Generation Kit V3（或V4）-HS（货号：PE-401-3001或PE-401-4001），包含以下成分。
- Box 1，PE cluster kit reagents（-20℃）：

One 96-well cBot single-read cluster generation reagent plate

HT1（Hybridization Buffer）

- Box 2，multiplexing reagents（-20℃保存）：

HP3（2 mol/L NaOH for denaturing DNA）

HT2（Wash Buffer）

HP8（Index Sequencing Primer）

- 其他组分：

Hiseq V3（或V4）PE flow cell（in orange lid 50 ml tube）（4℃保存）

cBot Manifold for Hiseq 室温保存

Hiseq Accessory Kit 室温保存

&emsp;&emsp;建议：（1）上机前一天，取出Box 1于4℃冷藏箱过夜融化；实验前1h，取出Box 2中的试剂整管放入室温水浴中融化。（2）实验前，将试剂盒信息记录在“cluster generation on the cBot”表格上备案留底。
## 2、准备测序模板
&emsp;&emsp;Illumina 推荐的测序文库储存浓度为2 nmol/L。当文库浓度高于2 nmol/L时，可用缓冲液（Tris-HCl 10 mmol/L，pH 8.5，含0.1% Tween 20）将其稀释至2 nmol/L。

&emsp;&emsp;缓冲液的制备方法：取500 ul 1 mol/L Tris-HCl（Ph 8.5，Emerald BioSystems，货号：EBS-1TRIS85-250，或同级产品），加入超纯水至总体积50 ml。然后加入50 ul 分子生物学级别的Tween 20（VWR，货号：BDH4210-500 ml，或同级产品），保存于4℃冰箱。

&emsp;&emsp;选择合适的文库上机浓度：选择合适的文库上机浓度非常重要！浓度过低，会导致仪器测序能力的浪费，直接造成经济损失；而浓度过高，又会使簇密度过大，超过测序仪的分辨率，从而降低测序数据的质量甚至导致测序失败。一般来说，选择上机文库模板浓度为7～8 pmol/L时可以使芯片上的簇密度达到750～850K/mm2。在这个密度条件下，可以使测序数据产出和数据质量都达到较为理想的状态。

&emsp;&emsp;值得注意的是：对于不同类型甚至同一类型的不同单机，即使操作人员选择相同的上机浓度，其成簇密度也可能存在差异。所以，操作人员应通过自己的上机实践经验来修正某一台特定仪器的上机浓度，而不宜照搬其他同型测序仪的上机浓度数值。



Truseq V3 试剂推荐的成簇密度为750～850 K/mm2，在使用 Truseq V4 试剂时，应适当增加上机浓度，其簇密度可以达到850～950 K/mm2。根据作者的经验，如果样品为碱基平衡性较好的DNA重测序或RNA转录组测序样品，其簇密度可以增加到1000 K/mm2，V4 最高可达到1300～1400 K/mm2。在上述簇密度水平下，不仅能够得到较高的数据产出，而且也可以保证较高的数据质量。对于 ChIP 测序，甲基化测序或扩增子测序的样品，不宜追求过高的成簇密度，选用系统推荐的750～850 K/mm2成簇密度即可。

测序模板的准备分以下两步：（1）文库变性；（2）将变性后的文库稀释至上机所需浓度。具体操作步骤如下。
（1）文库变性
1）在200 ul 的PCR 管中混合以下成分，涡旋混匀。
成分	体积（ul）
文库DNA（2 nmol/L）	10
NaOH（0.1 mol/L）	10

注意：0.1 mol/L NaOH 需新鲜配制，并用pH 试纸检测pH 值在13～14。
2）用小型台式离心机以280g 离心1 min。
3）室温静置5 min，使文库解离为单链。
4）转移20 ul 变性模板至980 ul 预先冷处理的HT1 缓冲液中（Hybridization Buffer，在试剂盒Box 1中）。
5）将变性后的模板（20 pmol/L）置于冰上，待用。
（2）稀释变性后的文库
1）将装有HT1缓冲液的离心管置于室温水浴中融化。
2）按照下表选择合适的浓度稀释模板。
模板终浓度（pmol/L）	6	7	7.5	8	10	12	13
20 pmol/L变性模板体积（ul）	300	350	375	400	500	600	650
HT1 缓冲液体积（ul）	700	650	625	600	500	400	350

3）颠倒离心管数次混匀溶液，短暂离心。
4）将稀释好的模板置于冰上待用。
3、测序模板中加入标准样品PhiX
Illumina 选用 PhiX 病毒的基因组作为测序结果的阳性对照。PhiX 病毒具有















