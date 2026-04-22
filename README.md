# NumPy Mini Projects: Logic Validation & Data Analysis

**Prepared by:** Syed Moyeez Ali  
**Domain:** Data Science / Data Analytics  

## About This Repository
This repository contains a Jupyter Notebook that demonstrates practical, hands-on applications of the **NumPy** library. Instead of just basic functions, this project focuses on applying NumPy arrays to solve logical problems and query structured data.

The notebook is divided into two main sections:

### Project 1: Sudoku Board Validator
A logic-based script that checks whether a given 9x9 matrix follows the fundamental sum rules of Sudoku. 
**Key Skills Demonstrated:**
* 2D Array initialization.
* Row-wise and Column-wise aggregations using `axis=1` and `axis=0`.
* Complex matrix slicing `s[i:i+3, j:j+3]` to validate 3x3 sub-grids.

### Project 2: Student Data Analysis & Cleaning
An exploratory data analysis task on a dataset of students (Age, Math Marks, Science Marks) to answer 10 specific analytical questions.
**Key Skills Demonstrated:**
* **Statistical Aggregation:** Calculating means, maximums, and column-wise averages.
* **Boolean Masking & Filtering:** Extracting specific rows based on complex multi-conditions (e.g., `(data[:,1] >=80) & (data[:,2] >=80)`).
* **Broadcasting:** Modifying entire columns efficiently (e.g., increasing marks by 5).
* **Conditional Data Cleaning:** Replacing values based on specific thresholds (e.g., replacing marks < 75 with 0).

## How to Run
1. Clone this repository.
2. Open the `.ipynb` file in Jupyter Notebook or VS Code.
3. Ensure `numpy` is installed in your Python environment.
4. Run the cells to see the real-time data filtering and validation outputs.

---
*Building analytical thinking and programmatic problem-solving skills for Data Science.*
