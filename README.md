# Faceattendence-Project

# Face Recognition Attendance System

This repository contains code for a simple face recognition attendance system using OpenCV and scikit-learn.

## Overview

The face recognition attendance system utilizes the K-Nearest Neighbors (KNN) algorithm for recognizing faces captured through a webcam. It detects faces in real-time using Haar cascades, predicts the identity of the person, and records their attendance along with timestamp in a CSV file.

## Requirements

- Python 3.x
- OpenCV
- scikit-learn
- win32com (for Windows text-to-speech functionality)

## Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/your_username/face-recognition-attendance-system.git
    cd face-recognition-attendance-system
    ```

2. Install the required Python packages:

    ```bash
    pip install -r requirements.txt
    ```

3. Download the Haar cascade XML file for face detection and place it in the project directory.

4. Prepare the face dataset: 

    - Collect images of individuals to be recognized and store them in the `data/faces` directory.
    - Label each image with the name of the individual and ensure they are stored in separate folders.

5. Train the model:

    - Run the `train_model.py` script to train the KNN classifier on the face dataset.

6. Run the attendance system:

    - Execute the `attendance_system.py` script to start the attendance system.

## Usage

- Press 'o' to take attendance for the recognized faces.
- Press 'q' to quit the application.

## Contributors

- Ajay Kumar(https://github.com/your_username)

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
