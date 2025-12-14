# Assignment 05 — Linear Regression From Scratch
 Overview

In this assignment, Linear Regression is implemented manually using only NumPy, without using Scikit-learn.
This helps in understanding the mathematical foundation behind:

Loss function (MSE)

Gradient Descent optimization

Weight updates

Model predictions

Training loop

 What I Learned

Derivation of cost function for linear regression

How gradients work

How to implement batch gradient descent

Importance of learning rate

Plotting loss vs iterations

Evaluating model performance manually

 Mathematical Concepts Used
 Hypothesis
𝑦
^
=
𝑚
𝑥
+
𝑐
y
^
	​

=mx+c
 Loss Function
𝐽
=
1
2
𝑚
∑
(
𝑦
−
𝑦
^
)
2
J=
2m
1
	​

∑(y−
y
^
	​

)
2
 Gradients
∂
𝐽
∂
𝑚
=
−
1
𝑚
∑
𝑥
(
𝑦
−
𝑦
^
)
∂m
∂J
	​

=−
m
1
	​

∑x(y−
y
^
	​

)
∂
𝐽
∂
𝑐
=
−
1
𝑚
∑
(
𝑦
−
𝑦
^
)
∂c
∂J
	​

=−
m
1
	​

∑(y−
y
^
	​

)
 Update Rule
𝑚
=
𝑚
−
𝛼
∂
𝐽
∂
𝑚
m=m−α
∂m
∂J
	​

𝑐
=
𝑐
−
𝛼
∂
𝐽
∂
𝑐
c=c−α
∂c
∂J
	​

Technologies Used

Python 3.x

NumPy

Pandas (optional)

Matplotlib

Folder Structure
Assignment-05-Linear-Regression-From-Scratch/
│── Assignment-05.ipynb
│── dataset.csv       (optional)
│── README.md
│── requirements.txt

 How to Run
1. Install dependencies
pip install -r requirements.txt

2. Launch notebook
jupyter notebook Assignment-05.ipynb

 Expected Outputs

Gradient Descent implementation

Graph of Loss vs Iterations

Learned slope m and intercept c

Predicted values vs Actual values plot
