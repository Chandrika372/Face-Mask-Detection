# Face-Mask-Detection
<br></br>
Mask Detection using OpenCV
<br></br>
<b>Prerequisites</b>
<br>OpenCV</br>
Numpy

<b>Methodology</b>
<br>1.Place some test images in Test folder that we want to predict in the facemask.py file.</br>
<br>2.Place images for training the classifier in MaskTraining folder. Here, two types of recognizations are done, nanely "Mask" and "No mask".
We add pictures of each category in seperate folders within the Train folder and label them as 0 and 1.
We add names to these labels in the facemask.py file in the "name" variable.</br>
<br>3.The face.py file on being run generates training.yml file that would be used in the test.py script.</br>
<br>4.We use the facemask.py script for predicting mask on face realtime via the webcam.</br>
