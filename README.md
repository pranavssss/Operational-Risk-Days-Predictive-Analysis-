# Predicting High Operational Risk Days Using Machine Learning Techniques
-------------------------------------------------------------------------------------------------------------------------------
# Abstract:

Operational risk can lead to production delays, quality issues, and increased downtime if not identified early. The
goal of this project is to build a machine learning model that can predict high-risk operational days using
historical daily operational data collected across multiple locations.

In this project, the data was first explored to understand patterns, distributions, and class imbalance. Data
preprocessing and transformation steps such as date conversion, categorical encoding, and feature scaling were
applied to make the data suitable for machine learning models. Several meaningful features were engineered to
better represent operational stress, such as rejection rate, downtime per ticket, and tickets per unit..
Multiple classification models were trained, starting with simple baseline models like Logistic Regression and
Linear SVM, followed by more advanced tree-based and non-linear models such as Random Forest and
CatBoost. The models were evaluated using standard metrics including Precision, Recall, F1-score, ROC-AUC,
and confusion matrices.

Finally, model interpretation techniques were used to identify key factors associated with high operational risk.
While the models highlight strong associations, the results are predictive and correlational rather than causal.
Overall, the project demonstrates how machine learning can be used as an early warning system to flag risky
operational days and support proactive decision-making.
-------------------------------------------------------------------------------------------------------------------------------
Keywords: Date Conversion, Categorical Encoding, Feature Scaling, Logistic Regression, Linear SVM, Random
Forest, CatBoost, Correlation.
