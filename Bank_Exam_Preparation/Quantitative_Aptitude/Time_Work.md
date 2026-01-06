# ⏱️ Time &amp; Work – Universal Template for Work Problems

> 🧠 Goal: Aisa system bana lo ki Time–Work, Men–Days, Pipes–Cisterns,  
> sab ko **ek hi framework** se solve kar sako.

---

## 🧭 Concept Map – Time &amp; Work Kahan Use Hota Hai?

- Simple work questions (A, B, C doing a job)
- Men–Days concepts (more men → less days)
- Pipes &amp; Cisterns (fill/empty tanks) – same logic
- Mains caselets: productivity, machines, jobs, etc.

Core idea:

> Kaam = “total work”  
> Speed = “work per day” (ya per hour)  
> Time = “kitne din me total work complete?”

---

## 🌟 1. Core Idea – 1 Day’s Work

If A alone can finish work in N days:

```text
A’s 1 day work = 1/N (part of total work)
```

Example:

A → 10 days → 1 day work = 1/10  
B → 20 days → 1 day work = 1/20  

Together:

1 day work = 1/10 + 1/20 = 3/20  
Total time = 1 ÷ (3/20) = 20/3 days

---

## 🧮 2. Standard Formula (Two People)

If A alone takes a days, B alone takes b days:

- A’s 1-day work = 1/a  
- B’s 1-day work = 1/b  
- (A+B) 1-day work = 1/a + 1/b = (a + b)/ab

Time taken together:

```text
T = ab / (a + b)
```

> [!TIP] 💡  
> “Time ka product upar, time ka sum niche”.

---

## 🧱 3. Efficiency Method (Work = 100 Units Logic)

Kabhi-kabhi fractions ugly ho jate hain. Tab hum work ko “100 ya LCM units” assume karte hain.

Steps:

1. Total work = LCM of individual times (ya 100)  
2. Efficiency = work/time  
3. Together efficiency = sum, phir time = work/efficiency

#### Example

A → 10 days, B → 20 days

- LCM of 10,20 = 20 units (or 100 bhi le sakte)  
- A’s 1-day work = 20/10 = 2 units  
- B’s 1-day work = 20/20 = 1 unit  
- Together = 3 units/day  
- Time = 20/3 days

Same as fraction method, but “units” me sochna asaan lagta hai.

---

## 🔁 Algorithms / Templates

### 🔹 Template A – A &amp; B Together / Separately

1. Identify times a, b.  
2. Find total work (LCM) or use fraction.  
3. Find 1-day work of each.  
4. Add/subtract as per “together/alone/one leaves”.

---

### 🔹 Template B – A Works Some Days, B Joins Later

Steps:

1. Find 1-day work of each.  
2. Work done by first part: (days worked × 1-day work).  
3. Remaining work = 1 − work done.  
4. Now solve with combined work per day.

#### Example (Level 1)

A → 12 days, B → 18 days. A works 4 days, then B joins. Total time?

- A: 1/12, B: 1/18  
- A in 4 days = 4/12 = 1/3  
- Remaining = 2/3  
- (A+B) 1 day = 1/12 + 1/18 = (3+2)/36 = 5/36  
- Time = (2/3) ÷ (5/36) = (2/3)×(36/5) = 24/5 = 4.8 days  
Total = 4 + 4.8 = **8.8 days**

---

### 🔹 Template C – A More Efficient Than B (Efficiency Ratio)

If A takes a days, B takes b days:

- Efficiency ∝ 1/time  
- A:B efficiency = 1/a : 1/b = b : a

Use this directly for ratio or “how much more/less efficient” questions.

---

## 🎯 Levels of Questions

### LEVEL 1 – Basics (Prelims)

1) A → 8 days, B → 12 days. Together?

T = (8×12)/(8+12) = 96/20 = **4.8 days**

---

2) A → 10 days, B half as efficient as A. B alone?

A speed = 1/10  
B speed = 1/20  
So B = **20 days**

---

### LEVEL 2 – Typical Exam Questions

#### Q3 – Three Persons Together

A → 12 days, B → 18, C → 36. Together?

1-day work:

- 1/12 + 1/18 + 1/36  
= 3/36 + 2/36 + 1/36  
= 6/36 = 1/6

Time = **6 days**

---

#### Q4 – A &amp; B Together, B Alone

A+B → 10 days, A alone → 15 days. B alone?

- (A+B) 1 day = 1/10  
- A 1 day = 1/15  
- B 1 day = 1/10 − 1/15 = (3−2)/30 = 1/30  
→ B alone → **30 days**

---

### LEVEL 3 – High-Level / Twisted (Mains Style)

#### Pattern 1 – Work Done Fraction Given

A &amp; B can together complete a work in 12 days. After working together for 4 days, A leaves and B completes remaining work in 16 days. In how many days can B alone do the whole work?

Let B alone takes b days → 1-day work = 1/b.

A+B together → 12 days → 1-day work = 1/12.

So:

```text
A’s 1-day work = 1/12 − 1/b
```

Work done in first 4 days:

```text
4×(1/12) = 1/3
```

Remaining work = 2/3

This 2/3 is done by B alone in 16 days:

```text
16×(1/b) = 2/3
1/b = 2/(3×16) = 1/24
So b = 24 days
```

✅ B alone → 24 days.

---

#### Pattern 2 – Efficiency Ratio Type

A is twice as efficient as B. Together they finish work in 12 days. In how many days will A alone finish it?

Let B’s 1-day work = 1 unit.  
Then A = 2 units.  
Together = 3 units per day.

Let total work = 3×12 = 36 units.

A alone 2 units/day → time = 36/2 = **18 days**.

---

## ⚠️ Common Traps &amp; Mistakes

1. **Work assumed = 1 vs Work = LCM units**  

   - Dono valid hain, but be consistent.
   - LCM units me “integer values” milte hain, ratio questions easy ho jate.

2. **Parts completed / remaining ko galat treat karna**

   - Always write **“work done”** &amp; **“remaining work”** clearly as fraction/units.

3. **Direction misreading**  

   - “A leaves”, “A joins”, “work is finished 5 days before”,  
     in sab ne time-interval ke logic me confusion create kar sakta hai.  
     Timeline draw karna helpful hota hai.

---

## 🧾 Micro-Revision Box (Summary)

- A alone → a days → 1-day work = 1/a  
- B alone → b days → 1-day work = 1/b  
- Together → 1-day = 1/a + 1/b; time = ab/(a+b)

- Total work (units) = LCM(a,b,...)  
- Efficiency = work/time

- Templates:

  1. A+B→time; A alone given → B alone find  
  2. A works some days → remaining work with A+B/B alone  
  3. Efficiency ratio from time ratio (inverse)  

- Must-solve:

  - A &amp; B together / separately  
  - “X works for some days, Y joins/leaves”  
  - Men–Days type (inverse proportion)  
  - Efficiency comparison (A twice as efficient, etc.)

---

> [!TIP] 🚀  
> Time &amp; Work ko **1-day work + units** se socho, formula ratne ki zarurat nahi.  
> 40–50 mixed questions (basic + twisted) solve kar ke ye template tumhare dimaag me chipak jayega,  
> phir Pipes &amp; Cisterns bhi automatically easy lagne lagenge.