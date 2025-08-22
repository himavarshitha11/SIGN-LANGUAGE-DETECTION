##SIGN LAGUAGE DETECTION

A real-time system that detects hand gestures through your webcam and converts them into text — built using Python, TensorFlow, OpenCV, and MediaPipe.

#🔍 Overview

This project captures your hand gestures using the webcam and predicts the corresponding sign language word on the screen.

It is designed to help bridge communication between sign language users and non-signers.

#📸 Example Output

When you show the gesture for Hello, the system detects it and displays the word:


(Sample detection result)

#⚙️ Features

✅ Real-time gesture detection using webcam
✅ Converts sign gestures into text on screen
✅ Works with common signs like Hello
✅ Lightweight and runs on most laptops/desktops

#🛠️ Tech Stack

Python 3.9

TensorFlow / Keras – Deep Learning Model

OpenCV – Webcam video capture

MediaPipe / cvzone – Hand landmark detection

NumPy – Data processing

#🚀 How to Run

Clone or download the project.

Install required dependencies:

pip install tensorflow==2.9.1 opencv-python mediapipe cvzone numpy keras pyttsx3


Run the detection script:

python prediction_wo_gui.py


The webcam will open. Show a sign gesture and the system will display the detected word.

#📂 Project Files

cnn8grps_rad1_model.h5 → Trained CNN model

final_pred.py → Real-time detection script

prediction_wo_gui.py → Run detection without GUI

dataset collection scripts → Used for capturing training data

#🔮 Future Improvements

✨ Add more sign gestures
✨ Improve accuracy with larger datasets
✨ Add text-to-speech for detected words

#🙌 Acknowledgement

Built for learning and research to support Sign Language communication.
