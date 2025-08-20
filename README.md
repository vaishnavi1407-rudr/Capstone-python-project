# *Capstone Python Project* 🐍  

## *Project Overview*  
This project involves *data cleaning, manipulation, and analysis* using *Python* and *Pandas*.  
We worked with *three different datasets, merged them into a **single DataFrame*, handled missing values, created new columns, applied conditions, and derived insights from the data.

---

## *Project Objectives* 🎯
- Read and combine *three different tables* into *Pandas DataFrames*.
- Handle missing values and replace them with *running averages*.
- Create *new columns* (e.g., splitting full names into *first* and *last names*).
- Join all three DataFrames into one *final DataFrame*.
- Perform data cleaning and transformations, such as:
  - Adding *bonus columns*.
  - Decreasing *designation levels* for employees with failed projects.
  - Deleting employee records with *designation levels above 4*.
  - Adding *Mr.* / *Mrs.* prefixes to names.
  - Dropping unnecessary columns.
  - Decreasing designation levels by *1* for employees *aged above 29*.
- Calculate *total project cost* for each employee.
- Filter and display *employees* whose *city names contain specific letters*.

---

## *Technologies Used* 🛠️
- *Programming Language*: Python 🐍  
- *Libraries*:  
  - *Pandas* → Data manipulation  
  - *NumPy* → Numerical operations  
  - *Matplotlib / Seaborn* (optional) → Data visualization  

---

## *Project Structure* 📂
Capstone-Python-Project/ │ ├── data/ │   ├── employees.csv │   ├── projects.csv │   ├── departments.csv │ ├── notebooks/ │   ├── Capstone_Project.ipynb │ ├── scripts/ │   ├── data_cleaning.py │   ├── data_analysis.py │ ├── output/ │   ├── final_dataset.csv │ ├── README.md └── requirements.txt

##Key Insights 📊

Missing values handled using running averages.

Employee records cleaned, transformed, and enriched.

Final dataset generated with bonus calculations.

Employees filtered based on age, designation level, and city names.

##Final Output 🏆

Cleaned dataset with all transformations applied.

Final CSV file: final_dataset.csv

Insights ready for analysis and reporting.
