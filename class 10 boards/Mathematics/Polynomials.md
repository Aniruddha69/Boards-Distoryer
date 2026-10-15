# 1. General Forms of Polynomials

## General Form of Any Polynomial of Degree $n$  

A polynomial $P(x)$ in one variable $x$ of degree $n$ is an expression of the form:

$$P(x) = a_n x^n + a_{n-1} x^{n-1} + a_{n-2} x^{n-2} + \dots + a_1 x + a_0$$

- **Conditions:**
    
    - $a_n, a_{n-1}, \dots, a_0$ are real numbers (coefficients).
        
    - $a_n \neq 0$ (leading coefficient cannot be zero).
        
    - All powers of $x$ ($n, n-1, \dots$) must be **non-negative integers** (whole numbers).
        

## General Form of a Quadratic Polynomial

A polynomial of degree $2$ is called a **quadratic polynomial**:

$$P(x) = ax^2 + bx + c, \quad \text{where } a \neq 0 \text{ and } a, b, c \in \mathbb{R}$$

- **Degree:** $2$  
    
- **Maximum number of real zeroes:** $2$  
    

# 2. Relationship Between Zeroes and Coefficients

Let $\alpha$ and $\beta$ be the zeroes of the quadratic polynomial $P(x) = ax^2 + bx + c$.

## Core Formulae

1. **Sum of Zeroes:**  
    
    $$\alpha + \beta = -\frac{b}{a} = -\frac{\text{Coefficient of } x}{\text{Coefficient of } x^2}$$
2. **Product of Zeroes:**  
    
    $$\alpha \beta = \frac{c}{a} = \frac{\text{Constant term}}{\text{Coefficient of } x^2}$$

## Forming a Quadratic Polynomial Given Its Zeroes

If the sum of zeroes $S = (\alpha + \beta)$ and the product of zeroes $P = (\alpha \beta)$ are given:

$$P(x) = k \left( x^2 - (\alpha + \beta)x + \alpha\beta \right) = k \left( x^2 - Sx + P \right)$$

_(where_ $k$ _is any non-zero real constant)._

# 3. Methods to Find Zeroes of a Quadratic Polynomial

To find the zeroes, we set $P(x) = 0$ and factorise.

## Method 1: Splitting the Middle Term

Used when the polynomial has all three terms: $ax^2 + bx + c$.

- **Rule:** Find two numbers $p$ and $q$ such that:  
    
    $$p + q = b \quad \text{and} \quad p \times q = a \times c$$

#### Example

**Find the zeroes of** $P(x) = x^2 - 2x - 8$**.**

- **Solution:**
    
    - Here $a = 1$, $b = -2$, $c = -8$. Product $ac = -8$, Sum $b = -2$.
        
    - Factors of $-8$ that add up to $-2$ are $-4$ and $+2$.  
        
        $$x^2 - 4x + 2x - 8 = 0$$$$x(x - 4) + 2(x - 4) = 0$$$$(x - 4)(x + 2) = 0$$$$\implies x = 4 \quad \text{or} \quad x = -2$$
- **Zeroes:** $\alpha = 4, \beta = -2$.
    

## Method 2: Using Algebraic Identities

Used frequently when $b = 0$ (missing $x$-term) using $a^2 - b^2 = (a - b)(a + b)$, or for perfect square trinomials $a^2 \pm 2ab + b^2 = (a \pm b)^2$.

#### Example

**Find the zeroes of** $P(x) = t^2 - 15$**.**

- **Solution:**
    
    - Express as difference of squares:  
        
        $$t^2 - (\sqrt{15})^2 = 0$$$$(t - \sqrt{15})(t + \sqrt{15}) = 0$$$$\implies t = \sqrt{15} \quad \text{or} \quad t = -\sqrt{15}$$
- **Zeroes:** $\alpha = \sqrt{15}, \beta = -\sqrt{15}$.
    

## Method 3: Taking the Variable Common

