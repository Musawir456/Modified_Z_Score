# 📊 Modified Z-Score for Outlier Detection (Python)

This repository demonstrates the use of **Modified Z-Score** for detecting outliers in datasets using Python and Jupyter Notebook.

Modified Z-Score is a more robust alternative to the traditional Z-Score, especially when dealing with skewed data or datasets containing extreme outliers.

---

## 📌 Project Overview

This project covers:

- 📍 What is Modified Z-Score
- 📍 Difference between Z-Score and Modified Z-Score
- 📍 Median and MAD (Median Absolute Deviation)
- 📍 Outlier detection technique
- 📍 Practical implementation using real dataset
- 📍 Excel and CSV based examples

---

## 🧠 What is Modified Z-Score?

Unlike traditional Z-Score (which uses mean and standard deviation), Modified Z-Score uses:

- Median
- Median Absolute Deviation (MAD)

It is more robust because the median is less affected by extreme values.

---

## 📊 Formula

```
Modified Z-Score = 0.6745 × (Xi − Median) / MAD
```

Where:

- Xi = Data point
- Median = Middle value of dataset
- MAD = Median Absolute Deviation
- 0.6745 = Scaling constant

---

## 📌 Outlier Rule

A data point is considered an outlier if:

```
|Modified Z-Score| > 3.5
```

---

## 📂 Files in This Repository

| File Name | Description |
|------------|-------------|
| `modified_z_score_tutorial.ipynb` | Step-by-step explanation & implementation |
| `movie_revenues.csv` | Dataset for outlier detection |
| `modified_z_score.xlsx` | Excel-based calculation example |

---

## 📊 Why Use Modified Z-Score?

- Handles skewed data better
- Less sensitive to extreme values
- More reliable for real-world datasets
- Useful in financial and revenue analysis
- Important for ML data preprocessing

---

## 🛠️ Technologies Used

- Python 3
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Excel

---

## 🚀 How to Run

### 1️⃣ Clone the repository

```bash
git clone https://github.com/your-username/Modified_Z_Score.git
```

### 2️⃣ Open Jupyter Notebook

```bash
jupyter notebook
```

### 3️⃣ Open the notebook file

```
modified_z_score_tutorial.ipynb
```

---

## 🎯 Learning Outcomes

After completing this project, you will:

- Understand robust statistics
- Detect outliers using Modified Z-Score
- Compare Z-Score vs Modified Z-Score
- Apply outlier detection in ML preprocessing
- Strengthen statistical foundation

---

## 📈 Future Improvements

- Add comparison plots (Z-Score vs Modified Z-Score)
- Add boxplot visualization
- Add automated outlier removal function
- Integrate with ML pipeline
- Add real-world business dataset

---

## 👨‍💻 Author

**Abdul Musawir**  
BS IoT Student  
AI, ML & Data Science 

---

⭐ If you found this repository helpful, consider giving it a star!
