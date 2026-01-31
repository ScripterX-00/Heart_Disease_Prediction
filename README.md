# 🫀 Heart Disease Prediction Web Application



---

## 🧠 Overview

**Heart Disease Prediction Web App** combines Machine Learning with a user-friendly web interface to provide fast and accurate heart disease risk prediction.

The app allows users to:
- Enter medical details such as age, cholesterol level, blood pressure, etc.
- Predict heart disease using trained ML models.
- View results instantly on the web interface.   
- Use a responsive and simple UI. 


---

## 🧩 Key Features

- 💬 **ML-Based Prediction** – Predicts diabetes using trained Machine Learning models.
- 📊 **User Input Form** – Enter patient health parameters
- ⚡ **Instant Result** – Shows prediction result in real-time


---

## 🛠️ Tech Stack

| Layer | Technology |
|-------|-------------|
| **Frontend** | HTML, CSS, JavaScript,  |
| **Backend** | Flask |
| **Python Frameworks** | NumPy, Pandas, Matplotlib / Seaborn, Scikit-learn |
| **Dataset** | PIMA Indians Diabetes Dataset (Kaggle / UCI) |
| **Deployment** | Render / Railway / Localhost |


---

## 📁 Folder Structure

```
Diabetes_Prediction/
│               
├── ipynb_checkpoints/               
│   ├── Heart Disease Prediction-checkpoint.ipynb
├── static/
    ├── css/
    ├── fonts/
    ├── image/
    ├── js/
    ├── result/
    ├── vendor/    
    ├── pima_Nulls.ipynb
├── templates
├── app.py             
├── hdp_model.pkl 
├── Heart Disease Prediction 
├── Heart GIF 
├── heart.csv 
├── README.md             # Project documentation
└── LICENSE               # License (MIT recommended)
```

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the Repository
```bash
git https://github.com/ScripterX-00/Heart_Disease_Prediction.git
cd Heart_Disease_Prediction
```

### 2️⃣ Create a Virtual Environment
```bash
python -m venv venv
venv\Scripts\activate       # For Windows
# OR
source venv/bin/activate    # For macOS/Linux
```

### 3️⃣ Install Dependencies
```bash
pip install -r requirements.txt
```

### 5️⃣ Run the Application
```bash
python app.py
```

Now visit 👉 http://127.0.0.1:5000 in your browser.

---

## 🌐 Deployment

You can easily deploy this Flask app using:

### 🔹 Railway (Recommended for Simplicity)
1. Push your repo to GitHub.  
2. Create a new Railway project.  
3. Connect your GitHub repository.    
4. Deploy — it auto-detects Flask apps!

### 🔹 Render
1. Create a new web service.  
2. Connect your repo.  
3. Set build command:
   ```bash
   pip install -r requirements.txt
   ```
4. Set start command:
   ```bash
   gunicorn app:app
   ```

---

## 📊 Dataset

The dataset contains medical attributes such a

- Age
- Sex
- Chest Pain Type
- Resting Blood Pressure
- Cholesterol
- Fasting Blood Sugar
- Maximum Heart Rate
- Exercise Induced Angina
- Oldpeak
- ST Slope

Source: Kaggle – UCI Heart Disease Dataset

## 🤖 Machine Learning Algorithms

Join our growing community of herbal enthusiasts and developers!

- Logistic Regression
- K-Nearest Neighbors (KNN)
- Support Vector Machine (SVM)
- Naive Bayes
- Decision Tree
- Random Forest


---

## 📈 Results


- Model Accuracy: 76.92%
- Best Performing Model: Logistic Regression


## 🧪 Testing

Manual testing:

- Enter sample patient data
- Click Predict
- View result
- Verify prediction accuracy
```

## 🤝 Contributing

We welcome contributions from the open-source community!

1. Fork the repository  
2. Create your feature branch  
   ```bash
   git checkout -b feature/YourFeature
   ```
3. Commit your changes  
   ```bash
   git commit -m "Add new feature"
   ```
4. Push and submit a Pull Request  

Please make sure to include clear commit messages and test your feature before PR submission.

---

## 👨‍💻 Author

**Developed by:** Dibyajyoti Jana  
---


