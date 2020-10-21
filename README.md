# Face-Counting-Challenge
The method of face detection in pictures is complicated because of variability present across human faces such as pose, expression, position and orientation, skin colour, the presence of glasses or facial hair, differences in camera gain, lighting conditions, and image resolution.

Object detection is one of the computer technologies, which connected to the image processing and computer vision and it interacts with detecting instances of an object such as human faces, building, tree, car, etc. The primary aim of face detection algorithms is to determine whether there is any face in an image or not. We challenge all the hackers to participate in this computer vision challenge that aims to test skills in deep learning and object detection.

# Problem Statement
People detection and head counting is one of the classical albeit challenging computer vision application. For this problem, given a group selfie/photo, you are required to count the number of heads present in the picture. You are provided with a training set of images with coordinates of bounding box and head count for each image and need to predict the headcount for each image in the test set.

# Data
https://datahack.analyticsvidhya.com/contest/vista-codefest-computer-vision-1/#ProblemStatement
1. train.zip: Contains 2 csvs and 1 folder containing image data
  1. train.csv - ['Name', 'HeadCount'] (contains headcount value for each training image)
  2. bbox_train.csv - ['Name', 'width', 'height' , 'xmin', 'ymin', 'xmax', 'ymax', 'class'] (contains co-ordinates of each head in the train image, located by the          formation of a bound-box around the head)
3. test.csv - ['Name'] (contains only name of testing images)

