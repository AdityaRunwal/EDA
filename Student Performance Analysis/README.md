# Student Performance Analysis

## 📌 About the Project

This is a beginner-friendly Exploratory Data Analysis (EDA) project based on student performance data.

The goal of this project is to understand the dataset, clean the data, create useful visualizations, and explore which factors are related to students' final grades.

The main focus is on the final grade (`G3`) and its relationship with factors such as study time, absences, previous failures, and gender.

---

## 🎯 What I Wanted to Find

In this project, I explored questions like:

- How are students' final grades distributed?
- How many male and female students are in the dataset?
- Does study time have a relationship with final grades?
- Are absences related to final grades?
- How do previous failures relate to final grades?
- How do final grades differ between male and female students?
- Which numerical features are correlated with final grades?

---

## 📊 Dataset

The dataset contains information about students, including their:

- Age and gender
- Family background
- Study habits
- Social and lifestyle factors
- Previous failures
- School absences
- Academic grades

### Some Important Columns

| Column | Description |
|---|---|
| `school` | Student's school |
| `sex` | Student's gender |
| `age` | Student's age |
| `address` | Type of residential area |
| `studytime` | Weekly study-time category |
| `failures` | Number of previous failures |
| `absences` | Number of school absences |
| `G1` | First-period grade |
| `G2` | Second-period grade |
| `G3` | Final grade |

---

## 🔍 What I Did

### Data Understanding
- Checked the dataset size
- Checked column names and data types
- Viewed the first few records
- Generated a statistical summary
- Checked unique values

### Data Cleaning
- Checked for missing values
- Checked for duplicate records
- Checked numerical ranges
- Checked categorical values

### Data Visualization
- Final grade distribution
- Gender distribution
- Study time vs final grade
- Absences vs final grade
- Previous failures vs final grade
- Gender vs final grade
- Correlation heatmap

---

## 🛠️ Tools Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## 📁 Project Structure

```text
Student-Performance-EDA/
│
├── Student Performance Analysis.ipynb
├── student_data.csv
└── README.md
