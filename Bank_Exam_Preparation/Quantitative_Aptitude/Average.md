# 📏 Average – From Basics to High-Level Mastery

> 🧠 Goal: Aise notes ki 1–2 baar padhai ke baad **Average ka koi bhi question** (Prelims + Mains)  
> tum algorithm + logic se solve kar sako – chahe kitna bhi twisted ho.

---

## 🧭 Concept Map – Average Kya Hai, Kyon Zaroori Hai?

### 1️⃣ Why This Topic Exists?

Real life examples:

- Class me **average marks**
- Team ki **average age**
- Company ki **average salary**
- DI charts me “average production/sales”

Bank exams me Average:

- Direct questions
- Mixture–Alligation ka base
- Time &amp; Work / Speed / DI me hidden use

👉 Agar tum “average = total / number” ko **total-thinking** ke saath master kar loge,  
to kaafi arithmetic aur DI ke questions jaldi simplify ho jate hain.

---

### 2️⃣ Core Definition (Super Simple)

```text
Average = (Sum of all values) / (Number of values)
```

Example:

Numbers: 4, 6, 10

- Sum = 4 + 6 + 10 = 20  
- Count = 3  
- Average = 20 / 3 ≈ 6.67

> [!TIP] 💡  
> Hamesha do cheezen saath socho:  
> **Average ↔ Total** (dono ek doosre se directly linked hain).

---

## 🧱 Deep Logic: Average as “Balance Point”

Socho tumhare paas 3 log hain:

- A = 4 chocolates  
- B = 6 chocolates  
- C = 10 chocolates  

Average = 20/3 ≈ 6.67

Agar sab ko equal chocolates deni ho:

- A ko +2.67
- B ko +0.67
- C se −3.33

Average ek **“middle level”** hai jahan sab equal ho jate,  
aur jitna upar hai, utna hi kisi aur ka neeche hona zaroori hai.

> This idea se high-level questions ka pattern samajh aata hai:
> - Kuch log average se upar, kuch neeche → total deviations ka sum = 0.

---

## 🧮 Standard Formulas + Kab Use Karein?

### Formula 1: Basic Average

```text
Average (A) = Total Sum (S) / Number of items (n)
```

So:

```text
S = A × n
n = S / A
```

**Use karna kab:**

- “Average given, number given → total chahiye”
- “Total given, number given → average chahiye”
- “Average badla, naya total / naya member find karna hai”

---

### Formula 2: Combined Average (Two Groups)

2 groups:

- Group 1: n₁ items, average A₁ → sum S₁ = n₁A₁  
- Group 2: n₂ items, average A₂ → sum S₂ = n₂A₂  

Combined:

```text
Total sum S = S₁ + S₂ = n₁A₁ + n₂A₂
Total items = n₁ + n₂

Combined average A = (n₁A₁ + n₂A₂) / (n₁ + n₂)
```

**Use kab karein:**

- “Two classes”, “two batches”, “two years” ka combined average
- DI me multi-year average

---

### Formula 3: Average Speed (Same Distance)

If same distance covered with speed x and y:

```text
Average speed = 2xy / (x + y)
```

**Use kab karein:**

- “Gaya ek speed se, wapas doosri speed se, distance same”
- “Upstream–downstream same distance” type

---

## 🔁 Algorithms / Stepwise Templates

### 🔹 Template A: New Person Joins / Leaves

**Question Type:**  
“Average age of n persons is A. One more person joins / leaves, average changes. Find his age.”

**Algorithm:**

1. Old total = A × n  
2. New total = New Average × New Number  
3. Age of new/left person = Difference of totals

#### Example (Level 1)

Average age of 10 students = 12 years. One more student joins, average becomes 13. Find new student’s age.

Step 1: Old total = 10 × 12 = 120  
Step 2: New total = 11 × 13 = 143  
Step 3: Age = 143 − 120 = **23 years**

---

### 🔹 Template B: One Wrong Data Correct Karna

**Type:**  
“Average based on wrong value; correct value diya hai, correct average find karo.”

**Algorithm:**

1. Wrong total = wrong average × number  
2. Correct total = wrong total − wrong value + correct value  
3. Correct average = correct total / number

#### Example (Level 1)

Average marks of 30 students is 48. One student’s marks wrongly taken as 60 instead of 50. Find correct average.

Step 1: Wrong total = 30 × 48 = 1440  
Step 2: Correct total = 1440 − 60 + 50 = 1430  
Step 3: Correct average = 1430 / 30 ≈ **47.67**

---

### 🔹 Template C: Combined Average as Weighted Average

**Key idea:**  
Combined average is like **weighted average**.

