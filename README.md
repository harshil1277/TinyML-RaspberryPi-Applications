# Object Detection in RaspberryPi 4
## Introduction
Raspberry Pi is a series of small single-board computers (SBCs) developed in the United Kingdom by the Raspberry Pi Foundation in association with Broadcom. These can be used for smale scale end-to-end applications such as Object detection, face recoginition ,etc. with help of TinyML such as Tensorflow-lite and OpenCV. We can run pretrained models on Raspberry-Pi with ease.

TensorFlow Lite is set up on the Raspberry Pi and is used to run object detection model.

Hardware used:
- Raspberry Pi 4 (Raspian Buster OS)
- Web camera
- Display and micro HDMI cable
- Keyboard and Mouse

The detection will provide the name of detected object along with the accuracy in percentage.

## How to run
- Setup Ras
- Connect dispay and peripherals
- Open the terminal
- Go into th directory (assuming you have already downloaded the project)
- Run the script file : _bash get_pi_requirements.sh_
- Setup python virtual environment : _python3 venv object_detection_
- Activate virtual environment : _source object_detection/bin/activate_
- Run the python file using this command : __
