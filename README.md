# ✈️ Airline Passenger Forecasting using Prophet

## 📌 Project Overview

This project uses the classic **Airline Passengers dataset (1949–1960)** to forecast monthly international airline passenger traffic. The dataset exhibits strong growth and clear seasonality, making it ideal for **time series forecasting**.

The goal is to:

* Perform **Exploratory Data Analysis (EDA)** to understand trends and seasonality.
* Build a **forecasting model using Facebook Prophet**.
* Evaluate model accuracy with standard error metrics.
* Forecast passenger demand for the next 5 years.

---

## 📊 Workflow

1. **Data Cleaning & Preparation**

   * Renamed columns to Prophet-compatible format (`ds`, `y`).
   * Checked missing values and converted dates.

2. **Exploratory Data Analysis (EDA)**

   * Visualized passenger trends (1949–1960).
   * Rolling mean (12 months) to highlight long-term growth.
   * Identified seasonal peaks in mid-year months.

3. **Modeling with Prophet**

   * Trained Prophet model with yearly seasonality.
   * Generated forecasts for both test period and future years.
   * Visualized **trend and seasonality decomposition**.

4. **Model Evaluation**

   * Evaluated using:

     * MAE = **30.91**
     * RMSE = **40.22**
     * MAPE = **6.49%**
   * Interpretation: Predictions are accurate within **\~6.5% average error**.

5. **Future Forecast**

   * Forecasted next **5 years of passenger demand**.
   * Model predicts continued growth with seasonal fluctuations.

---

## 📈 Key Insights

* Airline passengers show a **steady upward trend** from 1949–1960.
* Clear **yearly seasonality**: peaks during summer months.
* Prophet model effectively captured both **trend** and **seasonality**.
* Forecast suggests **continued growth in air travel demand**.

---

## 🛠️ Tech Stack

* **Python**
* **Prophet**
* **Pandas, NumPy**
* **Matplotlib, Seaborn**

---

## 📂 Files

* `airline_passengers.csv` → Original dataset.
* `airline_forecasting.ipynb` → Jupyter Notebook with full analysis & model.

Dataset Source: [Airline Passenger Dataset](https://www.kaggle.com/datasets/rakannimer/air-passengers)

---

## 🚀 How to Run

1. Clone the repository:

   ```bash
   git clone https://github.com/YourUsername/airline-passenger-forecasting.git
   cd airline-passenger-forecasting
   ```
2. Install dependencies:

   ```bash
   pip install pandas matplotlib seaborn prophet scikit-learn
   ```
3. Run the notebook in Jupyter/Colab.

---