Example:

Class A: 20 students, avg 60  
Class B: 30 students, avg 70  

Step 1: Find total marks:  
S₁ = 20×60 = 1200  
S₂ = 30×70 = 2100

Step 2: Combined:  
S = 3300, n = 50 → A = 3300/50 = **66**

**Pattern:**  
Jiska weight (students) zyada, uska average combined average ko zyada pull karega.

---

## 🎯 Levels of Questions

### LEVEL 1 – Basic Foundation (Prelims Easy)

#### Q1

Average of 8 numbers is 15. Find their total sum.

- Total = 8 × 15 = **120**

#### Q2

Average of 6 numbers is 20. If one more number 26 is added, find new average.

- Old total = 6 × 20 = 120  
- New total = 120 + 26 = 146  
- New average = 146 / 7 ≈ **20.86**

---

### LEVEL 2 – Exam Typical (Prelims + Easy Mains)

#### Q3

The average age of 12 students is 14 years. One student of age 20 joins. Find new average.

- Old total = 12 × 14 = 168  
- New total = 168 + 20 = 188  
- New n = 13  
- New average ≈ 188 / 13 ≈ **14.46**

**Pattern Note:**  
New age > old avg → new avg increases, but **less than new age**.

---

#### Q4

Average marks of Class A (20 students) is 60, Class B (30 students) is 70. Find combined average.

- S₁ = 20×60 = 1200  
- S₂ = 30×70 = 2100  
- S = 3300, n = 50  
- A = 3300/50 = **66**

Shortcut insight:

- Closer to 70 because B (30 students) more than A (20 students).

---

### LEVEL 3 – High-Level / Twisted (Mains Type)

#### Q5

Average salary of all employees in a company is ₹20,000.  
Average salary of 10 officers is ₹40,000 and that of remaining employees is ₹18,000.  
Find total number of employees.

Let total employees = N.

Total salary by both groups:

- Officers: 10 × 40000 = 4,00,000  
- Others: (N − 10) × 18000

Overall:

```text
Total salary = 20000 × N

So:
400000 + 18000(N − 10) = 20000N
400000 + 18000N − 180000 = 20000N
220000 + 18000N = 20000N
20000N − 18000N = 220000
2000N = 220000
N = 110
```

✅ Total employees = **110**

**Pattern/Shortcut:**

- This is **weighted average** problem.  
- Could also think in terms of “deviation from overall average” method (advanced).

---

#### Q6 (Tricky Age Problem)

Average age of A, B and C is 25. Average age of B and C is 29. Find A’s age.

Let:

- Sum(A+B+C) = 3×25 = 75  
- Sum(B+C) = 2×29 = 58

A = 75 − 58 = **17 years**

**Pattern:**  
“Average of group of 3” and “average of last 2” given →  
Just total difference → age of left-out person.

---

## ⚠️ Common Traps &amp; Mistakes

1. **Averages of Averages ko direct average samajh lena**

   - Example:
     - Class1 avg = 50  
     - Class2 avg = 70  
     - Combined avg ≠ (50 + 70)/2 = 60 (only if equal students)

2. **Changing n but not updating total**

   - Jab new person join/leave kare → dono total &amp; count change hote hain.

3. **Roughness in Mains**  

   - Mains me decimals aa sakte hain. Approximation allowed, lekin logic clear hona chahiye.

---

## 🧾 Micro-Revision Box (1-Page Summary)

- **Basic:**

```text
Average = Total / Number
Total = Average × Number
```

- **Combined Average (Two Groups):**

```text
A = (n₁A₁ + n₂A₂) / (n₁ + n₂)
```

- **Average Speed (same distance):**

```text
Avg speed = 2xy / (x + y)
```

- **Templates:**

1. New person joins/leaves:
   - Old total = A_old × n_old  
   - New total = A_new × n_new  
   - Person’s value = |New total − Old total|

2. Wrong data correction:
   - Wrong total = A_wrong × n  
   - Correct total = Wrong total − Wrong + Correct  
   - A_correct = Correct total / n

3. Combined groups:
   - Convert average → totals, add, then divide.

- **Must-Practice Question Types:**

  1. New join/leave → find missing age/marks.  
  2. Combined average of two classes/years.  
  3. Wrong entry corrected.  
  4. “Average of A,B,C” + “Average of B,C” → find A.  

---

> [!TIP] 🚀  
> Average ko hamesha **Total-thinking + Deviation-thinking** ke saath padhoge,  
> to high-level bank exam questions bhi ek simple table/steps se ho jayenge.  
> Is note ko 2–3 baar padho + 30–40 mixed questions solve karo → topic solid ho jayega.