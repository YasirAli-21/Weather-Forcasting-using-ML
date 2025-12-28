# 🌦️ SkyCast: Weather Forecasting using Machine Learning

**Leveraging Predictive Analytics and Clustering to Forecast Atmospheric Patterns**

---

## 📚 Table of Contents
- 🌟 [Overview](#overview)
- 📊 [Data Insights & Visualization](#data-insights)
- 🚀 [Getting Started](#getting-started)
- 🛠️ [Tech Stack & Libraries](#tech-stack)
- 🧠 [Model Logic & Clustering](#model-logic)
- ⚙️ [Workflow](#workflow)
- ✨ [Future Enhancements](#future)
- 👨‍💻 [Author](#author)

---

## 🌟 Overview <a name="overview"></a>
Weather patterns are becoming increasingly volatile. **SkyCast** is a Machine Learning project designed to analyze historical climate data and predict future temperature trends. 

- **Predictive Accuracy:** Uses Decision Tree Regression to forecast monthly temperatures.
- **Clustering Intelligence:** Implements K-Means to identify distinct "Temperature Zones" (Cold, Moderate, Warm).
- **Dynamic Visualization:** Interactive plots built with Plotly to track climate changes across decades.
- **Forecasting Power:** Successfully generates forecasted data for upcoming years (e.g., 2018) based on historical patterns.

---

## 📊 Data Insights & Visualization <a name="data-insights"></a>
The project provides deep visual dives into climate history:
* **Timeline Analysis:** Continuous temperature tracking with Range Sliders.
* **Seasonal Trends:** Detailed breakdown of Winter, Summer, Monsoon, and Autumn shifts.
* **Distribution:** Frequency charts and histograms to analyze temperature density.
* **Actual vs Predicted:** Visual comparison plots to validate model reliability.



---

## 🚀 Getting Started <a name="getting-started"></a>
Follow these steps to setup the weather forecasting environment:

### Step 1: Clone the Repository
`git clone https://github.com/YasirAli-21/Weather-Forecasting-ML.git`

### Step 2: Navigate to Directory
`cd Weather-Forecasting-ML`

### Step 3: Setup Virtual Environment
* Create: `python -m venv .venv`
* Activate (Windows): `.\.venv\Scripts\activate`

### Step 4: Install Dependencies
`pip install -r requirements.txt`

---

## 🛠️ Tech Stack & Libraries <a name="tech-stack"></a>
* 🐍 **Python 3.13+** – Core processing.
* 🤖 **Scikit-learn** – DecisionTreeRegressor & KMeans Clustering.
* 📈 **Plotly & Seaborn** – For high-end interactive and static visualizations.
* 🧪 **Pandas & NumPy** – Data manipulation and melting.

---

## 🧠 Model Logic & Clustering <a name="model-logic"></a>



### 🔹 K-Means Clustering
Using the **Elbow Method**, the system identifies the optimal number of climate clusters. It labels data points into 3 categories (Cold, Moderate, Heatwaves) for better pattern recognition.

### 🔹 Decision Tree Regression
The core forecasting is handled by a **Decision Tree Regressor**. 
* **Training Split:** 70% Training / 30% Testing.
* **Feature Engineering:** Uses One-Hot Encoding on 'Month' variables to capture seasonality.
* **Metric:** R2 Score is utilized to evaluate the prediction accuracy.

---

## ⚙️ Workflow <a name="workflow"></a>
1. **Data Melting:** Reshaping monthly data columns into a single timeline.
2. **Preprocessing:** Converting string dates into `datetime` objects.
3. **Exploration:** Seasonal analysis (Winter, Summer, Monsoon, Autumn).
4. **Training:** Fitting the Regressor on historical encoded data.
5. **Prediction:** Generating the "Next Year" forecast.
6. **Logging:** Maintaining a record of historical trends for comparison.

---

## ✨ Future Enhancements <a name="future"></a>
* ⛈️ **Multi-Variable Prediction:** Adding Humidity and Wind Speed to the model.
* 🤖 **Deep Learning:** Implementing LSTMs for time-series forecasting.
* 🌍 **Global Mapping:** Integrating Mapbox for geographical weather heatmaps.
* ⚡ **Real-time API:** Fetching live data from OpenWeatherMap for instant testing.

---

## 👨‍💻 Author <a name="author"></a>
**Yasir Ali** | IT Enthusiast | © 2025 SkyCast

I am passionate about using Data Science to understand environmental changes and building tools that make data meaningful.

[![github](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/YasirAli-21)
[![linkedin](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/yasisahito)