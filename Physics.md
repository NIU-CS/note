---
title: Physics
description: Physics note
---

# Physics

[TOC]

## 規則與計分方式

小考(2~4次) 課程參與 習題(A4) 30% 

報告與筆記 10% 

期中考 30% 

期末考 30% 

### 加分項目 

程式融入物理應用 

期末報告(看電影談物理) (最高10分) 

物理相關磨課師課程完課證明 (一張5分) 

原文考試可查閱字典，工程計算機，不得使用 PDA 

小考老師可翻譯 大考時不得提示 

秘密考題大考可加分 

## 筆記

### 慣用單位

- S.I. base units 國際單位制 (M.K.S 制)

|   單位   | 縮寫    | 物理量                            |
|:--------:| :----: | :---------------------------- |
|  meter   | m      | 長度 length                      |
| kilogram | kg     | 質量 mass                        |
|  second  | s      | 時間 time                        |
|  Ampere  | A      | 電流 electire current            |
|  kelvin  | k      | 溫度 temperature, thermodynamics |
|    mole  | mol    | 物量 amount of subtance          |
| camdela  | cd     | 亮度 luminous intensity              |

### Significant digits(figures) 有效數字 (S.F.)

- 數學 -> 實際值
- 理化 -> 測量值

測試 S.F. 最好的方式是將測量值寫成科學記號
scientific notation(S.N.)

$$ 0.00620 = \frac{6.20 * 10^{-3}}{ 3位S.F.} $$

E.X. 1500m
$$ \frac{1.5 * 10^3}{2位S.F.} $$ 
$$ \frac{1.500 * 10^3}{4位S.F.} $$ 
$$ \frac{1.50 * 10^3}{3位S.F.} $$

- Operations with S.F.

| 英文      | 中文 |
| :---:    | :---: |
| add      | 加 |
| subtract | 減 |
| multiply | 乘 |
| divid    | 除 |

- 原則：最終結果以數量中最少的 S.F. 為準

EX:

$$ m = \frac{6.47kg}{3位 S.F} $$
$$ v = \frac{4.44*10^{-4} m^3}{3位 S.F} $$
$$ e = \frac{2.7*10^3}{2位S.F.} $$

Sol:


$$ m = m_1 + m_2 =
6.47 + (4.44*10^{-4})(2.7*10^3) $$
$$ = 6.47 + 1.1988 = 7.67 = 7.7 $$

#### Motion 1D 一維運動

1. position 位置

$$ \vec{x} $$

- position vector

2. time 時間 

$$ t $$

$$ \Delta{t} = t_f - t_i $$

3. displacement 位移

$$ \Delta{x}=\vec{x}_f-\vec{x}_i $$

4. average velocity 平均速度

$$ \Delta{v}_{avg} \equiv \frac{\Delta\vec{x}}{\Delta{t}} $$

$$ v_{avg} = constant $$ 常數

5. uniform motion 等速度運動

$$ \vec{v}_s \equiv \frac{\lim}{\Delta{t}\rightarrow 0}\frac{\Delta\vec{x}}{\Delta{t}} = \frac{d\vec{x}}{dt} $$

6. 瞬時速度 instantaneous velocity 

7. 平均加速度

$$ \vec{a}_{avg} \equiv \frac {\Delta \vec v} {\Delta t} $$

8. 瞬時加速度

$$ \vec{a} \equiv \frac{\lim}{\Delta{t}\rightarrow 0}\frac{\Delta\vec{v}}{\Delta{t}} = \frac{d\vec{v}}{dt} $$

### In calculus 微分

$$ u(t) = ct^n \quad c，n \space為常數$$ 

$$ \frac {du(t)} {dt} = cnt^{n-1} $$

E.X

$$ x(t) = t^2 \quad ，\ \frac{dx(t)} {dt} = 2t^{2-1} = 2t $$

$$ x(t) = 3t^3 + 2t^1 + 1t^0  $$

$$ \frac {dx(t)} {dt} = 3*3t^{3-1} + 2*1t^{1-1} + 1*0t^{0-1} = 9t^2 + 2 $$

### In integrals 積分

$$ u(t) = ct^n \quad c，n \ 為常數  $$

$$ \int^{tf \rightarrow上限}_{ti \rightarrow下限} \quad u(t)dt = \int^{tf}_{ti}ct^ndt=\frac{ct^{n+1}}{n+1}=\frac{c}{n+1}(t_f^{n+1}-t_i^{n+1}) $$

定積分

E.X.
$$ \int^2_1 x^2dt = \frac{x^{2+1}}{2+1}|^2_1 = \frac{1}{3}(2^3-1^3) = \frac{7}{3} $$

$$ \int^2_1 (3t^3+2t+1)dt = \int^2_1 3t^3dt + \int^2_1 2tdt + \int^2_1 1dt = \frac{3t^{3+1}}{3+1}|^2_1 + \frac{2t^{1+1}}{1+1}|^2_1 + \frac {1+t^{0+1}}{0+1}|^2_1 $$

### $$ \vec a = constant \space常數 $$

uniformly accelerated motion

等加速運動

kinematic Equtions

運動方程式

$$ \vec v_f = \vec v_i + \vec a\Delta t \quad|\quad \vec x_f = \vec x_i + \vec v_i \Delta t + \frac {1}{2} \vec a \Delta t^2 \quad | \quad \vec v_f^2 = \vec v_i^2 + 2\vec a \Delta \vec x$$

1-D $$ x_i=0 \quad t_i=0 \quad \Delta t = 0 $$
$$ v_f = v_i + at \quad | \quad x = v_i t + \frac {1}{2}at^2 \quad | \quad v_f^2 = v_i^2 + 2ax$$

#### EX:

$$ X(t) = (-t^3 + 3t) \space單位：m $$

t 單位：秒

##### a, 

求 t=2(s) 時之位置 速度 加速度

##### b, 

畫出

$$ x-t, v-t (-3 <= t <= 3) $$

for 練習

##### c, 

畫書 motion diagram (p.67 ~ p.68)

#### Sol:

$$ x(t) = -t^3 + 3t $$

$$ v(t)= \frac {dx(t)}{dt} = -3*3t^{3-1} + 3*1t^{1-1} = -9t^2 + 3 $$

$$a(t) = \frac {dv(t)}{dt} = $$

##### (a)

$$ x(2) = -2^3 + 3*2 = -2(m) $$
$$ v(2) = -3*2^2 + 3 = -9(m/s) $$
$$ a(2) = -6*2 = -12(m/s) $$

##### (b)

- x-t 圖

