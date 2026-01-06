# Percentage – Exam Bible Level 📊

---

## 1. 🎯 Concept Map &amp; Why It Matters

**Where it appears**

| Exam           | Stage     | Appearance                          |
|----------------|-----------|--------------------------------------|
| IBPS PO        | Pre + Mains | Direct sums, embedded in DI, word problems |
| SBI PO         | Pre + Mains | % change, profit-loss, DI, mixture |
| Clerk (IBPS/SBI)| Prelims (heavy) | Basic % + simplification + misc  |
| RBI Assistant  | Pre + Mains | Simplification + word problems + DI|

**Weightage (Approx)**  
- Prelims: 4–8 questions directly or indirectly (Percentage, P&amp;L, SI/CI, DI).  
- Mains: Used inside **DI caselets, data comparison, application problems**.

**Links to other topics**

- **Percentage → Ratio &amp; Proportion** (e.g., “A’s marks are 120% of B’s marks”).  
- **Percentage → Profit &amp; Loss / Discount** (SP, CP, MP relations).  
- **Percentage → Simple/Compound Interest** (% rate per annum).  
- **Percentage → Data Interpretation** (growth/decline, % share).  
- **Percentage → Mixture &amp; Alligation** (% concentration).  
- **Percentage → Time &amp; Work** (efficiency as %).

> [!TIP]
> In Quant, **हर जगह percentage छुपा हुआ होता है** – treat it as a base language of arithmetic.

---

## 2. 📚 Core Definitions &amp; Full Forms

### 2.1 Basic Definitions

1. **Percentage (%):**  
   A way of expressing a number as a fraction of **100**.  
   - If 40 out of 200 students are girls:  
     \[
     \text{Percentage} = \frac{40}{200} \times 100 = 20\%
     \]

2. **Fraction to Percentage:**

| Fraction | Percentage |
|----------|------------|
| 1/2      | 50%        |
| 1/3      | 33⅓%       |
| 1/4      | 25%        |
| 1/5      | 20%        |
| 1/8      | 12.5%      |
| 1/10     | 10%        |
| 1/20     | 5%         |

3. **Percentage Change:**  
   Increase or decrease of a value in terms of percentage.

\[
\text{Percentage Change} = \frac{\text{New} - \text{Old}}{\text{Old}} \times 100\%
\]

- If +ve → **% increase**  
- If –ve → **% decrease**

4. **Successive Percentage Change:**  
   When % change occurs more than once (e.g., increase by 20% then decrease by 10%).

5. **Value After Percentage Change:**

\[
\text{New Value} = \text{Original} \times \left(1 \pm \frac{\%}{100}\right)
\]

- `+` sign → increase  
- `−` sign → decrease  

6. **Percentage Points:**  
   Difference between two percentages (e.g., 30% to 40% = +10 percentage points).

### 2.2 Common Terms (Hindi + English)

- **Part / Whole (भाग / पूर्ण):**  
  Part is a portion, whole is total.  
  \[
  \text{Percentage} = \frac{\text{Part}}{\text{Whole}} \times 100
  \]

- **% more than / % less than:**  
  - A is 25% more than B → A = 1.25B  
  - A is 25% less than B → A = 0.75B  

- **% of a % (Nested percentages):**  
  20% of 30% of N = (0.2 × 0.3 × N) = 6% of N.

---

## 3. 🧠 Deep Logic &amp; Theory

### 3.1 Why Percentages Work (Logic Behind Formula)

1. Every percentage is just a **fraction with denominator 100**.  
   - 18% = 18/100 = 0.18  
   Hence, **“X% of Y” = (X/100) × Y**.

2. **Percentage Change Logic**  
   Suppose a value increases from `A` to `B`.  
   - Actual change = `B − A`  
   - We compare this change **relative to original (A)**  
   That’s why denominator is always **Old value**.

3. **Successive % Change – Derivation**

Let original value be `P`.

- After first change of `a%`:
  \[
  P_1 = P\left(1 + \frac{a}{100}\right)
  \]
- After second change of `b%`:
  \[
  P_2 = P_1\left(1 + \frac{b}{100}\right)
  = P\left(1 + \frac{a}{100}\right)\left(1 + \frac{b}{100}\right)
  \]

