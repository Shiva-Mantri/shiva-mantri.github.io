---
layout: post
title:  "Linear Regression Explained"
categories: [ds/ai/ml]
permalink: /:year/:month/:day/:title:output_ext
---

### Building an intuitive understanding of how Linear Regression works and how it leads to Gradient Descent.
**Reference**: How a straight line teaches machines to learn. [https://briefer.cloud/blog/posts/least-squares/](https://briefer.cloud/blog/posts/least-squares/) 

**Slope** Sets the tilt of the line. As the tilt increases, y-variable/x-variable increases. e.g. Price/Sq.Ft.  
**Intercept** Shifts the line up or down in the graph or where the line starts.  It sets the baseline value. e.g. starting value of home.  
**Error** Represents how far are we from the actual value.  
**Absolute Error** treats all the error magnitudes the same. Two medium errors is same as one big one.  
**Non-Linear Scale** Squaring errors cause big errors to be bigger and hence the error line will be non-linear.  

**Plotting errors** - Imagine a plot where each point represents a different line: the slope and intercept are the coordinates, and the vertical axis shows how bad the line is—its error. In this landscape of errors, high points mean worse lines; low points mean better ones. Our goal is simple: find the lowest point. We won't actually draw this plot (there are too many possibilities), but picturing it helps make the task clear.  
![image](https://github.com/user-attachments/assets/5b5e54fb-86a0-450b-b074-93c4bca07ea0)  

**Derivative & Gradient Descent** - At every step, we need to decide which way to move: left or right. To do that, we measure how steep the curve is at our current point. This measurement (the steepness of the curve) is called the derivative. If the derivative is positive, it means the error increases if we move right, so we should go left. If the derivative is negative, it means the error increases if we move left, so we should go right. This process of iteratively minimizing a function using derivatives is called **gradient descent**.




