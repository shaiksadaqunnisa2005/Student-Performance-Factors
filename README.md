# Student Academic Performance Analysis

## Project Overview
This project analyzes student academic performance and identifies factors associated with exam scores.

The analysis is performed on the **Student Performance Factors** dataset containing **6,607 student records and 20 variables** related to academic, personal, family, and school factors.

## Objective
The main objective is to understand which factors are associated with student exam performance and present the findings through clear data visualizations.

## Dataset
- **Dataset Name:** Student Performance Factors
- **Records:** 6,607
- **Variables:** 20
- **Target Variable:** `Exam_Score`
- **Source:** [Zenodo – Student Performance Factors](https://zenodo.org/records/18338186)
- The dataset contains academic, personal, family, and school-related factors. Missing values occur in `Teacher_Quality`, `Parental_Education_Level`, and `Distance_from_Home`.

## Tools and Technologies
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Google Colab

## Data Analysis
The project includes:
- Data cleaning and preprocessing
- Missing value handling
- Duplicate record checking
- Descriptive statistics
- Correlation analysis
- Group-wise average analysis
- Data visualization

## Key Findings
- Attendance shows a positive relationship with average exam scores.
- Students with more hours studied generally have higher average exam scores.
- Higher parental involvement is associated with higher average exam scores.
- Better access to educational resources is associated with higher average exam scores.

## Visualizations
The project includes visualizations such as:
1. Average Exam Score by Attendance Range
2. Average Exam Score by Hours Studied
3. Parental Involvement vs Average Exam Score
4. Access to Resources vs Average Exam Score

## Project Structure
```text
Student-Academic-Performance-Analysis/
│
├── ShaikSadaqunnisa_StudentAcademicPerformanceAnalysis.ipynb
├── requirements.txt
├── ShaikSadaqunnisa_ProjectReport.docx
└── README.md
```

> The dataset can be downloaded from the Zenodo link provided above and uploaded to Google Colab before running the notebook.

## Setup and Run Instructions

### 1. Download the project
Download or clone this GitHub repository.

### 2. Install the required libraries
Open a terminal or command prompt in the project folder and run:

```bash
pip install -r requirements.txt
```

### 3. Get the dataset
Download **Student Performance Factors.csv** from the [Zenodo dataset page](https://zenodo.org/records/18338186).

### 4. Open the notebook
Open the `.ipynb` file using **Google Colab** or **Jupyter Notebook**.

### 5. Upload the dataset
If using Google Colab, upload `Student Performance Factors.csv` to the Colab session.

### 6. Run the analysis
Run the notebook cells in order to perform data cleaning, exploratory analysis, correlation analysis, group-wise analysis, and visualization.

## Conclusion
The analysis shows that several academic and educational factors are associated with student exam performance. The project demonstrates how Python-based data analytics can be used to clean, analyze, visualize, and communicate insights from student data.

> **Note:** These findings describe associations in the dataset and should not be interpreted as proof of causation.
