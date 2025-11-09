# Edge-Linking-using-Hough-Transformm
## Aim:
To write a Python program to detect the lines using Hough Transform.

## Software Required:
Anaconda - Python 3.7

## Algorithm:
### Step1:

Import all the necessary modules for the program.
### Step2:

Load a image using imread() from cv2 module.
### Step3:

Convert the image to grayscale.
### Step4:

Using Canny operator from cv2,detect the edges of the image.
### Step5:

Using the HoughLinesP(),detect line co-ordinates for every points in the images.Using For loop,draw the lines on the found co-ordinates.Display the image.

## Output

### Input image 
<img width="527" height="384" alt="image" src="https://github.com/user-attachments/assets/8a40e380-739e-4536-8463-da35633bc7cd" />

### grayscale image
<img width="541" height="379" alt="image" src="https://github.com/user-attachments/assets/aad91605-6f09-403c-8287-689a273da4aa" />


### Canny Edge detector output
<img width="526" height="368" alt="image" src="https://github.com/user-attachments/assets/41e3df5e-c92b-4a34-8a27-84859456bcfe" />


### Display the result of Hough transform
<img width="533" height="380" alt="image" src="https://github.com/user-attachments/assets/8331520e-639e-46e7-861b-fc9b9898b1e3" />

## Result:
Thus the program is written with Python and OpenCV to detect lines using Hough transform.
