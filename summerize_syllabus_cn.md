# Cambridge International AS & A Level Further Mathematics (9231) — 全面知识点总结与扩展

该大纲适用于 2028、2029、2030 年考试，共包含 **4 张试卷**、**4 大板块**，涵盖 **21 个主题单元**。以下是完整的知识体系总结：

---

## 📌 整体结构

| 试卷 | 名称 | 考试时长 | 分值 | A Level 占比 | AS Level 占比 |
|------|------|---------|------|-------------|-------------|
| Paper 1 | Further Pure Mathematics 1 | 2 小时 | 75 | 30% | 60%（必修） |
| Paper 2 | Further Pure Mathematics 2 | 2 小时 | 75 | 30% | —（A Level 必修） |
| Paper 3 | Further Mechanics | 1.5 小时 | 50 | 20% | 40%（二选一） |
| Paper 4 | Further Probability & Statistics | 1.5 小时 | 50 | 20% | 40%（二选一） |

**AS Level 路线（二选一）**：
- 路线 A：Paper 1 + Paper 3（纯数1 + 进阶力学）
- 路线 B：Paper 1 + Paper 4（纯数1 + 进阶概率统计）

**A Level 路线**：必须考全部四张试卷（Paper 1 + 2 + 3 + 4）

---

# 📘 一、Further Pure Mathematics 1（Paper 1）

## 1.1 多项式方程的根（Roots of Polynomial Equations）

**核心知识点**：
- 掌握根与系数的关系（Vieta 公式），适用于 2、3、4 次方程
  - 二次方程：$ax^2+bx+c=0$，根 $\alpha,\beta$，则 $\alpha+\beta=-\frac{b}{a}$，$\alpha\beta=\frac{c}{a}$
  - 三次方程：$ax^3+bx^2+cx+d=0$，根 $\alpha,\beta,\gamma$，则 $\sum\alpha=-\frac{b}{a}$，$\sum\alpha\beta=\frac{c}{a}$，$\alpha\beta\gamma=-\frac{d}{a}$
  - 四次方程同理扩展
- **对称函数求值**（symmetric functions of roots）
- 通过变量代换构造新方程，使其根与原方程的根有简单关系
  - 如倒数关系（reciprocals）、平方关系（squares）、线性关系（linear function）

**扩展应用**：
- 已知根的关系求未知系数
- 利用代换求新方程：若原方程根为 $\alpha,\beta,\gamma$，则新根为 $k\alpha+m$、$\frac{1}{\alpha}$、$\alpha^2$ 等

---

## 1.2 有理函数与图像（Rational Functions and Graphs）

**核心知识点**：
- 绘制简单有理函数的草图（分子分母最高次数 ≤ 2）
- 确定**斜渐近线**（oblique asymptotes）——当分子次数比分母高 1 时
- 利用判别式求函数的值域（set of values taken by the function）
- 图像关键特征：转折点（turning points）、渐近线（垂直/水平/斜）、与坐标轴的交点

**图像变换关系**：理解并运用以下图像间的关系
- $y = f(x)$ 与 $y^2 = f(x)$
- $y = f(x)$ 与 $y = \frac{1}{f(x)}$
- $y = f(x)$ 与 $y = |f(x)|$
- $y = f(x)$ 与 $y = f(|x|)$

**扩展应用**：
- 利用图像变换解方程和不等式
- 求有理函数的渐近线方程
- 利用判别式法求函数值域

---

## 1.3 级数求和（Summation of Series）

**核心知识点**：
- 使用标准求和公式：
  - $\displaystyle\sum_{r=1}^{n} r = \frac{1}{2}n(n+1)$
  - $\displaystyle\sum_{r=1}^{n} r^2 = \frac{1}{6}n(n+1)(2n+1)$
  - $\displaystyle\sum_{r=1}^{n} r^3 = \frac{1}{4}n^2(n+1)^2$
- **差分法**（Method of Differences）：将通项写成相邻项之差的形式，求和时大量抵消
  - 常配合部分分式（partial fractions）使用

**扩展应用**：
- 判断级数收敛性，求收敛级数的无穷和（sum to infinity）
- 对复杂通项（如 $r(r+1)(r+2)$ 等）进行求和
- 利用差分法证明求和公式

---

