# 🧪 Pymaceuticals Inc. — Anti-Cancer Drug Data Analysis

## 📊 Overview

As a Senior Data Analyst at **Pymaceuticals Inc.**, your job is to analyze the results of a 45-day clinical study that monitored **249 mice** infected with **squamous cell carcinoma (SCC)**. The mice received treatment under various drug regimens to test for efficacy in reducing tumor size.

This project uses **Pandas**, **Matplotlib**, and **SciPy** to:
- Clean and prepare experimental data
- Calculate summary statistics
- Visualize distributions and treatment effects
- Identify promising treatments
- Evaluate correlation between tumor volume and mouse weight

---

## 📁 Project Structure
pymaceuticals/
├── pymaceuticals_study.ipynb          # Main analysis notebook
├── Resources/
│   ├── mouse_metadata.csv             # Mouse ID, sex, drug regimen, etc.
│   └── study_results.csv              # Tumor volume observations over time
└── README.md                          # Project documentation
---

## 🎯 Objectives

### 1. 🧼 Prepare the Data
- Merge `mouse_metadata` and `study_results` datasets
- Identify and remove duplicate mouse/timepoint entries
- Confirm unique mouse IDs post-cleaning

### 2. 📈 Generate Summary Statistics
- For each **drug regimen**:
  - Mean, median, variance, standard deviation, SEM of tumor volume

### 3. 📊 Bar & Pie Charts
- **Bar Charts**:
  - Total number of timepoints recorded per regimen (using both Pandas and Pyplot)
- **Pie Charts**:
  - Distribution of male vs. female mice (using both Pandas and Pyplot)

### 4. 📦 Quartiles, Outliers, Box Plot
- Analyze **Capomulin, Ramicane, Infubinol, and Ceftamin**
- Compute final tumor volume for each mouse
- Determine IQR and outliers
- Plot boxplot to visualize spread and outliers

### 5. 📉 Line Plot
- Choose a single mouse treated with **Capomulin**
- Plot tumor volume over time

### 6. ⚖️ Scatter Plot
- Show correlation between mouse weight and **average** tumor volume under **Capomulin**

### 7. 🧮 Correlation & Linear Regression
- Compute correlation coefficient
- Overlay linear regression line on scatter plot

---

## ✅ Requirements Checklist

| Feature                                       | Status |
|-----------------------------------------------|--------|
| Data preparation and merging                  | ✅     |
| Duplicate detection and removal               | ✅     |
| Summary statistics for all regimens           | ✅     |
| Bar charts (Pandas & Pyplot)                  | ✅     |
| Pie charts (Pandas & Pyplot)                  | ✅     |
| IQR, outlier detection, and box plot          | ✅     |
| Line plot for tumor volume over time          | ✅     |
| Scatter plot for mouse weight vs tumor volume | ✅     |
| Correlation coefficient & regression line     | ✅     |

---

## 📌 Example Visualizations

- 📦 **Box Plot**: Final tumor volumes for top 4 treatments  
- 📈 **Line Plot**: Tumor volume over time for Mouse l509 under Capomulin  
- 🔁 **Scatter Plot + Regression**: Mouse weight vs average tumor volume  
- 📊 **Bar/Pie Charts**: Drug regimen frequencies and mouse sex distribution  

---

## 🧠 Key Insights

- **Capomulin and Ramicane** showed the **lowest final tumor volumes** on average.
- There is a **strong positive correlation** between **mouse weight** and **tumor size** under Capomulin, suggesting heavier mice developed larger tumors.
- **Outliers** in Infubinol data may indicate inconsistencies or mice with poor response.

---

## 🛠️ Technologies Used

- Python 3.x  
- Pandas  
- Matplotlib  
- NumPy  
- SciPy (linregress)  
- Jupyter Notebook  

---

## 🧪 How to Run

1. Clone the repository.
2. Open `pymaceuticals_study.ipynb` in Jupyter Notebook.
3. Run all cells sequentially.
4. View visualizations inline.

---

## 📚 Acknowledgments

This analysis is part of the [edX Data Analytics Boot Camp]. The dataset and project structure are provided for educational purposes to simulate pharmaceutical data workflows.

---

## 👩‍💻 Author

**Aditi Nankar**  
Data Analyst | Visualization Enthusiast | Life Sciences + Python  
