# Face-detection-using-javascript-master
 A browser-based face detection app using face-api.js and TensorFlow.js. Detects facial landmarks, expressions, and identities in real time from webcam or images. Runs entirely in the browser with no server required. Ideal for learning, prototyping, or AI-based web projects.


````markdown
# 👁️‍🗨️ Face Detection Using JavaScript

This project demonstrates real-time **face detection** using the [face-api.js](https://github.com/justadudewhohacks/face-api.js) library in the browser. It uses TensorFlow.js under the hood and can detect facial features, landmarks, expressions, and more using a webcam feed or static images.

---

## 📸 Features

- Real-time face detection in the browser
- Detection of:
  - Facial landmarks (68-point model)
  - Facial expressions (happy, sad, angry, etc.)
  - Face recognition (match faces)
- Model loading from local files
- No server or backend required

---

## 🧪 Technologies Used

- JavaScript
- [face-api.js](https://github.com/justadudewhohacks/face-api.js)
- HTML5
- Webcam API (optional)
- Pre-trained models (SSD MobileNetV1, Tiny Face Detector, etc.)

---

## 🚀 Getting Started

### 1. Clone or Download

```bash
git clone https://github.com/yourusername/face-detection-using-javascript.git
````

Or download the ZIP and extract it.

### 2. Open the App

Open the `index.html` file in your browser.

> 🔒 Make sure to use a **local web server** (not just double-click). You can use:

```bash
npx serve
# or
python3 -m http.server
```

Then visit: `http://localhost:5000` or similar.

---

## 📂 Folder Structure

```
face-detection-using-javascript/
├── index.html              # Main page
├── script.js               # Detection logic
├── face-api.min.js         # Library
├── models/                 # Pre-trained model files
├── images/                 # Sample face images
```

---

## 📄 License

This project is open-source and free to use under the MIT License.

---

## 🙌 Acknowledgements

* [face-api.js](https://github.com/justadudewhohacks/face-api.js) by @justadudewhohacks
* TensorFlow\.js
