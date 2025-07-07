# 📊 Employee Performance Analysis

This project explores how structured HR data can be transformed into actionable insights using Python and Pandas. Using a real-world-style dataset of 1,000 employees, we demonstrate cleaning, feature engineering, and exploratory analysis techniques suitable for workforce evaluation and planning.

---

## 📁 Dataset

**File:** `Employe_Performance_dataset.csv`  
**Size:** ~1,000 records  
**Columns Include:**  
- Employee Name  
- Age  
- Department  
- Experience in Years  
- Performance Score  
- Salary  
- State  
- Status (Active/Left)

---

## ⚙️ Features Implemented

### 🧹 Data Cleaning
- Removed duplicates and unrealistic values  
- Filled missing performance scores using department-wise medians  
- Standardized inconsistent categorical entries  

### 🏗 Feature Engineering
- `Bonus (10%)` column based on Salary  
- `Experience Level` classification (Junior/Mid/Senior)  
- `Age Group` buckets (e.g., 20–30, 30–40, etc.)  
- `Monthly Salary` calculation  
- Merged project and budget data (example joins)  

### 📈 Data Analysis
- Grouped summaries by Department, Status, and State  
- Performance score distribution  
- Salary analysis by department  
- Filtering top performers, active staff, etc.  

---

## 📌 How to Run

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Aryan-0042/employee-performance-analysis.git
   cd employee-performance-analysis

2. **Install required packages:**
   ```bash
   pip install pandas numpy matplotlib jupyter

3. **Launch the analysis notebook:**
   ```bash
   jupyter notebook EmployeePerformancePrediction.ipynb

---

## 🖼 Sample Outputs

- **Performance Score Distribution**  
  Visual histogram showing how many employees fall into each performance category (1–5).

- **Average Salary by Department**  
  Bar chart comparing mean annual salaries across HR, IT, and Sales.

- **Bonus Estimates**  
  Table of calculated 10% bonus amounts alongside each employee’s salary.

- **High Performer Filters**  
  Predefined views that list employees with Performance Score ≥ 4, broken out by department.

---

## 💡 Use Cases

- **HR Dashboards**  
  Embed these analyses into an interactive dashboard for ongoing talent reviews.

- **Retention Analytics**  
  Spot at‑risk employees by combining performance trends with tenure and status.

- **Budget Planning**  
  Align headcount and salary data with departmental budgets for forecasting.

- **Training & Workshops**  
  Use as a teaching example in Python/Pandas bootcamps or university courses.

---

## 📄 License

This repository and its contents are provided **as-is** for educational purposes.  
Feel free to fork and modify, but please **do not** use the synthetic dataset or analysis for commercial applications.

---

## 🙌 Acknowledgements

- **Nishant Sir** for guidance and feedback throughout the project.  
- **Sharda University** for the Summer Internship Program and research support.
