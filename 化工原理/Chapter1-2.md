# 静力学方程
## 静压强的特性

   - 任意界面上只有大小相等，方向相反的压力
   - 作用于任意点不同方向的静压强数值相等
   - **压强各自传递**
## 静力学方程
设流体不可压缩（密度与压强无关），则该流体中有：<br />$\frac{p}{\rho}+gz=const$<br />在同一流体中，有：<br />$\frac{p_1}{\rho}+gz_1=\frac{p_2}{\rho}+gz_2$<br />或$p_1=p_2+\rho gh$<br />以上三式即静力学方程。注意，以上三式仅适用于在重力场中静止，连续不可压缩流体。<br />以上三式表明：

      - **静压强仅与垂直位置有关**，于水平位置无关。
      - 压强P与其液体的密度有关
      - 压力具有传递性：液面上方压力变化时，液体内部各点的压力也将发生相应的变化，液面上所受的压强能以同样大小传递到液体内部(物理学中的帕斯卡原理）
      - 在同一静止流体中，处在不同位置流体的位能和静压能各不相同，但二者可以转换，其总和保持不变 。

静止连续同种流体内处于同一水平面上各点压力处处相等，称为等压面
## 虚拟压强
用$\frac{p^*}{\rho}$表示单位质量流体的总势能（此处$p^*$写作花体字母p）<br />则有$\frac{p^*}{\rho}=gz+\frac{p}{\rho}$<br />$p^*=p+\rho gz$<br />对不可压缩流体，上式表明同种静止流体各点的虚拟压强处处相等。
## 应用
### 压差与压差计
#### U形压差计
![image.png](https://cdn.nlark.com/yuque/0/2022/png/26350656/1646531521619-bdd32c15-af79-45ec-8ec4-b332270dca28.png#clientId=u327547fd-e328-4&from=paste&height=233&id=uc9aae28b&originHeight=612&originWidth=1411&originalType=binary&ratio=1&rotation=0&showTitle=false&size=59404&status=done&style=none&taskId=u0db66d34-13c0-49ee-8ebf-b598a22da16&title=&width=538)![image.png](https://cdn.nlark.com/yuque/0/2022/png/26350656/1646531535195-8441e574-2d98-43ed-8296-6df1a343413f.png#clientId=u327547fd-e328-4&from=paste&height=243&id=RHiJ4&originHeight=510&originWidth=1118&originalType=binary&ratio=1&rotation=0&showTitle=false&size=37899&status=done&style=none&taskId=u6f54c933-a95c-4c17-820b-9c4768ad771&title=&width=532)<br />（1）U形压差计可测系统内两点的压力差，当将U形管一端与被测点连接、另一端与大气相通时，也可测得流体的表压或真空度； <br />（2）指示液的选取：<br /> 	指示液与被测流体不互溶，不发生化学反应；  其密度要大于被测流体密度。<br />应根据被测流体的种类及压差的大小选择指示液。常用的指示液有汞、四氯化碳、水和液体石蜡等。 <br />（3）当管壁倾斜时，压差为虚拟压强差。
#### **双液体U管压差计（微差压强计）**
适用于压差较小的场合。<br /> 密度接近但不互溶的两种指示液A和C$(\rho_A>\rho_C)$；扩大室内径与U管内径之比应大于10 <br />![image.png](https://cdn.nlark.com/yuque/0/2022/png/26350656/1646531864224-8eb20b91-94f2-4bee-b15d-0381ea9648b9.png#clientId=u327547fd-e328-4&from=paste&height=323&id=ue3d73348&originHeight=712&originWidth=427&originalType=binary&ratio=1&rotation=0&showTitle=false&size=55029&status=done&style=none&taskId=uab769559-c68e-4946-9081-f5fc1910253&title=&width=193.55557250976562)<br />$\because p_1+\rho_c(m+R)g=p_2+\rho_cmg+\rho_AgR$<br />$\therefore p_1-p_2=Rg(\rho_A-\rho_c)$<br />$(\rho_A-\rho_c)$值越小，则读数R越大，那么在测很小的压差时，也能精确读取R值。
#### **倒U形压差计**
        指示剂密度小于被测流体密度，如空气作为指示剂 <br />$p_1-p_2=Rg(\rho-\rho_0)\approx Rg\rho$<br />![image.png](https://cdn.nlark.com/yuque/0/2022/png/26350656/1646532040964-b8628e36-8605-4849-ad4a-6fa28ccb84e1.png#clientId=u327547fd-e328-4&from=paste&height=290&id=ufb2334ab&originHeight=725&originWidth=356&originalType=binary&ratio=1&rotation=0&showTitle=false&size=40489&status=done&style=none&taskId=uf8f6c932-93db-4e95-8512-bfce116ce4e&title=&width=142.4444580078125)

---

# 守恒原理
## 管流质量守恒
**定态流动中，单位时间内流入截面1的流体质量和单位时间内流出截面2的流体质量相等**<br />$\rho_1u_1A_1=\rho_2u_2A_2=......=const$<br />上式即为流体在管道中做定态流动时的质量守恒方程式。对于不可压缩流体，有：<br />$\frac{u_2}{u_1}=\frac{A_1}{A_2}=(\frac{d_1}{d_2})^2(当圆形管时)$<br />上式表明：因受质量守恒定律的约束，**不可压缩流体的平均流速其数值只随管截面的变化而变化**，即截面增加流速减少，截面减小流速增大；流体在均匀直管中做定态流动时，**平均流速**$u$**保持定值**，不因内摩擦而减速，消耗的是静压能。
## 机械能守恒（伯努利方程）
### 伯努利方程
对不可压缩的理想流体，在重力场中做定态管流，有<br />$gz+\frac{p}{\rho}+\frac{u^2}{2}=const\quad(J/kg)$<br />此式称为伯努利方程。表明在流动的流体中存在着三种形式的机械能，即位能、压强能、动能。伯努利方程表明在流体流动过程中此三种机械能可以互相转化，但其总和保持不变。<br />上式亦有写法如下：$gz_1+\frac{p_1}{\rho}+\frac{u_1^2}{2}=gz_2+\frac{p_2}{\rho}+\frac{u_2^2}{2}\quad(J/kg)$<br />使用条件：

      - 重力场、定态流动，不可压缩的理想流体
      - 无外加能量或机械能输出
### 伯努利方程的几何意义
将伯努利方程两边除以g可得伯努利方程的另一种形式（单位重量流体做基准）<br />$z+\frac{p}{\rho g}+\frac{u^2}{2g}=const\quad(m)$

   - $z$是单位重量流体所具有的位能，也是被考察流体据基准面的高度，称为位头；
   - $\frac{p}{\rho g}$是单位重量流体所具有的压强能，也是以流体柱高度表示的压强，称为压头；
   - $\frac{u^2}{2g}$是单位重量流体所具有的动能，称为速度头。![image.png](https://cdn.nlark.com/yuque/0/2022/png/26350656/1646532262894-26fb0821-1e98-4386-8e3c-0110c7297373.png#clientId=u327547fd-e328-4&from=paste&height=816&id=ua033a9dd&originHeight=918&originWidth=1483&originalType=binary&ratio=1&rotation=0&showTitle=false&size=41705&status=done&style=none&taskId=uec333133-3e48-4255-aea8-01d656f5d59&title=&width=1318.2222222222222)
### 实际流体的能量衡算
能量：$gz_1+\frac{p_1}{\rho}+\frac{u_1^2}{2}+W_e=gz_2+\frac{p_2}{\rho}+\frac{u_2^2}{2}+W_f\quad(J/kg)$<br />压头式：$z_1+\frac{p_1}{\rho g}+\frac{u_1^2}{2g}+H_e=z+\frac{p_2}{\rho g}+\frac{u_2^2}{2g}+\sum{H_f}\quad(m)$
### 解题过程的特殊注意

   - 根据题意，画出流程示意简图
   - 正确选择截面
      - 与流体的流动方向相垂直
      - 两截面间流体应是定态连续流动
      - 截面宜选在已知量多、计算方便处
   - 选择合适的基准水平面
      - 必须与地面平行；
      - 宜于选取两截面中位置较低的截面
      - 若截面不是水平面，而是垂直于地面，则基准面应选过管中心线的水平面
   - 单位必须一致
### 应用
流量、流体压力、可逆设备功率、容器间相对位置。

---

# 流体流动阻力
## 流动的类型、雷诺数、边界层
### 雷诺实验
![image.png](https://cdn.nlark.com/yuque/0/2022/png/26350656/1646718139589-fb93d4e4-1ab3-429b-94c0-a0c36042a2d6.png#clientId=u0d90b670-05fe-4&from=paste&height=444&id=ue20a5de1&originHeight=500&originWidth=1346&originalType=binary&ratio=1&rotation=0&showTitle=false&size=81997&status=done&style=none&taskId=u2d2d9cc5-a5e1-4d93-9637-aa64d1de51f&title=&width=1196.4444444444443)<br />在一个水箱力，水面下安装一个喇叭形进口的玻璃管。管下游安装一个阀门，利用阀门的开度调节流量。在喇叭形进口处中心有一根针形小管，从此小管流出一丝着色水流。<br />当水的流量较小时，玻璃管水流中出现一丝稳定而明显的着色直线。随着流速逐渐增加，起初着色线仍然保持凭证光滑；当流量增大到某临界值时，着色线开始抖动，弯曲，继而断裂，最后完全与水流主体混在一起无法分辨，而整个水流也就染上了颜色。
### 流动的类型
**层流（或滞流）：**流体质点仅沿着与管轴平行的方向作直线运动，即流体分层流动，层次分明，质点无径向脉动，质点之间互不混合；<br />**湍流（或紊流） ：**流体质点除了沿管轴方向向前流动外，还有径向脉动，各质点的速度在大小和方向上都随时变化，质点互相碰撞和混合。
### 雷诺数
$Re=\frac{du\rho}{\mu}\quad（1）$（无因次数群）

$Re<2000$必定形成层流，称为层流区<br />$2000<Re<4000$过渡区<br />$Re>4000$一般都会出现湍流，称为湍流层

$Re$反映了流体流动中惯性力与黏性力的对比关系，标志着流体流动的湍动程度。它在研究动量传递、热量传递、质量传递中尤为重要。  
### 流体在圆管内的速度分布
#### 层流速度分布
![image.png](https://cdn.nlark.com/yuque/0/2022/png/26350656/1646719182036-ca2afea7-cdc5-4bd9-aefb-745fc6b3d7d2.png#clientId=u110dab34-e331-4&from=paste&height=263&id=u27bed03b&originHeight=461&originWidth=800&originalType=binary&ratio=1&rotation=0&showTitle=false&size=83651&status=done&style=none&taskId=u86e7e81b-4dff-41f0-a3b6-9ead8f6c3ce&title=&width=457.11114501953125)<br />速率分布方程<br />$u=\frac{\Delta p}{4\mu l}(R^2-r^2)=u_{max}[1-(\frac{r}{R})^2]$即流体在圆形直管内层流流动时，其速度呈抛物线分布。<br />$\bar u=\frac{V_S}{A}=\frac{1}{2}u_{max}$即层流流动时的平均速度为管中心最大速度的1/2。 
#### **湍流速度分布**
![image.png](https://cdn.nlark.com/yuque/0/2022/png/26350656/1646719367245-3ca64146-4a38-44d3-9584-d596621a4fc6.png#clientId=u110dab34-e331-4&from=paste&height=265&id=u7d7ea084&originHeight=437&originWidth=763&originalType=binary&ratio=1&rotation=0&showTitle=false&size=64835&status=done&style=none&taskId=u2b2c5d95-36b5-46ae-9155-6391602465b&title=&width=463.22222900390625)<br />剪应力：$\tau=(\mu+\mu')\frac{du}{dy}$<br />μ′为湍流黏度，不是物性，其值与Re及流体质点位置有关，故湍流时速度分布不能像层流一样通过流体柱受力分析从理论上导出，只能将试验结果用经验式表示：<br />$u=u_{max}(1-\frac{r}{R})^n$<br />当$n=\frac{1}{7}$时，$\bar u=0.82u_{max}$
### 流体流动边界层
#### 边界层的形成与发展 
流动边界层：存在着较大速度梯度的流体层区域。即流速降为末受边壁影响流速的99％以内的区域。流动阻力主要集中在此区域。<br />边界层厚度：边界层外缘与壁面间的垂直距离。
#### 流体在平板上流动时的边界层： 
![image.png](https://cdn.nlark.com/yuque/0/2022/png/26350656/1646719879339-e7b7c38e-e08e-4737-ba62-15fa5f5b3d8f.png#clientId=u110dab34-e331-4&from=paste&height=205&id=u193f56be&originHeight=587&originWidth=1500&originalType=binary&ratio=1&rotation=0&showTitle=false&size=130221&status=done&style=none&taskId=uca03d43c-5b88-4932-9d66-ec2a8afc81f&title=&width=524) <br />边界层区（边界层内）：沿板面法向的速度梯度很大，需考虑黏度的影响，剪应力不可忽略。<br />主流区（边界层外）：速度梯度很小，剪应力可以忽略，可视为理想流体 。
#### **边界层流型：层流边界层和湍流边界层。**
![image.png](https://cdn.nlark.com/yuque/0/2022/png/26350656/1646719936296-84dc3423-1d2a-4302-906e-7e572076043e.png#clientId=u110dab34-e331-4&from=paste&height=246&id=u3ff28ee5&originHeight=556&originWidth=1113&originalType=binary&ratio=1&rotation=0&showTitle=false&size=124601&status=done&style=none&taskId=u8c3ccf4f-622f-4226-af84-4ac648bebf9&title=&width=492)<br />层流边界层：近壁面处，边界层内的流型为层流。<br />湍流边界层：离开壁面前沿一段距离后，边界层内的流型转为湍流。 
#### **流体在圆管内流动时的边界层**
![image.png](https://cdn.nlark.com/yuque/0/2022/png/26350656/1646720218581-78b635ec-1dc9-4628-a19a-a315bfb7e420.png#clientId=u533b3bc3-fefc-4&from=paste&height=176&id=u8ee0818c&originHeight=437&originWidth=1288&originalType=binary&ratio=1&rotation=0&showTitle=false&size=96167&status=done&style=none&taskId=u939ebd4d-fd55-421e-a9bf-cfec33644a2&title=&width=519)<br /> 充分发展的边界层厚度为圆管的半径；<br /> 进口段内有边界层内外之分 。<br /> 也分为层流边界层与湍流边界层。
#### 湍流流动时：
![image.png](https://cdn.nlark.com/yuque/0/2022/png/26350656/1646720239159-de58f6e5-edb2-4067-a413-32295bcef1e6.png#clientId=u533b3bc3-fefc-4&from=paste&height=265&id=u248651b9&originHeight=606&originWidth=1212&originalType=binary&ratio=1&rotation=0&showTitle=false&size=144514&status=done&style=none&taskId=uc3c24c3b-eb39-499b-93a0-f4f0573090f&title=&width=529)<br />  湍流主体：速度脉动较大，以湍流黏度为主，径向传递因速度的脉动而大大强化；<br />  过渡层：分子黏度与湍流黏度相当；<br />  层流内层：一般很薄，其厚度随Re的增大而减	小，速度脉动较小，以分子黏度为主，径向传递只能依赖分子运动。——层流内层为传递过程的主要阻力。

---

## 流体流动阻力	
流动阻力产生的原因与影响因素归纳为:流体具有粘性,流动时存在着内摩擦是流动阻力产生的根源。<br />直管阻力：流体流经一定直径的直管时由于内摩擦而产生的阻力；<br />局部阻力：流体流经管件、阀门、三通及截面的突然扩大或缩小等局部地方由于流速大小及方向的改变而引起的阻力。 
### 直管阻力损失
 流体的流动阻力表现为流体势能的降低； 只有管道水平安装时，流动阻力恰好等于两截面的静压能之差。 
#### **直管阻力的通式(范宁Fanning公式)**
$W_f=\lambda\frac{l}{d}\frac{u^2}{2}\quad(J/kg)$<br />$h_f=\lambda\frac{l}{d}\frac{u^2}{2g}\quad(m)$<br />$\Delta p_f=\lambda\frac{l}{d}\frac{\rho u^2}{2}\quad(Pa)$<br /> 该公式层流与湍流均适用；注意$\Delta p$ 与$\Delta p_r$的区别。
#### **层流时的摩擦系数（**哈根-泊稷叶方程 **）**
$\Delta p_f=\frac{32\mu lu}{d^2}\quad (Pa)$<br />应用条件：①牛顿流体<br />                   	  ②层流状态<br />            	         ③圆直管速度分布稳定段（非入口段）。<br />$W_f=\frac{32\mu lu}{\rho d^2}\quad(J/kg)$<br />经处理可知$\lambda=\frac{64}{Re}$
#### 湍流时的摩擦系数

   - 柏拉修斯（Blasius）式：
      - $\lambda=\frac{0.3164}{Re^{0.25}}$
      - 适用光滑管$Re＝5×10^3～5×10^5$
   - 考莱布鲁克（Colebrook）式
      - $\frac{1}{\sqrt{\lambda}}=1.74-2lg(\frac{2\varepsilon}{d}+\frac{18.7}{Re\sqrt\lambda})$，有图像如下：![image.png](https://cdn.nlark.com/yuque/0/2022/png/26350656/1646721097591-39eed326-3d3c-4057-ab69-d393bcecea37.png#clientId=u533b3bc3-fefc-4&from=paste&height=337&id=u90e89401&originHeight=560&originWidth=960&originalType=binary&ratio=1&rotation=0&showTitle=false&size=485253&status=done&style=none&taskId=u3d5cd401-a60c-45d7-8a48-1733d4b637f&title=&width=577)![image.png](https://cdn.nlark.com/yuque/0/2022/png/26350656/1646721211165-bac1c199-e490-4ee9-ad44-f66ee67c2ba9.png#clientId=u533b3bc3-fefc-4&from=paste&height=412&id=u4fa3365d&originHeight=1026&originWidth=1409&originalType=binary&ratio=1&rotation=0&showTitle=false&size=123410&status=done&style=none&taskId=udfd84a5a-d789-49b9-8fe9-2288cbdc6f9&title=&width=566)
### 局部阻力损失
#### 阻力系数法
将局部阻力表示为动能的某一倍数。 <br />$W_f'=\zeta \frac{u^2}{2}\quad(J/kg)$<br />$h_f'=\zeta\frac{u^2}{2g}\quad(m)$<br />$\zeta:$局部阻力系数（查表）
#### **当量长度法**
将流体流过管件或阀门的局部阻力，折合成直径相同、长度为$l_e$的直管所产生的阻力 。					$W_f=\lambda\frac{l_e}{d}\frac{u^2}{2}\quad(J/kg)$<br />$h_f=\lambda\frac{l_e}{d}\frac{u^2}{2g}\quad(m)$<br />$l_e$—— 管件或阀门的当量长度，m。<br />当量长度$l_e$ :把流体流过截面的阻力损失相当于一定长度的管道阻力损失.

