## 1. General Form of a Pair of Linear Equations

A pair of linear equations in two variables $x$ and $y$ can be represented in either of the following two standard conventions:

### Standard Form 1 (Constants on the right side)

$$\begin{aligned} a_1 x + b_1 y &= c_1 \\ a_2 x + b_2 y &= c_2 \end{aligned}$$

### Standard Form 2 (Standard zero form)

$$\begin{aligned} a_1 x + b_1 y + c_1 &= 0 \\ a_2 x + b_2 y + c_2 &= 0 \end{aligned}$$

Where:

- $a_1, b_1, c_1, a_2, b_2, c_2$ are real numbers.
    
- $a_1^2 + b_1^2 \neq 0$ and $a_2^2 + b_2^2 \neq 0$ (coefficients of $x$ and $y$ cannot both be zero simultaneously in either equation).
    

## 2. Types of Solutions & Nature of Lines (Tabular Overview)

Given two equations in standard zero form ($a_1x + b_1y + c_1 = 0$ and $a_2x + b_2y + c_2 = 0$):

|   |   |   |   |
|---|---|---|---|
|**Ratio Comparison**|**Graphical Representation**|**Algebraic Interpretation**|**Consistency Status**|
|$\dfrac{a_1}{a_2} \neq \dfrac{b_1}{b_2}$|**Intersecting Lines** (cross at exactly 1 point)|Exactly **One Unique Solution**|**Consistent**|
|$\dfrac{a_1}{a_2} = \dfrac{b_1}{b_2} = \dfrac{c_1}{c_2}$|**Coincident Lines** (overlap completely)|**Infinitely Many Solutions**|**Consistent** (Dependent)|
|$\dfrac{a_1}{a_2} = \dfrac{b_1}{b_2} \neq \dfrac{c_1}{c_2}$|**Parallel Lines** (never meet)|**No Solution**|**Inconsistent**|

> **Important Examination Tip:** When checking ratios, ensure both equations are written in the **exact same form** (either both with constant on RHS or both with constant on LHS). A mismatch in constant placement flips signs and causes sign errors in ratio comparison.

## 3. Algebraic & Graphical Methods of Solution

### Method 1: The Substitution Method

#### Step-by-Step Procedure:

1. Choose one equation and express one variable purely in terms of the other (e.g., $y = \dots$ in terms of $x$).
    
2. Substitute this expression into the **other** equation to create a single-variable linear equation.
    
3. Solve for that variable.
    
4. Substitute the calculated numerical value back into the substitution expression from Step 1 to determine the second variable.
    

#### Illustrative Example:

Solve:

$$\begin{aligned} x + y &= 14 \quad \text{--- (1)} \\ x - y &= 4 \quad \enspace \text{--- (2)} \end{aligned}$$

- From $(2)$: $x = y + 4$  
    
- Substitute into $(1)$:
    
    $$(y + 4) + y = 14 \implies 2y = 10 \implies y = 5$$
- Substitute $y = 5$ into $x = y + 4$:
    
    $$x = 5 + 4 = 9$$
- **Solution:** $x = 9, y = 5$.
    

### Method 2: The Elimination Method

#### Step-by-Step Procedure:

1. Multiply one or both equations by suitable non-zero constants so that the coefficients of one variable become numerically equal (or opposites).
    
2. Add the equations (if the coefficients have opposite signs) or subtract them (if the coefficients have the same sign) to eliminate that variable.
    
3. Solve the resulting single-variable equation.
    
4. Substitute this value into either original equation to find the other variable.
    

#### Illustrative Example:

Solve:

$$\begin{aligned} 2x + 3y &= 8 \quad \text{--- (1)} \\ 4x + 6y &= 7 \quad \text{--- (2)} \end{aligned}$$

- Multiply $(1)$ by $2$:
    
    $$4x + 6y = 16 \quad \text{--- (3)}$$
- Subtract $(2)$ from $(3)$:
    
    $$(4x - 4x) + (6y - 6y) = 16 - 7 \implies 0 = 9 \quad \text{(False statement)}$$
- Since $0 = 9$ is impossible, the pair has **no solution** (lines are parallel).
    

### Method 3: The Graphical Method

To present a graphical solution clearly without diagram blocks, work with **coordinate solution tables** and an axis-relative coordinate plot.

#### Procedure:

1. Find at least two (preferably three) points $(x, y)$ satisfying each equation by assuming values for $x$ and solving for $y$.
    