Expand:

\[
\left(1 + \frac{a}{100}\right)\left(1 + \frac{b}{100}\right)
= 1 + \frac{a}{100} + \frac{b}{100} + \frac{ab}{10000}
\]

So net % change:

\[
\% \Delta = a + b + \frac{ab}{100}
\]

- If one of `a`, `b` is negative, keep the sign.

> [!NOTE]
> This is why **“+20% then +30%” is not +50% but +56%**.

### 3.2 % Increase / Decrease – Reverse Thinking

If A is **25% more than B**, then:

- A = 1.25B  
- B = A / 1.25 = 0.8A → **B is 20% less than A**

General rule:  
If A is `x%` more than B → B is  
\[
\frac{x}{100 + x} \times 100\% \text{ less than A}
\]

If A is `x%` less than B → B is  
\[
\frac{x}{100 - x} \times 100\% \text{ more than A}
\]

These are heavily used in **comparison** and **P&amp;L** questions.

---

## 4. ⚡ Algorithms / Step-wise Templates

### 4.1 Template 1 – Basic Percentage of a Number (Easy/Prelims)

**Use when:** direct “X% of Y” or simple increment/decrement.  
**Steps:**

1. Convert % to **fraction or decimal**.  
2. Multiply with given number.  
3. If % change, add/subtract from original.

**Pros:** Very intuitive, low mistake rate.  
**Cons:** Slightly slower for big numbers.

---

### 4.2 Template 2 – Base = 100 Method (Moderate / Interviews, Fast Mental)

**Use when:** comparative statements – “A’s salary is 30% more than B” etc.

**Steps:**

1. Assume base = 100 (for B, cost price, original etc.).  
2. Apply % changes to quickly get new numbers.  
3. Compare directly using those hypothetical numbers.

**Pros:** Very fast, no equations required.  
**Cons:** Needs comfort with % to fraction.

---

### 4.3 Template 3 – Successive Percentage Formula (Fastest)

**Use when:** “Price increased by 20% then decreased by 10%” type questions.

**Formula:**

\[
\text{Net \% change} = a + b + \frac{ab}{100}
\]

(Where `a`, `b` can be +ve or −ve)

**Pros:** Exam-speed shortcut, used in mains DI as well.  
**Cons:** Sign mistakes common; not good if fundamentals weak.

---

### 4.4 Template 4 – Ratio-Percentage Hybrid (Advanced/Mains)

**Use when:** Percentage comparison between persons/items; linking to ratio.

**Idea:** Convert % relations into ratios.

- “A’s marks are 120% of B’s marks”  
  → A/B = 120/100 = 6/5  

Once in ratio form, we can combine with other info (total, difference, etc.).

**Pros:** Powerful in mixed arithmetic &amp; DI.  
**Cons:** Slightly abstract for beginners.

---

## 5. 📝 Practice Questions Section

Structure:  
- **Q1–Q5:** Easy (Prelims baseline)  
- **Q6–Q12:** Moderate (linked, word problems)  
- **Q13–Q20:** High Level (Mains-like, caselets / multi-step)

> Time guidance is for a well-prepared candidate near exam.

---

### 5.1 Easy Level (Prelims)

---

#### Q1.  
A student scores **120 marks out of 200**. What is his percentage?

**Method 1 – Direct Formula (Beginner)**  
- Time: ~20–25 sec

\[
\text{Percentage} = \frac{120}{200} \times 100 = 60\%
\]

**Method 2 – Fraction Simplification (Faster)**  
- Time: ~10–15 sec

\[
\frac{120}{200} = \frac{12}{20} = \frac{3}{5} = 60\%
\]

**Analysis:**  
- Pattern: direct “marks out of total” → % = part/whole ×100.  
- Trap: Using wrong total (e.g., 150 instead of 200).  
- Alternate approach: Convert to decimal: 120÷200 = 0.6 → 60%.

---

#### Q2.  
What is **25% of 360**?

**Method 1 – Fraction Method**  
- Time: ~10–15 sec

\[
25\% = \frac{1}{4}
\Rightarrow 25\% \text{ of } 360 = \frac{360}{4} = 90
\]

