# Insurance Cost Statistical Analysis

This project was completed during my remote internship as a **Data Science Intern at Great Learning Pvt. Ltd.** from *15 June 2020 to 16 August 2020*. It focuses on understanding and statistically evaluating factors affecting individual medical charges using a healthcare insurance dataset.

## 📌 Project Objective

To explore the healthcare insurance dataset and extract insights about how various attributes (such as age, BMI, smoking status, and region) affect individual medical costs. The project emphasizes both exploratory data analysis and hypothesis-driven statistical testing.

## 🗂️ Dataset Overview

- **Source**: Provided by Great Learning
- **Rows**: 1,338  
- **Columns**: 7  
- **Features**:
  - `age`: Age of beneficiary
  - `sex`: Gender of insurance holder
  - `bmi`: Body mass index
  - `children`: Number of dependents
  - `smoker`: Smoking status
  - `region`: Residential region
  - `charges`: Medical cost billed

## 🔍 Key Techniques Used

- **Exploratory Data Analysis**:
  - Distribution plots of `age`, `bmi`, and `charges`
  - Outlier detection using IQR
  - Countplots and violinplots for categorical variables

- **Statistical Analysis & Testing**:
  - **T-test** to compare charges between smokers and non-smokers
  - **T-test** to check BMI difference across genders
  - **Chi-square test** for association between gender and smoking
  - **ANOVA** to test BMI variance among women with different child counts

## 📈 Major Insights

- **Smokers pay significantly more** in medical charges than non-smokers (*p < 0.001*).
- **BMI does not differ significantly** between males and females.
- There is a **statistically significant association** between gender and smoking habits.
- **No statistical difference** in BMI among women with 0, 1, or 2 children.

## 🛠️ Tools & Libraries

- Python  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- SciPy Stats, Scikit-learn

## 📚 Learning Outcomes

- Hands-on application of statistical tests like T-Test, ANOVA, and Chi-square
- Practice in identifying skewness and outliers
- Visualization of distribution trends across numerical and categorical features

## 🔗 Other Projects of this Internship

- **Project 1: Amazon E-commerce Purchase Analysis**  
  [GitHub Link](https://github.com/raunak-choudhary/Amazon-Ecommerce-Purchase-Analysis-Data-Science-Internship-2020.git)

- **Project 3: LaLiga Statistics Analysis**  
  [GitHub Link](https://github.com/raunak-choudhary/LaLiga-Statistics-Analysis-Data-Science-Internship-2020.git)

## 👨‍💻 Author

**Raunak Choudhary**  
Email: [raunakchoudhary17@gmail.com](mailto:raunakchoudhary17@gmail.com)
