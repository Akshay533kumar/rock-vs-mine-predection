Rock vs Mine Prediction

This project is a binary classification model that predicts whether an object detected by sonar signals is a rock or a mine.

📊 Dataset

Used the Sonar dataset (UCI Machine Learning Repository).

Dataset contains 208 rows × 61 columns.

Each row represents sonar signal features with a label:

R → Rock

M → Mine

⚙️ Project Workflow

Data Preprocessing & Exploration

Loaded and analyzed dataset with Pandas & NumPy.

Checked dataset shape, statistics, and class distribution.

Feature & Target Separation

Features: 60 signal values.

Target: Rock/Mine label.

Train-Test Split

90% training, 10% testing.

Stratified sampling to maintain class balance.

Model Training

Implemented Logistic Regression from scikit-learn.

Trained model on sonar features.

Model Evaluation

Training Accuracy: ~83%

Testing Accuracy: ~76%

Prediction System

Takes input values (sonar readings).

Outputs whether the object is a rock or a mine.

🛠️ Tech Stack

Python

Pandas, NumPy

scikit-learn

Jupyter Notebook

🚀 How to Run

Clone the repository:

git clone https://github.com/your-username/rock-vs-mine-prediction.git


Install dependencies:

pip install numpy pandas scikit-learn


Run the notebook:

jupyter notebook rock_vs_mine_prediction.ipynb

📌 Results

Model successfully classifies objects as rock or mine.

Achieved 76% test accuracy.
