# Machine Learning Project: Classification, Regression, and Time Series Forecasting

This repository contains a comprehensive Machine Learning project divided into three distinct phases, exploring various predictive modeling techniques ranging from classical statistical methods to advanced Deep Learning architectures.

## Project Overview

The project is structured into three main phases, each tackling a different type of machine learning problem:

1.  **Phase 1: Classification** - Breast Cancer Detection
2.  **Phase 2: Regression** - Life Expectancy Prediction
3.  **Phase 3: Time Series** - Weather Forecasting

## Phase 1: Classification (Breast Cancer Detection)

This phase focuses on the classification task of diagnosing breast cancer.

*   **Goal:** Classify tumors as malignant or benign based on various features.
*   **Models:**
    *   **Base Models:** Implementation of fundamental classification algorithms.
    *   **Advanced Models:** Utilization of more sophisticated techniques to improve accuracy and robustness.
*   **Data:** The models are trained and tested on the `data.csv` dataset.

## Phase 2: Regression (Life Expectancy Prediction)

The second phase shifts focus to regression analysis, aiming to predict life expectancy.

*   **Goal:** Predict the life expectancy of populations based on health, economic, and social factors.
*   **Models:**
    *   **Linear Regression:** A baseline approach to understand linear relationships.
    *   **Gradient Boosting:** An ensemble technique for higher predictive performance.
    *   **MLP (Multi-Layer Perceptron):** A Neural Network approach implemented using **PyTorch**.
*   **Data:** The analysis is performed on the `Life Expectancy Data.csv`.

## Phase 3: Time Series (Weather Forecasting)

The final phase tackles the complexity of time series forecasting for weather data.

*   **Goal:** Forecast future weather conditions based on historical data.
*   **Models:**
    *   **ARIMA:** A classical statistical model for time series analysis.
    *   **Bi-LSTM (Bidirectional Long Short-Term Memory):** A Recurrent Neural Network (RNN) variant capable of capturing long-term dependencies in both forward and backward directions, implemented using **PyTorch** and accelerated with **GPUs**.
    *   **Transformer (Encoder):** An attention-based architecture (Encoder-only) designed to handle sequential data efficiently, implemented using **PyTorch** and accelerated with **GPUs**.
*   **Key Highlights:** This phase specifically leverages the power of **GPUs** for training the Deep Learning models (Bi-LSTM and Transformer).

## Technologies Used

*   **Python:** Primary programming language.
*   **PyTorch:** Deep Learning framework used for MLP (Phase 2), Bi-LSTM, and Transformer (Phase 3).
*   **Scikit-learn:** Used for classical machine learning algorithms and preprocessing.
*   **Pandas & NumPy:** For data manipulation and numerical operations.
*   **Matplotlib:** For data visualization.
*   **Jupyter Notebooks:** For interactive development and documentation.
