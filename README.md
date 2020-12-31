# Face-Mask-Detection
Mask Detection using OpenCV
<b>Prerequisites</b>
OpenCV
Numpy

../Methodology
1.Place some test images in Test folder that we want to predict in the facemask.py file.
2.Place images for training the classifier in Train folder. Here, two types of recognizations are done, nanely "Mask" and "No mask".
We add pictures of each category in seperate folders within the Train folder and label them as 0 and 1. 
We add names to these labels in the facemask.py file in the "name" variable.
3.The face.py file on being run generates training.yml file that would be used in the facemask.py script.
4.We use the facemask.py script for predicting mask on face realtime via the webcam.
