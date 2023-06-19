# 概述
## 吸收的目的

1. 回收或捕获气体混合物中的有用物质，以制取产品
2. 除去工艺气体中的有害成分，使气体净化以便进一步加工处理；或除去工业放空尾气中的有害物以免污染大气
## 需要解决的问题

1. 选择合适的溶剂，使某个（某些）被分离组分能选择性的溶解
2. 提供适当的传质设备以实现气液两相的接触，使被分离组分得以自气相转移至液相（吸收）或相反（解吸）
3. 溶剂的再生
## 溶剂的选择

1. 溶剂应对混合气中被分离组分（下称溶质）有较大的溶解度
2. 溶剂对混合气中其他组分的溶解度要小，即溶剂应具有较高的选择性。
3. 溶质在溶剂中的溶解度应对温度变化比较敏感
4. 溶剂蒸汽压低
5. 溶剂化学稳定
6. 溶剂黏度较低
7. 价廉、易得、不易燃烧
## 气体吸收的分类
物理吸收<br />化学吸收：需要可逆和较高的反应速度
## 吸收操作费用

1. 气液两相流经吸收设备的能量消耗（流动能耗）
2. 溶剂的挥发损失和和变质损失
3. 溶剂的再生费用
## 接触方式
级式接触、微分接触

---

# 溶解度与亨利定律
## 亨利定律
低含量气体混合物吸收式液相的含量通常也较低，即常在稀溶液范围内，服从亨利定律<br />$p_e=Ex$<br />$p_e=Hc$<br />$y_e=mx$<br />以上三式中，比例系数为以不同单位表示的亨利系数，其中m又称为相平衡常数。这些常数值与溶解能力成反比<br />各系数的关系如下：<br />$m=\frac{E}{p}$<br />$E=Hc_M$<br />$c=c_Mx$<br />p为总压，$c_M$为混合液的总体积浓度（$kmol/m^3$）<br />总浓度的估算：$c_M=\frac{\rho_m}{M_m}$<br />对稀溶液：$E\approx\frac{H\rho_s}{M_s}$
## 相平衡与吸收过程的关系
### 方向
|  | 液相组成x（平衡时xe） | 气相组成y（平衡时ye） |
| --- | --- | --- |
| 吸收 | x<xe | y>ye |
| 解吸 | x>xe | y<ye |

### 极限
相平衡关系限制了吸收溶剂离塔时的最高含量和气体混合物离塔时的最低含量<br />$y_{2,min}=y_{e2}=mx_2$<br />$x_{1,max}=x_{1e}=\frac{y_1}{m}$
### 计算过程的推动力
吸收：$\Delta y=y-y_e$$\Delta x=x_e-x$<br />解吸：$\Delta y=y_e-y$$\Delta x=x-x_e$

---

# 吸收速率
吸收过程设计两相见的物质传递，他包含三个步骤

   - 溶质由气相主体传递到两相界面
   - 溶质在相界面上的溶解
   - 溶质自界面被传递至液相主体
## 分子扩散速率——费克定律
$J_A=-D_{AB}\frac{dc_A}{dz}$<br />$J_A$是单位时间内组分A扩散通过单位面积的物质的量，称为扩散系数$kmol/(mol\cdot s)$；$dc_A/dt$为组分A在扩散方向z上的浓度梯度，浓度单位$kmol/m^3$；$D_{AB}$为组分A在AB两组分混合物中的扩散系数$m^2/s$;负号表示扩散沿浓度降低方向进行。

组分在气体中的扩散系数：$D=D_0
(\frac{T}{T_0})^{1.81}(\frac{p_0}{p})$<br />组分在液体中的扩散系数：$D=D_0(\frac{T}{T_0})(\frac{\mu_0}{\mu})$
## 对流传质
气相与界面的传质的速率方程可以写成<br />$N_A=k_G(p-p_i)$<br />$N_A=k_y(y-y_i)$<br />液相与界面的传质的速率方程可以写成<br />$N_A=k_L(c_i-c)$<br />$N_A=k_x(x_i-x)$

