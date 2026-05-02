# From-Compute-to-Capability-Predicting-AI-Model-Performance
The rapid growth of artificial intelligence has led to increasingly complex models requiring significant computational resources. While larger models often promise higher accuracy, they also introduce challenges. This project explore the relationships between model performance, training cost, infrastructure usage, and inference efficiency. 

**🚀 Project Overview**

The goal of this project is to:

•	Analyze trends in AI model training from 2018–2025

•	Understand how factors like cost, compute power, and model size affect performance

•	Build a regression model to predict model accuracy

•	Optimize the model using hyperparameter tuning (Optuna)


**📈This project helps answer several critical industry questions:**

Q1. Are larger AI models worth the cost?
Answer: Not always. Performance gains flatten as cost increases, making large models less cost-efficient.

Q2. What drives AI training cost the most?
Answer: Infrastructure factors such as power consumption, GPU usage, and model size—not accuracy.

Q3. Does better hardware guarantee better performance?
Answer: No. The dataset shows minimal differences across GPU types, emphasizing algorithmic efficiency.

Q4. How important is latency in production AI systems?
Answer: Very important. A few high-latency models can significantly degrade user experience.

Q5. Is AI scaling sustainable?
Answer: Current trends suggest challenges due to high energy consumption and carbon emissions.

Q6. What should organizations optimize for?
Answer: Efficiency—not just accuracy: cost per performance, energy usage and latency

**🤖 Machine Learning Model**

Model Used: XGBoost Regressor (XGBRegressor)

Pipeline:
Feature selection,
Train-test split,
Model training,
Evaluation using:
Mean Squared Error (MSE),
R² Score

Library used: Optuna (Hyperparameter Tuning)

This project demonstrates that scaling AI models is not always the most effective strategy. While larger models can achieve higher performance, the associated costs, latency, and environmental impact often outweigh the benefits.

#Python #Pandas #NumPy #Matplotlib #Seaborn #Scikit-learn #XGBoost #Optuna
