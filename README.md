
🖐️ Real-Time Sign Language to Text Converter using YOLOv5
🚀 Project Overview
This project aims to build a Real-Time Sign Language to Text Converter using YOLOv5 for hand gesture detection and classification. It helps bridge communication gaps for individuals with hearing or speech impairments by converting recognized sign language gestures into text in real-time.

🛠️ Technologies & Tools Used
Roboflow - For dataset annotation, preprocessing, and augmentation.

YOLOv5 (Ultralytics) - For object detection model training and inference.

Python - Programming language for scripting and model implementation.

OpenCV - For real-time video capture and visualization.

Google Colab (Free GPU) - For model training with GPU acceleration.

📂 Project Workflow
1️⃣ Data Collection & Annotation
Collected images representing different sign language gestures.

Uploaded the dataset to Roboflow for annotation (bounding boxes around hand signs).

Utilized Roboflow's features to preprocess and augment the dataset.

2️⃣ Model Training with YOLOv5
Exported the dataset from Roboflow in YOLOv5 format.

Trained the YOLOv5 model using Google Colab (Free GPU).

Tuned hyperparameters for optimal detection accuracy.

3️⃣ Real-Time Inference & Output
Integrated the trained YOLOv5 model with OpenCV for capturing live video.

Detected sign language gestures in real-time and displayed the recognized text output on the screen.

📊 Results
✅ Achieved accurate real-time detection of hand gestures.
✅ Successfully mapped detected gestures to text outputs for real-world usability.
