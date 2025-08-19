# ST2195-Coursework
Analysis of flight data using R and Python, featuring Metropolis sampling, delay trends, aircraft age impact, and a logistic regression model for flight diversions.

## 📌 Project Summary
This project analyzes flight data  using **R and Python**, focusing on flight delays, aircraft age, and diversion predictions. The project is divided into two main parts.

---

## 📝 Part 1: Metropolis Sampling
### Part 1a
- Implemented the **Random Walk Metropolis Algorithm** to generate samples.  
- Created histograms with kernel density plots and compared them with the probability density function.  
- Calculated sample mean and standard deviation for both R and Python implementations.  

### Part 1b
- Extended the algorithm to compute statistics such as sample mean, variance, and between-sample variance.  
- Generated scatter plots of R-hat values against step values.  
- Validated convergence by filtering out R-hat values greater than 2.5.  

---

## 📝 Part 2: Flight Data Analysis
### Part 2a
- Loaded and managed flight data using **SQLite databases**.  
- Analyzed delays by **time of day** and **day of week** (2000–2004).  
- Found that **morning flights** and **Thursdays/Saturdays** had the lowest delays.  

### Part 2b
- Merged aircraft data to calculate plane ages.  
- Examined correlation between aircraft age and delays using **linear regression**.  
- Concluded that older planes tended to have slightly more delays, though correlation was weak.  

### Part 2c
- Built a **logistic regression model** to predict flight diversions.  
- Addressed class imbalance with oversampling.  
- Achieved ~60–62% accuracy, with **Month** and **DayOfWeek** emerging as the most influential features.  

---

## 🛠️ Tools & Technologies
- **Languages**: R, Python  
- **Database**: SQLite  
- **Visualization**: ggplot2 (R), matplotlib (Python)  
- **Models**: Metropolis Sampling, Linear Regression, Logistic Regression  

---

## 👤 Author
- **Kang Zheng Rui**  
Course: ST2195 Programming for Data Science (SIM-UOL)   
Coursework submission (Mar 2025)
