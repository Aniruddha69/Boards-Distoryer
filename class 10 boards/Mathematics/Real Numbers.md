
# 1. The Fundamental Theorem of Arithmetic (FTA)

## Statement

### **Every composite number can be uniquely expressed (factorised) as a product of primes, apart from the order in which the prime factors occur.**

$$\text{Composite Number } N = p_1^{a_1} \cdot p_2^{a_2} \cdot p_3^{a_3} \cdots p_k^{a_k}$$

where $p_1 < p_2 < \dots < p_k$ are prime numbers and $a_1, a_2, \dots, a_k$ are natural numbers.

# 2. HCF and LCM Rules & Formulae

Let two positive integers be $a$ and $b$ expressed in prime factor form:

- $\text{HCF}(a, b)$: Product of the **smallest power** of each **common** prime factor involved in the numbers.
    
- $\text{LCM}(a, b)$: Product of the **greatest power** of **each** prime factor involved in the numbers.
    

## Core Identity (Only for TWO numbers)

$$\text{HCF}(a, b) \times \text{LCM}(a, b) = a \times b$$

> **Crucial Warning:** This rule does **NOT** apply to three numbers:  
> 
> $$\text{HCF}(a, b, c) \times \text{LCM}(a, b, c) \neq a \times b \times c$$

# 3. High-Yield "Cheat Codes" & Exam Hacks

1. **Powers Ending in Zero (**$n \in \mathbb{N}$**):**
    
    - A number of the form $a^n$ ends with the digit $0$ if and only if the prime factorisation of $a$ contains **both** $2$ **and** $5$ (i.e., $10 = 2 \times 5$).
        
    - _Example:_ $6^n = (2 \times 3)^n$ cannot end with digit $0$ because it lacks prime factor $5$.
        
    - _Example:_ $4^n = (2^2)^n = 2^{2n}$ cannot end with digit $0$.
        
2. **Exponent Rules for Variable LCM/HCF:**
    
    - If $x = p^a q^b$ and $y = p^c q^d$:  
        
        $$\text{HCF}(x, y) = p^{\min(a, c)} \cdot q^{\min(b, d)}$$$$\text{LCM}(x, y) = p^{\max(a, c)} \cdot q^{\max(b, d)}$$
3. **Coprime Trap:**
    
    - If two numbers $a$ and $b$ are coprime:  
        
        $$\text{HCF}(a, b) = 1 \implies \text{LCM}(a, b) = a \times b$$
4. **Divisibility Rule:**
    
    - $\text{HCF}(a, b)$ always divides $\text{LCM}(a, b)$ completely. If LCM is not divisible by HCF, such a pair of numbers cannot exist.
        

# 4. Fundamental Theorems for Irrationality

## Key Lemma (Without Proof)

Let $p$ be a prime number. If $p$ divides $a^2$, then $p$ **divides** $a$, where $a$ is a positive integer.  

$$p \mid a^2 \implies p \mid a$$

## Arithmetic of Irrationals

- $\text{Rational} \pm \text{Irrational} = \text{Irrational}$  
    
- $\text{Non-zero Rational} \times \text{Irrational} = \text{Irrational}$  
    
- $\frac{\text{Non-zero Rational}}{\text{Irrational}} = \text{Irrational}$  
    

# 5. Most Repeated Proofs (Standard Templates)

## Type A: Prove that $\sqrt{5}$ is irrational.

### **Proof (Method of Contradiction):**

1. Let us assume, to the contrary, that $\sqrt{5}$ is rational.
    
2. Therefore, we can find coprime integers $a$ and $b$ ($b \neq 0$, $\text{HCF}(a, b) = 1$) such that:  
    
    $$\sqrt{5} = \frac{a}{b} \implies a = b\sqrt{5}$$
3. Squaring both sides:  
    
    $$a^2 = 5b^2 \quad \text{--- (Equation 1)}$$
4. This means $5$ divides $a^2$. By the theorem ($p \mid a^2 \implies p \mid a$), $5$ **divides** $a$.
    
5. So, we can write $a = 5c$ for some integer $c$.
    
6. Substitute $a = 5c$ into Equation 1:  
    
    $$(5c)^2 = 5b^2 \implies 25c^2 = 5b^2 \implies b^2 = 5c^2$$
7. This means $5$ divides $b^2$, which implies $5$ **divides** $b$.
    
8. From steps (4) and (7), $5$ is a common factor of both $a$ and $b$.
    
9. But this contradicts the fact that $a$ and $b$ are coprime (they have no common factor other than $1$).
    
10. This contradiction has arisen because of our incorrect assumption that $\sqrt{5}$ is rational.
    

Hence, $\sqrt{5}$ **is irrational.** $\blacksquare$  

