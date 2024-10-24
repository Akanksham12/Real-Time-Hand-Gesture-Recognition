# Gesture-Based Game using OpenCV, MediaPipe, and Pygame

This project is a gesture-controlled game that uses real-time hand tracking to move a player within a Pygame window. The player must avoid obstacles that fall from the top of the screen by using hand gestures captured through the webcam. The game utilizes computer vision through OpenCV and MediaPipe to track hand movements and gestures.

## Key Features

- **Gesture Recognition**: Hand gestures are tracked using MediaPipe's hand detection. The player's movements are controlled based on the position of the index finger.
- **Real-time Webcam Input**: The game uses OpenCV to capture live video from the webcam.
- **Game Mechanics**: Pygame handles the game interface, rendering the player and obstacles, detecting collisions, and displaying a "Game Over" screen with a restart option.
- **Obstacle Avoidance**: The player must avoid falling obstacles by moving left or right through gestures.

## Technologies Used

- **OpenCV**: For real-time video capture and processing.
- **MediaPipe**: For hand tracking and gesture recognition.
- **Pygame**: For rendering the game, handling collisions, and controlling game logic.
- **NumPy**: For generating random obstacle positions and handling numeric operations.
- **Python**: The programming language used to tie everything together.

## How to Run the Project

### Prerequisites

Make sure you have the following installed:
- Python 3.x
- OpenCV (`pip install opencv-python`)
- MediaPipe (`pip install mediapipe`)
- Pygame (`pip install pygame`)
- NumPy (`pip install numpy`)

### Running the Game

1. Clone this repository or download the source code.
   
   ```bash
   git clone https://github.com/your-username/gesture-game.git
   cd gesture-game
   
### Game Controls
Move Left: Move your hand's index finger to the left third of the screen.
Move Right: Move your hand's index finger to the right third of the screen.
Restart Game: Click the "Restart" button on the "Game Over" screen with the mouse.
