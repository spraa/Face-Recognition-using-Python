# Face Recognition Using Python

A Python-based project for face detection and recognition using **OpenCV** and **face_recognition** library. This project demonstrates real-time face recognition as well as static image processing.

---

## 🚀 Features
- Real-time face recognition using a webcam.
- Recognizes faces from a predefined database of images.
- Static image processing to identify faces in photos.
- Scalable for adding more known faces.

---

## 🛠️ Components Required
- **Python 3.8+**
- Libraries:
  - `opencv-python`
  - `face_recognition`
  - `dlib`
  - `numpy`
- A webcam for real-time recognition (optional for static images).

---

## ⚡ Workflow
1. **Prepare Known Faces**:
   - Add images of known individuals in the `known_faces` directory. Filenames will act as labels (e.g., `person1.jpg`).

2. **Run the Script**:
   - For real-time recognition (using webcam):
     ```bash
     python face_recognition.py
     ```
   - For static image recognition:
     ```bash
     python face_recognition.py --input test_images/group_photo.jpg
     ```

3. **Output**:
   - Displays a live video or processed image with bounding boxes around detected faces and names for recognized ones. Unrecognized faces are labeled as "Unknown."

---


## 📂 Folder Structure
```plaintext
FaceRecognition
│
├── face_recognition.py         # Main Python script for recognition
├── known_faces/                # Directory of known face images
│   ├── person1.jpg
│   ├── person2.jpg
├── test_images/                # Directory for test images
│   ├── group_photo.jpg
├── Images
│   ├── circuit_diagram.png     # Circuit diagram image
│   ├── project_demo.png        # Demo image of your project

