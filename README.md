# Multiclass Job Category Classification Using Support Vector Machine Algorithm

## Project Description
This project uses a dataset scraped from the job portal **Tech in Asia**. After data cleaning and type adjustments, seven columns were selected for analysis:  
`Job ID`, `Label Category`, `Name`, `Company`, `Location`, `Salary`, and `Skills`.  

The model uses **Name** and **Skills** as inputs and **Label Category** as output. It was trained using a **Support Vector Machine (SVM)** with a **linear kernel** and **one-vs-rest** approach.  
The model achieved the following performance metrics:  
- **Accuracy:** 88.89%  
- **Precision (Weighted):** 88.87%  
- **Recall (Weighted):** 88.89%  
- **F1-Score (Weighted):** 88.32%

These results indicate that the model effectively predicts job categories based on textual data.

---

## Purpose
The main objective of this project is to develop a machine learning model capable of classifying job postings into multiple categories based on job titles and required skills.  
This project aims to:
- Improve understanding of job market segmentation.  
- Support data-driven career and hiring analysis.  
- Help job seekers and companies identify job types more efficiently.  

---

## Research Questions
- How can job categories be accurately classified using job posting data?  
- Which features (such as job titles and skills) most influence classification accuracy?  
- How effective is the SVM algorithm in multiclass job categorization?  

---

## Process
1. **Feature Selection** — using `Name` and `Skills` as inputs and `Label Category` as output.  
2. **Data Splitting** — dividing the dataset into 80% training and 20% testing data.  
3. **Encoding and Vectorization** — label encoding for output and TF-IDF vectorization for input text.  
4. **Model Training** — applying **SVM** with a **linear kernel** and **one-vs-rest** strategy.  
5. **Model Evaluation** — measuring performance using accuracy, precision, recall, and F1-score.  
6. **Result Visualization** — creating an interactive dashboard using **Google Looker Studio**.  

---

## Dashboard
An interactive dashboard built with **Google Looker Studio** visualizes:
- Job distribution by category  
- Top required skills for each job category  
- Overall demand for specific skills  

🔗 **[View Dashboard](https://lookerstudio.google.com/reporting/ed13a0fc-1e74-4fb4-9625-de6b65a46f88)**  

---

## Project Insights
The analysis shows that **job titles** and **skill keywords** are strong indicators for predicting job categories.  
The high accuracy demonstrates that **SVM with a linear kernel** performs effectively in **multiclass text classification tasks**.  

---

## Conclusion
The trained **SVM model** successfully predicts job categories based on job titles and skills.  
This project is supported by an **interactive analytics dashboard**, providing valuable insights for better visualization and decision-making.  


---

**Author:** Murti Sari Dewi 
**Year:** 2025  

