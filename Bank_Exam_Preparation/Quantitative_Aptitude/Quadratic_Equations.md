# 🧮 Quadratic Equations – Roots &amp; Comparison Masterclass

> 🧠 Target: ax²+bx+c=0 type equations se **roots jaldi nikalna**  
> aur do equations ke roots ko compare karke x, y ka relation decide karna (IBPS/SBI pattern).

---

## 🧭 Concept Map – Quadratics kyon important?

- Number Series me hidden use hota hai
- Inequalities / comparison based questions (I, II equations)
- Coordinate geometry / algebra DI me
- Mains me sometimes word problems reduce to quadratics

---

## 🌟 1. Basic Definition

Quadratic equation in x:

```text
ax² + bx + c = 0,  where a ≠ 0
```

- a, b, c – real numbers (constants)
- x – variable (unknown)

Example: `2x² + 5x + 3 = 0`

---

## 🔑 2. Finding Roots – Middle Term Split (Bank Exam Favourite)

For `ax² + bx + c = 0`:

1. Compute product = a×c  
2. Find two numbers p, q such that:
   - p + q = b  
   - p × q = a×c
3. Split middle term b into p and q.
4. Factorise with grouping → get two linear factors.

> [!TIP] 💡  
> “Sum = middle coefficient, Product = a×c”.

---

### Example 1 (a=1 case – easiest)

Solve: `x² + 7x + 12 = 0`

Here: a=1, b=7, c=12  
Need p+q=7, p×q=12 → 3 &amp; 4

```text
x² + 7x + 12
= x² + 3x + 4x + 12
= x(x+3) + 4(x+3)
= (x+3)(x+4) = 0
```

Roots: x = −3, −4

---

### Example 2 (a≠1)

Solve: `2x² + 5x + 3 = 0`

a=2, b=5, c=3 → ac=6  
Need p+q=5, p×q=6 → 2 &amp; 3

```text
2x² + 5x + 3
= 2x² + 2x + 3x + 3
= 2x(x+1) + 3(x+1)
= (x+1)(2x+3)
```

Roots:

```text
x = −1,  −3/2
```

---

## 🌈 3. Quadratic Formula + Discriminant

General formula:

```text
x = [−b ± √(b² − 4ac)] / (2a)
```

- `D = b² − 4ac` = discriminant

| D value | Roots type           |
|--------:|----------------------|
| D &gt; 0   | Real &amp; distinct      |
| D = 0   | Real &amp; equal (repeated) |
| D &lt; 0   | Complex (not real)   |

Formula mostly use hota hai jab splitting clean na ho.

---

### Example 3 (Formula Use)

Solve: `x² − 4x + 3 = 0`

a=1, b=−4, c=3

```text
D = (−4)² − 4×1×3 = 16−12 = 4
√D = 2

x = [−(−4) ± 2] / 2
  = (4 ± 2)/2

→ x₁ = 6/2 = 3
→ x₂ = 2/2 = 1
```

---

## 🧠 4. Root Sign Logic (Useful for Quick Checks)

For `x² + bx + c = 0`:

| Sign of b | Sign of c | Sign of roots         |
|----------:|-----------|-----------------------|
| +         | +         | Both negative         |
| −         | +         | Both positive         |
| +         | −         | One +, one −          |
| −         | −         | One +, one −          |

Example: `x² − 5x + 6 = 0` → b negative, c positive → both roots positive.

---

## 🔁 5. Comparison of Roots – Bank Pattern

Given:

I. quadratic in x  
II. quadratic in y  

Need relation:

- x &gt; y, x ≥ y, x &lt; y, x ≤ y, x = y or “no relation”.

**Strategy:**

1. Find both roots of eqn I (x₁,x₂).  
2. Find both roots of eqn II (y₁,y₂).  
3. Compare all combinations:
   - If all x’s &gt; all y’s → x&gt;y  
   - If all x’s &lt; all y’s → x&lt;y  
   - Otherwise (mixed) → Relationship cannot be determined.

> [!TIP] 💡  
> Exam me mostly roots simple rational numbers hote hain.

---

### Example 4 – Root Comparison

I. `2x² + 5x + 3 = 0`  
II. `3y² + 7y + 4 = 0`

