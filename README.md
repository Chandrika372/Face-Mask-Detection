# Face-Mask-Detection
<br></br>
Mask Detection using OpenCV
<br><b>Prerequisites</b></br>
<br>OpenCV</br>
<br>Numpy</br>
<br></br>
<br></br>
<b>Methodology</b>
<br></br>
<br>1.Place some test images in Test folder that we want to predict in the facemask.py file.</br>
<br>2.</b>Place images for training the classifier in Train folder. Here, two types of recognizations are done, nanely "Mask" and "No mask".<?br>
<br>We add pictures of each category in seperate folders within the Train folder and label them as 0 and 1. </br>
<br>We add names to these labels in the facemask.py file in the "name" variable.</br>
<br>3.The face.py file on being run generates training.yml file that would be used in the facemask.py script.</br>
<br>4.We use the facemask.py script for predicting mask on face realtime via the webcam.</br>