![](https://cdn.discordapp.com/attachments/1152935463603142806/1153166926885961798/IMG_6078.jpg)

- v-t 圖

![](https://cdn.discordapp.com/attachments/1152935463603142806/1153167082075197460/IMG_6079.jpg)

##### (c) motion diagram 運動圖

![](https://cdn.discordapp.com/attachments/1152935463603142806/1153168426894897152/IMG_6081.jpg)

EX:

Sol:

##### a

v-t 圖面積 = 位移

$$ \Delta{x} = \frac{1}{2} \times 3 \times 12 = 18(m) $$

##### b

$$ x(t) = \int^t_0 v(t) = \int^t_0 4tdt = \frac{4t^{1+1}}{1+1} |^t_0 = 2t^2 $$

$$ x(3) = 2 \times 3^2 = 18(m) $$

![](https://cdn.discordapp.com/attachments/1152935463603142806/1153172475581059124/IMG_6084.jpg)

#### Free Fall 自由落體

物體從靜止開始落下 (at rest)
除受重力外沒有其他外力作用之運動

$$ \vec{a} = -gj $$

$$ v_{yi} = 0 $$

$$ \vec{a}_{freefall}  = (9.80 \space m/s^2 ,\space \downarrow) $$

##### kinematic egnations

$$ v_{yf} = -g\Delta{t} $$

$$ Y_f = y_i - \frac{1}{2}g\Delta{t^2} $$

$$ v_{yf}^2 = -2g\Delta{y} $$

$$ \Delta{y} = y_t - y_i $$

$$ v_{yf} = g\Delta{t} $$

$$ y_f = y_i + \frac{1}{2} g\Delta{t} $$

$$ v_{yf}^2 = 2g\Delta{y} $$

#### Motion on an Inclined Plome 斜面運動

### Chapter 3 Motion in 2-D,3_D

- position vector : 描述位置 

$$ \vec{r} $$

-位置向量

$$ \vec{r} = (x, y) = x\hat{i} +y\hat{j} = r_x\hat{i} +r_y\hat{j}$$

![](https://cdn.discordapp.com/attachments/1152935463603142806/1153560992337379328/1695100747980.jpg)

- placement 位移

$$ \Delta{\vec{r}} = \vec{r}_2 - \vec{r}_1 =\Delta{x\hat{i}}+\Delta{y{\hat{j}}}$$

$$ \Delta{x} = x_2 -x_1 \quad horizental\ component\ 水平分量$$
$$ \Delta{y} = y_2 -y_1 \quad vertical\ component \  垂直分量$$

- average velocity 平均速度

$$ \vec{v_{avg}} \equiv \frac{\Delta\vec{r}}{\Delta\vec{t}} = \frac{\Delta{x}}{\Delta{t}} \hat{i} + \frac{\Delta{y}}{\Delta{t}} \hat{j}$$

- instantaneous velocity 瞬時速度

$$ \vec{v} \equiv \frac {\lim}{\Delta t \rightarrow 0} \frac {\Delta \vec r}{\Delta \vec t} = \frac {d\vec r}{dt} = \frac {dx}{dt}\hat i + \frac{dy}{dt} \hat j $$

![](https://cdn.discordapp.com/attachments/1152935463603142806/1153564552328392754/1695101613463.jpg)

$$ v_{x}=vcos\theta $$$$ v_{y}=vsin\theta$$$$v=\sqrt{v^{2}_{x}+v^{2}_{y}},tan\theta=\frac{v_{y}}{v_{x}},\theta=tan^{-1}(\frac{v_{y}}{v_{x}})$$

:::warning
向量沒有除法
:::

:+1: 
$$ AX = B $$

:-1: 
$$ X = \frac{B}{A} $$

- average acceleration 平均加速度

$$ \vec{a}_{avg} \equiv \frac{\Delta{\vec{v}}}{\Delta{t}} = \frac{\vec{v}_f - \vec{v_i}}{\Delta{t}} $$

- instantaneous acceleration 瞬時加速度

$$ \vec{a} \equiv \lim{} \frac{\Delta{\vec{v}}}{\Delta{t}} = \frac{d \vec{v}}{dt} = a_x \hat i + a_y \hat j$$ 

$$ \vec{a} = \frac{dv_x}{dt} \hat{i} + \frac{dv_y}{dt} \hat{j} $$

$$ a_x = \frac{dv_x}{dt} = \frac{d^2x}{dt^2} $$

$$ a_y = \frac{dv_y}{dt} = \frac{d^2y}{dt^2} $$

一物體運動 \Delta{\vec{v}} 的變化有兩種

$$ 1.\ \vec v 之大小改變 \quad magnitude \space change $$ 
$$ 2.\ \vec v 之方向改變 \quad direction \space change $$

![](https://cdn.discordapp.com/attachments/1152935463603142806/1153568166249779360/1695102473112.jpg)

產生一加速度稱為向心加速度 centripetal acceleration

$$ \vec{a} = \vec{a}_{\parallel} + \vec{a}_{\perp} $$


$$ \vec{a}_{\parallel} \space 改變 \space \vec{v} \space 之大小 $$

$$ \vec{a}_{\perp} \space 改變 \space \vec{v} \space 之方向 $$

$$ \vec{a} \space 為 \space constant \space 等加速度 $$

kinematic eguations:

![](https://cdn.discordapp.com/attachments/1152935463603142806/1153569428143886397/1695102773454.jpg)

##### x 方向

$$ v_{tx} = v_{ix} + a_x \Delta{t} $$$$
x_{f}=x_{i}+v_{ix}\Delta t+\frac{1}{2}a_{x}\Delta t^{2}
$$$$
v^{2}_{fx}=v^{2}_{ix}+2a_{x}\times\Delta x
$$

##### y 方向

$$ v_{ty} = v_{iy} + a_y \Delta{t} $$
$$  $$
$$  $$

<!-- y和x 一樣 用複製就好 -->

### Projectile Motion 拋體運動

![](https://cdn.discordapp.com/attachments/1152935463603142806/1155689141086986270/IMG_20230925_101544.jpg)

C.S. 重力 忽略其他外力。

T: 軌跡方程式

$$ \hat{i} \perp  \hat{j}, \hat{i}*\hat{j} = 0 $$

##### x 方向

$$ v_x = v_{ix} = v_i cos\theta $$
$$ X_f = X_i + v_{ix}\Delta t $$

##### y 方向

$$ v_{yf} = v_{iy} - g\Delta{t} $$
$$ y_f = y_i + v_{iy} \Delta{t} - \frac{1}{2}g \Delta{t}^2 $$
$$ v_{yf}^2 = v_{iy}^2 - 2g \Delta y $$

由2.式 
$$ \Delta{t} = \frac{\Delta{x_{i}}}{v_{i}cos\theta} $$
代入4式

$$ \Delta{y} = v_{i}sin\theta(\frac{\Delta{x}}{v_{i}cos\theta})-\frac{1}{2}g(\frac{\Delta{x}}{v_{i}cos\theta})^2 $$

$$ \Delta{y} = (tan\theta)\Delta{x}-\frac{g}{2v_{i}^{2}cos^{2}\theta}(\Delta{x})^{2} $$
$$ x_{i} = 0,y_{i} = 0 $$

$$ y=(tan\theta)\Delta{x}-\frac{g}{2v_{i}^{2}cos^{2}\theta} $$

C.S.
$$ v_y=0 $$

5式

$$ 0^{2} = v^{2}_{i}sin\theta^{2}-2gH\Rightarrow H=\frac{v^{2}_{i}sin^{2}\theta}{2g} $$

3式
$$ 0 = v_{i}sin\theta - g(\frac{T}{2})\Rightarrow T = \frac{2v_{i}sin\theta}{g} $$

2式
$$ \Delta{x}=v_{i}cos\theta\Delta{t} $$
$$ R=v_{i}cos\theta \frac{2v_{i}sin\theta}{g} = \frac{2v_{i}sin\theta cos\theta}{g} = \frac{v_{i}^{2}sin2\theta}{g} $$

$$ \theta = 45^。\Rightarrow sin2\theta=1=1 $$
$$ R_{max} = \frac{v_{i}^{2}}{g} $$
$$ \theta_{1} + \theta_{2}=90^{。}\quad R相同 $$
向量表示
$$ \vec{r_{f}} = (x_i+v_{xi}\Delta{t})\hat{i}+(y_i+v_{yi}\Delta{t} - \frac{1}{2}g\Delta{t^2}) \hat{j} $$
$$ \vec{v}_{f} = v_{xi} \hat{i}+(v_{yi} - g\Delta{t}) \hat{j} $$
$$ \vec{a}_{f} = -g\hat{j} $$
$$ |\vec{v_f}| = \sqrt{v^2_{xf}+v^2_{yf}}\quad ，\theta = tan^{-1}(\frac{v_{xf}}{v_{yf}}) $$

EX 3-1

$$ x(t) = 2.0m-(0.25m/s^{2})t^{2} $$
$$ y(t) = (1.0m/s)t+(0.025m/s^{3})t^{3} $$

a) t=2.0s時座標，距離
b) t=0.0s到t=2.0s之位移，平均速度
c) t=2.0s瞬時速度，向量v(分量形事)(大小方向)

Sol
a)

$$ x(t) = 2.0-0.25 t^{2} $$

$$ y(t) = 1.0t+0.025 t^{2} $$

$$ x(2.0) = 2.0-0.25(2.0)^{2}=1.0(m)$$

$$ y(2.0) = 1.0 \times 2.0+0.025(2.0)^{3} = 2.2(m) $$

$$ \vec{r_{(2.0)}} = 1.0 \hat{i}+2.2 \hat{j} = (1.0,2.2) $$

$$ |\vec{r}| = \sqrt{1.0^2+2.2^2}=2.4(m) $$

b)

$$\vec{r}_{(0,0)} = 2.0\hat{i}+0.0\hat{j}$$

$$\Delta\vec{r}=\vec{r}_{(2.0)}-\vec{r}_{(0,0)}=(1.0-2.0)\hat{i}+(2.2-0.0)\hat{j}=-1.0\hat{i}+2.2\hat{j}$$

$$\Delta\vec{v}=\frac{\Delta\vec{r}}{\Delta{t}}=\frac{-1.0\hat{i}+2.2\hat{j}}{2.0-0.0}=-0.50\hat{i}+1.1\hat{j}$$

c)

$$ v_{x} = \frac{dx}{dt} = -0.50t $$

$$ v_{y} = \frac{dy}{dt} = 1.0 + 0.075t^{2} $$

$$ \vec{v} = (-0.50t) \hat{i} + (1.0 + 0.075t^{2}) \hat{j} $$

$$ \vec{v}_{(2,0)} = (-0.50 \times 2.0) \hat{i} +(1.0+0.075(2.0)^2) \hat{j} = -1.0 \hat{i}+1.3 \hat{j}(m/s) $$

$$ |\vec{v}| = \sqrt{(-1.0)^{2} + (1.3)^{2}} = 1.6(m/s) $$

$$ tan\theta = \frac{v_{y}}{v_{x}} \Rightarrow \theta = tan^{-1} (\frac{v_{y}}{v_{x}}) = tan^{-1} (\frac{1.3}{-1.0}) = -52^{。} \ ，38^{。} $$

#### Relative Motion 相對運動

- Reference Frame (參考系) R.F.

測量物理事件位置和時間的座標系統

- Inertial R.F. 慣性座標系

1. 方向一致(oriented the same)
    i.e. x 軸 // x' 軸
2. t = 0 時 O = O' 
3. s,s' 相對速度為常數

$$ InS 中，測得 flash \ \vec{r} $$

$$\vec{r}=\vec{R}+\vec{r}'$$
$$\vec{r}=\vec{v}\Delta{t}+\vec{r}'$$

##### Galileam transformation for position

$$ x = x' + v_{x} \Delta{t} $$

$$ y = y' + v_{y} \Delta{t} $$

$$ \frac{d \vec{r}}{dt} = \frac{d (\vec{v} \Delta{t})}{dt} + \frac{d \vec{r}'}{dt} $$

$$ \vec{v} = \vec{v} + \vec{v}' \quad ， v 為常數 $$

##### Galilean transformation for velocity

$$ v_x=v_x+v'_x$$

$$ v_y=v_y+v'_y$$

$$\frac{d\vec{v}}{dt}=0+\frac{d\vec{v}'}{dt}\Rightarrow \frac{d\vec{v}}{dt}=\frac{d\vec{v}'}{dt}$$

$$\vec{a}=\vec{a}'\Rightarrow\vec{F}=m\vec{a}=m\vec{a}'=\vec{F}' \space 力學問題一致$$

$$ 向量表示 \vec{AB}=\vec{AO}+\vec{OB} $$

EX: 當車速 50m/s 時，警察開槍射中搶匪車的輪胎，警察射出子彈速率 300m/s，求路邊觀察者拍到的子彈速率為何？

Sol: 

$$ \vec{v}_{彈地} = \vec{v}_{彈車} + \vec{v}_{車地} = 300 + 50 = 350(m/s) $$

#### Uniform Circular Motion  等速率圓周運動

- 週期(T):period

$$ v=\frac{2\pi{r}}{T} $$

- Angular position 角位置

1.degree度

$$ \theta=30^{。}, 120^{。} $$

2. revolution 轉 rev

$$ \theta \frac{11}{22}rev = 330^{。}，\space 1rev = 360^{。} $$

3. radiam 弧度： rad 為 SI 單位制

$$ \theta_{(rad)} \equiv \frac{S}{r} $$

- angular displacement 角位移

$$ \Delta \theta = \theta_f - \theta_i  $$

- angular velocity 角速度 ω

##### average velocitty 向量

$$ \vec{v}_{avg} \equiv \frac{\Delta\vec{r}}{\Delta\vec{t}} $$

##### speed 速率

$$ \vec{v}_{avg} \equiv \frac{\Delta S}{\Delta t} $$

##### 平均角加速度

$$ \omega_{avg} = \frac{\Delta \theta}{\Delta t} $$

$$ \omega= \lim_{\Delta t \to 0} \frac {\Delta \theta} {\Delta t}= \frac {d \theta} {dt}$$

SI 單位是： rad/s
常用單位：。/s, rev/s (rps) , rev/min (rpm)

#### 等速率圓周運動

$$ \omega_{avg} = constant $$

$$ \Delta\theta = \omega * \Delta{t} => \theta_f = \theta_i + \omega{\Delta{t}} $$

#### 解析模式 mapping

$$ \Delta S = v \Delta t \Rightarrow S_f = S_i + v \Delta t $$

- 加速度

$$ \vec{a} $$

$$ |\vec a| \equiv | \frac {d \vec v}{dt} | = \frac{vd \theta}{dt} = v * \omega = \omega^2r = \frac{v^2}{r} = \frac{4\pi^2r}{T^2} $$

以前實驗公式 ， 現在它是數學必然的結果

$$ a_c = \frac{v^2}{r} $$

EX: 輪盤 (C.C.W) 逆時針轉
直徑 30cm 球在 1.20 秒內完成 2.0 rev

a) 球之角速度
b) 球在 t= 2.05 之位置？

$$ \theta{i} = 0 $$

Sol: 

1 rev -> 0.60s

a)

$$ \omega = \frac{1rev}{0.60s} \times \frac{2\pi{rad}}{1rev} = \frac{2\pi}{0.60} rad/s = 10.47 rad/s $$

b)

$$ \theta_f = \theta_i + \omega * \Delta{t} = 0 + 10.47 \times 2.0 = 20.94(rad) \approx 21 (rad)\ $$

- Nonuniform Circular Motion
Angular Acceleration

$$ \vec{a} = \vec{a}_{\parallel}  + \vec{a}_\perp = \vec{a}_t + \vec{a}_c $$

tamgemtial acceleration

$$ |\vec{a}_\parallel| = a_t $$

radial acceleration

$$ |\vec{a}_{\perp}| = a_c = a_r  $$

$$ |\vec{a}| = \sqrt{a^2_t + a^2_c} $$

$$ a_t = \frac{dv_t}{dt} = \frac{d(r\omega)}{dt} = \frac{d\omega}{dt} = r\alpha $$

$$ a_t = r \alpha  $$

#### angular acceleration 角加速度

$$ \alpha \equiv \frac {d \omega }{dt} $$

#### 運動方程式

$$ v_f = vi + a_t\Delta{t} $$

$$ S_f = S_i + V_i \Delta{t} + \frac{1}{2} a_t \Delta t^2 $$

$$ v^2_f = v^2_i + 2a_t* \Delta S $$

$$ \Delta{S} = S_f - S_i $$

#### 圓周運動方程式

$$ \omega_f = \omega_i + \alpha\Delta{t} $$

$$ \theta _f = \theta _ t + \omega_i \Delta t + \frac {1} {2} \alpha \Delta t^2 $$

$$ \omega_f^2 = \omega_i^2 + 2 \alpha \Delta{\theta} $$

$$ \Delta{\theta} = \theta_f - \theta_i $$

EX: r = 2.0m

靜止開始時，a~t~=10 m/s^2^ t=10.0秒，燃料用盡

a) t = 2.0 秒 
$$ \vec{a} = ? $$

b) 燃料用盡時， ω = ?

