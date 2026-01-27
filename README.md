# Salary Dataset — Exploratory Data Analysis (EDA)

## Objective
Analyze a salary dataset to understand how experience, education level, job role, and other factors are related to salary distribution.

## Dataset
- **Source:** Salary dataset (CSV)
- **Target variable:** Salary
- **Key features:** Experience, Education Level, Job Role, Age

## Questions Explored
- How is salary distributed overall?
- How does salary change with experience?
- Does education level meaningfully differentiate salary?
- Which numerical features show correlation with salary?

## Key Findings
- Salary distribution is right-skewed, with a long high-end tail.
- Experience shows a positive relationship with salary, but not strictly linear.
- Bachelor’s and Master’s degrees dominate the dataset.

## Tools Used
- Python
- Pandas
- NumPy
- Matplotlib / Seaborn
- Jupyter Notebook

## Data Cleaning & Assumptions
- Checked for missing and inconsistent values.
- Assumed reported salaries are annual and standardized.

## Next Steps
- Feature Engineering
- Outlier handling for high salary extreme values.
- Train a regression models.
- Validate findings with a larger or more diverse dataset.

## Repository Structure
- `eda_salary.ipynb` — Main EDA notebook
- `Salary_Data.csv` — Dataset
- `README.md` — Project overview