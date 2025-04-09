# Face Mask Detection (MobileNetV2 + OpenCV)

## 📌 Overview
Real-time face mask detection system using deep learning and webcam feed.

##  Tech Stack
- Python
- TensorFlow / Keras
- MobileNetV2 (Transfer Learning)
- OpenCV
- NumPy

##  Features
- Real-time mask detection using webcam
- Achieved ~95% accuracy on validation data
- Lightweight and fast model performance

## ▶️ How to Run
1. Clone this repo  
   `git clone https://github.com/Niveditta8896/facce-mask-detection.git`

2. Install dependencies  
   `pip install -r requirements.txt`

3. Run the app  
   `python mask_detector_app.py`

4. (Optional) Test with demo video:  
   Play `face_video_2.mp4` for reference
## 🎥 App Variants

- `face_mask_video_input.py`: Detects masks on a pre-recorded video
- `face_mask_webcam_app.py`: Detects masks in real-time using webcam input

> *Note:* Video file showing webcam output is too large for GitHub but available on LinkedIn post.

##  Files
- `mask_detector_app.py`: Real-time detection script
- `mask_detector_model.h5`: Trained CNN model
- `res10_300x300_ssd...caffemodel`: Face detection model
- `requirements.txt`: Python dependencies
- `face_video_2.mp4`: Sample output video

##  What I Learned
- Transfer learning with MobileNetV2
- Real-time image processing using OpenCV
- Building and deploying a deep learning model end-to-end
