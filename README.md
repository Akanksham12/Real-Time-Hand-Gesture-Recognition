# Real-Time-Hand-Gesture-Recognition
This project implements a real-time hand gesture recognition system using MediaPipe and TensorFlow. It uses the MediaPipe library to detect hand landmarks and a pre-trained TensorFlow model to recognize hand gestures.

## Installation

Before running the code, make sure to install the required libraries. Y
```bash
pip install opencv-python numpy mediapipe tensorflow
```

## Usage

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/your-username/hand-gesture-recognition.git
   cd hand-gesture-recognition
   ```

2. **Install Dependencies:**
   Install the required dependencies using the command mentioned above.

3. **Download Model and Names:**
   Download the pre-trained model file (`mp_hand_gesture`) and class names file (`gesture.names`). Place them in the project directory.

4. **Run the Code:**
   ```bash
   python hand_gesture_recognition.py
   ```
   This will initialize the webcam and start recognizing hand gestures.

## File Descriptions

- `hand_gesture_recognition.py`: Main Python script for hand gesture recognition.
- `mp_hand_gesture`: Pre-trained TensorFlow model for gesture recognition.
- `gesture.names`: Class names file.

## Libraries Used

- OpenCV (cv2): For image and video processing.
- NumPy: For numerical operations.
- MediaPipe: For hand landmark detection.
- TensorFlow: For deep learning-based hand gesture recognition.

