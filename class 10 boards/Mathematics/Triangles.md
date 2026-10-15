# Class 10 Mathematics: Triangles (Complete Guide & PYQs)

## 1. Basic Proportionality Theorem (BPT / Thales Theorem)

### Statement

> If a line is drawn parallel to one side of a triangle intersecting the other two sides in distinct points, then the other two sides are divided in the same ratio.

### Formal Proof

```
                     A
                    / \
                   /   \
                  /     \
                 /       \
              D /---------\ E
               / \       / \
              /   \     /   \
             /     \   /     \
            /       \ /       \
           B---------X---------C
```

- **Given:** In $\triangle ABC$, a line parallel to side $BC$ intersects side $AB$ at $D$ and side $AC$ at $E$ (i.e., $DE \parallel BC$).
    
- **To Prove:**  
    
    $$\frac{AD}{DB} = \frac{AE}{EC}$$
- **Construction:**
    
    - Join $B$ to $E$ and $C$ to $D$.
        
    - Draw $EN \perp AB$ and $DM \perp AC$.
        
- **Proof:** Recall the formula for area of a triangle:  
    
    $$\text{Area} = \frac{1}{2} \times \text{base} \times \text{height}$$
    1. Find the ratio of areas of $\triangle ADE$ and $\triangle BDE$:  
        
        $$\text{ar}(\triangle ADE) = \frac{1}{2} \times AD \times EN$$$$\text{ar}(\triangle BDE) = \frac{1}{2} \times DB \times EN$$$$\frac{\text{ar}(\triangle ADE)}{\text{ar}(\triangle BDE)} = \frac{\frac{1}{2} \times AD \times EN}{\frac{1}{2} \times DB \times EN} = \frac{AD}{DB} \quad \text{--- (Equation 1)}$$
    2. Similarly, find the ratio of areas of $\triangle ADE$ and $\triangle DEC$:  
        
        $$\text{ar}(\triangle ADE) = \frac{1}{2} \times AE \times DM$$$$\text{ar}(\triangle DEC) = \frac{1}{2} \times EC \times DM$$$$\frac{\text{ar}(\triangle ADE)}{\text{ar}(\triangle DEC)} = \frac{\frac{1}{2} \times AE \times DM}{\frac{1}{2} \times EC \times DM} = \frac{AE}{EC} \quad \text{--- (Equation 2)}$$
    3. Compare $\triangle BDE$ and $\triangle DEC$: Both triangles lie on the same base $DE$ and between the same parallel lines $DE$ and $BC$.  
        
        $$\text{ar}(\triangle BDE) = \text{ar}(\triangle DEC) \quad \text{--- (Equation 3)}$$
    4. From Equations (1), (2), and (3):  
        
        $$\frac{AD}{DB} = \frac{AE}{EC}$$

Hence proved. $\blacksquare$  

### Important Corollaries of BPT (Frequently used in numericals)

Adding $1$ to both sides yields:

- $\dfrac{AB}{AD} = \dfrac{AC}{AE}$  
    
- $\dfrac{AB}{DB} = \dfrac{AC}{EC}$  
    

## 2. Converse of Basic Proportionality Theorem

### Statement

> If a line divides any two sides of a triangle in the same ratio, then the line must be parallel to the third side.

### Formal Proof (By Contradiction)

- **Given:** In $\triangle ABC$, a line cuts $AB$ at $D$ and $AC$ at $E$ such that:  
    
    $$\frac{AD}{DB} = \frac{AE}{EC} \quad \text{--- (Equation 1)}$$
- **To Prove:** $DE \parallel BC$  
    
- **Proof:**
    
    1. Let us assume, to the contrary, that $DE$ is **not** parallel to $BC$.
        
    2. Then there must exist some line passing through $D$ which is parallel to $BC$. Let that line be $DE'$ meeting $AC$ at $E'$.
        
    3. Since $DE' \parallel BC$, by BPT:  
        
        $$\frac{AD}{DB} = \frac{AE'}{E'C} \quad \text{--- (Equation 2)}$$
    4. Comparing Equation (1) and Equation (2):  
        
        $$\frac{AE}{EC} = \frac{AE'}{E'C}$$
    5. Add $1$ to both sides:  
        
        $$\frac{AE}{EC} + 1 = \frac{AE'}{E'C} + 1$$$$\frac{AE + EC}{EC} = \frac{AE' + E'C}{E'C}$$$$\frac{AC}{EC} = \frac{AC}{E'C}$$$$\implies EC = E'C$$
    6. This is only possible when points $E$ and $E'$ coincide.
        
    7. Therefore, our assumption was incorrect, and $DE$ must be parallel to $BC$.
        

