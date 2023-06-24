# XAIReduct: Explainable-AI based Heart Disease Classification using Machine Learning appraoch 
This repository contains Explainable AI based heart disease classification using XGBoost technique. This study focuses on dimensionality reduction using explainable artificial intelligence (XAI), without negotiating on accuracy for heart disease classification.

To determine whether a patient has heart disease, we analyze 13 different features within the dataset. The specific combination of features will indicate the likelihood of the disease. This study uses four machine learning models to classify heart diseases, including their explanations. The four models under consideration are Decision Tree, Random Forest, Support Vector Machine, and XGBoost. Out of the four machine learning models deployed for classification, XGBoost presented the best results concerning performance metrics. The XGBoost model, when used for classification using the reduced feature vector having only 9 features, out of the 13 features, preserve the accuracy in comparison to existing proposals. After classification, a total of five explainable models have been used to explain the findings of the XGBoost classifier, namely SHAP, LIME, SHAPASH, PDP, and DALEX.

The proposed work is presented in the following paper: 

Das, S., Sultana, M., Bhattacharya, S. et al. XAI–reduct: accuracy preservation despite dimensionality reduction for heart disease classification using explainable AI. J Supercomput (2023). https://doi.org/10.1007/s11227-023-05356-3
