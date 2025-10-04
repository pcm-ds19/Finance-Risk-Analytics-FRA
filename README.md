#  Finance & Risk Analytics (FRA)

##  Overview
This project covers two major parts of financial analytics:

### Part A – Credit Default Prediction
- **Goal:** Predict whether a company will default on its debt using financial indicators.  
- **Dataset:** 4,256 companies × 58 financial features.  
- **Techniques:** EDA, outlier handling, encoding, scaling, VIF, ROC Curve, and hyperparameter tuning.  
- **Models:** Logistic Regression, Random Forest.  
- **Final Model:** Tuned Random Forest Classifier → AUC = 99.9%, strong precision and recall.  
- **Insights:** Key predictors were Net Worth Next Year, TOL/TNW, and Profitability Ratios.  
- **Outcome:** Enables banks and credit agencies to automate creditworthiness assessment and minimize loan defaults.

### Part B – Market Risk Analysis (Stock Portfolio)
- **Goal:** Evaluate risk and return for a 5-stock Indian portfolio (2016–2023).  
- **Metrics:** Log Returns, Volatility, Mean & Standard Deviation.  
- **Visuals:** Risk-Return Scatterplots and Price Trends.  
- **Findings:** Cipla, HUL, Infosys offered high risk-adjusted returns; Dish TV and Vodafone Idea had high risk and low returns.  
- **Recommendation:** Balanced allocation (60% HUL, 30% Cipla, 10% Infosys) for low-risk portfolios.

##  Key Learnings
Integrated supervised ML (classification) with financial time-series risk analysis, strengthening expertise in credit risk modeling and portfolio optimization.

##  Tools & Techniques
Python, Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, ROC Curve, VIF, Random Forest, Statistical Risk Metrics.

##  Repository Structure
FRA_Project/
├── FRA_Project_Part_A.ipynb   # Credit Default Prediction
├── FRA_Project_Part_B.ipynb   # Market Risk Analysis
└── FRA_Project_Report.pdf     # Final Business Report
  


##  Business Impact
Data-driven framework to:
- Predict default risk accurately.  
- Optimize stock portfolios for better risk-adjusted returns.  
- Support FinTech innovation in credit scoring and investment advisory.


Priyanka Chandrahar Mane  
PGP-DSBA | Great Lakes Institute of Management & The University of Texas at Austin (McCombs)


