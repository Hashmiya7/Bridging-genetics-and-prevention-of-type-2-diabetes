# 🩺 Diabetes Prediction System

## 📌 Overview
This project is a **Diabetes Prediction System** that uses machine learning to predict whether a person is diabetic based on medical input parameters.  

It includes:
- 📊 A predictive model (ML-based)
- 🌐 A modern frontend UI (React + Vite)
- 🔗 Integration between frontend and backend

---

## 🎯 Features
- Predict diabetes based on user input
- Clean and interactive UI
- Fast and responsive frontend using React
- Scalable architecture (Frontend + Backend separation)

---

## 🛠️ Tech Stack

### Frontend
- React.js
- Vite
- JavaScript / TypeScript
- HTML, CSS

### Backend (assumed)
- Python (Flask / FastAPI)
- Machine Learning model (Scikit-learn / similar)

---

## Project Structure
snp mini/
└── Diabetes_project/
    ├── Frontend/
    │   ├── public/                # Static files
    │   ├── src/                   # Main source code
    │   │   ├── assets/            # Images, icons, styles
    │   │   ├── components/        # Reusable UI components
    │   │   ├── pages/             # Page-level components (forms, results)
    │   │   ├── App.jsx            # Main React component
    │   │   ├── main.jsx           # Entry point
    │   │   └── styles.css         # Styling
    │   ├── index.html             # Root HTML file
    │   ├── package.json           # Dependencies & scripts
    │   ├── package-lock.json      # Dependency lock file
    │   └── vite.config.js         # Vite configuration
    │
    ├── Backend/ (if present)
    │   ├── app.py                 # Main backend server
    │   ├── model.pkl              # Trained ML model
    │   ├── requirements.txt       # Python dependencies
    │   └── utils.py               # Helper functions
    │
    ├── data/ (optional)           # Dataset used for training
    ├── notebooks/ (optional)      # Jupyter notebooks for model building
    ├── README.md                  # Project documentation
    └── .gitignore                 # Ignored files


---

## 🚀 How to Run the Project

### 🔹 Step 1: Clone the repository
```bash
git clone <your-repo-link>
cd Diabetes_project

cd Backend
pip install -r requirements.txt
python app.py
