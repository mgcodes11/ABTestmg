
# A/B Test Simulation: Loyalty Offer Optimization for Customer Engagement

## 📖 Overview
In this project, we simulate an A/B test to evaluate two competing loyalty program offers:  
- **Offer A**: A free eBook related to the customer's interests  
- **Offer B**: A 15% discount on their next purchase  

Our goal is to determine which offer drives more customer engagement, measured by **click-through rate (CTR)** or **offer redemption rate**. The simulated data mimics a real-world scenario where an e-commerce company is experimenting with ways to enhance its loyalty program and increase customer retention.

---

## 🎯 Objective
- Simulate A/B test results for two loyalty program offers  
- Perform a statistical test (independent t-test) to evaluate whether the observed difference is significant  
- Visualize the results  
- Deliver business recommendations grounded in data  

---

## 🧪 Experiment Design

**Business Context:**  
A mid-sized e-commerce company is revamping its loyalty program. They want to test which incentive leads to higher engagement: a free downloadable eBook or a discount on a future purchase. Both offers are sent via email to randomly selected loyalty members.

**Test Parameters:**
- 10,000 users per group (Offer A and Offer B)
- Engagement is measured as a binary outcome (1 = clicked/redeemed, 0 = ignored)
- Simulated true engagement rates:  
  - Offer A (eBook): 8%  
  - Offer B (Discount): 10%

**Hypotheses:**
- **Null (H₀):** There is no difference in engagement rates between Offer A and Offer B  
- **Alternative (H₁):** There is a significant difference in engagement rates (two-tailed)

---

## 🛠️ Tools & Libraries
- Python (NumPy, pandas, SciPy, Matplotlib, Seaborn)
- Jupyter Notebook

---

## 📈 Steps
1. Simulate user behavior for both offer groups using a binomial distribution
2. Visualize the conversion rates
3. Conduct an independent t-test
4. Interpret the statistical results
5. Generate actionable business recommendations

---

## 📊 Sample Output  
Visuals and outputs will include:
- Bar chart comparing conversion rates
- p-value and t-statistic for test results
- Summary of statistical significance
- Recommendation on which offer to scale

---

## 📌 Key Insights (Expected from Analysis)
> *"The 15% discount offer shows a statistically significant higher engagement rate (p < 0.05) compared to the free eBook. This suggests customers respond more strongly to immediate monetary incentives than informational perks. We recommend expanding Offer B in future campaigns."*

---

## 💡 Future Enhancements
- Add bootstrapping to quantify uncertainty
- Include a power analysis to determine optimal sample size
- Introduce noise/bias (e.g., user demographics) to simulate real-world challenges
- Simulate long-term effects (e.g., repeat purchases)

---

## 📁 Folder Structure
```
loyalty_offer_ab_test/
│
├── ab_test_simulation.ipynb     # Main notebook
├── README.md                    # Project summary
├── charts/                      # Saved visualizations
└── data/                        # Optional saved simulated datasets
```
