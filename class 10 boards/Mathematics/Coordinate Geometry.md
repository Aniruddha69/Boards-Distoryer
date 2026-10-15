# Class 10 Mathematics: Coordinate Geometry (Complete Guide & PYQs)

## 1. Foundational Concepts & Terminology

Every point on the two-dimensional Cartesian plane is denoted by an ordered pair $(x, y)$.

### Basic Terms

- **Abscissa (**$x$**-coordinate):** The perpendicular distance of a point from the $y$**-axis**, measured along the $x$-axis.
    
- **Ordinate (**$y$**-coordinate):** The perpendicular distance of a point from the $x$**-axis**, measured along the $y$-axis.
    
- **Origin (**$O$**):** The intersection point of the coordinate axes, denoted as $(0, 0)$.
    

### Crucial Distance-from-Axes Rules (Direct MCQ Trap!)

For any general point $P(x, y)$:

$$\text{Perpendicular distance from } x\text{-axis} = \vert{}y\vert{} = \vert{}\text{ordinate}\vert{}$$$$\text{Perpendicular distance from } y\text{-axis} = \vert{}x\vert{} = \vert{}\text{abscissa}\vert{}$$

> **Exam Alert:** Distance is **always non-negative**. If a point is $P(-4, -7)$, its distance from the $x$-axis is $\vert{}-7\vert{} = 7$ units, and its distance from the $y$-axis is $\vert{}-4\vert{} = 4$ units. Never write a negative distance.

### Sign Conventions by Quadrant

|   |   |   |   |
|---|---|---|---|
|**Quadrant**|**Sign of Abscissa (x)**|**Sign of Ordinate (y)**|**Form of Point**|
|**Quadrant I**|$+$|$+$|$(+, +)$|
|**Quadrant II**|$-$|$+$|$(-, +)$|
|**Quadrant III**|$-$|$-$|$(-, -)$|
|**Quadrant IV**|$+$|$-$|$(+, -)$|

- **Points on the** $x$**-axis:** Have ordinate $y = 0 \implies (x, 0)$  
    
- **Points on the** $y$**-axis:** Have abscissa $x = 0 \implies (0, y)$  
    

## 2. The Distance Formula

The distance between any two points $A(x_1, y_1)$ and $B(x_2, y_2)$ is given by:

$$d(A, B) = AB = \sqrt{(x_2 - x_1)^2 + (y_2 - y_1)^2}$$

### Distance from the Origin

The distance of point $P(x, y)$ from the origin $O(0, 0)$ is:

$$OP = \sqrt{x^2 + y^2}$$

### Checking Geometric Figures Using Distance

To prove the type of geometric figure formed by vertices:

1. **Equilateral Triangle:** All three sides equal ($AB = BC = CA$).
    
2. **Isosceles Triangle:** Any two sides equal ($AB = AC \neq BC$).
    
3. **Right-Angled Triangle:** Satisfies Pythagoras' Theorem ($AB^2 + BC^2 = AC^2$).
    
4. **Collinear Points:** Three points $A, B, C$ are collinear if the sum of any two distances equals the third ($AB + BC = AC$).
    
5. **Parallelogram:** Opposite sides are equal ($AB = CD$ and $BC = DA$). Diagonals are **not** equal ($AC \neq BD$).
    
6. **Rectangle:** Opposite sides are equal ($AB = CD$, $BC = DA$) **and** diagonals are equal ($AC = BD$).
    
7. **Rhombus:** All four sides are equal ($AB = BC = CD = DA$). Diagonals are **not** equal ($AC \neq BD$).
    
8. **Square:** All four sides are equal **and** diagonals are equal ($AC = BD$).
    

## 3. The Section Formula

Let a line segment joining $A(x_1, y_1)$ and $B(x_2, y_2)$ be divided internally by point $P(x, y)$ in the ratio $m_1 : m_2$:

$$P(x, y) = \left( \frac{m_1 x_2 + m_2 x_1}{m_1 + m_2}, \; \frac{m_1 y_2 + m_2 y_1}{m_1 + m_2} \right)$$

```
A(x1, y1) ----------- m1 ----------- P(x, y) ----- m2 ----- B(x2, y2)
```

### The $k : 1$ Method (High-Speed Ratio Finder)

When the ratio is unknown, **always assume the ratio as** $k : 1$:

$$P(x, y) = \left( \frac{k x_2 + x_1}{k + 1}, \; \frac{k y_2 + y_1}{k + 1} \right)$$

- If point $P$ lies on the $x$**-axis**, equate the $y$-coordinate to $0$: $\dfrac{k y_2 + y_1}{k + 1} = 0 \implies k = -\dfrac{y_1}{y_2}$.
    
- If point $P$ lies on the $y$**-axis**, equate the $x$-coordinate to $0$: $\dfrac{k x_2 + x_1}{k + 1} = 0 \implies k = -\dfrac{x_1}{x_2}$.
    

## 4. Midpoint Formula & Special Applications

### Midpoint Formula

When $P$ bisects the segment $AB$ ($m_1 : m_2 = 1 : 1$):

$$M = \left( \frac{x_1 + x_2}{2}, \; \frac{y_1 + y_2}{2} \right)$$

### Finding the Fourth Vertex of a Parallelogram (MCQ Speed-Hack)

In a parallelogram $ABCD$, diagonals $AC$ and $BD$ bisect each other at the same midpoint:

