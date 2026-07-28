# Algerian Forest Fire Prediction using Machine Learning

A Machine Learning based web application that predicts the **Fire Weather Index (FWI)** using meteorological and environmental features from the Algerian Forest Fires dataset. The application uses a trained **Ridge Regression** model to estimate the fire weather index based on user-provided weather conditions.

---

## Features

- Predicts Fire Weather Index (FWI)
- Data Cleaning and Preprocessing
- Feature Scaling using StandardScaler
- Ridge Regression Model
- Interactive Flask Web Application
- Real-time Prediction
- User-Friendly Interface

---

## Technologies Used

### Programming Language
- Python

### Machine Learning
- Scikit-learn
- Ridge Regression

### Backend
- Flask

### Frontend
- HTML
- CSS

### Libraries
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Joblib

---

## Project Structure

```
Algerian-Forest-Fire-Prediction/
│
├── .ebextensions/
│   └── python.config
├── templates/
│   ├── home.html
│   └── index.html
├── Algerian_forest_fires_dataset.csv
├── Algerian_forest_fires_cleaned_dataset.csv
├── app.py
├── data cleaning.ipynb
├── model_training.ipynb
├── ridge.pkl
├── scaler.pkl
├── require.txt
└── README.md
```

---

## Workflow

```
Weather Parameters
        │
        ▼
Data Cleaning
        │
        ▼
Feature Scaling
        │
        ▼
Ridge Regression Model
        │
        ▼
FWI Prediction
```

---

## Dataset

The project uses the **Algerian Forest Fires Dataset**, which contains weather observations collected from two regions of Algeria.

### Input Features

- Temperature
- Relative Humidity (RH)
- Wind Speed (Ws)
- Rain
- FFMC
- DMC
- ISI
- Classes
- Region

### Target Variable

- Fire Weather Index (FWI)

---

## Machine Learning Pipeline

1. Load the dataset
2. Data Cleaning
3. Handle Missing Values
4. Feature Selection
5. Feature Scaling
6. Train-Test Split
7. Train Ridge Regression Model
8. Evaluate Model Performance
9. Save Model using Joblib
10. Deploy using Flask

---

## Screenshots

### 1. Home Page

*(Add Home Page Screenshot)*

---

### 2. Prediction Page

*(Add Prediction Result Screenshot)*

---

## Installation

Clone the repository

```bash
git clone https://github.com/HARSHITHA994862/test-for-algeria-forest-fire-.git
```

Move into the project directory

```bash
cd test-for-algeria-forest-fire-
```

Install dependencies

```bash
pip install -r require.txt
```

Run the application

```bash
python app.py
```

Open your browser

http://127.0.0.1:5000

## Future Enhancements

- Improve prediction accuracy using advanced regression models.
- Deploy the application on a cloud platform.
- Add graphical visualization of weather parameters.
- Support batch predictions using CSV file upload.
- Compare multiple machine learning models.

---

## Author

**Mamidi Harshitha**

- B.Tech in Electronics and Communication Engineering
- Minor Degree in Artificial Intelligence and Machine Learning

GitHub: https://github.com/HARSHITHA994862
