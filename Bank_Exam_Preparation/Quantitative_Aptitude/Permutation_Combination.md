# 🔢 Permutation &amp; Combination – Arrangements &amp; Selections

> 🧠 P&amp;C = “Kitni tarah se possible hai?”.  
> Bank exams me mostly **basic arrangement/selection** wale sawal aate hain,  
> jo counting ka logic test karte hain, heavy theory nahi.

---

## 🧭 Concept Map – Kya test hota hai?

- Arrangement (order matters) vs Selection (order doesn’t)
- Counting principle (step-wise choices multiply)
- Factorials (n!)

---

## 🌟 1. Factorial – Counting Base

`n!` (n factorial):

```text
n! = n × (n−1) × (n−2) × ... × 2 × 1
```

Examples:

- 4! = 4×3×2×1 = 24  
- 5! = 5×4×3×2×1 = 120

By definition: 0! = 1

---

## 🎯 2. Fundamental Counting Principle

If:

- First choice has a ways  
- Second choice has b ways  

Total ways = a × b

Example:

2 shirts, 3 pants → outfits = 2×3 = 6

Ye hi principle P&amp;C ke formulas ka base hai.

---

## 🎯 3. Permutation – Arrangements (Order Matters)

From n distinct objects, arrange r of them:

```text
nPr = n! / (n − r)!
```

Special: arrange all → nPn = n!

### Example 1 – Simple Arrangement

Kitne tareeko se A, B, C ko arrange kar sakte?

n=3, r=3:

3! = 6:

ABC, ACB, BAC, BCA, CAB, CBA

---

### Example 2 – 3-digit Numbers (No Repetition)

Digits: 1,2,3,4. How many 3-digit numbers (no repetition)?

First place: 4 choices  
Second: 3  
Third: 2  

Total = 4×3×2 = 24 = 4P3

---

## 🎯 4. Combination – Selections (Order Doesn’t Matter)

From n distinct objects, select r of them (order not important):

```text
nCr = n! / [r! (n − r)!]
```

### Example 3 – Simple Selection

3 letters A,B,C me se 2 choose karne ke ways?

n=3, r=2:

3C2 = 3! / (2!×1!) = 3 ways: AB, AC, BC

(AB &amp; BA same team – isliye combination)

---

## 🧠 Quick Memory Aid

- **P for Permutation, P for Position** → order important.  
- **C for Combination, C for Committee** → sirf kaun-kaun, order nahi.

Captain/vice-captain → order matters → permutation.  
Team of 2 players → order doesn’t → combination.

---

## 🎯 5. Levels of Questions

### LEVEL 1 – Direct Factorial/P&amp;C

1) Find 4! and 5!.

- 4! = 24, 5! = 120

---

2) In how many ways can letters A, B, C be arranged?

3! = 6

---

3) From 4 people, how many 2-member committees?

4C2 = 4! / (2!×2!) = 6

---

### LEVEL 2 – Typical Exam Patterns

4) From 6 people, how many different committees of 2 people?

6C2 = 6! / (2!×4!) = (6×5)/2 = **15**

---

5) How many 2-digit numbers can be formed using digits 1, 2, 3 (no repetition)?

First digit: 3 (cannot be 0 anyway)  
Second: 2  

Total: 3×2 = **6**

---

6) From digits 1, 2, 3, 4, how many 3-digit numbers without repetition?

4P3 = 4×3×2 = **24**

---

7) From 5 players, how many ways to choose a captain and a vice-captain?

Captain: 5 choices  
Vice-captain: remaining 4  

Total = 5×4 = **20** = 5P2

---

8) From 5 players, how many ways to choose a team of 2?

5C2 = (5×4)/(2×1) = **10**

---

### LEVEL 3 – Slightly Twisted (Mains-Flavoured Light)

9) How many 3-letter “words” (not necessarily meaningful) can be formed from letters A, B, C, D if repetition is allowed?

Positions: 3; each position: 4 choices (A/B/C/D)

Total = 4×4×4 = **64**

(Here we don’t need permutation formula because repetition allowed; we use fundamental counting principle.)

---

10) From digits 1,2,3,4,5, how many 4-digit numbers can be formed if repetition is not allowed and number must be even?

Even → last digit must be even: {2,4}

Case-by-case:

- If last digit 2:
  - Remaining digits for first 3 positions: {1,3,4,5} → 4 digits
  - Arrangements = 4P3 = 4×3×2=24

- If last digit 4:
  - Remaining digits: {1,2,3,5} → 4 digits
  - Again 4P3 = 24

Total = 24+24= **48**

---

## 📝 Practice Set (with Answers)

```text
1)  Compute 6!.

2)  In how many ways can 4 different books be arranged on a shelf?

3)  From 7 people, in how many ways can a 3-member committee be formed?

4)  From digits 1, 2, 3, 4, 5, how many 3-digit numbers can be formed
    if repetition is not allowed?

5)  From digits 1, 2, 3, 4, 5, how many 3-digit numbers can be formed
    if repetition is allowed?

6)  From 8 students, in how many ways can a captain, vice-captain and
    a sports secretary be chosen (all different posts)?

7)  A box contains 5 red and 3 blue balls. In how many ways can 2 balls be chosen?

8)  In how many ways can the letters of the word “BANK” be arranged?

9)  In how many ways can 2 pens be chosen from 6 different pens?

10) From 5 men and 4 women, in how many ways can a group of 3 persons be chosen?
```

### ✅ Answers (Outline)

1) 6! = 720  
2) Arrange 4 books → 4! = 24  
3) 7C3 = 7! / (3!×4!) = 35  
4) 5P3 = 5×4×3 = 60  
5) Repetition allowed: 5×5×5 = 125  
6) Captain:8, VC:7, Sec:6 → 8×7×6=336  
7) Total 8 balls, choose 2 → 8C2 = 28  
8) “BANK” → 4 different letters → 4! = 24  
9) 6C2 = 15  
10) 9 total, choose 3 → 9C3 = 84

---

## 🧾 Micro-Revision Box

- Factorial: n! = n×(n−1)×...×1  
- Permutation (order matters):

```text
nPr = n! / (n−r)!
```

- Combination (order doesn’t matter):

```text
nCr = n! / [r!(n−r)!]
```

- Counting principle: steps → choices multiply (a×b×c…).

> [!TIP] 🚀  
> Bank exams me P&amp;C ka heavy theory nahi,  
> sirf **basic factorial, permutation, combination, repetition allowed/na allowed**  
> aur chhote selection/arrangement questions aate hain.  
> Roz 15–20 mixed questions solve karoge to ye topic comfortable ho jayega.