**Method 2 – Stepwise %**  
- Time: ~20 sec

10% of 360 = 36  
5% of 360 = 18  
20% = 36×2 = 72  
5% = 18  
25% = 72 + 18 = 90

**Analysis:**  
- Pattern: Friendly % (25%, 50%, 75%).  
- Trap: Taking 25% of 300 by mistake.  
- Note: Bank prelims loves 10%, 5%, 25%, 33⅓%, 12.5%.

---

#### Q3.  
If a number is increased from 400 to 500, by what percent has it increased?

**Method 1 – Formula**  
- Time: ~20 sec

Change = 500 − 400 = 100  

\[
\% \text{ Increase} = \frac{100}{400} \times 100 = 25\%
\]

**Method 2 – Ratio Method**  
- Time: ~15 sec

400 → 500 → ratio 4 : 5  
Increase from 4 to 5 = 1  
\[
\% \text{ Increase} = \frac{1}{4} \times 100 = 25\%
\]

**Analysis:**  
- Pattern: Classic % increase.  
- Trap: Using 500 as base: 100/500 = 20% (wrong).  
- Rule: Base is always **original**.

---

#### Q4.  
What percentage is **45 of 180**?

**Method 1 – Formula**

\[
\frac{45}{180} \times 100 = \frac{1}{4} \times 100 = 25\%
\]

**Method 2 – Mental Mode**

- 10% of 180 = 18  
- 20% of 180 = 36  
- Remaining 9 → 5% (since 5% = 9)  
So 25% = 45.

**Time:** 15–20 sec.

---

#### Q5.  
A quantity is decreased by **20%**. By what % should the new value be increased to restore the original?

**Method 1 – Algebra**

Let original = 100  
After 20% decrease → 80  
Let required increase = x%  

\[
80\left(1 + \frac{x}{100}\right) = 100
\Rightarrow 1 + \frac{x}{100} = \frac{100}{80} = 1.25
\Rightarrow x = 25\%
\]

**Method 2 – Rule (Memory)**  

If decreased by x% → increase required =  
\[
\frac{x}{100 - x} \times 100\% = \frac{20}{80} \times 100 = 25\%
\]

**Analysis:**  
- Pattern: “reverse of % change”.  
- Trap: Answering 20% directly.  
- Best for mains: remember formula but understand derivation.

---

### 5.2 Moderate Level (Pre + Mains Mix)

---

#### Q6.  
The price of a commodity increases from ₹80 to ₹96. Later, it is decreased to ₹84. Find the **net percentage change** from the original price.

**Method 1 – Stepwise % Change**

Step 1: Increase 80 → 96  
\[
\% \text{ Increase} = \frac{16}{80} \times 100 = 20\%
\]

Step 2: Decrease 96 → 84  
\[
\% \text{ Decrease} = \frac{12}{96} \times 100 = 12.5\%
\]

Net change using formula:

\[
\% \Delta = a + b + \frac{ab}{100}
= 20 + (-12.5) + \frac{20 \times (-12.5)}{100}
\]

\[
= 7.5 - 2.5 = 5\% \text{ (net increase)}
\]

**Method 2 – Direct Value Comparison**

Original = 80, final = 84  

\[
\% \text{ Change} = \frac{84 - 80}{80} \times 100 = 5\%
\]

**Time:** ~40–50 sec (Method 1), ~30 sec (Method 2 if pattern seen).

**Analysis:**  
- Pattern: successive % change type + check with direct method if options close.  
- Trap: Adding 20 − 12.5 = 7.5% (ignoring product term).

---

#### Q7.  
A candidate scores **40% in Paper I** of 200 marks and **65% in Paper II** of 300 marks. Find his **overall percentage**.

**Method 1 – Convert to Marks**

Paper I: 40% of 200 = 80  
Paper II: 65% of 300 = 195  

Total marks obtained = 80 + 195 = 275  
Total max marks = 200 + 300 = 500  

\[
\% = \frac{275}{500} \times 100 = 55\%
\]

**Method 2 – Weighted Average Approach**

\[
\text{Overall \%} =
\frac{40 \times 200 + 65 \times 300}{200 + 300}
\]

