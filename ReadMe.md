Here are some open-source GitHub repositories you can use or study for background removal in webcam/video calls — including both browser-based and Python/AI approaches:

🌐 Browser / WebRTC / JS Background Removal

transparent-virtual-background – Browser background removal with WebRTC & MediaPipe
https://github.com/webrtcHacks/transparent-virtual-background

• Uses getUserMedia, WebRTC and MediaPipe for real-time video segmentation and transparent background in the browser.

virtual-background – Webcam virtual background effect (HTML/JS)
https://github.com/vpalmisano/virtual-background

• Real-time webcam video stream processing with MediaPipe + adjustable filters.

These are good starting points if you want browser-side background removal in video calls without external APIs.

🐍 Python / AI-based Background Segmentation

real-time-person-background-removal – Python + YOLO + OpenCV (live video)
https://github.com/rmarquet21/real-time-person-background-removal

• Segments and removes the person background in real-time video feed using YOLO models and OpenCV.

backgroundremover – Command-line tool & video background removal
https://github.com/nadermx/backgroundremover

• CLI Python tool to remove background from image/video using AI models like U^2Net.

VideoBackgroundRemoval – Auto background removal tool for videos
https://github.com/killian31/VideoBackgroundRemoval

• Allows subject selection and automatic background removal from full videos.

💡 Notes & Tips

Browser-side solutions (like the WebRTC and virtual-background repos) are best if you’re building a real video-call client — they perform segmentation in real time and can be integrated directly with WebRTC streams.

Python/AI tools are more suited for standalone apps or preprocessing video feeds (e.g., before sending to a call). They usually rely on heavier models (PyTorch/TensorFlow) and may not be optimized for real-time browser use without additional work.

For a web conferencing product, you can also combine WebRTC insertable streams + a segmentation model — like TensorFlow.js segmentation (DeepLab, BodyPix) — for low-latency browser background removal.

🛠️ Bonus: Real-Time Web Background Replacement Tip

You can use libraries like Twilio Video Processors which implement background removal/virtual background by applying a segmentation processor to each video frame before sending over WebRTC. (Code example available in Twilio’s repo/blog).

If you want, I can provide example code to integrate one of these repos into a real video-call — for example using WebRTC + segmentation to stream a transparent or custom background live.