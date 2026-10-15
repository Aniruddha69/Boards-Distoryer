# Class 10 Mathematics: Circles (Complete Guide & PYQ Bank)

## 1. Core Terminology & Concepts

- **Tangent:** A line that intersects the circle at exactly one single point.
    
- **Secant:** A line that intersects the circle at two distinct points.
    
- **Point of Contact:** The unique point where the tangent touches the circle.
    

**Quick Facts for 1-Mark Questions:**

- A circle can have **infinitely many** tangents.
    
- There can be at most **two** parallel tangents to a given secant/diameter.
    
- There is **no** tangent passing through a point lying _inside_ the circle.
    
- There is exactly **one** tangent passing through a point _on_ the circle.
    
- There are exactly **two** tangents passing through a point _outside_ the circle.
    

## 2. The Two Mandatory Board Proofs

There are only two theorems in this chapter. You must memorize these proofs exactly as written, as they are guaranteed high-probability questions.

### Theorem 10.1: Tangent-Radius Theorem

> **Statement:** The tangent at any point of a circle is perpendicular to the radius through the point of contact.

**Given:** A circle with center $O$ and a tangent $XY$ to the circle at a point $P$. **To Prove:** $OP \perp XY$  

**Proof:**

1. Take any point $Q$ on the tangent $XY$ other than $P$.
    
2. Join $OQ$.
    
3. Since $Q$ lies on the tangent $XY$ (and is not the point of contact $P$), $Q$ must lie **outside** the circle. _(If_ $Q$ _were inside,_ $XY$ _would become a secant, not a tangent)._
    
4. Therefore, the length of $OQ$ must be strictly greater than the radius of the circle.  
    
    $$OQ > OP$$
5. Since this happens for every point on the line $XY$ except the point $P$, $OP$ is the **shortest of all distances** from the center $O$ to the points on the line $XY$.
    
6. We know from geometry that the shortest distance from a point to a line is the perpendicular distance.
    
7. Hence, $OP \perp XY$. $\blacksquare$  
    

### Theorem 10.2: Length of Tangents Theorem

> **Statement:** The lengths of tangents drawn from an external point to a circle are equal.

**Given:** A circle with center $O$. $P$ is an external point, and $PA$ and $PB$ are two tangents drawn from $P$ to the circle. **To Prove:** $PA = PB$ **Construction:** Join $OA$, $OB$, and $OP$.

**Proof:**

1. We know that a tangent is perpendicular to the radius through the point of contact (Theorem 10.1). Therefore, $\angle OAP = 90^\circ$ and $\angle OBP = 90^\circ$.
    
2. Now, consider right-angled triangles $\triangle OAP$ and $\triangle OBP$:
    
    - $OA = OB$ (Radii of the same circle)
        
    - $OP = OP$ (Common hypotenuse)
        
    - $\angle OAP = \angle OBP = 90^\circ$ (Proved above)
        
3. By RHS (Right angle - Hypotenuse - Side) congruence criterion:  
    
    $$\triangle OAP \cong \triangle OBP$$
4. By CPCT (Corresponding Parts of Congruent Triangles):  
    
    $$PA = PB$$
    
    Hence Proved. $\blacksquare$  
    

## 3. MCQ Rules & Shortcut Properties (VIP Deductions)

Whenever two tangents $PA$ and $PB$ are drawn from an external point $P$ to a circle with center $O$:

1. **Supplementary Angles Rule:** The angle between the two tangents and the angle subtended by the radii at the center are supplementary.  
    
    $$\angle APB + \angle AOB = 180^\circ$$
2. **Angle Bisector Rule:** The line $OP$ bisects both $\angle APB$ and $\angle AOB$.  
    
    $$\angle APO = \angle BPO \quad \text{and} \quad \angle AOP = \angle BOP$$
3. **Circumscribing Quadrilateral Rule (Standard Result):** If a quadrilateral $ABCD$ circumscribes a circle (touches it at all four sides), then the sum of opposite sides is equal.  
    
    $$AB + CD = AD + BC$$
4. **Right Triangle Inradius Trick:** If a circle is inscribed in a right-angled triangle with perpendicular $P$, base $B$, and hypotenuse $H$, the radius $r$ of the incircle is:  
    
    $$r = \frac{P + B - H}{2}$$

## 4. Fully Answered PYQs (Repeated Board Questions)

### Q1: The Circumscribed Quadrilateral (CBSE 2017, 2020, 2023 Standard)

