# TT Sprint_11_insurance
This is a repository for TT Sprint 11 project using machine learning models to predict customer insurance benefits. This project:

- Used machine learning to identify similar customers to support marketing activities, predict customers likely to receive an insurance benefit and the number of benefits, and protect clients’ personal data through a data transformation algorithm (data masking/obfuscation).
- Functions created to measure k nearest neighbors using both Euclidean and Manhattan distance metrics and to check invertibility for developing data mask. Used kNN classifier to identify similar customers and linear regression to predict the number of benefits.
- The model was built and tested on the Jupyter platform using Python language coding.
- The model was developed and tested by the data science student, and reviewed by a project reviewer.

Example code for using a kNN classifier to predict target on test data:
![image](https://github.com/user-attachments/assets/ce8fda62-af08-4fdc-9257-84f2d0c3b32e)

**Project Results and Conclusions:** Based on the results of the project, it was determined a linear classification model will accurately predict whether a given insurance customer will receive any insurance benefits, particularly if using scaled features data (independent variable data). Furthermore, a regression model will result in being able to accurately predict the number of benefits a customer will receive based on independent variables (gender, age, income, number of family members). Using obfuscated data protects clients' data without compromising model results.

This project uses insurance claim data available here: https://practicum-content.s3.us-west-1.amazonaws.com/datasets/insurance_us.csv

To run the program, Python 3 (3.11.5) was used with the following libraries: pandas, numpy, seaborn, sklearn, scipy, math, IPython.

To launch this project on a local machine, the data set should be accessible in the project folder, and python lanched with the above listed packages installed. 
