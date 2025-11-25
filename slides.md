---
marp: true
title: "Q4 2025 Earnings Report"
author: "24f1002781@ds.study.iitm.ac.in"
theme: custom-theme
paginate: true
footer: "Contact: 24f1002781@ds.study.iitm.ac.in"
---

<!-- _class: cover bg-overlay -->
<!-- _background: url('assets/bg.jpg') -->

# Q4 2025 Earnings Report

### Financial Performance & Strategic Insights

---

## Contact

- **Email:** 24f1002781@ds.study.iitm.ac.in
- **Team:** Financial Consulting

---

## Executive Summary

- **Revenue Growth:** 15% YoY
- **Profit Margin:** +2.3%
- **Market Rank:** Top 3 globally
- **Focus:** Digital transformation

> Strong fundamentals supporting sustained growth

---

## Key Financial Metrics

- **Net Profit Margin:** 18.5%
- **Return on Investment (ROI):** 22.3%
- **Earnings Per Share (EPS):** $4.75

---

## Python Example (data processing)

```python
import pandas as pd

df = pd.read_csv('quarterly_financials.csv')
df['net_margin'] = (df['net_income'] / df['revenue']) * 100
print(df[['revenue', 'net_margin']].head())
```

---

## JavaScript ROI Example

```javascript
function calculateReturns(initial, finalValue) {
  return ((finalValue - initial) / initial) * 100;
}

console.log(calculateReturns(10000, 12300).toFixed(2) + "%");
```

---

## Algorithmic Complexity (math examples)

- Merge sort average/worst-case complexity:

$$T(n) = 2T\left(\frac{n}{2}\right) + O(n) \Rightarrow T(n)=O(n\log n)$$

- Example recurrence and solution (Master Theorem):

$$T(n)=aT\left(\frac{n}{b}\right)+f(n)$$

For $a=2$, $b=2$, and $f(n)=n$ we get $T(n)=O(n\log n)$.

---

## Background Slide (example)

<!-- _background: url('assets/bg.jpg') -->
<!-- _class: bg-overlay -->

### Market Expansion

- Focus on APAC and EMEA growth channels

---

## Footer & Pagination

- Page numbers shown by Marp's `paginate: true` setting

---

