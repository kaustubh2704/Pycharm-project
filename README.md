Title

Face Detection Using OpenCV and Streamlit

🎯 2. Objective
The objective of this project is to build a system that can detect human faces in real-time using a webcam or from uploaded images using computer vision techniques.

🧠 3. Problem Statement
In many applications like security systems, attendance systems, and social media filters, detecting human faces is an important task.
This project aims to automatically detect faces using image processing.

🛠️ 4. Technologies Used
Python
OpenCV (Computer Vision)
NumPy
Streamlit (Web UI)
PIL (Image Processing)
⚙️ 5. Methodology

1: Image Input
Capture image from webcam OR upload image

2: Preprocessing
Convert image into grayscale using OpenCV

3: Face Detection
Use Haar Cascade Classifier (pre-trained model)
Detect faces using detectMultiScale()

4: Output
Draw rectangles around detected faces
Display result using Streamlit or OpenCV window

6. Working
User opens the application
Chooses either:
Open Camera
Upload Image
System processes the image
Faces are detected and highlighted
Output is displayed on screen

7. Features
Real-time face detection using webcam
Detect faces from uploaded images
Simple and interactive UI
Fast and efficient processing

8. Project Structure
Face-Detection-Project/
face.py
requirements.txt
README.md

9.Limitations
Works best with frontal faces
Accuracy may decrease in low lighting
Cannot recognize person identity (only detection)

10. Future Scope
Add face recognition (identify person)
Improve accuracy using deep learning (CNN)
Deploy on web for public use

11. Conclusion
This project successfully detects human faces using OpenCV. It demonstrates how computer vision can be used in real-time applications with a simple and efficient approach.

Output:
<img width="1103" height="688" alt="Screenshot 2026-04-19 211256 - Copy" src="https://github.com/user-attachments/assets/4c7d9bb4-0a75-4f46-a579-459e7e36fc45" />


13. Author
14. 
Kaustubh Manjarekar