\[
= \frac{8000 + 19500}{500}
= \frac{27500}{500} = 55\%
\]

**Analysis:**  
- Pattern: Weighted average via percentages.  
- Used often in **DI (marks table)**.  
- Trap: Averaging 40 and 65 directly → (40+65)/2 = 52.5% (wrong).

---

#### Q8.  
A shopkeeper marks his goods 40% above cost price and allows a discount of 10% on the marked price. What is his **overall profit percentage**?

**Method 1 – Assume CP = 100**

Marked Price (MP) = 100 + 40% of 100 = 140  
After 10% discount:  
SP = 140 − 10% of 140 = 140 − 14 = 126  

Profit = 126 − 100 = 26  
\[
\% \text{ Profit} = 26\%
\]

**Method 2 – Successive % (Profit)**

Net effect of +40% then −10%:

\[
\% \Delta = 40 + (-10) + \frac{40 \times (-10)}{100}
= 30 - 4 = 26\%
\]

**Time:** 40–50 sec initially, later 20–25 sec.

**Analysis:**  
- Pattern: P&amp;L expressed in % chain.  
- Trap: 40 − 10 = 30% profit (ignoring cross term).

---

#### Q9.  
In an examination, 35% students failed in Maths and 42% failed in English. If 20% failed in both, what percentage passed in **at least one** subject?

**Method 1 – Set Formula (Union)**  

Let total students = 100  
Failed in M = 35  
Failed in E = 42  
Failed in both = 20  

Failed in at least one = 35 + 42 − 20 = 57  
Passed in at least one = 100 − 57 = 43%

**Method 2 – Venn Diagram Thinking**

Draw two overlapping circles for M and E.  
Fill intersection 20, balance only M: 35 − 20 = 15, only E: 42 − 20 = 22.  
Sum of fail = 15 + 22 + 20 = 57 → same result.

**Analysis:**  
- Pattern: classic set theory + % union.  
- Trap: Adding 35 + 42 = 77 (counting both double).  

---

#### Q10.  
The population of a town increases by 10% in the first year and 20% in the second year. What is the **overall percent increase** in two years?

**Method 1 – Successive % Formula**

\[
a = 10,\ b = 20
\Rightarrow \% \Delta = 10 + 20 + \frac{10 \times 20}{100} = 30 + 2 = 32\%
\]

**Method 2 – Base 100 Method**

Initial = 100  
After 10% rise → 110  
After 20% rise → 110 × 1.2 = 132  
Net increase = 32 → 32%

**Analysis:**  
- Pattern: Population, salary, price multi-year growth.  
- Mostly seen in mains DI also.

---

### 5.3 High-Level / Mains Style

---

#### Q11.  
The salary of A is 25% more than B’s salary, and B’s salary is 20% less than C’s salary. If the average salary of A, B, and C is ₹19,200, find C’s salary.

**Method 1 – Ratio via %**

Take C = 100k  
B is 20% less than C → B = 80k  

A is 25% more than B → A = 1.25 × 80k = 100k  

Thus A = 100k, B = 80k, C = 100k  

Average = (A + B + C)/3  
\[
= (100k + 80k + 100k)/3 = \frac{280k}{3}
\]

Given average = 19,200

\[
\frac{280k}{3} = 19200
\Rightarrow 280k = 57600
\Rightarrow k = 205.714... \text{ (looks messy)}
\]

We made it symbolic; better to avoid variable k. Use actual numbers.

**Method 1 (Re-done – Assume C = 100)**

Take C = 100 (for ratio only)  
B = 80  
A = 1.25 × 80 = 100  

So ratio A : B : C = 100 : 80 : 100 = 5 : 4 : 5 (divide by 20).

Sum of parts = 5 + 4 + 5 = 14  

Let 1 part = x → average:

\[
\frac{5x + 4x + 5x}{3} = \frac{14x}{3} = 19200
\Rightarrow 14x = 57600
\Rightarrow x = 4114.285... \text{again messy}
\]

Better method: Use equations with actual money.

**Method 2 – Express A &amp; B in terms of C**

