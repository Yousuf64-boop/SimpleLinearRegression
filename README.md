📊 Simple Linear Regression from Scratch (MeraLR)
This project demonstrates how to implement Simple Linear Regression from scratch using Python—without relying on machine learning libraries like scikit-learn. The model is built using only Python, NumPy, and Pandas for data manipulation and math.

📁 File Overview
SimpleLinearRegression.ipynb
A Jupyter Notebook that:

Defines a custom linear regression class MeraLR

Trains the model on sample data

Predicts outputs on test data

Compares the predictions with expected values

🧠 Key Concepts
Manual implementation of the Linear Regression formula:

Slope (m) and intercept (b) are computed using:

𝑚
=
∑
(
𝑥
𝑖
−
𝑥
ˉ
)
(
𝑦
𝑖
−
𝑦
ˉ
)
∑
(
𝑥
𝑖
−
𝑥
ˉ
)
2
,
𝑏
=
𝑦
ˉ
−
𝑚
𝑥
ˉ
m= 
∑(x 
i
​
 − 
x
ˉ
 ) 
2
 
∑(x 
i
​
 − 
x
ˉ
 )(y 
i
​
 − 
y
ˉ
​
 )
​
 ,b= 
y
ˉ
​
 −m 
x
ˉ
 
Prediction using the equation:

𝑦
=
𝑚
𝑥
+
𝑏
y=mx+b
🛠 Technologies Used
Python

Jupyter Notebook

Pandas

NumPy (optional, used in extension)

Matplotlib (for plotting)


📈 Outputs & Visualization
Prints the learned slope (m) and intercept (b)

Predicts target values for test data

(Optional) Includes a regression line plot comparing predicted and actual data points.


🧩 Future Enhancements
Add support for multiple linear regression

Integrate error metrics like MAE, RMSE, and R² score

Add plotting of regression line with training/test points

Include input validation and exception handling
