# 🐼 Pandas CSV Reader & Basic Analysis

A comprehensive data analysis project using Pandas, covering data loading, inspection, statistical summarization, filtering, and exporting results.

> 📌 **Syntecxhub Data Science Internship | Week 1, Project 2**

---

## 📖 About the Project

This project simulates a real-world data analysis workflow using a student performance dataset. Starting from raw CSV data, it walks through the full pipeline of reading, exploring, analyzing, and exporting data, which is the core day-to-day workflow of any data analyst or data scientist.

---

## ✅ What's Covered

| Section | Topics |
|---|---|
| Reading Data | `pd.read_csv()`, `pd.read_excel()` |
| Inspection | `.head()`, `.tail()`, `.info()`, `.dtypes`, `.isnull()` |
| Summary Statistics | `.describe()`, `.mean()`, `.median()`, `.mode()`, `.groupby()` |
| Filtering | Boolean conditions, multiple conditions, `.isin()` |
| Slicing | `.iloc[]` (by position), `.loc[]` (by label/condition) |
| Saving Results | `.to_csv()`, `.to_excel()` (multi-sheet) |

---

## 🗂️ Dataset

A synthetically generated student dataset with **200 rows x 11 columns**, including:
- Student ID, Name, Age, Gender, Department
- Math Score, Science Score, English Score
- Attendance %, Grade, Enrolled Date

The dataset is auto-generated within the notebook, no external file needed.

---

## 📸 Screenshots

### DataFrame Inspection - head()
<img width="1265" height="293" alt="Image" src="https://github.com/user-attachments/assets/c948b893-1a3b-497d-8690-31f376b185f7" />

### Summary Statistics - describe()


### Grouped Stats by Department


### Filtering - CS Students with Grade A


---

## 🛠️ Tech Stack

- **Language:** Python 3.x
- **Libraries:** Pandas, NumPy
- **Environment:** Jupyter Notebook

---

## 🚀 How to Run

1. Clone the repository
```bash
git clone https://github.com/fsafva13-coder/Syntecxhub_Pandas_CSV_Analysis.git
cd Syntecxhub_Pandas_CSV_Analysis
```

2. Install dependencies
```bash
pip install pandas numpy openpyxl jupyter
```

3. Launch the notebook
```bash
jupyter notebook project2_pandas_csv_analysis.ipynb
```

4. Run all cells with **Kernel, Restart and Run All**

---

## 📁 Repository Structure

```
Syntecxhub_Pandas_CSV_Analysis/
├── README.md
└── project2_pandas_csv_analysis.ipynb
```

> Output files like `cs_students.csv` and `analysis_results.xlsx` are generated when you run the notebook.

---

## 💡 Key Takeaways

- Pandas DataFrames make it easy to explore and manipulate tabular data with minimal code
- `groupby()` is powerful for computing group-level statistics in one line
- `.loc[]` and `.iloc[]` serve different but complementary slicing purposes

---

## 👩‍💻 Author

**Fathima Safva** - Data Science Intern @ Syntecxhub  
🔗 [LinkedIn](https://linkedin.com/in/fathima-safva-578294315) · [GitHub](https://github.com/fsafva13-coder)