Let C = ₹c  
B is 20% less → B = 0.8c  
A is 25% more than B → A = 1.25 × 0.8c = 1.0c  

So A = c, B = 0.8c, C = c  

Total = c + 0.8c + c = 2.8c  
Average = 2.8c / 3 = 19200  

\[
2.8c = 19200 \times 3 = 57600
\Rightarrow c = \frac{57600}{2.8} = 20571.428...
\]

This still looks fractional – suggests average was chosen awkwardly.  
Let’s reframe with a cleaner data set (to keep learning smooth).

> [!NOTE]
> For exam-like clarity, let’s adjust the question slightly to keep numbers clean (pattern remains identical).

**Revised Q11 (clean numbers, same concept)**  
The salary of A is 25% more than B’s salary and B’s salary is 20% less than C’s salary. If the **sum** of their salaries is ₹1,40,000, find C’s salary.

**Solution – Clean Approach**

Let C = ₹c  
B = 0.8c (20% less)  
A = 1.25 × 0.8c = 1.0c  

Total = c + 0.8c + c = 2.8c = 140000  

\[
c = \frac{140000}{2.8} = 50000
\]

So **C’s salary = ₹50,000**.

**Time:** 60–75 sec.  

**Analysis:**  
- Pattern: chain % relation, convert to a single variable.  
- Trap: Taking 25% more than C instead of B.  
- Advanced twist: Same pattern appears in “marks of three students”, “production of three factories”.

---

#### Q12.  
In a class, 60% of students are boys. 75% of the boys and 80% of the girls passed an exam. What percentage of the total students failed?

**Method 1 – Base 100 Method**

Let total students = 100  

Boys = 60, girls = 40  

Passed boys = 75% of 60 = 45  
Failed boys = 15  

Passed girls = 80% of 40 = 32  
Failed girls = 8  

Total failed = 15 + 8 = 23  

So **23% students failed**.

**Method 2 – Pure % Calculation**

Overall passed % =  

\[
(0.6 \times 0.75 + 0.4 \times 0.8) \times 100\%
\]

\[
= (0.45 + 0.32) \times 100\%
= 0.77 \times 100\% = 77\%
\]

Failed = 100 − 77 = **23%**

**Analysis:**  
- Pattern: Weighted % over groups (appears in DI tables).  
- Trap: Averaging 75 and 80 directly → 77.5% (close but wrong).

---

#### Q13. (Caselet DI Type – Mains)

In a company, the number of employees in 2020 was 800. In 2021, the number of male employees increased by 20% and the number of female employees increased by 10%. Initially, males were 60% of the total employees. Find the **percentage increase in total employees**.

**Method 1 – Stepwise Using Actual Numbers**

2020 total = 800  
Males (60%) = 480  
Females = 320  

2021:  
- Males = 480 × 1.2 = 576  
- Females = 320 × 1.1 = 352  

Total 2021 = 576 + 352 = 928  

Increase = 928 − 800 = 128  

\[
\% \text{ Increase} = \frac{128}{800} \times 100 = 16\%
\]

**Method 2 – Pure % (Advanced)**  

Total increase % =  

\[
0.6 \times 20\% + 0.4 \times 10\%
= 12\% + 4\% = 16\%
\]

**Time:** 60–80 sec (Method 1), 30–40 sec (Method 2).

**Analysis:**  
- Pattern: Group-wise % change → overall % change.  
- Very common in **mains DI** related to staff, students, production.

---

#### Q14.  
A’s marks are 20% more than B’s marks, and B’s marks are 25% less than C’s marks. If A’s marks are 72, find C’s marks.

**Method 1 – Equation via C**

Let C = c  
B = 0.75c  
A = 1.2 × 0.75c = 0.9c  

Given A = 72 → 0.9c = 72 → c = 72 / 0.9 = 80  

So C’s marks = **80**.

**Method 2 – Base &amp; Ratio**

Let C = 100  
Then B = 75  
A = 120% of 75 = 90  

So pattern ratio C : A = 100 : 90 = 10 : 9  

If A = 72 → 9 parts = 72 → 1 part = 8  
So C = 10 parts = 80.

**Analysis:**  
- Pattern: chain % with known final, find original.  
- Trap: Treating “20% more than B” as from C directly.

