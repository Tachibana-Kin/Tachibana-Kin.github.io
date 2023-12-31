# 传热概述
## 热量传递方式
### 直接接触式传热
热流体与冷流体直接混合<br />优点：

      - 结构简单
      - 传热效率高
      - 易于防腐

缺点：

      - 工艺上需允许两种流体可以混合
### 间壁式传热
冷热两种流体之间用一金属壁（或石墨等导热性能好的非金属壁）隔开，以便两种流体在不相混合的情况下进行热量传递。<br />套管换热器（传热面为内管表面积）、列管散热器（传热面为壳内所有管束表面积）
### 蓄热式传热
将热流体的热量预先储存在热载体上，然后由热载体将热量传递给冷流体。<br />优点：结构简单，耐高温<br />	缺点：体积大；流体有一定程度的混合
## 传热基本概念
载热剂：输出或得到热量的流体<br />加热剂：起加热作用的载热体<br />冷却剂：起冷却作用的载热体<br />热量守恒定律<br />$Q_L=q_{m1} c_{P1}(T_1-T_2)=q_{m2} c_{P2}(t_1-t_2)$<br />热流密度（热通量）：<br />$q=\frac{dQ}{dA}$
# 热传导
## 温度场与温度梯度
温度场：$t=f(x,y,z,\theta)$<br />$t：温度\quad x,y,z:坐标\quad\theta:时间$<br />当温度场函数与时间无关时称为定态温度场<br />温度梯度：$\lim_{\Delta n\rightarrow0}\frac{\Delta t}{\Delta n}=\frac{\partial t}{\partial n}$<br />是向量，垂直于等温面，温度增大为正方向
## 傅里叶方程
### 热传导基本方式
热传导，对流传热，辐射传热
### 傅里叶方程
$q=-\lambda\frac{\partial t}{\partial n}$<br />$q:热流密度（W/m^2）\quad\frac{\partial t}{\partial n}:温度梯度（\degree C/m）\quad$<br />$\lambda:比例系数，称为导热系数（W/(m\cdot\degree C)）\quad$<br />傅里叶定律指出：热流密度正比于传热面的法向温度梯度，（负号指示热量传递方向于传递方向相反）<br />比例系数$\lambda$是表征材料导热性能的参数，称为导热率。其值越大，导热性能越好。

除绝热材料外，$\lambda(金属)>\lambda(非金属)>\lambda(液体)>\lambda(气体)$<br />随温度升高，固体导热系数减小，液体略微减小，气体增大
## **平壁热传导**
### 单层平壁热传导
热流密度：$q=
\frac{Q}{A}=\lambda\frac{\Delta t}{\delta}$<br />$\Delta t：平壁两侧温度差\quad\delta:传导层厚度$

损失热量：$Q=\frac{\Delta t}{\frac{\delta}{\lambda A}}=\frac{\Delta t}{R}=\frac{推动力}{热阻}$
### 多层平壁热传导
#### 推动力和阻力的加和性
$Q=\frac{t_1-t_2}{\frac{\delta_1}{\lambda_1A}}=\frac{t_2-t_3}{\frac{\delta_2}{\lambda_2A}}=\frac{t_3-t_4}{\frac{\delta_3}{\lambda_3A}}$<br />$Q=\frac{\sum\Delta t}{\sum\frac{\delta}{\lambda A}}=\frac{总推动力}{总热阻}$
#### 各层的温差
$(t_1-t_2):(t_2-t_3):(t_3-t_4)=\frac{\delta_1}{\lambda_1A}:\frac{\delta_2}{\lambda_2A}:\frac{\delta_3}{\lambda_3A}=R_1:R_2:R_3$
## 单层圆筒壁热传导
壁上温度分布$\int ^{t_2}_{t_1}dt=-\frac{Q}{2\pi rl}\int ^{t_2}_{t_1}\frac{dr}{r}$<br />解得$Q=\frac{2\pi rl(t_1-t_2)}{ln(\frac{d_2}{d_1})}$<br />上式改写成$Q=\lambda A_m\frac{t_1-t_2}{\delta}=\frac{\Delta t}{\frac{\delta}{\lambda A_m}}$<br />其中$A_m=\frac{A_2-A_1}{ln(\frac{A_2}{A_1})}=\pi l\frac{d_2-d_1}{ln(\frac{d_2}{d_1})}$称作对数平均面积<br />$当\frac{r_2}{r_1}<2时，A_m=\frac{A_1+A_2}{2}$

