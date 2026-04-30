# Cambridge International AS & A Level Further Mathematics (9231) — Comprehensive Knowledge Summary & Expansion

This syllabus is valid for exams in **2028, 2029, and 2030**, comprising **4 examination papers**, **4 major sections**, covering **21 topic units**.

---

## 📌 Overall Structure

| Paper | Name | Duration | Marks | A Level Weighting | AS Level Weighting |
|-------|------|---------|-------|------------------|--------------------|
| Paper 1 | Further Pure Mathematics 1 | 2 hours | 75 | 30% | 60% (compulsory) |
| Paper 2 | Further Pure Mathematics 2 | 2 hours | 75 | 30% | — (A Level compulsory) |
| Paper 3 | Further Mechanics | 1.5 hours | 50 | 20% | 40% (choose one) |
| Paper 4 | Further Probability & Statistics | 1.5 hours | 50 | 20% | 40% (choose one) |

**AS Level Routes (choose one)**:
- **Route A**: Paper 1 + Paper 3 (Further Pure Mathematics 1 + Further Mechanics)
- **Route B**: Paper 1 + Paper 4 (Further Pure Mathematics 1 + Further Probability & Statistics)

**A Level Route**: All four papers must be taken (Paper 1 + 2 + 3 + 4)

---

# 📘 I. Further Pure Mathematics 1 (Paper 1)

## 1.1 Roots of Polynomial Equations