![](https://cdn.discordapp.com/attachments/1152935463603142806/1156105612199997471/IMG_20230926_135007.jpg?ex=6513c2c1&is=65127141&hm=048b1006bd27a7401c404f94a4b405f4c855778b200709327906b29fe8e4b36c&)

$$ \theta_i = 0 $$

$$ a_t = 1.0 m/s $$

$$ \omega_i = 0 $$

$$ r = 2.0 m $$

$$ t_i = 0 $$

$$ t_f = 10.0 s $$

Sol:

a)

$$ \vec{a} = \vec{a_t} + \vec{a_c} $$

$$ | \vec{a}_c | = \frac {v^2_t} {r} = \frac {(2.0)^2} {2.0} = 2.0(m/s^2)$$

$$ v_t = a_t \Delta{t} = 1.0 \times 2.0 = 2.0 (m/s) $$

$$ |\vec{a}| = \sqrt{{a_t}^2 + {a_c}^2} = \sqrt{(1.0)^2 + (2.0)^2} = 2.2 (m/s^2) $$

b)

$$ v_t = 1.0 \times 10.0 = 10.0 (m/s) $$

$$ \omega _f = \frac{v_t}{r} = \frac{10.0}{2.0} = 5.0 (rad/s) $$

$$ \omega_f = 48 rpm $$

### Chapter 4 Newton's Laws of Motion

- Tone and Interaction
力和交互作用

使物體發生形變、運動方向速度改變
則物體受外力作用

力有三要素： 大小 方向 作用點

Drawing force vectors

長度(大小)、箭頭(方向)、起始點(作用點)

- net force (淨力)

- resultant force (合力)

$$ \vec{F}_{net} = \vec{F}_1 + \vec{F}_2 + ... + \vec{F}_n = \sum_{i=1} ^{N} \vec{F}_i $$ 

superposition of force 重疊原理

| Force    | Notation | 中文 |
| -------- | -------- | -------- |
| General Force | $$ \vec F $$ | 力 |
| Gravitational Force | $$ \vec{F}_G, \vec{F}_g$$ | 重力 |
| Spring Force | $$ \vec{F}_{sp} $$ | 彈力 | 
| Tensim | $$ \vec {T} $$ | 張力 | 
| Normal Force | $$ \vec {N}, \space \vec{n} $$ | 正向力 |
| Static friction | $$ \vec {f}_{s} $$ | 靜摩擦力 |
| kinetic friction | $$ \vec{f}_k $$ | 動摩擦力 |
| Drac Force | $$ \vec{D} $$ | 阻力 拖曳力 |
| Thrust | $$ \vec {F}_{thrust} $$ | 推力、驅動力 |
| Electric Force | $$ \vec {F}_{e} $$ | 電力 |
| Magnetic Force | $$ \vec{F}_B, \vec{F}_m $$ | 磁力 |

- Free-Body Diagrams 力圖

