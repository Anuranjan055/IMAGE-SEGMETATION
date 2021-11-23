# IMAGE-SEGMETATION
There are various method of image segmentation such as Thesholding method, Edge Based Method, Region Based method, Clustering Method and many more.
In this project I have done segmentation of image using Gaussian Mixture Model (GMM)

# Gaussian mixture models (GMM)

- GMM are based on the assumption that all data points come from a fine mixture of Gaussian distributions with unkonw parameters.
-  This is useful for modeling more complex data, that has multiple peaks. Sometimes one bell curve isn't enough. We can optimize this model for clustering so that we can classify the data into the discovered classes using the Expectation Maximization algorithm.
- Once we learn the Gaussian parameters, we can generate data from the same distribution as the sourse.
 #
 Suppose there are set of data points that needs to be grouped into several parts or clusters based on their similarty. In machine learning this known as  clustring.
 - I am skipping the mathemtical calculation for GGM.
 
 # Code Dependencies
 - Numpy
 - Matplotlib
 - cv2
 - sklearn.mixture
# sample Input-output image
Solarized dark             |  Solarized Ocean
:-------------------------:|:-------------------------:
![Tiger-mask0](https://user-images.githubusercontent.com/94883810/143028789-e43b5050-8af4-4df7-9f6e-dd1ff5445a3e.jpg) ![Tiger-mask1](https://user-images.githubusercontent.com/94883810/143029024-7b1a360e-28f3-489e-874c-ad5886a60f54.jpg)


