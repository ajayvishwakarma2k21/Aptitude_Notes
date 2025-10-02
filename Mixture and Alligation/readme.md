# Mixture and Alligation: Complete Notes

Mixture and Alligation is a fundamental topic in quantitative aptitude, especially for competitive exams like SSC, Banking, CAT, Railways, and more. This topic deals with mixing two or more entities (liquids, solids, costs, percentages) and finding their average value, or the ratio in which they must be mixed to achieve a desired mixture.

---

## 1. **Basic Concepts**

### **Mixture**
- A mixture is formed when two or more substances (components) are combined physically (not chemically).
- In exam questions, mixtures usually involve liquids (like milk and water), alloys (mixture of metals), or solutions (acid and water).

### **Alligation**
- Alligation is a rule that helps to find the ratio in which two or more ingredients at given prices must be mixed to obtain a mixture at a given price.
- The method can also be used for mixtures of different concentrations, strengths, or percentages.

---

## 2. **Types of Questions**

### **A. Simple Mixture Problems**
- Two or more substances mixed; find concentration or cost of resulting mixture.

**Formula:**

```
Average price/concentration = (Q₁ × C₁ + Q₂ × C₂) / (Q₁ + Q₂)
```

#### **Example:**
Mix 3L of milk at ₹20/L with 5L at ₹30/L. Cost per L = (3×20 + 5×30)/(3+5) = (60+150)/8 = ₹26.25/L

---

### **B. Replacement/Repeated Replacement**
- A part of the mixture is replaced with one of the components multiple times.

**Formula:**

```
Final Quantity = Initial Quantity × (1 - Replacement Qty / Final Volume)ⁿ
```

or, equivalently,

```
Final Quantity = Initial Quantity × ((Final Volume - Replacement Qty) / Final Volume)ⁿ
```

Where:
- **n** = Number of times replacement is done

#### **Example (From Image 1):**
A beaker contains 180 liters of alcohol. On each day, 60 liters are taken out and replaced by water. What is the quantity of alcohol after 3 days?

```
Final Alcohol = 180 × (1 - 60/180)³
              = 180 × (2/3)³
              = 180 × 2/3 × 2/3 × 2/3
              = 180 × 8/27
              = 53.3 liters
```

**Image Trick:**  
![Replacement Formula Example](attachment:image1)

---

### **C. Alligation Rule (Criss-Cross Method)**
Used to find the ratio in which two types must be mixed to get a mixture at a mean value.

**Formula:**

```
      C₁        C₂
       \       /
        \     /
         \   /
           M
   (C₂-M) : (M-C₁)
```

- Mix in this ratio (C₂-M):(M-C₁)

#### **Example:**
Mix sugar at ₹7/kg and ₹9/kg to get ₹8/kg:
Ratio = (9-8):(8-7) = 1:1

---

### **D. Problems on Concentration/Percentage**
- Mixing solutions of different percentages.

#### **Example:**
How much water to add to 40L of 30% alcohol to make it 20% alcohol?

Let x = water to add.
Alcohol quantity stays = 40 × 30% = 12L.
Total solution = 40 + x.

```
12 / (40 + x) = 20 / 100
12 = 0.2 × (40 + x)
12 = 8 + 0.2x
0.2x = 4
x = 20L
```

---

### **E. Profit & Loss based Mixture Problems**
- Cheating by mixing cheaper substances.

#### **Example:**
A milkman mixes water (free) with milk (₹20/L) to sell at cost price, and gains 25%. What is water % in mixture?

Let mixture = 1L. Cost = ₹20.
He sells 1L at ₹20, but cost is only milk used.
Let milk = x L, water = (1-x) L. His cost = ₹20x.

```
Profit = (20 - 20x) / 20x = 0.25
20 - 20x = 5x
20 = 25x
x = 0.8 L
So water = 0.2 L = 20%
```

---

## 3. **Short Tricks and Tips**

### **Trick 1: Alligation Ratio at a Glance**
- Always subtract diagonally (higher – mean, mean – lower).
- Place higher value on right, lower on left, mean in center.
- Ratio = (difference diagonally) : (difference diagonally).

### **Trick 2: Replacement Short Formula**
- For repeated replacement, percentage left:

```
% left = (1 - x/V)ⁿ × 100
```

If 10% of mixture replaced 3 times, % left = (0.9)³ × 100 ≈ 72.9%.

### **Trick 3: Water Added to Change Concentration**
- If x L water is added to S L solution of A% to make it B%:

```
Amount of Water to Add = (A × S - B × S) / B
```

### **Trick 4: Direct Profit % by Adulteration**
```
% profit = (Adulterant Quantity / (Total Mixture Quantity - Adulterant Quantity)) × 100
```

### **Trick 5: Mixing Two Mixtures of Same Components**
If two mixtures of the same two components are mixed (equal quantities):

```
If A:B in first is a:b, second is c:d, final ratio = (a+c):(b+d)
```

