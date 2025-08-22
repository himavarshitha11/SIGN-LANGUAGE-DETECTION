# SIGN-LANGUAGE-DETECTION 

This project is a real-time Sign Language Detection system that uses a webcam to recognize hand gestures and display the corresponding word on the screen.

It can help bridge the communication gap between people who use sign language and those who do not understand it.

📸 Example Output

When a user shows the sign for Hello, the system detects it and displays the word "Hello" on the screen.


⚙️ Features

Detects hand gestures in real-time using a webcam.

Converts gestures into text displayed on the screen.

Works with commonly used sign gestures.

Lightweight and runs on most laptops/desktops with a webcam.

🛠️ Technologies Used

Python 3.9

TensorFlow / Keras – Deep Learning model

OpenCV – Real-time video capture

MediaPipe / cvzone – Hand landmark detection

NumPy – Data processing

🚀 How to Run

Clone or download the project.

Install the required dependencies:

pip install tensorflow==2.9.1 opencv-python mediapipe cvzone numpy keras pyttsx3


Run the prediction script:

python prediction_wo_gui.py


The webcam will open. Show a hand gesture, and the system will display the detected word on the screen.

📂 Project Files

cnn8grps_rad1_model.h5 → Trained deep learning model.

final_pred.py → Script for running detection.

prediction_wo_gui.py → Script to test detection without GUI.

dataset collection scripts → Used to capture training data.

🔮 Future Improvements

Support for more sign gestures.

Add speech output (convert text to voice).

Improve accuracy with larger datasets.

🙌 Acknowledgement

This project is made for learning and research purposes to support sign language communication.
