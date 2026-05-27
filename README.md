# COVID-19 Data Analysis Project

## 📌 Project Overview

This project focuses on analyzing COVID-19 data using Python to uncover trends, patterns, and insights related to confirmed cases, deaths, recoveries, vaccination progress, and country-wise impact.

The analysis includes:

* Data cleaning and preprocessing
* Exploratory Data Analysis (EDA)
* Visualization of trends
* Country-wise comparison
* Vaccination analysis
* Insights and conclusions

---

# 📊 Objectives

* Understand the spread of COVID-19 globally
* Analyze confirmed, recovered, and death cases
* Compare country-wise pandemic impact
* Identify trends over time
* Visualize vaccination progress
* Build analytical skills using real-world datasets

---

# 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Plotly
* Jupyter Notebook

---

# 📂 Dataset Information

The dataset used in this project contains:

* Country/Region
* Confirmed Cases
* Death Cases
* Recovered Cases
* Active Cases
* Vaccination Data
* Date-wise Records

Dataset Source:

* Our World in Data
* Kaggle COVID-19 Dataset
* Johns Hopkins University Dataset

---

# 📁 Project Structure

```bash
COVID-19-Analysis/
│
├── data/
│   ├── covid_data.csv
│
├── notebooks/
│   ├── covid_analysis.ipynb
│
├── images/
│   ├── cases_trend.png
│   ├── vaccination_chart.png
│
├── README.md
└── requirements.txt
```

---

# ⚙️ Installation & Setup

## 1️⃣ Clone the Repository

```bash
git clone https://github.com/your-username/COVID-19-Analysis.git
```

## 2️⃣ Navigate to Project Folder

```bash
cd COVID-19-Analysis
```

## 3️⃣ Install Required Libraries

```bash
pip install -r requirements.txt
```

## 4️⃣ Run Jupyter Notebook

```bash
jupyter notebook
```

---

# 📈 Exploratory Data Analysis

The project performs several analyses including:

### ✅ Total Confirmed Cases Over Time

* Daily trend analysis
* Peak infection periods
* Growth patterns

### ✅ Death Rate Analysis

* Country-wise death comparison
* Mortality trends

### ✅ Recovery Analysis

* Recovery percentage
* Active vs recovered cases

### ✅ Vaccination Analysis

* Total vaccinated population
* Country-wise vaccination progress
* Vaccination trends over time

---

# 📊 Visualizations Included

* Line Charts
* Bar Charts
* Heatmaps
* Pie Charts
* Correlation Matrix
* Country Comparison Graphs

---

# 🔍 Key Insights

* Countries with higher population density showed rapid spread.
* Vaccination significantly reduced death rates in many countries.
* Recovery rates improved after healthcare improvements and vaccination rollout.
* Multiple waves of infections were observed globally.

---

# 📌 Sample Python Code

```python
import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sns

# Load dataset
_df = pd.read_csv('covid_data.csv')

# Top 10 countries by confirmed cases
top_countries = _df.groupby('Country')['Confirmed'].sum().sort_values(ascending=False).head(10)

# Plot
plt.figure(figsize=(12,6))
sns.barplot(x=top_countries.index, y=top_countries.values)
plt.xticks(rotation=45)
plt.title('Top 10 Countries by Confirmed Cases')
plt.show()
```

---

# 📉 Future Improvements

* Build an interactive dashboard using Power BI or Tableau
* Deploy project using Streamlit
* Add machine learning prediction models
* Perform state-wise analysis

---

# 🤝 Contribution

Contributions are welcome.
Feel free to fork this repository and submit pull requests.

---

# 📜 License

This project is licensed under the MIT License.

---

# 👨‍💻 Author

**Sudhir Maurya**

* Data Analyst Enthusiast
* Skilled in SQL, Python, Excel, Power BI

---

# ⭐ If You Like This Project

Give this repository a star ⭐ and share your feedback.
