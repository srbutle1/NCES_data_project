# NCES_data_project (In Progress)
Analyzing NCES high school data

The High School Longitudinal Study of 2009 (HSLS:09) is part of the High School Longitudinal Study (HSLS) program. HSLS:09 (https://nces.ed.gov/surveys/hsls09/) is a longitudinal survey that follows more than 21,000 9th graders in 944 schools throughout their secondary and postsecondary years. 

---

## Files

### Code

* nces_features.ipynb
* nces_analysis.ipynb
* nces_predict.ipynb

### Data Documentation

* data_docs/Codebook.txt
* data_docs/HSLS09_VariableList_BY-F2_revised.xlsx

## Explanation of Code Files

### nces_features.ipynb

This notebook chooses features from among the >8000 to be analyzed in this project.

data files

* in: data/hsls_16_student_v1_0.csv
* out: processed/hsls_16_student_processed.csv

### nces_analysis.ipynb

This notebook engineers some features and analyzes data.

data files

* in: processed/hsls_16_student_processed.csv 
* out: processed/hsls_16_student_engineered.csv

### nces_predict.ipynb

This notebook makes predictions about AP classes taken by using students math and science data from 9th grade.

data files

* in: processed/hsls_16_student_engineered.csv
