# customer-churn-prediction

Objective

The objective of this project is to predict customer churn for PowerCo, a utility company, by analyzing customer data and identifying key factors contributing to churn. The predictive model helps PowerCo make informed decisions to improve customer retention.

Dataset

The dataset used for this project is the PowerCo customer churn dataset, which contains customer demographic information, service usage, and contract details. (If the dataset is publicly available, include the link here.)

Tools and Libraries

Programming Language: Python
Libraries:
pandas
numpy
matplotlib
seaborn
scikit-learn
Streamlit (for app deployment)

Project Structure

Data: Contains the dataset used for training and evaluation.
Notebooks: Jupyter notebooks with the analysis and model development process.
Model: Stores the final model files.
App: Streamlit app files for showcasing the model.
README.md: Overview of the project.

Process

Data Cleaning: Handled missing values, outliers, and performed feature engineering on the dataset.
Exploratory Data Analysis (EDA): Analyzed key features and visualized correlations between customer attributes and churn.
Model Building: Built Random Forest Classifier  model and evaluated their performance.
Evaluation: Assessed models using accuracy, precision, recall, and AUC-ROC scores to select the best-performing model.
Deployment: Deployed the best model using Streamlit for real-time predictions.
Results and Visualizations
Key Findings: Customers with shorter contracts and higher usage tend to churn more frequently.
Best Model: The Random Forest classifier model achieved accuracy score of 90%.
Visualizations: Included visualizations such as churn rate by contract type, feature importance plot, and ROC curve for model performance.

Future Work

Model Improvement: Explore additional features and hyperparameter tuning to further improve model accuracy.
Additional Algorithms: Test deep learning models such as neural networks to compare performance.
Feature Expansion: Use more customer behavior data to improve prediction quality.
Instructions
Clone the repository: git clone <repository-link>
Install required libraries: pip install -r requirements.txt
Run the Jupyter notebook for analysis: jupyter notebook
Run the Streamlit app for live prediction: streamlit run app.py

Strategy Advice for PowerCo:

Focus on customers with short-term contracts and high usage for targeted retention strategies.
Implement personalized offers and loyalty programs to reduce churn in high-risk customer segments.
