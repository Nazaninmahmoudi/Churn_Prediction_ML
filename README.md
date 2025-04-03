# 📈Churn_Prediction_ML(2025)
## 📌 Project Overview
This project aims to predict customer churn using machine learning models. The dataset contains customer behavior data from a telecom company, with various features such as customer demographics, usage patterns, and subscription details. By applying different classification models, we identify the most effective approach for predicting whether a customer will churn or remain.

## 📊 Dataset
The dataset consists of customer information like tenure, online security, contract type, and payment methods, along with their subscription status (churn or no churn). The data has been preprocessed using techniques such as scaling, encoding, and handling class imbalances to ensure optimal model performance.

## ⚙️ Models Used

We experimented with various classification models and fine-tuned hyperparameters to find the best-performing model:             

🔹 Random Forest Classifier            

🔹 Decision Tree Classifier             

🔹 K-Nearest Neighbors (KNN)            

🔹 XGBoost Classifier           

🔹 LightGBM Classifier                

🔹 Stacked Model (Best Performing Model)               

## 🔮 Churn Prediction 

Using machine learning models like Random Forest, XGBoost, and Stacking, we successfully built a model that predicts whether a customer will churn based on features like account age, subscription type, and usage frequency. The model was trained on historical data and fine-tuned using hyperparameter optimization.                   
The output of the model provides an accurate prediction of churn, helping businesses identify at-risk customers and take proactive steps to retain them.            

## 📈 Key Findings

✅ Customer tenure has a strong negative correlation with churn—longer tenures are associated with lower churn rates.              
✅ Payment method and contract type are critical features in predicting churn behavior.                  
✅ The stacked model provided the best performance, combining the strengths of multiple classifiers to minimize errors and avoid overfitting.             

## 📊 Results & Performance

🎯 Train Score: ~99.75%                             
🎯 Test Score: ~82.28%                   
✅ Minimal Overfitting: While some models showed signs of overfitting (like Random Forest), models such as XGBoost and the stacked model, showed good generalization performance.                      

## 📁Dataset

Kaggle Dataset URL: https://www.kaggle.com/datasets/blastchar/telco-customer-churn  

## 👩‍💻 Author & Contact

📌 Project by: Nazanin Mahmoudy, 2025                              
📧 Email: Nazaninmahmoudy@gmail.com                     
🔗 GitHub: https://github.com/Nazaninmahmoudi                            
🔗 Kaggle: https://www.kaggle.com/nazaninmahmoudy                              
