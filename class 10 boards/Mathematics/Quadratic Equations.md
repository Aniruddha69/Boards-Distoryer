## 1. Introduction & Standard Form

A **quadratic equation** in the variable $x$ is an algebraic equation of the second degree.

### Standard Form
$$ax^2 + bx + c = 0$$

Where:
* $a, b, c \in \mathbb{R}$ (real coefficients)
* **$a \neq 0$** (If $a = 0$, the equation reduces to a linear equation $bx + c = 0$)
* $x$ is the unknown variable.

### Degree of the Equation
* The **degree** of a quadratic equation is **2** (the highest exponent/power of the variable $x$ is 2).

---

## 2. Roots of a Quadratic Equation

A real number $\alpha$ is called a **root** (or solution / zero) of the quadratic equation $ax^2 + bx + c = 0$ if:
$$a\alpha^2 + b\alpha + c = 0$$

* A quadratic equation can have at most **two roots** (by the Fundamental Theorem of Algebra).
* Geometrically, the roots correspond to the $x$-coordinates of the points where the parabola $y = ax^2 + bx + c$ intersects the $x$-axis.

---

## 3. Methods of Solving Quadratic Equations

### Method 1: Factorization (Splitting the Middle Term)

To solve $ax^2 + bx + c = 0$ by factorization:
1. Find two numbers $p$ and $q$ such that:
   $$p + q = b \quad \text{and} \quad p \cdot q = ac$$
2. Rewrite the middle term $bx$ as $px + qx$.
3. Factor by grouping terms:
   $$ax^2 + px + qx + c = 0 \implies (mx + n)(rx + s) = 0$$
4. Apply the Zero Product Rule:
   $$mx + n = 0 \quad \text{or} \quad rx + s = 0$$

#### Example (Factorization):
**Solve:** $x^2 - 5x + 6 = 0$
* Here, $a = 1, b = -5, c = 6 \implies ac = 6$.
* We need two numbers whose product is $6$ and sum is $-5$: $(-2)$ and $(-3)$.
$$x^2 - 2x - 3x + 6 = 0$$
$$x(x - 2) - 3(x - 2) = 0$$
$$(x - 2)(x - 3) = 0$$
$$\implies x = 2 \quad \text{or} \quad x = 3$$

---

### Method 2: Quadratic Formula (Shreedharacharya's Rule)

For the equation $ax^2 + bx + c = 0$ ($a \neq 0$), the roots are given by:
$$x = \frac{-b \pm \sqrt{b^2 - 4ac}}{2a}$$

#### Derivation (Completing the Square method):
1. Start with $ax^2 + bx + c = 0$.
2. Divide across by $a$:
   $$x^2 + \frac{b}{a}x + \frac{c}{a} = 0$$
3. Shift constant term to RHS:
   $$x^2 + \frac{b}{a}x = -\frac{c}{a}$$
4. Add $\left(\frac{b}{2a}\right)^2$ to both sides:
   $$x^2 + 2 \cdot x \cdot \frac{b}{2a} + \left(\frac{b}{2a}\right)^2 = \frac{b^2}{4a^2} - \frac{c}{a}$$
   $$\left(x + \frac{b}{2a}\right)^2 = \frac{b^2 - 4ac}{4a^2}$$
5. Take square roots:
   $$x + \frac{b}{2a} = \pm \frac{\sqrt{b^2 - 4ac}}{2a}$$
   $$x = \frac{-b \pm \sqrt{b^2 - 4ac}}{2a}$$

#### Example (Quadratic Formula):
**Solve:** $2x^2 - 7x + 3 = 0$
* $a = 2, b = -7, c = 3$
* $b^2 - 4ac = (-7)^2 - 4(2)(3) = 49 - 24 = 25$
* Applying formula:
  $$x = \frac{-(-7) \pm \sqrt{25}}{2(2)} = \frac{7 \pm 5}{4}$$
  $$x_1 = \frac{7 + 5}{4} = \frac{12}{4} = 3, \quad x_2 = \frac{7 - 5}{4} = \frac{2}{4} = \frac{1}{2}$$

---

## 4. Discriminant & Nature of Roots

The quantity **$D = b^2 - 4ac$** is called the **Discriminant** of the quadratic equation $ax^2 + bx + c = 0$. It determines the nature and number of real roots without explicitly solving the equation.

| Value of Discriminant ($D$) | Nature of Roots | Parabola $y = ax^2 + bx + c$ Intersection |
| :--- | :--- | :--- |
| **$D > 0$** | **Two distinct real roots** | Cuts $x$-axis at 2 distinct points |
| **$D = 0$** | **Two equal real roots** (coincident / repeated roots, $x = -\frac{b}{2a}$) | Touches $x$-axis at exactly 1 point (tangent) |
| **$D < 0$** | **No real roots** (imaginary / complex conjugate roots) | Does not intersect or touch $x$-axis |

