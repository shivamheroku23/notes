# 💵 Simple &amp; Compound Interest – Complete Exam Toolkit

> 🧠 SI–CI ka base clear ho to banking, loans, investments, DI caselets – sab manageable ho jate hain.  
> yahan hum formula nahi, **logic + patterns** ke saath master karenge.

---

## 🧭 Concept Map – Interest Kya Hai, Kyon Zaroori Hai?

### 1️⃣ Why This Topic?

- Bank se loan loge → interest doge  
- FD/RD me paisa doge → bank tumhe interest dega  
- Credit card late payment → high interest

Exams me:

- Direct SI/CI problems
- Difference of SI &amp; CI
- Installment / growth / depreciation
- DI me interest-based tables

---

### 2️⃣ Core Terms (Simple Language)

- **Principal (P)** – starting amount (jise invest/borrow kiya).
- **Rate (R)** – interest per year (in %).
- **Time (T)** – years.
- **Amount (A)** – final value including principal.

---

## 🌟 Simple Interest (SI)

**Simple Interest**: Interest every year **sirf principal par** lagta hai.

### Formula

```text
SI = (P × R × T) / 100
Amount A = P + SI
```

**Logic**:

Har saal interest same hoga:

- 1st year: PR/100  
- 2nd year: PR/100  
- T year: T×(PR/100) = PRT/100

---

### Example (Level 1)

Find SI on ₹5000 at 10% p.a. for 3 years.

```text
SI = 5000 × 10 × 3 / 100
   = 1500
A  = 5000 + 1500 = 6500
```

✅ SI = 1500, A = 6500

---

## 🌟 Compound Interest (CI)

**Compound Interest**: Interest **principal + previous interest** dono pe lagta hai.

### Formula (Annual Compounding)

```text
A = P (1 + R/100)^T
CI = A − P
```

**Logic (Year-wise)**:

Same example: P = 10000, R=10%, T=2

Year 1:

- Interest₁ = 10% of 10000 = 1000  
- Amount₁ = 11000

Year 2:

- Interest₂ = 10% of 11000 = 1100  
- Amount₂ = 12100

Total CI = 1000 + 1100 = 2100

Which matches formula:

```text
A = 10000(1.1)² = 12100
CI = 2100
```

> [!TIP] 💡  
> 2–3 years ke CI ke liye **year-wise table** method bohot clear &amp; fast hota hai.

---

## 🔁 Difference Between SI &amp; CI (Same P, R, T)

### For 2 Years

Difference (CI − SI):

```text
= P × (R/100)^2
```

**Why?**  
Conceptually:

- SI 2 years = 2PR/100  
- CI 2 years = P[(1+R/100)² − 1]  
  = P[(1 + 2R/100 + (R/100)²) − 1]  
  = P[2R/100 + (R/100)²]  
  = 2PR/100 + P(R/100)²  

Difference = P(R/100)².

---

### For 3 Years (Advanced, Mains)

```text
Difference (CI − SI) for 3 years = P × (R/100)^2 × (3 + R/100)
```

(Use only when explicitly needed.)

---

## 🔁 Algorithms / Templates

### 🔹 Template A – Find Any of P, R, T using SI

If SI known:

```text
SI = PRT/100
```

- Find P: P = (SI×100)/(R×T)  
- Find R: R = (SI×100)/(P×T)  
- Find T: T = (SI×100)/(P×R)

#### Example (Level 1)

SI = 2000, P = 5000, R = 8%. Find T.

```text
2000 = 5000×8×T/100
2000 = 400T
T = 5 years
```

---

### 🔹 Template B – CI by Factor Method

For annual compounding:

1. Find factor = (1 + R/100)  
2. Raise to power T  
3. Multiply by P → Amount  
4. CI = A − P

#### Example (Level 2)

P = 8000, R = 12.5% = 1/8, T = 2

Factor = 1 + 1/8 = 9/8

```text
A = 8000(9/8)² = 8000×81/64 = 8000/64×81 = 125×81 = 10125
CI = 10125 − 8000 = 2125
```

