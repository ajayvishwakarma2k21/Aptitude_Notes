# Simple and Compound Interest Notes (with Extra Shortcuts & Tricks)

## 1. Simple Interest (SI)

**Definition**: Simple Interest is calculated only on the original principal for the entire period.

### Formula:
- **SI = (P × R × T)/100**
- **Total Amount (A) = P + SI**

#### Shortcuts & Tricks:
- **SI for months:** SI = (P × R × Months) / (100 × 12)
- **SI for days:** SI = (P × R × Days) / (100 × 365) (or 366 for leap year)
- **If SI for each year is the same, it's Simple Interest!**

---

## 2. Compound Interest (CI)

**Definition**: Compound Interest is calculated on the principal plus all previous interest.

### Formula:
- **A = P × (1 + R/100)^T**
- **CI = A - P**

#### Shortcuts & Tricks:
- **For 2 years:**  
  CI = SI + (SI × R)/100  
  (where SI is for 2 years)
- **For 3 years:**  
  CI ≈ SI + 3 × (SI × R)/100 + (SI × R × R)/(100 × 100)
- **Difference between CI and SI for 2 years:**  
  Difference = P × (R/100)^2
- **Compounded Half-Yearly:**  
  R → R/2, T → 2T
- **Compounded Quarterly:**  
  R → R/4, T → 4T

---

## 3. Special & Direct Shortcuts

### Shortcut 1: Find Sum (Principal) Given SI and CI (for 2 years)
- **P = (CI - SI) × 100^2 / (R^2)**
  - Useful when given SI, CI for 2 years and rate.

### Shortcut 2: Quick Percentage Change for 2 Years CI
- If interest is compounded annually, the net percentage increase after 2 years is:
  - **Net % increase = 2R + (R^2)/100**
  - Example: 10% rate, Net = 2×10 + (10×10)/100 = 20 + 1 = 21%

### Shortcut 3: Amount Doubles/Triples/Quadruples?
- For doubling:  
  **(1 + R/100)^T = 2**  
  Take log both sides to solve for T or R.
- For tripling:  
  **(1 + R/100)^T = 3**
- For quadrupling:  
  **(1 + R/100)^T = 4**

### Shortcut 4: When Rate Changes Every Year
- **A = P × (1 + R1/100) × (1 + R2/100) × (1 + R3/100) ...**
- Multiply sequentially for each year.

### Shortcut 5: For Small Rates and Short Time (Approximation)
- **CI ≈ SI + (SI × R)/100**
- Very useful for quick calculations for 2 years and small rates.

### Shortcut 6: Interest for Fractional Time
- For 1 year 6 months at 10% p.a. compounded annually:
  - First year: 10% on P
  - Next 6 months: 10/2 = 5% on (P + 1yr interest)

---

## 4. Practice Questions

1. What will be the SI on ₹4000 at 6% per annum for 4 years?
2. Find the CI on ₹5000 at 12% per annum for 2 years.
3. The difference between CI and SI on ₹2500 for 2 years at 4% per annum is?
4. If the CI on a certain sum for 2 years at 5% per annum is ₹512.50, find the sum.
5. At what rate percent will ₹10,000 become ₹12,100 in 2 years, compounded annually?
6. In how many years will ₹5000 amount to ₹10,000 at 10% p.a. compounded annually?
7. If the amount becomes ₹5832 in 2 years, at 8% p.a. compounded annually, find the principal.

---

## 5. Explanation of Sample Questions

### Q1. What will be the SI on ₹4000 at 6% per annum for 4 years?
SI = (4000 × 6 × 4)/100 = ₹960

### Q2. Find the CI on ₹5000 at 12% per annum for 2 years.
Amount = 5000 × (1 + 12/100)^2 = 5000 × (1.12)^2 = 5000 × 1.2544 = ₹6272  
CI = 6272 - 5000 = ₹1272

### Q3. The difference between CI and SI on ₹2500 for 2 years at 4% p.a. is?
Difference = 2500 × (4/100)^2 = 2500 × 0.0016 = ₹4

### Q4. If the CI on a certain sum for 2 years at 5% per annum is ₹512.50, find the sum.
Let principal = P  
A = P × (1 + 5/100)^2 = P × 1.1025  
A - P = 512.50  
So, 1.1025P - P = 0.1025P = 512.50  
P = 512.50 / 0.1025 = ₹5000

### Q5. At what rate percent will ₹10,000 become ₹12,100 in 2 years, compounded annually?
A = P × (1 + R/100)^T  
12,100 = 10,000 × (1 + R/100)^2  
(1 + R/100)^2 = 1.21 ⇒ 1 + R/100 = 1.1 ⇒ R = 10%

### Q6. In how many years will ₹5000 amount to ₹10,000 at 10% compounded annually?
A = P × (1 + 10/100)^T  
10,000 = 5,000 × (1.1)^T  
(1.1)^T = 2  
T = log(2) / log(1.1) ≈ 7.27 years

### Q7. If the amount becomes ₹5832 in 2 years, at 8% compounded annually, find the principal.
A = P × (1.08)^2 = P × 1.1664  
P = 5832 / 1.1664 = ₹5000

---

## 6. Final Tips

- Always check whether interest is simple or compound—don't get tricked!
- For CI, look for compounding period; adjust R and T accordingly.
- Use difference shortcut for 2 years and small rates.
- For quick doubling/tripling questions, use log shortcut or memorize powers.
- For competitive exams: memorize the SI and CI difference formula for 2 years:  
  **P × (R/100)^2**
- If time is in months/days, convert to years before calculating.

---