### **Trick 6: Alligation in Seconds**
- For prices/concentrations equally distant from mean, mix in 1:1 ratio.
- If mean is exactly midpoint, ratio is always 1:1.

### **Trick 7: Successive Removal (Quick Check)**
- After n replacements of y liters from x liters:

```
Final quantity = x × ((x-y)/x)ⁿ
```

- **Formula from image:**  
```
Final Alcohol = Initial Alcohol × (1 - Replacement Qty / Final Volume)ⁿ
```
Where n = number of days/replacements.

---

## 4. **Typical Exam Question Types**

1. **Finding average price/concentration of mixture**
2. **Finding ratio in which to mix two (or more) varieties**
3. **Problems on replacement and repeated replacement**
4. **Profit calculation by adulteration/cheating**
5. **Mixing solutions of different percentages/concentrations**
6. **Mixture problems involving alloys or solids**
7. **Successive mixing and removal**
8. **Finding initial/final quantity of a component**

---

## 5. **Practice Questions with Solutions**

### **Question 1:**
**In what ratio must 70% acid solution be mixed with 30% acid solution to obtain a 50% acid solution?**

**Solution:**
By alligation:
- Higher concentration (C₂) = 70%
- Lower concentration (C₁) = 30%
- Mean (M) = 50%

```
Ratio = (C₂ - M) : (M - C₁)
      = (70 - 50) : (50 - 30)
      = 20 : 20
      = 1 : 1
```

---

### **Question 2:**
**A vessel contains 40L of milk. 8L is taken out and replaced by water. This process is repeated 2 more times. How much milk is left after 3 such operations?**

**Solution:**

```
Remaining milk = 40 × (1 - 8/40)³
               = 40 × (0.8)³
               = 40 × 0.512
               = 20.48L
```

---

### **Question 3:**
**How much water must be added to 25L of a 36% acid solution to reduce the concentration to 20%?**

**Solution:**
Amount of acid = 25 × 36% = 9L  
Final solution = 25 + x

```
9 / (25 + x) = 20 / 100
9 = 0.2 × (25 + x)
9 = 5 + 0.2x
0.2x = 4
x = 20L
```
**Answer:** 20L water must be added.

---

### **Question 4:**
**A dishonest milkman adds water to milk and sells the mixture at cost price, thereby gaining 20%. What is the proportion of water in the mixture?**

**Solution:**
Let total mixture = 1L, cost price of milk = ₹1/L  
Let milk = x L, water = (1-x)L  
Cost = ₹x  
Selling price = ₹1  
Profit = (1 - x)/x

```
Given profit = 20% ⇒ (1 - x)/x = 0.2
1 - x = 0.2x
1 = 1.2x
x = 5/6

Water = 1 - 5/6 = 1/6
```

**Proportion of water = 1/6 or 16.67%**

---

### **Question 5:**
**20L of a mixture contains milk and water in the ratio 3:2. How much water must be added so that the ratio becomes 2:3?**

**Solution:**
Milk = (3/5) × 20 = 12L  
Water = (2/5) × 20 = 8L  
Let x = water to be added

```
New water = 8 + x
New ratio: 12 : (8 + x) = 2:3
3×12 = 2×(8 + x)
36 = 16 + 2x
20 = 2x
x = 10L
```

**Answer:** 10L water must be added.

---

### **Question 6 (Image Example):**
**A beaker contains 180 liters of alcohol. On first day, 60 liters of alcohol is taken out and replaced by water. Second day, 60 liters of mixture is taken out and replaced by water and the process continues day after day. What will be the quantity of alcohol in beaker after 3 days?**

**Solution:**

```
Final Alcohol = 180 × (1 - 60/180)³
              = 180 × (2/3) × (2/3) × (2/3)
              = 180 × (8/27)
              = 53.3 liters
```

**Answer:** 53.3 liters

---

### **Question 7:**
**How many liters of a 40% solution must be mixed with a 60% solution to get 100L of a 50% solution?**

**Solution:**
Let x = liters of 40%, so (100 - x) = liters of 60%

```
x × 40 + (100 - x) × 60 = 100 × 50
40x + 6000 - 60x = 5000
-20x = -1000
x = 50
```

**Answer:** 50L of 40% solution and 50L of 60% solution.

---

### **Question 8:**
**In what ratio should tea costing ₹80/kg be mixed with tea costing ₹120/kg so that the mixture costs ₹100/kg?**

**Solution:**
By alligation:

```
Ratio = (120-100):(100-80)
      = 20:20
      = 1:1
```

---

## 6. **Shortcuts and Key Points**

- **Alligation Rule** is best for two-component mixing for mean value.
- **Replacement Formula**: Use for repeated addition/removal.
- **% of profit by adulteration = (Adulterant quantity / Total mixture) × 100**
- For **successive mixing**, use the formula recursively.

---

**Practice is essential**—solving a variety of problems will help master this topic!
