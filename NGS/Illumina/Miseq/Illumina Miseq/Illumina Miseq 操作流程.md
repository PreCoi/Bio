# Illumina Miseq 操作流程
## 一、测序准备
### 1、目的
&emsp;&emsp;Miseq测序仪的测序原理与Hiseq相同，也是采用SBS技术和3’端可逆屏蔽终结子技术。与高通量测序仪Hiseq不同的是，Miseq簇生成过程直接在Miseq测序仪上进行。Miseq测序芯片（flow cell）只有1个泳道（lane），根据数据产出和图像采集tile数不同，分为不同的类型，最多可产生约15Gb数据。
### 2、试剂
&emsp;&emsp;Miseq reagent kit；Illumina PhiX Control；Stock 1.0 mol/L NaOH；Tris-HCl 10mmol/L；pH 8.5含0.1% Tween 20。
### 3、设备
&emsp;&emsp;Illumina Miseq测序仪；台式离心机（Eppendorf5424）；涡旋振荡器（Genie 2）；加样器和枪头；250ml；50ml；15ml加样管。
### 4、上机文库的质量检验
&emsp;&emsp;仪器：实时荧光定量PCR仪，Agilent 2100 Bioanalyzer。

&emsp;&emsp;质检内容：检验文库浓度与插入片段的大小。

&emsp;&emsp;质检标准：文库终浓度应不小于2nmol/L，体积不小于10ul。文库插入DNA片段大小为预期大小，且没有接头盒引物二聚体。
## 二、准备测序文库模板
&emsp;&emsp;Illumina 测序文库模板的准备分两步进行：文库变性和变性文库的稀释。Illumina建议测序文库储存浓度为20 pmol/L或10 pmol/L，实验人员可根据实际需要进行选择。当测序文库储存浓度分别选择20 pmol/L和10 pmol/L时，对应的变性前文库的浓度分别为4 nmol/L和2 nmol/L。变性前文库浓度过高时，可用缓冲液（Tris-HCl 10 mmol/L，pH 8.5，含0.1% Tween 20）将其稀释至4 nmol/L或2 nmol/L。

&emsp;&emsp;缓冲液的制备方法：取500 ul 1 mol/L Tris-HCl（Ph 8.5，Emerald Biosystems，货号：EBS-1TRIS85-250，或同级产品），加入超纯水至总体积50 ml。然后加入50 ul 分子生物学级别的 Tween 20（VWR，货号BDH4210-500 ml，或同级产品），保存于4℃冰箱。
### 1、4 nmol/L 模板 DNA 文库的变性和稀释
&emsp;&emsp;配制0.2 mol/L NaOH：在1.5 ml 离心管中加入以下试剂，涡旋混匀。

| 成分 | 体积（ul） | 
|:-------------:| :-------------:|
| 超纯水 | 800 | 
| NaOH（0.1 mol/L） | 200 | 

&emsp;&emsp;注意：0.2 mol/L NaOH 需要现用现配，保存时间不超过12 h；配制精确浓度的NaOH非常关键，NaOH浓度偏高，会抑制文库片段与测序芯片的杂交，浓度偏低，会导致文库模板变性不完全。
#### （1）4 nmol/L模板DNA文库的变性

1）在1.5 ml 离心管中加入以下试剂，涡旋混匀。