**Core Knowledge**:
- Understand and apply the relations between roots and coefficients (Vieta's formulas) for equations of degrees 2, 3, or 4
  - Quadratic: $ax^2+bx+c=0$, roots $\alpha,\beta$, then $\alpha+\beta=-\frac{b}{a}$, $\alpha\beta=\frac{c}{a}$
  - Cubic: $ax^3+bx^2+cx+d=0$, roots $\alpha,\beta,\gamma$, then $\sum\alpha=-\frac{b}{a}$, $\sum\alpha\beta=\frac{c}{a}$, $\alpha\beta\gamma=-\frac{d}{a}$
  - Quartic: similarly extended
- **Evaluating symmetric functions** of roots
- Using a substitution to obtain an equation whose roots are related in a simple way to those of the original equation
  - e.g., reciprocals, squares, or a simple linear function of the old roots

**Extended Applications**:
- Finding unknown coefficients given relationships between roots
- Constructing new equations via substitution: if original roots are $\alpha,\beta,\gamma$, new roots could be $k\alpha+m$, $\frac{1}{\alpha}$, $\alpha^2$, etc.

---

## 1.2 Rational Functions and Graphs

**Core Knowledge**:
- Sketching graphs of simple rational functions (numerator and denominator degree ≤ 2)
- Determining **oblique asymptotes** (when numerator degree exceeds denominator degree by 1)
- Using the discriminant to find the **set of values** (range) taken by the function
- Key graph features: turning points, asymptotes (vertical/horizontal/oblique), intercepts with axes

**Relationships between graphs**: understand and use the relationships among
- $y = f(x)$ and $y^2 = f(x)$
- $y = f(x)$ and $y = \frac{1}{f(x)}$
- $y = f(x)$ and $y = |f(x)|$
- $y = f(x)$ and $y = f(|x|)$

**Extended Applications**:
- Solving equations and inequalities using graph transformations
- Finding equations of asymptotes for rational functions
- Determining function ranges using the discriminant method

---

## 1.3 Summation of Series

**Core Knowledge**:
- Using standard summation results:
  - $\displaystyle\sum_{r=1}^{n} r = \frac{1}{2}n(n+1)$
  - $\displaystyle\sum_{r=1}^{n} r^2 = \frac{1}{6}n(n+1)(2n+1)$
  - $\displaystyle\sum_{r=1}^{n} r^3 = \frac{1}{4}n^2(n+1)^2$
- **Method of Differences**: Expressing the general term as a difference between successive terms, causing cancellation when summed
  - Often used in conjunction with partial fractions
- Recognising when a series converges and finding the sum to infinity

**Extended Applications**:
- Summing complex terms such as $r(r+1)(r+2)$
- Proving summation formulas using the method of differences
- Handling telescoping series

---

## 1.4 Matrices

**Core Knowledge**:
- Matrix addition, subtraction, and multiplication (including non-square matrices, up to 3×3)
- Zero matrix and identity (unit) matrix
- Meaning of **singular** and **non-singular** for square matrices
- For 2×2 and 3×3 matrices: evaluating determinants and finding inverses
  - Notation: $\det M$ for determinant, $I$ for identity matrix
  - Result: $(AB)^{-1} = B^{-1}A^{-1}$ (for non-singular matrices)
- **2×2 matrices representing geometric transformations** in the $x$-$y$ plane:
  - Rotation, reflection, enlargement, stretch, shear
  - Relationship between $A$ and $A^{-1}$
  - Matrix product $AB$ represents transformation $B$ followed by $A$
  - Determinant and area scale factor
- **Invariant points and lines** in the context of matrix transformations

**Extended Applications**:
- Finding the matrix representing a given transformation or sequence of transformations
- Locating invariant points and lines for a given transformation matrix

---

## 1.5 Polar Coordinates

**Core Knowledge**:
- Relationship between Cartesian and polar coordinates:
  - $x = r\cos\theta$, $y = r\sin\theta$
  - $r^2 = x^2 + y^2$, $\tan\theta = \frac{y}{x}$
- Converting curve equations between Cartesian and polar forms
- Sketching simple polar curves (typically for $0 \leq \theta \leq 2\pi$ or $-\pi \leq \theta \leq \pi$)
  - Key features: symmetry, coordinates of intersections with the initial line, behaviour at the pole, least/greatest values of $r$
- **Area of a sector**: $A = \frac{1}{2}\int_{\alpha}^{\beta} r^2 \, d\theta$

**Extended Applications**:
- Sketching cardioids, rose curves, spirals
- Finding intersection points of polar curves
- Calculating areas enclosed by polar curves

---

## 1.6 Vectors

**Core Knowledge**:
- **Equation of a plane** in three forms and interconversion:
  - $ax + by + cz = d$ (Cartesian form)
  - $\mathbf{r} \cdot \mathbf{n} = p$ (dot product form)
  - $\mathbf{r} = \mathbf{a} + \lambda\mathbf{b} + \mu\mathbf{c}$ (parametric form)
- **Vector (cross) product**:
  - $\mathbf{a} \times \mathbf{b} = |\mathbf{a}||\mathbf{b}|\sin\theta \,\hat{\mathbf{n}}$
  - Component form: $\mathbf{a} \times \mathbf{b} = (a_2b_3 - a_3b_2)\mathbf{i} + (a_3b_1 - a_1b_3)\mathbf{j} + (a_1b_2 - a_2b_1)\mathbf{k}$
- **Solving problems** concerning distances, angles, and intersections:
  - Determining whether a line lies in a plane, is parallel to, or intersects a plane; finding intersection point
  - Finding the foot of the perpendicular from a point to a plane
  - Finding the angle between a line and a plane, and between two planes
  - Finding the line of intersection of two planes
  - Calculating the **shortest distance between two skew lines**
  - Finding the equation of the **common perpendicular** to two skew lines

**Extended Applications**:
- Distance from a point to a line
- Using scalar (dot) products for perpendicularity tests
- Using vector products to find normal vectors

---

## 1.7 Proof by Induction

**Core Knowledge**:
- Using mathematical induction to establish a given result
  - **Base case**: Verify for $n=1$ (or smallest $n$)
  - **Inductive hypothesis**: Assume true for $n=k$
  - **Inductive step**: Prove true for $n=k+1$
  - **Conclusion**: By induction, true for all positive integers

**Types of statements provable**:
- Summation formulas (e.g., $\sum r^4$)
- Recurrence sequences (e.g., $u_1=1$, $u_{n+1}=2u_n+1$, prove $u_n=2^n-1$)
- Divisibility results (e.g., $3^{2n}+2^{6n-5}$ divisible by 11)
- Derivative formulas (e.g., $n$th derivative of $xe^x$)
- Matrix powers (e.g., $A^n$ expression)

**Extended Applications**:
- Recognising situations where conjecture based on limited trial followed by inductive proof is useful
- Proving $\sum r \cdot r!$

---

# 📘 II. Further Pure Mathematics 2 (Paper 2)

*Prerequisite: Knowledge of Paper 1 content is assumed*

## 2.1 Hyperbolic Functions

**Core Knowledge**:
- **Definitions** (in terms of exponential functions):
  - $\sinh x = \frac{e^x - e^{-x}}{2}$
  - $\cosh x = \frac{e^x + e^{-x}}{2}$
  - $\tanh x = \frac{\sinh x}{\cosh x} = \frac{e^x - e^{-x}}{e^x + e^{-x}}$
  - $\text{sech}\,x = \frac{1}{\cosh x}$, $\text{cosech}\,x = \frac{1}{\sinh x}$, $\coth x = \frac{1}{\tanh x}$
- Sketching graphs of hyperbolic functions
- **Identities** (note sign differences from trigonometric identities):
  - $\cosh^2 x - \sinh^2 x \equiv 1$
  - $\sinh 2x \equiv 2\sinh x \cosh x$
  - $\cosh 2x \equiv \cosh^2 x + \sinh^2 x$
- **Inverse hyperbolic functions** and their logarithmic forms:
  - $\sinh^{-1} x = \ln(x + \sqrt{x^2 + 1})$ (all $x$)
  - $\cosh^{-1} x = \ln(x + \sqrt{x^2 - 1})$ ($x \geq 1$)
  - $\tanh^{-1} x = \frac{1}{2}\ln\frac{1+x}{1-x}$ ($|x| < 1$)

**Extended Applications**:
- Proving hyperbolic function identities
- Analogous learning with trigonometric identities (Osborne's Rule)

---

## 2.2 Matrices (Advanced)

**Core Knowledge**:
- Formulating 3 linear equations in 3 unknowns as a matrix equation $A\mathbf{x} = \mathbf{b}$
- **Consistency/inconsistency** of 3 linear equations:
  - Singular matrix ↔ no unique solution (none or infinitely many)
  - Non-singular matrix ↔ unique solution
  - Geometric interpretation: three planes meeting at a point, along a line, or having no common points
- **Eigenvalues and eigenvectors**:
  - Characteristic equation: $\det(A - \lambda I) = 0$
  - Definition: $A\mathbf{e} = \lambda\mathbf{e}$
  - Finding eigenvalues and eigenvectors for 2×2 and 3×3 matrices (real and distinct eigenvalues only)
- **Matrix diagonalisation**: $A = QDQ^{-1}$, where $D$ is a diagonal matrix of eigenvalues and $Q$'s columns are eigenvectors
  - Application: calculating powers $A^n = QD^nQ^{-1}$
- **Cayley-Hamilton theorem**: a square matrix satisfies its own characteristic equation
  - Applications: finding successive powers, finding inverse matrices

**Extended Applications**:
- Proving that if $\lambda$ is an eigenvalue of $A$, then $\lambda^n$ is an eigenvalue of $A^n$
- Reducing high powers using the characteristic equation

---

## 2.3 Differentiation

**Core Knowledge**:
- Derivatives of hyperbolic functions:
  - $\frac{d}{dx}\sinh x = \cosh x$
  - $\frac{d}{dx}\cosh x = \sinh x$
  - $\frac{d}{dx}\tanh x = \text{sech}^2 x$
- Derivatives of inverse trigonometric and hyperbolic functions:
  - $\frac{d}{dx}\sin^{-1}x = \frac{1}{\sqrt{1-x^2}}$
  - $\frac{d}{dx}\cos^{-1}x = -\frac{1}{\sqrt{1-x^2}}$
  - $\frac{d}{dx}\sinh^{-1}x = \frac{1}{\sqrt{1+x^2}}$
  - $\frac{d}{dx}\cosh^{-1}x = \frac{1}{\sqrt{x^2-1}}$
  - $\frac{d}{dx}\tanh^{-1}x = \frac{1}{1-x^2}$
- Finding $\frac{d^2y}{dx^2}$ for implicitly or parametrically defined relations
- **Maclaurin series** expansion:
  - $f(x) = f(0) + f'(0)x + \frac{f''(0)}{2!}x^2 + \frac{f'''(0)}{3!}x^3 + \cdots$
  - Finding first few terms (general term not required)
  - Successive implicit differentiation may be used

**Standard expansions to know**:
- $e^x = 1 + x + \frac{x^2}{2!} + \frac{x^3}{3!} + \cdots$
- $\ln(1+x) = x - \frac{x^2}{2} + \frac{x^3}{3} - \frac{x^4}{4} + \cdots$
- $\sin x = x - \frac{x^3}{3!} + \frac{x^5}{5!} - \cdots$
- $\cos x = 1 - \frac{x^2}{2!} + \frac{x^4}{4!} - \cdots$
- $\tan x = x + \frac{x^3}{3} + \frac{2x^5}{15} + \cdots$
- $\sinh x = x + \frac{x^3}{3!} + \frac{x^5}{5!} + \cdots$
- $\cosh x = 1 + \frac{x^2}{2!} + \frac{x^4}{4!} + \cdots$
- $\tanh x = x - \frac{x^3}{3} + \frac{2x^5}{15} - \cdots$

---

## 2.4 Integration

**Core Knowledge**:
- Integrating hyperbolic functions
- **Standard integral forms**:
  - $\int \frac{1}{\sqrt{a^2 - x^2}} dx = \sin^{-1}\frac{x}{a}$ ($|x| < a$)
  - $\int \frac{1}{\sqrt{x^2 - a^2}} dx = \cosh^{-1}\frac{x}{a}$ ($x > a$)
  - $\int \frac{1}{\sqrt{a^2 + x^2}} dx = \sinh^{-1}\frac{x}{a}$
  - Using completing the square where necessary
- Trigonometric/hyperbolic substitutions
- **Reduction formulae**: establishing recurrence relations for definite integrals
  - e.g., $I_n = \int_0^{\pi/2} \sin^n x \, dx$, $I_n = \int_0^1 x^n e^{-x} dx$, $I_n = \int_0^{\pi/4} \sec^n x \, dx$
- **Approximating area using rectangles**: setting bounds for areas or deriving inequalities/limits for sums
  - e.g., $\sum_{r=1}^{n} \frac{1}{r}$ and its relation to $\ln n$
- **Arc length**:
  - Cartesian: $s = \int_a^b \sqrt{1 + \left(\frac{dy}{dx}\right)^2} dx$
  - Parametric: $s = \int_{t_1}^{t_2} \sqrt{\left(\frac{dx}{dt}\right)^2 + \left(\frac{dy}{dt}\right)^2} dt$
  - Polar: $s = \int_{\alpha}^{\beta} \sqrt{r^2 + \left(\frac{dr}{d\theta}\right)^2} d\theta$
- **Surface area of revolution**:
  - About $x$-axis: $S = 2\pi \int_a^b y \sqrt{1 + \left(\frac{dy}{dx}\right)^2} dx$
  - Parametric forms included

**Extended Applications**:
- More advanced integration by parts, e.g., $\int e^x \sin x \, dx$
- Substitution $t = \tan\frac{x}{2}$
- Polar coordinate arc length (may appear in questions)

---

## 2.5 Complex Numbers

**Core Knowledge**:
- **de Moivre's Theorem**:
  - For positive integer $n$: $(\cos\theta + i\sin\theta)^n = \cos n\theta + i\sin n\theta$
  - Extension to negative integer and rational exponents
  - Geometrical interpretation: multiplication and division of complex numbers as rotations and scalings
- **Applications**:
  1. **Multiple angle formulas**: expressing $\cos n\theta$, $\tan n\theta$ in terms of $\cos\theta$, $\tan\theta$
     - e.g., $\cos 5\theta = 16\cos^5\theta - 20\cos^3\theta + 5\cos\theta$
  2. **Powers of sine and cosine**: expressing $\sin^n\theta$ or $\cos^n\theta$ in terms of multiple angles
     - e.g., $\sin^6\theta$ in terms of $\cos 2\theta$, $\cos 4\theta$, $\cos 6\theta$
  3. **Summation of series**: using the "$C + iS$" method
     - e.g., $\sum_{r=1}^{n} \sin r\theta$, $\sum_{r=1}^{n} \cos r\theta$
  4. **Roots of unity**: solving $z^n = 1$
     - $z = e^{2\pi i k/n}$, $k = 0,1,2,\ldots,n-1$
     - Roots are equally spaced on the unit circle
     - Sum of all roots is 0 (for $n \geq 2$)

**Extended Applications**:
- Proving trigonometric identities using roots of unity
- Geometric applications of complex numbers

---

## 2.6 Differential Equations

**Core Knowledge**:
- **Integrating factor** for first-order linear differential equations:
  - Standard form: $\frac{dy}{dx} + P(x)y = Q(x)$
  - Integrating factor: $I = e^{\int P(x) dx}$
  - General solution: $y \cdot I = \int Q \cdot I \, dx$
- **Second-order linear differential equations with constant coefficients**:
  - **Complementary Function** (CF):
    - Auxiliary equation $am^2 + bm + c = 0$
    - Distinct real roots: $y = Ae^{m_1x} + Be^{m_2x}$
    - Repeated real root: $y = (A + Bx)e^{mx}$
    - Complex conjugate roots $m = \alpha \pm i\beta$: $y = e^{\alpha x}(A\cos\beta x + B\sin\beta x)$
  - **Particular Integral** (PI):
    - Polynomial form
    - $ae^{bx}$ form
    - $a\cos px + b\sin px$ form
    - Given a suitable form, find coefficients
  - **General solution** = CF + PI
- **Using substitutions** to reduce differential equations to simpler forms:
  - $x = e^t$ for Cauchy-Euler equations
  - $y = ux$ to reduce to separable form

**Extended Applications**:
- Using initial conditions to find particular solutions
- Interpreting solutions in terms of a modelled problem

---

# 📘 III. Further Mechanics (Paper 3)

*Prerequisite: Knowledge of 9709 Mathematics Paper 4 (Mechanics) is assumed*

## 3.1 Motion of a Projectile

**Core Knowledge**:
- Modelling projectile motion as a particle moving with constant acceleration
- Horizontal and vertical equations of motion:
  - Horizontal: $x = Vt\cos\theta$
  - Vertical: $y = Vt\sin\theta - \frac{1}{2}gt^2$
- Finding the magnitude and direction of velocity at a given time or position
- Range on a horizontal plane
- Greatest height reached
- **Cartesian equation of the trajectory**:
  - $y = x\tan\theta - \frac{gx^2}{2V^2\cos^2\theta}$
- Problems where initial speed and/or angle of projection are unknown

> ⚠️ Vector methods not required. Knowledge of the 'bounding parabola' is not included.

**Extended Applications**:
- Finding initial speed or angle given that the trajectory passes through a specific point
- Projectile motion on an inclined plane

---

## 3.2 Equilibrium of a Rigid Body

**Core Knowledge**:
- **Moment of a force** about a point (coplanar forces only)
- **Centre of mass**:
  - Gravity effect on a rigid body is equivalent to a single force acting at the centre of mass
  - Using symmetry to find centre of mass of uniform bodies
  - Known results for standard shapes:
    - Triangular lamina: $\frac{2}{3}$ along median from vertex
    - Solid hemisphere (radius $r$): $\frac{3}{8}r$ from centre
    - Hemispherical shell (radius $r$): $\frac{1}{2}r$ from centre
    - Circular arc (radius $r$, angle $2\alpha$): $\frac{r\sin\alpha}{\alpha}$ from centre
    - Circular sector (radius $r$, angle $2\alpha$): $\frac{2r\sin\alpha}{3\alpha}$ from centre
    - Solid cone/pyramid (height $h$): $\frac{3}{4}h$ from vertex
  - **Composite bodies**: determining centre of mass by considering equivalent system of particles
    - e.g., uniform L-shaped lamina, cone joined to hemisphere
- **Equilibrium conditions** for coplanar forces:
  - Vector sum of forces is zero
  - Sum of moments about any point is zero
- Solving equilibrium problems including **toppling** and **sliding**

**Extended Applications**:
- Finding equilibrium position of a suspended object
- Determining the critical angle for toppling
- Equilibrium with friction

---

## 3.3 Circular Motion

**Core Knowledge**:
- **Angular speed** $\omega$: relation $v = r\omega$
- **Centripetal acceleration**:
  - Magnitude: $a = r\omega^2 = \frac{v^2}{r}$
  - Direction: towards the centre of the circle
- **Horizontal circular motion**:
  - Conical pendulum
  - Other horizontal circle problems
- **Vertical circular motion**:
  - Without loss of energy (energy conservation)
  - Finding normal contact force or tension in a string
  - Locating points where these forces are zero
  - Conditions for completing a full circle

**Extended Applications**:
- Relationship between speed and force at the highest/lowest points of a vertical circle
- Conical pendulum combined with elastic strings (Hooke's law)

---

## 3.4 Hooke's Law

**Core Knowledge**:
- **Hooke's law**: force in an elastic string or spring is proportional to extension/compression
  - $T = \frac{\lambda}{l}x$, where $\lambda$ is the modulus of elasticity, $l$ is natural length, $x$ is extension/compression
- **Elastic potential energy** stored in a string or spring:
  - $E = \frac{\lambda x^2}{2l}$
- Solving problems involving forces due to elastic strings or springs:
  - Particles moving horizontally, vertically, or on an inclined plane
  - Attached to one or more strings/springs
  - Using work and energy considerations
  - Elastic string acting as a 'conical pendulum'

**Extended Applications**:
- Series and parallel combinations of springs
- Preliminary analysis of simple harmonic motion

---

## 3.5 Linear Motion under a Variable Force

**Core Knowledge**:
- Modelling problems as linear motion of a particle under a variable force
- Setting up and solving appropriate **differential equations**
- Alternative expression for acceleration: $a = v\frac{dv}{dx}$
- Limited to differential equations with **separable variables**
- Calculus restricted to Pure Mathematics 3 content from 9709

**Extended Applications**:
- Motion with resistance proportional to velocity ($F \propto v$) or $v^2$
- Motion under inverse-square law forces
- Finding terminal velocity
- Finding displacement or velocity as functions of time

---

## 3.6 Momentum

**Core Knowledge**:
- **Newton's Experimental Law**:
  - Coefficient of restitution: $e = \frac{\text{relative speed of separation}}{\text{relative speed of approach}}$
  - $0 \leq e \leq 1$
  - Perfectly elastic: $e = 1$
  - Inelastic: $e = 0$
- **Conservation of linear momentum**
- Impact problems:
  - **Direct impact** of two smooth spheres
  - **Oblique impact** of two smooth spheres
  - Direct or oblique impact of a smooth sphere with a fixed surface

**Extended Applications**:
- Successive collisions (multiple impacts)
- Calculating kinetic energy loss in collisions
- Series of collisions between multiple spheres

---

# 📘 IV. Further Probability & Statistics (Paper 4)

*Prerequisite: Knowledge of 9709 Mathematics Papers 5 & 6 (Probability & Statistics) is assumed*

## 4.1 Continuous Random Variables

**Core Knowledge**:
- **Probability density function** (PDF): may be defined piecewise
  - Properties: $f(x) \geq 0$, $\int_{-\infty}^{\infty} f(x) dx = 1$
- **Expectation of a function**: $\displaystyle E[g(X)] = \int_{-\infty}^{\infty} g(x) f(x) dx$
- **Cumulative distribution function** (CDF): $F(x) = P(X \leq x)$
  - Relationship: $F'(x) = f(x)$
  - Using CDF to evaluate probabilities: $P(a < X < b) = F(b) - F(a)$
  - Using CDF to find percentiles
- **CDFs of related variables**:
  - Given CDF of $X$, find CDF of $Y = g(X)$, then find its PDF
  - e.g., $Y = X^3$, $Y = e^X$, etc.

**Extended Applications**:
- Finding median, quartiles
- Jacobian method for variable transformation

---

## 4.2 Inference using Normal and t-distributions

**Core Knowledge**:
- **Hypothesis testing**:
  - Formulating null $H_0$ and alternative $H_1$ hypotheses
  - **t-test** (small sample, normal population, unknown variance):
    - One-sample t-test for population mean
  - **Pooled estimate of common variance** from two samples:
    - $s_p^2 = \frac{(n_1-1)s_1^2 + (n_2-1)s_2^2}{n_1 + n_2 - 2}$
  - **Two-sample t-test**
  - **Paired-sample t-test**
  - Test using normal distribution (when appropriate)
  - Selecting the appropriate test for given circumstances
- **Confidence intervals**:
  - For population mean (small sample, unknown variance) using t-distribution
  - For difference of population means using t-distribution or normal distribution

**Extended Applications**:
- Calculations from both raw and summarised data
- p-value interpretation
- Type I and Type II errors

---

## 4.3 Chi-squared (χ²) Tests

**Core Knowledge**:
- **Goodness of fit test**:
  - Fitting a theoretical distribution (as prescribed by a given hypothesis) to given data
  - Computing $\chi^2 = \sum \frac{(O-E)^2}{E}$
  - Determining degrees of freedom
  - Combining classes so that each expected frequency is at least 5
- **Contingency table test for independence**:
  - Testing whether two categorical variables are independent
  - Degrees of freedom = (rows - 1) × (columns - 1)
  - Expected frequency: $E_{ij} = \frac{\text{row total}_i \times \text{column total}_j}{\text{grand total}}$
  - Yates' correction is NOT required
  - Combine rows or columns so expected frequency in each cell is at least 5

**Extended Applications**:
- Testing fit of binomial and Poisson distributions
- Testing fit of uniform distribution

---

## 4.4 Non-parametric Tests

**Core Knowledge**:
- Understanding the idea of a **non-parametric test** and when it is useful
  - e.g., sampling from a population that cannot be assumed to be normally distributed
- **Sign test** (basis and application)
- **Wilcoxon signed-rank test** (basis and application)
- **Wilcoxon rank-sum test** (basis and application)
- Conditions: Wilcoxon tests are valid only for **symmetrical distributions**
- **Single-sample sign test** and **single-sample Wilcoxon signed-rank test**: testing hypothesis concerning a population median
  - Including normal approximations where appropriate
- **Paired-sample sign test**, **Wilcoxon matched-pairs signed-rank test**, and **Wilcoxon rank-sum test**: testing for identity of populations
  - Including normal approximations where appropriate

> ⚠️ Questions will NOT involve tied ranks or observations equal to the population median value being tested. Zero-difference pairs will not appear.

**Extended Applications**:
- Reading critical value tables for sign test and Wilcoxon tests
- Applying normal approximation for larger sample sizes

---

## 4.5 Probability Generating Functions (PGFs)

**Core Knowledge**:
- **Definition**: $G_X(t) = E(t^X) = \sum_{x} t^x P(X=x)$
- **PGFs for specific distributions**:
  - Discrete uniform
  - Binomial $B(n,p)$: $G(t) = (q + pt)^n$
  - Geometric $Geo(p)$: $G(t) = \frac{pt}{1-qt}$
  - Poisson $Po(\lambda)$: $G(t) = e^{\lambda(t-1)}$
- **Using PGFs to find mean and variance**:
  - $E(X) = G_X'(1)$
  - $\text{Var}(X) = G_X''(1) + G_X'(1) - [G_X'(1)]^2$
- **PGF of sum of independent random variables**:
  - If $S = X_1 + X_2 + \cdots + X_n$, then $G_S(t) = G_{X_1}(t) \cdot G_{X_2}(t) \cdots G_{X_n}(t)$

**Extended Applications**:
- Deriving distributions using PGFs
- Proving additivity of binomial distributions
- Proving additivity of Poisson distributions

---

# 📝 Appendix: Assessment Objectives (AOs)

| AO | Description | AS Level Weighting | A Level Weighting |
|:--:|-------------|:------------------:|:-----------------:|
| AO1 | **Knowledge and Understanding**: Show understanding of relevant mathematical concepts, terminology and notation; recall accurately and use appropriate mathematical manipulative techniques | 45% | 45% |
| AO2 | **Application and Communication**: Recognise the appropriate mathematical procedure for a given situation; apply appropriate combinations of skills and techniques in solving problems; present relevant mathematical work and communicate corresponding conclusions in a clear and logical way | 55% | 55% |

---

# 📚 Appendix: Key Formula Quick Reference (from MF19 Formula Booklet)

**Summation Formulas**:
$$\sum r = \frac{n(n+1)}{2}, \quad \sum r^2 = \frac{n(n+1)(2n+1)}{6}, \quad \sum r^3 = \frac{n^2(n+1)^2}{4}$$

**Maclaurin Series**:
$$e^x = 1 + x + \frac{x^2}{2!} + \cdots, \quad \ln(1+x) = x - \frac{x^2}{2} + \frac{x^3}{3} - \cdots$$

**Hyperbolic Identities**:
$$\cosh^2 x - \sinh^2 x \equiv 1, \quad \sinh 2x \equiv 2\sinh x\cosh x$$

**Projectile Trajectory**:
$$y = x\tan\theta - \frac{gx^2}{2V^2\cos^2\theta}$$

**Hooke's Law**:
$$T = \frac{\lambda}{l}x, \quad E = \frac{\lambda x^2}{2l}$$

**Circular Motion Acceleration**:
$$a = r\omega^2 = \frac{v^2}{r}$$

**Centres of Mass** (selected): Solid hemisphere $\frac{3}{8}r$, Cone/pyramid $\frac{3}{4}h$, Triangular lamina $\frac{2}{3}$ along median

**Probability Generating Functions**:
$$G_X(t) = E(t^X), \quad E(X) = G_X'(1), \quad \text{Var}(X) = G_X''(1) + G_X'(1) - [G_X'(1)]^2$$

---

# 🔗 Knowledge System Relationship Map

```
Paper 1: Further Pure Mathematics 1 (Foundation Pure Mathematics)
  ├── Polynomial Roots ↔ Matrices (characteristic polynomial) ↔ Paper 2
  ├── Vectors (3D) ↔ Paper 2 Matrices
  ├── Polar Coordinates ↔ Paper 2 Integration (arc lengths, areas)
  └── Proof by Induction ↔ Foundation for all proofs

Paper 2: Further Pure Mathematics 2 (Advanced Pure Mathematics)
  ├── Hyperbolic Functions ↔ Differentiation & Integration
  ├── Matrices (eigenvalues) ↔ Differential Equations (systems)
  ├── Complex Numbers ↔ Trigonometric Identities & Series
  └── Differential Equations ↔ Paper 3 Variable Force Motion

Paper 3: Further Mechanics (Advanced Mechanics)
  ├── Projectiles ↔ Differential Equations
  ├── Rigid Body Equilibrium ↔ Centre of Mass Integration
  ├── Circular Motion ↔ Energy Conservation
  ├── Hooke's Law ↔ Elastic Potential Energy
  └── Momentum ↔ Conservation in Collisions

Paper 4: Further Probability & Statistics (Advanced Probability & Statistics)
  ├── Continuous Random Variables ↔ Integration
  ├── t-tests ↔ Normal Distribution
  ├── χ² Tests ↔ Goodness of Fit
  ├── Non-parametric Tests ↔ Rank Methods
  └── Probability Generating Functions ↔ Series
```

---

This concludes the comprehensive English summary of the entire Cambridge International AS & A Level Further Mathematics (9231) syllabus for 2028-2030. The syllabus spans **four major domains** — **Pure Mathematics (two papers)**, **Mechanics**, and **Probability & Statistics** — across **21 topic units**, with depth and rigour far exceeding standard A Level Mathematics, providing a solid foundation for university-level study in mathematics, physics, engineering, economics, and related fields.
