# Wafer Fault Detection Using Machine Learning

This project automates the process of detecting faults in silicon wafers based on sensor data using Machine Learning. It helps identify defective wafers during the manufacturing process to improve quality and reduce human intervention.

## 📌 Problem Statement

In semiconductor manufacturing, determining whether a wafer is faulty or not is essential for product quality. This system uses historical sensor data to build a classification model that predicts whether a wafer is "Faulty" or "Good".

## 🧠 Technologies Used

- **Python**
- **Scikit-learn**
- **Pandas, NumPy**
- **Flask (Web App)**
- **Logging & Exception Handling**
- **CI/CD (Coming Soon)**

## 📁 Project Structure

Wafer_Fault_Detection_ML/
├── artifacts/               → Saved models and outputs
├── data/                    → Input data files
├── logs/                    → Log files
├── notebooks/               → EDA and experimentation
├── src/                     → Source code
│   ├── components/          → Data ingestion, transformation, training
│   ├── pipelines/           → Model training and prediction
│   ├── utils/               → Utility functions
│   └── config/              → Configuration files
├── templates/               → HTML templates for Flask
├── app.py                   → Flask application
├── requirements.txt         → Python dependencies
├── setup.py                 → Package setup
└── README.md                → Project documentation



## ⚙️ How to Run Locally
1. **Clone the repository:**

   bash
   git clone https://github.com/githubvishal1234/Wafer_Fault_Detection_ML.git
   cd Wafer_Fault_Detection_ML

  bash
  python -m venv venv
  venv\Scripts\activate   # For Windows

  pip install -r requirements.txt

  python app.py

✅ Features
Sensor data ingestion and validation

Data cleaning and transformation

Model training and fault prediction

Web UI to upload CSV and get predictions

Logging and error handling

📊 Model Evaluation
Confusion Matrix

Accuracy, Precision, Recall

Cross-Validation Score

🚀 Future Enhancements
Streamlit-based UI

Docker containerization

CI/CD pipeline for automated testing and deployment

Integration with cloud storage

📄 License
Licensed under the MIT License

📬 Contact
Kondaparthy Vishal
📧 kondaparthyvishal6@gmail.com
🔗 GitHub Profile
