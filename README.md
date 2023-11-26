Project: Machine learning project for forecasting Christmas seasonal sales in a textile industry

Objective: To forecast daily sales, by factory and by product throughout the month of December.

Some technical details:

- Use of PyCaret and Pandas libraries;
- Implementation of a machine learning model with a supervised approach;
- Adoption of a multivariate regression model;
- Exploration of methods, with a main focus on Ensemble Decision Trees and Gradient Boosting;
- Evaluation of models, mainly LightGBM, XGBoost, Random Forest (RF), Gradient Boosting Regressor (GBR), and Extra Trees (ET).

Database:

- Total records: 33,044
- Columns: data (datetime); ID_fabrica (int64); ID_prod (int64); vendas (int64)
- Categorical (or qualitative) variables: ID_fabrica, ID_prod
- Numerical (quantitative) variables: vendas
