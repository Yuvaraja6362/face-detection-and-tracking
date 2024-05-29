# Face Detection and Tracking

## Overview
This project involves developing a system for detecting and tracking faces in real-time video streams. It utilizes computer vision techniques and machine learning models to accurately identify and follow faces within a video frame.

## Features
- Real-time face detection
- Face tracking across multiple frames
- Support for multiple faces
- High accuracy and performance
- Easy integration with video feeds

## Requirements
To run this project, you need the following dependencies : 
- Python
- OpenCV
- Dlib
- NumPy
- SciPy
- imutils
- haarcascade_frontalface_default.xml

You can install these dependencies using pip :
 1. Install Pip Library
    sh
    pip install opencv-python dlib numpy scipy imutils


## Installation

1. Clone the repository
    sh
    git clone https://github.com/your-username/face-detection-and-tracking.git
    cd face-detection-and-tracking
    



2. Install dependencies
    sh
    pip install -r requirements.txt
    
## Haar cascade algorithm

The Haar Cascade is a machine learning object detection algorithm used to identify objects in images or video. The Haar Cascade algorithm was proposed by Viola and Jones in their paper "Rapid Object Detection using a Boosted Cascade of Simple Features" in 2001.

This haar cascade is available on github. A Haar Cascade works by training the cascade on thousands of negative images with the positive image superimposed on it.
## Usage
1. Run the application
    sh
    python main.py
    

2. Configuration
   - Modify config.py to set parameters like video source, detection thresholds, etc.

## Project Structure
face-detection-and-tracking/
│
├── models/                # Pre-trained models for face detection
├── examples/              # Example images and videos
├── face_detection_and_tracking.py   # Main script to run the application
├── requirements.txt       # List of dependencies
├── README.md              # Project documentation
└── LICENSE                # License information
## How It Works
1. Face Detection: The system uses pre-trained models to detect faces in each frame of the video.
2. Face Tracking: Detected faces are tracked across subsequent frames to maintain continuity.

## Contributing
Contributions are welcome! Please fork the repository and submit a pull request for any enhancements or bug fixes.

## License
This project is licensed under the MIT License. See the LICENSE file for more details.

## Contact
For any questions or feedback, please reach out to [ yuvaraja6362@gmail.com ].
