Eyes Tracking Part 1
  -Detecting face landmarks with Mediapipe 👨‍💻
  -Detecting Eyes Landmarks 👁️‍🗨️ 👁️‍🗨️
  -Draw Eyes,Eyebrows, lips and Face Oval with transparent shapes.

Eyes Tracking Part 2
  -Detecting the blinks
  -Counting Blinks

Eyes Tracking Part 3
  -Extracting Eyes from the frame using Masking techniques
  -Thresholding Eyes to get black ⚫ and white ⚪ pixels separated
  -Dividing Each Eye into three 3️⃣ pieces, right_piece, center_piece, left_piece
  -Counting the Black Pixel in each piece, and estimating position.

Eyes Tracking Part 4
  -Voice position indicator using pygame.

Eyes Tracking :-     
My major application, named "EyeTrack," employed Mediapipe and OpenCV for real-time eye tracking.

Functionality:
EyeTrack detected and tracked the movement of a person's eyes in real-time using a computer's camera.

Inputs:
Video feed from a camera capturing the user's face.
Real-time image frames for eye detection.

Outputs:
Real-time display of the detected eyes.
Eye movement tracking coordinates.

Tech Stack:
Mediapipe for facial landmark detection.
OpenCV for image processing and visualization.

Main Challenges:
Accuracy: Ensuring precise eye tracking across varying lighting and head angles.
Real-Time Processing: Achieving low-latency eye tracking to provide real-time feedback.
User Interface: Designing a simple and intuitive interface to visualize eye movement.
Hardware Compatibility: Ensuring the application worked on a variety of camera setups.
Calibration: Implementing an accurate calibration process for different users.
EyeTrack demonstrated the potential of computer vision technologies in applications like gaze tracking, with applications in fields such as human-computer interaction and accessibility.
