## 1. General Form and Basic Terminology

An **Arithmetic Progression (AP)** is a sequence of numbers in which each term after the first is obtained by adding a fixed number to the preceding term.

### General Representation of an AP:

$$a, \; a + d, \; a + 2d, \; a + 3d, \; \dots, \; a + (n-1)d$$

### Variable Notation & Meanings:

- $a$: First term of the AP
    
- $d$: Common difference ($d = a_{k+1} - a_k$)
    
    - $d$ can be **positive** (increasing AP), **negative** (decreasing AP), or **zero** (constant AP).
        
- $n$: Number of terms ($n \in \mathbb{N}$, must always be a positive integer: $1, 2, 3, \dots$)
    
- $a_n$ (or $l$): $n^{\text{th}}$ term (general term or last term)
    
- $S_n$: Sum of the first $n$ terms of the AP
    

## 2. Core Formulae

### 1. $n^{\text{th}}$ Term of an AP ($a_n$)

$$a_n = a + (n - 1)d$$

- **9th Term (**$a_9$**):** $a + (9 - 1)d = a + 8d$  
    
- **13th Term (**$a_{13}$**):** $a + (13 - 1)d = a + 12d$  
    
- $n^{\text{th}}$ **Term from the End (Last term** $= l$**):**  
    
    $$a_n' = l - (n - 1)d$$

### 2. Sum of First $n$ Terms ($S_n$)

When first term ($a$) and common difference ($d$) are known:

$$S_n = \frac{n}{2} \left[ 2a + (n - 1)d \right]$$

When first term ($a$) and last term ($l = a_n$) are known:

$$S_n = \frac{n}{2} (a + l)$$

### 3. Relation Between $S_n$ and $a_n$  

$$a_n = S_n - S_{n-1} \quad (\text{for } n \ge 2)$$

_(For_ $n = 1$_,_ $a_1 = S_1$_)_

## 3. Shortcut Rules, Cheat Codes & Special Results

### 1. Linear & Quadratic Shortcuts

- **If** $a_n$ **is linear in** $n$ **(**$a_n = p + qn$**):**
    
    - The common difference is simply the coefficient of $n$:  
        
        $$d = q$$
    - First term: $a_1 = p + q$  
        
- **If** $S_n$ **is quadratic in** $n$ **without constant term (**$S_n = An^2 + Bn$**):**
    
    - The common difference is **double the coefficient of** $n^2$:  
        
        $$d = 2A$$
    - First term: $a_1 = S_1 = A + B$  
        

### 2. Standard Sum Identities

- **Sum of first** $n$ **natural numbers (**$1 + 2 + 3 + \dots + n$**):**  
    
    $$\Sigma n = \frac{n(n + 1)}{2}$$
- **Sum of first** $n$ **odd positive integers (**$1 + 3 + 5 + \dots + (2n - 1)$**):**  
    
    $$S_n = n^2$$
- **Sum of first** $n$ **even positive integers (**$2 + 4 + 6 + \dots + 2n$**):**  
    
    $$S_n = n(n + 1)$$

### 3. Finding the Middle Term(s) of an AP

Let an AP have $n$ terms:

- **Case 1: When** $n$ **is ODD**
    
    - There is **one** single middle term:  
        
        $$\text{Middle Term position} = \left(\frac{n + 1}{2}\right)^{\text{th}} \text{ term}$$
- **Case 2: When** $n$ **is EVEN**
    
    - There are **two** middle terms:  
        
        $$\left(\frac{n}{2}\right)^{\text{th}} \text{ term} \quad \text{and} \quad \left(\frac{n}{2} + 1\right)^{\text{th}} \text{ term}$$

### 4. Smart Assumptions of Terms

- **3 terms in AP:** $(a - d), \; a, \; (a + d)$ $\longrightarrow$ _Sum_ $= 3a$  
    
- **4 terms in AP:** $(a - 3d), \; (a - d), \; (a + d), \; (a + 3d)$ $\longrightarrow$ _(Common difference is_ $2d$_)_
    
- **5 terms in AP:** $(a - 2d), \; (a - d), \; a, \; (a + d), \; (a + 2d)$  
    

## 4. VIP / High-Yield CBSE Board PYQs

### Question 1 (Ratio of Sums $\rightarrow$ Ratio of Terms — CBSE 2016, 2020 Standard)

**If the ratio of the sum of first** $n$ **terms of two APs is** $(7n + 1) : (4n + 27)$**, find the ratio of their** $9^{\text{th}}$ **terms.**

