# Live Face Detection

## Live Face Detection in Computer Vision
### 1. What is Live Face Detection?
- Live face detection involves the real-time identification of human faces within digital images, particularly in live video streams. Unlike static face detection, which works on still images, it continuously analyzes video frames to locate and identify faces.

### 2. Role in Computer Vision
- Face detection is a fundamental component of computer vision, a field of AI that enables computers to interpret and understand the visual world. Using digital images from cameras and videos, computer vision systems can accurately identify and classify objects, and react based on what they "see."

### 3. Techniques and Algorithms
- **Haar Cascades:** An object detection method used in the script, effective for face detection in images or video streams.
- **Deep Learning:** Advanced face detection systems often utilize deep learning algorithms, like convolutional neural networks (CNNs), for more accurate and robust detection in diverse environments.

## Introduction
Live Face Detection is a Python application that uses OpenCV for real-time face detection in video streams. It employs the `haarcascade_frontalface_default.xml` classifier for detecting faces in live video, showcasing the integration of computer vision and AI techniques.

## Prerequisites
- Python 3.x
- OpenCV library 
- `haarcascade_frontalface_default.xml` file (included)

## Installation
1. **Install Python**: Ensure Python 3.x is installed on your system. [Official Python website](https://www.python.org/downloads/).
2. **Install OpenCV**: Install using pip:
```bash
pip install opencv-python
```
3. **Clone the Repository**: Download or clone this repository to your local machine.
4. **Haarcascade File**: Ensure the `haarcascade_frontalface_default.xml` file is in the same directory as the script.

## Usage
Run the application simply by clicking on the run button, or by typing in the Python shell : 
 `python main.py ` .The application accesses the webcam, highlighting detected faces with rectangles. Press 'q' to quit.

## Troubleshooting
- Check webcam connection and accessibility.
- Verify installation of prerequisites.
- Ensure the `haarcascade_frontalface_default.xml` file is correctly placed.

## Next step
Now you can create your own AI program for Live Face Detection!
