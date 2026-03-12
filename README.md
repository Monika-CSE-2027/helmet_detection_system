🚦 AI Helmet Detection System
📌 Project Description

The AI Helmet Detection System is a computer vision application that detects whether a person riding a motorcycle is wearing a helmet or not. The system uses a trained YOLOv8 deep learning model to analyze images from uploads or a webcam and classify them as Helmet or No Helmet.

This project helps improve road safety monitoring and can assist traffic authorities in identifying helmet rule violations.

🎯 Objectives

Detect whether a rider is wearing a helmet.

Provide real-time helmet detection using images or webcam.

Improve road safety using AI technology.

Demonstrate the use of deep learning for traffic monitoring systems.

🧠 Technologies Used

Python

YOLOv8 (Ultralytics)

Gradio – For building the web interface

OpenCV – Image processing

Google Colab – Model execution environment

NumPy

📂 Project Structure
AI-Helmet-Detection/
│
├── helmet_detection.py
├── README.md
├── requirements.txt
└── helmet_model_v2.pt
⚙️ Installation

Install the required libraries using:

pip install ultralytics gradio opencv-python
▶️ How to Run the Program

Open Google Colab or your local Python environment.

Mount your Google Drive.

Ensure the trained model file is located in:

/content/drive/MyDrive/helmet_mmodel_v2.pt

Run the Python script.

A Gradio web interface will launch.

🖼️ How It Works

The user uploads an image or captures an image using a webcam.

The image is passed to the YOLOv8 trained model.

The model detects objects in the image.

The system checks the detected class:

Helmet

No Helmet

The result is displayed with bounding boxes and status.

🧾 Output

The system displays:

Detection Result Image (with bounding boxes)

Helmet Status

✅ Helmet Detected

❌ No Helmet Detected

⚠ Helmet Status Unclear

📊 Applications

Traffic rule enforcement

Smart traffic monitoring systems

Road safety analysis

Automated violation detection

🔮 Future Enhancements

Number plate recognition

Automatic fine generation

Triple riding detection

Real-time CCTV monitoring

Traffic police alert system

👩‍💻 Author

Monika L
B.E Computer Science and Engineering
