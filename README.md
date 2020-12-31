# Face-Mask-Detection
Mask Detection using OpenCV
-<b>Prerequisites</b>
-OpenCV
-Numpy
-
-
-
-
-<b>Methodology</b>
-
->b>1.</b>Place some test images in Test folder that we want to predict in the facemask.py file.
-<b>2.</b>Place images for training the classifier in Train folder. Here, two types of recognizations are done, nanely "Mask" and "No mask".
-We add pictures of each category in seperate folders within the Train folder and label them as 0 and 1. 
-We add names to these labels in the facemask.py file in the "name" variable.
-<b>3.</b>The face.py file on being run generates training.yml file that would be used in the facemask.py script.
-<b>4.</b>We use the facemask.py script for predicting mask on face realtime via the webcam.
