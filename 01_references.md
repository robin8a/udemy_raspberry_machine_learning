# References

## Articles
[We Built A Powerful Amazon Facial Recognition Tool For Under $10](https://www.forbes.com/sites/thomasbrewster/2018/06/06/amazon-facial-recognition-cost-just-10-and-was-worryingly-good/#5f409eb151db)
## Performance
Raspberry Pi performance:
 - Darknet(YOLO)
 - Tensorflow Google Object Detection (API)
 - Microsoft Embedded Learning Library (ELL)
 - Darknet-NNPACK
 - [SSD or YOLO on raspberry pi](https://stackoverflow.com/questions/42354824/ssd-or-yolo-on-raspberry-pi)

## Py Image Search

In this tutorial, you’ll learn how to use the YOLO object detector to detect objects in both images and video streams using Deep Learning, OpenCV, and Python.
- [YOLO object detection with OpenCV: ](https://www.pyimagesearch.com/2018/11/12/yolo-object-detection-with-opencv/)


In this tutorial, you will learn how to utilize YOLO and Tiny-YOLO for near real-time object detection on the Raspberry Pi with a Movidius NCS.
- [YOLO and Tiny-YOLO object detection on the Raspberry Pi and Movidius NCS](https://www.pyimagesearch.com/2020/01/27/yolo-and-tiny-yolo-object-detection-on-the-raspberry-pi-and-movidius-ncs/)


In today’s blog post you are going to learn how to perform face recognition in both images and video streams using:
- OpenCV
- Python
- Deep learning
As we’ll see, the deep learning-based facial embeddings we’ll be using here today are both (1) highly accurate and (2) capable of being executed in real-time.
- [https://www.pyimagesearch.com/2018/06/18/face-recognition-with-opencv-python-and-deep-learning/](https://www.pyimagesearch.com/2018/06/18/face-recognition-with-opencv-python-and-deep-learning/)

## Nanonets
This article has a good explanation of classification, training models with tensor flow and rapsberry pi integration. [RO] The problem is: is a private library

- [How to easily Detect Objects with Deep Learning on Raspberry Pi](https://nanonets.com/blog/how-to-easily-detect-objects-with-deep-learning-on-raspberry-pi/)


## Real Time Object Detection on Raspberry Pi using YOLO, Yad2k
The purpose of this project is to attach a USB camera to a Raspberri Pi and then automatically detect objects that the camera sees.
[RO] Also uses Docker, is quite interesting for DevOps
- [YOLO-Pi: Real Time Object Recognition on Raspberry Pi](https://github.com/CiscoBlockChain/YOLO-Pi)


## Fun DIY
References from [Raspberry forums](https://www.raspberrypi.org/forums/viewtopic.php?t=219601) TO
[Deep Learning with Raspberry Pi -- Real-time object detection with YOLO v3 Tiny! [updated on Dec 19 2018, detailed instruction included]](http://funofdiy.blogspot.com/2018/08/deep-learning-with-raspberry-pi-real.html)


## medium.com
The project requires tensorflow, keras, numpy and matplotlib to be installed on your raspberry pi.

- [Offline Object Detection and Tracking on a Raspberry Pi](https://medium.com/ml-everything/offline-object-detection-and-tracking-on-a-raspberry-pi-fddb3bde130)

# Create your own clasifier
Object Detection using Haar feature-based cascade classifiers is an effective object detection method proposed by Paul Viola and Michael Jones in their paper, "Rapid Object Detection using a Boosted Cascade of Simple Features" in 2001.
- [Tutorial Cascade Classifier](https://docs.opencv.org/trunk/db/d28/tutorial_cascade_classifier.html)


## Bottle Clasiffier

- [Bottle Classifier & Cocktail Resolver](https://github.com/jemgunay/bottle-classifier)

## Haar Clasifier
- [Github](https://github.com/opencv/opencv/tree/master/data/haarcascades)
- [Making your own Haar Cascade Intro - OpenCV with Python](https://www.youtube.com/watch?v=jG3bu0tjFbk)
- [Haar Cascade for image & video object classification - OpenCV w/ Python for Image Video Analysis 21](https://youtu.be/-Mhy-5YNcG4)

### Siraj Raval
- [Build a TensorFlow Image Classifier in 5 Min](https://youtu.be/QfNvhPx5Px8)

## Raspberry Pi camera
[Use a Raspberry Pi camera and a solenoid lock to create a door lock that unlocks when it recognizes your face!](https://maker.pro/raspberry-pi/projects/how-to-create-a-facial-recognition-door-lock-with-raspberry-pi)


- [[RO]Good for detectFace Recognition of single and multiple faces using Python](https://youtu.be/jNCcXyyie14)


- [Multiple Face Detection and Recognition for Attendance System](https://www.youtube.com/watch?v=QauP7q4FTzI)

# Training Tensor flow

- [How To Train an Object Detection Classifier Using TensorFlow (GPU) on Windows 10](https://youtu.be/Rgpfk6eYxJA)
- [AWS Tensor Flow, SageMaker, Machine Learning](https://youtu.be/HS7U6IugXmE)
- [AWS Innovate | Intro to Deep Learning: Building an Image Classifier on Amazon SageMaker](https://youtu.be/KCzgR7eQ3PY)


# Control Motors with Raspberry Pi
[RO] the controller (MBC) is sell in UK, the code is in github and has good examples for motor control, including protection ctrl+c interruption and turn-off the motor
- [Raspberry Pi - How to control motors.](https://youtu.be/JJXzlCK4vnY)

[RO] with Arduino operations:
for clock wise motion, delay for 3 sec Clock wise motion, for break, for anticlock wise

- [Control a DC Motor Using Arduino With L293D](https://www.instructables.com/id/Control-a-DC-Motor-Using-Arduino-With-L293D/)

[RO] this is it, simply to implement
- [Controlling a DC Motor with Raspberry Pi](https://www.electronicshub.org/controlling-a-dc-motor-with-raspberry-pi/)