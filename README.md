# Real-Time Sign Language Detection using YOLOv5
# Overview
This project aims to develop a robust real-time sign language detection system utilizing the YOLOv5 (You Only Look Once) object detection algorithm. The system is designed to interpret and recognize various sign language gestures from live video feeds, enabling effective communication between deaf and mute individuals and the broader community.
# Motivation
Sign language is a vital communication tool for deaf and mute individuals. However, the lack of widespread understanding of sign language in the general population can create communication barriers. This project seeks to bridge this gap by providing a real-time sign language recognition system that can interpret sign gestures instantly, making communication more accessible and inclusive.
# Features
Real-Time Detection: The model is capable of detecting and classifying sign language gestures in real-time using a webcam or other video input devices.
High Accuracy: Trained with YOLOv5, the model achieves high accuracy in recognizing various sign language gestures.
Scalable and Customizable: The system can be easily adapted to recognize additional gestures or customized for different sign languages.
# Technical Details
YOLOv5: The project utilizes YOLOv5, a state-of-the-art object detection algorithm, known for its speed and accuracy in detecting multiple objects in a single frame.
Dataset: The model is trained on a custom dataset containing labeled images of various sign language gestures.
Frameworks and Libraries: Python, OpenCV, PyTorch, and TensorFlow are some of the primary technologies used in this project.
Environment: The model is developed and trained using Jupyter Notebooks, and can be deployed in various environments including Google Colab, local machines, or cloud-based services.
# Model Training
# Training Data
![train_batch0](https://github.com/user-attachments/assets/d732b84e-5f58-4f9d-a3f7-9101a26a5ded)
![train_batch1](https://github.com/user-attachments/assets/d63cd54d-85f0-40ea-814f-18e13b8875ed)
# Validation data 
![val_batch0_labels](https://github.com/user-attachments/assets/1e7de8ce-ea96-4987-9558-e0f29ebb3819)
# Parameters
# F1 Curve
![F1_curve](https://github.com/user-attachments/assets/c97ba0fe-8b7c-4426-8365-550c04bd9b05)
# Confusion Matrix
![confusion_matrix](https://github.com/user-attachments/assets/e5828669-58ff-4275-89bf-5f1d189ff14f)
# Labels
![labels](https://github.com/user-attachments/assets/067a3234-6ee6-45b0-ad45-a93197cbdd5e)
# Result 
![results](https://github.com/user-attachments/assets/2bdd8c2e-1e8c-4e5b-865b-b4c127e8a6f0)
# Usage
Real-Time Detection: The system will start detecting sign language gestures in real-time. Detected gestures will be displayed on the screen along with their corresponding labels.
# Future Work
Gesture Expansion: Integrate more sign language gestures into the model.
Multi-language Support: Expand the model to recognize different sign languages from various regions.
Improved Accuracy: Continuously refine the model using larger and more diverse datasets.
# Acknowledgments
Special thanks to Nicholas Renotte (nicknochnacks) for his project tutorial following which I was able to create my own custom dataset.