### Key Conditions frequently tested in Board Exams:
1. **Condition for Real Roots:** $D \ge 0$ ($b^2 - 4ac \ge 0$).
2. **Condition for Equal Roots:** $D = 0$ ($b^2 - 4ac = 0$).
3. **If $a, b, c \in \mathbb{Q}$ and $D$ is a perfect square ($>0$):** Roots are **rational and distinct**.
4. **If $a, b, c \in \mathbb{Q}$ and $D > 0$ is NOT a perfect square:** Roots are **irrational conjugates** ($p + \sqrt{q}$ and $p - \sqrt{q}$).

---

### Nature of Roots: Worked Examples

#### Example A ($D > 0$):
Find nature of roots for $3x^2 - 5x + 2 = 0$.
* $a = 3, b = -5, c = 2$
* $D = (-5)^2 - 4(3)(2) = 25 - 24 = 1 > 0$
* **Conclusion:** Since $D > 0$, the equation has **two distinct real roots** (rational, since 1 is a perfect square).

#### Example B ($D = 0$):
Find value of $k$ for which $2x^2 - kx + 2 = 0$ has equal roots.
* $a = 2, b = -k, c = 2$
* For equal roots, $D = 0$:
  $$b^2 - 4ac = 0 \implies (-k)^2 - 4(2)(2) = 0$$
  $$k^2 - 16 = 0 \implies k^2 = 16 \implies k = \pm 4$$

#### Example C ($D < 0$):
Determine nature of roots of $2x^2 + 3x + 5 = 0$.
* $a = 2, b = 3, c = 5$
* $D = 3^2 - 4(2)(5) = 9 - 40 = -31 < 0$
* **Conclusion:** Since $D < 0$, the equation has **no real roots**.

---

## 5. Relation Between Roots and Coefficients

If $\alpha$ and $\beta$ are the roots of $ax^2 + bx + c = 0$:
* **Sum of roots:**
  $$\alpha + \beta = -\frac{b}{a} = -\frac{\text{Coefficient of } x}{\text{Coefficient of } x^2}$$
* **Product of roots:**
  $$\alpha \beta = \frac{c}{a} = \frac{\text{Constant term}}{\text{Coefficient of } x^2}$$

### Forming an Equation Given Its Roots:
If $\alpha$ and $\beta$ are given roots:
$$x^2 - (\alpha + \beta)x + \alpha\beta = 0$$
$$\implies x^2 - (\text{Sum of roots})x + (\text{Product of roots}) = 0$$

---

## 6. Board-Ready PYQs & Selected Sample Problems

### Section A: 1-Mark & 2-Mark Standard Questions

#### Q1. Find the value of $k$ for which the quadratic equation $kx(x - 2) + 6 = 0$ has two equal roots. (CBSE 2017, 2020)
**Solution:**
1. Simplify into standard form:
   $$kx^2 - 2kx + 6 = 0$$
   Here $a = k, b = -2k, c = 6$ (with $k \neq 0$).
2. For equal roots, $D = 0$:
   $$b^2 - 4ac = 0 \implies (-2k)^2 - 4(k)(6) = 0$$
   $$4k^2 - 24k = 0 \implies 4k(k - 6) = 0$$
3. Since $k \neq 0$ (otherwise degree is not 2), we have:
   $$\mathbf{k = 6}$$

---

#### Q2. If one root of the quadratic equation $2x^2 + px - 15 = 0$ is $-5$, find the value of $p$. Also find the other root. (CBSE 2018)
**Solution:**
1. Since $-5$ is a root, it must satisfy the equation:
   $$2(-5)^2 + p(-5) - 15 = 0$$
   $$2(25) - 5p - 15 = 0 \implies 50 - 15 - 5p = 0 \implies 35 = 5p \implies \mathbf{p = 7}$$
2. Substitute $p = 7$ back:
   $$2x^2 + 7x - 15 = 0$$
   $$2x^2 + 10x - 3x - 15 = 0$$
   $$2x(x + 5) - 3(x + 5) = 0 \implies (2x - 3)(x + 5) = 0$$
3. Therefore, other root is:
   $$\mathbf{x = \frac{3}{2}}$$

---

### Section B: 3-Mark Medium Problems

#### Q3. Solve for $x$: $\sqrt{3}x^2 + 10x + 7\sqrt{3} = 0$. (CBSE 2019)
**Solution:**
* $a = \sqrt{3}, b = 10, c = 7\sqrt{3}$
* Product $ac = \sqrt{3} \times 7\sqrt{3} = 21$.
* Two numbers whose product is 21 and sum is 10 are $7$ and $3$.
$$\sqrt{3}x^2 + 3x + 7x + 7\sqrt{3} = 0$$
$$\sqrt{3}x(x + \sqrt{3}) + 7(x + \sqrt{3}) = 0$$
$$(x + \sqrt{3})(\sqrt{3}x + 7) = 0$$
$$\implies \mathbf{x = -\sqrt{3}} \quad \text{or} \quad \mathbf{x = -\frac{7}{\sqrt{3}} = -\frac{7\sqrt{3}}{3}}$$

---

