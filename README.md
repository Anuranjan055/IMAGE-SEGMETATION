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
    <td valign="top"><img src="![rose_Mask0](https://user-images.githubusercontent.com/94883810/143034938-5bc312bf-8484-4da4-af18-f5ef3ceb4a76.jpg)"></td>
    <td valign="top"><img src="![rose_Mask1](https://user-images.githubusercontent.com/94883810/143034994-0037d27a-bc72-4b76-8ade-fd09ac01ee24.jpg)"></td>
    <td valign="top"><img src="![rose-Segmented](https://user-images.githubusercontent.com/94883810/143035040-e686b900-e597-47f0-a5b1-4041d4c97033.jpg)"></td>
  </tr>
 </table>
  


