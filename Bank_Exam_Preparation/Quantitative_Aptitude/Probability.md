# 🎲 Probability – Concept, Patterns &amp; Exam Tricks

> 🧠 Probability = “chance” ka maths – kisi event ke hone ki sambhavana.  
> Banking exams me mostly **simple discrete cases** (coins, dice, cards, selection) se questions aate hain.

---

## 🧭 Concept Map – Kya test hota hai?

- Counting favourable cases correctly
- Understanding “equally likely outcomes”
- Basic combinatorics (P&amp;C link)
- Misleading wording ko dhyaan se padhna

---

## 🌟 1. Core Definition

For an experiment with equally likely outcomes:

```text
P(Event) = (Number of favourable outcomes) / (Total number of possible outcomes)
```

Properties:

- 0 ≤ P(E) ≤ 1
- P(impossible event) = 0
- P(sure event)      = 1
- P(not E) = 1 − P(E)

---

## 🎲 2. Standard Models

### 2.1 Coin Toss

1 fair coin:

- Outcomes: H, T → total 2
- P(H) = 1/2, P(T) = 1/2

2 coins:

- HH, HT, TH, TT → total 4  

3 coins:

- HHH, HHT, HTH, THH, HTT, THT, TTH, TTT → total 8

---

### 2.2 Dice

1 standard die:

- Faces: 1,2,3,4,5,6 → total 6

Examples:

- P(getting 3) = 1/6  
- P(even) = {2,4,6} → 3/6 = 1/2  
- P(number &gt;4) = {5,6} → 2/6 = 1/3  

---

### 2.3 Playing Cards

Standard deck: 52 cards

- 4 suits: Hearts ♥, Diamonds ♦ (red), Clubs ♣, Spades ♠ (black)
- Each suit: 13 cards → A,2,3,4,5,6,7,8,9,10,J,Q,K
- Red cards = 26, Black cards = 26
- Face cards (J,Q,K) = 3 per suit → 12 total
- Aces = 4

Examples:

- P(red card) = 26/52 = 1/2  
- P(ace) = 4/52 = 1/13  
- P(face card) = 12/52 = 3/13  

---

## 🔁 3. Union &amp; Complement – Basic Logic

For events A, B:

- P(A or B) = P(A) + P(B) − P(A and B)
- P(not A) = 1 − P(A)

Example:

From a deck, P(card is red or a king)?

- Red cards = 26  
- Kings = 4  
- Red kings = 2

So:

```text
P(red or king) = (26 + 4 − 2) / 52 = 28/52 = 7/13
```

---

## 🎯 4. Levels of Questions

### LEVEL 1 – Basic (Prelims Easy)

1) A coin is tossed once. P(tails)?

= 1/2

---

2) A die is rolled. P(even)?

Even numbers: 2,4,6 → 3/6 = 1/2

---

3) From deck, P(black king)?

Black kings: ♣, ♠ → 2 cards  
Total = 52 → P = 2/52 = 1/26

---

### LEVEL 2 – Slightly Combined Events

4) A die is rolled. P(number &lt;4)?

Favourable = {1,2,3} → 3/6 = 1/2

---

5) A card is drawn. P(queen)?

Queens = 4 → P=4/52=1/13

---

6) A card is drawn. P(face card or ace)?

Face cards = 12, Aces = 4, but Aces are not face cards → disjoint:

Total favourable=16 → P=16/52 = 4/13

---

### LEVEL 3 – Bit More Involved (Mains flavour)

7) Two dice are thrown together. What is the probability that the sum is 7?

Total outcomes = 6×6 = 36

Sum 7 combinations:

(1,6),(2,5),(3,4),(4,3),(5,2),(6,1) → 6 ways

P = 6/36 = 1/6

---

8) Two cards are drawn from a deck **without replacement**. What is the probability that both are kings?

Total ways to choose 2 cards from 52: 52C2  
Favourable (2 kings from 4): 4C2

So:

```text
P = (4C2) / (52C2)
  = (6) / (1326)
  = 1 / 221
```

---

> [!TIP] 💡  
> Jahan multiple selections ho (2 cards, 3 persons, etc.) –  
> wahan P&amp;C ka idea (nCr) use karna simple hota hai.

---

## 📝 Practice Questions (with Answers)

```text
1)  A coin is tossed once. What is the probability of getting tails?

2)  A die is rolled. What is the probability of getting an odd number?

3)  A die is rolled. What is the probability of getting a number less than 4?

4)  From a deck of 52 cards, what is the probability of drawing a red card?

5)  From a deck of 52 cards, what is the probability of drawing a face card?

6)  From a deck of 52 cards, what is the probability of drawing a queen?

7)  A die is rolled. What is the probability of getting a multiple of 3?

8)  A card is drawn at random. What is the probability that it is a black king?

9)  A coin is tossed twice. What is the probability of getting two heads?

10) Two dice are thrown together. What is the probability that the sum is 10?
```

### ✅ Answers (Brief)

1) 1/2  
2) Odd: 1,3,5 → 3/6=1/2  
3) {1,2,3} → 3/6=1/2  
4) 26/52=1/2  
5) Face=12 → 12/52=3/13  
6) 4/52=1/13  
7) {3,6} → 2/6=1/3  
8) 2/52=1/26  
9) Outcomes: HH,HT,TH,TT → P(HH)=1/4  
10) Sum 10: (4,6),(5,5),(6,4) → 3/36=1/12

---

## 🧾 Micro-Revision Box

- P(E) = favourable / total  
- P(not E) = 1 − P(E)  
- Cards: 52 total, 26 red, 26 black, 4 suits, 13 per suit, 12 face cards  
- Dice: 6 outcomes, 36 for 2 dice  
- Use combinations for multiple draws (without replacement).

> [!TIP] 🚀  
> Probability me sabse bada game **counting sahi karna** hai.  
> Har question me pehle “total outcomes” likho, phir “favourable” carefully gino –  
> formula se zyada important yahi habit hai.