# Face-Detection

This Python script demonstrates real-time face detection using the OpenCV library. It captures video from the default camera of your system and detects faces using a pre-trained Haar Cascade classifier.

## Requirements

- Python 3.x
- OpenCV library (cv2)

## Installation

1. Make sure you have Python installed on your system. You can download it from [python.org](https://www.python.org/downloads/).

2. Install OpenCV library using pip:
   #pip install opencv-python

## Python face_detection.py

3. A new window will open showing the live video feed from your default camera with face detection overlays.

4. Press 'a' key to exit the program.

## File Description

- `face_detection.py`: Python script containing the code for real-time face detection.

- `haarcascade_frontalface_default.xml`: Pre-trained Haar Cascade classifier for detecting frontal faces. You may need to adjust the file path if it differs on your system.

## Customization

- You can customize the parameters of the `detectMultiScale` function to adjust the sensitivity and accuracy of face detection.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

