📂 Medical Insurance Cost Prediction
📋 Project Overview
This project aims to predict individual medical insurance costs based on several health and demographic factors. By leveraging Linear Regression, the model analyzes features like age, BMI, and smoking status to estimate the annual charges billed by health insurance.

📊 Dataset Description
The dataset includes 1,338 records with the following features:

Age: Age of primary beneficiary.

Sex: Insurance contractor gender (female, male).

BMI: Body Mass Index, providing an understanding of body weights that are relatively high or low relative to height.

Children: Number of children covered by health insurance / Number of dependents.

Smoker: Smoking status (yes, no).

Region: The beneficiary's residential area in the US.

Charges (Target): Individual medical costs billed by health insurance.

🛠️ Key Steps Involved
Exploratory Data Analysis (EDA): Visualizing distributions and correlations using Seaborn and Matplotlib.

Data Preprocessing: Handling categorical variables using encoding techniques.

Model Development: Building a Linear Regression model using Scikit-Learn.

Evaluation: Assessing the model using R-squared (R²) and Mean Absolute Error (MAE).

📈 Results
The model successfully predicts insurance costs with promising accuracy.

R-squared Score: 78.36%

Key Insight: Smoking status was found to be the most significant factor influencing insurance costs.
