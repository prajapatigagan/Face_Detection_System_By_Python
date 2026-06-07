# 🎯 Face Detection System By Python

A real-time **Face Detection System** built with Python and OpenCV that detects faces via webcam and predicts **Age** and **Gender** using pre-trained deep learning (Caffe) models.

---

## 📸 Features

- ✅ Real-time face detection using webcam
- ✅ Age prediction (e.g. 0-2, 3-6, 21-25, etc.)
- ✅ Gender prediction (Male / Female)
- ✅ Deep learning based — high accuracy
- ✅ Live bounding box around detected faces

---

## 🛠️ Tech Stack

| Technology | Purpose |
|------------|---------|
| Python 3.x | Core programming language |
| OpenCV (cv2) | Computer vision & webcam access |
| Caffe Models | Age & Gender prediction |
| DNN Module | Deep neural network inference |

---

## 📁 Project Structure

```
Face-Detection-System-By-Python/
│
├── gagan.py                          # Main Python script
├── age_deploy.prototxt               # Age model architecture
├── age_net.caffemodel                # Age model weights
├── gender_deploy.prototxt            # Gender model architecture
├── gender_net.caffemodel             # Gender model weights
├── opencv_face_detector.pbtxt        # Face detector config
├── opencv_face_detector_uint8.pb     # Face detector model
├── detection_matrix.txt              # Detection matrix data
└── README.md                         # Project documentation
```

---

## ⚙️ Installation & Setup

### Step 1: Clone the Repository
```bash
git clone https://github.com/prajapatigagan/Face_Detection_System_By_Python.git
cd Face_Detection_System_By_Python
```

### Step 2: Install Required Library
```bash
pip install opencv-python
```

### Step 3: Download Model Files
Download these 2 files and place them in the project folder:

- **age_net.caffemodel** — [Download from GitHub](https://github.com/smahesh29/Gender-and-Age-Detection/blob/master/age_net.caffemodel)
- **gender_net.caffemodel** — [Download from GitHub](https://github.com/smahesh29/Gender-and-Age-Detection/blob/master/gender_net.caffemodel)

### Step 4: Run the Project
```bash
python gagan.py
```

---

## 🚀 How It Works

1. Webcam se live video capture hota hai
2. **OpenCV DNN** model har frame mein face detect karta hai
3. Detected face ko crop karke **Age model** aur **Gender model** mein bheja jata hai
4. Model prediction ke baad face par **bounding box** aur **label** draw hota hai
5. **Q** press karne par program band ho jaata hai

---

## 🎯 Age Categories

| Age Group |
|-----------|
| 0-2 |
| 3-6 |
| 7-12 |
| 15-20 |
| 21-25 |
| 26-30 |
| 31-35 |
| 36-40 |
| 41-47 |
| 48-53 |
| 54-57 |
| 58-66 |
| 67-73 |
| 74-80 |

---

## 📌 Requirements

```
Python 3.8+
opencv-python
```

---

## ⚠️ Notes

- Achhi lighting mein accuracy behtar hoti hai
- Ek frame mein multiple faces bhi detect ho sakte hain
- Press **Q** to quit the application

---

## 👨‍💻 Developer

**Gagandeep**  
