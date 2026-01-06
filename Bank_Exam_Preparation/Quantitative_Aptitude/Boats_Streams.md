# 🚣 Boats &amp; Streams – From Basics to Exam-Level Mastery

> 🧠 Goal: Downstream–Upstream ke **har pattern** ko samajhna,  
> taaki koi bhi Prelims + Mains question tum algorithm se tod sako.

---

## 🧭 Concept Map – Boats &amp; Streams kaha use hote hain?

- Time, Speed &amp; Distance ka direct extension
- Boat + stream = **relative speed** concept
- Use cases:
  - Simple speed/time questions
  - Round trip (upstream + downstream)
  - People walking on moving walkway (same logic)
  - Mains me: mixture-type, time-difference, ratio-based twists

Core idea:

> **Upstream = against flow → slower**  
> **Downstream = with flow → faster**

---

## 🌊 Core Definitions (Bilkul clear)

- **Still water**: Paani bilkul stable hai, koi flow nahi.
- **Stream / Current**: Paani ka flow – fixed speed se chal raha hai.
- **Boat speed in still water (B)**:  
  Boat ki khud ki speed, jab paani static ho.
- **Stream speed (S)**:  
  Flow ki speed.

- **Downstream**:  
  Boat direction = stream direction (saath-saath)  
  → speed **add** hogi.

- **Upstream**:  
  Boat direction opposite to stream  
  → speed **subtract** hogi.

---

## 🌟 Standard Formulas + Deep Logic

Let B = speed of boat in still water  
Let S = speed of stream

```text
Downstream speed (D) = B + S
Upstream speed   (U) = B − S
```

Isse hum reverse bhi kar sakte hain:

```text
B = (D + U) / 2
S = (D − U) / 2
```

### Logic (5th class level):

Socho:

- Boat apne dum se 10 km/hr chal sakta hai.
- Paani 2 km/hr se nadi ke direction me beh raha hai.

Downstream:

- Boat ka 10 + paani ka 2 = 12 km/hr (extra push)

Upstream:

- Boat 10, paani 2 opposite direction me kheech raha →  
  net = 10 − 2 = 8 km/hr (slow)

Yahi logic hai **plus/minus** ka.

> [!TIP] 💡  
> “Down me **Plus**, Up me **Minus**” –  
> downstream = plus, upstream = minus.

---

## 🔁 Algorithms / Stepwise Templates

### 🔹 Template A – Given Downstream &amp; Upstream → Find B &amp; S

Steps:

1. Downstream speed find karo: D = Distance / Time (agar directly given nahi).  
2. Upstream speed find karo: U = Distance / Time.  
3. Boat speed: B = (D + U)/2  
4. Stream speed: S = (D − U)/2

#### Example (Level 1)

Boat goes 20 km downstream in 2 hours and 20 km upstream in 4 hours.  
Find B &amp; S.

Step 1: D = 20/2 = 10 km/hr  
Step 2: U = 20/4 = 5 km/hr  
Step 3: B = (10+5)/2 = 15/2 = **7.5 km/hr**  
Step 4: S = (10−5)/2 = 5/2 = **2.5 km/hr**

---

### 🔹 Template B – Given B &amp; S → Find Time

Steps:

1. Find downstream / upstream speed using formulas.  
2. Use `Time = Distance / Speed`.

#### Example (Level 1)

B = 15 km/hr, S = 3 km/hr. Time to cover 36 km upstream?

Step 1: U = B − S = 15 − 3 = 12  
Step 2: Time = 36/12 = **3 hours**

---

### 🔹 Template C – Round Trip (Upstream + Downstream)

Type:

- Boat goes from A to B upstream, returns downstream → find total time, average speed, etc.

Steps:

1. Find U and D.  
2. Time up = d/U; Time down = d/D  
3. Total time = sum.  
4. Average speed (if required) = (total distance) / (total time)

---

## 🎯 Levels of Questions

### LEVEL 1 – Foundation (Prelims Easy)

#### Q1

A boat goes downstream at 12 km/hr and upstream at 8 km/hr. Find B and S.

```text
B = (12 + 8)/2 = 10 km/hr
S = (12 − 8)/2 = 2 km/hr
```

---

#### Q2

Speed of boat in still water is 10 km/hr and stream speed is 2 km/hr. Find time to cover 24 km downstream.

D = B + S = 10 + 2 = 12  
Time = 24/12 = **2 hours**

---

### LEVEL 2 – Exam Typical (Prelims + Simple Mains)

#### Q3