## 1.4 矩阵（Matrices）

**核心知识点**：
- 矩阵的加、减、乘法运算（含非方阵，最多 3×3）
- 零矩阵（zero matrix）和单位矩阵（identity matrix）
- 奇异矩阵（singular）与非奇异矩阵（non-singular）的含义
- 对 2×2 和 3×3 矩阵求行列式（determinant）和逆矩阵（inverse）
  - 记法：$\det M$
  - 公式：$(AB)^{-1} = B^{-1}A^{-1}$
- **2×2 矩阵的几何变换**（在 $xy$ 平面中）：
  - 旋转（rotation）、反射（reflection）、放大（enlargement）、拉伸（stretch）、剪切（shear）
  - 变换 $A$ 与 $A^{-1}$ 的对应关系
  - 矩阵乘积 $AB$ 表示先 $B$ 后 $A$ 的复合变换
  - 行列式与面积缩放因子的关系
- **不变性**（invariant）：
  - 不变点（invariant points）
  - 不变线（invariant lines）

**扩展应用**：
- 求给定变换的矩阵
- 求复合变换的矩阵
- 证明某条线在变换下不变

---

## 1.5 极坐标（Polar Coordinates）

**核心知识点**：
- 极坐标 $(r,\theta)$ 与直角坐标 $(x,y)$ 的转换关系：
  - $x = r\cos\theta$，$y = r\sin\theta$
  - $r^2 = x^2 + y^2$，$\tan\theta = \frac{y}{x}$
- 曲线方程的直角坐标 ↔ 极坐标互化
- 绘制简单极坐标曲线（通常在 $0 \leq \theta \leq 2\pi$ 或 $-\pi \leq \theta \leq \pi$ 或其子区间）
  - 关键特征：对称性、与极轴的交点、在极点处的形态、$r$ 的最大/最小值
- **扇形面积公式**：$A = \frac{1}{2}\int_{\alpha}^{\beta} r^2 \, d\theta$

**扩展应用**：
- 绘制心形线（cardioid）、三叶玫瑰线（rose curve）、螺旋线（spiral）等
- 求两曲线交点
- 求曲线围成的面积

---

## 1.6 向量（Vectors）

**核心知识点**：
- **平面的方程**的三种形式及互化：
  - $ax + by + cz = d$（笛卡尔形式）
  - $\mathbf{r} \cdot \mathbf{n} = p$（点积形式）
  - $\mathbf{r} = \mathbf{a} + \lambda\mathbf{b} + \mu\mathbf{c}$（参数形式）
- **向量积（叉积）**：
  - $\mathbf{a} \times \mathbf{b} = |\mathbf{a}||\mathbf{b}|\sin\theta \,\hat{\mathbf{n}}$
  - 分量形式：$\mathbf{a} \times \mathbf{b} = (a_2b_3 - a_3b_2)\mathbf{i} + (a_3b_1 - a_1b_3)\mathbf{j} + (a_1b_2 - a_2b_1)\mathbf{k}$
- **应用问题**：
  - 判断直线与平面的位置关系（在平面内、平行、相交）
  - 求直线与平面的交点
  - 求点到平面的垂足（foot of perpendicular）
  - 求直线与平面的夹角、两平面的夹角
  - 求两平面的交线方程
  - 求两**异面直线**（skew lines）的最短距离
  - 求两异面直线的公垂线方程

**扩展应用**：
- 点到直线的距离
- 利用标量积（点积）判定垂直
- 利用向量积求法向量

---

## 1.7 数学归纳法（Proof by Induction）

**核心知识点**：
- 理解数学归纳法的基本原理和步骤：
  1. **奠基步骤**（base case）：验证 $n=1$（或最小 $n$ 值）时命题成立
  2. **归纳假设**（inductive hypothesis）：假设 $n=k$ 时命题成立
  3. **归纳步骤**（inductive step）：证明 $n=k+1$ 时命题也成立
  4. **结论**：由数学归纳法，命题对所有正整数成立

