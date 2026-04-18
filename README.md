# Bank Marketing Campaign Analysis

**Objective:** Identify customer profiles with the highest conversion rates for term deposits and provide actionable recommendations to improve campaign efficiency.

---

## Business Problem

The bank conducted marketing campaigns but needed to understand:

- Which customer segments are most likely to subscribe
- How to optimize campaign costs and effort
- Where to focus future marketing efforts

---

## Dataset

- **Source:** [Bank Marketing Dataset — Kaggle]([https://www.kaggle.com/](https://www.kaggle.com/datasets/janiobachmann/bank-marketing-dataset/data))
- ~11,000 records with customer demographics, financial data, and campaign outcomes

---

## Tools Used

- **Python:** pandas, numpy, matplotlib
- **Environment:** Jupyter Notebook

---

## Key Findings

### Best Converting Customer Profile

| Attribute | Detail | Conversion Rate |
|---|---|---|
| Age | Under 25 or over 65 | High |
| Occupation | Management, technical, administrative | High |
| Pensioners | Dedicated segment | **66%** |
| Balance ≥ €1,700 | High-balance clients | **57%** |
| Balance < €122 | Low-balance clients | 36% |

### Untapped Opportunity

> **Blue-collar workers** represent the largest volume segment (1,944 clients) but convert at only **36%** — significant growth potential with targeted campaigns.

### Campaign Efficiency

- First **3 contacts** generate **86.6%** of all conversions
- Calls after the **11th contact** have minimal ROI — waste of resources

### Critical Success Factor

> Clients with **previous campaign success** convert at **91%**. Re-contacting this segment should be **Priority #1**.

---

## Recommendations

| Priority | Recommendation | Expected Impact |
|---|---|---|
| 1 | Create a dedicated retention campaign for previously successful clients | 91% conversion potential |
| 2 | Develop targeted offers for the blue-collar segment | Large untapped volume |
| 3 | Cap contact attempts at 3–5 per client | Reduce costs, protect brand reputation |
| 4 | Focus on balance-based segmentation — prioritize €1,700+ clients | Higher conversion yield |

---

## Next Steps

- [ ] Build a predictive model to score lead probability
- [ ] A/B test different messaging for the blue-collar segment
- [ ] Analyze cost-per-acquisition by contact method

---

*Built by **Vlad Dvorshiv** as part of a data analyst portfolio. Background in economics and statistics. Feedback welcome!*
