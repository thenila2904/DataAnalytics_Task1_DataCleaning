# DataAnalytics_Task1_DataCleaning
Part of Elevate labs Data Analytics Virtual Internship
# 📊 Task 1: Data Cleaning and Preprocessing

## 🎯 Objective
The goal of this task is to clean and preprocess a raw dataset by identifying and fixing common data issues such as missing values, duplicates, inconsistent formats, and incorrect data types.  
This step ensures that the dataset is accurate, consistent, and ready for further analysis or modeling.

---

## 🛠 Tools & Technologies Used
- **Python**
- **Pandas** library
- **Google Colab** / **Jupyter Notebook**
- **GitHub** for version control

---

## 📂 Dataset
The dataset used for this task is from [Kaggle](https://www.kaggle.com/).  
Example: **Customer Personality Analysis**  
It contains demographic and behavioral information about customers.  

---

## 🧹 Data Cleaning Steps Performed
1. **Loading the Dataset**
   - Imported dataset using Pandas.

2. **Handling Missing Values**
   - Identified missing values using `.isnull().sum()`.
   - Filled missing values with mean/mode where applicable or removed rows if necessary.

3. **Removing Duplicates**
   - Removed duplicate rows using `.drop_duplicates()`.

4. **Standardizing Text Data**
   - Converted text to lowercase or proper case for consistency.
   - Removed extra spaces from strings.

5. **Formatting Date Columns**
   - Converted date columns to a consistent format (`dd-mm-yyyy`).

6. **Renaming Columns**
   - Renamed columns to lowercase with underscores for readability.

7. **Fixing Data Types**
   - Converted numerical columns to appropriate numeric types.
   - Ensured date columns were stored as `datetime` objects.

---

## 📁 Files in This Repository
- `dataset.csv` → Raw dataset from Kaggle.
- `cleaning.ipynb` → Jupyter Notebook with all cleaning steps.
- `cleaned_dataset.csv` → Final cleaned dataset ready for analysis.
- `README.md` → Documentation for this project.

---

## 📈 Result
- The cleaned dataset is **free from duplicates, missing values, and inconsistencies**.
- Ready for **data analysis** or **machine learning model building**.

---

## 🚀 How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/thenila2904/task1_data_cleaning.git

