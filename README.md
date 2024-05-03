# Object Detection in RaspberryPi 4
## Introduction
Raspberry Pi is a series of small single-board computers (SBCs) developed in the United Kingdom by the Raspberry Pi Foundation in association with Broadcom. These can be used for smale scale end-to-end applications such as Object detection, face recoginition ,etc. with help of TinyML such as Tensorflow-lite and OpenCV. We can run pretrained models on Raspberry-Pi with ease.

TensorFlow Lite is set up on the Raspberry Pi and is used to run object detection model.

Hardware used:
- Raspberry Pi 4 (Raspian Buster OS)
- Web camera (USB) or picamera
- Display and micro HDMI cable
- Keyboard and Mouse (Optional)

The detection will provide in form of video stream providing name of detected object along with the probability in percentage. 

## How to run
- Setup Raspberry-Pi 4 
- Connect dispay and peripherals
- Open the terminal
- Go into the directory (assuming you have already downloaded the project from github)
- Run the script file :
  ```bash
  get_pi_requirements.sh
  ```
- Setup python virtual environment :
  ```bash
  python3 venv object_detection
  ```
- Activate virtual environment :
  ```bash
  source object_detection/bin/activate
  ```
- Run the python file using this command :
  ```bash
  python3 TFLite_detection_webcam.py --modeldir=Object_Detection_TFLite_model
  ```
  
