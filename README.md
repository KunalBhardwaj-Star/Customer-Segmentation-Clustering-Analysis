# SmartCart Customer Segmentation 🛒

## Overview
This project applies **Unsupervised Learning** techniques to group customers based on their purchasing behavior, demographics, and response to marketing campaigns.

## Key Findings
* **Cluster 0 (Family Shoppers):** High number of children, focused on discounts.
* **Cluster 3 (High Value Singles):** High ROI, prefer premium services and personalization.

## Methodology
1. **Preprocessing:** Handled missing income data and performed feature engineering (Age, Tenure).
2. **Scaling:** Used **Standardization** to ensure high-value features didn't bias the model.
3. **Clustering:** Implemented K-Means to identify 4 distinct personas.

## How to Run
1. Clone the repo.
2. Install dependencies: `pip install -r requirements.txt`.
3. Run `smartCart.ipynb`.
