# data-cleaning-project
This project focuses on cleaning a raw Netflix dataset using Python and pandas.  
The goal is to transform messy, real-world data into a clean, consistent, and reliable dataset that can be used for further analysis 

The project demonstrates a complete end-to-end data cleaning workflow, including inspection, validation, and documentation of decisions.

##  Dataset
- **Source**: Netflix dataset (CSV)
- **Format**: Zipped CSV file
- **Description**:  
  The dataset contains information about Netflix movies and TV shows, including title, type, director, country, date added, release year, rating, duration, and genres.
##  Data Cleaning Steps Performed

The following steps were applied systematically:

1. **Initial Data Inspection**
   - Used `head()`, `info()` to understand structure and issues

2. Deleted redundant columns

3. **Column Name Standardization**
   - Converted the first letter of column names to Uppercase
   - checked for spaces and underscores

4. **Duplicate Handling**
   - Checked for and removed duplicate records

5. **Missing Value Handling**
   - Identified missing values
   - Applied appropriate strategies based on column context

6. **Data Type Validation**
   - Ensured numeric columns were correctly typed
   - Preserved text columns where mixed formats existed (e.g., date_added)

7. **Sanity Checks**
   - Verified numeric ranges and logical validity of values

8. **Final Validation**
   - Confirmed no unintended missing values
   - Verified final data types and dataset integrity

---

##  Tools & Technologies Used
- Python
- pandas
- Google Colab
- GitHub

---

##  Final Outcome
The final dataset contains **8,790 clean records** with consistent formatting, validated values, and no unintended missing data.  
It is ready for exploratory data analysis (EDA), visualization, or machine learning workflows.

---

##  Key Learnings
- Importance of thoughtful handling of missing values
- How to identify and correct inconsistent categorical data
- Why data validation is critical in real-world datasets
- How to structure and document a professional data cleaning project

---
