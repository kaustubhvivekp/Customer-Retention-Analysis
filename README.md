# Customer Retention & Revenue Growth Analysis  

## Overview  
This project analyzes customer retention patterns and revenue growth drivers using transactional data. The goal is to identify high-value customers, segment behavior, and provide actionable recommendations for retention strategies.  

The analysis leverages **Python (Jupyter Notebook)** for data preparation, exploratory analysis, and clustering, supported by structured input datasets in Excel format.  

## Files in Repository  
- **Customers.xlsx** – Customer master dataset with demographic and profile attributes.  
- **Products.xlsx** – Product catalog with pricing and category information.  
- **Transactions.xlsx** – Historical purchase transactions including quantities, prices, and timestamps.  
- **Shops.xlsx** – Store-level dataset containing information on locations and attributes of sales outlets.  
- **Dictionary.xlsx** – Data dictionary explaining variables across datasets.  
- **retention_analysis.ipynb** – Main analysis notebook containing preprocessing, clustering, and retention modeling.  

## Methodology  
1. **Data Preparation**  
   - Cleaned and joined datasets: Customers, Transactions, Products, Shops, Refunds.  
   - Standardized variables using the provided **Dictionary** file.  

2. **Exploratory Analysis**  
   - Evaluated purchasing behavior and product affinities.  
   - Analyzed shop-level performance and its effect on customer retention.  
   - Calculated customer lifetime value (CLV) proxies.  

3. **Customer Segmentation**  
   - Applied **k-means clustering** to group customers by behavioral patterns.  
   - Overlaid customer value (monetary contribution) with behavior clusters.  

4. **Retention Risk Definition**  
   - Established thresholds for inactivity to flag when customers become “at-risk.”  

5. **Strategic Recommendations**  
   - **Protect Champions:** Ensure high-value customers are nurtured.  
   - **Grow Mid-Tier:** Encourage moderate spenders to increase engagement.  
   - **Win Back At-Risk:** Target personalized offers for those showing churn signals.  
   - **Automate Outreach:** Use rules-based automation for timely interventions.  
   - **Personalize by Cluster:** Tailor strategies per segment for maximum impact.  

## Findings  
- Champions drive a disproportionate share of revenue; retention here is critical.  
- Mid-tier customers show strong potential if engaged effectively.  
- Shop-level analysis revealed regional differences in customer behavior.  
- Behavioral clustering revealed distinct shopping patterns (e.g., frequent small orders vs. occasional high-value orders).  
- Defining clear inactivity thresholds allows for timely interventions before churn.  

## Tools & Libraries  
- **Python:** pandas, numpy, scikit-learn, matplotlib, seaborn  
- **Excel:** Source data preparation  
- **Jupyter Notebook:** Main analysis environment  

## How to Run  
1. Clone the repository:  
   ```bash
   git clone https://github.com/<your-username>/<repo-name>.git

2.	Open retention_analysis.ipynb in Jupyter Lab/Notebook.

3.	Ensure required libraries are installed:
```bash
   pip install pandas numpy scikit-learn matplotlib seaborn

4.	Run the notebook sequentially to reproduce results.



## Kaustubh Pandit 
