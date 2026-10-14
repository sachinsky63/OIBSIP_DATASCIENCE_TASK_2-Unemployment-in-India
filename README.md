# 📊 Unemployment Analysis in India&#x20;

## 📌 Project Overview

This project focuses on performing Exploratory Data Analysis (EDA) on unemployment data in India to understand regional variations, monthly trends, and the impact of the COVID-19 pandemic on unemployment rates.

The analysis uses Python libraries to clean, explore, visualize, and interpret unemployment-related indicators.

## 🎯 Objectives

- Analyze average unemployment rates across Indian regions.
- Identify regions with relatively high unemployment rates.
- Examine monthly unemployment trends over time.
- Compare unemployment patterns across selected regions.
- Explore correlations between unemployment, employment, and labour participation.
- Compare average unemployment rates before and after March 2020.

## 📂 Dataset

**Dataset:** Unemployment in India

The dataset contains the following key columns:

- `Region` — Indian region or state.
- `Date` — Observation date.
- `Estimated Unemployment Rate (%)` — Estimated unemployment rate.
- `Estimated Employed` — Estimated number of employed people.
- `Estimated Labour Participation Rate (%)` — Estimated labour participation rate.

**Note:** The dataset is expected to be available as `Unemployment in India.csv` in the project directory. Refer to the original dataset source for attribution and usage terms.

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## 🔍 Exploratory Data Analysis

The project includes the following analyses:

1. **Data Inspection and Cleaning**

   - Dataset shape and column inspection.
   - Missing-value analysis.
   - Date and numerical data type conversion.

2. **Region-wise Analysis**

   - Calculation of average unemployment rates.
   - Identification of the ten regions with the highest averages.
   - Bar chart and horizontal bar chart visualizations.

3. **Monthly Trend Analysis**

   - Visualization of monthly average unemployment rates.
   - Identification of fluctuations over time.

4. **Selected Region Comparison**

   - Comparison of unemployment trends in Tripura, Haryana, and Jharkhand.

5. **Correlation Analysis**

   - Correlation matrix for unemployment, employment, and labour participation indicators.
   - Heatmap visualization.

6. **Pre-COVID vs. Post-COVID Comparison**

   - Pre-COVID period: Before March 2020.
   - Post-COVID period: March 2020 onward.
   - Comparison of average unemployment rates and their difference in percentage points.

## 📈 Key Findings

The analysis is designed to identify:

- Regional differences in average unemployment rates.
- Monthly fluctuations in unemployment.
- Differences in unemployment patterns across selected regions.
- Relationships between unemployment, employment, and labour participation.
- Differences between average unemployment rates before and after March 2020.

**Note:** Exact numerical findings should be added after running the notebook and verifying the calculated results.

## ⚙️ Installation and Setup

### 1. Clone the repository

```bash
git clone https://github.com/sachinsky63/OIBSIP_DATASCIENCE_TASK_2-Unemployment-in-India.git
```

### 2. Navigate to the project directory

```bash
cd SachinKumarYadav_Task_2
```

### 3. Install the required libraries

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

### 4. Launch Jupyter Notebook

```bash
jupyter notebook
```

Open the unemployment analysis notebook and run the cells sequentially.

## 📁 Project Structure

```text
Unemployment-Analysis/
├── Unemployment_Analysis.ipynb
├── Unemployment in India.csv
├── README.md
└── requirements.txt
```

## 💡 Conclusion

This project demonstrates how Exploratory Data Analysis can be used to investigate regional and temporal unemployment patterns in India.

Visualizations and statistical summaries help identify variations in unemployment rates and explore relationships between labour market indicators. The pre-COVID and post-COVID comparison provides an initial descriptive assessment of unemployment levels across the two periods.

However, the comparison alone does not establish that COVID-19 caused the observed differences.

## 🚀 Future Improvements

- Perform a detailed month-by-month analysis around the 2020 lockdown.
- Compare regional recovery patterns.
- Investigate missing values and potential outliers.
- Apply statistical tests to evaluate differences between periods.
- Develop an interactive dashboard using Streamlit or Power BI.

## 👨‍💻 Author

**Sachin Kumar Yadav**

Data Science Intern — Oasis Infobyte

GitHub: [@sachinsky63](https://github.com/sachinsky63)

## 🙏 Acknowledgement

This project was completed as part of the Oasis Infobyte Data Science Internship, Task 2.

Thanks to Oasis Infobyte for providing the opportunity to work on a practical data analysis project.
