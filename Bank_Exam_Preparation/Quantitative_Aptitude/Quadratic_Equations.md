# 🧮 Quadratic Equations – Fast Cracking for Bank Exams

> 🧠 **Quadratic = x² type equation**. In exams, you mostly solve for **roots** and compare with another equation.

---

## 🌟 1. What is a Quadratic Equation?

A **quadratic equation** is:

```text
ax² + bx + c = 0   (a ≠ 0)
```

- `a`, `b`, `c` are numbers.
- `x` is the unknown (what we need to find).

Example: `2x² + 5x + 3 = 0` is quadratic.

---

## 💡 2. Root-Finding Shortcut (Middle Term Splitting)

Most exam questions have **simple integers** as roots. Use this method:

For `ax² + bx + c = 0`:

1. Multiply `a × c`.
2. Find two numbers **p and q** such that:
   - `p + q = b`
   - `p × q = a × c`
3. Split middle term using `p` and `q`.
4. Factorize.

### Example 1 (Easy)

Solve: `x² + 7x + 12 = 0`

1. Here, `a = 1`, `b = 7`, `c = 12`
2. Need `p + q = 7` and `p × q = 12`
   - 3 + 4 = 7 and 3×4 = 12 → so p=3, q=4
3. Write:
   ```text
   x² + 7x + 12
   = x² + 3x + 4x + 12
   = x(x + 3) + 4(x + 3)
   = (x + 3)(x + 4)
   ```
4. So roots are:
   ```text
   x + 3 = 0 → x = −3
   x + 4 = 0 → x = −4
   ```

✅ Roots: −3, −4

> [!TRICK] 🎯  
> Just remember: “**Sum and product**” – find two numbers having given **sum (b)** and **product (ac)**.

---

### Example 2 (Coefficient ≠ 1)

Solve: `2x² + 5x + 3 = 0`

1. `a = 2`, `b = 5`, `c = 3`  
2. `a × c = 2 × 3 = 6`  
   Need `p + q = 5` and `p × q = 6`  
   → 2 and 3
3. Split:
   ```text
   2x² + 5x + 3
   = 2x² + 2x + 3x + 3
   = 2x(x + 1) + 3(x + 1)
   = (x + 1)(2x + 3)
   ```
4. Roots:
   ```text
   x + 1 = 0 → x = −1
   2x + 3 = 0 → x = −3/2
   ```

✅ Roots: −1, −3/2

---

## 📐 3. Formula Method (When Splitting is Hard)

Use **Quadratic Formula**:

```text
For ax² + bx + c = 0:

x = [−b ± √(b² − 4ac)] / (2a)
```

- The term `D = b² − 4ac` is called **discriminant**.

| D value     | Nature of roots       |
|------------:|-----------------------|
| D &gt; 0       | Real &amp; distinct       |
| D = 0       | Real &amp; equal          |
| D &lt; 0       | Not real (complex)    |

> [!MEMORY] 💡  
> Think of **“b² − 4ac” as “big square minus 4 apple cake”** to remember the formula. 😄

---

### Example 3 – Using Formula

Solve: `x² − 4x + 3 = 0`

- a = 1, b = −4, c = 3  
- D = b² − 4ac = (−4)² − 4×1×3 = 16 − 12 = 4  
- √D = 2

Now:

```text
x = [−b ± √D] / 2a
  = −(−4) ± 2 / 2
  = (4 ± 2) / 2
```

So:

- x₁ = (4 + 2)/2 = 6/2 = 3
- x₂ = (4 − 2)/2 = 2/2 = 1

✅ Roots: 1 and 3

---

## 🔁 4. Comparing Roots (Bank Exam Pattern)

Typical question:

> Given two equations:  
> I. `2x² + 5x + 3 = 0`  
> II. `3y² + 7y + 4 = 0`  
> Find relationship between x and y.

Options usually:

1. x &gt; y  
2. x ≥ y  
3. x &lt; y  
4. x ≤ y  
5. x = y or relationship cannot be established

### Step-by-Step Strategy

1. **Find roots of both equations** (they are usually simple).
2. You’ll get two roots for x and two for y.
3. Compare each x-root with each y-root:

   - If **all x &gt; y** → x &gt; y  
   - If **all x &lt; y** → x &lt; y  
   - If **mixed** → “relationship cannot be determined”

---

### Example 4 – Root Comparison

**Q:**  

I. `2x² + 5x + 3 = 0`  
II. `3y² + 7y + 4 = 0`

