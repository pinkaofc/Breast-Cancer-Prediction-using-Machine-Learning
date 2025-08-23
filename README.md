🩺 Breast Cancer Prediction using Machine Learning
📌 Overview

This project predicts whether a breast tumor is benign or malignant using the Breast Cancer Wisconsin (Diagnostic) Dataset.
It applies Machine Learning models for classification and provides a Flask web app for real-time predictions through a simple user interface.

🚀 Features

Data preprocessing and visualization (EDA).

Model training with Scikit-learn (Logistic Regression, Random Forest, etc.).

Model evaluation (accuracy, precision, recall, F1-score).

Flask web application for user-friendly predictions.

Ready to deploy on Heroku / Render / AWS.

📊 Dataset

The dataset used:

UCI Breast Cancer Wisconsin Dataset

Or Kaggle version: Breast Cancer Dataset

🛠️ Tech Stack

Python

Flask (web framework)

Pandas, NumPy (data handling)

Scikit-learn (ML models)

Matplotlib, Seaborn (visualization)

HTML, CSS (Jinja2) for frontend

⚙️ Installation & Usage

Clone this repository

git clone https://github.com/pinkaofc/Breast-Cancer-Prediction-using-ML.git
cd Breast-Cancer-Prediction-using-ML


Create & activate a virtual environment

python -m venv venv
venv\Scripts\activate   # On Windows
source venv/bin/activate   # On Mac/Linux


Install dependencies

pip install -r requirements.txt


Run the Flask app

python app.py


Open in browser

http://127.0.0.1:5000/

📈 Results

Achieved 95–97% accuracy depending on the model.

Logistic Regression and Random Forest performed best.

🌍 Deployment

This project can be deployed on:

Heroku

Render

AWS / Azure / GCP

🤝 Contributing

Contributions are welcome! Please open an issue or submit a pull request.

📜 License

This project is licensed under the MIT License.
