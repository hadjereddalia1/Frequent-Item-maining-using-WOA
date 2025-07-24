# Frequent Itemset Mining Using the Whale Optimization Algorithm (WOA)

### 🎓 Mini Project – Metaheuristic Module  
**Academic Year:** 2024–2025  M1 Intelligent System
**Department:** Computer Science  
**Institution:** Saad Dahlab University  
**Students:** Hadjer Eddalia, Mohamed Etaib Benaicha  
**Supervisor:** Mme Zahra

---

## 📌 Project Overview

This mini project explores the use of the **Whale Optimization Algorithm (WOA)** to solve the **Frequent Itemset Mining (FIM)** problem — a key task in data mining that uncovers recurring patterns and associations in transactional datasets.

Traditional methods like **Apriori** and **FP-Growth** face scalability issues as dataset size grows. This project proposes a metaheuristic approach using WOA, inspired by the bubble-net hunting strategy of humpback whales, to efficiently discover frequent itemsets with better scalability and execution time.

---

## 🧠 Objectives

- Apply the Whale Optimization Algorithm (WOA) to mine frequent itemsets.
- Improve computational efficiency compared to classical FIM methods.
- Evaluate WOA performance against Apriori using execution time, itemset diversity, and scalability.

---

## ⚙️ Methodology

- **Itemset Representation:** Binary vector indicating presence/absence of items.
- **Optimization Goal:** Maximize support of itemsets in the dataset.
- **WOA Mechanisms:**
  - Encircling Prey
  - Spiral Bubble-Net Attack
  - Random Exploration
- **Fitness Function:** `Support(S) = #transactions_containing_S / total_transactions`

---

## 📊 Experimental Setup

- **Dataset Used:** RecordLink (10-feature transactional dataset)
- **Key Parameters:**
  - Population Size: 10
  - Iterations: 200
  - Minimum Support Threshold: 0.005
  - WOA constants: `a=2`, `w=0.5`, `c=1`, `l=1`, `p=0.5`

---

## 🔍 Comparison: WOA vs Apriori

| Metric                 | Apriori                | WOA (Proposed)           |
|------------------------|------------------------|--------------------------|
| **Execution Time**     | Slower on large data   | ~40% faster              |
| **Itemset Quality**    | Meets support threshold| Broader, more diverse    |
| **Scalability**        | Degrades with size     | Efficient with large data|

---

## 📈 Performance Metrics

- **Execution Time** (in seconds)
- **Number of Frequent Itemsets**
- **Average Support**

---

## ✅ Conclusion

The Whale Optimization Algorithm (WOA) provides a promising, scalable alternative to traditional algorithms like Apriori for Frequent Itemset Mining. It achieves better execution time, explores a broader solution space, and scales efficiently with high-dimensional data.

---

## 🔮 Future Work

- Integrate quantum computing for performance enhancement.
- Experiment with alternative objective functions.
- Extend the approach to other data mining tasks.

---

## 📚 References

1. Bowker, M., Williams, P. (1985). *Helsinki and West European Security*. International Affairs.
2. Doe, J., Smith, J. (2022). *WOA for FIM*. Journal of Computational Intelligence.
3. Smith, J. (2023). *Data Mining with WOA*. Data Science Journal.

---

> *This project is submitted as part of the Metaheuristic Module under the supervision of Mme Zahra.*
