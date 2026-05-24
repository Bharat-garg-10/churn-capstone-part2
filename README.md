# Part 2: RFM Segmentation & Retention Strategy
## D2C Customer Churn Intelligence Capstone

### Overview
This project contains the second phase of the Customer Churn Capstone. It focuses on performing RFM (Recency, Frequency, Monetary) segmentation augmented with non-transactional signals (support tickets, return rates, and web sessions) to classify customers into actionable retention cohorts.

### Setup & Requirements
```bash
pip install -r requirements.txt
```

### Data
The `data/` folder contains the required CSV files from Part 1. 

### How to Run
1. Install dependencies: `pip install -r requirements.txt`
2. Open and run `rfm_segmentation.ipynb` to execute the segmentation logic and generate `segments.csv` and the charts.

### Repository Contents
| File | Description |
|---|---|
| `rfm_segmentation.ipynb` | Full RFM notebook with segmentation logic and generated visual charts. |
| `segments.csv` | Output file mapping every customer ID to their segment and key features. |
| `retention_strategy.md` | Strategic recommendations and campaign budget prioritization for each segment. |
| `manual_review_cases.md` | 10 ambiguous customer cases that require manual review or complex strategies. |
| `charts/` | Saved RFM scatter plots and segment distributions. |
| `data/` | The raw CSV files. |
| `requirements.txt` | Python dependencies. |

### Key Findings
- Our largest segment is **Needs Attention** (966 customers), accounting for a significant 68.5% churn risk.
- The **Champions** segment (389 customers) exhibits a flawless 0.0% churn rate, proving that high RFM directly correlates with brand loyalty.
- The **At-Risk High Value** segment requires immediate intervention, representing ₹4,209 average spend but facing 100% churn without our intervention.