2. Tabulate the points clearly.
    
3. Plot the ordered pairs on the Cartesian plane and draw straight lines through them.
    
4. Identify the point of intersection $P(x_0, y_0)$. That coordinate is the unique solution.
    

#### Example:

Solve graphically:

$$\begin{aligned} L_1: x - y + 1 &= 0 \implies y = x + 1 \\ L_2: 3x + 2y - 12 &= 0 \implies y = \frac{12 - 3x}{2} \end{aligned}$$

**Coordinate Table for** $L_1$ **(**$y = x + 1$**):**

|   |   |   |   |
|---|---|---|---|
|**x**|**0**|**1**|**2**|
|$y$|$1$|$2$|$3$|
|Points on $L_1$: $A(0, 1)$, $B(1, 2)$, $C(2, 3)$.||||

**Coordinate Table for** $L_2$ **(**$y = \frac{12 - 3x}{2}$**):**

|   |   |   |   |
|---|---|---|---|
|**x**|**0**|**2**|**4**|
|$y$|$6$|$3$|$0$|
|Points on $L_2$: $D(0, 6)$, $C(2, 3)$, $E(4, 0)$.||||

#### Plane Intersection Representation:

```
                         Y-axis
                           ^
                     (0,6) * D
                           |  \
                           |   \  L2: 3x + 2y - 12 = 0
                           |    \
                           |     * C(2, 3)  <-- Point of Intersection!
                     (0,1) *    / \
                  L1       |   /   \
              y = x + 1    |  /     \
    <----------------------*---------*----------------------> X-axis
                        (-1,0)     (4,0) E
                           |

```

- Both lines intersect at point $C(2, 3)$.
    
- Therefore, the unique solution is $x = 2, y = 3$.
    

## 4. Complicated PYQs & Most Probable Board Questions

### Question 1 (Special Symmetric Interchange Pattern — CBSE 2019, 2023)

**Solve for** $x$ **and** $y$**:**

$$\begin{aligned} 152x - 378y &= -74 \\ -378x + 152y &= -604 \end{aligned}$$

- **Concept:** When coefficients of $x$ and $y$ are interchanged ($ax + by = c_1$ and $bx + ay = c_2$), **add** the two equations once, then **subtract** them once. Never multiply by massive coefficients directly.
    
- **Solution:** Let:
    
    $$152x - 378y = -74 \quad \text{--- (1)}$$$$-378x + 152y = -604 \quad \text{--- (2)}$$
    
    **Step 1: Add** $(1)$ **and** $(2)$**:**
    
    $$(152 - 378)x + (-378 + 152)y = -74 - 604$$$$-226x - 226y = -678$$
    
    Divide entire equation by $-226$:
    
    $$x + y = 3 \quad \text{--- (3)}$$
    
    **Step 2: Subtract** $(2)$ **from** $(1)$**:**
    
    $$[152 - (-378)]x + [-378 - 152]y = -74 - (-604)$$$$530x - 530y = 530$$
    
    Divide entire equation by $530$:
    
    $$x - y = 1 \quad \text{--- (4)}$$
    
    **Step 3: Solve the simplified system** $(3)$ **and** $(4)$**:**
    
    $$(x + y) + (x - y) = 3 + 1 \implies 2x = 4 \implies x = 2$$
    
    Substitute $x = 2$ into $(3)$:
    
    $$2 + y = 3 \implies y = 1$$
- **Answer:** $x = 2, y = 1$.
    

### Question 2 (Equations Reducible to Linear Form — CBSE 2020, 2024)

**Solve for** $x$ **and** $y$ **(**$x+y \neq 0, x-y \neq 0$**):**

$$\frac{10}{x + y} + \frac{2}{x - y} = 4$$$$\frac{15}{x + y} - \frac{5}{x - y} = -2$$

- **Solution:** Let $u = \frac{1}{x + y}$ and $v = \frac{1}{x - y}$. The equations transform into:
    
    $$10u + 2v = 4 \implies 5u + v = 2 \quad \text{--- (1)}$$$$15u - 5v = -2 \quad \text{--- (2)}$$
    
    From $(1)$, $v = 2 - 5u$. Substitute into $(2)$:
    
    $$15u - 5(2 - 5u) = -2$$$$15u - 10 + 25u = -2$$$$40u = 8 \implies u = \frac{8}{40} = \frac{1}{5}$$
    
    Find $v$:
    
    $$v = 2 - 5\left(\frac{1}{5}\right) = 2 - 1 = 1$$
    
    Now substitute back to find $x$ and $y$:
    
    $$\frac{1}{x + y} = \frac{1}{5} \implies x + y = 5 \quad \text{--- (3)}$$$$\frac{1}{x - y} = 1 \implies x - y = 1 \quad \text{--- (4)}$$
    
    Adding $(3)$ and $(4)$:
    
    $$2x = 6 \implies x = 3$$
    
    Subtracting $(4)$ from $(3)$:
    
    $$2y = 4 \implies y = 2$$
