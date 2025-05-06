Age and Gender Detection System
Overview

This repository contains a deep learning-based system for detecting age and gender from facial images in real-time. The system uses pre-trained Caffe models for accurate classification and OpenCV for face detection.
Project Structure
Core Files

    Age_Gender_Detection.ipynb: Jupyter notebook with the complete implementation

    age_deploy.prototxt: Age model architecture definition

    age_net.caffemodel: Pre-trained age detection model weights

    gender_deploy.prototxt: Gender model architecture definition

    gender_net.caffemodel: Pre-trained gender detection model weights

Face Detection Models

    opencv_face_detector.pbtxt: Face detector configuration

    opencv_face_detector_uint8.pb: Pre-trained face detection model

Sample Images

    girl1.jpg, kid1.jpg, kid2.jpg, man1.jpg, man2.jpg, woman1.jpg: Test images for demonstration

Features

    Real-time age and gender detection from:

        Webcam feed

        Static images

        Video files

    Age prediction in 8 age ranges:

        0-2, 4-6, 8-12, 15-20, 25-32, 38-43, 48-53, 60-100

    Gender classification (Male/Female)

    Face detection using OpenCV's DNN module

    Visualization of results with bounding boxes and labels

Technologies Used

    Python 3.x

    OpenCV (cv2)

    Caffe models

    NumPy

    Matplotlib

    Jupyter Notebook
