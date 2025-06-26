# 📊 Exploratory Data Analysis (EDA) on Airquality

Welcome to my EDA project! This project explores and analyzes the **Air Quality ** to uncover patterns, trends, and key insights using Python and data visualization libraries.

---

## 📁 Project Structure

```
├── data/               # Raw and cleaned datasets
├── notebooks/          # Jupyter notebooks for EDA
├── images/             # Visualizations and charts
├── README.md           # Project overview
└── requirements.txt    # List of Python libraries
```

---

## 🧠 Objective

- Load, inspect, and clean the dataset.
- Perform exploratory analysis (univariate, bivariate, multivariate).
- Visualize the data to gain actionable insights.
- Handle missing values and outliers.
- Summarize findings using visuals and descriptive statistics.

---

## 📊 Dataset Overview

- **Source**: https://archive.ics.uci.edu/dataset/360/air+quality
- **Format**: CSV
- **Size**: 9358 rows and 15 columns

- ## 📊 Dataset Features
The dataset contains hourly air quality measurements and meteorological data from an Italian city.

- **Date** – Date of measurement  
- **Time** – Time of measurement  
- **CO(GT)** – Carbon monoxide concentration in mg/m³ (ground truth)  
- **PT08.S1(CO)** – Sensor 1: Tin oxide sensor for CO  
- **NMHC(GT)** – Non-methane hydrocarbons in µg/m³ (ground truth)  
- **C6H6(GT)** – Benzene concentration in µg/m³  
- **PT08.S2(NMHC)** – Sensor 2: Metal oxide sensor for NMHC  
- **NOx(GT)** – Nitrogen oxides concentration in ppb (ground truth)  
- **PT08.S3(NOx)** – Sensor 3: Electrochemical sensor for NOx  
- **NO2(GT)** – Nitrogen dioxide concentration in µg/m³ (ground truth)  
- **PT08.S4(NO2)** – Sensor 4: Metal oxide sensor for NO2  
- **PT08.S5(O3)** – Sensor 5: Metal oxide sensor for ozone  
- **T** – Temperature in °C  
- **RH** – Relative Humidity in %  
- **AH** – Absolute Humidity in g/m³

---

## 🛠️ Tools & Technologies Used

- Python 3.x
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn

---

## 📈 Key Insights

- 🔹 **CO(GT)** levels were significantly higher during winter months, likely due to increased heating usage and stagnant weather conditions.
- 🔹 There were a large number of **missing or abnormal values (-200)** in the sensor readings, which required data cleaning before analysis.
- 🔹 **Temperature** and **Absolute Humidity (AH)** showed a strong positive correlation — as temperature increased, AH also rose.
- 🔹 Some sensors (e.g., PT08.S1, PT08.S5) had strong linear correlations with their corresponding pollutant ground truth values, indicating good sensor performance.
- 🔹 **Benzene (C6H6)** levels were consistently low but showed spikes during traffic hours (early morning and evening).

---

## 🚀 Getting Started

### Clone the repository:

```bash
git clone https://github.com/yourusername/eda-project.git
cd eda-project
```

### Install dependencies:

```bash
pip install -r requirements.txt
```

### Launch the notebook:

```bash
jupyter notebook
```

---

## 🤝 Contributions

Contributions are welcome! Feel free to fork the repository and submit a pull request.

---

## 📬 Contact

Created by **Sharmila T**  
📧 [sharmilathirukumaran16@gmail.com]
