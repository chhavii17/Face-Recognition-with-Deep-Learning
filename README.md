# Face Recognition Real-Time Attendance System
This project is a real-time attendance system that uses facial recognition to identify students and mark their attendance. The system displays student information and their photos upon successful recognition, all managed through a Firebase backend.

## Features
* **Real-Time Recognition:** Detects and recognizes faces from a live webcam feed.
* **Firebase Integration:** Uses Firebase Realtime Database for student data and Firebase Storage for student images.
* **Automatic Attendance:** Marks attendance and updates the last attended time in the database.
* **UI Display:** Shows student details like name, major, and total attendance on a clean interface.
* **Cooldown System:** Prevents marking attendance for the same person within a 30-second window to avoid duplicate entries.

## Tech Stack
* **Python**: The core programming language.
* **OpenCV**: For capturing and processing video from the webcam.
* **face-recognition**: A library for state-of-the-art face recognition.
* **Firebase Admin SDK**: To connect and interact with the Firebase backend.
* **cvzone**: A helper library to easily display text and shapes on the video feed.
* **NumPy**: For numerical operations, especially with image data.
