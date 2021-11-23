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
 # Instructions
 - First get your sample image in "Images" folder 
 - Run the image_segmentation_using_GMM (python sourse code file) to get the segmented image.
 - Enter image name and number of componants of image.
 - Output segmented image will be store in "Result" folder.
# Sample Input-output images
Markup:![rose_Mask0](https://user-images.githubusercontent.com/94883810/143035412-79445923-d60d-457c-985c-5399554d0fe5.jpg)
Markup: ![rose_Mask1](https://user-images.githubusercontent.com/94883810/143035872-4aee7c0c-e52f-4fec-82fb-1b11741fd7ab.jpg)
Markup: ![rose-Segmented](https://user-images.githubusercontent.com/94883810/143035951-edaa5e9c-32ee-4ae5-877e-d1eb6df371c7.jpg)




