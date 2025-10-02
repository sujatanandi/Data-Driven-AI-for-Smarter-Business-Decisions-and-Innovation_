
## Key Findings
- Centralized and hybrid MDM improve predictive accuracy by reducing duplication and inconsistent entities; decentralized MDM provides marginally faster Decision_Speed_Days with a small accuracy trade‑off.  
- AutoML adoption among Indian SMEs associates with higher Business_Performance_Score; descriptive and predictive analytics remain most common, indicating a capability and cost gap addressable via training and managed services.  
- XAI adoption aligns with higher Trust_Score and a positive trust–performance relationship in regulated sectors, making transparency a strategic value lever when embedded in validation and monitoring.

## SDG Alignment
- SDG 9: Stronger digital infrastructure and continuous innovation via disciplined MDM.  
- SDG 8 and SDG 10: Productivity gains and narrowed capability gaps through SME‑focused AutoML enablement.  
- SDG 12: Reduced analytic rework and waste via robust data governance.  
- SDG 11: Responsive operations from balanced routing by risk and timeliness.  
- SDG 16: Higher trust and accountability through XAI in regulated contexts.

## Data Schema (selected fields)
- Company_ID, Industry, Company_Size, Region  
- AI_Adoption_Level, Data_Quality_Score, MDM_Strategy  
- Analytics_Type_Used, XAI_Implemented, Trust_Score  
- Market_Trend_Prediction_Accuracy, Decision_Speed_Days  
- Business_Performance_Score, AI_Investment_USD

## Reproduce Core Analyses
1) Grouped means by MDM_Strategy:
- Market_Trend_Prediction_Accuracy  
- Decision_Speed_Days

2) SME AutoML impact:
- Compare Business_Performance_Score for AutoML adopters vs non‑adopters  
- Plot analytics type counts for Indian SMEs

3) Trust vs Performance (XAI adopters):
- Scatter Business_Performance_Score vs Trust_Score, color by Industry

## How to Use
- Open data/RM_dataset.csv in analysis environment of choice (Python/R).  
- Recreate figures similar to:
  - figures/2.1.jpg for accuracy by MDM  
  - figures/3.2.jpg for analytics type counts  
  - figures/1.1.jpg for trust vs performance among XAI users

## Interpretation Guide
- Treat MDM as a control surface for the accuracy–speed frontier: centralized for high‑risk analytics, decentralized for time‑critical tasks, hybrid for portfolio needs with explicit accuracy/latency service levels.  
- Enable SMEs with training, partner‑led deployments, and managed services to realize AutoML gains.  
- Institutionalize XAI checkpoints in validation and monitoring, tied to risk tiers and accountability.

## Citation
If this repository or dataset informs published work, please cite:
- The RM_dataset.csv, accompanying figures, and the manuscript included in docs/manuscript.

## License
This repository is intended for academic and non‑commercial research use. See LICENSE (if provided) or include appropriate attribution in derivative work.
