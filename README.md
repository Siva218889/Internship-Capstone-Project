# ✈️ Airline Passenger Forecasting using Machine Learning

This project focuses on forecasting airline passenger traffic using a **Random Forest Regressor** with time-series feature engineering techniques such as lag variables and rolling statistics.

---

## 📌 Project Overview

Accurate passenger forecasting is essential for airline planning and resource management.
In this project, we:

* Transform time-series data into supervised learning format
* Engineer features like lag values and rolling averages
* Train a Random Forest model
* Evaluate performance using regression metrics
* Forecast future passenger counts

---

## 📊 Dataset

* Dataset: Airline Passenger Time Series
* Features:

  * `Month` (Date)
  * `Passengers` (Number of passengers)

---

## ⚙️ Features Engineering

The following features were created to improve model performance:

* **Lag Features**

  * `lag1`, `lag2`, `lag3`
* **Rolling Statistics**

  * `rolling_mean_3`
  * `rolling_mean_6`
* **Time Feature**

  * `month`

---

## 🤖 Model Used

* **Random Forest Regressor** (from sklearn)

Why Random Forest?

* Handles non-linear relationships
* Robust to noise
* Works well with engineered features

---

## 🧪 Model Evaluation

The model performance is evaluated using:

* Mean Squared Error (MSE)
* Root Mean Squared Error (RMSE)
* Mean Absolute Error (MAE)

---

## 📈 Results Visualization

* Actual vs Predicted values plotted using Matplotlib
* Pairplot visualization using Seaborn for feature relationships

---

## 🔮 Future Forecasting

The model is used to predict passenger counts for the next **12 months** using iterative forecasting.

---

## 📁 Output

* Final predictions are saved as:

```
final_output.csv
```

---

## 🛠️ Tech Stack

* Python 🐍
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

---

## ▶️ How to Run

1. Clone the repository:

```bash
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
```

2. Install dependencies:

```bash
pip install -r requirements.txt
```

3. Run the notebook:

```bash
jupyter notebook
```

---

## 📌 Project Structure

```
├── airline_passengers.csv
├── notebook.ipynb
├── final_output.csv
├── README.md
└── requirements.txt
```

---

## 🚀 Future Improvements

* Try advanced models like:

  * XGBoost / LightGBM
  * LSTM (Deep Learning)
* Hyperparameter tuning
* Cross-validation for time series
* Deployment as a web app

---

## 🤝 Contributing

Feel free to fork this repo and submit pull requests.

---

## 📜 License

This project is open-source and available under the MIT License.

---

## 👤 Author

Siva Bhaskar Kora
GitHub: https://github.com/Siva218889
