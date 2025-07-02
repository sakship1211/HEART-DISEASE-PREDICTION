# ❤ Heart Disease Prediction

A machine learning project that predicts whether a person has heart disease based on medical attributes. Built using Python, scikit-learn, pandas, and deployed both as a CLI and interactive Jupyter Notebook app.

---

##  Features

- Data preprocessing and visualization  
- Model training using RandomForestClassifier  
- CLI-based prediction app  
- Interactive prediction in Jupyter Notebook  
- Input validation and one-hot encoding  
- Model and features saved using `joblib`  

---

##  Project Structure

```
heart-disease-predictor/
├── heart.csv               # Dataset
├── model.pkl               # Trained model
├── features.pkl            # Saved feature names
├── Heart_Disease_App.ipynb # Jupyter notebook interface
├── app.py                  # CLI interface
├── model.py                # Training script
├── preprocess.py           # Preprocessing logic
└── README.md               # This file
```

---

##  Setup Instructions

###  Requirements

Install dependencies:

```bash
pip install pandas scikit-learn matplotlib seaborn joblib ipywidgets
```

Enable Jupyter widgets:

```bash
jupyter nbextension enable --py widgetsnbextension
```

---

###  Running the App

####  Jupyter Notebook (Interactive)

1. Launch the notebook:
    ```bash
    jupyter notebook
    ```
2. Open `Heart_Disease_App.ipynb`
3. Run cells, enter patient data, and get prediction interactively.

####  Command-Line Interface (CLI)

1. Train the model:
    ```bash
    python model.py
    ```

2. Run the CLI app:
    ```bash
    python app.py
    ```

---

##  Dataset Info

- **Source**: [Kaggle - Heart Disease UCI](https://www.kaggle.com/datasets)
- Contains attributes like:
  - Age, Sex, Chest Pain Type, Resting BP, Cholesterol, Fasting BS, ECG, Max HR, etc.
- Target column: `HeartDisease` (1 = Disease present, 0 = Not present)

---

##  Technologies Used

- Python 3  
- Scikit-learn  
- Pandas, Seaborn, Matplotlib  
- ipywidgets  
- Jupyter Notebook  
