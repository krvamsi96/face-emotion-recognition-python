# face-emotion-recognition-python


## Description:
 Our Human face is having a mixed emotions so we are to demonstrate the probabilities of these emotions that we have.



## What does Emotion Recognition mean?
Emotion recognition is a technique used in software that allows a program to "read" the emotions on a human face using advanced image processing. Companies have been experimenting with combining sophisticated algorithms with image processing techniques that have emerged in the past ten years to understand more about what an image or a video of a person's face tells us about how he/she is feeling and not just that but also showing the probabilities of mixed emotions a face could has.

## Dependencies:
- pip install numpy.1.5
- pip install pandas.1.5
- pip install tensorflow.2.0
- pip install keras.2.0
- pip install opencv-python.4.3


## datasets
- Download kaggle dataset from here => https://www.kaggle.com/c/challenges-in-representation-learning-facial-expression-recognition-challenge/data
- Download haarcascades file from here=> https://github.com/opencv/opencv/blob/master/data/haarcascades/haarcascade_frontalface_default.xml

## Algorithm
 - First, the haar cascade method is used to detect faces in each frame of the webcam feed.
 - The region of image containing the face is resized to 48x48 and is passed as input to the CNN.
 - The network outputs a list of softmax scores for the seven classes of emotions.
 - The emotion with maximum score is displayed on the screen.