A man can row 30 km downstream in 3 hours and 18 km upstream in 3 hours. Find speed of boat in still water and speed of stream.

Downstream speed D = 30/3 = 10 km/hr  
Upstream speed U = 18/3 = 6 km/hr

B = (D + U)/2 = (10+6)/2 = 8 km/hr  
S = (D − U)/2 = (10−6)/2 = 2 km/hr

✅ Answer: B = 8 km/hr, S = 2 km/hr

---

#### Q4 (Difference in Time)

A boat goes 45 km downstream in 3 hours and the same distance upstream in 5 hours. Find:

1) B, S  
2) Time taken to go 60 km downstream.

D = 45/3 = 15  
U = 45/5 = 9  

B = (15+9)/2 = 24/2 = 12  
S = (15−9)/2 = 6/2 = 3  

Now for 60 km downstream:

Speed D = 15, so Time = 60/15 = **4 hours**

---

### LEVEL 3 – High-Level / Twisted (Mains Style)

#### Q5 – Ratio &amp; Time Difference

A boat takes 4 hours to travel from A to B upstream and 2 hours to return downstream. If the distance between A and B is 24 km, find the speed of boat in still water and stream speed.

Upstream:

- Distance = 24, Time = 4 → U = 24/4 = 6 km/hr

Downstream:

- Distance = 24, Time = 2 → D = 24/2 = 12 km/hr

Boat speed:

```text
B = (D + U)/2 = (12 + 6)/2 = 18/2 = 9
S = (D − U)/2 = (12 − 6)/2 = 6/2 = 3
```

✅ B = 9 km/hr, S = 3 km/hr

(Ye simple-looking hai, par mains me isko longer words me ghuma diya jaata hai.)

---

#### Q6 – Walking on Moving Walkway (Hidden Boats Logic)

On an escalator (moving staircase), a person takes 30 steps to reach top when escalator is moving. If he stands still, escalator alone takes him up in 75 seconds. Find the time taken to climb 30 steps when escalator is not moving. (Assume person takes equal time for each step.)

This is **exact same logic** as boats &amp; stream:

- Person’s speed = P
- Escalator’s speed = E
- Effective (when walking + escalator) = P + E
- Effective (only escalator) = E

Let total steps = N.

Case 1: Walking + escalator → 30 steps taken (so relative = 30 steps / t₁)  
Case 2: Standing → escalator alone takes N steps in 75 seconds.

But exam-level detailed solving yahan likhna long ho jayega; main sirf pattern dikha raha hoon:

> Moving walkway / escalator wale questions = **Boats &amp; Streams ka hi pattern**  
> bas units “steps/second” ho jate hain.

---

## ⚠️ Common Traps &amp; Mistakes

1. **Unit conversion bhool jana**  
   - Agar km &amp; hours use ho rahe hain, sab same unit me rakho.

2. **Downstream / Upstream galat identify karna**  
   - “with the stream” = downstream  
   - “against the stream” = upstream

3. **D &amp; U se B, S galat nikalna**  
   - Kabhi bhi B = D + U mat likh do. Hamesha:  
     - B = (D + U)/2  
     - S = (D − U)/2

4. **Round trip me distance mix karna**  
   - Same distance ho to hi average speed ka formula 2xy/(x+y) use karo.

---

## 🧾 Micro-Revision Box (Summary)

- Definitions:

```text
B = speed of boat in still water
S = speed of stream

Downstream speed D = B + S
Upstream speed   U = B − S

B = (D + U)/2
S = (D − U)/2
```

- Templates:

1. Given D &amp; U → Find B &amp; S:

   - D = d₁/t₁  
   - U = d₂/t₂  
   - B = (D+U)/2, S = (D−U)/2

2. Given B &amp; S → time for given distance:

   - For downstream: use D = B+S  
   - For upstream: use U = B−S  
   - Time = Distance / Speed

3. Round trip:

   - Time up = d/U  
   - Time down = d/D  
   - Total time = sum  
   - Avg speed = (2d) / (time up + time down)

- Must-solve types:

  - D &amp; U from distance/time → B &amp; S  
  - Given B &amp; S → time for upstream/downstream distance  
  - Round trip with time difference  
  - Moving walkway / escalator – same pattern

---

> [!TIP] 🚀  
> Boats &amp; Streams ko alag chapter mat samjho –  
> isko bas **TSD + Relative Speed** ka special case samjho.  
> 30–40 mixed questions (easy → high-level) karo,  
> ye formulas aur templates tumhare dimaag me permanent ho jayenge.