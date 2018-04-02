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

建议：（1）上机前一天，取出Box 1于4℃冷藏箱过夜融化；实验前1h，取出Box 2中的试剂整管放入室温水浴中融化。（2）实验前，将试剂盒信息记录在“cluster generation on the cBot”表格上备案留底。
## 2、准备测序模板
Illumina 推荐的测序文库储存浓度为2 nmol/L。当文库浓度高于2 nmol/L时，可用缓冲液（Tris-HCl 10 mmol/L，pH 8.5，含0.1% Tween 20）将其稀释至2 nmol/L。
缓冲液的制备方法：取500 ul 1 mol/L Tris-HCl（Ph 8.5，Emerald BioSystems，货号：EBS-1TRIS85-250，或同级产品），加入超纯水至总体积50 ml。然后加入50 ul 分子生物学级别的Tween 20（VWR，货号：BDH4210-500 ml，或同级产品），保存于4℃冰箱。
选择合适的文库上机浓度：选择合适的文库上机浓度非常重要！浓度过低，会导致仪器测序能力的浪费，直接造成经济损失；而浓度过高，又会使簇密度过大，超过测序仪的分辨率，从而降低测序数据的质量甚至导致测序失败。一般来说，选择上机文库模板浓度为7～8 pmol/L时可以使芯片上的簇密度达到750～850K/mm2。在这个密度条件下，可以使测序数据产出和数据质量都达到较为理想的状态。

值得注意的是：对于不同类型甚至同一类型的不同单机，即使操作人员选择相同的上机浓度，其成簇密度也可能存在差异。所以，操作人员应通过自己的上机实践经验来修正某一台特定仪器的上机浓度，而不宜照搬其他同型测序仪的上机浓度数值。
