# A/B Email Campaign Test: Open, Click & Purchase Analysis

## Project Overview
This project simulates and analyzes an A/B test of an email marketing campaign using Python and prepares the dataset for integration into Tableau. The analysis compares two groups - control (A) and test (B) across engagement metrics such as open rate, click rate, and purchase rate.

The goal is to demonstrate statistical reasoning, performance comparison, and BI-readiness in a business context.

---

## Dataset Summary
- **Total Users**: 500
- **Groups**: A (Control), B (Test)
- **Simulated Behaviors**:
  - `open`: whether the email was opened
  - `click`: whether the recipient clicked inside the email
  - `purchase`: whether the recipient made a purchase after clicking

Conversion funnel: `open → click → purchase`, with Group B having slightly improved probabilities.

---

## Key Metrics
| Metric         | Group A (Control) | Group B (Test) | Lift        |
|----------------|-------------------|----------------|-------------|
| Open Rate      | 31.1%             | 39.0%          | +7.88%      |
| Click Rate     | 7.88%             | 8.88%          | +1%         |
| Purchase Rate  | 1.24  %           | 1.16%          | -0.09%      |


---

## Files
```
AB_Email_Campaign_Test/
├── ab_campaign_results.csv      # Simulated user-level data
├── ab_test_analysis.ipynb       # Jupyter Notebook with code and analysis
├── ab_summary_metrics.csv       # Aggregated summary for BI dashboards
├── README.md                    # Project documentation
```

---

## BI Dashboard 

Explore the interactive Tableau dashboard here:  
👉 [A/B Testing Campaign Performance – Tableau Public](https://public.tableau.com/app/profile/mariia.maslova/viz/ABTestingCampaingPerformance/Dashboard1)

Tableau dashboard includes:
- Group filter (A/B)
- KPI cards: Open Rate, Click Rate, Purchase Rate
- Funnel bar chart
- Lift metrics
- Сomparison of A and B by stages

### ✨ Key Insights from the Dashboard:

- **Group B** achieved a significantly higher **Open Rate** of **39%**, compared to **31%** in Group A.  
- **Click Rate** was also better in Group B (**8.88%**) than in Group A (**7.88%**), indicating stronger engagement overall.
- **Purchase Rate** did not improved in Group B (**1.16%** vs **1.24%**), suggesting that the email modifications didn't show the growth in purchase.
- The **vertical funnel visualizations** show user drop-off at each stage clearly and effectively.

---

## How to Run
1. Clone this repository:
    ```bash
    git clone https://github.com/msmaslova/ab-email-campaign-test.git
    ```
2. Install requirements:
    ```bash
    pip install pandas numpy faker
    ```
3. Open and run `ab_test_analysis.ipynb` in Jupyter.
4. Load `ab_campaign_results.csv` into your preferred BI tool.

---

## Contact
Created with ❤️ by Mariia Maslova.  
