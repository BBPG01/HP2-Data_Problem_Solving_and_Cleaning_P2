# HP2-Data_Problem_Solving_and_Cleaning_P2

This project is the continuation of my data science portfolio, inspired by TripleTen’s methodology but adapted to the healthcare context. It focuses on cleaning, transforming, and analyzing hospital patient records to generate actionable.

## 🎯 Project Goals
- Clean raw hospital data (names, ages, services, expenses).
- Normalize categories of medical services for consistent analysis.
- Calculate hospital KPIs such as:
  - Total revenue
  - Service usage distribution
  - Patient segmentation by age and spending
- Build reusable functions for filtering patients by service or condition.

## 📂 Dataset
The dataset simulates hospital records with the following fields:
- **patient_id**: unique identifier
- **patient_name**: full name (string)
- **patient_age**: age (float → integer)
- **categories_of_care**: list of services (uppercase)
- **expenses**: list of expenses per service

Example:
```python
['1001', ' juan_perez ', 45.0, ['EMERGENCY','CONSULTATION','PHARMACY'], [1200,450,230]]

```

## 🛠️ Technologies
- Python (data cleaning, transformation, analysis)
- Jupyter Notebook (documentation and execution)
- Power BI (visualization of KPIs)

## 🚀 How to Run
1. Clone this repository:
```python
bash
git clone https://github.com/yourusername/HP2-Hospital-Data-Cleaning.git
```
2. Install dependencies:
```python
bash
pip install pandas numpy
Open the notebook in Jupyter and run the cells step by step.
```

## 📊 Example Outputs
- Cleaned patient dataset
- Total hospital revenue calculation
- List of patients under 40 years old
- Patients with high spending (>2000)
- Service usage percentages
