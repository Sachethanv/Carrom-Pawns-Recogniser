# Carrom-Pawns-Recogniser
This project implements a Carrom Pawn Recogniser using computer vision and machine learning to detect and classify carrom pawns in real-time. It uses the YOLO object detection model to identify black, white, and queen pawns, track their positions, and automate scoring, offering gameplay analysis and insights. Built with Python and OpenCV.
Carrom-Pawns-Recogniser
This project implements a Carrom Pawn Recogniser using computer vision and machine learning techniques to detect and classify carrom pawns in real-time. The system leverages the YOLO (You Only Look Once) object detection model to identify and classify different types of pawns (black, white, and queen) on a carrom board. It can track their positions during the game, helping to automate scoring and provide insights for gameplay analysis.

Features
Real-Time Pawn Detection: Detect and classify carrom pawns during the game in real-time through a live camera feed.
Pawn Classification: Classifies pawns into categories such as black, white, and queen.
Position Tracking: Tracks the positions of pawns and their movements on the board, which can be useful for scoring and game analysis.
Automated Scoring: Automates scoring by recognizing which pawns are potted or moved.
Game Insights: Provides visual feedback and insights for players about the current game state.
Technologies Used
Python: The primary programming language for this project.
YOLO (You Only Look Once): A real-time object detection model for detecting pawns in images.
OpenCV: A computer vision library used for image processing and video stream handling.
TensorFlow/Keras: For implementing and fine-tuning the YOLO model.
