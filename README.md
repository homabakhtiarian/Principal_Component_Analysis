# Principal Component Analysis(PCA)

Many Machine Learning problems involve thousands or even millions of features for
each training instance. Not only do all these features make training extremely slow,
but they can also make it much harder to find a good solution.
Principal Component Analysis (PCA) is by far the most popular dimensionality reduction algorithm.
First it identifies the hyperplane that lies closest to the data, and then
it projects the data onto it.
PCA identifies the axis that accounts for the largest amount of variance in the training set.
It also finds a second axis, orthogonal to the
first one, that accounts for the largest amount of remaining variance. If it were a higher-dimensional 
dataset, PCA would also find a third axis, orthogonal to both previous axes, and a fourth,
a fifth, and so on—as many axes as the number of dimensions in the dataset.
The i'th axis is called the i'th principal component (PC) of the data. 