**可证明的类型**：
- 求和公式：如 $\displaystyle\sum_{r=1}^{n} r^4 = \frac{n}{30}(n+1)(2n+1)(3n^2+3n-1)$
- 递推数列：如 $u_1 = 1$，$u_{n+1} = 2u_n + 1$，证明 $u_n = 2^n - 1$
- 整除性问题：如 $3^{2n} + 2^{6n-5}$ 能被 11 整除
- 导数公式：求 $y = xe^x$ 的 $n$ 阶导数
- 矩阵幂：证明 $A^n$ 的表达式

**扩展应用**：
- 先通过有限试验猜测规律，再用归纳法证明（conjecture + inductive proof）
- 乘积求和：如 $\sum_{r=1}^{n} r \cdot r!$

---

# 📘 二、Further Pure Mathematics 2（Paper 2）

*前提知识：需掌握 Paper 1 全部内容*

## 2.1 双曲函数（Hyperbolic Functions）

**核心知识点**：
- **定义**（以指数函数表示）：
  - $\sinh x = \frac{e^x - e^{-x}}{2}$
  - $\cosh x = \frac{e^x + e^{-x}}{2}$
  - $\tanh x = \frac{\sinh x}{\cosh x} = \frac{e^x - e^{-x}}{e^x + e^{-x}}$
  - $\text{sech}\,x = \frac{1}{\cosh x}$，$\text{cosech}\,x = \frac{1}{\sinh x}$，$\coth x = \frac{1}{\tanh x}$
- **图像特征**：绘制六个双曲函数的图像
- **恒等式**（与三角恒等式类比但注意符号差异）：
  - $\cosh^2 x - \sinh^2 x \equiv 1$
  - $\sinh 2x \equiv 2\sinh x \cosh x$
  - $\cosh 2x \equiv \cosh^2 x + \sinh^2 x$
- **反双曲函数**的对数形式：
  - $\sinh^{-1} x = \ln(x + \sqrt{x^2 + 1})$（对所有 $x$）
  - $\cosh^{-1} x = \ln(x + \sqrt{x^2 - 1})$（$x \geq 1$）
  - $\tanh^{-1} x = \frac{1}{2}\ln\frac{1+x}{1-x}$（$|x| < 1$）

**扩展应用**：
- 证明双曲函数恒等式
- 与三角恒等式的类比学习（Osborne's Rule）

---

## 2.2 矩阵进阶（Matrices）

**核心知识点**：
- **三元一次方程组**的矩阵表示：$A\mathbf{x} = \mathbf{b}$
- 方程组的**相容性**（consistent）与**不相容性**（inconsistent）：
  - 奇异矩阵 ↔ 无唯一解（无解或无穷多解）
  - 非奇异矩阵 ↔ 唯一解
  - 几何解释：三平面的交点情况（交于一点、交于一线、无公共点）
- **特征值与特征向量**：
  - 特征方程（characteristic equation）：$\det(A - \lambda I) = 0$
  - 定义：$A\mathbf{e} = \lambda\mathbf{e}$
  - 对 2×2 和 3×3 矩阵求特征值和特征向量（限于实特征值且互异的情况）
- **矩阵对角化**：$A = QDQ^{-1}$，其中 $D$ 为特征值对角矩阵，$Q$ 的列是特征向量
  - 应用：计算矩阵的幂 $A^n = QD^nQ^{-1}$
- **Cayley-Hamilton 定理**：方阵满足自身的特征方程
  - 应用：求矩阵的高次幂、求逆矩阵

**扩展应用**：
- 证明若 $\lambda$ 是 $A$ 的特征值，则 $\lambda^n$ 是 $A^n$ 的特征值
- 利用特征方程将高次幂降阶

---

## 2.3 微分（Differentiation）

**核心知识点**：
- 双曲函数的导数：
  - $\frac{d}{dx}\sinh x = \cosh x$
  - $\frac{d}{dx}\cosh x = \sinh x$
  - $\frac{d}{dx}\tanh x = \text{sech}^2 x$
- 反三角和反双曲函数的导数：
  - $\frac{d}{dx}\sin^{-1}x = \frac{1}{\sqrt{1-x^2}}$
  - $\frac{d}{dx}\cos^{-1}x = -\frac{1}{\sqrt{1-x^2}}$
  - $\frac{d}{dx}\sinh^{-1}x = \frac{1}{\sqrt{1+x^2}}$
  - $\frac{d}{dx}\cosh^{-1}x = \frac{1}{\sqrt{x^2-1}}$
  - $\frac{d}{dx}\tanh^{-1}x = \frac{1}{1-x^2}$
