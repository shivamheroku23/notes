# 🔐 Coding–Decoding – Letter &amp; Word Patterns

> 🧠 Is topic mein ek word/number ko “code” diya hota hai.  
> Hume pattern pakadkar naye word ka code find karna hota hai.

---

## 🌟 1. Common Types

1. **Letter shifting** (A→D, B→E type)
2. **Position-based** (A=1, B=2… Z=26)
3. **Word coding** (APPLE = 50, then ORANGE = ?)
4. **Substitution** (if ‘+’ means ‘×’, etc.)

---

## 🔤 2. Alphabet Position Table (Bahut Important)

| Letter | Pos | Letter | Pos | Letter | Pos |
|--------|----:|--------|----:|--------|----:|
| A      |  1 | J      | 10 | S      | 19 |
| B      |  2 | K      | 11 | T      | 20 |
| C      |  3 | L      | 12 | U      | 21 |
| D      |  4 | M      | 13 | V      | 22 |
| E      |  5 | N      | 14 | W      | 23 |
| F      |  6 | O      | 15 | X      | 24 |
| G      |  7 | P      | 16 | Y      | 25 |
| H      |  8 | Q      | 17 | Z      | 26 |
| I      |  9 | R      | 18 |        |    |

> [!TIP] 💡  
> A–M tak ko yaad kar lo; N–Z derive ho sakte hain.

---

## 🔁 3. Letter Shifting

Example:

> In a certain code, CAT is written as FDW. How is DOG written?

Check letters:

- C → F (+3)
- A → D (+3)
- T → W (+3)

So pattern = **each letter +3**

DOG:

- D → G  
- O → R  
- G → J  

✅ Code = **GRJ**

---

## 🧮 4. Position Sum / Product Coding

Example:

> In a certain code, CAR = 24. How is BUS coded?

Find positions:

- C = 3, A = 1, R = 18  
  Sum = 3 + 1 + 18 = 22 (but code is 24)  
  Try product? Not likely.

Maybe pattern: (sum + 2) = 24

So for BUS:

- B = 2, U = 21, S = 19  
  Sum = 2 + 21 + 19 = 42  
  Sum + 2 = 44

✅ Code = **44**

(Exam mein clear logic dikhega.)

---

## 🧪 5. Word Coding Type

Example:

> In a certain code language,  
> “GO TO SCHOOL” is written as “51 35 79”.  
> “TO SCHOOL DAILY” is written as “35 79 64”.  
> What is the code for “DAILY”?

Observation:

- “GO TO SCHOOL” → 51 35 79  
- “TO SCHOOL DAILY” → 35 79 64  

Common words = “TO SCHOOL” → common codes = **35, 79**

Remaining in second: “DAILY” → remaining code = **64**

✅ DAILY = 64

---

## 🔄 6. Mathematical Symbol Coding

Example:

> If ‘+’ means ‘×’, ‘−’ means ‘+’, ‘×’ means ‘÷’ and ‘÷’ means ‘−’,  
> then find value of: 8 + 4 × 2 − 6 ÷ 3

Replace symbols:

- ‘+’ → ×  
- ‘×’ → ÷  
- ‘−’ → +  
- ‘÷’ → −

Expression becomes:

```text
8 × 4 ÷ 2 + 6 − 3
```

Now BODMAS:

1. 8 × 4 = 32  
2. 32 ÷ 2 = 16  
3. 16 + 6 = 22  
4. 22 − 3 = 19

✅ Answer = **19**

---

## 📝 7. Practice Questions (with Answers)

```text
1)  In a certain code, BALL is written as EDLO. How is CAT written?
    (Pattern hint: each letter +3)

2)  In a code language, if PEN = 40, then how is INK coded?
    (Positions: P=16,E=5,N=14; check sum +5)

3)  In a certain code, "HE IS TALL" → "27 18 52", 
    "HE IS SMART" → "27 18 63". 
    What is code for "SMART"?

4)  If '−' means '×', '×' means '+', '+' means '÷', then 
    find value of: 6 − 2 × 3 + 4

5)  In a certain code, FLOWER is written as SJVDVI.
    (Hint: letters go from ends of alphabet)
```

---

### ✅ Solutions (Outline)

1. BALL →  
   B(2)→E(5), A(1)→D(4), L(12)→O(15) → +3 shift  
   So CAT: C→F, A→D, T→W → **FDW**

2. PEN code 40:  
   P=16, E=5, N=14 → sum=35 → 35+5=40  
   INK: I=9, N=14, K=11 → sum=34 → 34+5=39 → **39**

3.  
   “HE IS TALL” → 27 18 52  
   “HE IS SMART” → 27 18 63  
   Common words: HE, IS → common codes: 27, 18  
   So SMART → remaining = **63**

4. Replace:

- ‘−’→×  
- ‘×’→+  
- ‘+’→÷  

Expression: `6 × 2 + 3 ÷ 4`  

Now original meaning:

6×2 =12  
3÷4=0.75  
12 + 0.75 = 12.75  

✅ Answer ≈ **12.75**

5. FLOWER → SJVDVI (thoda advanced pattern; actual exam mein options se pattern pick karna hota hai, yahan sirf idea ke liye diya hai).

---

> [!TIP] 🚀  
> Coding–Decoding mein sabse pehle **pattern dhoondo**:  
> position sum, letter shift, common word–common code, ya symbol change.  
> 20–30 questions solve karke pattern spotting ka “feel” aa jata hai.