#### Q4. If the equation $(1 + m^2)x^2 + 2mcx + (c^2 - a^2) = 0$ has equal roots, prove that $c^2 = a^2(1 + m^2)$. (CBSE 2017)
**Proof:**
* Here: $A = (1 + m^2)$, $B = 2mc$, $C = (c^2 - a^2)$.
* For equal roots, discriminant $D = B^2 - 4AC = 0$:
  $$(2mc)^2 - 4(1 + m^2)(c^2 - a^2) = 0$$
  $$4m^2 c^2 - 4[(1)(c^2 - a^2) + m^2(c^2 - a^2)] = 0$$
* Divide entire equation by 4:
  $$m^2 c^2 - [c^2 - a^2 + m^2 c^2 - m^2 a^2] = 0$$
  $$m^2 c^2 - c^2 + a^2 - m^2 c^2 + m^2 a^2 = 0$$
  $$-c^2 + a^2(1 + m^2) = 0$$
  $$\mathbf{c^2 = a^2(1 + m^2)} \quad \text{(Hence Proved)}$$

---

### Section C: 4/5-Mark Long & Word Problems

#### Q5. Solve for $x$ ($x \neq -1, -2, -4$): (CBSE 2016, 2020)
$$\frac{1}{x + 1} + \frac{2}{x + 2} = \frac{4}{x + 4}$$

**Solution:**
1. Combine LHS:
   $$\frac{1(x + 2) + 2(x + 1)}{(x + 1)(x + 2)} = \frac{4}{x + 4}$$
   $$\frac{x + 2 + 2x + 2}{x^2 + 3x + 2} = \frac{4}{x + 4}$$
   $$\frac{3x + 4}{x^2 + 3x + 2} = \frac{4}{x + 4}$$
2. Cross-multiply:
   $$(3x + 4)(x + 4) = 4(x^2 + 3x + 2)$$
   $$3x^2 + 12x + 4x + 16 = 4x^2 + 12x + 8$$
   $$3x^2 + 16x + 16 = 4x^2 + 12x + 8$$
3. Bring all terms to one side:
   $$4x^2 - 3x^2 + 12x - 16x + 8 - 16 = 0$$
   $$x^2 - 4x - 8 = 0$$
4. Using quadratic formula ($a = 1, b = -4, c = -8$):
   $$D = (-4)^2 - 4(1)(-8) = 16 + 32 = 48$$
   $$x = \frac{-(-4) \pm \sqrt{48}}{2(1)} = \frac{4 \pm 4\sqrt{3}}{2} = \mathbf{2 \pm 2\sqrt{3}}$$

---

#### Q6. A motor boat whose speed is $18\text{ km/h}$ in still water takes $1\text{ hour}$ more to go $24\text{ km}$ upstream than to return downstream to the same spot. Find the speed of the stream. (CBSE 2018, 2023)

**Solution:**
1. Let speed of stream = $y\text{ km/h}$.
   * Speed upstream = $(18 - y)\text{ km/h}$ (Note: $y < 18$)
   * Speed downstream = $(18 + y)\text{ km/h}$
   * Distance = $24\text{ km}$
2. Time taken upstream $t_1 = \frac{24}{18 - y}$ hours.
   Time taken downstream $t_2 = \frac{24}{18 + y}$ hours.
3. According to question:
   $$t_1 - t_2 = 1$$
   $$\frac{24}{18 - y} - \frac{24}{18 + y} = 1$$
   $$24 \left[ \frac{(18 + y) - (18 - y)}{(18 - y)(18 + y)} \right] = 1$$
   $$24 \left[ \frac{2y}{324 - y^2} \right] = 1$$
   $$48y = 324 - y^2$$
   $$y^2 + 48y - 324 = 0$$
4. Factorize ($54 \times (-6) = -324$ and $54 - 6 = 48$):
   $$y^2 + 54y - 6y - 324 = 0$$
   $$y(y + 54) - 6(y + 54) = 0$$
   $$(y - 6)(y + 54) = 0$$
5. Since speed cannot be negative, $y \neq -54$.
   $$\mathbf{y = 6\text{ km/h}}$$
   * The speed of the stream is **$6\text{ km/h}$**.

---

## 7. Quick Revision Checklist & Common Exam Pitfalls

| Pitfall / Mistake                                                      | Correction / Best Practice                                                                            |
| :--------------------------------------------------------------------- | :---------------------------------------------------------------------------------------------------- |
| Forgetting $a \neq 0$ when determining parameters (e.g., $kx^2 + ...$) | Always write condition $k \neq 0$. If $k=0$, it ceases to be quadratic.                               |
| Missing negative sign when computing $-b$ in formula                   | Write explicitly: $-(-b)$ to avoid sign errors when $b < 0$.                                          |
| Writing $D > 0$ for "real roots"                                       | "Real roots" means **$D \ge 0$** (both distinct and equal are real). Only "distinct real" is $D > 0$. |
| Forgetting to reject inadmissible values in word problems              | Speeds, dimensions, times cannot be negative; check domain constraints (e.g., denominators $\neq 0$). |