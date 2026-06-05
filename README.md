# 1_Data_Analysis_Warm_Up_-NP-
## Pandas Data Analysis Warm-Up

A quick, hands-on practice notebook designed to brush up on fundamental data analysis techniques using Python's **Pandas** and **NumPy** libraries. 

This project demonstrates core DataFrame manipulation skills, basic filtering, and exploratory data analysis (EDA) techniques on a small, synthetic student dataset.

---

## Objectives & Tasks Covered

The notebook steps through 15 fundamental operations frequently used in data science workflows:

### 1. Data Inspection
* **Top 3 Rows:** Viewing the initial structure using `.head()`.
* **Last 3 Rows:** Inspecting the tail end of the dataset using `.tail()`.
* **Dataset Shape:** Discovering total row and column counts using `.shape`.
* **Dataset Information:** Displaying data types, column counts, and memory footprint via `.info()`.

### 2. Summary Statistics & Exploration
* **Null Value Check:** Finding and handling missing values with `.isnull().sum()`.
* **Overall Statistics:** Generating statistical metrics (mean, min, max, etc.) using `.describe()`.
* **Categorical Breakdown:** Extracting unique values, counting unique elements, and finding value distribution frequencies (`.unique()`, `.nunique()`, and `.value_counts()`) for categorical dimensions (e.g., `Gender`).

### 3. Filtering, Sorting & Data Manipulation
* **Range Filtering:** Finding students with specific score windows using the `.between()` method.
* **Aggregations:** Calculating mathematical aggregates like the average marks (`.mean()`).
* **Column Dropping:** Removing unnecessary columns safely from a DataFrame (`.drop()`).
* **Metadata Extraction:** Grabbing a raw list of column headers (`.columns`).
* **Sorting Data:** Sorting records sequentially by specific numeric parameters (`.sort_values()`).
* **Conditional Slicing:** Extracting target column attributes (e.g., `Name` and `Marks`) filtered dynamically by conditions (e.g., female students only).

---

## Tech Stack & Dependencies

* **Language:** Python 3.x
* **Libraries:** * [Pandas](https://pandas.pydata.org/) - For structured data manipulation.
  * [NumPy](https://numpy.org/) - For underlying multi-dimensional array capabilities.
* **Environment:** Jupyter Notebook / JupyterLab

---

## Dataset Quick View

The operations are conducted on a built-in dictionary structured as follows:

| Name | Marks | Gender |
| :--- | :---: | :--- |
| Priyang | 98 | Male |
| Aadhya | 89 | Female |
| Krisha | 99 | Female |
| Vedant | 87 | Male |
| Parshv | 90 | Male |
| Mittal | 83 | Female |
| Archana | 99 | Female |

---

## How to Run This Project

Choose the option below that fits your workflow best:

### Option 1: The Quick Way (No Tools Required)
1. Click the green **Code** button at the top right of this GitHub page.
2. Select **Download ZIP** and extract the files to a folder on your computer.
3. Open your terminal or command prompt, navigate to that folder, and run:
   ```bash
   pip install pandas numpy notebook
   jupyter notebook
