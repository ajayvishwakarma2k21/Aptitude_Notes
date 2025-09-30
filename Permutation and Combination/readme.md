# 🧮 Permutation and Combination – Complete Notes

This guide covers all key concepts, formulas, tricks, and both basic and difficult questions for **permutation and combination**. Perfect for placements, competitive exams, and interviews.

---

## 📘 Key Concepts

- **Permutation:** Arrangement of objects in a specific order.
- **Combination:** Selection of objects without regard to order.

---

## 📚 Basic Formulas

### 1. **Permutation (Order Matters)**
- Number of ways to arrange $n$ objects taken $r$ at a time:
  $$
  {^n}P_r = nPr = \frac{n!}{(n - r)!}
  $$
- If all $n$ objects are used, total arrangements = $n!$

### 2. **Combination (Order Doesn’t Matter)**
- Number of ways to choose $r$ objects from $n$:
  $$
  {^n}C_r = nCr = \frac{n!}{r!(n - r)!}
  $$

---

## 📝 Tricks & Special Cases

- **Repetition Allowed:**
  - Permutations: $n^r$ (each of $r$ positions can be filled by any of the $n$ objects)
  - Combinations: $\displaystyle \binom{n+r-1}{r}$

- **Circular Permutations:**
  - Arranging $n$ objects in a circle: $(n-1)!$
  - If clockwise/anticlockwise counted as same: $\frac{(n-1)!}{2}$

- **Permutations with Repetition:**  
  - For $n$ objects with $p$ alike of one kind, $q$ alike of another, etc.:
    $$
    \text{Total arrangements} = \frac{n!}{p!q!r!...}
    $$

- **Selection with At Least/At Most Constraints:**  
  - Use combinations and add/subtract accordingly.

- **Arranging/Selecting with Restrictions:**
  - Treat "together" as a single unit.
  - For "not together" use total - together.

---

## 🧠 Example Questions (All Levels)

### **Example 1: Simple Permutation**
**Q:** In how many ways can 5 books be arranged on a shelf?

**A:** $5! = 120$ ways

---

### **Example 2: Simple Combination**
**Q:** From 8 students, select 3 for a team.

**A:** ${^8}C_3 = 56$ ways

---

### **Example 3: Permutations with Restrictions**
**Q:** In how many ways can the letters of the word "BANANA" be arranged?

**A:**  
- Total letters = 6 (A=3, N=2)
- Arrangements = $\frac{6!}{3!\,2!} = \frac{720}{12} = 60$ ways

---

### **Example 4: Circular Permutation**
**Q:** In how many ways can 7 people sit around a round table?

**A:** $(7-1)! = 720$ ways

---

### **Example 5: At Least/At Most Combinations**
**Q:** From 10 people, how many ways can a committee of at least 5 be formed?

**A:**  
$\displaystyle \sum_{r=5}^{10} {^{10}C_r} = {^{10}C_5} + {^{10}C_6} + {^{10}C_7} + {^{10}C_8} + {^{10}C_9} + {^{10}C_{10}}$

---

### **Example 6: Arrangements with Objects Together**
**Q:** In how many ways can the letters of "SUCCESS" be arranged so that all S’s are together?

**A:**  
- Treat all 3 S as 1 entity. Now letters: (SSS), U, C, C, E = 5 objects (C repeated)
- Arrangements = $\frac{5!}{2!} = 60$ ways

---

### **Example 7: Difficult – Placing Objects with Restrictions**
**Q:** In how many ways can 4 boys and 4 girls be seated in a row so that no two girls sit together?

**A:**  
- Arrange boys: $4! = 24$ ways
- Gaps between boys = 5. Place 4 girls in these gaps: ${^5}C_4 = 5$ ways
- Girls can be arranged among themselves: $4! = 24$ ways
- Total = $24 \times 5 \times 24 = 2880$ ways

---

### **Example 8: Difficult – Selection with Multiple Constraints**
**Q:** In how many ways can a committee of 5 be formed from 6 men and 4 women so that at least 2 women are included?

**A:**  
- Case 1: 2 women, 3 men: ${^4}C_2 \times {^6}C_3 = 6 \times 20 = 120$
- Case 2: 3 women, 2 men: ${^4}C_3 \times {^6}C_2 = 4 \times 15 = 60$
- Case 3: 4 women, 1 man: ${^4}C_4 \times {^6}C_1 = 1 \times 6 = 6$
- Total = $120 + 60 + 6 = 186$ ways

---

### **Example 9: Arrangements with Identical Objects (Advanced)**
**Q:** In how many ways can the letters of the word "MISSISSIPPI" be arranged?

**A:**  
- Letters: 11 (I=4, S=4, P=2)
- Arrangements: $\frac{11!}{4!\,4!\,2!} = \frac{39916800}{24 \times 24 \times 2} = 34650$ ways

---

### **Example 10: Advanced – Circular Permutation with Restrictions**
**Q:** In how many ways can 6 boys and 6 girls be seated around a round table so that no two girls are together?

**A:**  
- Arrange 6 boys in circle: $(6-1)! = 120$ ways
- Gaps between boys = 6. Place 6 girls: $6! = 720$ ways
- Total = $120 \times 720 = 86,400$ ways

---

### **Example 11: Advanced – Using Stars and Bars (Repetition Allowed)**
**Q:** How many ways can 5 identical balls be placed in 3 distinct boxes?

**A:**  
- Formula: $\binom{n + r - 1}{r}$, here $n=3, r=5$
- Ways = $\binom{3+5-1}{5} = \binom{7}{5} = 21$ ways

---

## 🧾 Quick Reference Table

| Situation                                 | Formula                                                 |
|--------------------------------------------|---------------------------------------------------------|
| n objects, r at a time (permutation)       | $nPr = \frac{n!}{(n-r)!}$                               |
| n objects, r at a time (combination)       | $nCr = \frac{n!}{r!(n-r)!}$                             |
| With repetition (permutation)              | $n^r$                                                   |
| With repetition (combination)              | $\binom{n+r-1}{r}$                                      |
| Circular permutation                       | $(n-1)!$                                                |
| Circular (identical, both directions same) | $\frac{(n-1)!}{2}$                                      |
| Arrangements with identical objects        | $\frac{n!}{p!q!r!...}$                                  |

---

## ⚡ Tricks & Tips

- For "at least"/"at most" selection, add up the relevant cases.
- "Together" → treat as single unit; "not together" → total minus together.
- For arrangements with restrictions, always start with the restriction.
- When objects/people are identical, divide by factorial of identicals.

---

**Practice these concepts and tricks to master permutation and combination for any level of aptitude test!**
