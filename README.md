# Support-Vector-Machines

Support Vector Machine (SVM) is a supervised machine learning algorithm and is very popular among data scientists.
The main idea behind SVM is to draw a line between two or more classes in the best possible manner. Once the line is drawn to separate the classes, you can then use it to predict future data. The goal is to find the largest possible width for the margin that can separate the two groups. The center of the margin is called a hyperplane.
The hyperplane is the line separating the two groups of points. We use the term “hyperplane” instead of “line” because in SVM we typically deal with more than two dimensions, and using the word “hyperplane” more accurately conveys the idea of a plane in a multidimensional space.

![SVM_4](https://user-images.githubusercontent.com/53411455/138561828-cdc2ea45-5dd4-4474-bf66-3dd38019ff3a.png)
Decision boundary found by linear SVM

# Kernel Trick

Sometimes, the points in a dataset are not always linearly separable. You can see that it is not possible to draw a straight line to separate the two sets of points. With some manipulation, however, you can make this set of points linearly separable. This technique is known as the kernel trick. The kernel trick is  technique in machine learning that transforms data into a higher dimension space so that, after the transformation, it has a clear dividing margin between classes of data.

![SVM_6](https://user-images.githubusercontent.com/53411455/138561795-707272b8-d032-4148-9c21-f3773d268db6.png)
3D hyperpane cutting through two sets of points

# Types of Kernel

## Polynomial Kernel

## Radial Basis Function (RBF)

# Conclusion

Kernelized support vector machines are powerful models and perform well on a variety of datasets. SVMs allow for complex decision boundaries, even if the data has only a few features. They work well on low-dimensional and high-dimensional data (i.e., few and many features), but don’t scale very well with the number of samples. Running an SVM on data with up to 10,000 samples might work well, but working with datasets of size 100,000 or more can become challenging in terms of runtime and memory usage.
Another downside of SVMs is that they require careful preprocessing of the data and tuning of the parameters.

