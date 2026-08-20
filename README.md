# 🎯 Real-Time Object Detection using Haar Cascades

This project demonstrates how to detect human faces and other objects in real-time using OpenCV's Haarcascade classifier. A lightweight and fast approach suitable for edge devices and basic surveillance tasks.

---

## 📌 Project Goals

- Perform real-time object detection using traditional CV techniques
- Implement face, eye, and body detection with Haarcascade XML models
- Learn OpenCV-based computer vision pipeline

---

## 🚀 Technologies Used

- Python
- OpenCV
- Haarcascade Classifiers
- NumPy
- Webcam Integration (cv2.VideoCapture)

---

## 🧠 Key Concepts

- Haar Feature-based Cascade Classifiers
- Grayscale conversion and frame preprocessing
- Detection using `.detectMultiScale()` method
- Drawing bounding boxes around detected objects



## 🖥️ How it Works

1. Load Haarcascade XML model (e.g., for face, eyes)
2. Start webcam feed
3. Convert each frame to grayscale
4. Apply detection model on each frame
5. Display bounding boxes in real-time



## 🔬 Sample Output

> 🧍 Real-time bounding box around:
- Faces
- Eyes
- Full human body (if configured)





## 📈 Performance

- Very fast on CPU (~25–30 FPS)
- No need for GPU or large deep learning models
- Works well in controlled lighting environments



## 📁 File Structure


├── object-detection.ipynb
├── haarcascade_frontalface_default.xml
├── haarcascade_eye.xml
├── haarcascade_fullbody.xml


💡 Future Work
Upgrade to YOLOv5/YOLOv8 or SSD for deep learning-based detection

Build GUI interface using Tkinter or Streamlit

Add object tracking (e.g., SORT or DeepSORT)

Use video input instead of webcam

🤝 Author
A.H.M. Nazmul Hasan
Computer Engineer | AI/ML Developer
GitHub: @nh30073007


