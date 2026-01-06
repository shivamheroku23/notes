# 🔢 Permutation &amp; Combination – Arrangements &amp; Selections

> 🧠 Is chapter mein mostly basic level questions aate hain in bank exams,  
> soch simple rakho: **Permutation = arrangement (order matters)**,  
> **Combination = selection (order does not matter)**.

---

## 🌟 1. Factorial Concept

`n!` (n factorial):

```text
n! = n × (n−1) × (n−2) × ... × 2 × 1
```

Examples:

- 4! = 4×3×2×1 = 24
- 5! = 5×4×3×2×1 = 120

Special:  
0! = 1 (by definition)

---

## 🎯 2. Permutation – Arrangement

From **n different objects**, number of ways to arrange **r** of them:

```text
P(n, r) = nPr = n! / (n−r)!
```

Special case: arrange all `n` objects → nPn = n!

---

### Example 1 – Simple Arrangement

In how many ways can 3 letters A, B, C be arranged?

Total letters n=3, r=3:

n! = 3! = 3×2×1 = 6

List:

- ABC
- ACB
- BAC
- BCA
- CAB
- CBA

---

## 🎯 3. Combination – Selection (Order Doesn’t Matter)

From **n different objects**, number of ways to select **r** of them:

```text
C(n, r) = nCr = n! / [r! (n−r)!]
```

---

### Example 2 – Simple Selection

From 3 letters A, B, C, in how many ways can we choose 2 letters?

n=3, r=2:

3C2 = 3! / [2! × 1!] = 6 / 2 = 3

Pairs:

- AB
- AC
- BC

(AB and BA same in combination)

---

## 🧮 4. Bank Exam Style Easy Examples

### Example 3 – Committee Selection

From 5 people, in how many ways can we select a group of 3?

5C3 = 5! / [3!×2!] = (5×4×3!)/(3!×2) = 20/2 = 10

✅ 10 ways

---

### Example 4 – Arranging Digits

How many 3-digit numbers can be formed using digits 1, 2, 3, 4 if repetition not allowed?

We are making **arrangements of 4 digits taken 3 at a time**:

4P3 = 4! / (4−3)! = 4! / 1! = 24

---

## 📘 5. Memory Trick

- **P for Permutation, P for Position** → order important.  
- **C for Combination, C for Committee** → only selection.

---

## 📝 6. Practice Questions (with Answers)

```text
1)  Find 4! and 5!.

2)  In how many ways can the letters A, B, C be arranged?

3)  In how many ways can 2 letters be selected from A, B, C, D?

4)  From 6 people, how many different committees of 2 people can be formed?

5)  How many 2-digit numbers can be formed using digits 1, 2, 3 (no repetition)?

6)  From digits 1, 2, 3, 4, in how many ways can a 3-digit number be formed (no repetition)?

7)  What is 5C2?

8)  What is 5P2?

9)  From 5 players, in how many ways can a captain and vice-captain be chosen (distinct posts)?

10) From 5 players, in how many ways can a team of 2 players be chosen (equal posts)?
```

---

### ✅ Answers (Brief)

1) 4! = 24, 5! = 120

2) 3! = 6 arrangements

3) Select 2 from 4:

4C2 = 4! / (2!×2!) = 6

4) 6C2 = 6! / (2!×4!) = (6×5)/2 = 15

5) For 2-digit number (no repetition):

- 1st place: 3 choices  
- 2nd place: 2 choices  
Total = 3×2 = 6

6) 4P3 = 4! / 1! = 24

7) 5C2 = (5×4)/(2×1) = 10

8) 5P2 = 5! / 3! = 5×4 = 20

9) Captain &amp; vice-captain (order matters):

5P2 = 20

10) Team of 2 (order doesn’t matter):

5C2 = 10

---

> [!TIP] 🚀  
> Bank exams me P&amp;C ke **high-level questions** kam aate hain.  
> Basic factorial, nPr, nCr, arrangements vs selections ka concept clear rakho,  
> aur thode se practice questions se hi ye topic handle ho jayega.