# 🚀 Task 1: Data Cleaning & Preprocessing - Elevate AI/ML Internship

## 📌 Objective
The goal of this task was to learn and implement basic data preprocessing techniques to clean and prepare raw data for machine learning models.

---

## 📁 Dataset Used
**Titanic Dataset**  
Source: [Kaggle Titanic Dataset]
https://www.kaggle.com/datasets/yasserh/titanic-dataset

---

## 🧰 Tools & Libraries
- Python
- Pandas
- NumPy
- Seaborn
- Matplotlib
- Scikit-learn

---

## 🧪 Steps Performed

### 1. **Data Loading & Exploration**
- Loaded dataset using `pandas`.
- Explored dataset using `.info()`, `.describe()`, `.isnull().sum()`.

### 2. **Handling Missing Values**
- `Age`: Filled missing values using **median**.
- `Embarked`: Filled using **mode**.
- `Cabin`: Dropped due to high percentage of missing data.

### 3. **Encoding Categorical Features**
- Used **Label Encoding** for `Sex` and `Embarked`.

### 4. **Dropping Unnecessary Columns**
- Removed columns: `Name`, `Ticket`, `PassengerId`.

### 5. **Outlier Detection & Removal**
- Used **boxplots** to visualize outliers.
- Applied **IQR method** to remove outliers in `Age` and `Fare`.

### 6. **Feature Scaling**
- Applied **StandardScaler** to `Age` and `Fare`.

---

## 📊 Final Output
- Cleaned and preprocessed dataset ready for ML model training.

---

## 📎 File Structure
├── Titanic-Dataset.csv
├── task1.ipynb
├── README.md
