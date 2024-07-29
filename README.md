FaceIt

FaceIt is a facial recognition system project developed in Python. This project captures 100 pictures of an individual's face during the enrollment process and matches the face every time the code is run to authenticate the person.

Features

- Enrollment: Captures 100 images of the user's face for accurate recognition.
- Recognition: Matches the user's face with the enrolled images for authentication.
- User-friendly: Simple and intuitive interface for easy enrollment and recognition.

Requirements

- Python 3.x
- OpenCV
- NumPy
- dlib

Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/FaceIt.git
   cd FaceIt


Usage

1. Enroll a new user:
   ```bash
   python create_data.py


  Follow the on-screen instructions to capture 100 images of the user's face.

2. Recognize a user:
   ```bash
   python faceRecognition.py

  The script will match the face with the enrolled images and authenticate the user.

File Structure

FaceIt/
├── data/
│   ├── enrolled_faces/
│   └── ...
├── enroll.py
├── recognize.py
├── requirements.txt
└── README.md

- data/: Directory to store enrolled face images.
- enroll.py: Script for enrolling a new user.
- recognize.py: Script for recognizing and authenticating a user.
- requirements.txt: List of required packages.

Contributing

Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes.

License

This project is licensed under the MIT License. See the LICENSE file for details.

Acknowledgments

- OpenCV: https://opencv.org/
- dlib: http://dlib.net/

Contact

For any questions or suggestions, please open an issue or contact me at vinu.naruni@gmail.com
---

Feel free to customize the README file further to suit your project's specific details and needs.
