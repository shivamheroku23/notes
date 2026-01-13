# 🔄 Input–Output – Machine Pattern Reasoning

> 🧠 Is topic mein ek “machine” input ko step-by-step badalti hai.  
> Hume pattern samajhkar kisi step ka output ya number of steps find karna hota hai.

---

## 🌟 1. Question Pattern

Given:

- One **input line** (numbers/words mixed)
- 4–6 **steps** (Step I, Step II, …)

Tasks:

- Find **Step X** for a new input.
- Find which step corresponds to a given output.
- Identify position of some element after certain step.

---

## 🔎 2. How to Detect Pattern (Step-by-Step)

1. **Input se Step I** ka change dekho.
2. Sirf **one change per step** hota hai usually.
3. Common patterns:
   - Numbers: arranging increasing/decreasing order
   - Words: alphabetical order
   - Words + numbers: both sorted separately
4. Check:
   - Kya leftmost ya rightmost element fix ho raha hai?
   - Kya numbers edges pe jaa rahe hain?

> [!TIP] 💡  
> Pattern spot karne ke liye **Input → Step I → Step II** ko side-by-side likho.

---

## 🧪 3. Example (Numbers + Words)

### Given:

Input:  
`go 15 come 8 here 20 now 3`

Step I:  
`3 go 15 come 8 here 20 now`

Step II:  
`3 8 go 15 come here 20 now`

Step III:  
`3 8 15 go come here 20 now`

Step IV:  
`3 8 15 20 go come here now`

Final step: `3 8 15 20 go come here now`

### Pattern Observation

- Numbers: 15, 8, 20, 3  
- Sorted ascending: 3, 8, 15, 20

Steps:

- Step I: smallest number 3 → leftmost  
- Step II: next smallest 8 → place after 3  
- Step III: next 15 → place after 8  
- Step IV: next 20 → after 15  
Words remain same order after numbers.

So **each step places one number in correct order**.

---

## 📘 4. Example Question Based on Pattern

If new Input is:

`take 25 rest 5 now 10 work 30`

Numbers: 25, 5, 10, 30 → order: 5, 10, 25, 30

We expect:

- Step I: `5 take 25 rest now 10 work 30`
- Step II: `5 10 take 25 rest now work 30`
- Step III: `5 10 25 take rest now work 30`
- Step IV: `5 10 25 30 take rest now work`

(Exact positions of words depend on exam pattern, but logic same hoga.)

---

## 🧮 5. Example with Words (Alphabetical Order)

Input:  
`red blue green yellow`

Step I: `blue red green yellow`  
Step II: `blue green red yellow`  
Step III: `blue green red yellow` (already sorted except “yellow” at last)

Pattern:

- Alphabetical: blue, green, red, yellow
- Each step mein **next smallest word** left side pe aa raha hai.

---

## 🧠 6. General Tips

- Input–Output questions mein **rough work allowed** – har step likh ke pattern pakdo.
- Kabhi-kabhi pattern:
  - Odd–even numbers shifting,
  - Largest number left, smallest right,
  - Word length based sorting.

---

## 📝 7. Practice (Conceptual) – Try

1. Input: `9 3 7 1`  
   Step I: `1 9 3 7`  
   Step II: `1 3 9 7`  
   Step III: `1 3 7 9`  

   👉 Pattern?  
   (Ans: In each step, **next smallest number** is placed in correct position.)

2. New Input: `8 2 5 4`  
   Based on above pattern, final step output will be?

---

### ✅ Answer Outline

For `8 2 5 4`:

Numbers sorted ascending: 2, 4, 5, 8 → So final step:  

`2 4 5 8`

---

> [!TIP] 🚀  
> Input–Output ke tough sets ke liye pehle 5–10 simple examples khud se banao:  
> - input numbers  
> - har step mein ek number sort karo  
> Ye habit develop ho jaaye to exam wale machine pattern questions fast ho jaayenge.