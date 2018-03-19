# Q-PCR
Real-time PCR实验步骤：（实验时用低吸附性枪头）

1、实验准备：

试剂（SYBR Green 1试剂盒）

引物（专用引物）

PCR管（专用耗材，0.1ml离心管，96孔板，8联管，单个小管，平盖光学透明）

2、样品稀释：

Phix control先稀释10倍（1ul Phix+9ul水）

稀释梯度：

1 5ul稀释后Phix+45ul水；

2 5ul 1号Sample +45ul水；

3 5ul 2号Sample +45ul水；

4 5ul 3号Sample +45ul水；

5 5ul 4号Sample +45ul水；

6 CK（空白对照，只加水）50ul；

需PCR定量的文库均稀释100倍，每个样品需3个重复。

3、实验

（1）配相应的Mix：

SYBR Green mix   10ul

F-Primer        0.5ul

R-Primer        0.5ul

                 11ul

11ul Mix +9ul 稀释样品

（2）混匀，避光，确保样品均匀，且注意盖子密封性；

（3）放入PCR仪中，程序为：

95℃ 3min；

**95℃ 3s（15s）**

**60℃ ≥20s（30s）**  40cycles/35

**72℃ 20s**

72℃ 1omin

4℃  ∞


================================================================================
## 1.3.4、实时荧光定量PCR反应体系和条件
&emsp;&emsp;将构建的标准质粒DNA 10倍梯度稀释：10^{6}、10^{5}、10^4、10^3、10^2和10 copies/uL，用于构建实时荧光定量PCR标准曲线。实时荧光定量PCR反应体系为25uL，包含12.5uL 2XTaqMan® Gene Expression Master Mix，10umol/L正向引物和反向引物各1uL，10umol/L探针0.5uL。

&emsp;&emsp;实时荧光定量PCR使用两步扩增法，程序如下：94℃，10min预变性；94℃变性15s，60℃退火60s，共45个循环，在退火步骤中采集荧光信号。每个模板重复3个平行扩增，重复3轮实验。扩增结束后使用SDS 2.4软件分析实验数据，获得实时荧光定量PCR结果。

## 2.1.2、实时荧光定量PCR反应的重演性检测
&emsp;&emsp;为确定实时荧光定量PCR的准确性和可重复性，重复进行3轮扩增，每轮3次平行扩增，对Ct值进行重演性分析。相对标准偏差（relative standard deviation，RSD）是判断定量准确性和重演性的重要指标，欧盟规定在qRT-PCR定量检测中RSD≤25%（ENGL,2008）。本实验中各基因的重演性分析数据见表3，SD值处于0.01～0.10之间，RSD介于0.03%～0.33%之间，远小于25%，在欧盟规定的接受阈内，说明实验建立的qRT-PCR扩增方法具有良好的稳定性和可重复性。

维普资讯中文期刊服务平台- 利用微滴数字PCR分析转基因生物外源基因拷贝数
http://61.178.127.9:8080/rewriter/WEIPU/http/0Z9Z9Z9040.74/article/detail.aspx?id=662816398

http://www.jabiotech.org


===============================================================================================
## 5.1 文库的浓度检测

|  |
| ------------- |
| Library Dillution Buffer
| Vazyme Code：NQ106 50ml
| L/N 7E142D7 Exp：2018.11.24
| Store at -20℃

|  |
| ------------- | 
| Illumine Phix v3
| REF：15017666 LOT：20175333
| 2018.05.20
| Label PN：15017667.B

|  |
| ------------- |
| VAHTS Library Quantification Kit for Illumina（High ROX Premixed）
| Vazyme Code：NQ104 5ml 500rxn
| L/N：7E142D7 Exp：2018.11.24
| Store at -20℃避光

VAHTS Library Quantification Kit for Illumina®：http://www.vazyme.com/downloadRepository/989f605d-598e-4e2a-b40c-eb5da213516e.pdf

### 5.1.1 实时荧光定量PCR（qPCR）定量
1.根据文库上机表在-20℃冰箱找到上机文库，振荡混匀，离心；

2.用Library Dilution Buffer对文库稀释50倍（98ul Library Dilution Buffer+2ul文库），振荡混匀，离心；

3.用Library Dilution Buffer对上一步稀释的文库稀释40倍（78ul Library Dilution Buffer+2ul上一步稀释的文库），振荡混匀，离心；

