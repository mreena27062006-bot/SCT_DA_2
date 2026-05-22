# SCT_DA_2 - Data Cleaning & Preparation

## 📌 Task
Internship Task 2 at SkillCraft Technology
Data Cleaning and Preparation using Python & Pandas

## 📊 Dataset
Global Superstore Dataset
- Total Rows: 51,290
- Total Columns: 33

## 🛠️ Tools Used
- Python 3
- Pandas Library
- JupyterLab

## ✅ Steps Performed
1. Loaded dataset using pd.read_csv()
2. Explored data using head(), info(), describe()
3. Checked missing values — found 0 missing values
4. Applied dropna() and fillna() as verification
5. Removed duplicate rows — found 0 duplicates
6. Fixed corrupted column name (Chinese characters → Returns)
7. Converted Order.Date and Ship.Date from object to datetime64
8. Extracted Order Year, Order Month, Order Month Name
9. Verified Sales and Profit as numeric types
10. Exported cleaned data as SCT_DA_2_cleaned.csv

## 📁 Files
- SCT_DA_2.ipynb — Jupyter Notebook with complete code
- SCT_DA_2_cleaned.csv — Final cleaned dataset
- Screenshots — Output screenshots

## 🔑 Key Concepts Learned
- DataFrame operations with Pandas
- Handling missing values
- Removing duplicates
- Data type conversion
- DateTime manipulation
- Data export to CSV
