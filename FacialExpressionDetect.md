✅ 📌 Popular & Real-World Facial Emotion Detection Repos

1. Facial Emotion Recognition using OpenCV + Deepface (Python)
GitHub: https://github.com/manish-9245/Facial-Emotion-Recognition-using-OpenCV-and-Deepface

• Detects expressions like happy, sad, surprised in real time using OpenCV and Deepface models.
• Good starter for Python real-time webcam emotion detection.

2. Facial Emotion Recognition (TensorFlow / Keras)
GitHub: https://github.com/jalajthanaki/facial_emotion_recognition_using_keras

• Uses CNN models trained on FER-2013 (Kaggle dataset) for real-time webcam emotion classification.
• Includes scripts for realtime and static image inference.

3. Face Emotion Recognition (Python + OpenCV)
GitHub: https://github.com/silent18killer/face-emotion-recognition

• Simple Python project using OpenCV for emotion detection and classifier inference.
• Lightweight and easy to tweak.

4. Real-Time Facial Emotion Analyzer
GitHub: https://github.com/susantabiswas/realtime-facial-emotion-analyzer

• Realtime emotion detection from webcam or video feed using trained models.
• Works with common emotion classes (happy, sad, angry, etc.).

🧠 Other Related Repositories / Topics

GitHub topic search – facial emotion detection
• There are many projects under the “facial-emotion-detection” topic page with diverse implementations (CNN, transformer models, etc.) on GitHub.

Explore directly:
🔗 https://github.com/topics/facial-emotion-detection

🔬 Research / Tools with Open Source Code

EmotiEffLib – Efficient Emotion Analysis Library
GitHub: https://github.com/av-savchenko/EmotiEffLib

• Lightweight library for emotion recognition from images & video.
• Python & C++ support with ONNX/PyTorch backends.




🆓 Free or Freemium Tools
🧠 Expression / Emotion Analyzers (Web / Visual Tools)

1. Expression Explorer – AI-powered facial expression analysis tool (browser based)
• Detects emotions like happiness/sadness from uploaded images.

2. Emotion Reader – Free image emotion detection via AI on yeschat.ai
• Analyzes basic emotions (happy, sad, angry, fear, etc.) from face images.

3. Morphcast (online) – Simple online face emotion detection (free tier available)
• Captures and analyzes emotional expressions from photos directly in the browser.

🖥 Open-Source Tools & Browser Extensions

💼 Premium / Commercial Solutions
🧠 Affectiva Facial Coding SDK (Commercial)

• Industry-grade SDK for emotion and facial action unit analysis, optimized for real-time use in apps and research.

Why it’s premium:

Recognizes multiple emotional states beyond basic categories

Works in real time with video streams

Designed for market research, UX testing, healthcare and behavior analysis

📊 FaceReader (by Noldus) (Professional Software)  https://my.noldus.com/download/latest/facereade

• Desktop application for facial expression analysis from video or live camera.

Features:

Detects 7 core emotions

Integrates with other biometric sensors

Various licensing levels from basic to advanced

Use cases: research labs, UX, advertising insights

🧩 Visage Technologies Emotion SDK

• Commercial SDK that adds real-time emotion detection to your own software.

Good for: developers building custom apps with emotion analytics

🧠 Developer Libraries (Free to Use)

If you want to build your own tool or integrate emotion detection, these are popular:

face-api.js — Browser-based face & emotion detection (JS)

OpenFace / OpenFace 3.0 — Lightweight open-source face behavior analysis (research)

Py-Feat — Python toolbox for facial expression analysis including Action Units

EmotiEffLib — Open-source inference library for real-time facial expression recognition (Python/C++)

OpenFace 3.0 in particular is a modern free toolkit for real-time facial analysis and emotion recognition.




🧠 1. face-api.js (Offline Browser/Node)

🔹 Language: JavaScript
🔹 Runs on: Browser or Node.js
🔹 Can detect: Faces + facial expressions (happy, sad, angry, surprised, neutral, etc.)

👉 GitHub: https://github.com/justadudewhohacks/face-api.js

This runs entirely offline in the browser using pretrained models — just download the model files and host them locally.

Pros:
✔ Real-time webcam support in the browser
✔ Offline once models are downloaded
✔ Works with static images too

Cons:
⚠ Not as powerful as full research-grade AI