---

### 🔹 Template C – Difference between SI &amp; CI (2 years)

1. Use formula `Difference = P(R/100)²`  
2. Add difference to SI to get CI (if required).

#### Example (Level 2)

P = 8000, R = 10%, T = 2:

```text
Diff = 8000×(10/100)² = 8000×1/100 = 80
```

---

## 🎯 Levels of Questions

### LEVEL 1 – Basic (Prelims)

1) Find SI on ₹6000 at 10% p.a. for 4 years.

```text
SI = 6000×10×4/100 = 2400; A=8400
```

2) SI on a sum at 12% p.a. for 3 years is 2160. Find P.

```text
2160 = P×12×3/100 = P×36/100
P = 2160×100/36 = 6000
```

---

### LEVEL 2 – Typical Exam Questions

3) At what rate will ₹4000 amount to 5200 in 3 years at SI?

SI = 5200 − 4000 = 1200

```text
1200 = 4000×R×3/100
1200 = 120R
R = 10% p.a.
```

---

4) Find CI on ₹5000 at 8% p.a. for 2 years.

```text
A = 5000(1.08)² = 5000×1.1664 = 5832
CI = 832
```

---

5) Difference between CI &amp; SI on ₹8000 at 10% for 2 years.

```text
Diff = P(R/100)² = 8000×(10/100)² = 8000×1/100 = 80
```

---

### LEVEL 3 – High-Level / Mains Style

#### Q6 – Find Principal from CI &amp; Rate

CI on a sum at 5% p.a. for 2 years is ₹512.5. Find principal.

Use factor: (1.05)² = 1.1025

Let P = x.

```text
A = x×1.1025
CI = A − x = 512.5
x(1.1025 −1) = 512.5
x×0.1025 = 512.5
x = 512.5 / 0.1025 = 5000
```

P = **5000**

---

#### Q7 – CI Case: Amount Known, P Unknown

A sum becomes ₹6724 in 2 years at CI at 10% p.a. Find principal.

Factor: 1.1² = 1.21

```text
6724 = P×1.21
P = 6724/1.21 = 5560
```

---

#### Q8 – Comparing SI &amp; CI (Rate or Time Dependent)

Pattern type:

> For a certain sum, CI for 2 years at R% is ₹x more than SI. Find R.

We use:

```text
Difference = P(R/100)²
```

Given P and difference → R nikal sakte hain.

*(Exact numeric example tum jab CA/Mocks se karoge, pattern already yaad hoga.)*

---

## ⚠️ Common Traps &amp; Mistakes

1. **SI &amp; CI ko mix kar dena**

   - SI: interest har saal same.  
   - CI: interest every year slightly zyada than previous.

2. **Time units mis-match**

   - R always “per annum” hota hai (unless specified quarterly/monthly).  
   - Half-yearly compounding → R/2, T in half-years.

3. **Direct formula use without thinking**

   - 2–3 years CI ke liye year-wise approach bahut clear hai –  
     specially jab fraction rate ho (like 12.5%, 6.25%).

---

## 🧾 Micro-Revision Box (Summary)

- SI:

```text
SI = PRT/100
Amount = P + SI
```

- CI (annual):

```text
A = P(1 + R/100)^T
CI = A − P
```

- 2-year CI−SI:

```text
Diff = P(R/100)²
```

- Year-wise method:

  - Year 1: Interest₁ = P×R/100, Amount₁ = P + I₁  
  - Year 2: Interest₂ = Amount₁×R/100, A₂ = Amount₁ + I₂  

- Must-solve types:

  1. SI based (find P/R/T)  
  2. CI 2–3 years by factor/year-wise  
  3. Difference between CI &amp; SI  
  4. Given amount, find principal  

---

> [!TIP] 🚀  
> SI–CI ko formula-ratta se nahi, **story mode + year-wise logic** se padho.  
> 40–50 mixed questions (SI + CI + difference) practice karke,  
> tum exam me kisi bhi interest-based question ko **confidently tod paoge**.