We already found for I:  
`2x² + 5x + 3 = 0` → roots are x = −1, −3/2 ( = −1.5)

Now solve II:

`3y² + 7y + 4 = 0`

- a = 3, b = 7, c = 4  
- ac = 3×4 = 12  
Need p+q = 7, p×q = 12 → 3 and 4

So:

```text
3y² + 7y + 4
= 3y² + 3y + 4y + 4
= 3y(y + 1) + 4(y + 1)
= (y + 1)(3y + 4)
```

Roots:

- y + 1 = 0 → y = −1  
- 3y + 4 = 0 → y = −4/3 ≈ −1.33

So:

- x-roots: −1, −1.5
- y-roots: −1, −1.33

Compare:

- x = −1 vs y = −1 → equal  
- x = −1 vs y = −1.33 → x greater (less negative)  
- x = −1.5 vs y = −1 → x smaller  
- x = −1.5 vs y = −1.33 → x smaller

We see **sometimes x&gt;y and sometimes x&lt;y** → relationship **cannot be determined**.

---

## 🧠 5. Memory Tricks for Quick Solving

- **“Product &amp; Sum”** – always check if `b` and `ac` allow simple splitting.
- **If a = 1**:  
  Find two numbers that multiply to `c` and add to `b`.
- **Signs Rule**:

For `x² + bx + c = 0`:

| Sign of b | Sign of c | Roots sign              |
|----------:|-----------|-------------------------|
| +         | +         | both − (negative)      |
| −         | +         | both + (positive)      |
| +         | −         | one +, one −           |
| −         | −         | one +, one −           |

Example: `x² − 5x + 6 = 0`  
b negative, c positive → both roots positive.

---

## 📘 6. Solved Examples (Shortcut-Oriented)

### Example 5

Solve: `x² − 7x + 10 = 0`

- a = 1, b = −7, c = 10  
- Need numbers whose **product = 10** and **sum = 7** → 5 and 2
- So:

```text
x² − 7x + 10
= x² − 5x − 2x + 10
= x(x − 5) − 2(x − 5)
= (x − 5)(x − 2)
```

Roots: x = 5, x = 2

---

### Example 6

Solve: `3x² + 11x + 10 = 0`

- a = 3, b = 11, c = 10  
- ac = 30  
Need sum 11, product 30 → 5 and 6

```text
3x² + 11x + 10
= 3x² + 5x + 6x + 10
= x(3x + 5) + 2(3x + 5)
= (3x + 5)(x + 2)
```

Roots: x = −5/3, −2

---

## 📝 7. Practice Questions (with Answers)

Try to solve mentally as much as you can.

```text
1)  x² + 9x + 20 = 0
2)  x² − 8x + 12 = 0
3)  2x² + 3x − 5 = 0
4)  3x² − 5x − 2 = 0
5)  4x² + 4x − 3 = 0

For 6–10, compare x and y:

6)  I. x² − 7x + 12 = 0
    II. y² − 5y + 6 = 0

7)  I. x² + 5x + 6 = 0
    II. y² + 7y + 12 = 0

8)  I. 2x² + 7x + 3 = 0
    II. 2y² + 5y + 3 = 0

9)  I. 3x² − 13x + 12 = 0
    II. 3y² − 10y + 8 = 0

10) I. x² − 3x − 10 = 0
    II. y² − 4y − 12 = 0
```

---

### ✅ Answers (Outline Only)

1. `x² + 9x + 20 = 0`  
   Numbers: 5 and 4  
   Roots: x = −5, −4

2. `x² − 8x + 12 = 0`  
   Numbers: 6 and 2  
   Roots: x = 2, 6

3. `2x² + 3x − 5 = 0`  
   ac = −10 → numbers: 5, −2  
   Roots: x = 1, x = −2.5

4. `3x² − 5x − 2 = 0`  
   ac = −6 → numbers: −6, 1  
   Roots: x = 2, x = −1/3

5. `4x² + 4x − 3 = 0`  
   ac = −12 → numbers: 6, −2  
   Roots: x = 1/2, x = −3/2

For 6–10, you can find roots similarly and compare:

6. Relationship: **x ≥ y**  
7. Relationship: **x ≤ y**  
8. Relationship: **x &gt; y**  
9. Relationship: **Cannot be determined** (mixed comparison)  
10. Relationship: **x &lt; y**

> [!TIP] ⚡  
> In real exams, quadratic equations are designed so that **roots come out very neat**.  
> If calculation gets ugly, pause and re-check your splitting – you may have picked wrong numbers.