不难导出如下关系<br />$k_y=pk_G$<br />$k_x=c_Mk_L$
# 相际传质
## 速率方程
$N_A=K_y(y-y_e)$<br />$K_y=\frac{1}{\frac{1}{k_y}+\frac{m}{k_x}}$<br />或<br />$N_A=K_x(x_e-x)$<br />$K_y=\frac{1}{\frac{1}{k_ym}+\frac{1}{k_x}}$
## 传质阻力的控制步骤
阻力：$\frac{1}{K_y}=\frac{1}{k_y}+\frac{m}{k_x}$<br />当$\frac{1}{k_y}>>\frac{m}{k_x}$此时阻力集中在气相，称为气相阻力控制过程<br />当$\frac{1}{k_y}<<\frac{m}{k_x}$此时阻力集中在液相，称为液相阻力控制过程

---

# 低含量气体吸收
## 数学描述
### 物料衡算
#### 微分形式
对气相：$Gdy=N_Aadh$<br />对液相：$Ldx=N_Aadh$<br />对两相：$Gdy=Ldx$
#### 积分形式
$Gy_1+Lx_2=Gy_2+Lx_1$
### 相际传质速率方程
$H=\frac{G}{K_ya}\int_{y_2}^{y_1}\frac{dy}{y-y_e}$<br />$H=\frac{L}{K_xa}\int^{x_1}_{x_2}\frac{dx}{x_e-x}$
### 传质单元数与传质单元高度.
对上式，令<br />$H_{OG}=\frac{G}{K_ya}，H_{OL}=\frac{L}{K_xa}$<br />$N_{OG}=\int_{y_2}^{y_1}\frac{dy}{y-y_e}，N_{OL}=\int^{x_1}_{x_2}\frac{dx}{x_e-x}$<br />$N_{OG}$为以$(y-y_e)$为推动力的传质单元数，是一个无量纲量。$H_{OG}$具有长度量纲，单位为m，称为传质单元高度

- 传质单元数反映了分离任务的难易。越大越差
- 传质单元高度与设别的型式设备中的操作条件，表示完成一个传质单元所需要的塔高吸收设备效能高低的反应。
- 传质系数随流率增加而增加，但$G/K_ya(L/K_xa)$与流率关系不大
### 操作线与推动力的变化规律
![逆流吸收操作线](https://cdn.nlark.com/yuque/0/2022/jpeg/26350656/1649469494160-06c6042e-d5c3-46e6-afca-45f73bfd3885.jpeg#clientId=udad0833a-db7a-4&from=drop&height=490&id=u0fd9845e&originHeight=1256&originWidth=2716&originalType=binary&ratio=1&rotation=0&showTitle=true&size=66287&status=done&style=none&taskId=ue39bc064-55bc-45b5-8231-14a213945ab&title=%E9%80%86%E6%B5%81%E5%90%B8%E6%94%B6%E6%93%8D%E4%BD%9C%E7%BA%BF&width=1060 "逆流吸收操作线")<br />垂直方向$y-y_e$为气相吸收推动力，水平方向$x_e-x$为液相吸收推动力<br />$\frac{d(\Delta y)}{dy}=\frac{\Delta y_1-\Delta y_2}{y_1-y_2}$<br />$\frac{d(\Delta x)}{dx}=\frac{\Delta x_1-\Delta x_2}{x_1-x_2}$
## 传质单元数的计算
### 平均推动力**法——当平衡线为直线时**
$H_{OG}=\frac{G}{K_ya}\cdot \frac{y_1-y_2}{\Delta y_m}$<br />$\Delta y_m =\frac{\Delta y_1-\Delta y_2}{ln\frac{\Delta y_1}{\Delta y_2}}$<br />$N_{OG}=\frac{y_1-y_2}{\Delta y_m}$

$H_{OL}=\frac{L}{K_xa}\cdot \frac{x_1-x_2}{\Delta x_m}$<br />$\Delta x_m =\frac{\Delta x_1-\Delta x_2}{ln\frac{\Delta x_1}{\Delta x_2}}$<br />$N_{OL}=\frac{x_1-x_2}{\Delta x_m}$

### 吸收因数法
$N_{OG}=\frac{1}{1-\frac{1}{A}}ln[(1-\frac{1}{A})\frac{y_1-mx_2}{y_2-mx_2}+\frac{1}{A}]$<br />$N_{OL}=\frac{1}{1-A}ln[(1-A)\frac{y_1-mx_2}{y_1-mx_1}+A]$
