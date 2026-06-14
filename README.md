# 🔥 Algerian Forest Fire Prediction

## 📌 Project Overview

This project predicts the **Fire Weather Index (FWI)** using Machine Learning techniques and Flask web deployment.

The application takes weather and fire-related parameters from users through a web interface and predicts the FWI value using a trained **Ridge Regression** model.

---

# 🚀 Features

* Machine Learning Regression Model
* Flask Web Application
* User Input Form
* Real-time Prediction
* Model Deployment Ready
* Git & GitHub Integration

---

# 🛠️ Technologies Used

* Python
* Flask
* Scikit-learn
* Ridge Regression
* NumPy
* Pandas
* HTML/CSS
* Bootstrap
* Git & GitHub

---

# 📂 Dataset

The project uses the **Algerian Forest Fire Dataset** containing weather and fire-related attributes collected from two Algerian regions.

---

# 📊 Input Features

The model uses the following features for prediction:

* Temperature
* RH (Relative Humidity)
* Ws (Wind Speed)
* Rain
* FFMC
* DMC
* ISI
* Classes
* Region

---

# 🤖 Machine Learning Model

### Model Used:

* Ridge Regression

### Workflow:

1. Data Cleaning
2. Exploratory Data Analysis (EDA)
3. Feature Engineering
4. Feature Scaling
5. Model Training
6. Model Serialization using Pickle
7. Flask Deployment

---

# 📁 Project Structure

```text id="mjlwm1"
forest-fire-prediction/
│
├── application.py
├── ridge.pkl
├── scaler.pkl
├── requirements.txt
├── Procfile
│
├── templates/
│   └── index.html
│
└── README.md
```

# ⚙️ Installation & Setup

## Clone Repository

```bash id="mjlwm2"
git clone https://github.com/kislay2702/forest-fire-prediction.git
```

## Move to Project Folder

```bash id="mjlwm3"
cd forest-fire-prediction
```

## Install Dependencies

```bash id="mjlwm4"
pip install -r requirements.txt
```

## Run Flask Application

```bash id="mjlwm5"
python application.py
```

---

# 🌐 Application Demo

The web application accepts input parameters and predicts the Fire Weather Index (FWI) value instantly.

---

# 📈 Future Improvements

* Improve frontend UI/UX
* Deploy on AWS
* Add Docker support
* Add CI/CD pipeline
* Add model monitoring

---

# 👨‍💻 Author

### Kislay

Machine Learning & Flask Deployment Project

