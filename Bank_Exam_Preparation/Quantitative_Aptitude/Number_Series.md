# 🔢 Number Series – Pattern Engine for Prelims &amp; Mains

> 🧠 Goal: Number Series ko itna samajhna ki tum **missing term** &amp; **wrong term**  
> dono ko pattern se identify kar sako – chahe addition, multiplication, squares, mix kuch bhi ho.

---

## 🧭 Concept Map – Number Series Kya Test Karta Hai?

- Pattern spotting
- Basic arithmetic feel:
  - Differences
  - Multiplication factors
  - Squares, cubes, primes
- Mental agility (fast elimination)

Do main types:

1. **Missing term** – `2, 6, 12, 20, ?, 42`
2. **Wrong term** – `4, 9, 19, 39, 80, 159`

---

## 🌟 1. Master Algorithm (Stepwise)

When you see a series:

```text
Step 1: Check differences: a₂−a₁, a₃−a₂, ...
Step 2: See pattern in differences:
        - Constant?
        - Increasing +2, +4, +6...?
        - Squares/cubes in differences?
Step 3: If differences are large/strange → try multiplication:
        - a₂/a₁, a₃/a₂ (×2, ×3, ×1.5, etc.)
Step 4: Look for special patterns:
        - Squares: 1,4,9,16,25...
        - Cubes: 1,8,27,64...
        - Alternate terms pattern
        - Fibonacci (sum of previous terms)
Step 5: Check pattern for ALL given terms.
Step 6: Only then fill missing or mark wrong.
```

> [!TIP] 💡  
> “Pehle difference, phir multiplication” – always.

---

## 🎯 2. Common Pattern Types

### 2.1 Pure Addition / Subtraction

Example: `3, 8, 13, 18, 23, ?`

Differences = +5 each → next = 23 + 5 = **28**

---

### 2.2 Increasing Differences

Example: `2, 5, 10, 17, 26, ?`

Differences = 3, 5, 7, 9 → odd numbers  
Next diff = 11 → 26+11 = **37**

---

### 2.3 Multiplication-Based

Example: `2, 4, 8, 16, 32, ?`

×2 each → next = 64

---

### 2.4 Multiply + Add (Mixed)

Example: `2, 5, 11, 23, 47, ?`

Pattern:

- 2×2+1 = 5  
- 5×2+1 = 11  
- 11×2+1 = 23  
- 23×2+1 = 47  

Next = 47×2+1 = **95**

---

### 2.5 Squares / Cubes

Example: `1, 4, 9, 16, 25, ?`

Squares: 1²,2²,3²,4²,5² → next = 6² = **36**

---

### 2.6 Fibonacci Type

Each term ≈ sum of previous two.

Example: `2, 3, 5, 8, 13, 21, ?`

2+3=5, 3+5=8, 5+8=13, 8+13=21 → next = 13+21 = **34**

---

### 2.7 Difference of Differences

Example: `5, 6, 10, 19, 35, ?`

1st differences:

- 1,4,9,16 → squares (1²,2²,3²,4²)

Next difference = 5² = 25 → next term = 35+25 = **60**

---

### 2.8 Alternate Pattern

Example: `2, 5, 4, 7, 6, 9, ?`

Odd positions: 2,4,6,… ( +2 )  
Even positions: 5,7,9,… (+2)

So next at position 7 = odd sequence → 8.

---

## 🎯 Levels of Questions

### LEVEL 1 – Foundation

#### Q1

`7, 10, 15, 22, 31, ?`

Differences:

+3, +5, +7, +9 → odd numbers  
Next diff = 11 → 31+11 = **42**

---

#### Q2

`3, 9, 27, 81, ?`

×3 each → next = 81×3 = **243**

---

### LEVEL 2 – Typical Exam Series

#### Q3 – Mixed Multiply+Add

`3, 10, 31, 94, ?`

Check:

- 3×3+1 = 10  
- 10×3+1 = 31  
- 31×3+1 = 94