**多样性文库稀释2000倍，基因组文库稀释4000倍；**

4.标准品（Illumine Phix v3）梯度稀释；

（1）9ul稀释缓冲液（Library Dilution Buffer）+1ul标准品（Illumine Phix v3），振荡混匀，离心得到标准品I；

（2）18ul稀释缓冲液（Library Dilution Buffer）+2ul标准品I，振荡混匀，离心得到标准品CK1；

（3）18ul稀释缓冲液（Library Dilution Buffer）+2ul标准品CK1，振荡混匀，离心得到标准品CK2；

（4）18ul稀释缓冲液（Library Dilution Buffer）+2ul标准品CK2，振荡混匀，离心得到标准品CK3；

（5）18ul稀释缓冲液（Library Dilution Buffer）+2ul标准品CK3，振荡混匀，离心得到标准品CK4；

（6）18ul稀释缓冲液（Library Dilution Buffer）+2ul标准品CK4，振荡混匀，离心得到标准品CK5；

5.用VAHTS Library Quantification Kit for Illumina（High ROX Premixed）配制qPCR Mix；

|  |  | 
| ------------- |:-------------:| 
| VAHTS SYBR qPCR Master Mix（Without ROX，Low or High ROX Premixed） | 10.0ul
| qPCR Primer Mix | 2.0ul
| DNA Standard 1-6或稀释后的文库或灭菌蒸馏水 | 4.0ul
| 灭菌蒸馏水 | 4.0ul
| 总和 | 20.0ul

6.取qPCR板，分装16ul qPCR Mix至孔中；

A1A2孔加4ul标准品CK1；（标准曲线）

A3A4孔加4ul标准品CK2；

A5A6孔加4ul标准品CK3；

A7A8孔加4ul标准品CK4；

A9A10孔加4ul标准品CK5；

A11孔加入4ul标准品CK1；（阳性对照）

A12孔加入4ul Library Dilution Buffer；（阴性对照）

剩余的孔加入4ul稀释好的文库，B1C1孔为一组重复，依次类推；

7.戴上PE手套盖上封口膜，放在振荡器上稍微振荡，离心，放入荧光定量仪器里面；

8.设置参数；

（1）打开桌面上的StepOne Software v2.3快捷方式；

（2）弹出Login界面，User Name填写Guest，点击OK；
 
（3）弹出主界面；
 
（4）选择Set Up菜单下Advanced Setup，创建新的反应程序，默认进入Experiment Properties子菜单；

How do you want to identify this experiment？

Experiment Name填写文件名；

Which instrument are you using to run the experiment?

选择StepOnePlusTM Instrument（96 Wells）

What type of experiment do you want to set up?

选择Quantitation-Standard Curve

Which reagents do you want to use to detect the target sequence?

选择SYBR® Green Reagents

去掉Include Melt Curve前面的勾；

Which ramp speed do you want to use in the instrument run？

选择Standard（~2 hours to complete a run）
 
进入Plate Setup子菜单；

默认在Define Targets and Samples标签里面；

Define Samples-Add New Sample添加文库名列表；

切换到Assign Targents and Samples-View Plate Layout标签，

添加样本加入孔的位置，A1-A10孔标记为S（标准曲线），A11孔标记为U（阳性对照），A12孔标记为N（阴性对照），剩余加样孔孔标记为U（未知）；

设置标准曲线：

选择Define and Set Up Standards弹出窗口；

#of Points：5

#of Replicates：2

Starting Quantifity：1000000

Serial Factor：1:10

Select and arrange wells for the standards

Use Wells：选择Let Me Select Wells，选择A1-A10孔-Apply-Yes-Close；

进入Run Method子菜单，默认在Graphical View标签下；

95.0℃ 05:00

95.0℃ 00:30

60.0℃ 00:45

Number of Cycles：35
 
确认无误后，点击START RUN开始运行（耗时60min）；
 
运行结束后查看标准曲线的R2值及阳性对照的值是否在可用范围内；

合格后导出表格，选择Export-Browse（选择路径）-Start Export-Close Export-Tool；
 
 
打开导出的表格，Quantity Mean后面插入一列，计算公式=Quantity Mean/10000X2；

删除重复项，所得浓度为文库摩尔浓度，同时标记文库名称对应顺序。

5.1.2 Qubit荧光定量计定量

5.1.3 TBS-380微型荧光计定量

5.2 文库的片段大小检测