Used when $c = 0$ (constant term is missing): $ax^2 + bx = 0$.

#### Example

**Find the zeroes of** $P(x) = 4u^2 + 8u$**.**

- **Solution:**
    
    - Take the common factor $4u$ out:  
        
        $$4u(u + 2) = 0$$$$4u = 0 \implies u = 0$$$$u + 2 = 0 \implies u = -2$$
- **Zeroes:** $\alpha = 0, \beta = -2$.
    

# 4. Must-Know Symmetric Identities for $\alpha$ and $\beta$  

Every symmetric function must be expressed strictly in terms of $(\alpha + \beta)$ and $(\alpha\beta)$:

|   |   |
|---|---|
|**Target Expression**|**Expressed in Terms of (α+β) and αβ**|
|$\alpha^2 + \beta^2$|$(\alpha + \beta)^2 - 2\alpha\beta$|
|$(\alpha - \beta)^2$|$(\alpha + \beta)^2 - 4\alpha\beta$|
|$\alpha - \beta$|$\pm\sqrt{(\alpha + \beta)^2 - 4\alpha\beta}$|
|$\alpha^2 - \beta^2$|$(\alpha + \beta)(\alpha - \beta) = (\alpha + \beta)\sqrt{(\alpha + \beta)^2 - 4\alpha\beta}$|
|$\alpha^3 + \beta^3$|$(\alpha + \beta)^3 - 3\alpha\beta(\alpha + \beta)$|
|$\alpha^3 - \beta^3$|$(\alpha - \beta)(\alpha^2 + \alpha\beta + \beta^2) = (\alpha - \beta)\left[(\alpha + \beta)^2 - \alpha\beta\right]$|
|$\frac{1}{\alpha} + \frac{1}{\beta}$|$\frac{\alpha + \beta}{\alpha\beta}$|
|$\frac{\alpha}{\beta} + \frac{\beta}{\alpha}$|$\frac{\alpha^2 + \beta^2}{\alpha\beta} = \frac{(\alpha + \beta)^2 - 2\alpha\beta}{\alpha\beta}$|
|$\alpha^4 + \beta^4$|$(\alpha^2 + \beta^2)^2 - 2(\alpha\beta)^2 = \left[(\alpha + \beta)^2 - 2\alpha\beta\right]^2 - 2(\alpha\beta)^2$|

# 5. High-Yield PYQs & Important Questions

## Q1 (CBSE 2019, 2023) — Finding $\alpha^2 + \beta^2$ and Fractions

**If** $\alpha$ **and** $\beta$ **are zeroes of the quadratic polynomial** $f(x) = 2x^2 - 5x + 7$**, find the value of:**

1. $\alpha^2 + \beta^2$  
    
2. $\frac{1}{\alpha} + \frac{1}{\beta}$  
    

- **Solution:** For $2x^2 - 5x + 7$, $a = 2, b = -5, c = 7$.  
    
    $$\alpha + \beta = -\frac{b}{a} = \frac{5}{2}$$$$\alpha\beta = \frac{c}{a} = \frac{7}{2}$$
    1. **For** $\alpha^2 + \beta^2$**:**  
        
        $$\alpha^2 + \beta^2 = (\alpha + \beta)^2 - 2\alpha\beta$$$$= \left(\frac{5}{2}\right)^2 - 2\left(\frac{7}{2}\right) = \frac{25}{4} - 7 = \frac{25 - 28}{4} = -\frac{3}{4}$$
    2. **For** $\frac{1}{\alpha} + \frac{1}{\beta}$**:**  
        
        $$\frac{1}{\alpha} + \frac{1}{\beta} = \frac{\alpha + \beta}{\alpha\beta} = \frac{\frac{5}{2}}{\frac{7}{2}} = \frac{5}{7}$$

## Q2 (CBSE 2020) — Finding $\alpha^3 + \beta^3$  

**If** $\alpha$ **and** $\beta$ **are zeroes of** $p(x) = 3x^2 - 6x + 4$**, find the value of** $\alpha^3 + \beta^3$**.**

