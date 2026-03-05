# PA-3-Banking
Banking assignment in Python 
Bank Marketing Classification Project
	Project Overview
		This project applies several classification models to predict whether a customer will subscribe to a bank term deposit based on data from previous marketing campaigns conducted by a Portuguese banking institution. The goal is to compare the performance of multiple machine learning algorithms and determine which model best predicts customer responses.
The dataset comes from the UCI Machine Learning Repository and includes demographic information, previous marketing interactions, and economic indicators.
	Business Objective
		The objective of this analysis is to build predictive models that help the bank identify customers who are most likely to subscribe to a term deposit during a telemarketing campaign. By identifying these customers, the bank can improve marketing efficiency, reduce unnecessary calls, and allocate marketing resources more effectively.
	Models Evaluated
The following classification models were implemented and compared:
•	Logistic Regression
•	K-Nearest Neighbors (KNN)
•	Decision Tree
•	Support Vector Machine (SVM)
Each model was trained using default parameters and evaluated based on:
•	Training Time
•	Training Accuracy
•	Test Accuracy
Hyperparameter tuning using GridSearchCV was also explored to improve model performance.
Key Findings
•	Logistic Regression and SVM provided strong and stable predictive performance.
•	Decision Trees achieved very high training accuracy but showed signs of overfitting.
•	KNN performed well but required more computational resources as the dataset grows.
•	Because the dataset is imbalanced (many more "no" responses than "yes"), additional evaluation metrics such as precision, recall, and F1-score are important when assessing model effectiveness.
Technologies Used
•	Python
•	Pandas
•	NumPy
•	Scikit-learn
•	Seaborn
•	Matplotlib
•	Jupyter Notebook
Project Structure
.
├── bank_marketing_analysis.ipynb   # Main analysis notebook
├── bank-additional-full.csv        # Dataset
├── bank-additional.csv             # Sample dataset
├── bank-additional-names.txt       # Data description
├── CRISP-DM-BANK.pdf               # Research paper describing dataset
└── README.md                       # Project summary
Notebook
The full analysis and modeling workflow can be found in the Jupyter Notebook:
bank_marketing_analysis.ipynb
The notebook includes:
•	Data exploration
•	Data preprocessing
•	Feature encoding
•	Model training
•	Model comparison
•	Model improvement through hyperparameter tuning
•	Interpretation of results and recommendations
Next Steps
Future improvements could include:
•	Additional hyperparameter tuning
•	Exploring ensemble models such as Random Forest or Gradient Boosting
•	Handling class imbalance using resampling techniques
•	Deploying the best-performing model for real-time marketing decision support
