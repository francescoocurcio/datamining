# Heart Disease Prediction Project
🧑🏼‍🏫 This project focuses on predicting the likelihood of heart disease using machine learning techniques. The dataset originates from the CDC's Behavioral Risk Factor Surveillance System (BRFSS), a large-scale survey on the health conditions of U.S. residents.

💻 What has been made:

1. **Dataset Origin**<br>
The dataset used in this project comes from Kaggle, originally sourced from the CDC's **BRFSS**. The **BRFSS** conducts annual phone surveys across all 50 U.S. states to collect health-related data. This dataset contains crucial indicators of heart disease such as high blood pressure, high cholesterol, diabetes, and lifestyle factors like smoking and physical activity. Here the direct **link** for the dataset: https://www.kaggle.com/datasets/kamilpytlak/personal-key-indicators-of-heart-disease

3. **Pre-analysis Phase**<br>
This phase involves an initial exploration of the dataset. Key aspects of this phase include a **dataset overview**, providing insights into the structure of the data, including the variables and their types. **Missing data analysis** is performed to identify any gaps or inconsistencies in the dataset. A **statistical summary** gives an overview of the distribution of key features like age, BMI, and health conditions. Additionally, a **correlation analysis** is conducted to assess the relationships between important features and the target variable (heart disease).
  
4. **Pre-processing Phase**<br>
In this phase, several data cleaning and transformation steps are carried out. **Handling missing data** is the first step, where any missing values are addressed. Next, **data normalization** is applied to features like BMI and age, ensuring they are within comparable ranges. Through **feature engineering**, new variables are derived from the existing data to enhance model performance. Lastly, **encoding categorical variables** transforms non-numeric data (e.g., "Yes/No" responses) into numerical formats using techniques like One-Hot Encoding.

5. **Classification Phase** (*Imbalanced Data*)<br>
In this phase, the dataset, which is **imbalanced** (with a disproportionate number of cases with and without heart disease), is used to train several machine learning models. These models include **Logistic Regression**, **Decision Tree Classifier**, and **Random Forest Classifier**.

6. **Classification Phase** (*Balanced Data*)<br>
To address the imbalance in the dataset, techniques such as **oversampling** or **undersampling** are applied, resulting in a more **balanced dataset**. The models are then retrained on this modified dataset, improving the predictive accuracy for both heart disease and non-heart disease cases.
