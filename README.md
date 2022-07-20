# Mouse Virtual
![](https://raw.githubusercontent.com/matahatiai/opencv_mouse_tracking/master/hand-tracking.png)
![](https://raw.githubusercontent.com/matahatiai/opencv_mouse_tracking/master/click.png)

In our continuing deep dive into practical real-time computer vision, we’ll show you how to code a hands-free webcam-based controller for your computer mouse using the OpenCV library on Python. This will allow you to control your computer without any physical peripheral required—Iron Man style!  In this session, we’ll first obtain our live camera feed using OpenCV and then estimate hand poses using MediaPipe Hands, an open-source framework that employs machine learning to infer 3D landmarks of the hand from single frames in real-time without any fancy hardware acceleration, working even on mobile phones. Following this, we’ll set up our simulated mouse movement in response to the poses using the AutoPy automation module.

### Import Library
import mediapipe as mp
import cv2
import numpy as np
import uuid
import os

## Prerequisites
### pip install: OpenCV , MediaPipe, AutoPy 
