# Automation of Counting objects using Image Processing Techniques

<h2>ABSTRACT:</h2>

This project discuss about techniques of object detection that are used to count the number of objects on the image.The program should automatically detect the desire object and count the number of objects in that image by detecting the edges of an image. We are going to estimate density of image whose integral over any image region gives us count of objects within that region.

<h2>INTRODUCTION:</h2>

Object counting is a very common task performed in different industries.Finding out how many objects in an image is required in image analysis. Object counting is used to get certain number of elements from images. These elements act as a source of information for quantitative analysis, motion tracking and qualitative analysis.The conventional method for object counting is manual, time consuming and in non-automatic form. Continuous counting leads to eye fatigue and affects the accuracy of results.

Because automatic counting is objective, reliable and reproducible, comparison of cell number between specimens is considerably more accurate with automatic programs than with manual counting. While a user normally gets a different result in each measurement when counting manually, automatic programs obtain consistently a unique value.The program should automatically detect and count the total number of object from image. In the process of object detection, targeted object which is uncertain due to presence of other object is one of the main problem faces in image processing field.

<h2>PROCESS:</h2>

<h3>Canny Edge Detection:</h3>

The high pass filtered image is passed through the canny edge detection algorithm which detects the edges of the cells. It includes many sub functions involving double thresholding,differentiation of the image based on the change in the intensity and avoiding the false edges.The secondary edges in the image are obtained by using connected components methodology removing and edge detection are performed at this stage.

![image](https://user-images.githubusercontent.com/53599318/100911930-dfb8e380-34f5-11eb-97c7-5be98abdc3b2.png)

<h3>Closing Morphological Operation:</h3>

Closing is Dilation followed by Erosion. It is useful in closing small holes inside the foreground objects and the small points on the image. This is useful for connecting the small gaps present in the edges of the cells.

<h3>Contouring The image:</h3> 

Contours are closed regions in the image which are obtained by the canny edge detection algorithm. These contours are found in the image, which indirectly represent the cells present in the image. The basic idea of the red blood cells counting was to use three major techniques which are logical, morphology and contour detection.

<h2>ARCHITECTURE AND SYSTEM MODEL:</h2>

![architecture](https://user-images.githubusercontent.com/53599318/100908918-142aa080-34f2-11eb-8b73-6be0034b0ed9.png)
  
  The methods used are:

1. The proposed density-based approach.

2. The counting-by-regression baseline.

3. The counting-by-detection baseline.

4. Application-specific method.

<h2>RESULTS AND DISCUSSION:</h2>

![image](https://user-images.githubusercontent.com/53599318/100912343-5524b400-34f6-11eb-83dd-d60e458651f2.png)

![image](https://user-images.githubusercontent.com/53599318/100912698-d2e8bf80-34f6-11eb-917d-8a1966f67072.png),![image](https://user-images.githubusercontent.com/53599318/100910633-37eee600-34f4-11eb-9a7e-bf9871ed60dc.png)

![image](https://user-images.githubusercontent.com/53599318/100910729-505f0080-34f4-11eb-9bef-9ddbd1ad31c6.png),![image](https://user-images.githubusercontent.com/53599318/100910772-5e148600-34f4-11eb-8f29-891c2dda4187.png)

<h2>SUMMARY :</h2>

• The separation of detection quality and detection quantity. New performance graphs allow us to easily perceive the detection quantity (“how many objects have been detected?” and “how many false alarms have been detected?”) as well as detection quality (“how accurate is the detection of the objects?”).

• The influence of the data base is evaluated, i.e., the relationship between the performance of the detection algorithms and the structure of the image test database is put forward. This makes it easier to grasp the advantage an object detection algorithm might have when it is tested on an image collection which larger percentage of relevant information.

• The derivation of a single performance value which does not depend on quality related thresholds. Although this performance value, by definition, does not allow us to fully comprehend the behaviour of a detection algorithm, it makes it easier to create a ranking of the algorithms to evaluate.

<h2>CONCLUSION:</h2>

Our aim is to estimate accurate count of object in the image. So we are going to develop a program which detects the objects in an image.The program should automatically detect the desire object and count the number of objects in that image by detecting the edges of an image. We are going to estimate density of image whose integral over any image region gives us count of objects within that region.


