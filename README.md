# 📌 Association Rule Mining: Apriori & ECLAT

> Discover meaningful customer purchase patterns using Apriori and ECLAT algorithms.

---

## 🎯 Objective  
Uncover hidden relationships between items frequently bought together to improve:
- 🛍️ Product recommendations  
- 🧃 Cross-sell strategies  
- 🧠 Business decision-making

---

## 🔍 What is Association Rule Mining?

Association Rule Mining is a data mining technique used to identify **frequent item combinations** in transactional datasets.

> "If customers buy bread and butter, they may also buy jam."

It helps in:
- 🔗 Discovering links between products  
- 🎯 Targeted marketing  
- 🛒 Smarter inventory planning

---

## 🚀 Techniques Used

### 🧮 Apriori Algorithm  
- Works in **horizontal format** (row-wise transaction data)  
- Generates frequent itemsets based on **minimum support**
- Derives **association rules** based on **minimum confidence**

### ⚡ ECLAT Algorithm   
- Uses **vertical format** (item → list of transactions)  
- Faster than Apriori for large or dense datasets  
- Finds frequent itemsets using **set intersections**  

---

## 📊 Results & Insights

### 🔹 Frequent Itemsets Discovered:
- 🥛 **Milk & Butter** frequently purchased together  
- 🍞 **Bread & Butter** co-occur across many transactions  
- 🥤 **Coke**, 🍞 **Bread**, and 🍯 **Jam** show significant patterns  
- 📌 ECLAT revealed deeper patterns like:
  - `['Bread', 'Butter', 'Milk']`
  - `['Butter', 'Milk', 'Coke']`

### 🔸 Association Rules (Apriori):
| Rule | Confidence |
|------|------------|
| Cookies → Milk | ✅ Strong |
| Bread & Butter → Milk | ✅ Strong |

---

## 🧠 Business Applications

These insights enable:
- 🛒 **Smart product placement**
- 🎯 **Targeted promotions**
- 📦 **Effective bundling**
- 🤖 **Personalized recommendations**
- 💸 **Dynamic pricing strategies**

---

## 📈 Visualizations

- 📊 **Bar Charts**: Show support of top itemsets  
- 🌐 **Network Graphs**: Visualize item relationships and rule strengths  

---

## 💡 Conclusion

This project combines the **Apriori** and **ECLAT** algorithms to build a robust understanding of customer buying behavior.  
These patterns can drive:
- Higher sales  
- Better customer satisfaction  
- Smarter retail strategies

---

> 📂 Want to try it out? Clone the repo, run the notebook, and explore your own dataset with Apriori or ECLAT!

---