$$\text{Midpoint of } AC = \text{Midpoint of } BD$$$$\left( \frac{x_1 + x_3}{2}, \frac{y_1 + y_3}{2} \right) = \left( \frac{x_2 + x_4}{2}, \frac{y_2 + y_4}{2} \right)$$$$\implies x_1 + x_3 = x_2 + x_4 \quad \text{and} \quad y_1 + y_3 = y_2 + y_4$$$$\therefore x_4 = x_1 + x_3 - x_2 \quad \text{and} \quad y_4 = y_1 + y_3 - y_2$$

## 5. Centroid of a Triangle

The centroid $G(x, y)$ is the point where the three medians of a triangle intersect. It divides each median in the ratio $2 : 1$.

For $\triangle ABC$ with vertices $A(x_1, y_1)$, $B(x_2, y_2)$, and $C(x_3, y_3)$:

$$G(x, y) = \left( \frac{x_1 + x_2 + x_3}{3}, \; \frac{y_1 + y_2 + y_3}{3} \right)$$

## 6. Points of Trisection

To find points $P$ and $Q$ that divide segment $AB$ into three equal parts ($AP = PQ = QB$):

- Point $P$ divides segment $AB$ internally in the ratio $1 : 2$.
    
- Point $Q$ divides segment $AB$ internally in the ratio $2 : 1$ (or $Q$ is the midpoint of $PB$).
    

## 7. Important CBSE Previous Year Questions (PYQs)

### Question 1: Finding an Equidistant Point on the $x$-axis (CBSE 2019, 2023)

**Find a point on the** $x$**-axis which is equidistant from the points** $A(2, -5)$ **and** $B(-2, 9)$**.**

- **Solution:**
    
    1. Let the point on the $x$-axis be $P(x, 0)$.
        
    2. Given $PA = PB \implies PA^2 = PB^2$.
        
    3. Using distance formula:  
        
        $$(x - 2)^2 + (0 - (-5))^2 = (x - (-2))^2 + (0 - 9)^2$$$$(x - 2)^2 + 25 = (x + 2)^2 + 81$$$$x^2 - 4x + 4 + 25 = x^2 + 4x + 4 + 81$$
    4. Cancel $x^2 + 4$ on both sides:  
        
        $$-4x + 25 = 4x + 81$$$$-8x = 56 \implies x = -7$$
- **Answer:** The required point is $(-7, 0)$.
    

### Question 2: Ratio Divided by an Axis & Point of Intersection (CBSE 2020, 2024)

**Find the ratio in which the line segment joining** $A(1, -5)$ **and** $B(-4, 5)$ **is divided by the** $x$**-axis. Also find the coordinates of the point of division.**

- **Solution:**
    
    1. Let the required ratio be $k : 1$, and let the point of division on the $x$-axis be $P(x, 0)$.
        
    2. By section formula:  
        
        $$P(x, 0) = \left( \frac{k(-4) + 1(1)}{k + 1}, \; \frac{k(5) + 1(-5)}{k + 1} \right)$$
    3. Equating the $y$-coordinate to $0$:  
        
        $$\frac{5k - 5}{k + 1} = 0 \implies 5k - 5 = 0 \implies k = 1$$
        
        So, the ratio is $1 : 1$ (i.e., $P$ is the midpoint).
        
    4. Now substitute $k = 1$ to find $x$:  
        
        $$x = \frac{-4(1) + 1}{1 + 1} = \frac{-3}{2}$$
- **Answer:** Ratio is $1 : 1$, and the point of division is $\left(-\frac{3}{2}, 0\right)$.
    

### Question 3: Finding Points of Trisection (CBSE 2018, 2022)

**Find the coordinates of the points of trisection of the line segment joining** $A(2, -2)$ **and** $B(-7, 4)$**.**

- **Solution:** Let $P$ and $Q$ be the points of trisection such that $AP = PQ = QB$.
    
    1. **Point** $P$ **divides** $AB$ **in ratio** $1 : 2$**:**  
        
        $$P = \left( \frac{1(-7) + 2(2)}{1 + 2}, \; \frac{1(4) + 2(-2)}{1 + 2} \right)$$$$P = \left( \frac{-7 + 4}{3}, \; \frac{4 - 4}{3} \right) = \left( \frac{-3}{3}, \; 0 \right) = (-1, 0)$$
    2. **Point** $Q$ **is the midpoint of** $PB$**:**  
        
        $$Q = \left( \frac{-1 + (-7)}{2}, \; \frac{0 + 4}{2} \right) = \left( \frac{-8}{2}, \; \frac{4}{2} \right) = (-4, 2)$$
- **Answer:** The points of trisection are $P(-1, 0)$ and $Q(-4, 2)$.
    

### Question 4: Fourth Vertex of a Parallelogram (CBSE 2017, 2021)

**If** $A(1, 2)$**,** $B(4, y)$**,** $C(x, 6)$ **and** $D(3, 5)$ **are the vertices of a parallelogram taken in order, find the values of** $x$ **and** $y$**.**

- **Solution:** In parallelogram $ABCD$, diagonals $AC$ and $BD$ bisect each other at the same point.
    
    $$\text{Midpoint of } AC = \left( \frac{1 + x}{2}, \; \frac{2 + 6}{2} \right) = \left( \frac{1 + x}{2}, \; 4 \right)$$$$\text{Midpoint of } BD = \left( \frac{4 + 3}{2}, \; \frac{y + 5}{2} \right) = \left( \frac{7}{2}, \; \frac{y + 5}{2} \right)$$
    
    Equating corresponding coordinates:
    
    1. $\dfrac{1 + x}{2} = \dfrac{7}{2} \implies 1 + x = 7 \implies x = 6$  
        
    2. $\dfrac{y + 5}{2} = 4 \implies y + 5 = 8 \implies y = 3$  
        
- **Answer:** $x = 6$ and $y = 3$.