- **Answer:** $x = 3, y = 2$.
    

### Question 3 (Upstream / Downstream Speed Problem — CBSE 2018, 2022)

**A boat goes** $30\text{ km}$ **upstream and** $44\text{ km}$ **downstream in** $10\text{ hours}$**. In** $13\text{ hours}$**, it can go** $40\text{ km}$ **upstream and** $55\text{ km}$ **downstream. Determine the speed of the stream and that of the boat in still water.**

- **Solution:**
    
    - Let speed of boat in still water $= x\text{ km/h}$.
        
    - Let speed of stream $= y\text{ km/h}$ ($x > y$).
        
    - Speed upstream $= (x - y)\text{ km/h}$.
        
    - Speed downstream $= (x + y)\text{ km/h}$.
        
    
    Using $\text{Time} = \dfrac{\text{Distance}}{\text{Speed}}$:
    
    $$\frac{30}{x - y} + \frac{44}{x + y} = 10 \quad \text{--- (1)}$$$$\frac{40}{x - y} + \frac{55}{x + y} = 13 \quad \text{--- (2)}$$
    
    Let $\frac{1}{x - y} = u$ and $\frac{1}{x + y} = v$:
    
    $$30u + 44v = 10 \quad \text{--- (3)}$$$$40u + 55v = 13 \quad \text{--- (4)}$$
    
    Multiply $(3)$ by $4$ and $(4)$ by $3$ to eliminate $u$:
    
    $$120u + 176v = 40 \quad \text{--- (5)}$$$$120u + 165v = 39 \quad \text{--- (6)}$$
    
    Subtract $(6)$ from $(5)$:
    
    $$11v = 1 \implies v = \frac{1}{11}$$
    
    Substitute $v = \frac{1}{11}$ into $(3)$:
    
    $$30u + 44\left(\frac{1}{11}\right) = 10 \implies 30u + 4 = 10 \implies 30u = 6 \implies u = \frac{1}{5}$$
    
    Now solve for $x$ and $y$:
    
    $$x - y = \frac{1}{u} = 5 \quad \text{--- (7)}$$$$x + y = \frac{1}{v} = 11 \quad \text{--- (8)}$$
    
    Adding $(7)$ and $(8)$:
    
    $$2x = 16 \implies x = 8\text{ km/h}$$
    
    Subtracting $(7)$ from $(8)$:
    
    $$2y = 6 \implies y = 3\text{ km/h}$$
- **Answer:** Speed of the boat in still water is $8\text{ km/h}$; speed of the stream is $3\text{ km/h}$.
    

### Question 4 (Conditions for Infinite Solutions with Parameters — CBSE 2021 Standard)

**For what values of** $a$ **and** $b$ **does the following pair of linear equations have an infinite number of solutions?**

$$\begin{aligned} 2x + 3y &= 7 \\ (a - b)x + (a + b)y &= 3a + b - 2 \end{aligned}$$

- **Solution:** For infinitely many solutions:
    
    $$\frac{a_1}{a_2} = \frac{b_1}{b_2} = \frac{c_1}{c_2}$$$$\frac{2}{a - b} = \frac{3}{a + b} = \frac{7}{3a + b - 2}$$
    
    **Equate first two fractions:**
    
    $$2(a + b) = 3(a - b) \implies 2a + 2b = 3a - 3b \implies a - 5b = 0 \implies a = 5b \quad \text{--- (1)}$$
    
    **Equate first and third fractions:**
    
    $$2(3a + b - 2) = 7(a - b)$$$$6a + 2b - 4 = 7a - 7b$$$$a - 9b = -4 \quad \text{--- (2)}$$
    
    Substitute $a = 5b$ from $(1)$ into $(2)$:
    
    $$5b - 9b = -4 \implies -4b = -4 \implies b = 1$$$$a = 5(1) = 5$$
- **Answer:** $a = 5$ and $b = 1$.