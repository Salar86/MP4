# MP4 MACHINE LEARNING FOR ANALYSIS AND PREDICTION OF ATTRITION
Made by Group 13

### Which machine learning methods did you choose to apply in the application?

- For supervised learning (classification), we applied the Decision Tree and Naïve Bayes classifiers to predict employee attrition. 
- For unsupervised learning (clustering), we used the K-Means algorithm to segment employees into groups based on their attributes.

### How accurate is your solution of prediction?

- The Naïve Bayes classifier demonstrated better performance with an accuracy of approximately 84% while the Decision Tree had an accuracy of 78%.

### Which are the most decisive factors for quitting a job?

- Positive Correlation: OverTime showed a positive correlation with attrition, suggesting that employees who work or have worked overtime are more likely to leave.
- Negative Correlations: YearsAtCompany showed a slight negative correlation with attrition. This indicates that employees with more years in the company are less likely to leave.

### Which work positions and departments are in higher risk of losing employees?
| Job Role                  | Attrition Rate |
|---------------------------|----------------|
| Sales Representative      | 0.397590       |
| Laboratory Technician     | 0.239382       |
| HR                        | 0.230769       |
| Sales Executive           | 0.174847       |
| Research Scientist        | 0.160959       |
| Manufacturing Director    | 0.068966       |
| Healthcare Representative | 0.068702       |
| Manager                   | 0.049020       |
| Research Director         | 0.025000       |

- Sales Representatives have the highest attrition rate at approximately 39.76%. This suggests that employees in this role are leaving the company at a significantly higher rate compared to other roles. 

- Laboratory Technicians and HR roles also show notable attrition rates at 23.94% and 23.08%.

- On the other end, Research Directors show the lowest attrition rate at 2.5%. This suggests that employees in this role are more likely to stay with the company.

| Department              | Attrition Rate |
|-------------------------|----------------|
| Sales                   | 0.206278       |
| HR                      | 0.190476       |
| Research and Development| 0.138398       |

- Sales Department has the highest attrition rate at 20.63%. This indicates that employees in the Sales department are leaving the company at a higher rate compared to the other two departments.

- HR Department shows an attrition rate of about 19.05%. While lower than Sales, this rate is still relatively high, indicating that the HR department also faces significant employee turnover.

- Research and Development Department has the lowest attrition rate at approximately 13.84%. This suggests that employees in Research and Development are more likely to stay with the company compared to the other two departments.

### Are employees of different gender paid equally in all departments?

| Gender/Department      | Female       | Male         |
|------------------------|--------------|--------------|
| HR                     | 7264.000000  | 6371.023256  |
| Research & Development | 6513.691293  | 6129.888316  |
| Sales                  | 6972.126984  | 6949.645914  |

- In this dataset it is shown that in all three departments, female employees, on average, earn more than their male counterparts.

### Do the family status and the distance from work influence the work-life balance?

| Marital Status | Work-Life Balance |
|----------------|-------------------|
| Divorced       | 2.749235          |
| Married        | 2.756315          |
| Single         | 2.776596          |

- The differences are quite minor, indicating that marital status alone does not have a significant impact on work-life balance in this dataset.

- Correlation between Distance from Home and Work-Life Balance: -0.026556004106569116

The value is close to 0, suggesting that there is almost no linear relationship between the distance an employee lives from work and their perceived work-life balance. This implies that changes in one variable do not predict changes in the other.

### Does education make people happy (satisfied from the work)?

| Education Level      | Job Satisfaction |
|----------------------|------------------|
| Education Level 1    | 2.800000         |
| Education Level 2    | 2.769504         |
| Education Level 3    | 2.652098         |
| Education Level 4    | 2.786432         |
| Education Level 5    | 2.666667         |

- The differences in job satisfaction scores across education levels are relatively small, suggesting that while there might be some variation, education level is not a major determinant of job satisfaction in this dataset

### Which were the challenges in the project development?

- Due to time constraints and no previous experience in Streamlit it proved to be difficult to make the frontend application. However there is a app.py streamlit template provided in the repository.
The large dataset with 32 features was more difficult to code than anticapted. More experience and time is needed to make something meaningful in Streamlit. However, this has been accounted for in the exam project, where we will allocate more time for this part.

