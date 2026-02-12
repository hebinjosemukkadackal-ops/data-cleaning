# 📊 Task 1: Data Cleaning and Preprocessing (Google Colab)

## 📁 Dataset
Netflix Movies and TV Shows Dataset (Kaggle)

---

## 🎯 Objective
To clean and preprocess the Netflix dataset using Python (Pandas) in Google Colab.

---

## 🛠 Tools Used
- Python
- Pandas
- NumPy
- Google Colab

---

## 🧹 Data Cleaning Steps Performed

### 1️⃣ Loaded Dataset
- Imported dataset using pandas
- Checked basic structure using `df.head()` and `df.info()`

### 2️⃣ Handled Missing Values
- Filled missing values in:
  - `director` → "Unknown"
  - `cast` → "Unknown"
  - `country` → "Unknown"
- Filled missing `rating` using mode
- Cleaned `date_added` column by removing extra spaces
- Converted `date_added` to datetime format

### 3️⃣ Removed Duplicates
- Checked and removed duplicate rows using:
