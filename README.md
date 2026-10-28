# AI-Based Symptom Diagnosis System

An AI-powered web application that predicts possible diseases based on user-reported symptoms. Built using a machine learning model (XGBoost) and served through a Flask-based interactive interface. The app accepts natural language input and provides predictions, advice, probability charts, and downloadable PDF reports.

---

## 🔍 Features

- Natural language symptom input (e.g., "I have fever and cough")
- AI-driven disease prediction using XGBoost
- Pie chart visualization of top 5 likely diseases
- PDF report generation with diagnosis and medical advice
- Interactive, responsive web interface built with Flask

---

## 🛠 Tech Stack

- **Backend**: Python, Flask, XGBoost, Scikit-learn, Joblib
- **Frontend**: HTML, CSS, JavaScript
- **Libraries**: FPDF, Matplotlib, NumPy

---

## 📁 Folder Structure

AI-Based_Symptom_Diagnosis_System/
├── app.py
├── train_model.py
├── model/
│ └── model.pkl
│ └── symptom_vectorizer.pkl
│ └── disease_encoder.pkl
├── templates/
│ └── index.html
│ └── about.html
│ └── contact.html
│ └── faq.html
├── static/
│ └── piechart.png
│ └── report.pdf
├── utils/
│ └── predictor.py
│ └── pdf_generator.py
│ └── db_utils.py

---

## 🚀 Getting Started

### 1. Clone the repository
```bash
git clone https://github.com/MohammedAdam240604/AI-Based-Symptom-Diagnosis-System.git
cd AI-Based-Symptom-Diagnosis-System
2. Install dependencies
pip install -r requirements.txt
Or manually install:
pip install flask scikit-learn xgboost joblib matplotlib fpdf
3. Run the application
python app.py
4. Open in browser
Visit http://127.0.0.1:5000

🤝 Feedback & Collaboration
Feel free to check it out or share your thoughts.
I welcome feedback and collaboration opportunities to improve this further.

---
