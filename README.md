# Credit-card-fraud-detection-and-risk-Analysis
Credit Card Fraud Detection & Risk Analysis

A Data Analytics + Machine Learning project focused on analyzing credit card transactions to identify fraud patterns and assess transaction risk.

-Analyzed 10,908 credit card transactions
-Identified 101 fraudulent transactions with an overall fraud rate of 0.93%
-Performed data cleaning, validation, and exploratory data analysis using Python
-Analyzed fraud patterns across transaction channels, merchant categories, age groups, customer segments, devices, authentication methods, and time
-Identified higher fraud activity in shopping_net, POS transactions, and late-night hours
-Built a Random Forest classification model for fraud prediction
-Evaluated the model using Accuracy, Precision, Recall, and ROC-AUC
-Model achieved 99.54% Accuracy, 92% Precision, 55% Recall, and 98.60% ROC-AUC
-Classified transactions into Low, Medium, and High Risk based on predicted fraud probability
-Created interactive Tableau dashboards to communicate analytical and ML findings
=Developed dashboards covering fraud overview, fraud patterns, and ML-based fraud risk
-Added business recommendations based on the observed fraud patterns
-The project highlights the importance of Recall and Precision in fraud detection rather than relying only on accuracy

Tools-Python,Pandas,NumPy,Scikit-learn,Tableau,Excel

Project Flow
Data Cleaning - EDA - Fraud Pattern Analysis - Machine Learning - Risk Classification - Tableau Dashboards - Recommendations

Objective
To understand where, when, and under which conditions fraud is more likely to occur, while using Machine Learning to help identify potentially risky transactions.

After the working on this project,
My Insights

Overall fraud rate was 0.93%, with 101 fraudulent transactions out of 10,908.
Shopping_net recorded the highest fraud rate among merchant categories at approximately 2.92%.
The 18–25 age group had the highest fraud rate at approximately 3.08%.
Fraud rates were highest during late-night hours, particularly around 22:00–23:00.
POS transactions had the highest fraud rate among device types at approximately 1.25%.
Platinum customers recorded the highest fraud rate among customer segments at approximately 1.30%.
PIN authentication had the highest fraud rate among authentication methods at approximately 1.07%.
Saturday had the highest fraud rate among the days of the week at approximately 1.49%.

Recommendations and Suggestions for improvement

Increase monitoring of late-night transactions, especially between 22:00 and 23:00.
Apply additional verification to online shopping transactions, particularly shopping_net transactions.
Strengthen monitoring of POS and ATM transactions.
Introduce additional verification for transactions with unusual amounts or transaction patterns.
Encourage stronger authentication methods for transactions showing suspicious characteristics.
Pay closer attention to unusual transaction activity within high-risk merchant categories.
Monitor transaction patterns across different customer segments to identify unusual behavior.
Use day and time-based monitoring to identify unusual transaction activity during periods with higher observed fraud rates.
Regularly review fraud patterns because transaction behavior and fraud trends can change over time

Dashboard links
Dashboard 1- credit card fraud overview dashboard-https://public.tableau.com/views/CreditcardFraudOverviewDashboard/Dashboard1?:language=en-GB&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link
Dashboard 2- Credit card fraud pattern dashboard-https://public.tableau.com/views/CreditcardFraudPatternAnalysis/Dashboard2?:language=en-GB&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link
Dashboard 3- Ml fraud risk analysis dashboard-https://public.tableau.com/views/MLFraudRiskAnalysis/Dashboard3?:language=en-GB&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link
NOTE - PLEASE AFTER OPENING THE DASHBOARD LINK ,VIEW THE DASHBOARD IN FULL SCREEN FOR BETTER VIEW(FULL SCREEN ICON WILL BE ON THE BOTTOM RIGHT OF THE SCREEN AFTER CLICKING THE LINK) 
