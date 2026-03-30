# Environmental Time-Series Analysis: Delhi Climate Trends

This project analyzes multi-year hourly weather data from Delhi to identify temperature, humidity, pressure, wind speed, and seasonal behavioral patterns. After cleaning and structuring the dataset, the analysis explores monthly and seasonal trends, extreme values, and variability to understand how Delhi’s climate shifts across the year.

---

## 📂 Repository Structure
```
delhi-weather-analysis/
├── README.md
├── notebook.ipynb
├── requirements.txt
├── data/
│ └── delhi_weather.csv
└── images/
├── Average Monthly Humidity.png
├── Average Monthly Tempreture.png
├── Tempreture Distribution Percentage.png

```


---

## 📊 Dataset

- Source: Historical hourly weather data (public dataset) **Kaggle**
  https://www.kaggle.com/mahirkukreja/delhi-weather-data?select=testset.csv
- Key fields include: temperature, humidity, pressure, wind speed, visibility, weather descriptions, and timestamps
- Time granularity: Hourly measurements
- Coverage: Multiple seasons across a full year (or more, depending on dataset)

---

## 🎯 Objectives

- Clean and preprocess raw weather data into usable analytical columns  
- Examine daily, monthly, and seasonal temperature trends  
- Analyze humidity, pressure, and wind speed variations  
- Identify patterns such as seasonal extremes, monsoon effects, and winter shifts  
- Visualize overall climate behavior in Delhi across the year  

---

## 🛠 Technologies Used

- Python  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Jupyter Notebook  

---

## 🔍 Key Insights

- Clear seasonal signatures: high summer temperatures, monsoon humidity spikes, and winter drops  
- Pressure levels remain more stable than temperature and humidity across seasons  
- Wind speed patterns show distinct pre- and post-monsoon behavior  
- Monthly aggregation reveals strong contrasts between summer, monsoon, and winter periods  
- Seasonal weather transitions occur sharply rather than gradually  

---

## 📁 Visualizations

Stored in the `images/` folder:

- Average Monthly Humidity
- Average Monthly Tempreture
- Tempreture Distribution Percentage 


---

## ▶️ How to Run

1. **Clone the repository:**

```bash
git clone https://github.com/anisahmed01/delhi-weather-analysis
```

2. **Install dependencies:**
```bash
pip install -r requirements.txt
```

3. **Open the notebook:**
```bash
jupyter notebook notebook.ipynb
```
4. **Run all cells** to reproduce the analysis.

---

## 📘 Project Summary

> This analysis highlights how Delhi's weather behaves across different seasons using structured hourly data. Through trend visualization and statistical summaries, it reveals temperature cycles, humidity variations, pressure stability, and wind speed behavior, giving a clear picture of climatic patterns throughout the year.