We already got for I → (x+1)(2x+3)=0 → x = −1, −3/2 (−1.5)

Now for II:

```text
3y² + 7y + 4
= 3y² +3y +4y +4
= 3y(y+1) + 4(y+1)
= (y+1)(3y+4)
```

Roots: y = −1, y = −4/3 (≈ −1.33)

Comparison:

- x=−1 vs y=−1 → equal  
- x=−1 vs y=−1.33 → x greater  
- x=−1.5 vs y=−1 → x smaller  
- x=−1.5 vs y=−1.33 → x smaller

Mixed (kabhi x&gt;y, kabhi x&lt;y) → **relation cannot be determined**.

---

## 🎯 Levels of Questions

### LEVEL 1 – Basic Roots

1) `x² + 9x + 20 = 0` → sum = 9, product = 20 → 4 &amp; 5

```text
Roots: x = −4, −5
```

2) `x² − 8x + 12 = 0` → sum = 8, product = 12 → 2 &amp; 6

```text
Roots: 2, 6
```

---

### LEVEL 2 – Mixed Coefficients

3) `2x² + 3x − 5 = 0`

ac = −10 → numbers 5 and −2

```text
2x² + 5x − 2x − 5
= x(2x+5) −1(2x+5)
= (2x+5)(x−1)
```

Roots: x = 1, x = −2.5

---

4) `3x² − 5x − 2 = 0`

ac = −6 → factors: −6 and 1

```text
3x² −6x + x −2
= 3x(x−2) +1(x−2)
= (x−2)(3x+1)
```

Roots: x = 2, x = −1/3

---

### LEVEL 3 – Comparison-Based (IBPS/SBI Style)

#### Q5

I. `x² − 7x + 12 = 0`  
II. `y² − 5y + 6 = 0`

Equation I:

```text
x² −7x+12 = 0 → (x−3)(x−4)=0 → x=3,4
```

Equation II:

```text
y² −5y+6 = 0 → (y−2)(y−3)=0 → y=2,3
```

Compare:

- x=3, y=2 → x&gt;y  
- x=3, y=3 → equal  
- x=4, y=2 or 3 → x&gt;y

So here **x ≥ y**, but because one pair equal and others x&gt;y, exam options me choose “x ≥ y”.

(Actual options pattern pe depend karega – sometimes they just want “x≥y”.)

---

## 🧠 Memory / Pattern Notes

- Middle-term split works 90% of banking-level quadratic questions.
- Discriminant se quickly “nature of roots” check ho sakta hai.
- For comparison:
  - Hamesha **numeric roots** nikal lo; sign logic se shortcut possible but risk bhi.

---

## 📝 Practice Set (with Answers Outline)

```text
1)  x² − 7x + 10 = 0
2)  4x² + 4x − 3 = 0
3)  5x² − 13x + 8 = 0
4)  2x² − x − 3 = 0
5)  3x² + 2x − 8 = 0

Compare x and y:

6)  I. x² + 3x − 10 = 0
    II. y² + 5y − 14 = 0

7)  I. 2x² − 7x + 3 = 0
    II. 2y² − 9y + 10 = 0
```

### ✅ Short Answers

1) `x² −7x+10=0` → (x−5)(x−2)=0 → x=2,5  
2) `4x²+4x−3=0` → roots = 1/2, −3/2  
3) `5x² −13x+8=0` → ac=40 → 5 &amp; 8 → (5x−5)(x−? ) etc. (you can solve as exercise)  
4) `2x² −x−3=0` → ac=−6 → −3,2 → (2x+3)(x−1) → roots −3/2,1  
5) `3x²+2x−8=0` → ac=−24 → 6,−4 → (3x−4)(x+2) → roots 4/3, −2  

6) Solve both, compare as in examples (good practice for IBPS pattern).  
7) Same.

---

> [!TIP] 🚀  
> Quadratic me speed ka secret:  
> - Middle-term split ko automatic bana lo (2–3 days me ho jata hai),  
> - har roz 10–15 quadratic solve karo (including comparison),  
> - formula ko backup me rakho, main weapon split + factorization rakho.  
> Phir exam me quadratic equations tumhara **fastest scoring topic** ban jayega.