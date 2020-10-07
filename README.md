## Gradient Descent from Scratch

The gradient descent is the central algorithm of Neural Nets, Deep Learning, Machine Learning and optimization in general. This is the way you achieve any critical point, either extrema points (minima an maxima) or stationary points (saddle points), depending on the shape of your function on a specific region (concave, convex or undefined).

Here I want to leave aside, at least for now, as much formal math definitions as possible, since any good Calculus book may provide explanations about generalizations, proofs, propositions, theorems and corollaries.

In this series I would like to focus on the practical approach of how to calculate the gradient descent from scratch, and then how it translates into Python, so that you can grasp the very basic details of the algorithm and how it works.

Later we can move to using some advanced packages and let the machine build and calculate everything for you.

### Programming language
Python

### IDE 
Jupyter Notebook (IPython)

### How to use it (the way I do when learning something new)
1. Install required packages and tools.
2. Fork this repository to have your own copy.
3. Clone this copy on your local system.
4. Make your changes, carry out experiments and draw your own conclusions.

### Important notice
I have focused on making the code simple, readable and easily modifiable.  It is not optimized and omits desirable features.

So let's start off by analyzing a very basic gradient descent algorithm, applied on a small simple linear regression example.





The gradient descent is an iterative algorithm that converges to the answer by taking steps in the direction of the gradient of this function.

A gradient is the vector of partial derivatives and it points to the direction of maximum increase of the function (steepest ascent) because of its nature of being perpendicular to the tangent lines of the function contour lines at each of its points. The magnitude of the gradient is the value of the maximum directional derivative at some point.

Let's see what happens under the hood when running gradient descent on different models.

### Model examples
* Linear Regression (1)
* Linear Regression (2)
* Logistic Regression
