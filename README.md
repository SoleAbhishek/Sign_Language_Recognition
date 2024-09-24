# Sign Language Recognition using OpenCV
## Overview

This project is designed to recognize and convert hand gestures into text using a webcam feed. It leverages computer vision techniques to detect hands and machine learning to classify the gestures into corresponding letters of the sign language alphabet.

## Features

- Real-time hand gesture recognition using OpenCV and CVZone.
- Utilizes a pre-trained TensorFlow model for gesture classification.
- Displays the recognized sign language letter on the webcam feed.

## Requirements

To run this project, you need to have the following packages installed:

- Python 3.x
- OpenCV
- NumPy
- TensorFlow
- CVZone

You can install the required packages using pip:

```bash
pip install opencv-python numpy tensorflow cvzone
```

## How to Run

1. Ensure your webcam is connected and working.
2. Clone the repository or download the project files.
3. Navigate to the project directory in your terminal.
4. Run the main Python script:

   ```bash
   python test.py
   ```

5. Perform gestures in front of the webcam, and the recognized sign will be displayed on the screen.

## How It Works

1. The program captures video from the webcam.
2. It detects the hand using the HandDetector from CVZone.
3. The detected hand's bounding box is extracted and preprocessed.
4. The processed image is classified using the pre-trained model.
5. The recognized letter is displayed on the video feed.

## Publications

You can view my published journal here: [Sign Language Recognition Using OpenCV](https://ieeexplore.ieee.org/document/10369046).