🐍 2. OpenFace 2.0 (Offline C++ / Python)

🔹 Language: C++ / Python bindings
🔹 Runs on: Windows, macOS, Linux
🔹 Can detect: Facial landmarks, action units, poses, expressions

👉 GitHub: https://github.com/TadasBaltrusaitis/OpenFace

OpenFace is a powerful offline toolkit originally developed for research. It doesn’t rely on internet APIs once installed.

Pros:
✔ Research-quality
✔ Very detailed expression analysis (Facial Action Coding System)
✔ Real-time webcam support

Cons:
⚠ Setup is heavier (CMake, dependencies)

🐍 3. Py-Feat (Offline Python Library)

🔹 Language: Python
🔹 Runs on: Local Python environment (no cloud)
🔹 Detects: Emotions and facial action units

👉 GitHub: https://github.com/cosanlab/py-feat

Works with offline models to analyze images and video, and outputs emotion probabilities.

Pros:
✔ Python native
✔ Works with images or webcam feeds
✔ Outputs detailed metrics (AU intensities)

Cons:
⚠ Less real-time optimized than face-api.js

🐍 4. EmotiEffLib (Offline C++ / Python)

🔹 Language: C++ with Python support
🔹 Runs on: Linux, macOS, Windows
🔹 Detects: Facial expressions and emotion classes

👉 GitHub: https://github.com/av-savchenko/EmotiEffLib

A lightweight, open-source library for offline emotion detection with real-time performance focus.

🧠 5. dlib + Pretrained Models (Offline C++ / Python)

🔹 Language: Python / C++
🔹 Runs on: Local
🔹 Uses: dlib’s HOG/SVM models + custom emotion classifier




Desktop Applications
🖥️ 1. FaceReader (Professional) — Paid with Trial

📍 Windows desktop application | Professional research standard

✔ Detects 7 core emotions (happy, sad, angry, surprised, disgust, fear, neutral)
✔ Tracks facial features, action units, gaze, and head orientation
✔ Works on video files or live webcam
✔ Used in psychology, UX research, marketing analysis

🔗 Official download (Windows):
https://my.noldus.com/download/latest/facereader

⚠️ Free trial available, full version requires a license

🆓 2. OpenFace Viewer (Desktop) — Free

📍 Cross-platform (Windows, macOS, Linux)

✔ Built on OpenFace engine
✔ Detects facial landmarks & action units
✔ Some emotion scoring depending on setup
✔ Offline (no internet requirement)

GitHub (OpenFace):
https://github.com/TadasBaltrusaitis/OpenFace

Note: It’s more “research GUI + command-line + viewer”, not a polished consumer app — but it runs locally and shows expression data.

🖥️ 3. Kinovea — Free

📍 Windows application for video analysis

🟡 Not specialized emotion detection by default, but can be extended with plugins / visual tracking.

Download:
https://www.kinovea.org

Good for:
✔ Annotating video
✔ Tracking facial motion if external model added

(Not dedicated emotion detection — more video analysis)

🖥️ 4. Affectiva Emotion SDK / Affdex Desktop Examples — Free & Paid SDK

📍 Windows & macOS examples
• Affectiva used to ship a desktop demo tool (AffdexMe) that runs locally and shows emotion analytics from webcam.

SDK (commercial with free tier):
https://developer.affectiva.com

💡 Many sample desktop apps are available that you can run offline (built with Python/C++, Qt)

🖥️ 5. FaceAPI Desktop Demonstrators — Free Examples (Local)

If you want a ready-to-run GUI without heavy coding:

👉 People have packaged face-api.js / Electron clients that run locally and detect expression in a desktop app.

Examples (GitHub hosted, install locally):

Electron Face Expression Demo
https://github.com/justadudewhohacks/face-api.js/tree/master/examples/electron

Steps:
✔ Clone repo
✔ Install Node/Electron
✔ Run on desktop as compiled app

No cloud needed — runs purely on your machine using webcam.

🖥️ 6. EmoVision (Chrome App / Desktop) — Free

While technically a browser extension, you can install Chrome as a standalone app and run it like a desktop:

✔ Detects facial expressions in real time from webcam
✔ Works offline after initial load

GitHub (community extension):
https://github.com/itsnerflo/emovision

(Not as polished as paid products — but works locally)