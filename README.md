Support Vector Machine (SVM)

Support Vector Machine (SVM) is a supervised machine-learning algorithm used for classification and regression. Its main idea is to find the best separating boundary (called a hyperplane) between classes. SVM tries to maximize the margin, which is the distance between the hyperplane and the closest data points—these important points are called support vectors. A larger margin usually means better generalization to unseen data.

Kernel Trick

Many datasets are not linearly separable in their original space. The kernel trick solves this by transforming the data into a higher-dimensional space, where a linear separator can exist.

Instead of computing this transformation directly (which can be expensive), SVM uses kernel functions that compute the inner product in the higher-dimensional space without ever transforming the data explicitly.
This makes SVM powerful and computationally efficient.

Common Kernel Transformations

Here are four widely used kernel transformations:

1. Linear Kernel

No transformation; works well when classes are already linearly separable.

2. Polynomial Kernel

Maps data into polynomial feature space.

Captures more complex curves and interactions.

3. RBF (Radial Basis Function) / Gaussian Kernel

Very popular; maps data into infinite-dimensional space.

Excellent for circular or irregular boundaries.


4. Sigmoid Kernel

Based on the activation function of neural networks.

Useful when relationships resemble neural-style nonlinearities.

′
)=tanh(αx
T
x
′
+c)