- **二阶导数** $\frac{d^2y}{dx^2}$ 的求法：
  - 隐函数定义（implicitly defined）
  - 参数方程定义（parametrically defined）
- **Maclaurin 级数**展开：
  - $f(x) = f(0) + f'(0)x + \frac{f''(0)}{2!}x^2 + \frac{f'''(0)}{3!}x^3 + \cdots$
  - 求前几项（不需要求通项公式）
  - 可用逐次隐式微分法（successive implicit differentiation）

**标准展开式**（需掌握）：
- $e^x = 1 + x + \frac{x^2}{2!} + \frac{x^3}{3!} + \cdots$
- $\ln(1+x) = x - \frac{x^2}{2} + \frac{x^3}{3} - \frac{x^4}{4} + \cdots$
- $\sin x = x - \frac{x^3}{3!} + \frac{x^5}{5!} - \cdots$
- $\cos x = 1 - \frac{x^2}{2!} + \frac{x^4}{4!} - \cdots$
- $\tan x = x + \frac{x^3}{3} + \frac{2x^5}{15} + \cdots$
- $\sinh x = x + \frac{x^3}{3!} + \frac{x^5}{5!} + \cdots$
- $\cosh x = 1 + \frac{x^2}{2!} + \frac{x^4}{4!} + \cdots$
- $\tanh x = x - \frac{x^3}{3} + \frac{2x^5}{15} - \cdots$

---

## 2.4 积分（Integration）

**核心知识点**：
- 双曲函数的积分
- **标准积分形式**：
  - $\int \frac{1}{\sqrt{a^2 - x^2}} dx = \sin^{-1}\frac{x}{a}$（$|x| < a$）
  - $\int \frac{1}{\sqrt{x^2 - a^2}} dx = \cosh^{-1}\frac{x}{a}$（$x > a$）
  - $\int \frac{1}{\sqrt{a^2 + x^2}} dx = \sinh^{-1}\frac{x}{a}$
  - 配合配方法（completing the square）使用
- **三角/双曲代换**（trigonometric/hyperbolic substitutions）
- **递推公式**（Reduction Formulae）：通过分部积分建立 $I_n$ 与 $I_{n-1}$ 或 $I_{n-2}$ 的关系
  - 如 $I_n = \int_0^{\pi/2} \sin^n x \, dx$，$I_n = \int_0^1 x^n e^{-x} dx$，$I_n = \int_0^{\pi/4} \sec^n x \, dx$
- **矩形法估计面积**与不等式推导：
  - 用矩形面积估计曲线下面积
  - 导出有关和式的不等式或极限
  - 如 $\sum_{r=1}^{n} \frac{1}{r}$ 与 $\ln n$ 的关系
- **弧长**（Arc Length）：
  - 直角坐标：$s = \int_a^b \sqrt{1 + \left(\frac{dy}{dx}\right)^2} dx$
  - 参数形式：$s = \int_{t_1}^{t_2} \sqrt{\left(\frac{dx}{dt}\right)^2 + \left(\frac{dy}{dt}\right)^2} dt$
  - 极坐标：$s = \int_{\alpha}^{\beta} \sqrt{r^2 + \left(\frac{dr}{d\theta}\right)^2} d\theta$
- **旋转体表面积**（Surface Area of Revolution）：
  - 绕 $x$ 轴：$S = 2\pi \int_a^b y \sqrt{1 + \left(\frac{dy}{dx}\right)^2} dx$
  - 参数形式同理

**扩展应用**：
- 更复杂情况下的分部积分，如 $\int e^x \sin x \, dx$
- 代换 $t = \tan\frac{x}{2}$
- 极坐标曲线的弧长（试卷中可能涉及）

---

## 2.5 复数（Complex Numbers）

**核心知识点**：
- **棣莫弗定理**（de Moivre's Theorem）：
  - 对于正整数指数：$(\cos\theta + i\sin\theta)^n = \cos n\theta + i\sin n\theta$
  - 扩展到负整数和有理数指数
  - 几何意义：复数乘法和除法的旋转与伸缩
