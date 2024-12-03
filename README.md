# basic-object-detection
# Object Detection with MobileNet-SSD

This project demonstrates **real-time object detection** using the **MobileNet-SSD** model. It leverages OpenCV's DNN module to process live camera feeds and detect objects in real-time. The model is trained on the **COCO dataset** and can detect 20 common objects, including people, cars, animals, and more.

## Features

- Real-time object detection using the MobileNet-SSD model.
- Detects 20 classes of objects (e.g., person, car, dog, cat).
- Runs on live camera feeds (e.g., webcam or IP camera).
- Efficient and lightweight for real-time applications.

## Requirements

To run this project, you need to have the following dependencies installed:

- Python 3.x
- OpenCV (with DNN module support)

You can install the required Python libraries using pip:

pip install opencv-python
pip install opencv-python-headless


├── MobileNetSSD_deploy.caffemodel       # Pre-trained MobileNet-SSD model weights
├── MobileNetSSD_deploy.prototxt         # Model architecture
├── main.py                             # Python script to run object detection
├── README.md                           # Project documentation



## Licensing

- **MobileNet-SSD model**: Licensed under the [Apache 2.0 License](https://opensource.org/licenses/Apache-2.0).
- **COCO dataset**: Licensed under [CC BY 4.0 License](http://creativecommons.org/licenses/by/4.0/).
- **This project**: Licensed under the [MIT License](https://opensource.org/licenses/MIT).