## Type B: Given that $\sqrt{5}$ is irrational, prove that $3 + 2\sqrt{5}$ is irrational.

### **Proof (Method of Contradiction):**

1. Let us assume, to the contrary, that $3 + 2\sqrt{5}$ is rational.
    
2. Therefore, there exist coprime integers $a$ and $b$ ($b \neq 0$) such that:  
    
    $$3 + 2\sqrt{5} = \frac{a}{b}$$
3. Rearranging the terms:  
    
    $$2\sqrt{5} = \frac{a}{b} - 3$$$$2\sqrt{5} = \frac{a - 3b}{b}$$$$\sqrt{5} = \frac{a - 3b}{2b}$$
4. Since $a$ and $b$ are integers, $(a - 3b)$ and $2b$ are integers with $2b \neq 0$.
    
5. Therefore, $\frac{a - 3b}{2b}$ is a rational number.
    
6. This implies that $\sqrt{5}$ must also be a rational number.
    
7. But this contradicts the given fact that $\sqrt{5}$ is irrational.
    
8. This contradiction has arisen because of our incorrect assumption that $3 + 2\sqrt{5}$ is rational.
    

Hence, $3 + 2\sqrt{5}$ **is irrational.** $\blacksquare$  

# 6. Important PYQs & Exemplar Questions

## Category 1: Variable Exponent Questions ($p^x q^y$)

### **Q1 (CBSE 2020 / Standard):** If two positive integers $a$ and $b$ are written as $a = x^3 y^2$ and $b = x y^3$, where $x, y$ are prime numbers, find $\text{HCF}(a, b)$ and $\text{LCM}(a, b)$.

- **Solution:**
    
    - $\text{HCF}(a, b) = x^{\min(3, 1)} \cdot y^{\min(2, 3)} = x^1 y^2 = xy^2$  
        
    - $\text{LCM}(a, b) = x^{\max(3, 1)} \cdot y^{\max(2, 3)} = x^3 y^3$  
        

### **Q2 (CBSE 2023):** If $p = a^2 b^3$ and $q = a^3 b$, where $a$ and $b$ are prime numbers, then find $\text{LCM}(p, q) / \text{HCF}(p, q)$.

- **Solution:**
    
    - $\text{LCM}(p, q) = a^3 b^3$  
        
    - $\text{HCF}(p, q) = a^2 b$  
        
    - Ratio $= \frac{a^3 b^3}{a^2 b} = a^{3-2} b^{3-1} = ab^2$  
        

### **Q3 (CBSE 2019):** If $a = 2^3 \times 3$, $b = 2 \times 3 \times 5$, $c = 3^n \times 5$ and $\text{LCM}(a, b, c) = 2^3 \times 3^2 \times 5$, find the value of $n$.

- **Solution:**
    
    - In the prime factorisation, powers of $3$ in $a, b, c$ are $1, 1,$ and $n$ respectively.
        
    - The maximum power of $3$ present in $\text{LCM}$ is $2$.
        
    - Therefore, $\max(1, 1, n) = 2 \implies n = 2$.
        

## Category 2: $\text{HCF} \times \text{LCM} = a \times b$ Applications

### **Q4 (CBSE 2021 Term-1):** Given that $\text{HCF}(306, 657) = 9$, find $\text{LCM}(306, 657)$.

- **Solution:**  
    
    $$\text{LCM}(a, b) = \frac{a \times b}{\text{HCF}(a, b)} = \frac{306 \times 657}{9} = 34 \times 657 = 22338$$

### **Q5 (CBSE 2018):** Can two numbers have $15$ as their HCF and $175$ as their LCM? Give reasons.

- **Solution:**
    
    - HCF must always be a factor of LCM.
        
    - Checking divisibility: $\frac{175}{15} = \frac{35}{3} = 11.66\dots$ (not an integer).
        
    - Since $15$ does not divide $175$ completely, two numbers **cannot** have $15$ as their HCF and $175$ as their LCM.
        

### **Q6 (CBSE 2024 / Sample Paper):** The LCM of two numbers is $14$ times their HCF. The sum of LCM and HCF is $600$. If one number is $280$, find the other number.

- **Solution:**
    
    1. Let $\text{HCF} = h$ and $\text{LCM} = l$.
        
    2. Given: $l = 14h$ and $l + h = 600$.
        
    3. $14h + h = 600 \implies 15h = 600 \implies h = 40$.
        
    4. $l = 14 \times 40 = 560$.
        
    5. Using $a \times b = \text{HCF} \times \text{LCM}$:  
        
        $$280 \times b = 40 \times 560 \implies b = \frac{40 \times 560}{280} = 40 \times 2 = 80$$
    
    - The other number is $80$.