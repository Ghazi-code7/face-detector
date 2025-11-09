# 👁️ Face Detection App

An AI-powered **real-time face detection web application** that uses your device’s webcam and the **BlazeFace model (TensorFlow.js)** to identify and highlight faces directly in the browser — no data ever leaves your device.

---

## ✨ Features

- 🔍 Real-time face detection using BlazeFace
- 📸 Works entirely in your browser
- 🧠 Built with TensorFlow.js
- ⚡ Lightweight and fast — runs even on mobile browsers
- 💡 Beautiful, minimal, glowing UI
- 🔒 100% private — your camera feed never leaves your device
- 🧾 Face counter with live updates
- 🧰 Simple start/stop camera controls
- 🎨 Responsive design for all screen sizes

---

## ⚡ Quick Start

### Prerequisites
- A modern browser (Chrome, Edge, Firefox, Safari)
- A working webcam
- Internet connection (to load TensorFlow.js & BlazeFace)

### Steps
1. Clone this repository:
   ```bash
   git clone https://github.com/Ghazi-code7/face-detector.git
   cd face-detector

	2.	Open face_detection.html in your browser
	3.	Allow camera permissions when prompted
	4.	Enjoy real-time AI-powered face detection!

⸻

🚀 Deploy to Production

You can host this app anywhere that serves static files — no backend needed.

Option 1 — GitHub Pages
	1.	Push your code to the main branch on GitHub.
	2.	Go to your repository → Settings → Pages.
	3.	Under Branch, choose main and / (root).
	4.	Click Save.

After a minute or two, your live app will be available at:
👉 https://Ghazi-code7.github.io/face-detector

Option 2 — Local Server

Run a quick local server (optional):

python3 -m http.server

Then open:

http://localhost:8000/face_detection.html


⸻

🧭 How to Use
	1.	Open the app in your browser.
	2.	Wait for the status to show “Click Start Camera to begin”.
	3.	Click Start Camera.
	4.	Allow camera permissions when prompted.
	5.	Faces in the view will be detected and highlighted with glowing bounding boxes; the face counter updates in real time.
	6.	Click Stop Camera to end detection.

⸻

⚙️ Settings Explained

Setting	Description
Start Camera	Begins webcam stream and starts detection.
Stop Camera	Stops the webcam and clears the canvas.
Face Count	Shows the number of faces currently detected.
Model Loader	Displays model loading state and errors.


⸻

🧩 Technical Details
	•	Frontend: HTML5, CSS3, JavaScript (ES6)
	•	AI Model: BlazeFace (via TensorFlow.js)
	•	Rendering: HTML5 <canvas> overlays bounding boxes over the video feed
	•	Libraries Used:
	•	@tensorflow/tfjs (via CDN)
	•	@tensorflow-models/blazeface (via CDN)
	•	Detection loop uses requestAnimationFrame() for smooth frame updates.
	•	Canvas dimensions are synced to video frame size for accurate overlays.

⸻

🔐 Privacy

Your camera feed is processed entirely locally in your browser.
	•	No images or video frames are uploaded to any server.
	•	All model inference happens on-device via TensorFlow.js.
	•	No telemetry or personal data collection by default.

⸻

🧰 Troubleshooting

Problem	Solution
Camera not detected	Make sure your browser has permission to access the webcam, and no other app is blocking it.
Model won’t load	Check your internet connection; the app loads TFJS & BlazeFace from CDN.
Faces not being detected	Improve lighting and ensure faces are within the camera frame.
Canvas not updating	Reload the page and click “Start Camera”; try a different browser if issues persist.
High CPU usage	Close other tabs/apps; reduce video resolution in getUserMedia if needed.


⸻

💡 Use Cases
	•	👨‍🏫 Educational demos (AI, ML, or computer vision)
	•	🧪 Prototype for face tracking or downstream models (e.g., emotion, landmark detection)
	•	🎮 Interactive web-based AR and camera-based games
	•	📷 Privacy-preserving local face counters and analytics

⸻

📜 License (MIT)

MIT License

Copyright (c) 2025 Ghazi_K

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.


⸻

📬 Contact

Ghazi_k
✉️ ideafuel008@gmail.com
🔗 Ghazi-code7

⸻

🙏 Acknowledgements
	•	TensorFlow.js￼
	•	BlazeFace Model (tfjs-models)￼
	•	MDN Web Docs￼

⸻

📊 Project Stats

Metric	Value
🧠 Model	BlazeFace (tfjs-models)
⚙️ TensorFlow.js	v4.11.0 (CDN)
📄 Approx. lines	~450
🕒 Last Updated	November 2025
💻 Compatibility	Chrome, Edge, Firefox, Safari


⸻

“Real-time AI at your fingertips — built for privacy, performance, and simplicity.”