Hence proved. $\blacksquare$  

## 3. The Three Similarity Criteria

Two triangles $\triangle ABC$ and $\triangle DEF$ are similar ($\triangle ABC \sim \triangle DEF$) if their corresponding angles are equal and their corresponding sides are proportional.

### 1. AAA (or AA) Similarity Criterion

- **Rule:** If two angles of one triangle are respectively equal to two angles of another triangle, then the two triangles are similar.
    
- **Symbolic Condition:**  
    
    $$\angle A = \angle D, \quad \angle B = \angle E \implies \triangle ABC \sim \triangle DEF \text{ (by AA)}$$

### 2. SSS (Side-Side-Side) Similarity Criterion

- **Rule:** If the corresponding sides of two triangles are proportional, then their corresponding angles are equal, and the triangles are similar.
    
- **Symbolic Condition:**  
    
    $$\frac{AB}{DE} = \frac{BC}{EF} = \frac{AC}{DF} \implies \triangle ABC \sim \triangle DEF \text{ (by SSS)}$$

### 3. SAS (Side-Angle-Side) Similarity Criterion

- **Rule:** If one angle of a triangle is equal to one angle of another triangle, and the sides including these angles are proportional, then the triangles are similar.
    
- **Crucial Condition:** The angle **must be included** between the two sides.  
    
    $$\frac{AB}{DE} = \frac{AC}{DF} \quad \text{and} \quad \angle A = \angle D \implies \triangle ABC \sim \triangle DEF \text{ (by SAS)}$$

## 4. Special Pointers & Traps (Exclusively for MCQs)

_Keep these in your toolkit for 1-minute MCQ solutions, but never skip steps when writing 3-mark or 5-mark subjective answers!_

|   |   |   |
|---|---|---|
|**Shortcut / MCQ Fact**|**How to use it**|**Common Trap to Avoid**|
|**Ratio of Perimeters**|$\dfrac{\text{Perimeter}(\triangle ABC)}{\text{Perimeter}(\triangle DEF)} = \dfrac{\text{Side}_1}{\text{Side}_2}$|Do **not** square the ratio! Squaring is only for areas (which is not part of the reduced syllabus, but perimeters remain purely linear).|
|**Median / Altitude Ratio**|$\dfrac{\text{Side}_1}{\text{Side}_2} = \dfrac{\text{Altitude}_1}{\text{Altitude}_2} = \dfrac{\text{Median}_1}{\text{Median}_2} = \dfrac{\text{Angle Bisector}_1}{\text{Angle Bisector}_2}$|Ensure the corresponding vertex is chosen correctly.|
|**Letter Ordering Trap**|If $\triangle ABC \sim \triangle QRP$, then:<br><br>  <br><br>$\dfrac{AB}{QR} = \dfrac{BC}{RP} = \dfrac{AC}{QP}$|**Never assume** $AB$ corresponds to $PQ$. Always match letter positions directly: 1st-2nd with 1st-2nd, 2nd-3rd with 2nd-3rd!|
|**Parallel Base Trap**|In $\triangle ABC$ with $DE \parallel BC$, $\dfrac{AD}{DB} = \dfrac{AE}{EC}$ is true, but $\dfrac{DE}{BC} \neq \dfrac{AD}{DB}$!<br><br>  <br><br>Instead: $\dfrac{DE}{BC} = \dfrac{AD}{AB} = \dfrac{AE}{AC}$|Never write $\dfrac{DE}{BC} = \dfrac{AD}{DB}$. The parallel segment ratio requires the **full triangle side**.|
|**Hourglass / Bowtie Figure**|Vertically opposite angles at intersection are equal. Line transversals give alternate interior angles.|Always re-order vertices before writing ratios ($AB \parallel CD \implies \triangle AOB \sim \triangle COD$).|

## 5. High-Yield PYQs & Important Questions

### Question 1 (CBSE 2020 Standard) — Algebraic BPT Equation

