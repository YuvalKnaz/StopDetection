Stop Sign Violation Detection System
Project Overview
This project was developed as part of a Seminar Course during my B.Sc. studies in Information Systems at The Max Stern Yezreel Valley College.

The system utilizes Computer Vision and Deep Learning techniques to identify stop signs and detect whether a vehicle has performed a full stop as required by law. This project aims to enhance road safety by providing an automated tool for monitoring traffic violations.

Features
Object Detection: Identifies stop signs in real-time or from video files.

Violation Logic: Analyzes vehicle movement to determine if a full stop occurred before the sign.

Data Driven: Processed using Python and specialized Computer Vision libraries.

Model Details

The system utilizes a trained YOLO (You Only Look Once) model for high-accuracy object detection. The model weights are stored in the best.pt file.
You can download the trained model weights from the following link:
https://drive.google.com/file/d/1ryqWDbz4VCG8BB0uXWYa1mv2CgPSiF3F/view?usp=sharing

Dataset and Videos
Since the video files used for this project are large, they are not hosted directly on GitHub. You can access the raw footage and the test datasets through the following link:
https://drive.google.com/drive/folders/1OpQCJ8xOb0e8a2Syvn9teBk9EfZYbuww?usp=sharing

Technologies Used
Language: Python

Libraries: OpenCV, NumPy, and Deep Learning frameworks

Platform: Google Colab

**How to Run**
1. Open the `Stop_Sign_Detection.ipynb` file in this repository.
2. Click the "Open in Colab" button at the top of the notebook.
3. Run **Block 1** to install all necessary dependencies (YOLO, OpenCV, etc.).
4. Mount your Google Drive when prompted to access the model and videos.
5. Run **Block 2** and provide the path to your video file to start the detection process.
