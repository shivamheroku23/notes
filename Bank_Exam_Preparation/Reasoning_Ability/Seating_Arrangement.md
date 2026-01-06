# 🪑 Seating Arrangement – Linear &amp; Circular

> 🧠 Seating Arrangement = Reasoning ka **star topic**.  
> Mostly **puzzles + seating** combo ke form mein aata hai.

---

## 🌟 1. Types of Seating Arrangement

1. **Linear** – in a row (facing north/south/both)
2. **Circular** – sitting around a circle (facing centre/outside)
3. **Square/Rectangular** – at corners &amp; sides
4. **Double row** – two rows facing each other

---

## 🔑 2. Common Instructions (Very Important)

- Facing **North** → person’s left/right = **your normal left/right**
- Facing **South** → left/right **reverse** ho jata hai.

### Quick trick:

- Facing North:  
  - Left = West (your left)  
  - Right = East (your right)
- Facing South:  
  - Left = East  
  - Right = West

> [!TIP] 💡  
> Jab bhi sitting diagram banao, top pe **N** likho, ya arrow, taaki confusion na ho.

---

## 🧍 3. Linear Arrangement – Example

### Question

Five persons – A, B, C, D, E – are sitting in a row facing **North**.

Clues:

1. A sits **second from the left** end.  
2. B sits **to the right of A** but not adjacent to A.  
3. C sits **at the extreme right** end.  
4. D sits **to the immediate left of E**.

### Step-by-Step

Five seats facing North:

```text
_   _   _   _   _
1   2   3   4   5   (from left to right)
```

From (1): A second from left → seat 2:

```text
_   A   _   _   _
1   2   3   4   5
```

From (3): C at extreme right → seat 5:

```text
_   A   _   _   C
1   2   3   4   5
```

From (2): B to the right of A but not adjacent:

- A at 2 → right of A = seats 3,4,5  
- Not adjacent → seat 3 not allowed  
- Seat 5 already C → so B at seat 4:

```text
_   A   _   B   C
1   2   3   4   5
```

Remaining seats: 1 and 3 → D &amp; E.  
From (4): D to immediate left of E.

Possible:

- D at 1, E at 2 ❌ (2 already A)  
- D at 3, E at 4 ❌ (4 is B)

So we misinterpreted something → let’s re-check.

Observation: We assumed B at 4 based on (2). Try **B at 3** (we rejected due to “not adjacent”, but actually check again):

- “B sits to the right of A but not adjacent to A”  
  → Right of A but not next seat.

Right of A = seats 3,4,5  
Not adjacent → seat **3 not allowed**. Correct.

So B at 4 only. D/E impossible? Let’s check again:

Oh, we forgot seat 1 and 3 for D/E:

To satisfy “D immediate left of E”:

- If E at 3, D at 2 ❌ (2=A)  
- If E at 4, D at 3 ✅ (E at 4 is B, but already B) ❌  
- If E at 2, D at 1 ❌ (2 already A)

So with C fixed at 5 and A at 2, there is no solution.  
Hence, we must re-check **C at extreme right** – we placed at seat 5; that’s correct.  
Problem: This example is slightly inconsistent as stated; in real exams, clues consistent honge.

Let’s adjust example slightly (to make it logically sound):

Change clue (2) to:

> 2. B sits **second to the right of A**.

Now:

From (1): A at seat 2  
Second to right → B at seat 4 ✅

Then from (4): “D sits to the immediate left of E.”

Remaining persons: D, E at seats 1 and 3:

- If E at 3, D at 2 ❌  
- If E at 1, D at 0 (not possible)  

So better to assume row numbered from left but unknown; let’s skip this flawed example complexity and use a clean one.

---

### Clean Linear Example

Five persons – A, B, C, D, E – are sitting in a row facing North.

Clues:

1. A sits at the **left end**.  
2. C sits **third to the right of A**.  
3. B is **immediate neighbour** of C.  
4. D does not sit at the right end.

### Solution

Seats:

```text
1   2   3   4   5
_   _   _   _   _
```

From (1): A at left end → seat 1.

From (2): C is third to right of A → seat 4 (1 → 2 → 3 → 4):

```text
A   _   _   C   _
1   2   3   4   5
```

From (3): B is neighbour of C → seat 3 or 5.

From (4): D not at right end → D ≠ seat 5

Let’s try B seat 3:

```text
A   _   B   C   _
1   2   3   4   5
```

Remaining = D, E at seat 2 &amp; 5.

D not at 5 → D at 2, E at 5.

Final:

- 1: A
- 2: D
- 3: B
- 4: C
- 5: E

---

## 🔵 4. Circular Arrangement – Facing Centre

### Important:

- Facing **centre**:  
  - Left = anticlockwise  
  - Right = clockwise

### Example

Six persons A, B, C, D, E, F are sitting around a circle facing **centre**.

Clues:

1. A sits **second to the right** of B.  
2. C sits **second to the left** of D.  
3. E is an immediate neighbour of B.  
4. F is not neighbour of A.

### Step-by-Step (Overview)

1. Draw a circle with 6 positions (just rough).  
2. Fix B somewhere.  
3. Place A second to the right of B (clockwise).  
4. Place E as neighbour of B.  
5. Fit C, D according to clue 2.  
6. Ensure F is not neighbour of A.

(Actual stepwise drawing practice strongly advised with pen-paper.)

---

## 🧠 5. Tips for Seating Arrangement

- Always mark directions (N / S / centre / outside).
- Start with the clue that gives **fixed position**:
  - “A sits at one of the ends”
  - “B sits exactly opposite C”
- Use possibility diagrams when needed.

---

## 📝 6. Practice (Simple Linear) – Try

Seven friends – P, Q, R, S, T, U, V – sit in a row facing North.

Clues:

1. P sits at the left end.  
2. R sits third to the right of P.  
3. Q is an immediate neighbour of R.  
4. T sits second to the right of Q.  
5. S does not sit at any end.  
6. U sits to the left of V.

🧩 Find exact arrangement.

---

### ✅ Hint / Outline Answer

Final order (left to right) will be:

P – V – R – Q – T – S – U  

(You can try to derive this using the same steps as above.)

---

> [!TIP] 🚀  
> Roz kam se kam **1–2 Linear + 1 Circular** sitting sets solve karo.  
> Starting mein rough lagega, but after practice, seating arrangement becomes **one of the highest scoring** parts in Reasoning.