# 🦠 COVID-19 Global Data Tracker

## 📌 Project Overview

This project is a data analysis notebook that tracks **global COVID-19 trends** using real-world data from [Our World in Data](https://ourworldindata.org/coronavirus). It includes data cleaning, exploration, visualizations, and insights focused on **cases**, **deaths**, and **vaccinations** across multiple countries.

---

## 🎯 Project Objectives

- ✅ Import and clean global COVID-19 data
- ✅ Analyze trends over time (cases, deaths, vaccinations)
- ✅ Compare metrics across countries and regions
- ✅ Visualize data with charts and interactive maps
- ✅ Summarize key findings and insights

---

## 📁 Data Source

- **Dataset**: `owid-covid-data.csv`
- **Provider**: [Our World in Data](https://github.com/owid/covid-19-data)
- **Format**: CSV

---

## 🛠️ Technologies Used

- `Python 3`
- `pandas` – data manipulation
- `matplotlib`, `seaborn` – static charts
- `plotly.express` – interactive choropleth map
- `Jupyter Notebook` – code, visuals & narrative

---

## 📂 Project Structure

| File | Description |
|------|-------------|
| `COVID19_Global_Data_Tracker.ipynb` | The main analysis notebook |
| `owid-covid-data.csv` | COVID-19 dataset (Our World in Data) |
| `README.md` | Project overview and instructions |
| `*.pdf` (optional) | Exported report version |

---

## 🔍 Tasks Breakdown

### 1️⃣ Data Collection  
- Downloaded OWID COVID-19 dataset (`.csv`)

### 2️⃣ Data Loading & Exploration  
- Checked structure, columns, and missing values

### 3️⃣ Data Cleaning  
- Filtered for Kenya, USA, India  
- Handled missing values  
- Converted dates and normalized fields

### 4️⃣ Exploratory Data Analysis (EDA)  
- Line charts for total cases, deaths, and death rate  
- Daily trends and comparison by country

### 5️⃣ Vaccination Progress  
- Cumulative vaccinations by country  
- % of vaccinated population

### 6️⃣ Choropleth Map  
- Interactive world map showing total cases  
- Uses Plotly and ISO country codes

### 7️⃣ Insights  
- Written summary of key patterns and anomalies

---

## 📊 Example Visuals

- 📈 Total Cases Over Time  
- 💉 Vaccination Rollout Charts  
- 🗺️ Global Case Map (Plotly Choropleth)

---

## 📌 How to Run the Project

1. Open the notebook in Jupyter or JupyterLab.
2. Ensure `owid-covid-data.csv` is in the same directory.
3. Run all cells from top to bottom.
4. To export:
   - Go to `File > Export As > PDF` *(in JupyterLab)*

---

## 💡 Key Insights

- The USA had the highest cumulative COVID-19 cases.
- India showed rapid vaccination rollout.
- Kenya had lower cases but also limited data in early months.
- Death rates decreased as vaccinations increased globally.

---

## 🧠 Author

**Niniwe Xaka**  
📧 xakaniniwe@gmail.com  
🌍 South Africa

---

## 📜 License

This project is for educational and academic purposes only.
# COVID-19-Global-Data-Tracker