- **Solution:** Here $a = 3, b = -6, c = 4$.  
    
    $$\alpha + \beta = -\frac{-6}{3} = 2$$$$\alpha\beta = \frac{4}{3}$$
    
    Using the identity:  
    
    $$\alpha^3 + \beta^3 = (\alpha + \beta)^3 - 3\alpha\beta(\alpha + \beta)$$$$\alpha^3 + \beta^3 = (2)^3 - 3\left(\frac{4}{3}\right)(2)$$$$\alpha^3 + \beta^3 = 8 - 4(2) = 8 - 8 = 0$$

## Q3 (CBSE 2015, 2018) — Finding $(\alpha - \beta)$ and Unknown Constant $k$  

**If the zeroes** $\alpha, \beta$ **of the polynomial** $f(x) = x^2 - 5x + k$ **satisfy the relation** $\alpha - \beta = 1$**, find the value of** $k$**.**

- **Solution:** From the polynomial $x^2 - 5x + k$:  
    
    $$\alpha + \beta = 5, \quad \alpha\beta = k$$
    
    We know that:  
    
    $$(\alpha - \beta)^2 = (\alpha + \beta)^2 - 4\alpha\beta$$
    
    Substitute the given values:  
    
    $$(1)^2 = (5)^2 - 4(k)$$$$1 = 25 - 4k$$$$4k = 24 \implies k = 6$$

## Q4 (CBSE 2021) — Finding $\alpha^2 - \beta^2$  

**If** $\alpha, \beta$ **are the zeroes of the quadratic polynomial** $p(x) = x^2 - 4x + 3$**, find the value of** $\alpha^2 - \beta^2$ **(assuming** $\alpha > \beta$**).**

- **Solution:** Here $a = 1, b = -4, c = 3$.  
    
    $$\alpha + \beta = 4, \quad \alpha\beta = 3$$
    
    First calculate $(\alpha - \beta)$:  
    
    $$(\alpha - \beta)^2 = (\alpha + \beta)^2 - 4\alpha\beta = (4)^2 - 4(3) = 16 - 12 = 4$$$$\implies \alpha - \beta = \sqrt{4} = 2 \quad (\text{since } \alpha > \beta)$$
    
    Now calculate $\alpha^2 - \beta^2$:  
    
    $$\alpha^2 - \beta^2 = (\alpha + \beta)(\alpha - \beta) = (4)(2) = 8$$

## Q5 (CBSE 2024 Sample Paper) — Forming a New Polynomial with Modified Zeroes

**If $\alpha$ and $\beta$ are the zeroes of the polynomial $2x^2 - 4x + 1$, form a quadratic polynomial whose zeroes are $\frac{1}{\alpha}$ and $\frac{1}{\beta}$.**

- **Solution:** For $2x^2 - 4x + 1$:  
    
    $$\alpha + \beta = -\frac{-4}{2} = 2, \quad \alpha\beta = \frac{1}{2}$$
    
    Let the zeroes of the required polynomial be $\alpha' = \frac{1}{\alpha}$ and $\beta' = \frac{1}{\beta}$.
    
    - **Sum of new zeroes (**$S'$**):**  
        
        $$S' = \frac{1}{\alpha} + \frac{1}{\beta} = \frac{\alpha + \beta}{\alpha\beta} = \frac{2}{\frac{1}{2}} = 4$$
    - **Product of new zeroes (**$P'$**):**  
        
        $$P' = \left(\frac{1}{\alpha}\right)\left(\frac{1}{\beta}\right) = \frac{1}{\alpha\beta} = \frac{1}{\frac{1}{2}} = 2$$
    - **Required Polynomial:**  
        
        $$k(x^2 - S'x + P') = k(x^2 - 4x + 2)$$
        
        _(Taking_ $k = 1$_, the polynomial is_ $x^2 - 4x + 2$_.)_