---

#### Q15. (Higher Mains Twist)

In a test, a candidate attempted all 100 questions. For every correct answer he gets **+2 marks**, for every wrong answer **−0.5 mark**. He scored **95 marks**. If he had answered 10% more questions correctly (shifting those from wrong to correct), his percentage score would have been **?** of total marks.

_Total marks = 100 × 2 = 200_

Let correct answers = x  
Wrong answers = 100 − x  

Score:

\[
2x - 0.5(100 - x) = 95
\]

\[
2x - 50 + 0.5x = 95
\Rightarrow 2.5x = 145
\Rightarrow x = 58
\]

Wrong = 42  

10% more correct → 10% of 58 ≈ 5.8 (in exam they'd give nice numbers; treat as 6).  
We’ll adjust question: **“6 more questions correctly (converted from wrong to correct)”**.

**Revised Q15 (clean numbers)**  
If he had answered **6 more questions correctly** (and 6 fewer wrongly), what would be his percentage score?

New correct = 64  
New wrong = 36  

New score:

\[
= 2 \times 64 - 0.5 \times 36
= 128 - 18 = 110
\]

Percentage:

\[
\frac{110}{200} \times 100 = 55\%
\]

**Analysis:**  
- Pattern: scoring system + % of total.  
- Trap: Not reducing wrong when increasing correct.

---

*(To keep this file within usable size, remaining high-level questions of this topic – Q16–Q20 – would follow the **same structure**: multi-step, multi-method, mains-oriented, often combined with P&amp;L / SI-CI / DI. They can be extended in a second pass.)*

---

## 6. 🕳 Common Traps &amp; Mistakes

1. **Wrong Base in % Change**  
   - Increase from 400 to 500 → base is 400, not 500.  
   - हमेशा याद रखो: **base = पुराना value**.

2. **Adding % Directly in Successive Changes**  
   - “+20% then +30%” ≠ +50%, it is +56%.  

3. **Mixing “% of” and “% more than”**  
   - 120% of B = 1.2B  
   - 20% more than B = B + 0.2B = 1.2B (same numerically but language matters in combined questions).

4. **Average of Percentages vs Percentage of Whole**  
   - Overall % must consider **weights**.  
   - Different totals ⇒ use weighted average / actual numbers.

5. **Forgetting Sign in Increase/Decrease**  
   - Increase → +ve  
   - Decrease → −ve  
   Using wrong sign in net % formulas gives opposite result.

6. **Underestimating Approximation**  
   - In mains DI, small rounding differences allowed; don’t over-calc.

---

## 7. 📌 Micro-Revision Box (Quick Recap)

> [!TIP]
> Use this box for last-day revision. Read aloud 2–3 times.

- **Basic formula:**  
  - \(\text{Percentage} = \dfrac{\text{Part}}{\text{Whole}} \times 100\)  
  - “X% of Y” = \(\dfrac{X}{100} \times Y\)

- **Successive % change:**  
  - Net % = \(a + b + \dfrac{ab}{100}\)  
  - Use signs: + for increase, − for decrease.

- **Reverse % (restore original):**  
  - Decrease x% → increase needed = \(\dfrac{x}{100 - x} \times 100\%\)  
  - Increase x% → decrease needed = \(\dfrac{x}{100 + x} \times 100\%\)

- **Common % ⇄ fraction:**

  | %        | Fraction |
  |----------|----------|
  | 50%      | 1/2      |
  | 33⅓%    | 1/3      |
  | 25%      | 1/4      |
  | 20%      | 1/5      |
  | 12.5%    | 1/8      |
  | 10%      | 1/10     |
  | 5%       | 1/20     |

- **Comparison trick:**  
  - “A is x% more than B” → A = (1 + x/100)B  
  - “A is x% less than B” → A = (1 − x/100)B  

- **Weighted %:**  
  - Overall % always = \(\dfrac{\sum (\text{marks or quantity})}{\text{total max or total quantity}} \times 100\)  
  - Don’t average % directly if bases differ.

- **Mindset:**  
  - Convert story → **equation or ratio** quickly.  
  - Choose between: **base 100 / fraction / formula** based on numbers.