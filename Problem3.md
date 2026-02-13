Problem: Minimize Cost Function

Given cost function:
![Gradient Descent Graph](images/gradient_descent_graph.png)

f(x)= x^2 − 4x + 4

Step 1: Compute Derivative

f′(x) = 2x − 4

Step 2: Set Learning Rate

Let: α = 0.1


Update rule:

x(new) = x(old)− αf′(x)

Step 3: Iterative Updates

Start with x = 0
f′(0)= −4
x = 0 − (0.1)(−4) = 0.4

Next iteration:
f′(0.4) = 2(0.4) − 4 = −3.2
x = 0.4 − (0.1)(−3.2) = 0.72

Repeating this process converges toward:
x=2

Optimal Solution

Minimum occurs at:
x = 2
f(2) = 0
	​
