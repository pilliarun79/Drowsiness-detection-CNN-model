# Deep-learning--drowsiness-detection---CNN-model



**Research problem :**

Drowsy driving accounts for about 10% of all traffic accidents, placing not just the driver but also others on the road in danger. Due to extensive journeys and irregular work patterns, this is particularly common among heavy vehicle drivers. Many researchers are looking into the factors that cause drivers to fall asleep while driving, and many mechanical advancements are being made to ensure driver safety in the event of an accident. However, this does not prevent the driver from becoming drowsy, and the main problem is to prevent or alert the driver from becoming drowsy.


**Research question :**

How deep learning techniques can detect drivers’ physical activity and alerts the driver when he/she feels drowsiness?



**Solution :**

Deep learning models can recognise a wide range of human activities and can process images from a webcam to determine the driver's status. First, a series of physical patterns of the driver are taught to CNN models so that they can learn how the driver's physical activity and facial expressions change when he/ she is driving normally, and then a live feed from the webcam is sent to machine learning models to compare the facial changes, it can tell if the driver is drowsy and alert by comparing at specific facial landmarks.

Instructions to run this project :

** Pre-Requisities: **

Below are the libraries that needs to be installed in the project environment but not in the base environment of the acandonda.

Opencv
Tensorflow
Dlib
Keras
Numpy
Pygame


** I have organised all the necessary files as below :**

Main_code : In this folder we have haar cascade files which are also available on the internet, I have taken all the available one and used only few for this project. so, dont be confused by looking at the files.

Next is drowsiness model training.ipynb file is the CNN trained model file which helps you to understand about how model is trained to detect the closed eyes below are some model results, drowsiness_detection is the main file which you can run from your cmd to test this project.

![drow-model-evaluation](https://user-images.githubusercontent.com/60965823/198892341-eb6511db-39b2-43fb-913e-c2599c06667c.PNG)

![drow-model-summary](https://user-images.githubusercontent.com/60965823/198892343-092ca998-6a17-4696-839e-df62f9c2f529.PNG)


Model: In this folder i have saved all the trained model files during testing and training times, so you might not need it, but can be used for experiment purpose.

Steps: In this folder i have python files which helps to understand my step by step leanring process to execute this project. again these can be used for experiment purpose.
