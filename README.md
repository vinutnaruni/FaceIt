FaceIt

FaceIt is a facial recognition system project written in Python. This project captures 100 pictures of an individual during the enrollment phase and matches the captured image with the enrolled images every time the code is run. 

Table of Contents

- Introduction
- Features
- Installation
- Usage
- Project Structure
- Contributing
- License

Introduction

FaceIt leverages machine learning and computer vision techniques to recognize faces. It is built using Python and utilizes OpenCV for image processing tasks. The system captures 100 images of a person's face during enrollment and matches these images with the person during recognition.

Features

- Enrollment: Capture 100 images of a person's face for accurate recognition.
- Recognition: Match real-time images with the enrolled images to identify the person.
- Camera Integration: Support for capturing images using a webcam or IP camera.
- Configurable: Easily modify the number of images to capture or change the camera settings.

Installation

To get started with FaceIt, follow these steps:

1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/FaceIt.git
    cd FaceIt
    ```

2. Install the required packages:
    ```bash
    pip install -r requirements.txt
    ```

Usage

Enrollment

To enroll a new person, run the `create_data.py` script. This script will capture 100 images of the person's face and store them in the `dataset` folder.

```bash
python create_data.py
```


Recognition

To recognize a person, run the `face_recognize.py` or `faceRecognition.py` script. This script will use the images captured during enrollment to identify the person in real-time.

```bash
python face_recognize.py
```

or

```bash
python faceRecognition.py
```

IP Camera

To use an IP camera for recognition, run the `ipcam.py` script.

```bash
python ipcam.py
```

Project Structure

```
FaceIt/
│
├── create_data.py                 # Script to capture images for enrollment
├── face_recognize.py              # Script for face recognition
├── faceRecognition.py             # Alternative script for face recognition
├── ipcam.py                       # Script to use IP camera for recognition
├── functional_representation.txt  # Description of the functional flow
├── haarcascade_frontalface_default.xml  # Haarcascade file for face detection
├── dataset/                       # Folder containing the captured images
│
└── README.md                      # Project README file
```


Contributing

Contributions are welcome! If you have any improvements or suggestions, feel free to create a pull request or open an issue.


