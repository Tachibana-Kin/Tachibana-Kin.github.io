# 概述
## 蒸馏过程的依据
液体混合物部分气化所生成的气相组成与液相组成之间存在差距<br />$\frac{y_A}{y_B}>\frac{x_A}{x_B}$
## 工业蒸馏过程
### 平衡蒸馏
平衡蒸馏又称闪蒸，是连续定态过程。原料连续进入加热炉，在炉内加热到一定温度，然后经节流阀减压至预定压强<br />特点：

1. 连续操作
2. 定态过程
3. 气液两相一次平衡
### 简单蒸馏
简单蒸馏为间歇操作过程<br />特点：

1. 间歇操作
2. 非定态过程
3. 计算时选择时间微元作物料衡算和能量衡算
# 双组分溶液的气液平衡
## 气液两相共存时的自由度
根据相律，平衡物系的自由度为$F=N-\Phi+2$<br />其中组分数$N=2$，相数$\Phi=2$,故自由度为$2$
## 双组分理想气体的液相组成——温度关系式
### 理想物系的定义

1. 溶液为理想溶液，服从Raoult定律
2. 气相为理想气体，服从理想气体状态方程和道尔顿分压定律
### 温度关系式
根据拉乌尔定律，有$p_A=p_A^o\cdot x_A$$\quad$$p_B=p_B^o\cdot x_B$<br />混合液的沸腾条件是各组分组分的蒸汽压之和等于外压，即$p_A+p_B=p$<br />$p_A^ox_A+p_B^o(1-x_A)=p$<br />显然有$x_A=\frac{p-f_B(t)}{f_A(t)-f_B(t)}$
#### 安托因方程
$log_{10}{p^o}=A-\frac{B}{t+C}$
### 气液两相平衡组成间的关系式
$K=\frac{p_A^o}{p}$
### 露点方程
$y_A=\frac{p_A^o}{p}\cdot\frac{p-p_B^o}{p_A^o-p_B^o}=\frac{f_A(t)}{p}\cdot\frac{f_A(t)-f_B(t)}{f_A(t)-f_B(t)}$
### 温度-组成图
恒定压力下表示二组分系统气 - 液平衡时的温度与组成关系的相图，叫做温度 - 组成图。<br />对理想液态混合物，若已知两个纯液体在不同温度下的蒸气压数据，则可通过计算得出其温度 - 组成图。![未命名图片.jpg](https://cdn.nlark.com/yuque/0/2022/jpeg/26350656/1650089697176-062ce625-d4ff-4dc2-8058-0da6e9638575.jpeg#clientId=udf2da8e5-6997-4&from=drop&height=510&id=uda7f9828&originHeight=12024&originWidth=10976&originalType=binary&ratio=1&rotation=0&showTitle=false&size=2188243&status=done&style=none&taskId=u3849fb8c-b3cc-4738-8171-198c5595066&title=&width=466)<br />上方线为露点线，下线为泡点线
### 相对挥发度
定义：各组分的挥发度是各组分的平衡蒸汽压与其液相摩尔分数的比值。$\nu _A=\frac{p_A}{x_A}\quad \nu _B=\frac{p_B}{x_B}$<br />相对挥发度是两组分挥发度之比$\alpha=\frac{\nu_A}{\nu_B}$
### 相平衡方程
$y=\frac{\alpha x}{1+(\alpha-1)x}$$x=\frac{y}{\alpha-(\alpha-1)y}$

1.  对理想溶液$\alpha=\frac{p_A^o}{p_B^o}$ 
2.  如果在接近两纯组分沸点，可取$\alpha_m=0.5(\alpha_1+\alpha_2)$ 
3.  若在接近两纯组分沸点下，物系的相对挥发度相差较大但不超过30%时，$\alpha=\alpha_1+(\alpha_1-\alpha_2)x$ 
4.  $\alpha=1$时$y=x$ 
### 总压对相平衡的影响
蒸馏操作的压强增高，泡点随之增高，相对挥发度减小，分离较为困难。
# 精馏
将液态混合物同时经多次部分气化和部分冷凝而使之分离的操作称为精馏。<br />精馏多在恒压下进行，这里以混合物的泡点介于两纯组分沸点之间的某 A- B 系统为例，其温度–组成图如图。![1.jpg](https://cdn.nlark.com/yuque/0/2022/jpeg/26350656/1650089723048-71da40fa-67d7-45ac-bf4d-9f8e05260bcd.jpeg#clientId=udf2da8e5-6997-4&from=drop&height=452&id=u3cde1b78&originHeight=10864&originWidth=12504&originalType=binary&ratio=1&rotation=0&showTitle=false&size=2783256&status=done&style=none&taskId=u85d87723-5702-4bc6-bb73-b4e626d9eb5&title=&width=520)

设液态混合物原始组成为$x_0$，温度 $t_0$，在恒压下升温到$t_1$时，系统点为$M_1$，平衡的气、液两相相点分别为 $G_1$与$L_1$ 。组成为 $y_1$ 与 $x_1$ 。气液两相分开。液相L1被加热到 $t_2$ 到达$M_2$ ， 液体又部分气化，气、液两相相点分别为$G_2$ 与 $L_2$ 。组成为 $y_2$ 与 $x_2$ 。气液两相再度分开……如此等等，当液相每气化一次，A在液相中的相对含量就增大一些，这种操作多次重复，可得到$x_B$很小的液相，最后得到纯A。而将 $t_1$温度下得到的气相	 冷却到 $t_2^´$ ，到 $M_2^´$点，气体部分冷凝，气相点为$G_2^´$ ，液相点为 $L_2^´$ ，组成分别为 $y_2^´$ 和 $x_2^´$ 。气液两相分开后，气相中B的含量增大，如此反复操作，可得到 $y_B$ 很大的气相，最后得到纯 B。

在精馏塔中，部分气化与部分冷凝同时连续进行，即可将 A、B分开。加料位置以上，称为精馏段，加料位置一下为提馏段。

## 回流比
回流量的相对大小通常以回流比，即塔顶回流量与塔顶产品量之比表示<br />$R=L/D$
## 精馏过程的数学描述
### 物料衡算
#### 全塔
$F=D+W$<br />做轻组分物料衡算，有$Fx_F=Dx_D+Wx_W$<br />由此可得<br />$\frac{D}{F}=\frac{x_F-x_W}{x_D-x_W}$<br />$\frac{W}{F}=1-\frac{D}{F}$<br />,其中$\frac{W}{F}$,$\frac{D}{F}$为馏出液和釜液的采出率。<br />**精馏塔分离基本条件：**$x_D\le \frac{F x_F}{D}$
#### 精馏段
$Vy_{n+1}-Lx_n=Dx_D$
#### 提馏段
$\bar Vy_{n+1}-\bar Lx_n=Dx_D-Fx_F$
#### 单块塔板
总物料衡算：$V_{n+1}+L_{n-1}=V_n+L_n$<br />轻组分衡算：$V_{n+1}y_{n+1}+L_{n-1}x_{n+1}=V_ny_n+L_nx_n$
### 单块塔板的热量衡算

1.  $V_{n+1}I_{n+1}+L_{n-1}i_{n+1}=V_nI_n+L_ni_n$ 
2.  因为饱和蒸汽的焓说泡点液体的焓与气化潜热之和，故有<br />$V_{n+1}(i_{n+1}+r_{n+1})+L_{n-1}i_{n+1}=V_n(i_n+r_n)+L_ni_n$ 
3.  忽略组成与温度所引起的饱和液体焓和汽化潜热的区别，有$(V_{n+1}-V_n)r=(L_n+V_n-L_{n-1}-V_{n+1})i$,此时，$V_{n+1}=V_n,L_n=L_{n-1}$<br />在精馏塔内没有加料和出料的任意塔段中，各板上升的蒸汽量相等，下降的液体量也相等。 

恒摩尔溢流：精馏段内，除了加料板以外再没有中间加料或出料的情况下，每层塔板下降的液体摩流量都相等，提馏段也一样。
### 精馏塔气相回流比
$\bar R=\frac{\bar V}{W}$
### 理论板与板效率
板效率定义如下<br />$E_{m,v}=\frac{y_n-y_{n+1}}{y_n^*-y_{n+1}}\quad E_{m,L}=\frac{x_{n-1}-x_n}{x_{n-1}-x_n^*}$
### 加料热状态参数
$q=\frac{I-i_F}{I-i}=\frac{1kmol原料变为饱和蒸汽所需的热}{原料的摩尔汽化热}$

| q的大小关系 | 描述 | 操作线形态 |
| --- | --- | --- |
| $q=0$ | 饱和蒸汽加料 | 水平线，$x_F=y_F=y_e$ |
| $0<q<1$ | 气液混合物加料 | 在第二象限 |
| $q=1$ | 泡点加料 | 垂线，$x_e=x_f$ |
| $q>1$ | 冷液加料 | 在第一象限 |
| $q<0$ | 过热蒸汽加料 | 在第三象限 |

### 操作方程
令$L=RD，V=(R+1)D$
#### 精馏段操作方程
$y_{n+1}=\frac{R}{R+1}x_n+\frac{x_D}{R+1}$
#### 提馏段操作方程
$y_{n+1}=\frac{RD+qF}{(R+1)D-(1-q)F}x_n+\frac{Dx_D-Fx_F}{(R+1)D-(1-q)F}$<br />$=\frac{RD+qF}{(R+1)D-(1-q)F}x_n-\frac{Wx_W}{(R+1)D-(1-q)F}$
#### q线方程
$y_q=\frac{q}{q-1}x_q-\frac{x_F}{q-1}$
### 操作线图示
从a点出发做精馏操作线，截距$\frac{x_D}{R+1}$；从c点出发做提馏线,斜率$\frac{\bar L}{V}$<br />过点F做q线，斜率$\frac{q}{q-1}$,其与精馏线交点与c点的连线即为提馏线![扫描全能王 2022-04-16 14.06.jpg](https://cdn.nlark.com/yuque/0/2022/jpeg/26350656/1650089771273-72caa1d2-0660-4327-8d74-63e204a0c57f.jpeg#clientId=udf2da8e5-6997-4&from=drop&height=493&id=uec77cff8&originHeight=1512&originWidth=1508&originalType=binary&ratio=1&rotation=0&showTitle=false&size=64899&status=done&style=none&taskId=udd82cd0e-9d64-44c1-a475-cfb419eb44d&title=&width=492)