- **应用**：
  1. **倍角公式**：用 $\cos\theta$ 表示 $\cos n\theta$，用 $\tan\theta$ 表示 $\tan n\theta$
     - 如 $\cos 5\theta = 16\cos^5\theta - 20\cos^3\theta + 5\cos\theta$
  2. **三角幂的线性化**：将 $\sin^n\theta$ 或 $\cos^n\theta$ 表示为倍角余弦/正弦的线性组合
     - 如 $\sin^6\theta$ 用 $\cos 2\theta, \cos 4\theta, \cos 6\theta$ 表示
  3. **级数求和**：利用 "$C + iS$" 方法
     - 如 $\sum_{r=1}^{n} \sin r\theta$，$\sum_{r=1}^{n} \cos r\theta$
  4. **单位根**：$z^n = 1$ 的 $n$ 个根
     - $z = e^{2\pi i k/n}$，$k = 0,1,2,\ldots,n-1$
     - 根在复平面单位圆上均匀分布
     - 所有根的和为 0（$n \geq 2$）

**扩展应用**：
- 利用单位根证明三角恒等式
- 复数的几何应用

---

## 2.6 微分方程（Differential Equations）

**核心知识点**：
- **一阶线性微分方程**的积分因子法（Integrating Factor）：
  - 标准形式：$\frac{dy}{dx} + P(x)y = Q(x)$
  - 积分因子：$I = e^{\int P(x) dx}$
  - 通解：$y \cdot I = \int Q \cdot I \, dx$
- **二阶常系数线性微分方程**：
  - **齐次解**（Complementary Function）：
    - 辅助方程 $am^2 + bm + c = 0$
    - 两个不等实根：$y = Ae^{m_1x} + Be^{m_2x}$
    - 重根：$y = (A + Bx)e^{mx}$
    - 共轭复根 $m = \alpha \pm i\beta$：$y = e^{\alpha x}(A\cos\beta x + B\sin\beta x)$
  - **特解**（Particular Integral）的求法：
    - 多项式形式
    - $ae^{bx}$ 形式
    - $a\cos px + b\sin px$ 形式
    - 对简单情况，给定特解形式求待定系数
  - **通解** = 齐次解 + 特解
- **变量代换法**：通过代换将微分方程简化为标准形式
  - $x = e^t$ 代换化 Cauchy-Euler 方程
  - $y = ux$ 代换化齐次方程

**扩展应用**：
- 利用初值条件求特解
- 将实际问题建模为微分方程并解释解的含义

---

# 📘 三、Further Mechanics（Paper 3）

*前提知识：需掌握 9709 数学 Paper 4（力学）内容*

## 3.1 抛体运动（Motion of a Projectile）

**核心知识点**：
- 将抛体运动建模为**匀加速直线运动**的合成（水平匀速 + 竖直匀加速）
- 水平与竖直运动方程：
  - 水平：$x = Vt\cos\theta$
  - 竖直：$y = Vt\sin\theta - \frac{1}{2}gt^2$
- 求给定时刻或位置的速度**大小和方向**
- 水平射程（range on a horizontal plane）
- 最大高度（greatest height）
- **轨迹的笛卡尔方程**：
  - $y = x\tan\theta - \frac{gx^2}{2V^2\cos^2\theta}$
  - 即 $y = x\tan\theta - \frac{gx^2}{2V^2}(1+\tan^2\theta)$
- 初速度大小和/或抛射角未知时的求解

> ⚠️ 不要求向量方法；不要求"边界抛物线"（bounding parabola）

**扩展应用**：
- 已知轨迹经过某点，反求初速度或抛射角
- 斜面上的抛体运动

---

## 3.2 刚体平衡（Equilibrium of a Rigid Body）

**核心知识点**：
- **力矩**（Moment of a Force）：绕某点的力矩 = 力 × 力臂
  - 限于共面力系（coplanar forces）
