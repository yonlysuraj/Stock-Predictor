# Stock Predictor

This repository contains a machine learning model designed to predict stock prices based on historical data. The project includes data preprocessing, model training using algorithms like **Linear Regression**, and evaluation using metrics such as **Accuracy** and **F1 Score**.

---

## Features

- **Data Preprocessing**: Cleaning and preparing historical stock data.
- **Model Training**: Using algorithms like Linear Regression, Decision Trees, etc.
- **Evaluation**: Metrics such as Accuracy and F1 Score to assess model performance.
- **Future Improvements**:
  - Real-time prediction capabilities.
  - Incorporation of more diverse datasets.

---

## Requirements

To run this project, ensure you have the following Python packages installed:

```bash
pip install -r requirements.txt
```

### Dependencies:
- `numpy`
- `pandas`
- `scikit-learn`
- `tensorflow`
- `matplotlib`
- `seaborn`

---

## Dataset

The project uses a historical stock price dataset: **`all_stocks_5yr.csv`**.  
This dataset contains stock price data of various companies over the past 5 years.

---

## How to Run

Follow these steps to set up and run the project:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yonlysuraj/Stock-Predictor.git
   ```

2. **Navigate to the project directory**:
   ```bash
   cd Stock-Predictor
   ```

3. **Set up a virtual environment**:
   ```bash
   python -m venv .venv
   ```

4. **Activate the virtual environment**:
   - On Windows:
     ```bash
     .\.venv\Scripts\Activate
     ```
   - On macOS/Linux:
     ```bash
     source .venv/bin/activate
     ```

5. **Install dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

6. **Run the Jupyter notebook**:
   ```bash
   jupyter notebook stock-predictor.ipynb
   ```

---

## Future Improvements

- **Real-time Prediction**: Integrate live stock data for real-time predictions.
- **Additional Features**: Add more diverse datasets to improve accuracy.
- **Model Optimization**: Experiment with different machine learning models and fine-tune hyperparameters.

---

## © Suraj Mallick

This project is created and maintained by **Suraj Mallick**.  
All rights reserved. Feel free to explore, contribute, or reach out for collaboration opportunities!

---

Feel free to contribute or modify sections based on your needs!