Next = 94×3+1 = 283

---

#### Q4 – Wrong Term Pattern

`7, 14, 28, 56, 113, ?`

Expected pattern: ×2 each:

7,14,28,56, **112**, 224

So **113** wrong, should be 112; next = 224.

> [!TIP] 💡  
> Wrong term me pattern “mostly” follow hota hai, ek jagah break hota.

---

### LEVEL 3 – High-Level / Mains-Type

#### Pattern 1 – Combined Operation

`2, 6, 15, 31, 56, ?`

Differences: 4,9,16,25 → squares (2²,3²,4²,5²)  
Next diff = 6² = 36 → next = 56+36 = **92**

---

#### Pattern 2 – Alternate Multiply/Add

`1, 2, 6, 21, 88, ?`

Try pattern:

1 → 2 (×2)  
2 → 6 (×3)  
6 → 21 (×3.5)  
21 → 88 (×(4+something))

Better approach: Check n²−1 pattern?  
1=1, 2=?, 6=?, 21=?,88? hard. This is a bit complex; exam me options help karte hain.  
But general idea: when direct differences/multiplications not clean, look for:

- alternating patterns  
- n²+n type  
- n! type (rare in banking pre, more in aptitude tests).

(For actual exam-level, you’ll solve from options quickly.)

---

## 🧠 Strategy Tips

1. **Always write at least first-level differences**.
2. If differences consistent → addition pattern.  
   If differences themselves form pattern → difference pattern.
3. If numbers grow very fast → multiplication/square/cube possible.
4. Wrong term: check **sequence trend** and find where it breaks.

---

## 📝 Practice Set (with Answers)

```text
1)  3, 7, 15, 31, 63, ?
2)  2, 6, 12, 20, 30, ?
3)  5, 11, 23, 47, 95, ?
4)  1, 4, 9, 16, 25, ?
5)  2, 5, 11, 23, 47, ?
6)  1, 2, 4, 7, 11, 16, ?
7)  10, 13, 18, 25, 34, 45, ?
8)  4, 6, 9, 13, 18, ?
9)  7, 14, 28, 60, 120, ?  (check wrong term)
10)  2, 4, 12, 48, 240, ?
```

### ✅ Answers &amp; Patterns (Brief)

1) Differences: 4,8,16,32 → ×2 → next diff = 64 → 63+64 = **127**

2) Differences: 4,6,8,10 → +2 → next diff=12 → 30+12=**42**

3) ×2+1 → 95×2+1 = **191**

4) Squares → next: 36

5) ×2+1 → 47×2+1= **95**

6) Differences: 1,2,3,4,5 → next=6 → 16+6= **22**

7) Differences: 3,5,7,9,11 → next=13 → 45+13= **58**

8) Differences: 2,3,4,5 → next=6 → 18+6= **24**

9) Pattern expected: ×2 then + ?  
   7→14 (×2), 14→28 (×2), 28→56 (×2), 56→112 (×2), 112→224 (×2)  
   So **60** is wrong (should be 56), next = **224**.

10) Multiply by 2,3,4,5,... pattern:

2×2=4  
4×3=12  
12×4=48  
48×5=240  
Next=240×6= **1440**

---

## 🧾 Micro-Revision Box (Summary)

- Always:
  - Step 1: differences  
  - Step 2: pattern in differences  
  - Step 3: multiplication factors; squares/cubes; alternate terms.

- Common patterns:
  - Constant difference  
  - Difference increasing by constant  
  - Squares/cubes themselves or in differences  
  - ×k, ×k+something, Fibonacci

- Wrong term:
  - Find where pattern breaks.

---

> [!TIP] 🚀  
> Roz 20–30 mixed Number Series questions solve karo
> (10 missing + 10 wrong term + 5 high-level).  
> 1–2 hafte me tum automatically pattern “dekhne lagoge” bina zyada likhe.  
> Ye skill pure Quant section me tumhari speed double kar sakti hai.