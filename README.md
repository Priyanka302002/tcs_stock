# 🏢 TCS Stock Data Analysis and Prediction

## 🎯 Objective
Analyze historical TCS stock data to:
- 📊 Understand stock behavior.
- 🔍 Identify trends using data visualization and statistical methods.
- 🤖 Predict future stock prices using machine learning models.

---

## 📄 Project Overview
Tata Consultancy Services (TCS) is a leading Indian IT company with a market capitalization exceeding $200 billion. This project involves analyzing TCS stock data to gain insights and build predictive models for stock prices based on historical trends.

---

## 📁 Dataset
The dataset contains the following columns:
1. 🗓️ **Date**: Trading date.
2. 🟢 **Open**: Opening price of the stock.
3. 📈 **High**: Highest price during the day.
4. 📉 **Low**: Lowest price during the day.
5. 🔴 **Close**: Closing price of the stock.
6. 📦 **Volume**: Number of shares traded.
7. 💰 **Dividends**: Dividends paid on the stock.
8. 🔄 **Stock Splits**: Number of stock splits.

**📥 Download Dataset**: [Click here to download the dataset](https://drive.google.com/drive/folders/1rQSDEtgZJpkFs3XeUHDEX94jYSPwhhn4?usp=drive_link)(#)

---

## ⚙️ Tools and Technologies
- 🐍 **Languages**: Python, SQL, Excel
- 🛠️ **Tools**: VS Code, Jupyter Notebook
- 📚 **Libraries**: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, TensorFlow/Keras

---

## 📝 Workflow

### 1. 🔄 **Data Preprocessing**
- Handle missing values.
- Convert the date column to datetime format.
- Scale features for modeling (e.g., MinMaxScaler for price columns).

### 2. 📊 **Exploratory Data Analysis (EDA)**
- Visualize trends in opening, closing, high, and low prices.
- Analyze stock price volatility.
- Perform correlation analysis between features like volume and closing price.

### 3. 🛠️ **Feature Engineering**
- Create new features like moving averages (5-day, 20-day).
- Add technical indicators such as RSI or MACD.

### 4. 📈 **Data Visualization**
- Plot historical trends of stock prices.
- Use candlestick charts for detailed price behavior.
- Visualize volume vs. price correlations.

### 5. 🤖 **Machine Learning Models**
- **Regression Models**:
  - 📐 Linear Regression
  - 🌲 Random Forest Regressor
  - ⏳ LSTM (Long Short-Term Memory) for time-series forecasting
- Evaluate models using metrics like RMSE, MAE, and R².
- Optimize models using hyperparameter tuning.

### 6. 💡 **Insights and Conclusions**
- Summarize stock trends and predictive insights.
- Highlight limitations and potential future work.

---

## 📦 Deliverables
- Preprocessed dataset and cleaning scripts.
- EDA results and visualizations.
- Trained machine learning models.
- Prediction results with evaluation metrics.
- A detailed project report summarizing analysis and findings.

---

## 🔥 Difficulty Level
**Advanced**

---

## 🚀 How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/Priyanka302002/tcs_stock.git
