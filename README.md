# project-face-recon

## Face Detection using OpenCV in Google Colab

This project demonstrates face detection in real-time images using OpenCV's deep learning module. The implementation runs in a Google Colab environment and uses a pre-trained model for face detection.

## Features
- Capture images directly from the webcam using the browser.
- Detect faces in the captured image using OpenCV's DNN module and a pre-trained Caffe model.
- Display the detected faces with bounding boxes and confidence scores.

## Requirements
To run this project, you need the following dependencies:
- Python 3
- Google Colab
- OpenCV
- Imutils
- Numpy

All required packages are pre-installed in Google Colab.

## How to Run
1. Open the Jupyter notebook `face.ipynb` in Google Colab.
2. Run the cells sequentially to execute the code.
3. When prompted, use the webcam interface to capture a photo.
4. The script will process the image and display it with detected faces.

## Model Details
This project uses the following files for face detection:
- `deploy.prototxt`: Defines the architecture of the deep learning model.
- `res10_300x300_ssd_iter_140000.caffemodel`: Pre-trained model weights.

The files are automatically downloaded during execution using the following commands:
```bash
!wget -N https://raw.githubusercontent.com/opencv/opencv/master/samples/dnn/face_detector/deploy.prototxt
!wget -N https://raw.githubusercontent.com/opencv/opencv_3rdparty/dnn_samples_face_detector_20170830/res10_300x300_ssd_iter_140000.caffemodel

