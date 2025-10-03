# Mapping the Future of Data Careers  
*A Big Data Approach to Job Trend Analysis and Salary Prediction*

This project explores trends in the data science job market using a large dataset of job postings. We focused on how salaries vary by job title, experience, employment type, and company characteristics, and built machine learning models to predict salary ranges. The goal is to help job seekers, employers, and educators make better decisions using data-driven insights.

---

## 🔍 Project Overview
We used a dataset from **AI Jobs.net**, updated monthly throughout 2024, covering thousands of data science job postings. After cleaning and enhancing the dataset, we analyzed trends and applied predictive modeling.

Key objectives:
- Understand salary dynamics across roles, industries, and locations  
- Build predictive models for salary forecasting  
- Provide insights that support career planning and hiring decisions  

---

## 📊 Dataset
Main features included:
- **work_year** – year of posting  
- **job_title** – specific job role  
- **job_category** – grouped into 10 broader categories  
- **salary_in_usd** – annual gross salary in USD  
- **experience_level** – entry, mid, senior, executive  
- **employment_type** – full-time, part-time, contract  
- **work_setting** – remote, hybrid, in-person  
- **company_size** – small, medium, large  
- **company_location** – country of employer  

---

## ⚙️ Methods & Models
- **Gradient Boosting Regressor** for salary prediction  
  - RMSE: ~$53,491  
  - Model underpredicted very high salaries and overpredicted very low ones  
- **Log Transformation** of salary target improved results slightly  
  - RMSE: ~$53,997  
  - Still showed bias at higher salary ranges  

Visualizations included:
- **Box plots** of salaries by job title and employment type  
- **Bar charts** of job category counts  
- **Salary distribution dashboards** built in Tableau  

---

## 📈 Key Insights
- **Experience level** is the single biggest driver of salary differences.  
- **Research Engineer** roles emerged with higher salary ranges than most other titles.  
- **Data Science & Research** is the largest category by job count.  
- Contract and freelance roles showed greater variability in salaries, with some extreme outliers.  
- Entry-level analysts in certain countries offered surprisingly strong salary opportunities when adjusted for cost of living.  

---

## ✅ Conclusion
Our analysis shows that:  
- Data careers continue to offer **significant upward mobility**.  
- Salaries vary widely by role, company size, and work setting.  
- Predictive models can provide guidance but still struggle with extremes (very high salaries).  
- Adding **cost of living adjustments** and correcting dataset imbalances improves fairness in comparison.  
- A continuously updated analysis pipeline ensures job seekers have real-time insights.  

---

## 📚 References
- *The Ambiguity of Data Science Team Roles* – IEEE Xplore  
- *Glassdoor Job Description Analytics* – IEEE Xplore  
- Shapiro, J. (2023). *4 Skills the Next Generation of Data Scientists Needs* – HBR  
- Simplilearn (2024). *Top 20+ Data Scientist Skills You Need*  
- AI Jobs.net (2024). *Global AI/ML/Data Science Salary Index*  

---

## 👨‍💻 Team
- **Rakesh Somukalahalli Venkatappa**  
- Pritham Mahajan  
- Nithish Bilasunur Manjunatha Reddy  
- Sai Sriram Dubsi  

Advisor: **Dr. Eddy Zhang**  
Course: **AIT-614 Big Data Essentials** – George Mason University (Spring 2024)  

---