**A quadrilateral** $ABCD$ **is drawn to circumscribe a circle. Prove that** $AB + CD = AD + BC$**.**

**Solution:**

1. Let the circle touch the sides $AB, BC, CD$, and $DA$ of quadrilateral $ABCD$ at points $P, Q, R$, and $S$ respectively.
    
2. Using Theorem 10.2 (Lengths of tangents from an external point are equal):
    
    - From point $A$: $AP = AS$ --- (1)
        
    - From point $B$: $BP = BQ$ --- (2)
        
    - From point $C$: $CR = CQ$ --- (3)
        
    - From point $D$: $DR = DS$ --- (4)
        
3. Adding equations (1), (2), (3), and (4) vertically:  
    
    $$(AP + BP) + (CR + DR) = (AS + DS) + (BQ + CQ)$$
4. Combining the line segments:  
    
    $$AB + CD = AD + BC$$
    
    **Hence Proved.** $\blacksquare$  
    

### Q2: Tangents at Ends of a Diameter (CBSE 2016, 2024)

**Prove that the tangents drawn at the ends of a diameter of a circle are parallel.**

**Solution:**

1. Let $AB$ be a diameter of a circle with center $O$. Let $PQ$ and $RS$ be the tangents drawn at the ends $A$ and $B$ respectively.
    
2. By Theorem 10.1, the radius is perpendicular to the tangent at the point of contact.
    
    - $OA \perp PQ \implies \angle OAP = 90^\circ$ and $\angle OAQ = 90^\circ$  
        
    - $OB \perp RS \implies \angle OBR = 90^\circ$ and $\angle OBS = 90^\circ$  
        
3. Since $A, O, B$ form a straight line (diameter), $\angle OAP$ and $\angle OBS$ act as alternate interior angles for lines $PQ$ and $RS$ intersected by transversal $AB$.
    
4. Since $\angle OAP = \angle OBS = 90^\circ$, the alternate interior angles are equal.
    
5. Therefore, line $PQ \parallel$ line $RS$. **Hence Proved.** $\blacksquare$  
    

### Q3: Concentric Circles Chord Property (CBSE 2015, 2019, 2022)

**Two concentric circles are of radii** $5\text{ cm}$ **and** $3\text{ cm}$**. Find the length of the chord of the larger circle which touches the smaller circle.**

**Solution:**

1. Let $O$ be the common center. Let $AB$ be the chord of the larger circle ($R = 5\text{ cm}$) that touches the smaller circle ($r = 3\text{ cm}$) at point $P$.
    
2. Since $AB$ touches the smaller circle at $P$, $AB$ is a tangent to the smaller circle.
    
3. By Theorem 10.1, radius $OP \perp AB$. Thus, $\triangle OPA$ is a right-angled triangle.
    
4. In $\triangle OPA$, apply Pythagoras Theorem:  
    
    $$OA^2 = OP^2 + AP^2$$$$5^2 = 3^2 + AP^2$$$$25 = 9 + AP^2 \implies AP^2 = 16 \implies AP = 4\text{ cm}$$
5. We know that the perpendicular drawn from the center to a chord bisects the chord.  
    
    $$AB = 2 \times AP = 2 \times 4 = 8\text{ cm}$$
    
    **Answer:** The length of the chord is $8\text{ cm}$.
    

### Q4: Angle Relations (CBSE 2018, 2021)

**If** $PA$ **and** $PB$ **are tangents from an external point** $P$ **to a circle with centre** $O$ **such that** $\angle APB = 50^\circ$**, find** $\angle OAB$**.**

**Solution:**

1. From Theorem 10.2, $PA = PB$.
    
2. In $\triangle PAB$, since $PA = PB$, the angles opposite to them are equal: $\angle PAB = \angle PBA$.
    
3. Sum of angles in $\triangle PAB$ is $180^\circ$:  
    
    $$\angle PAB + \angle PBA + \angle APB = 180^\circ$$$$2\angle PAB + 50^\circ = 180^\circ$$$$2\angle PAB = 130^\circ \implies \angle PAB = 65^\circ$$
4. By Theorem 10.1, the radius $OA$ is perpendicular to tangent $PA$, so $\angle OAP = 90^\circ$.
    
5. From the figure, $\angle OAP = \angle OAB + \angle PAB$.  
    
    $$90^\circ = \angle OAB + 65^\circ$$$$\angle OAB = 90^\circ - 65^\circ = 25^\circ$$
    
    **Answer:** $\angle OAB = 25^\circ$.