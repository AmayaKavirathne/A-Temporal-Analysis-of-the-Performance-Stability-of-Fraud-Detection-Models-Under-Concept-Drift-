# A-Temporal-Analysis-of-the-Performance-Stability-of-Fraud-Detection-Models-Under-Concept-Drift-
## Abstract 
Fraud detection algorithms are commonly used in modern financial systems to spot fraudulent 
transactions and reduce financial loss. Nevertheless, these models are usually assessed using 
static approaches that do not account for the dynamic structure of transaction data, where fraud 
trends and user behavior change over time. When models are used in real-world situations, this 
restriction may cause performance reduction. 
This study assesses the effectiveness of retraining techniques in sustaining performance over 
time and looks into the temporal stability of fraud detection models under concept drift. A 
temporal evaluation framework was created using the IEEE-CIS fraud detection dataset. To 
replicate realistic deployment conditions, transactions were arranged chronologically and 
divided into multiple times frames. XGBoost, Random Forest, and Logistic Regression were 
used in a few experiments, such as retraining experiments, temporal model evaluation, and 
exploratory data analysis (EDA). 
The findings provide clear evidence of concept drift by showing that model performance 
continually declines when applied to future data. Random Forest demonstrated more steady 
behavior, while XGBoost demonstrated the highest predictive performance but the largest risk 
to temporal variations. Logistic Regression served as a baseline with consistently low 
performance. Retraining strategies significantly improved performance, with fixed retraining 
at shorter intervals achieving the best results, and performance-triggered retraining offering a 
more efficient balance between performance and computational cost. 
Overall, this study highlights the limitations of static evaluation and emphasizes the importance 
of temporal evaluation and adaptive retraining in maintaining robust fraud detection systems.