---

# 对流给热
## 基础知识
### 分类
流体无相变的对流给热过程：强制对流给热、自然对流给热<br />（强制：外力作用，自然：温度导致密度变化）<br />流体有相变的对流给热过程：蒸汽冷凝给热过程、沸腾给热过程
### 对流给热过程的层区分布
#### 层流层
热量按传导方式进行，热阻与温度差集中在本层。有温度梯度存在的区域称为传热边界层或温度边界层。
#### 过渡区
热量靠流体质点分子的运动和混合来传递，可以看作时候热传导和对流给热共同作用的结果。
#### 湍流区
热量靠流体质点分子的运动和混合来传递，因为质点的剧烈混合，可以认为没有热阻。即没有温度梯度。

对流给热是流体流动与热传导协同作用的结果。流体对壁面的热流密度因流动而增大。
### 牛顿冷却定律
流体被加热时：$q=\alpha (t_w-t)$<br />流体被冷却时：$q=\alpha (t-t_w)$<br />$t_w:壁温\quad t:流体主体温度\quad \alpha:对流给热系数（W/(m^2\cdot\degree C)）\quad$<br />这是工程处理的一种方法，但这样的处理并未改变问题复杂性。按牛顿冷却定律，实验的任务是测定不同情况下的给热系数，并将其关联成经验表达式以供设计时用。
## 对流给热系数的影响因素

   - 流体相态：液体、气体、固体的$\alpha$值不同，发生相变时的$\alpha$远大于不发生相变的$\alpha$
   - 流体性质：密度、比热容、导热系数、黏度
   - 流体流动状态：层流与湍流时的$\alpha$不同。湍流程度高时，$\alpha$值增大
   - 流体流动原因：强制对流和自然对流的$\alpha$差距较大
   - 传热面的几何特征：传热面的形状、大小、位置、管道和板的排列方式

针对以上因素定义部分无量纲特征数：

   - 努塞尔数$Nu=\frac{ad}{\lambda}$
   - 雷诺数$Re=\frac{du\rho}{\mu}$
   - 普朗特数$Pr=\frac{c_P\mu}{\lambda}$
   - 格拉斯霍夫数（略）

描述给热过程的准数关系式如下：<br />$Nu=A\cdot Re^aPr^bGr^c$
## 管内无相变对流给热系数的经验关系式
对于圆形直管内的强制湍流，忽略自然对流的影响（$Gr=1$），故有<br />$Nu=0.023Re^{0.8}Pr^b$<br />$\alpha=0.023\frac{\lambda}{d}(\frac{du\rho}{\mu})^{0.8}(\frac{c_p\mu}{\lambda})^b$<br />其适用范围如下：

   - $Re>10000$
   - $0.7<Pr<140$
   - 流体低黏度（$\eta<=2\eta_{水}$）
   - $\frac{l}{d}>30\sim40$
   - 定性温度：进出口温度的算数平均值

