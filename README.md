<h1 style="font-weight:900; color:black;">✋ Sign Language Detection System</h1>

A real-time system that detects hand gestures through your webcam and converts them into text — built using Python, TensorFlow, OpenCV, and MediaPipe.

---

<h1 style="font-weight:900; color:black;">🔍 Overview</h1>

This project captures your hand gestures using the webcam and predicts the corresponding sign language word on the screen.

It is designed to help bridge communication between sign language users and non-signers.

---

<h1 style="font-weight:900; color:black;">📸 Example Output</h1>

When you show the gesture for **Hello**, the system detects it and displays the word:

![Sample Output](screenshot.png)

---

<h1 style="font-weight:900; color:black;">⚙️ Features</h1>

✅ Real-time gesture detection using webcam  
✅ Converts sign gestures into text on screen  
✅ Works with common signs like **Hello**  
✅ Lightweight and runs on most laptops/desktops  

---

<h1 style="font-weight:900; color:black;">🛠️ Tech Stack</h1>

- Python 3.9  
- TensorFlow / Keras – Deep Learning Model  
- OpenCV – Webcam video capture  
- MediaPipe / cvzone – Hand landmark detection  
- NumPy – Data processing  

---

<h1 style="font-weight:900; color:black;">🚀 How to Run</h1>

1. Clone or download the project.  
2. Install required dependencies:  
   ```bash
   pip install tensorflow==2.9.1 opencv-python mediapipe cvzone numpy keras pyttsx3
Run the detection script:

bash
Copy
Edit
python prediction_wo_gui.py
The webcam will open. Show a sign gesture and the system will display the detected word.

<h1 style="font-weight:900; color:black;">📂 Project Files</h1>
cnn8grps_rad1_model.h5 → Trained CNN model

final_pred.py → Real-time detection script

prediction_wo_gui.py → Run detection without GUI

dataset collection scripts → Used for capturing training data

<h1 style="font-weight:900; color:black;">🔮 Future Improvements</h1>
✨ Add more sign gestures
✨ Improve accuracy with larger datasets
✨ Add text-to-speech for detected words

<h1 style="font-weight:900; color:black;">🙌 Acknowledgement</h1>
This project was developed as part of a learning exercise to explore computer vision, deep learning, and human-computer interaction.
