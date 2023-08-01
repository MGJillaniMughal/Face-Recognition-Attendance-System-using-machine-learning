# Face Recognition Attendance System

Description:
Face Recognition Attendance System is a web app that uses machine learning to recognize human faces and mark their attendance. It detects faces in real-time using the webcam and compares them with known images to identify the person. The system records attendance in a CSV file along with the timestamp.

Features:
- Real-time face detection using webcam
- Face recognition using machine learning
- Attendance recording in a CSV file
- User-friendly web interface

Installation:
1. Clone the repository from GitHub:
   git clone https://github.com/MGJillaniMughal/Face-Recognition-Attendance-System-using-machine-learning.git

2. Navigate to the project directory:
   cd Face-Recognition-Attendance-System-using-machine-learning

3. Install the required libraries using `pip`:
   pip install -r requirements.txt

4. Run the app:
   python app.py

5. Open the web app in your browser:
   http://localhost:5000

Usage:
1. Open the web app in your browser.

2. Allow access to your webcam.

3. The app will detect and recognize faces in the video stream.

4. If a known face is detected, the system will mark the attendance for that person in the CSV file.

How it Works:
- The app loads known images of people along with their names.
- It encodes these images to create a face recognition model.
- The app captures video from the webcam and detects faces in real-time.
- For each detected face, it calculates its encoding and compares it with known encodings.
- If a match is found, the person's name is displayed, and their attendance is marked.

Technologies Used:
- Python
- OpenCV
- NumPy
- face_recognition
- HTML5
- CSS3
- Bootstrap
- JavaScript


Contributors:
- [Your Name](https://github.com/MGJillaniMughal) (Owner)

License:
This project is licensed under the MIT License - see the LICENSE file for details.