**In** $\triangle ABC$**,** $DE \parallel BC$ **such that** $AD = x$**,** $DB = x - 2$**,** $AE = x + 2$**, and** $EC = x - 1$**. Find the value of** $x$**.**

- **Solution:** By Basic Proportionality Theorem (since $DE \parallel BC$):  
    
    $$\frac{AD}{DB} = \frac{AE}{EC}$$$$\frac{x}{x - 2} = \frac{x + 2}{x - 1}$$
    
    Cross-multiplying:  
    
    $$x(x - 1) = (x + 2)(x - 2)$$$$x^2 - x = x^2 - 4$$$$-x = -4 \implies x = 4$$
- **Answer:** $x = 4$  
    

### Question 2 (CBSE 2019, 2023) — Trapezium Diagonals

$ABCD$ **is a trapezium with** $AB \parallel DC$**. The diagonals** $AC$ **and** $BD$ **intersect each other at the point** $O$**. Show that:**  

$$\frac{AO}{BO} = \frac{CO}{DO}$$

- **Solution:**
    
    - In $\triangle AOB$ and $\triangle COD$:
        
        1. $\angle OAB = \angle OCD$ (Alternate interior angles, as $AB \parallel DC$ and $AC$ is a transversal)
            
        2. $\angle OBA = \angle ODC$ (Alternate interior angles, as $AB \parallel DC$ and $BD$ is a transversal)
            
        3. $\angle AOB = \angle COD$ (Vertically opposite angles)
            
    - Therefore, by AAA (or AA) similarity criterion:  
        
        $$\triangle AOB \sim \triangle COD$$
    - Taking corresponding sides:  
        
        $$\frac{AO}{CO} = \frac{BO}{DO}$$
    - Rearranging the terms:  
        
        $$\frac{AO}{BO} = \frac{CO}{DO}$$
- **Hence Proved.** $\blacksquare$  
    

### Question 3 (CBSE 2018, 2024 Sample Paper) — The Parallel Overlap Proof

**In the given figure,** $DE \parallel AC$ **and** $DF \parallel AE$**. Prove that:**  

$$\frac{BF}{FE} = \frac{BE}{EC}$$

```
                     B
                    / \
                   /   \
                  /     \
               D /       \
                /         \
               /           \
              A---F----E----C
```

- **Solution:**
    
    1. In $\triangle BAC$, given $DE \parallel AC$. By Basic Proportionality Theorem:  
        
        $$\frac{BD}{DA} = \frac{BE}{EC} \quad \text{--- (Equation 1)}$$
    2. In $\triangle BAE$, given $DF \parallel AE$. By Basic Proportionality Theorem:  
        
        $$\frac{BD}{DA} = \frac{BF}{FE} \quad \text{--- (Equation 2)}$$
    3. Equating the right sides of Equation (1) and Equation (2):  
        
        $$\frac{BF}{FE} = \frac{BE}{EC}$$
- **Hence Proved.** $\blacksquare$  
    

### Question 4 (CBSE 2022 Term-2) — Vertical Pole & Shadow (Classic 2/3 Marker)

**A vertical pole of length** $6\text{ m}$ **casts a shadow** $4\text{ m}$ **long on the ground, and at the same time a tower casts a shadow** $28\text{ m}$ **long. Find the height of the tower.**

- **Solution:**
    
    - Let $AB$ be the pole ($6\text{ m}$) and $BC$ be its shadow ($4\text{ m}$).
        
    - Let $PQ$ be the tower ($h\text{ m}$) and $QR$ be its shadow ($28\text{ m}$).
        
    - At the same time, the angular elevation of the Sun is the same for both objects:  
        
        $$\angle C = \angle R$$
    - Both the pole and tower stand vertically:  
        
        $$\angle B = \angle Q = 90^\circ$$
    - By AA similarity:  
        
        $$\triangle ABC \sim \triangle PQR$$
    - Equating ratios of corresponding sides:  
        
        $$\frac{AB}{PQ} = \frac{BC}{QR}$$$$\frac{6}{h} = \frac{4}{28}$$$$\frac{6}{h} = \frac{1}{7} \implies h = 6 \times 7 = 42\text{ m}$$
- **Answer:** The height of the tower is $42\text{ m}$.