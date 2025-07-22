# Smart Resume-Based Salary Predictor

A Machine Learning-powered tool that predicts salary based on a candidate's resume. Simply upload a resume in PDF format and get insights like:
- Predicted Salary
- 3-Year Salary Projection
- Skill Gap Analysis based on job title

From resume to personalized career insights – all in one click.

---

## Features

- **PDF Resume Upload**  
  Extracts name, age, gender, job title, education, experience, location, email, GitHub, LinkedIn, and skills.

- **Salary Prediction**  
  Uses a trained Linear Regression model on real-world salary data to predict current salary.

- **3-Year Salary Projection**  
  Projects salary growth over the next 3 years assuming a 7% yearly increment.

- **Skill Gap Analysis**  
  Compares extracted skills with job-specific required skills and highlights what’s missing.

- **Visualization**  
  Plots your projected salary growth using Matplotlib.

---

## Tech Stack

- Python
- Pandas, NumPy, Scikit-learn – Data preprocessing & ML model
- PyMuPDF (fitz) – PDF text extraction
- Regex (re) – Resume parsing
- Matplotlib – Salary projection plots

---

## Project Structure

├── Salary Data.csv # Training dataset
├── Prediction.ipynb # Main jupyter notebook

---

## How It Works

1. Upload your resume in PDF format  
2. Resume text is extracted using PyMuPDF  
3. Skills, job title, and other features are parsed using Regex  
4. A Linear Regression model predicts salary  
5. Skill gap analysis compares parsed skills with job-specific requirements  
6. A plot shows 3-year salary projection

---