![](https://cdn.discordapp.com/attachments/1152935463603142806/1158230969631911946/IMG_20231002_103606.jpg?ex=651b7e26&is=651a2ca6&hm=45ca818a6221d7e3b17f5d384a5dba4b56be24c4aebb88cf4686ba6c7b1e7e31&)

- 四大交互作用 => Fundamental Forces

1. Graritation 重力交互作用 => gravitation force
2. Electroweak interaction 電磁力交互作用 => electornagnetic force 電磁力
3. strong interaction 強交互作用 => strong nuclear force
4. Weak interation 弱交互作用 => weak nuclear force

- 粒子
重力子
r 光子
g 膠子
w, z 波色子

上帝粒子
<iframe width="560" height="315" src="https://www.youtube.com/embed/q33ZpVvX-nk?si=zXkh1naDAp-3sK7i" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe> 

| 相對強度 | 作用範圍 |粒子|
| :----: | :----: |:----:|
| $$ 10^{-39} $$ | $$ \infty $$ | 重粒子 |
| $$ \frac{1}{137} $$ | $$ \infty $$ | r 光子 |
| $$ 1 $$ | $$ 10^{-15} $$ | g 膠子 |
| $$ 10^{-13} $$ | $$ 10^{-18}m $$ |w,z波色子|

- uncertainty principle
測不準原理

$$ \Delta{x} * \Delta{p} > h $$
$$ \Delta{E} = \Delta{p} * c, \Delta {E} = mc^2 $$
$$ \frac{\Delta{x}}{c} * \Delta{p} * c > h $$
$$ \Delta{t} = \frac{\Delta{x}}{c} = \frac{R}{C} $$
$$ \Delta{t} * \Delta{E} > h $$
$$ \frac{R}{C} * mc^2 \approx h $$
$$ R \approx \frac{h}{mc}  h\thicksim 10^{-34}$$

- 光子
$$ m = 0 $$
$$ R \approx \frac{10^{-34}}{0 \times 10^8} $$

- 動子
$$ m = 0 $$
$$ R \approx \frac{10^{-30}}{0 \times 10^8} $$

- 膠子
$$ m_\pi = \frac{1}{4}m_p \approx 10^{-27} $$
$$ R \approx \frac{10^{-3x}}{10^{-27} \times 10^8} = 10^{-15} (m) $$ 
 
- 波色子
$$ m_{wz} \approx 10^{-27} \times 10^{3} $$
$$ R \approx \frac {10^{-34}} {10^{-27} \times 10^{3} \times 10^{8}} \approx 10^{-18} (m) $$

##### 4.4 Mass, Weigh & Gravity

Mass (質量):
Intrinsic Propeoty 本質特性
$$ m_{地} = m_{月} = 60kg $$
$$ F = ma $$

Gravity: A Force
Newton's Law of gravity: 
$$ F_{12} = F_{21} = \frac{Gm_1m_2}{r^2} $$
$$ G = 6.67 \times 10^(-11) Nm^2 / kg^2 $$
r = R+h
$$ \vec{F}_{G} = ( \frac{GMm}{r^{2}}， \space \downarrow ) $$
$$ \vec{F}_{地表G} = ( \frac{GMm}{R^2}, \space \downarrow)$$
誤差 0.3%

![](https://cdn.discordapp.com/attachments/1152935463603142806/1158244182394155129/IMG20231002112803.jpg)

$$ mg = m\frac{GM}{R^2} => g = \frac{GM_地}{R^2_地} $$
gravitation field 重力場

$$ g_{地} = \frac{GM_{地}}{R_{地}^2}= \frac{6.67 \times 10^{-11} \times 5.98 \times 10^{24}}{(6.37 \times 10^6)^2} = 9.83 N/kg = 9.83 m/s^2 $$

扭秤實驗

- Weight: A Measurement 測量值

![](https://cdn.discordapp.com/attachments/1152935463603142806/1158245842038304830/IMG_20231002_113514.jpg)

$$ \because F_{sp} = F_G = mg $$
$$ W = mg $$

重量

EX:

![](https://cdn.discordapp.com/attachments/1152935463603142806/1158247688337379328/1696218160135.jpg)

$$ (F_{nut})_y = F_{sp} - F_G = ma $$

$$ W = F_{sp} \space 測量值 $$

1. a = 0 等速 
$$ w = F_G + ma = F_G = mg $$

2. a > 0 
$$ w = mg + ma = m(g + a) > mg $$

3. a < 0 
$$ w = mg - ma = m(g - a) < mg $$

4. a = -g
$$ w = mg - mg = 0 $$

##### 4.2 Newton's Laws

1687 Isaac Newton
Newton's 1st Law: the law of inertia 慣性定律
Newton's 2nd Law: 運動定律 $$ \vec{F} = m \vec{a} $$
Newton's 3rd Law: 作用力與反作用力 $$ \vec{F}_{12} = -\vec{F}_{21} $$

- primary units: kg, m, s
基本量

secondary units: N
導出量

##### 4.3 Newton's Second Law

虛擬實驗

$$ \vec{a} = \frac{\vec{F}_{rut} }{m} $$

力單位：N

$$ 1N = 1kg * 1m/s^2 = 1 * kg * m/s^2 $$

物體受合力 != 0 時沿合力方向產生一個加速度

$$ V = IR, R = \frac{V}{I} $$

所有電器的電阻值都是定值

- Newton's 1st Laws

物體合力為 0

$$ \vec{F}_{net} = 0 $$

靜者恆靜，動者恆做等速度運動。

- Mechanical equilibrium 力學平衡

1) Static equilibrium: at rest 靜止
靜態

2) Dynamic equilibrium:uniform
動態

- 1'st Law : 完備力的定義

$$ \vec{F}_{net} = 0 $$
natural state 自然狀態 1st

$$ \vec{F}_{net} \ne 0 $$
物體狀態改變 2nd

By Nt's 1st Law

$$ (F_{net})_x = \sum_{i} (F_i)_x = 0 $$

$$ (F_{net})_y = \sum_{i} (F_i)_y = 0 $$

By Nt's 2nd Law:

$$ (F_{net})_x = \sum_i (F_i)_x = ma_x $$

$$ (F_{net})_y = \sum_i (F_i)_y = ma_y  $$

- Newton's 3rd Law

兩物體之間有交互作用的概念

$$ \vec{F}_{AB} = action force (作用力) $$

$$ -\vec{F}_{BA} = reaction force (反作用力) $$

$$ (\vec{F}_{AB} = -\vec{F}_{BA}) = action pair$$

大小相等，方向相反，同時產生，不能抵消(作用點不同)

![](https://cdn.discordapp.com/attachments/1152935463603142806/1158638912944746496/IMG_20231003_133704.jpg)

- Ropes & Pulleys 繩和滑輪組

Massless String Approximation 弦線無質量近似 (M.S.A)

C.S.

![](https://cdn.discordapp.com/attachments/1152935463603142806/1158639832113881119/IMG_20231003_134054.jpg)

$$ F = (m_A + m_B)a, \space a = \frac{F}{m_A + m_B} $$

![](https://cdn.discordapp.com/attachments/1152935463603142806/1158640493635313685/IMG_20231003_134330.jpg)

$$ T_{BS} - T_{AS} = m_sa $$

$$ T_{BS} = T_{AS} + m_sa $$

$$ T_{BS} > T_{AS} \space 稱為 \space M.S.A $$

$$ 當 \space m_s \rightarrow 0 \quad T_{BS} = T_{AS} = T $$

EX: Atwood Machine 阿特伍德

![](https://cdn.discordapp.com/attachments/1152935463603142806/1158641917660237824/IMG_20231003_134908.jpg)

(M.S.A),
$$ m_p \approx 0 $$  
滑輪質量
$$ 求 \space \vec{a} = ? $$

Sol: 

$$ 假設 \space m_1 > m_2 $$

![](https://cdn.discordapp.com/attachments/1152935463603142806/1158644535858040832/IMG_20231003_135920.jpg)

$$\begin {cases} 
m_1 g - T = m_1 a \\
T- m_2 g = m_2 a
    \end {cases}$$

$$ (m_1 - m_2)g = (m_1 + m_2)a $$

$$ a = \frac{m_1 - m_2}{m_1 + m_2}g $$

$$ \vec{a} = ( \frac{m_1 - m_2}{m_1 + m_2}g, m_1 \downarrow) $$

$$ 反之 \space m_1 < m_2  $$

$$ \vec{a} = (\frac{m_2 - m_1}{m_1 + m_2}g, m_1 \uparrow) $$

$$ m_1 = m_2, \vec{a} = 0 $$

- force multiplier 力的倍增器

![](https://cdn.discordapp.com/attachments/1152935463603142806/1158644536071962684/IMG_20231003_135930.jpg)

左 F = 60 kgw
右 F = 40 kgw
3F = 120 kgw
F = 40 kgw

![](https://cdn.discordapp.com/attachments/1152935463603142806/1163301234522984531/IMG_20231016_102330.jpg)

### Chapter 6 Work and Energy 功與能

- 能量的形式：
光 熱 電 磁 聲 力學能 化學能 核能 E=mc^2^

C.S.

free fall

$$ V_{yf} = V_{yc} + g\Delta{t} $$
$$ y_{f} = y_{i} + V_{yi}\Delta{t} - \frac{1}{2}g\Delta{t}^2$$
$$ V_{yf}^2 = V_{yi}^2 - 2g\Delta{y} $$
$$ \Delta{y} = y_f = y_i $$

$$ V_{yf}^2 = V_{yi}^2 - 2g(y_f - y_i) $$

$$ V_{yf}^2 + 2gy_f = V_{yi}^3 + 2gy_i $$
$$ P_1V_1 =P_1V_2 = ... $$ 

$$ V_y^2 + 2gy_f = constant $$
恆等式 Conservation Law 等恆律

#### from Nt's 2nd Law for 1-D free fall y-axis

![](https://cdn.discordapp.com/attachments/1152935463603142806/1163311689832345620/IMG_20231016_110503.jpg)

$$ (F_{net})_{y} = ma_{y} = -mg $$

$$ => ma_y = -mg $$

$$ a_y = \frac{dV_y}{dt} = \frac{dV_y}{dy} \frac{dy}{dt} $$

$$ mV_y \frac{dV_y}{dt} = -mg $$

$$ \int_{V_yi}^{V_yf} mV_ydV_y = \int_{yi}^{yf} -mgdy $$

$$ \frac{1}{2} mV_y^2 |_{Vyi}^{Vyf} = -mg y|_{y_i}^{y_f} $$

$$ \frac{1}{2} mV_{yf}^2 - \frac{1}{2} mV_{yi}^2 = -mgy_f + mgy_i $$

$$ \frac{1}{2} mV_{yf}^2 + mgy_f = \frac{1}{2} mV_{yi}^2 + mgy_i $$

$$ k = \frac{1}{2} mv_y^2 \space 動能 \space kinetic \space energy $$

$$ U_g = mgy_f \space 重力位能 \space gravitation \space potental \space energy $$

$$ k + U = Emech \space mechanical \space energy $$

$$ \Delta E_{mech} = 0 = \Delta k + \Delta U $$

law of conserVation of mechincal emergy 力學能守恆

#### Work

![](https://cdn.discordapp.com/attachments/1152935463603142806/1163311689555517470/IMG_20231016_110445.jpg)

- by Nt's Law $F_s$ component (分量)

$$ (F_{net})_s = ma_s = F_s $$

$$ ma_s = Fs $$

$$ a_s = \frac{dV_s}{dt} = \frac{dV_s}{ds} \frac{ds}{dt} = V_s \frac{dV_s}{ds} $$

$$ mV_s \frac{dV_s}{ds} = F_s $$

$$ \int_{V_{si}}^{V_{sf}} mV_s dV_s = \int_{si}^{sf} F_s ds $$

$$ \frac{1}{2} mV_{sf}^2 - \frac{1}{2} mV_{si}^2 = \int_{si}^{sf} F_s ds $$

F~s~ 不是定力
動能變化

$$ \Delta{K} = \frac{1}{2}mv_{sf}^2 - \frac{1}{2}mv_{si}^{2}$$

$$ W \equiv \int_{si}^{sf} F_s ds = \int_{si}^{sf} F ds \space cos\theta $$

![](https://cdn.discordapp.com/attachments/1152935463603142806/1163316163082731530/1697426573356.jpg)

$$ W = \int_{s_{f}}^{s_{si}} \vec{F}d\vec{s}$$

單位：

$$ 1Nm = 1 \times kg \times m/s^2 \times m = 1 \times J $$

$$ 1J = 1 kgm^2/s^2 \space 能量 $$

$$ K = \frac{1}{2}mv^{2} => 1kgm^2/s^2 = 1J$$

$$ \Delta{k} = w $$

功 - 動能原理 Work-kinetic energy theorem

- F 為定力

$$ W = \int_{si}^{sf} \vec F d\vec s = \vec F \int_{si}^{sf} d\vec s $$

$$ W = \vec{F}\Delta{\vec{s}} $$

$$ W = F_s \Delta s = F \Delta s \space ws \theta $$

Cs. 重力做功

$$ \vec{F} = -mg\hat{j} $$

$$ d\vec{s} = dx\hat{i} + dy\hat{j} $$

$$ dW_{grav} = \vec{F} d\vec{s} $$

$$ \int dw_{grav} = \int^f_{y_i} -mgdy $$

$$ W_grav = -mg \int_{yi}^{yf} dy = -mg \Delta y = - \Delta U $$

![](https://cdn.discordapp.com/attachments/1152935463603142806/1163319146298220604/1697427257229.jpg)

重力做功和所行路徑無關
保守力作功(Conservative force)和所行路徑無關

![](https://cdn.discordapp.com/attachments/1152935463603142806/1163323094631456828/1697428229092.jpg)

1. 作功所行路徑無關 $W_1 = W_2$

2. 沿一封閉路徑保守力做功為 0

i -> f -> i $W_1 - W_2 = 0$

3. 保守力可定義出相應之位能

判斷原則：F 只有位置有關




$$ F = - kx \rightarrow U_sp = \frac{1}{2}kx^2 $$

$$ F = -mg \rightarrow U_{g} = mgy $$

$$ F = \frac{GMm}{r^{2}} \rightarrow U = \frac{GMm}{r}$$

$$ F = \frac{kQq}{r^2} \rightarrow U = \frac{kQq}{r} $$

$$ F=qvB \space X $$

Nonconservative force 非保力 
<!-- 可是她叫我寶... -->

![](https://cdn.discordapp.com/attachments/1152935463603142806/1163322416836120637/1697428056675.jpg)

1. 作功和所行路徑有關

2. 沒有對應之位能

$$ H = T + V, L = T - V $$

C.S. 一系統內物體之交互作用，同時有保守力和非保守力

W~c~ : 保守力作功
W~nc~ : 非保守力作功

$$ W_{?t} = W_n + W_{nc} $$

由功 動能原理

$$ \Delta{k} = W_{net} = W_n + W_{nc} $$

由
$$ W_{n} = -\Delta{U}$$

$$ \Delta k = -\Delta U + W_{nc} $$

$$ \Delta k + \Delta U = W_{nc} $$

if $W_{nc} \Rightarrow \Delta k + \Delta U = 0$ 力學能守恆

### Restoring/Spring Force & Hook's Law

彈力(恢復力)使系統回到平衡位置之力
elastic:彈性系統能表示出恢復力的??
你剛要說啥直接打在這邊 
我也不知道

Hook Laws: 
$$ (\vec{F})_{sp} = -k \Delta{S}$$

$$ \Delta{S} = S_f - S_e = S $$

By Nt's 2^nd^ Law
$$ (\vec{F}_{mt})_s = ma_s m\frac{dv_s}{dt} = m \frac{dv_s}{ds} \times \frac{ds}{dt} = mv_s \frac{dv_s}{ds} = -k \Delta{s} $$

$$ mv_s \frac{dv_s}{ds} = -k \Delta{S} => \int_{V_{si}}^{V_{sf}}mv_sdv_s = -\int_{Si}^{Sf}k \Delta{S}ds = - $$

$$ \frac{1}{2}mv_{sf}^2 + \frac{1}{2}k(s_f - s_e)^2 = \frac{1}{2} mv_{si}^2 + \frac{1}{2} k(s_i-s_e)^2$$

$$ K = \frac{1}{2}mv_s^2$$

$$ K_f + U_{spf} = K_i + U_{spi} $$

$$ K + U_{sp} = const $$

$$ E_{mach} = K + U_{sp} \space is \space conserved $$

#### Impluse & Momentum 衝量和動量

![](https://cdn.discordapp.com/attachments/1152935463603142806/1165842414750146641/IMG_20231023_104043.jpg)

collision 碰撞
duration 時間區間
impulsive force 衝力 F(t)

By Nt's 2^nd^ Law

$$ F(t) = ma_x = m \frac{dv_x}{dt} = mv_x \frac{dv_x}{dx}   = m \frac{d^2x}{dt^2}$$

$$ m \frac{dv_x}{dt} = F(t)$$

$$ \int^{v_{xf}}_{v_{xi}} mdv_x= \int^{t_f}_{t_i}F(t)dt  $$

$$ mv_{xf} - mv_xi = \int^{t_f}_{t_i} F(t) dt$$

![](https://cdn.discordapp.com/attachments/1152935463603142806/1165842778727657522/1698028965314.jpg)

#### Momentum

$$ \vec P \equiv m \vec v $$

linear momentum 線動量

$P_x = mv_x$
$P_y = mv_y$

$$ \vec F = m \vec a = m\frac{d\vec v}{dt} = \frac{d(m \vec v)}{dt} = \frac{d\vec P}{dt} $$

$$ \vec F = \frac{d\vec P}{dt} = \frac {d(m\vec v)}{dt} = (\frac{dm}{dt})\vec v + m \frac{d\vec v}{dt} = (\frac{dm}{dt})\vec v + m \vec a $$

$$ \Delta{P_x} = P_{xf} - P_{xi} = \int^{tf}_{ti} F(t)dt $$

$$ J_x \equiv \int^{t_f}_{t_i} F(t)dt = \space F(t)vs圖曲線下面的面積 $$

$$ J_x = F_{avg} \Delta t $$

![](https://cdn.discordapp.com/attachments/1152935463603142806/1165846440568967229/1698029834162.jpg)

$$ \Delta P_x = J $$ 
impulse-momentum theorem 衝動量原理

- Momentum Bar Charts ： 動量長條圖

![](https://cdn.discordapp.com/attachments/1152935463603142806/1165851503471382611/1698031043678.jpg)

[![]()](https://cdn.discordapp.com/attachments/1152935463603142806/1165851503039348756/1698031037370.jpg)

$$ P_{xf} = P_{xi} + J $$

### Conservation of Momentum 動量等恆

Nt's 2nd Law impuilse - monentum
Nt's 3rd Law => 等恆律

$$ \vec{F}_{AB} + \vec{F}_{BA} = 0 $$

$$ \vec F_{AB} = \frac{(d\vec P)_B}{dt} = m_B \vec a_B $$

$$ \vec{F}_{BA} = \frac{(d \vec p)_A}{dt} = m_A \vec{a}_A $$

$$ \frac{d\vec P_B}{dt} + \frac{d\vec P_A}{dt} = 0 $$

$$ \frac{d}{dt}(\vec P_B + \vec P_A) = 0 $$

$$ \vec P_A + \vec P_B = const \space 動量守恆 $$

$$ \vec{P}_{Af} + \vec{P}_{Bf} = \vec{P}_{Ai} + \vec{P}_{Bi} $$

力學能守恆 $K+U_g = Emech$
功動能原理 $W = \Delta K$
力學能守恆 $K + U_{sp} = Emech$
衝動量原理 $J = \Delta p$
動量守恆　 $\frac{d\vec P}{dt} = 0 ，\vec P = winst，\vec P_f = \vec P_i$

### Power 功率
W=1N*1W=1J(1s) 
  1N*1W=1J(1天)

平均 $P = \frac{\Delta W}{\Delta t}$
瞬時 $P = \lim_{\Delta t to 0} \frac{\Delta W}{\Delta t}$

單位:瓦特(watt) 1W=1J/s=1kgm^2^/s^3^
1N = 1kgm/s^2^
1J = 1kgm^2^/s^2^
1W = 1kgm^2^/s^3^

英制單位:馬力(hasepuwer hp)
1hp = 746N

$W =\int \vec{F}*d\vec{s}$

$dw = \vec{F}d\vec{s}$

$P = \frac{dw}{dt} = \frac{\vec{F}d\vec{s}}{dt} =\vec{F}\vec{v}_s$
$P = Fv_s cos\theta$

- 一種能量的新單位 仟瓦一小時(kwh)=度
$1kwh = 1000 \times 3600 = 3.6 \times 10^6(J)$

### Finding Force from potential Energy
c.s

$dW = F_s dW$

保守力 $dW = -dU$

![](https://cdn.discordapp.com/attachments/1152935463603142806/1168373849889452032/IMG_20231030_102012.jpg)

比較 $F_sds=-du$
$F_s=-\frac{dU}{ds}$

![](https://cdn.discordapp.com/attachments/1152935463603142806/1168373861717377095/1698632396197.jpg)

EX: $Ug = mgy \rightarrow F_y = - \frac{dU}{dy} = -mg$ 重力

$U_{sp} = \frac{1}{2}kx^2 \rightarrow F_x = - \frac{dU}{dx} = -kx$ 彈力

$U_g = \frac{GMm}{r} \rightarrow F_g = - \frac{dU}{dr} = -\frac{GMm}{r^2}$ 萬有引力

C.S. $U=U (x, y, z)$

$$ F_x = -\frac{\partial U}{\partial x}, F_y = -\frac{\partial U}{\partial y}, F_z = -\frac{\partial U}{\partial z} $$

$\partial$ partial 偏微

$$ \vec{F} = (-\frac{\partial U}{\partial x})\hat{i} + (-\frac{\partial U}{\partial y})\hat{j} + (-\frac{\partial U}{\partial z})\hat{k} $$

Ex:
$U = x^2y + y^3 + xz^2$
求$\vec{F}$

Sol:
$$ F_x = -\frac{\partial U}{\partial x} = -(2xy + 0 + z^2) $$

$$ F_y = -\frac{\partial U}{\partial y} = -(x^2 + 3y^2 + 0) $$

$$ F_z = -\frac{\partial U}{\partial z} = (0 + 0 + 2xz) $$

$$ \vec F = -(2xy + z^2)\hat i -(x^2 + 3y^2)\hat j -(2xz)\hat k $$

EX: Molecular Force  分子力

Lennard-Jones Potential (L-J 勢)

$$ U(x) = 4U_0 [(\frac{x_0}{x})^{12} - (\frac{x_0}{x})^6] $$

$U_0 : constom \space energy$
$X_0 : constom \space length$

Find $\vec F$ = ?

Sol:

(1)

$$ F_x = - \frac{dU}{dx} = -4U_0[x_0^{12} \frac{d}{dx}(x^{-12}) - x_0^6 \frac{d}{dx}(x^{-6})] $$
$$ = -4U_0[x_0^{12}(-12x^{-13}) - x_0^6(-6x^{-7})] $$
$$ = \frac{24JU_0}{x_0}[2(\frac{x_0}{x})^{13} - (\frac{x_0}{x})^7] $$

(2)
在 $x=?$ potential 有 min

![](https://cdn.discordapp.com/attachments/1152935463603142806/1168381850864070686/IMG_20231030_105211.jpg)

由 (1) 知 min 發生在

$$ \frac{dU}{dx} = 0 ，\space 2(\frac{x_0}{x})^{13} - (\frac{x_0}{x})^{7} = 0  $$
$$ 2(\frac{x_0}{x})^6 = 1 $$
$$ x = \sqrt[6]{2}x_0 $$

### Collision 碰撞

(1) Inelastic collision: 非彈性碰撞

![](https://cdn.discordapp.com/attachments/1152935463603142806/1168382527673745418/IMG_20231030_105451.jpg)

$\vec P$ 守恆, $\vec E$ 不守恆
最後$m_1 \space m_2$結合在一起，perfectly非彈性碰撞

(2) elastic collision: 彈性碰撞

![](https://cdn.discordapp.com/attachments/1152935463603142806/1168383192319934485/IMG_20231030_105732.jpg)

$\vec P$ 守恆, $\vec E$ 守恆

(1) 完全非彈性碰撞 $\vec P_i = \vec P_f$

$$ m_1 \vec v_{xi1} + m_2 \vec v_{xi2} = (m_1 +m_2)\vec v_{xf} $$

1-D

$$ V_{xf} = \frac{m_1 v_{x1} + m_2 v_{x2}}{m_1 + m_2} $$

$$ U = -\frac{GMm}{Y} \Rightarrow \vec F_g = - \frac{dU}{dr} = \frac{GMm}{r^2} $$

(2) 彈性碰撞 + - 吸收至 $V_{xi1}，V_{xi2}...$

P 守恆: $m_1v_{xi1} + m_2v_{xi2} = mv_{xf1} + mv_{xf2}$-1

E 守恆: $\frac{1}{2} m_1v^2_{xi1} + \frac{1}{2} m_2v^2_{xi2} = \frac{1}{2} m_1v^2_{xj1} + \frac{v}{2} m_2v^2_{xf2}$ －2

由 2 式整理

$$ m_1(v_{xi1}^2 - v_{xf1}^2) = m_2((v_{xf2}^2 - v_{xi2}^2) $$

$$ m_1(v_{xi1} + v_{xf1})(v_{xi1} - v_{xf1}) = m_2(v_{xf2} + v_{xi2})(v_{xf2} - v_{xi2}) $$

由 1 式

$$ m_1v_{xi1} - m_1v_{xf1} = m_2v_{xf2} - m_2v_{xi2} $$
$$ \Rightarrow v_{xi1} + v_{xf1} = v_{xi2} + v_{xf2} $$
$$ v_{ax1} - v_{xi2} = v_xf2 - v_{xf1} $$ －3

$$ v_{xi1} - v_{xi2} = -(v_{xf1} - v_{xf2}) $$

碰撞前的速度差 = 碰撞後的速度差負值

由 1, 3 式，解 $v_{xf1}, v_{xf2}$

$$ v_{xf1} = \frac{m_1 - m_2}{m_1 m_2} v_{xi1} + \frac{2m_2}{m_1 + m_2} v_{xi2} $$

$$ v_{xf2} = \frac{2m_1}{m_1+m_2} v_{xi} + \frac{m_2-m_1}{m_1+m_2} v_{xi2} $$

C.S. $v_{xi2} = 0$

1. Case $m_1 >> m_2 \space 10^3$

$$ v_{xf1} = \frac{m_1 - m_2}{m_1 + m_2} v_{xi1} \approx v_{xf1} $$
$$ v_{xf2} = \frac{2m_1}{m_1 +m_2} v_{xf1} \approx 2v_{xf1} $$

2. Case $m_1 << m_2 \space 10^{-3}$

$$ v_{xf1} = \frac{m_1 - m_2}{m_1 + m_2} v_{xi1} \approx -v_{xi1} $$
$$ v_{xf2} = \frac{2m_1}{m_1 +m_2} v_{xf1} \approx 0 $$

3. Case $m_1 \approx m_2$

$$ v_{xf1} = \frac{m_1 - m_2}{m_1 + m_2} v_{xi1} = 0 $$

$$ v_{xf2} = \frac{2m_1}{m_1 +m_2} v_{xf1} = v_{xi1} $$

before

![](https://cdn.discordapp.com/attachments/1152935463603142806/1168398090231885884/IMG_20231030_115608.jpg)

兩邊可以一起拍
有拍嗎？

P 守恆

$$ p_{xf1} + p+{xf2} = p_{xi1} + p_{xi2} $$

$$ p_{yf1} + p_{yf2} = p_{yi1} + p{yi2} $$

x:
$$ mv_{i1} + 0 m_1v_{f1}cos\theta + m_2v_{f2}cos\phi $$

y:
$$ 0 + 0 = m_1v_f\sin\theta + m_2v_{f2}\sin\phi  $$

if elastic

$$ \frac{1}{2}m_1v_i^2 + 0 = \frac{1}{2}m_1v_{f1}^2 + \frac{1}{2}m_2v_{f2}^2 $$

EX:

![](https://cdn.discordapp.com/attachments/1152935463603142806/1168398098171707513/IMG_20231030_115634.jpg)!

Sol:

$$ m_cv_{xoc} + m_{vn}v_{x0vw} = (m_c + m_{vw}) v_1 \cos\theta $$
$$ 0 + 1000 v_{x0vw} = (3000)v_1\cos{35}度 $$
－1

$$ m_cv_{y0c} + m_{vw}v_{y0vw} = (m_c+m_{vw})v_1 sin\theta$$
2000

![](https://cdn.discordapp.com/attachments/1152935463603142806/1168398629996871680/IMG_20231030_115850.jpg)

### 8.5 Center of Mass (C.M.)
particle其質量$m_i$ position ($x_i,y_i$)

$x_{cm} = \frac{m_1 x_1 + m_2 x_2+...+m_n x_n}{m_1+m_2+...+m_n} = \frac{1}{M} \displaystyle\sum_{i=1}^{n} m_i x_i$

$y_{cm} = \frac{m_1 y_1+m_2 y_2+...+m_n y_n}{m_1+m_2+...+m_n} =\frac{1}{M} \displaystyle\sum_{i=1}^{n}{m_i y_i}$

![](https://cdn.discordapp.com/attachments/1152935463603142806/1173455391548522626/IMG_20231113_105225.jpg)

Sol

$$ x_{cm} = \frac{2.0 \times 0 + 0.50 \times 0.50}{2.00 + 0.50} = 0.10 (m) $$

#### Realistic object , continuous body

![](https://cdn.discordapp.com/attachments/1152935463603142806/1173456103091212379/IMG_20231113_105526.jpg)

$x_{cm} = \displaystyle\lim_{\Delta m \rightarrow 0} \frac{1}{M}\sum_{i}{x_i}\Delta m=\frac{1}{M}\lim_{\Delta m ->0}\sum_{i}\Delta m = \frac{1}{M}\int{xdm}$

$x_{cm} = \frac{1}{M} \int xdm$
$y_{cm} = \frac{1}{M} \int ydm$

EX
![](https://cdn.discordapp.com/attachments/1152935463603142806/1173457954285035632/IMG_20231113_110247.jpg)

Sol

$\lambda = \frac{M}{L} \space 總密度$

$\sigma = \frac{M}{A} \space 面密度$

$\rho = \frac{M}{V} \space 體密度$

$x_{cm} = \frac{1}{M}\int_{0}^{L} xdm = \frac{1}{M} \int_{0}^{L} x \lambda dx = \frac{\lambda}{M} \int_{0}^{L} xdx = \frac{\lambda}{M} \frac{x^2}{2} |_{0}^{L} = \frac{\lambda}{M} \frac{L^2}{M} = \frac{\frac{M}{L}}{M} \frac{L^2}{M} = \frac{L}{2}$


#### Center-of-Mass Momentum
Position vector of c.m
$\vec{R}=\frac{1}{M}\sum_{i=1}^{n}{m_i \vec{r_i}}$

$\vec{V}=\frac{d\vec{R}}{dt} = \frac{1}{M}\sum_{i=1}{n}$

$\vec{P_c} \equiv M \vec V = \displaystyle \sum_{i=1}^{n} \vec{P_i}$

$\frac{d \vec{P_c}}{dt} = \frac{d(M \vec v)}{dt} = \displaystyle \sum_{i=1}^{n} \frac{d \vec{P_i}{dt}$

$\vec{F_{net}} = \displaystyle\sum_{i=1}^{n} \vec{F_i}$
superposition

### Rotation 轉動
物體視為Rigid body 剛體
$s = r \theta$
$v_t = r \omega$
$a_t = r \alpha$
$a_c = \frac{v^2}{r} = rw^2 = \frac{4\pi ^2r}{T}$
$a = \sqrt{a_t^2 + a_c^2}$
(ccm)counteclockwise 逆時針方向 (+)
(cw)clockwise 順時針方向 (-)

轉動動能

![](https://cdn.discordapp.com/attachments/1152935463603142806/1173465353070858300/IMG_20231113_113209.jpg)

$k_{rot} = \frac{1}{2} m_1 v_1^2 + \frac{1}{2}m_2 v_2^2 +...$

$k_{rot} = \frac{1}{2} m_1 r_{1\perp}^2 \omega^2+....=\frac{1}{2}(m_1 r_{1\perp}^2+...)\omega^2=\frac{1}{2}{\sum_{i=1}{m_ir_{i\perp}}^2}\omega^2=\frac{1}{2}I\omega^2$


I：轉動慣量

$I \equiv \displaystyle \sum_{i} m_i r_{prep}^2$

$\vec P = m \vec v \rightarrow \vec L = I \vec\ \space 角動量$

$\vec F = \frac{d \vec P}{dt} \rightarrow \vec\tau = \frac{d \vec L}{dt}$

$\vec F = m \vec a \rightarrow \vec\tau = I \vec d \space 力矩$

### 連續體 
$\displaystyle I = \sum_{i = 1}{m_i}r_{i \perp}^2 \rightarrow I = \int r^2_{\perp} dm$

#### Parallel-Axis Theorem 平行軸原理

![](https://cdn.discordapp.com/attachments/1152935463603142806/1173469192922599434/IMG_20231113_114728.jpg)

$I = I_{cm} + Md^2$

![](https://cdn.discordapp.com/attachments/1152935463603142806/1173469703251972136/IMG_20231113_114930.jpg)

![](https://cdn.discordapp.com/attachments/1152935463603142806/1173470206304202782/IMG_20231113_115129.jpg)

Ex

![](https://cdn.discordapp.com/attachments/1152935463603142806/1173853545494229002/IMG_20231114_131429.jpg)

$\lambda = \frac{M}{L}$

$I = \int_0^L x^2 dm = \int_0^L x^2 \lambda dx = \lambda \int_0^L x^2 dx = \lambda \frac{x^3}{3} |_0^L = \frac{M}{L} \frac{L^3}{3} = \frac{1}{3} ML^2$

另法: $I_{cm}=\frac{1}{12}ML^2$
$I=I_{cm}+M(\frac{L}{2})^2=\frac{1}{12}ML^2=\frac{4}{12}ML^2=\frac{1}{3}ML^2$

EX:

![](https://cdn.discordapp.com/attachments/1152935463603142806/1173855054315401287/IMG_20231114_132045.jpg)
 
半徑 $R$ 質量 $M$ 均勻 求已圓心為軸之 $I = ?$
$\sigma = \frac{M}{\pi R^2}$面密度
$I = \int r_{\perp}^2 dm$

$da =  2 \pi rdr$
$dm = \sigma da$
$dm = \sigma 2 \pi rdr$


$I = \int_0^r r^2 dm$
$I = \int_0^r \sigma 2\pi dr$
$= 2 \pi \frac{M}{\pi R^2} \frac{r^4}{4} \int_0^R$
$= \frac{1}{2} MR^2$

EX:

![](https://cdn.discordapp.com/attachments/1152935463603142806/1173857611876159498/IMG_20231114_133050.jpg)

$\rho = constant$ 均勻

hollow cylinder
 中空    圓柱

求

$M =$
$I =$

Sol:
$M=\int \rho dv = \rho \int dv$

柱座標 $dV = rdrd\phi dz$

$$ M = \rho \int^{2 \pi}_{0} \int^{h}_0 \int^{R_2}_{R_1} rdrd\phi dz $$
$$ = \rho [\int_0^2\pi d\phi][\int_0^h dz][\int_R1^R2 rdr] $$
$$ = \rho 2\pi h \frac{1}{2}(R_2^2 - R_1^2) $$
$$ = \rho \pi h(R_2^2 - R_1^2) $$

![](https://cdn.discordapp.com/attachments/1152935463603142806/1173858910017441833/IMG_20231114_133602.jpg)

$$ I = \int{r}_2^2 dm = \int r^2 \rho dv$$
$$ = \rho \int r^2 rdrd\phi dz $$
$$ = \rho \int_0^{2\pi} \int_0^h \int _{R_1}^{R_2} r^3 drd\phi dz $$

$$ I  = \rho 2\pi h \int^{R_2}_{R_1} r^3dr $$
$$ = \rho 2\pi h \frac{r^4}{4} |_{R1}^{R2} $$
$$ = \frac{1}{2} \rho \pi h (R^4_2 - R^4_1) $$
$$ = \frac{1}{2} \frac{M}{\pi h(R^2_2 R^2_1)} \pi h(R^2_2 R^2_1)(R^2_2 + R^2_1) $$
$$ = \frac{1}{2} M(R^2_2 + R^2_1)$$


Ex:

$(x, y) \rightarrow (r, \theta)$
$(x, y, z) \rightarrow (r, \theta , \phi)$

$M$，$R$，均勻
求 $I = ?$

![](https://cdn.discordapp.com/attachments/1152935463603142806/1173862436865056868/IMG_20231114_135002.jpg)

![](https://cdn.discordapp.com/attachments/1152935463603142806/1173863056346988554/IMG_20231114_135233.jpg)

$$ dV = dr\space rd\theta r_{\perp} d\phi $$
$$ r^2\sin\theta drd\theta d\phi $$

$$ I = \int r^2_{\perp}dm = \int r^2_{\perp} \rho dv $$
$$ = \rho \int_0^{2\pi} \int_0^\pi \int_0^R r^2\sin\theta drd\theta d\phi $$
$$ = \rho [\int_0^{2\pi}d\phi][\int_0^{\pi}sin^3 \theta d\theta][\int_0^R r^4 dr] $$
$$ =\frac{M}{\frac{4}{3} \pi R^3} 2\pi \frac{4}{3} \frac{R^5}{5} = \frac{2}{5}MR^2 $$

### Rolling Motion 滾動

![](https://cdn.discordapp.com/attachments/1152935463603142806/1175985040103059527/IMG_6415.jpg)

$\Delta x_{cm}=v_{cm}\Delta t=2\pi R$
$\Delta t=T$
$V_{cm}T=2\pi R$
$V_{cm} = \frac{2 \pi R}{T}=\omega R$
$\omega =\frac{2\pi}{T}$

![](https://cdn.discordapp.com/attachments/1152935463603142806/1175985040388276284/IMG_6416.jpg)

移動 + 轉動 = 滾動
translation + rotation = rolling motion

### kinetic Energy of a rolling object

$$ K_{roll}=\frac{1}{2}I_p\omega^2=\frac{1}{2}(I_{cm}+MR^2)\omega^2=\frac{1}{2}(\frac{1}{2}MR^2+MR^2)\omega^2=\frac{1}{2}(\frac{3}{2}MR^2)\omega^2 $$

EX 10.5 M 誰最先到地面？

![](https://cdn.discordapp.com/attachments/1152935463603142806/1175987414569865388/IMG_6417.jpg)

| 英文      | 中文 | Icm    |
| -------- | ---- | ------ |
| Hoop     | 鐵環 | $MR^2 |
| Cylinder | 圓柱 | $\frac{1}{2}MR^2$ |
| Sphere   | 球   | $\frac{2}{5} MR^2$ |
| Particle | 質點 | $?$ |

$$ Icm = cMR^2 $$

sol: $E_f=U_i$ 能量守恆$V_{cm}=R\omega$
$Mgh=\frac{1}{2}I_{cm}\omega^2+frac{1}{2}MR^2\omega^2=\frac{1}{2}I_{cm}\omega^2+\frac{1}{2}mV_{cm}^2=\frac{1}{2}cMR^2\omega^2+\frac{1}{2}MV_{cm}^2=\frac{1}{2}(c+1)MV^2_{cm}$

$$ V_{cm} = \sqrt{\frac{2gh}{c+1}} $$
$$ v^2 = v_0^2 + 2a \Delta x $$
$$ \frac{2gh}{c+1} = 2a\frac{h}{sin\theta} $$
$$ a = \frac{g\sin \theta}{c+1} $$

$$ \Delta x = \frac{h}{\sin \theta} $$

### Torgue 力矩

移動中 $\vec{F} = m\vec{a}$
滾動中 $\vec{\tau} = I \vec{\alpha}$

虛擬實驗:

![](https://cdn.discordapp.com/attachments/1152935463603142806/1175991477113979000/IMG_6418.jpg)

結果：
1. $\tau \alpha F$
2. $\tau \alpha r$(力臂)
3. $\tau \alpha sin\theta$

$\tau = rF\sin\theta\rightarrow\vec{\tau}=\vec{r}\cross\vec{F}$
$\vec{\tau}_{rat} = \sum_i \vec{\tau_i}$
$y = kx$

### Gravitationalitationalitational Torgue
C.S. 重力作用在一物體上所產生的力矩

![](https://cdn.discordapp.com/attachments/1152935463603142806/1176000170429792376/IMG_6420.jpg)

(c.c.w)$\tau_1 = +m_1gd_1$
(C.W) $\tau _2 = -m_2gd_2$

$$ \tau_1 = -m_1gx_1$$

$$ \tau_2 = -m_2gx_2 $$

$$ \tau_i = -m_igx_i $$

$$ \vec{\tau_{net}} = \sum_i m_i gx_i = (\sum_i m_ix_i) = MX_{cm} $$

$$ \tau_{net} = -MgX_{cm} $$

![](https://cdn.discordapp.com/attachments/1152935463603142806/1176000170777903225/IMG_6421.jpg)

### Couples 力隅

$\vec{F_1}=-\vec{F_2}$
$\tau _{net} = F_1d_1+F_2d_2 = F(d_1+d_2) = Fl$
$F_1x_1+F_2x_2 = F(x_1+x_2) = Fl$


| linear kinematics | = | $R \times$ rotation kinematies | 運動學 |
| ----------------- | - | ------------------- | ----- |
| $S$               |   | $\theta$            |       |
| $V_t$             |   | $\omega$            |
| $a_t$             |   | $\alpha$            |
| $V=v_0+at$        |   | $\omega = \omega_0 + \alpha t$
| $\Delta S = v_0t + \frac{1}{2}at^2$ |   | $\Delta \theta = \omega_0t + \frac{1}{2}\alpha t^2$
| $v^2=v^2_0 + 2a\Delta S$ |   |$\omega^2=\omega_0^2+2\alpha \Delta\theta$

- 解析

| linear dynamics | rotation dynamics | 動力學 |
| --------------- | ----------------- | ----- |
| $m$             | $I$               |       |
| $\vec{P} = m\vec{v}$ | $\vec{L} = I\omega$ | 角動量 |
| $\vec{F} = m\vec{a}$ |  $\vec{\tau} = I\vec{\alpha}$ | 力矩 |
| $k = \frac{1}{2}mv^2$ | $k = \frac{1}{2}I\omega^2$ |   |

### Atwood Machine

![](https://cdn.discordapp.com/attachments/1152935463603142806/1176004105131532400/IMG_6422.jpg)

$a=?$
$m_1g - T_1 = m_1 a$ -(i)
$T_2 - m_2g = m_2a$ -(ii)
$\tau = (T_1 - T_2)R=I\alpha$
$m_1g - m_2g-(T_1-T_2)=(m_1+m_2)a$
$a=R\alpha$

$m_1g - m_2g -[\frac{1}{2}m_pa] = (m_1 + m_2)a$
$(m_1 - m_2)g = (m_1 + \frac{1}{2}m_p + m_2)a$
$a = \frac{m_1-m_2}{m_2+\frac{1}{2}m_p+m_2}g$

### Chapter 14 S.H.M 簡諧振盪

Simple Harmonic Motion (S.H.M)

By Nt's 2nd Law

$F_x=-kx$
$(F_{out})_x = ma_x = -kx \rightarrow a_x = -\frac{k}{m}x$
$ma_x + kx=0$
$a_x = \frac{dv_x}{dt} = \frac{d^2x}{dt^2}$
$m\frac{d^2x}{dt^2} + kx = 0$ = 階常微分方程式
令 $x=Acos(\omega t+\phi)$
$\omega = \sqrt{\frac{k}{m}}$

A: Amplitude 振幅
$\omega$: angular frequence 角頻率
$\phi_0$: phase constant 相常數
$\phi_0$: phase angle 相角
$\omega t+\phi_0$: phase 相

$\because x(t)$ 為週期函數。 T(period)
$\omega(t+T)+\phi_0-(\omega t+\phi_0) = 2\pi$
$\omega t=2\pi, \rightarrow \omega = \frac{2\pi}{T}$
$f = \frac{1}{T} =\frac{\omega}{2\pi} \rightarrow \omega = 2\pi f$
$\omega = \frac{2\pi}{T} = \sqrt{\frac{k}{m}} \rightarrow T = 2\pi \sqrt{\frac{m}{k}}$

![image](https://hackmd.io/_uploads/SyeaA3t4T.png)

S.H.M 常見的兩種情況

![image](https://hackmd.io/_uploads/rkTPJ6tVp.png)

$x(t) = A \cos (\omega t + \phi_0)$
$x(0) = A = A \cos \phi_0 \rightarrow \cos\phi_0 = 1$
$v(t) = -\omega A sin(\omega t +\phi_0)$
$v_{max} = \omega A$
$v(0) = 0 = -\omega A sin(\phi_0)$
$\rightarrow cos\phi_0=1\space and\space sin\phi_0\rightarrow \phi_0=0$

端點開始

$x(t) = A\cos(\omega t)$

![image](https://hackmd.io/_uploads/SJQ4latET.png)

$x(t) = A\cos(\omega t + \phi_0)$
$x(0) = 0 = A \cos \phi_0$
$v(0) = v_i = -V_i \sin \phi_0$
$\cos \phi_0 = 0$
$\sin \phi+0 = -1$
$x(t) = Acos(\omega t-\frac{\pi}{2})=cos(\frac{\pi}{2}-\theta) = +sin\theta$

平衡點開始

$x(t) = A \sin(\omega t)$

![image](https://hackmd.io/_uploads/H1idWTKVa.png)

EX: 右拉 20 cm 釋放 (t=0s)，其在 10.0s 內震盪 15 次，求 $a, T, b V_{max}, t= 0.800s$ 之位置速率

a) T: 每次n秒
   T = $\frac{10.0}{15} = 0.667(s)$
b) $V_{max} = \omega A = \frac{2\pi}{T}A = \frac{2\pi}{0.667}\cross 0.20 =1.88m/s$
   $a_{max} = \omega^2 A$
c) $x(t) = A\cos(\omega t)$
   $v(t) = -\omega A\sin(\omega t)$ 
   $x(0.800) = 0.20\cos(\frac{2\pi}{0.667} \times 0.800) = 0.0625cm = 6.25m$
   $v(0.800) = -0.20\frac{2\pi}{0.667} sin(\frac{2\pi}{0.667}\cross0.800) = -1.79m/s$

EX:

T = 0.80s, A = 10.0cm, t = 0s 十 其在平衡點左方 5cm 向左運動，求 t= 2.0s 時運動位置和方向？

Sol:

令 $x(t) = A\cos(\omega t + \phi_0)$
$\phi_0 = \frac{2}{3}\pi$

![image](https://hackmd.io/_uploads/r1dNB6KNT.png)

$\frac{2.0}{0.80}T = \frac{5}{2}T$
$x(2.0) = +5.0cm$ 向右

EX:

t = 0s 時，m = 500g S.H.M x = 15.0cm 向右運動 
達 A = 25.0 cm 時 t = 0.30s

a) 畫出 x-t 圖
b) 在 $1^{st}T$ 內何時通過 x = 20cm

Sol: 

a) $x(t) = 25.0 \cos(\omega t + \phi_0)$
   $x(0) = 15.0 = 25.0cos\phi_0$
   $cos\phi_0 = \frac{3}{5} \rightarrow \phi_0 = +- 53^\circ$(+不合)
   $x(0.30) = 25 \rightarrow cos(\omega\cross0.30 -53^\circ)=1$

![](https://hackmd.io/_uploads/SJdAUatVT.png)

$\omega \times 0.30 -53^\circ$
$\omega = 3.09 rad/s \frac{2\pi}{T}, T = 2.0s$

$x(t) = 25.0\cos(3.09t-0.927)$

{image}

b) $20=25cos(3.09t-0.927)$
   $t=0.51s,0.09s$

### 14.3 Emergy in S.H.M

無摩擦 $E=K+U$ 為定值

S.H.M $x(t)=Acos(\omega t + \phi_0)$
      $v(t)=-\omega A sin(\omega t + \phi_0)$
      $a(t)=-\omega^2Acos(\omega t+\phi_0)$
    
$K=\frac{1}{2}mv^2 = \frac{1}{2}m\omega^2A^2sin^2(\omega t+\phi_0)$

$U_{sp} = \frac{1}{2}kx^2 = \frac{1}{2}kA^2\cos(\omega t + \phi_0) = \frac{1}{2} m \omega^2 A^2 \cos^2(\omega t + ]phi+0)$

$E = K+U_{sp} = \frac{1}{2}m\omega^2A^2(sin^2(\omega t+\phi_0)+cos^2(\omega t+\phi_0))$
$=\frac{1}{2}\omega^2A^2$
$= \frac{1}{2}kA^2 \rightarrow$ 最大彈力位能
$= \frac{1}{2}V_{max}^2 \rightarrow$ 最大動能

EX:

![](https://cdn.discordapp.com/attachments/1152935463603142806/1178522070926233712/IMG_20231127_102538.jpg)

已知A，x
$\frac{1}{2}mv^2 = \frac{1}{2}k(A^2 - x^2)$
$v^2 = \frac{k}{m}(A^2 - x^2)$
$v = \pm w\sqrt{A^2 - x^2}$

已知$v,v_{max}$
$\frac{1}{2}kx^2 = \frac{1}{2}m(v_{max}^2-v^2)$
$x^2 = \frac{m}{k}(v_{max}^2 - v^2)$
$x=\pm \sqrt{\frac{m}{k}(v_{max}^2-v^2)}$

### 14.4 S.H.M 應用

- Vertical S.H.M

![](https://cdn.discordapp.com/attachments/1152935463603142806/1178523734613696632/IMG_20231127_103147.jpg)

![](https://cdn.discordapp.com/attachments/1152935463603142806/1178523734827597854/IMG_20231127_103222.jpg)

平衡

$F_{sp} = md = k \Delta L$
$\Delta L = \frac{mg}{k}$

y 點：

$(F_{net})_y = (F_{sp})_y + (F_{cs})_y = l(\Delta L - y) - mg = k\Delta L - ky - mg = ma_y$
$ma_y = -ky \leftrightarrow ma_x = -kx (S.H.M)$

$y(t) = A\cos(\omega t + \phi_0), \omega = \sqrt{\frac{k}{m}}$

### 14.5 Simple Pendulum 單擺

![](https://cdn.discordapp.com/attachments/1152935463603142806/1178525964376997908/IMG_20231127_104116.jpg)

- particle 粒子



S : 方向
$(F_{net})_s = -mg\sin\theta = ma_s$
$m\frac{d^2s}{dt} = -mg\sin\theta$
$mL\frac{d^2\theta}{dt^2} + mg\sin\theta = 0$

![](https://cdn.discordapp.com/attachments/1152935463603142806/1178528107259514910/IMG_20231127_104948.jpg)

$\theta << 1 \space 0^。\le \theta \le 10^。$
$\sin\theta \approx \theta \approx \tan\theta$
$L\frac{d^2\theta}{dt^2} + g\theta = 0 \rightarrow$S.H.M
$\theta (t) = Acos(\omega t + \phi_0)$
$\omega = \sqrt{\frac{g}{L}} = \frac{2\pi}{T} T = 2\pi \sqrt{\frac{L}{g}}$

### 14.6 Physical Pendulume  compound 複擺

物理擺，複擺

![](https://cdn.discordapp.com/attachments/1152935463603142806/1178534007475011685/IMG_20231127_111303.jpg)

$\tau = I\alpha$
$-mgL\sin]theta = I\alpha$
$I\frac{d^2\theta}{dt^2} + mgL\sin\theta$
$\theta << 1 \space 0^。\le \theta \le 10^。$
$I\frac{d^2\theta}{dt^2} + mgL\theta = 0\rightarrow SHM$
$\theta (t) = Acos(\omega t + \phi_0)$
$\omega = \sqrt{\frac{mgL}{I}} = \frac{2\pi}{T} \rightarrow T = 2\pi\sqrt{\frac{I}{mgL}}$

![](https://cdn.discordapp.com/attachments/1152935463603142806/1178534994386358332/IMG_20231127_111709.jpg)

$T = \pi\sqrt{\frac{I}{mgR}}$
$I = I_{c.m} + MR^2$
$= \frac{1}{2}MR^2 + MR^2$
$= \frac{3}{2}MR^2$

平行軸原理

$T = 2\pi \sqrt{\frac{\frac{3}{2}MR^2}{MgR}}=2\pi\sqrt{\frac{3R}{2g}}$

### 14.7 Damped Oscillations 阻尼振盪

$\vec D = -b\vec v$ 阻尼係數
$(F_{net})_x = -kx - bv_x = ma_x$
$m\frac{d^2x}{dt^2} + b\frac{dx}{dt} + kx = 0$

令 $x(t) = Ae^{\alpha t}$ 代入求解 $\alpha = ?$

$x(t) = Ae^{-\frac{b}{2m}t}cos(\omega t +\phi_0)$
$\omega = \sqrt{\frac{k}{m} - (\frac{b}{2m})^2}$ 自然頻率$\omega_0 = \sqrt{\frac{k}{m}}$
$\omega = \sqrt{\omega_0^2 - (\frac{b}{2m})^2}$

(i) $b = 0, \omega = \omega_0$ S.H.M
(ii) $\omega_0 = \frac{b_c}{2m}, b = b_c$ 臨界阻尼，不再震盪 critically damped
(iii) $\frac{b}{2m} > \omega_0$
介質非數?，overdamped 過阻尼

![](https://cdn.discordapp.com/attachments/1152935463603142806/1178538420453249114/IMG_20231127_113043.jpg)

### 14.8 Forced Oscillations

$m\frac{d^2x}{dt^2} + b\frac{dx}{dt} + kx = F_0\sin\omega t$ 外在效應

$x = A\cos(\omega t + \phi)$
$A = \frac{F_0/m}{\sqrt{(\omega^2-\omega_0^2)^2+(\frac{b\omega}{m})^2}}$
$\omega_0 = \sqrt{\frac{k}{m}}$
$omega \approx \omega_0, A \uparrow$ resonance 共振

![](https://cdn.discordapp.com/attachments/1152935463603142806/1178555031985864806/IMG_20231127_123639.jpg)

### Chapter 21 Electrostaties 靜電學

- 西元前 2000 年左右，中國文獻就有磁學介紹。

- 西元前 700 年左右，希臘才有電和磁。

- 1600 年 William Gibert 發現起電現象 phenomena

- 1785 年 Coulomb 確立了電力導守
  反平方定律 $F_e = \frac{kQq}{r^2}$

- 電和磁是兩個學科各自發的

- 1820 年 Oersted 發現導線中的電流會影響羅盤的磁針 (電生磁)

- 1831 年 英 Farady 美 Henyy
  變化中的磁場會產生電流 (磁生電)

- 1873年 Maxwell 整理理論 
  Maxwell's equation 統合電學磁學
  預測電磁波存在
    
- 1888 年 Hertz 證明了 E.M. Wave 存在

### Maxwell's equations

$\vec E$: 電場 $\vec B$: 磁場 $\oint$: 封閉面積分，環場積
$\Phi_B$: 磁通量 $\Phi_E$: 電通量
$\oint \vec E d \vec A = \frac{q_{in}}{\epsilon_0}$
$\oint \vec B d\vec A = 0$
$\oint \vec E d \vec s = -\frac{d\Phi_B}{dt}$
$\oint \vec B d \vec s = u_0I + u_0 \epsilon_0\frac{d\Phi_E}{dt}$

電的高斯定律（可以推出庫侖定律）
磁的高斯定律（沒有磁單極）
法拉第定律（磁生電）
安培定律（電生磁）
安培馬克斯威爾定律

free space $q_{?} = 0, I = 0$
$\oint \vec{E} d\vec{A} = 0$
$\oint \vec{B} d\vec{A} = 0$
$\oint \vec{E} d\vec{s} = -\frac{d\Phi_B}{dt}$
$\oint \vec{B} d\vec{s} = 0 + \mu_0 \epsilon_0 \frac{d\Phi_E}{dt}$
$\vec{F} = q(\vec{E} = \vec{v} \times \vec{B})$ 羅倫茲力

### E.M.Wave

$y(x,t) = y_{max} sin(kx - \omega t),\vec{E}\perp\vec{v}$
$E(x,t) = E_{max} sin(kx - \omega t),\vec{B}\perp\vec{v}$
$B(x,t) = B_{max} sin(kx - \omega t)$

$v = \frac{\omega}{k} = \lambda f = c = \frac{1}{\sqrt{\mu_0\epsilon_0}}$
$= \frac{1}{\sqrt{4\pi \times 10^{-7}\times 8.85\times 10^{-12}}}$

### 21.1 Charges 電荷

1. positive (正), negative (負)

- 富蘭克林 玻 $\rightarrow$ 正 塑 $\rightarrow$ 負

2. 同性相斥(repel)，異性相吸(attract)

3. 孤立系統 (isolated system) 電荷是守恆的

4. 電荷的量子化 Quamtization
$1 el = 1.6\times 10^{-19} C$ 為基本單位
$Q = n|e|$ n 為整數

### 21.2 Insulators & Conductors 絕緣體和導體

![image](https://hackmd.io/_uploads/HkDlqgXSa.png)
![image](https://hackmd.io/_uploads/rJFZcemBa.png)

加 Si,Ge 成為半導體
Y, Ba, Cu, O 超導體 $92^。k$
             低溫超導 $40^。k$ 以下

$T < T_c$

1. 零電阻
2. 抗磁性

### 21.3 Coulumb's law

$F_c = k \frac{g_1 g_2}{k}$

k: 庫侖常數 $8.99 \times 10^9 Nm^2/c^2$

$\epsilon_0$ : 容電常數 permittivity constant

$k = \frac{1}{4\pi\epsilon_0}$

$\epsilon_0: 8.85 \times 10^{-12}$

EX:

![](https://hackmd.io/_uploads/SkOc3gQHT.png)

$q_3$ 放至在何處?力為0

Sol:

$q_3$ 放在 A, B, C, D 點皆不為 0
$q_3$ 在 $p$ 點 $F_{13} = F_{23}$

$\frac{kq_1q_3}{x^2} = \frac{kq_2q_3}{(10.0-x)^2}$

$g_2 = 4g_1$

$\frac{g_1}{x^2} = \frac{4g_1}{(10.0 - x)^2}$

$\frac{1}{x} = \pm \frac{2}{10.0 - x}$

$g_2 = 3g_1$

$\frac{g_1}{x^2} = \frac{3g_1}{(10.0 - x)^2}$

$\frac{1}{x} = \pm \frac{\sqrt{3}}{10.0 - x}$

$x = 3.66$ cm $-13.66$ cm 後者不合

### 21.4 Coulumb's law & Newton's law of gravity

EX:

$Fe, Fg$ ratio = ?

Sol:

$Fe = \frac{ke^2}{r^2}, Fg = \frac{Gm^2}{r^2}$

$\frac{Fe}{Fg} = \frac{\frac{ke^2}{r^2}}{\frac{Gme^2}{r^2}} = \frac{ke^2}{Gme^2} = \frac{9 \times 10^9 \times (1.6 \times 10^{-19})^2}{(6.67 \times 10^{-11})(9.11 \times 10^{-31})^2}$

Electric Fields 電場

![image](https://hackmd.io/_uploads/r1QkWWXB6.png)
![image](https://hackmd.io/_uploads/HydkZbmB6.png)

$\vec E \equiv \frac{\vec F_e}{g_0}$

電場方向
電場單位 : $\frac{N}{c}$

$\vec E = \frac{\vec F_e}{g_1} = \frac{\frac{k g_0 Q}{r^2} \hat r}{g_0} = \frac{kQ}{r^2} \hat r$

$\vec E_p = \sum_i \vec E_i = k\sum_i \frac{g_i}{r_i^2} \hat r_i$



$\vec E_p = k\int \frac{1}{r^2}dq\hat r$



法拉第 $\rightarrow$ 電力場

1. 力線上的任一點切線方向即為$\vec E$的方向
2. 單位面積之線數正比於$\vec E$大小
3. 可描述$\vec E = \frac{kq}{r^2} \hat r$

【image】你寫這樣我不知道是哪張

$\frac{N}{4\pi r^2} \space \alpha \space E$
線數(N) $\alpha$ 電荷數(nq)
$E \space \alpha \space \frac{nq}{4\pi r^2} = \frac{kq}{r^2}$

4. 畫法

【image】

5. 電力線不相交

Ex. Diople 電隅極
$\vec E_p = ?$

【image】

Sol:

因為對稱，所以只算 y 方向

$(E_p)_y = E_{+y} + E_{-y}$
$= \frac{kq}{r^2_+} sin\theta + \frac{kq}{r^2_-} sin\theta$
$= \frac{2kq}{r^2_+} \frac{\frac{S}{2}}{r_+} = \frac{kqS}{((\frac{S}{2})^2 + x^2)^{\frac{3}{2}}}$

【image】

$x>>1$ $(E_p)_y = \frac{kqs}{x^3}$
點電荷 $E_p = \frac{kq}{r^2}$
$\vec p = q \vec S$ diople(-$\rightarrow$+)
$\vec E_p = \frac{k\vec p}{r^3}$ diople electric field
$E_{\theta} = \frac{2k\vec p}{r^3}$ (自行練習)

Ex: 均勻帶電體

$\vec E_p = ?$

【image】

Sol:
$(E_p)_x = \int^\frac{L}{2}_{-\frac{L}{2}} dE_{ix} = \int^\frac{L}{2}_{-\frac{L}{2}}\frac{kdq}{r^2}\frac{d}{r}$
$= \int^{\frac{L}{2}}_{-\frac{L}{2}}\frac{kd}{(d^2 + y^2)^{\frac{3}{2}}}dq$
$= \int^{\frac{L}{2}}_{-\frac{L}{2}}\frac{kd}{(d^2 + y^2)^{\frac{3}{2}}}\lambda dy$
$\lambda = \frac{Q}{L}$ 總電荷密度

公式: $= kd\lambda \frac{y}{d^2(d^2 + y^2)^\frac{1}{2}}\bracevert^\frac{L}{2}_{-\frac{L}{2}}$
$= \frac{kQ}{d(d^2 + (\frac{L}{2})^2)^\frac{1}{2}}$
d>>1
$(E_p)_x \approx \frac{kQ}{d^2}$ ?點電荷電場

Ex: 均勻帶電體 $\vec E_p = ?$ 

【image】

Sol: 因為對稱所以只算z方向
$(E_p)_z = \sum_i \frac{k\Delta Q_i}{r^2_i} \frac{z}{r_i}$
$= \frac{kQz}{(R^2+z^2)^\frac{3}{2}}$
z>>R||1 $(E_p)_z \approx \frac{kQz}{z^3} \approx \frac{kQ}{z^2}$ ??電荷電場
z<<R $(E_p)_{canter} \approx 0$

Ex: Disk 均勻帶電體 

$\vec E_p = ?$

【image】

$(E_p)_z = \int \frac{kz}{(r^2+z^2)^\frac{3}{2}}dq$

Ex: Plame of charge

![image](https://hackmd.io/_uploads/H1gjH4nH6.png)

無限平面帶均勻電荷
$\rho$ 面電荷密度(定值)
將 Disk 圓盤 R$\rightarrow\infty$
$Eplane = \frac{\rho}{2\epsilon_0}$
$\vec E_phane = \frac{\rho}{2\epsilon_0} \space ，z>0$
            $=-\frac{\rho}{2\epsilon_0} \space ,z<0$

EX: Sphere of charge (?率)

![image](https://hackmd.io/_uploads/SJQaSEnSp.png)

$\vec{E_{sphere}} = \frac{kQ}{r^2} \hat r , r\ge R$

EX: Parallel - Plate Capacitor (電容器)

![image](https://hackmd.io/_uploads/S19Z8NhBa.png)

$E = E_+ + E_- = \frac{\rho}{2\epsilon_0} + \frac{\rho}{2\epsilon_0} = \frac{\rho}{\epsilon_0}$

$\vec{F_e} = q\vec E = m\vec a, \vec a = \frac{q\vec E}{m}$

### Motion of a dipde in an $\vec E$

![image](https://hackmd.io/_uploads/H1e_IEhHT.png)

$|\vec\tau| = lF = qEs\space sin\theta = pEsin\theta$
$\vec\tau = \vec P \times \vec E$

### Gauss' Law 高斯定律

$\phi_E$: Electric Flux 電通量

![image](https://hackmd.io/_uploads/BJyl9N2Hp.png)

$\vec E \parallel \vec A$

$\phi_E = EA$

![image](https://hackmd.io/_uploads/Bkqxq43BT.png)

$\phi_E = EAcos\theta$
$\phi_E = \vec E \vec A$

![image](https://hackmd.io/_uploads/S1fb54hrp.png)

$d\Phi_E = E_i a_i cos\theta_i$
$\Phi_E = \int d|Phi = \int_{surface} \vec E d\vec A$

![image](https://hackmd.io/_uploads/SyzzqV2ST.png)

$\Phi_E = \oint \vec E d\vec A$ 封閉曲面

Symmetry(對稱) $\rightarrow$ Invariane(不變量) $\rightarrow$ Conservation(守恆律)

- Planar Symm

![image](https://hackmd.io/_uploads/SkK8s42ST.png)

- Cylindrical Symm

![image](https://hackmd.io/_uploads/ryxPiN3Ba.png)

- sphere Symm
- 
![image](https://hackmd.io/_uploads/HylwjVhSa.png)

高斯定律

![image](https://hackmd.io/_uploads/B16-eHnBa.png)

$\phi_E = \oint \vec E d\vec A = \oint EdA = E \oint dA = \frac{kq}{r^2}4\pi r^2 = kq4\pi = \frac{q}{\epsilon_0}$

![image](https://hackmd.io/_uploads/HyAfgH2Sp.png)




<!-- 討論區
字太多是不是 狗幹卡 
我網頁還當掉 bruh
我在想要不要把檔案分開放
現在真的卡到靠北
我覺得要 回去再用
不行 太卡了我沒辦ㄈ 太卡了我沒辦ㄈ 太卡了我沒辦ㄈ 太卡了我沒辦ㄈ 太卡了我沒辦ㄈ 太卡了我沒辦ㄈ 太卡了我沒辦ㄈ 太卡了我沒辦ㄈ 太卡了我沒辦ㄈ 太卡了我沒辦ㄈ 太卡了我沒辦ㄈ 太卡了我沒辦ㄈ
-->

<!-- 留四個錢號是為了下面編輯模式裡的顏色不要出 Bug，學期末再拿掉 -->
$$$$

## 作業

9/11 : EX 1-9 1-11 翻譯
9/18 : EX 2-7 2-9 翻譯
9/25 : 線上習題(?
10/2 : ?
10/16: ?
10/23: ?
10/30: ?
11/6: ?
11/13: ?
11/20: ?
11/27: ?

### 小考 

## 秘密考題（？

- S.F. 有效數字
- 電學4大公式(學長說有10分)
- 笑話(?學長說的)
- 牛頓3大運動定律(題目使用到哪個寫出來)
- 把你想得到的跟物理有關的都可以寫

---

[中文文案排版指北](https://github.com/sparanoid/chinese-copywriting-guidelines/tree/master)
[常用 LaTeX 數學符號指令](https://hackmd.io/@CynthiaChuang/Basic-LaTeX-Commands)
[LaTeX/數學公式 維基教科書](https://zh.wikibooks.org/zh-tw/LaTeX/%E6%95%B0%E5%AD%A6%E5%85%AC%E5%BC%8F)

---

{%hackmd @lumynou5/dark-theme %}
