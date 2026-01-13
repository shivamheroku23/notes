# 🧪 Mixture &amp; Alligation – Ratio + Average Masterclass

> 🧠 Is chapter ko sahi se pakad loge, to Milk–Water, Tea blending, Cost price mix, DI me mixture-based questions sab aasaan ho jayenge.

---

## 🧭 Concept Map – Mixture Kya Test Karta Hai?

- **Average thinking** (weighted average)
- **Ratio thinking** (parts)
- Fast calculation using **alligation cross**
- Lot of DI, Profit–Loss, SI–CI type questions mixture par based hote hain.

---

## 🌟 1. Basic Mixture Idea (Simple Story)

2 cheezen mila rahe ho:

- Cheap item (C) – e.g., ₹20/kg tea
- Dear item (D) – e.g., ₹30/kg tea

Dono mila ke mixture milta hai jiska average (M) beech me aata hai:

```text
C < M < D
```

Mixture ka M → weighted average:

```text
M = (C×qty_C + D×qty_D) / (qty_C + qty_D)
```

Alligation method iss formula ko **bahut fast** bana deta hai.

---

## 🧮 2. Alligation Rule – Core Formula

When two kinds of items:

- Cheaper value = C  
- Dearer value = D  
- Mean (mixture) value = M

Then ratio of quantities:

```text
Cheaper : Dearer = (D − M) : (M − C)
```

> [!TIP] 💡  
> Number line socho:  
>
> C —— M —— D  
>  ↑      ↑  
>  |      |  
> (D−M) (M−C)  
>
> Jo difference door hota hai, uska quantity kam hota hai.

---

### Example 1 – Price Mixture

Tea at ₹20/kg and ₹30/kg are mixed to get tea of ₹26/kg. Find ratio of cheaper to dearer tea.

C=20, D=30, M=26

```text
Cheaper : Dearer = (D − M) : (M − C)
                     = (30 − 26) : (26 − 20)
                     = 4 : 6
                     = 2 : 3
```

So cheaper:dearer = **2:3**

---

## 💧 3. Percentage / Concentration Mixture

Same rule, but values = percentage:

### Example 2 – Milk Percentage

Solution A has 30% milk, B has 50% milk. In what ratio mix to get 40%?

C = 30, D = 50, M = 40

```text
A:B = (50 − 40) : (40 − 30) = 10 :10 = 1 :1
```

So mix in **1:1**.

---

### Example 3 – Different Percentage

Solution A has 20% alcohol, B has 50% alcohol. Obtain 40% solution.

C=20, D=50, M=40

```text
A:B = (50 − 40) : (40 − 20) = 10 :20 = 1 :2
```

So **20% : 50% = 1 : 2**

---

## 🔁 4. Algorithms / Templates

### 🔹 Template A – Given C, D, M → Find Ratio

1. Check that M is between C and D.  
2. Use alligation: (D−M):(M−C).  
3. That ratio gives quantity of C : D.

---

### 🔹 Template B – Given C, D, Ratio → Find M

If ratio of quantities known (q₁:q₂), mean M:

```text
M = (C×q₁ + D×q₂) / (q₁ + q₂)
```

Example:

C=20, D=30, ratio 2:3.

```text
M = (20×2 + 30×3)/(2+3) = (40+90)/5 = 130/5 = 26
```

---

### 🔹 Template C – Removal &amp; Replacement (Basic Version)

A container with total V litres. Remove R litres, replace with water, this done once.

Milk left after one operation:

```text
Milk left = V − R
Fraction of milk left = (V − R)/V
```

If repeated k times:

```text
Milk remaining = V × [(V − R)/V]^k
```

But bank prelims me mostly single operation hi aata hai.

#### Example 4 – Single Operation

Container has 40 litres of milk. Remove 8 litres milk and replace with water. Final milk?

Milk left = 40 − 8 = 32  
Water added = 8 → total = 40  
So milk = 32 litres.

---

## 🎯 Levels of Questions

### LEVEL 1 – Price/Percentage Alligation

1) Two types of rice ₹25/kg &amp; ₹35/kg mixed to get ₹31/kg. Find ratio.

C=25, D=35, M=31:

```text
25-part : 35-part = (35−31):(31−25)=4:6=2:3
Cheaper : Dearer = 2:3
```

---

2) Tea costing ₹100/kg and ₹160/kg mixed, mixture = ₹140/kg (no profit/loss). Ratio?

C=100, D=160, M=140:

```text
100:160 = (160−140):(140−100) = 20:40 = 1:2
```

---

### LEVEL 2 – Slightly Twisted

3) In what ratio should milk costing ₹30/litre be mixed with milk costing ₹40/litre so that mixture costs ₹36/litre?

C=30, D=40, M=36:

```text
30:40 = (40−36):(36−30) = 4:6 = 2:3
```

So 30₹ milk : 40₹ milk = **2:3**

---

4) A mixture has milk &amp; water in ratio 3:1. How much water to add to 60 litres of mixture so that ratio becomes 3:2?

Initial milk:water = 3:1 → total 4 parts → 1 part = 60/4 = 15  
Milk = 3×15 = 45 L, Water = 15 L.

Add x litres water:

New water = 15 + x  
Milk stays = 45  

New ratio = 3:2 → 45 : (15+x) = 3 : 2

```text
45/(15+x) = 3/2
3(15+x) = 90
45 + 3x = 90
3x = 45 → x = 15 L
```

---

### LEVEL 3 – High-Level / Mains-Style

#### Pattern – Profit + Mixture

A shopkeeper mixes two types of sugar costing ₹30/kg and ₹40/kg in some ratio and sells the mixture at ₹42/kg to get overall 20% profit. Find the mixing ratio.

Step 1: Find effective CP of mixture.

Let mixture CP = M. Profit = 20%, SP = 42:

```text
SP = M × 1.2 → 42 = 1.2M → M = 42/1.2 = 35
```

So mixture CP = ₹35/kg.

Now apply alligation on costs:

C=30, D=40, M=35:

```text
30:40 = (40−35):(35−30) = 5:5 = 1:1
```

So mixture ratio = **1:1**.

---

## ⚠️ Common Traps

1. **M must lie between C and D**

   - If M not between min(C,D) &amp; max(C,D), alligation not applicable as-is.

2. **Confusing which side is cheaper/dearer**

   - Cheaper value ke saamne hamesha (D−M) aata hai,  
     dearer ke saamne (M−C).

3. **Mixing percentage with absolute values**

   - Percentage mixture me always percentages ko C, D, M treat karo.

---

## 🧾 Micro-Revision Box (Summary)

- Alligation:

```text
Cheaper : Dearer = (D − M) : (M − C)
```

- Mean from ratio:

```text
M = (C×q₁ + D×q₂)/(q₁ + q₂)
```

- Removal–Replacement (k operations):

```text
Milk remaining = V × (1 − R/V)^k
```

- Must-practice question types:

  1. Cost-based (cheaper &amp; dearer articles)  
  2. Percentage-based (milk-water, acid-water)  
  3. Profit + mixture (effective CP from SP &amp; profit)  
  4. Simple remove &amp; replace (one-step)  

---

> [!TIP] 🚀  
> Mixture &amp; Alligation par 50–60 questions (easy se mains-level tak)  
> **sirf alligation cross + ratio logic** se karo –  
> kuch hi dino me ye chapter tumhara favourite ban sakta hai,  
> especially DI &amp; Profit–Loss ke complicated caselets me.