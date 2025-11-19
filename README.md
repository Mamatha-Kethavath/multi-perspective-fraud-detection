# multi-perspective-fraud-detection

💻 E-Commerce Fraud Detection Using Machine Learning and Process Mining
📜 Abstract
With the rise of e-commerce platforms, fraudulent transactions have also surged. Traditional detection methods often lack dynamic and contextual awareness, making them ineffective against modern fraud schemes. This project introduces an innovative fraud detection system that integrates machine learning (SVM, Decision Trees, etc.) with process mining techniques to detect and prevent fraud in real time. Our system provides multi-perspective analysis by monitoring user behavior and analyzing deviations from normal workflows.

🧠 Technologies Used
Frontend: HTML, CSS, JavaScript

Backend: Python (Django ORM)

Database: MySQL (WAMP Server)

ML Algorithms: SVM, KNN, Random Forest, Naïve Bayes, Logistic Regression, Decision Tree (with Gradient Boosting)

📁 Modules Overview
🛠️ 1. Service Provider
Login/Register

Train & Test ML models

View accuracy charts and prediction reports

Manage remote user activities

👥 2. Remote User
Register/Login

Upload data for fraud detection

View fraud prediction results and profile info

🔐 3. Admin
Authorize users

Monitor system performance and fraud status

🕸️ System Architecture
pgsql
Copy
Edit
Web Server
├── Remote Users
│   └── Submit Transaction Data
│
├── Service Provider
│   ├── Train/Test Datasets
│   ├── Predict Fraud Status
│   └── View Results
│
└── Web Database
(You can include architecture.png here)

📊 Algorithms Used
✅ Decision Tree (with Gradient Boosting)
Tree-based decisions

Gradient Boosting enhances accuracy

✅ K-Nearest Neighbors (KNN)
Classifies based on data similarity

Simple yet powerful

✅ Logistic Regression
Ideal for binary classification

Works well with both numeric and categorical data

✅ Naïve Bayes
Probabilistic model

Assumes feature independence

✅ Random Forest
Ensemble of decision trees

Reduces overfitting and increases accuracy

✅ Support Vector Machine (SVM)
Classifier with optimal separating hyperplane

Efficient for high-dimensional data

🔎 Features
Real-time fraud detection

Conformance checking via process mining

Graph-based fraud behavior modeling (DIGIN Framework)

Visual dashboards (Bar Charts, Fraud Ratios)

Admin authorization & session management

Multiple ML models for comparative performance

🧪 Testing Strategy
Unit Testing: For each module individually

Integration Testing: Top-down and bottom-up methods

User Acceptance Testing: Feedback from prospective users

Validation Testing: Input checks (text/numeric fields)

Output Testing: Validates required output formats

📈 Results
The proposed model combining control-flow and data-flow features achieved:

Precision: 0.946

Recall: 0.852

F1-score: 0.895

AUC: 0.935

Clearly, a multi-perspective detection system performs significantly better than traditional single-view approaches.

✅ Conclusion
This system presents a hybrid fraud detection method that integrates user behavior analytics and formal modeling through Petri nets. It dynamically captures anomalies and applies machine learning for efficient fraud detection. Future improvements include deep learning integration, richer time-series modeling, and standard fraud behavior libraries.

