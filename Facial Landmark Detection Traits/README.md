
# 📌 Facial Landmark Detection with MediaPipe 🖥️📸

This project implements **Facial Landmark Detection** using Python’s **MediaPipe Face Mesh** framework. It detects a human face in a static image, identifies **468 key facial landmarks**, and performs simple facial measurements like interocular distance and nose length.


---

## 🚀 Features  
- Detect human faces in images.
- Predict and extract **468 facial landmarks**.
- Draw facial tesselation overlays on images.
- Calculate key facial measurements:
  - Interocular distance (between both eyes)
  - Nose length (top to tip)

---

## 🛠️ Tech Stack  

| Tool/Library | Purpose                          |
|:------------|:---------------------------------|
| `OpenCV`     | Image loading and processing     |
| `MediaPipe`  | Real-time facial landmark detection |
| `NumPy`      | Numerical operations             |
| `Matplotlib` | Image visualization (optional)  |

---

## 📖 How It Works  

1. **Load an image** containing a face.
2. **Process the image with MediaPipe Face Mesh** to detect facial landmarks.
3. **Extract the pixel coordinates** of all 468 landmark points.
4. **Calculate specific measurements** between selected landmark points.
5. Optionally, **visualize the annotated image** with facial tesselation.

---

## 📦 Installation  

```bash
pip install opencv-python mediapipe numpy matplotlib
```

---

## 📊 Example Usage  

```python
import cv2
import mediapipe as mp
import numpy as np

# Initialize Face Mesh
face_mesh = mp.solutions.face_mesh.FaceMesh(static_image_mode=True)

# Load and process an image
image = cv2.imread('your_path_picture.jpg')
rgb_image = cv2.cvtColor(image, cv2.COLOR_BGR2RGB)
results = face_mesh.process(rgb_image)

# Extract landmarks, calculate distances, and visualize
```

---

## 🔮 Applications  

- Facial feature measurement and analysis.
- Medical and cosmetic facial assessments.
- Augmented reality effects and filters.
- Emotion detection and face alignment.

---

## 🌱 Future Improvements  

- Add support for **real-time video detection**.
- Compute more facial ratios and traits.
- Integrate with a web app interface.
- Extend to multi-face detection in complex images.

---

## 📎 Notes  

The MediaPipe Face Mesh model processes **468 facial landmarks** efficiently in real-time and can be adapted for both static images and video streams.
