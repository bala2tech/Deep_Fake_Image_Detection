Deepfake Image Detection using a hybrid CNN + RNN architecture with patch-based analysis and a Gradio web app. Detects real vs fake images using Efficient Net and LSTM sequence modeling.

DeepShield: Deepfake Image Detection using CNN + RNN (Image Patch Sequence Model)

A powerful deepfake image classifier that combines CNN (EfficientNet) + RNN (LSTM) to detect subtle manipulation artifacts in face images. The system splits each input image into patches, extracts high-level features using a pretrained CNN, and then models patch relationships using an LSTM to classify REAL vs FAKE.

A simple Gradio web app is included for deployment and live demo.

🚀 Project Highlights

🧠 Hybrid CNN + RNN architecture
EfficientNetB0 extracts patch-level features → LSTM learns sequential artifacts.

🖼️ Image-only deepfake detection
No videos required — works purely with images.

🔍 Patch-based fake detection
Each image is divided into 16 patches, capturing micro-texture distortions caused by deepfake generation.

🌐 Gradio Web App
Upload an image and instantly get prediction + confidence score.

🔧 Transfer Learning
Uses EfficientNet pretrained on ImageNet for robust feature extraction.

📊 Full Train/Val/Test pipeline
Automatically loads dataset, splits it, and trains with generators.

🧪 Technologies Used

Python

TensorFlow / Keras

EfficientNetB0

LSTM / RNN

OpenCV

NumPy

Gradio

Google Colab

🏆 Skills Demonstrated
Data Science & Deep Learning Skills

CNN feature extraction

Sequence modeling using LSTM

Transfer learning

Image preprocessing pipelines

Model evaluation & classification metrics

Computer Vision Skills

Patch-based modeling

Image segmentation

Deepfake artifact detection

Software & Deployment Skills

Gradio interactive UI

Model saving/loading (Keras .h5)

End-to-end deep learning workflow

🎯 Real-World Applications

Social media moderation

Deepfake detection in KYC verification

Fraud prevention

Digital forensics

Image authenticity checks

