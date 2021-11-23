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
![Tiger](https://user-images.githubusercontent.com/94883810/143028324-aea64fa6-5d53-451e-8972-903b764a6876.jpg)
![Tiger-Segmented](https://user-images.githubusercontent.com/94883810/143028384-5b918de1-81b8-4dd6-b246-01d0f1cf8f41.jpg)