注意：**当管内流体温度升高时，b取0.4；温度降低时，b取0.3。**<br />高粘度流体需引入系数$(\frac{\mu}{\mu_W})^{0.14}$<br />加热时，系数=1.05；冷却时，系数=0.95
## 有相变的对流给热
### 沸腾给热
对液体加热时，在液体内部伴有由液相变成气相，产生大量气泡的过程称为沸腾。<br />由于液体沸腾时必伴有流体流动，所以沸腾传热属于对流传热。
#### 两种沸腾——大容积沸腾与管内沸腾
大容积沸腾是指加热壁面被沉浸在无强制对流的液体中产生的沸腾现象。此时加热面产生的气泡长大到一定尺寸后，脱离表面自由上浮。这种沸腾液体中一方面存在着由温差引起的自然对流，另一方面又存在着因旗袍运动所导致的液体运动
#### 沸腾条件
##### 过热度
气泡存在的必要条件：其内部的蒸气压必须等于外压与液层静压强之和。因此液体温度至少等于ts，实际上在该温度下，小气泡还是不可能生成。因首先生成的微小气泡使液体呈现凹面，而液体在凹面上的Ps小于同温度下平面上Ps。凹面的曲率越大，产生的Ps越小。因此为弥补由于凹面而引起的蒸气压降低，使小气泡得以生成，液体的温度必须高相应ts。这种现象称为液体的过热。<br />液体的过热时新相（小气泡）生成的必要条件。<br />过热度$=t(实际温度)-ts(饱和蒸汽温度)$<br />过热度也与气泡半径有关
##### 气化核心
液体沸腾时气泡只能在租糙加热面的若干个点上产生这种点称为汽化核心。粗糙表面的小凹缝易于成为汽化核心，因表面功小，对气泡有依托作用，存在气泡胚胎，使初生气泡曲率半径增大，所需的过热度较小。<br />如果加热面比较光滑，则汽化核心少且曲率半径小，必须有很大的过热度才能使气泡生成，但一旦气泡长大，过热度已不再需要，过热液体在气泡表面迅速蒸发产生大量蒸气。此瞬间蒸发过程进行得十分激烈，称之暴沸。暴沸之后，过热度全部丧失，重又开始新相生成的孕育过程，此期间不生成蒸气。蒸发过程变得极为不平稳。暴沸现象对给热过程是不利的，应设法避免。但对粗糙表面一般不会产生暴沸现象。<br />在无相变对流给热中，热阻主要集中在紧贴加热表而的液体簿层内。沸腾给热也是如此，但在沸腾给热时，气泡的生成和脱对该薄层液体产生强烈的扰动。使热阻大为降低，所以沸腾给热的强度高于无相变的对流给热。<br />提高加热面的温度，可增加单位加热表面上的汽化核心数目。这是因为ｔ使加热面各点所能提供的过热度普遍增大，因而会有更多的部位具备产生气泡的条件，成为汽化核心。同时，ｔｗ增大还可使原有汽化核心上的气泡长大速度增加，脱离频率加快，从而使液体薄层受到更加剧烈的扰动。因此，沸腾给热系数必与温差有关。
#### 大容积饱和沸腾曲线
任何液体的大容积饱和沸腾随温差的变化，都会出现不同类型的沸腾状态。下面以大气压下饱和水在电热丝表面上的为例作具体说明：<br />![扫描全能王 2022-03-24 09.12.jpg](https://cdn.nlark.com/yuque/0/2022/jpeg/26350656/1648084453330-8ba1f711-1ae9-4828-8e12-046f97cc9099.jpeg#averageHue=%23f6f6f6&clientId=uf35a955f-0a66-4&from=drop&height=436&id=u3b4f4470&originHeight=1608&originWidth=1896&originalType=binary&ratio=1&rotation=0&showTitle=false&size=95970&status=done&style=none&taskId=ua2a50497-8ad4-402c-a9e2-7dd1da55d45&title=&width=514)

1. 当$\Delta t<2.2\degree C$，$\alpha$随$\Delta t$缓慢增加。此时紧贴加热表面的液体过热度很小不足以产生气泡加热表面与液体之间的给热是靠自然对流进行的。此阶段汽化现象只在液面上发生严说不是沸腾，而是**表面汽化**
2. 当$\Delta t>2.2\degree C$加热面上有气泡产生，$α﻿随Δt$增加急剧上升。由于气泡的产生和脱离对加热面附近液体的扰动越来越的缘战此阶段称为**核状沸腾**
3. 当$\Delta t$增大到某一定数值时，加热面上的汽化核心继续增多，产生的气泡来不及脱离加热面就相互连接，形成气膜，把加热面与液体隔开，开始形成的气膜是不稳定的，随着$\Delta t$增大，气膜趋于稳定。因气体$\lambda$远小于液体，故$\alpha$反而下降，称为**不稳定膜状沸腾**。
4. 当△t增大250℃。加热表面上形成一层稳定的气膜，把液体和加热表面完全隔开，但此时壁温较高，辐射传热作用变得更重要，$\alpha$再度随$\Delta t \uparrow$而加，此阶段称为**稳定膜状沸腾**。

在上述饱和沸腾各阶段中，核状沸腾具有$\alpha$大，壁温较低的优点，故工业沸应在核状沸腾状态下操作，但必须$\Delta t<=\Delta t_c$，否。核状沸将转变为膜状沸腾使$\alpha$急剧下降。<br />所以不适当地提高热流体温度，反而会使沸腾装置的效率降低

#### 强化

- 粗糙加热表面可以提供更多的气化核心，使气泡运动加剧，给热过程得以强化
- 加入少量添加剂，改变沸腾的表面张力。
### 蒸汽冷凝给热
在蒸汽冷凝加热过程中，加热介质为饱和蒸汽（有恒定温度，给热系数较大）。饱和蒸汽与低于其温度的冷壁接触时将凝结为液体，释放出气化潜热。<br />在饱和蒸汽冷凝过程中，气液两相共存，对于纯物质蒸汽的冷凝，系统只有一个自由度。因此只有一个气相温度，不存在温度梯度，不存在热阻。<br />冷却液凝结形成的液膜将覆盖壁面，因此蒸汽冷凝只能在冷凝液面上发生，冷凝时放出的潜热必须通过这层液膜才能传递给冷壁，内阻主要集中于此。
#### 膜状冷凝与滴状冷凝
当冷凝液能润湿壁面时，冷凝液在壁面呈膜状，否则呈滴状。<br />滴状的给热系数比膜状的给热系数大5~10倍，但工业冷凝器的涉及都按膜状冷凝考虑。
#### 影响因素

- 不凝性气体

工业用蒸汽不可能绝对纯，总有微量的不凝性气体。工业上都设有疏水器，只排除冷凝液而不允许气体和蒸汽逸出。这样，在连续运转过程中，不凝性气体将在冷凝空间中积聚

- 蒸汽过热
- 蒸汽流速的影响

当蒸汽流速过大时，则会影响冷凝液的流动。当蒸汽速度较大时，有必要考虑流速对给热系数的影响。<br />通常，蒸汽进入口设在换热器的上部，以避免蒸汽和冷凝液逆向流动。
#### 强化

- 在其上开若干纵向沟槽使冷却液炎沟槽流下
- 沿垂直壁装若干金属丝
- 采用适当的内插物分散冷却液

---

# 间壁式传热过程
## 热量衡算与传热系数
### 热量衡算
热量平衡方程：$q_{m1}c_{p1}(T_2-T_1)=q_{m2}c_{p2}(t_2-t_1)$<br />前提：

   - 冷热流体的流量和比热容沿热传面保持不变
   - 没有相变化
   - 没有热量损失
   - 热传导忽略不计
### 传热系数
![yuque_diagram (1).jpg](https://cdn.nlark.com/yuque/0/2022/jpeg/26350656/1648279166121-1630b27c-d03e-4a18-aef6-e97b7c96cc85.jpeg#averageHue=%23f5f5f5&clientId=u0f45d555-397a-4&from=drop&height=255&id=ua8093b56&originHeight=464&originWidth=920&originalType=binary&ratio=1&rotation=0&showTitle=false&size=30774&status=done&style=none&taskId=u1a20f60f-8637-46d9-afa0-84e66aa2e19&title=&width=506)<br />热量定向的由热流体传给管壁内侧，最后由管壁外侧传给冷流体，过程中热流密度恒定（忽略内外表面积差）<br />$q=\frac{T-T_w}{\frac{1}{\alpha_1}}=\frac{T_w-t_w}{\frac{\delta}{\lambda}}=\frac{t_w-t}{\frac{1}{\alpha_2}}$<br />由上式推得$q=\frac{T-t}{\frac{1}{\alpha_1}+\frac{\delta}{\lambda}+\frac{1}{\alpha_2}}=K(T-t)$<br />其中：$K=\frac{1}{\frac{1}{\alpha_1}+\frac{\delta}{\lambda}+\frac{1}{\alpha_2}}$<br />$K$**即为传热系数，其倒数是热阻之和**<br />$\frac{1}{K}=\frac{1}{\alpha_1}(内壁热阻)+\frac{\delta}{\lambda}(壁阻)+\frac{1}{\alpha_2}(外壁热阻)$
#### 四种特殊情况
$d_m(对数平均直径)=\frac{d_1-d_2}{ln \frac{d_1}{d_2}}$

1. 平壁

$\frac{1}{K}=\frac{1}{\alpha_{in}}+\frac{\delta}{\lambda}+\frac{1}{\alpha_{out}}$

2. 外表面基准

$\frac{1}{K_o}=\frac{1}{\alpha_o}+\frac{\delta}{\lambda}\frac{d_o}{d_m}+\frac{1}{\alpha_i}\frac{d_o}{d_i}$

3. 内表面基准

$\frac{1}{K_i}=\frac{1}{\alpha_i}+\frac{\delta}{\lambda}\frac{d_i}{d_m}+\frac{1}{\alpha_o}\frac{d_i}{d_o}$

4. 壁基准

$\frac{1}{K_m}=\frac{1}{\alpha_i}\frac{d_m}{d_i}+\frac{\delta}{\lambda}+\frac{1}{\alpha_o}\frac{d_m}{d_o}$
## 传热基本方程
条件：

   - 冷热流体的流量和比热容沿热传面保持不变
   - 没有相变化
   - 没有热量损失
   - 热传导忽略不计

$Q=KA\frac{(T_1-t_2)-(T_2-t_1)}{ln\frac{T_1-t_2}{T_2-t_1}}=KA\Delta t_m$<br />其中：$\Delta t_m=\frac{(T_1-t_2)-(T_2-t_1)}{ln\frac{T_1-t_2}{T_2-t_1}}$（对数平均温差）
### 对数平均温差的选择
流体第一入口侧和流体第一出口侧之间<br />逆流：$(T_1-t_2)-(T_2-t_1)$<br />并流：$(T_1-t_1)-(T_2-t_2)$
### 对数平均温差（对数平均推动力）

- 恒温传热

$\Delta t_m=T-t$

- 变温传热

![image.png](https://cdn.nlark.com/yuque/0/2022/png/26350656/1648282037099-c67448de-b29e-4e54-b23c-b529c706846c.png#clientId=u1f5b71a4-c9e0-4&from=paste&height=210&id=u681134a2&originHeight=272&originWidth=646&originalType=binary&ratio=1&rotation=0&showTitle=false&size=26568&status=done&style=none&taskId=u04f38125-8c28-4ecd-ba17-30f921dbce6&title=&width=499.22222900390625)![逆流、并流的示意图及其对数平均温差](https://cdn.nlark.com/yuque/0/2022/png/26350656/1648282213458-e25f9078-25c3-498f-8df0-312613451622.png#clientId=u1f5b71a4-c9e0-4&from=paste&height=414&id=u6fb8c526&originHeight=518&originWidth=696&originalType=binary&ratio=1&rotation=0&showTitle=true&size=58091&status=done&style=none&taskId=u84e226b3-abab-4dc1-ba1c-bf25ad5d56c&title=%E9%80%86%E6%B5%81%E3%80%81%E5%B9%B6%E6%B5%81%E7%9A%84%E7%A4%BA%E6%84%8F%E5%9B%BE%E5%8F%8A%E5%85%B6%E5%AF%B9%E6%95%B0%E5%B9%B3%E5%9D%87%E6%B8%A9%E5%B7%AE&width=555.6666870117188 "逆流、并流的示意图及其对数平均温差")

- 讨论
   - $\Delta t_m$的计算式也适用于并流
   - 大温差为$\Delta t_1$，大温差为$\Delta t_2$
   - 若$\frac{\Delta t_1}{\Delta t_2}<2,\Delta t_m=\frac{\Delta t_1+\Delta t_2}{2}$
   - 若$\Delta t_1=\Delta t_2,\Delta t_m= \Delta t_1=\Delta t_2$
## 一些特殊情况
### 污垢热阻
$\frac{1}{K}=\frac{1}{\alpha_{in}}+R_{in}+\frac{\delta}{\lambda}+\frac{1}{\alpha_{out}}+R_{out}$
### 壁温计算
$q=\frac{T-T_w}{1/\alpha_{in}}=\frac{T_w-t_w}{\delta/\lambda}=\frac{t_w-t}{1/\alpha_{out}}$<br />$\frac{T-T_w}{T_w-t}=\frac{\frac{1}{\alpha_{in}}}{\frac{1}{\alpha_{out}}}$（管内热流体，管外热流体限定）

$q=A\cdot\alpha\cdot(T-T_w)$<br />变温过程温度取对数平均温度<br />结论：壁温总是趋于$\alpha$值较大或热阻较小的温度

## 
