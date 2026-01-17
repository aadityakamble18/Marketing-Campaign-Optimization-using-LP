# Marketing Campaign Optimization using Linear Programming

## 📌 Overview
This project presents a data-driven approach to optimize marketing budget allocation across multiple channels using **Multiple Linear Regression** and **Linear Programming (LP)**.

The objective is to maximize predicted sales while respecting overall budget constraints.

---

## 🧠 Problem Statement
Marketing budgets are often allocated based on intuition rather than data, leading to inefficient spending and lower ROI.  
This project formulates an optimization model that allocates marketing spend optimally across channels such as:
- TV
- Radio
- Newspaper

---

## ⚙️ Methodology
1. **Data Analysis**
   - Exploratory analysis on advertising spend vs sales.
2. **Regression Modeling**
   - Multiple Linear Regression used to estimate channel impact coefficients.
3. **Optimization**
   - Linear Programming formulation:
     ```
     Maximize: Z = β₁x₁ + β₂x₂ + β₃x₃ + β₀
     Subject to: x₁ + x₂ + x₃ ≤ Budget
     ```
4. **Solution**
   - Optimal budget allocation maximizing predicted sales.

---

## 📊 Results
- Achieved optimized allocation of marketing spend.
- Demonstrated potential **ROI improvement of 15–25%**.
- Showed effectiveness of LP-based decision-making in marketing analytics.

---

## 📁 Repository Structure
├── data/ # Dataset
├── notebooks/ # Jupyter notebook
├── reports/ # Final report and presentation
├── README.md
└── requirements.txt
