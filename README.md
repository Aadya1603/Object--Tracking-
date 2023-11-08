# Object Tracking Code

This repository contains a Python script for real-time object tracking using OpenCV.

## Getting Started

To run the object tracking code, follow these steps:

1. Install the required libraries, including OpenCV, on your Python environment.

2. Clone this repository to your local machine.

3. Run the Python script.

```bash
python object_tracking.py
```
A window will open, showing your webcam feed. Select an object to track by drawing a bounding box around it.

The script will then track the object in real-time and display the tracking results on the screen.

To stop tracking, press the 'q' key.

Dependencies
This code relies on the following Python libraries:

OpenCV
You can install these dependencies using the following command:
```
pip install opencv-python
```
Usage
The script allows you to track objects in real-time using your webcam. You can select the object to track by drawing a bounding box around it in the initial frame. The script will then track the object and display the tracking results on the screen.

Tracker Selection
By default, the code uses the CSRT tracker. You can switch to the MOSSE tracker by uncommenting the appropriate line and commenting out the CSRT tracker line.

```
# tracker = cv2.legacy.TrackerMOSSE_create()
# tracker = cv2.TrackerCSRT_create()




```
License
This project is licensed under the MIT License - see the LICENSE file for details.
