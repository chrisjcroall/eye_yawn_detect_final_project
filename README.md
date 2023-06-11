# eye_yawn_detect_final_project
Implementing an eye-yawn detection system using machine learning libraries and algorithms, can analyze the driver's gaze direction and determine whether their attention is focused on the road ahead or diverted elsewhere or under the influence.


![Screenshot 2023-06-11 215252](https://github.com/chrisjcroall/eye_yawn_detect_final_project/assets/126267745/c187a7d0-3e94-4f42-afcb-c64b9f858917)


This project is an implementation of a fatigue detection system using computer vision techniques. It detects drowsiness and yawning in a person's face using a webcam or a video file as input.

The code uses several libraries such as OpenCV (cv2), dlib, pygame, and time. It initializes the pygame mixer for playing sound alerts. It also loads a pre-trained face detector and facial landmark predictor using dlib.

The code defines functions to calculate the eye aspect ratio (eye_aspect_ratio), detect closed eyes (detect_closed_eyes), and detect yawning (detect_yawn). These functions utilize the facial landmarks provided by the predictor to analyze the eyes and mouth regions.

The main part of the code reads video frames from a webcam or video file, converts them to grayscale, and displays them in a resizable window. It then uses the face detector to detect faces in the frame. For each detected face, it applies the eye and yawning detection functions, calculates various metrics, and updates the display accordingly. It also plays sound alerts and keeps track of detection counts.


![Untitled video - Made with Clipchamp](https://github.com/chrisjcroall/eye_yawn_detect_final_project/assets/126267745/3d19063b-bd9b-4eb9-a601-70529d4b6bd3)


The code continues this process until the user exits by pressing 'q'. Finally, it releases the video capture and closes the windows.

In conclusion, this code demonstrates a basic implementation of a fatigue detection system using computer vision techniques.
