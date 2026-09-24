# Student Lifestyle & Academic Performance Data Analysis

## 1. Project Overview
This project performs an end-to-end data analysis of student lifestyle and academic variables. It includes data loading, data cleaning, exploratory data analysis (EDA), visualization, correlation analysis, hypothesis testing, and a simple regression model.

**Important:** The included CSV is a synthetic/sample dataset created for demonstration. For an actual submission based on Google Forms, export your real responses as CSV and replace `student_survey_data.csv` with your file, keeping the column names consistent or updating the notebook accordingly.

## 2. Objectives
- Clean and prepare survey data.
- Summarize student demographic and lifestyle characteristics.
- Visualize study, sleep, screen-time, attendance, stress, and GPA patterns.
- Examine relationships between lifestyle/academic variables and GPA.
- Apply Pearson correlation and an independent-samples t-test.
- Demonstrate a simple regression model.
- Produce a reproducible Jupyter Notebook.

## 3. Dataset
File: `student_survey_data.csv`

Rows: 302
Columns: 11

Variables:
- Student_ID
- Age
- Gender
- Study_Hours_Per_Day
- Sleep_Hours_Per_Day
- Screen_Time_Hours_Per_Day
- Attendance_Percent
- Stress_Level
- Assignments_Completed_Percent
- Extracurricular_Activity
- GPA

## 4. Technologies
- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- SciPy
- Scikit-learn

## 5. Project Files
- `Aditya_StudentLifestyleDataAnalysis.ipynb` — complete analysis notebook
- `student_survey_data.csv` — sample dataset
- `requirements.txt` — Python dependencies
- `Aditya_StudentLifestyleProjectReport.docx` — project report
- `README.md` — project documentation

## 6. Setup and Run

### Windows
```bash
python -m venv venv
venv\Scripts\activate
pip install -r requirements.txt
jupyter notebook
```

### Linux/macOS
```bash
python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt
jupyter notebook
```

Open:
`Aditya_StudentLifestyleDataAnalysis.ipynb`

Run all cells from top to bottom.

## 7. Replacing the Dataset with Google Forms Responses
1. Open Google Forms.
2. Open the **Responses** tab.
3. Export/link the responses to Google Sheets.
4. Download the response sheet as CSV.
5. Rename it to `student_survey_data.csv`.
6. Update the column names in the notebook if your form questions differ.
7. Run the notebook again.
8. Verify every chart and statistic before submission.

## 8. Data Ethics and Limitations
The analysis should not be used to identify or judge individual students. Survey data can contain self-reporting bias and sampling bias. Correlation does not prove causation. If real responses are used, remove unnecessary personal identifiers before sharing the dataset.

## 9. Dataset Link
For the provided sample, the dataset is included locally in this project folder. If your college requires a public dataset link, use the link to your own Google Sheet/Drive dataset or the approved source specified by your instructor.
