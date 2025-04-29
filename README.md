# A/B Email Campaign Test: Open, Click & Purchase Analysis

## Project Overview
This project simulates and analyzes an A/B test of an email marketing campaign using Python and prepares the dataset for integration into BI dashboards (e.g., Tableau, Power BI). The analysis compares two groups — control (A) and test (B) — across engagement metrics such as open rate, click rate, and purchase rate.

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
| Open Rate      | e.g. 35%          | 42%            | +7%         |
| Click Rate     | e.g. 18%          | 25%            | +7%         |
| Purchase Rate  | e.g. 7%           | 11%            | +4%         |

*Note: Actual values generated and printed via script.*

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
Tableau dashboard includes:
- Group filter (A/B)
- KPI cards: Open Rate, Click Rate, Purchase Rate
- Funnel bar chart
- Lift metrics
- Conversion breakdown table

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
