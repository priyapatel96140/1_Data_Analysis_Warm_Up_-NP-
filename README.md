# 1_Data_Analysis_Warm_Up_-NP-
# Pandas Data Analysis Warm-Up

A quick, hands-on practice notebook designed to brush up on fundamental data analysis techniques using Python's **Pandas** and **NumPy** libraries. 

This project demonstrates core DataFrame manipulation skills, basic filtering, and exploratory data analysis (EDA) techniques on a small, synthetic student dataset.


## Project Structure

The repository includes:
* **`1-Data Analysis Warm Up - question.ipynb`**: The Jupyter Notebook outlining the fundamental data manipulation exercises and practice cells.


## Tech Stack & Dependencies

* **Language:** Python 3.x
* **Libraries Used:** Pandas, NumPy
* **Environment:** Jupyter Notebook / JupyterLab


## Dataset Overview

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


## Key Tasks Covered

The notebook goes through 15 practical steps to find insights on:
1. **Data Inspection:** Using `.head()`, `.tail()`, `.shape`, and `.info()` to view rows, structural counts, and memory details.
2. **Summary Statistics:** Generating data summaries via `.describe()` and checking for missing data using `.isnull().sum()`.
3. **Categorical Analysis:** Finding unique items and tracking distribution frequencies using `.unique()`, `.nunique()`, and `.value_counts()`.
4. **Data Slicing & Filtering:** Isolating rows using score ranges with `.between()`, computing column updates, and applying logical filters (like isolating rows matching female students).
5. **Sorting & Column Management:** Dropping specific unneeded columns, listing column headers, and sorting rows sequentially by numeric attributes.


## How to Run This Project

Choose the option below that works best for you:

### Option 1: The Quick Way (No Git Required)
1. Click the green **Code** button at the top right of this GitHub page.
2. Click **Download ZIP** and unzip the files into a folder on your computer.
3. Open your terminal or command prompt, navigate to that folder, and run:
   ```bash
   pip install pandas numpy notebook
   jupyter notebook

## Author

Priya Patel  
Aspiring Data Analyst  
Email: priyapatel18217@gmail.com  
LinkedIn: 
GitHub:  

If you like this project, feel free to give it a star!