- **Solution:** Let the first terms be $a_1, a_2$ and common differences be $d_1, d_2$.
    
    $$\frac{S_n}{S_n'} = \frac{\frac{n}{2}[2a_1 + (n - 1)d_1]}{\frac{n}{2}[2a_2 + (n - 1)d_2]} = \frac{2a_1 + (n - 1)d_1}{2a_2 + (n - 1)d_2} = \frac{7n + 1}{4n + 27}$$
    
    Dividing numerator and denominator on LHS by 2:  
    
    $$\frac{a_1 + \left(\frac{n - 1}{2}\right)d_1}{a_2 + \left(\frac{n - 1}{2}\right)d_2} = \frac{7n + 1}{4n + 27}$$
    
    We need the ratio of their $9^{\text{th}}$ terms: $\dfrac{a_1 + 8d_1}{a_2 + 8d_2}$. Equate:  
    
    $$\frac{n - 1}{2} = 8 \implies n - 1 = 16 \implies n = 17$$
    
    Substitute $n = 17$ into the RHS:  
    
    $$\frac{a_1 + 8d_1}{a_2 + 8d_2} = \frac{7(17) + 1}{4(17) + 27} = \frac{119 + 1}{68 + 27} = \frac{120}{95} = \frac{24}{19}$$
- **Answer:** $24 : 19$  
    

### Question 2 (Sum of Given Specific Terms — CBSE 2017, 2023)

**If the** $m^{\text{th}}$ **term of an AP is** $\frac{1}{n}$ **and the** $n^{\text{th}}$ **term is** $\frac{1}{m}$**, prove that the sum of first** $mn$ **terms is** $\frac{1}{2}(mn + 1)$**.**

- **Solution:** Given:  
    
    $$a_m = a + (m - 1)d = \frac{1}{n} \quad \text{--- (1)}$$$$a_n = a + (n - 1)d = \frac{1}{m} \quad \text{--- (2)}$$
    
    Subtracting $(2)$ from $(1)$:  
    
    $$(m - n)d = \frac{1}{n} - \frac{1}{m} = \frac{m - n}{mn} \implies d = \frac{1}{mn}$$
    
    Substitute $d = \frac{1}{mn}$ into $(1)$:  
    
    $$a + (m - 1)\left(\frac{1}{mn}\right) = \frac{1}{n} \implies a + \frac{1}{n} - \frac{1}{mn} = \frac{1}{n} \implies a = \frac{1}{mn}$$
    
    Now find $S_{mn}$:  
    
    $$S_{mn} = \frac{mn}{2}\left[ 2a + (mn - 1)d \right]$$$$S_{mn} = \frac{mn}{2}\left[ \frac{2}{mn} + (mn - 1)\frac{1}{mn} \right] = \frac{mn}{2} \cdot \frac{1}{mn} [2 + mn - 1] = \frac{1}{2}(mn + 1)$$
- **Hence Proved.** $\blacksquare$  
    

### Question 3 (Finding Middle Term — CBSE 2015, 2019)

**Find the middle term of the AP:** $6, 13, 20, \dots, 216$**.**

- **Solution:** Here, $a = 6$, $d = 13 - 6 = 7$, last term $a_n = 216$.
    
    1. Find total number of terms ($n$):  
        
        $$a_n = a + (n - 1)d$$$$216 = 6 + (n - 1)7 \implies 210 = (n - 1)7 \implies n - 1 = 30 \implies n = 31$$
    2. Since $n = 31$ is **odd**, there is only one middle term:  
        
        $$\text{Position} = \frac{n + 1}{2} = \frac{31 + 1}{2} = 16^{\text{th}} \text{ term}$$
    3. Calculate $a_{16}$:  
        
        $$a_{16} = a + 15d = 6 + 15(7) = 6 + 105 = 111$$
- **Answer:** Middle term is $111$.
    

### Question 4 (Double Answer Significance in $S_n$ — CBSE 2020)

**How many terms of the AP:** $24, 21, 18, \dots$ **must be taken so that their sum is** $78$**? Explain the double answer.**

- **Solution:** Here $a = 24$, $d = 21 - 24 = -3$, $S_n = 78$.
    
    $$S_n = \frac{n}{2}[2a + (n - 1)d]$$$$78 = \frac{n}{2}[2(24) + (n - 1)(-3)] = \frac{n}{2}[48 - 3n + 3] = \frac{n}{2}[51 - 3n]$$$$156 = 51n - 3n^2 \implies 3n^2 - 51n + 156 = 0$$
    
    Divide throughout by $3$:  
    
    $$n^2 - 17n + 52 = 0$$$$(n - 4)(n - 13) = 0 \implies n = 4 \quad \text{or} \quad n = 13$$
    - **Reason for two answers:** The common difference is negative ($d = -3$). The terms from $5^{\text{th}}$ to $13^{\text{th}}$ add up to zero because positive and negative terms cancel each other out ($a_5 = 12, a_6 = 9, \dots, a_{13} = -12$). Hence, both $S_4 = 78$ and $S_{13} = 78$.