- **质心**（Centre of Mass）：
  - 重力对刚体的作用等价于一个作用于质心的合力
  - 利用对称性求均匀物体的质心位置
  - 已知标准图形的质心位置：
    - 三角形薄板：中线上距顶点 $\frac{2}{3}$ 处
    - 均匀实心半球（半径 $r$）：距球心 $\frac{3}{8}r$
    - 均匀半球壳（半径 $r$）：距球心 $\frac{1}{2}r$
    - 均匀圆弧（半径 $r$，角度 $2\alpha$）：距圆心 $\frac{r\sin\alpha}{\alpha}$
    - 均匀扇形（半径 $r$，角度 $2\alpha$）：距圆心 $\frac{2r\sin\alpha}{3\alpha}$
    - 均匀圆锥/棱锥（高 $h$）：距顶点 $\frac{3}{4}h$
  - **组合体**的质心：将组合体分解为简单形状，用等效质点系方法求解
    - 如 L 形薄板、圆锥与半球相连等
- **共面力系平衡条件**：
  - 力的矢量和为零：$\sum \mathbf{F} = 0$
  - 对任意点的力矩和为零：$\sum M = 0$
- **平衡问题**：包括倾倒（toppling）和滑动（sliding）的分析

**扩展应用**：
- 求悬挂物体的平衡位置
- 求临界倾倒角
- 摩擦力参与下的平衡分析

---

## 3.3 圆周运动（Circular Motion）

**核心知识点**：
- **角速度**（Angular Speed）：$\omega$，与线速度关系 $v = r\omega$
- **向心加速度**（Centripetal Acceleration）：
  - 大小：$a = r\omega^2 = \frac{v^2}{r}$
  - 方向：指向圆心
- **水平圆周运动**（Horizontal Circle）：
  - 圆锥摆（conical pendulum）
  - 汽车在水平弯道
- **竖直圆周运动**（Vertical Circle）：
  - 能量守恒（无能量损失）
  - 求法向接触力或绳子张力
  - 力为零的位置（脱离轨道或绳子松弛的条件）
  - 完成完整圆周运动的条件

**扩展应用**：
- 在竖直圆轨道上的最底点和最高点速度与力的关系
- 结合弹性绳（如 3.4 Hooke's law）的圆锥摆问题

---

## 3.4 胡克定律（Hooke's Law）

**核心知识点**：
- **胡克定律**：弹性绳或弹簧中的力与伸长量/压缩量成正比
  - $T = \frac{\lambda}{l}x$，其中 $\lambda$ 为弹性模量（modulus of elasticity），$l$ 为自然长度，$x$ 为形变量
- **弹性势能**（Elastic Potential Energy）：
  - $E = \frac{\lambda x^2}{2l}$
- 综合应用：
  - 粒子水平或竖直运动，连接一根或多根弹性绳/弹簧
  - 斜面上的弹性体问题
  - 功和能量守恒的综合应用

**扩展应用**：
- 弹性绳连接的圆锥摆问题
- 弹簧的串联与并联
- 简谐运动的前期分析

---

## 3.5 变力作用下的直线运动（Linear Motion under a Variable Force）

**核心知识点**：
- 将实际问题建模为变力作用下的直线运动
- 建立并求解恰当的**微分方程**
- 加速度的另一种表达式：$a = v\frac{dv}{dx}$
- 限于**可分离变量**的微分方程（separable variables）
- 微积分知识限于 9709 Pure Mathematics 3 范围

**扩展应用**：
- 阻力与速度成正比的运动（$F \propto v$ 或 $F \propto v^2$）
- 万有引力下的运动
- 求终极速度（terminal velocity）
- 求位移或速度作为时间的函数

---

## 3.6 动量（Momentum）

**核心知识点**：
- **牛顿碰撞定律**（Newton's Experimental Law）：
  - 恢复系数（Coefficient of Restitution）：$e = \frac{\text{相对分离速度}}{\text{相对接近速度}}$
  - $0 \leq e \leq 1$
  - 完全弹性（perfectly elastic）：$e = 1$
  - 完全非弹性（inelastic）：$e = 0$
- **动量守恒定律**（Conservation of Linear Momentum）
- 碰撞问题：
  - 两个光滑球体的**对心碰撞**（direct impact）
  - 两个光滑球体的**斜碰**（oblique impact）
  - 光滑球体与固定平面的碰撞（含斜碰）

**扩展应用**：
- 多次碰撞问题
- 碰撞中的动能损失计算
- 球与球之间的连续碰撞

---

# 📘 四、Further Probability & Statistics（Paper 4）

*前提知识：需掌握 9709 数学 Papers 5 & 6（概率统计）内容*

## 4.1 连续随机变量（Continuous Random Variables）

