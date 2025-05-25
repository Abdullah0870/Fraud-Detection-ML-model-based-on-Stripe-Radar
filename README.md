# Fraud-Detection-ML-model-based-on-Stripe-Radar
Stripe Radar provides business with the capability to utilize their ML models that detect fraud, mainly transaction fraud in real time when using Stripe as a payment processor. Stripe has evolved to utiltize over 1000 features to classify a transaction  as fraudulent or not. Stripe's model has evolved significiantly over the years:  Stripe initially used an XGBoost, which then evolved into and XGBoost + DNN(Deep Neural Network) Ensemble from which the XGBoost component was later removed. In this file we attempt to replicate Stripe radar and come up with an ML model that does an accurate job of catching fraud. This code contains multiple models that aim to catch fraud accurately in a quick time.
The following models were used
1. Logistic Regression: Simple, fast and highly interpretable which makes it good for real world application
2. XGBoost: Stripes inital model for Radar. Quick and has high precision, recall and AUC-ROC
3. DNN: Deep Neural Network which was stripes final model. High accuracy scores because it runs many different predictions and keeps learning from its old predictions.
4. XGBoost + DNN Ensemble: Stripes middle model. Combines the 2 best models.
5. KNN: Distance/Proximity based model for variety
