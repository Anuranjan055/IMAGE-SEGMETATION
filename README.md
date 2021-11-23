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

<table>
  <tr>
    <td>First Screen Page</td>
     <td>Holiday Mention</td>
     <td>Present day in purple and selected day in pink</td>
  </tr>
  <tr>
    <td><![rose_Mask0](https://user-images.githubusercontent.com/94883810/143034251-7b421f0d-eb0c-4297-bf4d-2474d306054e.jpg)></td>
    <td><![rose_Mask1](https://user-images.githubusercontent.com/94883810/143034300-9b842098-3ffd-4f46-8479-55ff8c6ba3c9.jpg)></td>
    <td><![rose-Segmented](https://user-images.githubusercontent.com/94883810/143034409-331ca1e0-7496-4fe5-baf9-57ca7a7d0b82.jpg)></td>
  </tr>
 </table>