**核心知识点**：
- **概率密度函数**（PDF）：可以是分段定义的 $f(x)$
  - 性质：$f(x) \geq 0$，$\int_{-\infty}^{\infty} f(x) dx = 1$
- **期望的一般公式**：$\displaystyle E[g(X)] = \int_{-\infty}^{\infty} g(x) f(x) dx$
- **累积分布函数**（CDF）$F(x) = P(X \leq x)$：
  - $F'(x) = f(x)$
  - 用 CDF 求概率：$P(a < X < b) = F(b) - F(a)$
  - 用 CDF 求百分位数（percentiles）
- **相关变量的 CDF**：
  - 已知 $X$ 的 CDF，求 $Y = g(X)$ 的 CDF，进而求 PDF
  - 如 $Y = X^3$，$Y = e^X$ 等

**扩展应用**：
- 求中位数、四分位数
- 变量变换的雅可比方法

---

## 4.2 正态分布与 t 分布推断（Inference using Normal and t-distributions）

**核心知识点**：
- **假设检验**（Hypothesis Testing）：
  - 建立原假设 $H_0$ 和备择假设 $H_1$
  - **t 检验**（用于小样本，总体方差未知，正态总体假定）
    - 单样本 t 检验：检验总体均值
  - **合并方差估计**（Pooled Estimate of Common Variance）：
    - $s_p^2 = \frac{(n_1-1)s_1^2 + (n_2-1)s_2^2}{n_1 + n_2 - 2}$
  - **两样本 t 检验**（2-sample t-test）
  - **配对 t 检验**（Paired-sample t-test）
  - 根据实际情况选择恰当的检验方法
- **置信区间**（Confidence Interval）：
  - 基于 t 分布的单总体均值置信区间
  - 基于 t 分布或正态分布的两总体均值之差置信区间

**扩展应用**：
- 原始数据与汇总数据的计算
- 检验的 p 值解读
- 两类错误分析

---

## 4.3 χ² 检验（Chi-squared Tests）

**核心知识点**：
- **拟合优度检验**（Goodness of Fit）：
  - 按给定假设拟合理论分布
  - 计算 $\chi^2 = \sum \frac{(O-E)^2}{E}$
  - 确定自由度（degrees of freedom）
  - 要求每组的期望频数 ≥ 5（不足则合并组）
- **列联表独立性检验**（Contingency Tables）：
  - 判断两个分类变量是否独立
  - 自由度 = (行数-1) × (列数-1)
  - 期望频数计算：$E_{ij} = \frac{\text{行合计}_i \times \text{列合计}_j}{\text{总合计}}$
  - 不要求 Yates 校正

**扩展应用**：
- 检验二项分布、泊松分布的拟合
- 检验均匀分布的拟合

---

## 4.4 非参数检验（Non-parametric Tests）

**核心知识点**：
- 非参数检验的**基本思想**和适用场景（不知道总体分布形态时）
- **符号检验**（Sign Test）：
  - 单样本：检验总体中位数
- **Wilcoxon 符号秩检验**（Wilcoxon Signed-Rank Test）：
  - 单样本：检验总体中位数
  - 配对样本：检验两总体的同质性（Wilcoxon matched-pairs signed-rank test）
  - 要求分布对称
- **Wilcoxon 秩和检验**（Wilcoxon Rank-Sum Test / Mann-Whitney U Test）：
  - 两独立样本：检验两总体分布是否相同
  - 要求分布对称
- **正态近似**：当样本量较大时用正态分布近似检验统计量

> ⚠️ 不涉及并列秩（tied ranks）或等于所检验中位数的观测值

**扩展应用**：
- 符号检验的临界值表查阅
- Wilcoxon 检验的临界值表查阅

---

## 4.5 概率生成函数（Probability Generating Functions, PGF）

**核心知识点**：
- **定义**：$G_X(t) = E(t^X) = \sum_{x} t^x P(X=x)$
- **常见分布的 PGF**：
  - 离散均匀分布
  - 二项分布 $B(n,p)$：$G(t) = (q + pt)^n$
  - 几何分布 $Geo(p)$：$G(t) = \frac{pt}{1-qt}$
  - 泊松分布 $Po(\lambda)$：$G(t) = e^{\lambda(t-1)}$
