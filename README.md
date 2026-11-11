
# 💻 Laptop Price Predictor

A Machine Learning web application that predicts the estimated price of a laptop based on its hardware specifications and features.

The application uses a pre-trained machine learning pipeline and an interactive Streamlit interface to generate price predictions.

## 🚀 Project Overview

Laptop prices depend on several factors, including brand, processor, RAM, storage, graphics card, display resolution and operating system.

This project uses machine learning to estimate laptop prices based on these specifications.

Users can select laptop configurations through a simple web interface and receive an estimated price.

## ✨ Features

- Predict laptop prices using machine learning.
- Interactive web application built with Streamlit.
- Multiple laptop brands and configurations.
- RAM, HDD and SSD selection.
- CPU and GPU selection.
- Screen size and resolution inputs.
- Touchscreen and IPS display options.
- Pre-trained model pipeline for price prediction.

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| Python | Programming language |
| Pandas | Data handling and analysis |
| NumPy | Numerical operations |
| Scikit-learn | Machine learning pipeline |
| Streamlit | Web application |
| Jupyter Notebook | Model development and experimentation |
| Pickle | Saving and loading model artifacts |

## 📂 Project Structure

```text
Laptop-price-predictor/
│
├── app.py
├── laptop_price_predictor.ipynb
├── laptop_data.csv
├── pipe.pkl
├── df.pkl
├── requirements.txt
├── setup.sh
├── Procfile
└── README.md
```

## ⚙️ Installation and Setup

### 1. Clone the repository

```bash
git clone https://github.com/ksingh0777/Laptop-price-predictor.git
```

### 2. Navigate to the project directory

```bash
cd Laptop-price-predictor
```

### 3. Create a virtual environment (recommended)

```bash
python -m venv venv
```

Activate it:

**macOS / Linux**
```bash
source venv/bin/activate
```

**Windows**
```bash
venv\Scripts\activate
```

### 4. Install dependencies

```bash
pip install -r requirements.txt
```

### 5. Run the application

```bash
streamlit run app.py
```

The application will open in your browser, usually at:

`http://localhost:8501`

## 🧠 How It Works

1. The user selects laptop specifications.
2. The application collects the selected inputs.
3. Screen resolution and screen size are used to calculate pixel density (PPI).
4. The input features are converted into the format expected by the pre-trained model pipeline.
5. The model generates a price prediction.
6. The predicted value is displayed in the application.

## 📊 Input Features

- Laptop Brand
- Laptop Type
- RAM
- Weight
- Touchscreen
- IPS Display
- Screen Size
- Screen Resolution
- CPU Brand
- HDD Storage
- SSD Storage
- GPU Brand
- Operating System

## 📁 Project Files

- **app.py:** Streamlit application and prediction interface.
- **laptop_price_predictor.ipynb:** Jupyter Notebook for model development and experimentation.
- **laptop_data.csv:** Laptop dataset.
- **pipe.pkl:** Serialized machine learning pipeline.
- **df.pkl:** Saved dataframe used by the application.
- **requirements.txt:** Python dependencies.
- **setup.sh:** Setup script.

## 🎯 Project Objective

The objective is to demonstrate how machine learning can be applied to a real-world regression problem and integrated into an interactive web application.

## 🔮 Future Improvements

- Compare multiple regression algorithms.
- Improve prediction accuracy through hyperparameter tuning.
- Add model evaluation metrics such as MAE, RMSE and R².
- Deploy the application online.
- Improve the user interface and add visual analytics.
- Expand the dataset with more laptop configurations.

## 👨‍💻 Author

**Keeratjot Singh**

GitHub: [@ksingh0777](https://github.com/ksingh0777)

Project Repository: [Laptop Price Predictor](https://github.com/ksingh0777/Laptop-price-predictor)

## 📌 Attribution

This repository is based on the project originally hosted at [dvnr-s/Laptop-price-predictor](https://github.com/dvnr-s/Laptop-price-predictor). Original Git history is retained. Please refer to the original repository and its applicable license for authorship and usage permissions.
