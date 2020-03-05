# Raspberry Pi Machine Learning

## Udemy course
Examples images tranformation
- Load
- Scaling
- Flipping
- Varying Brightness
- Bitwise
- Blurring
- Thresholding
- Erosion, dilatation
- Edge detection
- Segmentation

A set of scripts for image processing using raspberry pi:
- Detection Human, faces, eyes, nose 
- Detection Cars
- Pedestrian
- Object based on an image


## Getting Started
Connect to raspberry pi
```
pi@192.168.43.45
k4m4y18$

cd /op
```


### Prerequisites

What things you need to install the software and how to install them

- Raspberry Pi
- Raspberry camera connected
- Connect the raspberry via wifi same computer network

```
python3
pip python
opencv

```

#### On raspberry install the following:
```sh
sudo apt-get update  
sudo apt-get -y install python-pip 
sudo apt-get -y install python-git 
sudo apt-get -y install python-numpy 
sudo apt-get -y install python-scipy 
sudo apt-get -y install python-opencv 
sudo pip install --upgrade cython  
sudo pip install -U scikit-learn 
sudo pip install imutils 
sudo apt-get -y install python-sklearn
sudo apt-get -y install python-skimage

# List of packages installed
pip freeze
```

### Installing

#### Install OpenCV on Raspberry
Follow the following instructions complemented with the two links
- [Install OpenCV 4 on your Raspberry Pi](https://www.pyimagesearch.com/2018/09/26/install-opencv-4-on-your-raspberry-pi/)
- [Installing OpenCV on Raspberry Pi 3 B](https://www.alatortsev.com/2018/04/27/installing-opencv-on-raspberry-pi-3-b/)
- [Common errors using the Raspberry Pi camera module](https://www.pyimagesearch.com/2016/08/29/common-errors-using-the-raspberry-pi-camera-module/)
- [Test Raspberry Pi - Camera Tutorial](https://www.youtube.com/watch?v=T8T6S5eFpqE)

#### Phyton Virtual Environment
- [Installing packages using pip and virtual environments](https://packaging.python.org/guides/installing-using-pip-and-virtual-environments/)


End with an example of getting some data out of the system or using it for a little demo

## Running the tests

```sh
# Enable Environment
$ source ~/.profile
# Change Enviroment
$ workon cv 
# Enable openCV
sudo ln -s /usr/local/python/cv2 cv2
```

### Camera is enable

```sh
raspistill -v -o test.jpg
```
### Test video
```sh
sudo find . -name test_video.py
cd ~/opencv/pi-object-detection
python test_video.py
```

### Real time object detection
```sh
sudo find . -name real_time_object_detection.py
cd ~/opencv/pi-object-detection/
python real_time_object_detection.py --prototxt MobileNetSSD_deploy.prototxt.txt --model MobileNetSSD_deploy.caffemodel

python real_time_object_detection_person.py --prototxt MobileNetSSD_deploy.prototxt.txt --model MobileNetSSD_deploy.caffemodel

```

### Image processing scripts
```sh
cd /home/pi/opencv/udemy_raspberry_machine_learning/Codes/Image_processing_projects/Project_1-Human_Face_Eyes_Noise_Detection
python 5.1-Human_Face_Eyes_Nose_Detection.py

```

### Break down into end to end tests

Explain what these tests test and why

```
Give an example
```

### And coding style tests

Explain what these tests test and why

```
Give an example
```

## Deployment

Connect to SFTP Visual Code Studio and check the config such as:

```json
[
    {
        "name": "Raspberry on Kardun Object Detection",
        "host": "192.168.43.45",
        "protocol": "sftp",
        "port": 22,
        "username": "pi",
        "remotePath": "/home/pi/opencv/udemy_raspberry_machine_learning",
        "uploadOnSave": true
    }
]

```
This is for sync the scripts in raspberry

## Built With

* [Dropwizard](http://www.dropwizard.io/1.0.2/docs/) - The web framework used
* [Maven](https://maven.apache.org/) - Dependency Management
* [ROME](https://rometools.github.io/rome/) - Used to generate RSS Feeds

## Contributing

Please read [CONTRIBUTING.md](https://gist.github.com/PurpleBooth/b24679402957c63ec426) for details on our code of conduct, and the process for submitting pull requests to us.

## Versioning

We use [SemVer](http://semver.org/) for versioning. For the versions available, see the [tags on this repository](https://github.com/your/project/tags). 

## Authors

* **Robin Ochoa** - *Initial work* - [PurpleBooth](https://github.com/PurpleBooth)

See also the list of [contributors](https://github.com/your/project/contributors) who participated in this project.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

* Hat tip to anyone whose code was used
* Inspiration
* etc