- **用 PGF 求均值和方差**：
  - $E(X) = G_X'(1)$
  - $\text{Var}(X) = G_X''(1) + G_X'(1) - [G_X'(1)]^2$
- **独立随机变量之和的 PGF**：
  - 若 $S = X_1 + X_2 + \cdots + X_n$，则 $G_S(t) = G_{X_1}(t) \cdot G_{X_2}(t) \cdots G_{X_n}(t)$

**扩展应用**：
- 利用 PGF 推导分布
- 利用 PGF 证明二项分布的可加性
- 利用 PGF 证明泊松分布的可加性

---

# 📝 附：评估目标（Assessment Objectives）

| AO | 描述 | AS Level 权重 | A Level 权重 |
|:--:|------|:------------:|:-----------:|
| AO1 | **知识与理解**：展示对数学概念、术语和符号的理解；准确回忆并运用适当的数学技巧 | 45% | 45% |
| AO2 | **应用与交流**：识别适当的数学方法；综合运用技能解决问题；清晰且有逻辑地展示数学过程和结论 | 55% | 55% |

---

# 📚 附：关键公式速览（MF19 公式册部分核心内容）

**求和公式**：
$$\sum r = \frac{n(n+1)}{2}, \quad \sum r^2 = \frac{n(n+1)(2n+1)}{6}, \quad \sum r^3 = \frac{n^2(n+1)^2}{4}$$

**Maclaurin 级数**：
$$e^x = 1 + x + \frac{x^2}{2!} + \cdots, \quad \ln(1+x) = x - \frac{x^2}{2} + \frac{x^3}{3} - \cdots$$

**双曲函数恒等式**：
$$\cosh^2 x - \sinh^2 x \equiv 1, \quad \sinh 2x \equiv 2\sinh x\cosh x$$

**抛体轨迹方程**：
$$y = x\tan\theta - \frac{gx^2}{2V^2\cos^2\theta}$$

**胡克定律**：
$$T = \frac{\lambda}{l}x, \quad E = \frac{\lambda x^2}{2l}$$

**圆周运动向心加速度**：
$$a = r\omega^2 = \frac{v^2}{r}$$

**质心位置**（部分）：实心半球 $\frac{3}{8}r$，圆锥/棱锥 $\frac{3}{4}h$，三角形薄板 $\frac{2}{3}$ 中线

**概率生成函数**：
$$G_X(t) = E(t^X), \quad E(X) = G_X'(1), \quad \text{Var}(X) = G_X''(1) + G_X'(1) - [G_X'(1)]^2$$

---

# 🔗 知识体系关系图

```
Paper 1: Further Pure Mathematics 1（基础纯数）
  ├── 多项式根 ↔ 矩阵（特征多项式）↔ Paper 2
  ├── 向量（3D）↔ Paper 2 矩阵
  ├── 极坐标 ↔ Paper 2 积分（弧长、面积）
  └── 归纳法 ↔ 全部证明基础

Paper 2: Further Pure Mathematics 2（进阶纯数）
  ├── 双曲函数 ↔ 微分 & 积分
  ├── 矩阵（特征值）↔ 微分方程（系统）
  ├── 复数 ↔ 三角恒等式 & 级数
  └── 微分方程 ↔ Paper 3 变力运动

Paper 3: Further Mechanics（进阶力学）
  ├── 抛体 ↔ 微分方程
  ├── 刚体平衡 ↔ 质心积分
  ├── 圆周运动 ↔ 能量守恒
  ├── 胡克定律 ↔ 弹性势能
  └── 动量 ↔ 碰撞守恒

Paper 4: Further Probability & Statistics（进阶概率统计）
  ├── 连续随机变量 ↔ 积分
  ├── t 检验 ↔ 正态分布
  ├── χ² 检验 ↔ 拟合优度
  ├── 非参数检验 ↔ 秩方法
  └── 概率生成函数 ↔ 级数
```

---

以上就是剑桥国际 AS & A Level 进阶数学（9231）2028-2030 考纲的全部知识体系总结与扩展。该大纲涵盖了**纯数学（两卷）**、**力学**和**概率统计**四大领域共 **21 个主题**，内容深度远超普通 A Level 数学，为大学数学、物理、工程、经济等专业奠定了坚实基础。
