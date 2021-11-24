# IMAGE-SEGMENTATION
There are various method of image segmentation such as Thesholding method, Edge Based Method, Region Based method, Clustering Method and many more.
In this project I have done segmentation of image using Gaussian Mixture Model (GMM)

# Gaussian mixture models (GMM)

- GMM are based on the assumption that all data points come from a fine mixture of Gaussian distributions with unkonw parameters.
-  This is useful for modeling more complex data, that has multiple peaks. Sometimes one bell curve isn't enough. We can optimize this model for clustering so that we can classify the data into the discovered classes using the Expectation Maximization algorithm.
- Once we learn the Gaussian parameters, we can generate data from the same distribution as the sourse.
 #
 Suppose there are set of data points that needs to be grouped into several parts or clusters based on their similarty. In machine learning this known as  clustring.
 - Mathemtical calculation and formulation for GGM has skipped here .
 
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
- Input image
 
![rose](https://user-images.githubusercontent.com/94883810/143036286-968749a1-190a-419c-8dce-ca5b0986caeb.jpg)

- Output images
 
![rose_Mask0](https://user-images.githubusercontent.com/94883810/143035412-79445923-d60d-457c-985c-5399554d0fe5.jpg)
![rose_Mask1](https://user-images.githubusercontent.com/94883810/143035872-4aee7c0c-e52f-4fec-82fb-1b11741fd7ab.jpg)

- Segmentated image

![rose-Segmented](https://user-images.githubusercontent.com/94883810/143044184-072d172c-420e-4537-ba36-beaf2c8faa06.jpg)





