

# 🩺 Sonar Rock vs Mine Prediction Using Logistic Regression







A machine learning project to classify sonar signals as Rock (R) or Mine (M) using Logistic Regression.The model is trained on sonar signal datasets, with preprocessing, evaluation, and visualization of performance metrics.



---







## 🚀 Features









📊 Exploratory Data Analysis (EDA): Shape, summary statistics, distribution of classes

🧮 Preprocessing: Splitting features & labels, stratified train-test split

🤖 Model Training: Logistic Regression for classification

📈 Evaluation Metrics: Accuracy, Confusion Matrix, Classification Report

🧪 Prediction on New Samples: Input reshaping and real-time classification

🔎 Visualization: Heatmap of confusion matrix, bar plots, feature importance

📂 Testing on New Dataset (sonarTest.csv) with re-evaluation





---







## 🧠 Machine Learning







- **Machine Learning Workflow:**  

Import libraries (Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn)

Load Sonar dataset (sonar data.csv)

Explore dataset (shape, summary, value counts, group by mean)

Split dataset into training & testing sets (90% / 10%)

Train Logistic Regression model

Evaluate performance (train/test accuracy, confusion matrix)

Test predictions on new input samples

Load additional dataset (sonarTest.csv), preprocess, and evaluate

Generate styled HTML classification report

Analyze Logistic Regression feature weights (coefficients)



---







## 🛠️ Tech Stack







| Layer       | Technology       |



|-------------|------------------|



| Language    | Python 3.12 |



| Framework   | Scikit-learn |



| Dataset     | Sonar Dataset |



| Tools       | NumPy, Pandas, Matplotlib, Seaborn |







---







## 📁 Project Structure







```text



├── sonar data.csv              ← Main dataset
├── sonarTest.csv               ← Additional dataset
├── Sonar Rock vs Mine.ipynb    ← Jupyter Notebook (main workflow)
├── outputs/                    ← Graphs & plots (optional)
└── README.md                   ← Project documentation


