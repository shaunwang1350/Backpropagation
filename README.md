# Backpropagation
![Developement](https://img.shields.io/badge/progress-complete-green)
![commit](https://img.shields.io/github/last-commit/shaunwang1350/Backpropagation)
![githubfollows](https://img.shields.io/github/followers/shaunwang1350?style=social)
## Summary
In this Programming Assignment: Backpropagation on Coursera's Mathematics for Machine Learning: MultiVariate (Imperial College London), I trained a neural network to draw a curve. The curve takes one input variable, the amount travelled along the curve from 0 to 1, and returns 2 outputs, the 2D coordinates of the position of points on the curve.

## Processes
- Using Numpy matrices, I implemented a backpropagation Jacobians with a 3 layer neutral net. 

<div style="text-align:center"><img src="image/formula1.png" /></div>
<div style="text-align:center"><img src="image/formula2.png" /></div>

- Wrote algorthim for layer 3, 2, 1 of Jacobian for the cost fuction / weight partial derivatives.

<div style="text-align:center"><img src="image/formula3.png" /></div>
<div style="text-align:center"><img src="image/formula4.png" /></div>
<div style="text-align:center"><img src="image/formula5.png" /></div>

- Tested my results through tracing 50,000 iterations using plot_training from the matplotlib class.

## Technologies Used
* Python
* Numpy
* Matplotlib Pyplot
* Jupyter Notebook

## Result:

![Image](image/image1.png)
