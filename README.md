Human Pose Estimation using Machine Learning

📌 Overview

This project implements human pose estimation using OpenCV's Deep Neural Network (DNN) module. It detects key points of the human body and connects them to form a skeleton-like structure.

🛠️ Features

Pose estimation from images and videos.

Uses OpenCV DNN to process frames.

Implements Streamlit UI for an interactive experience.

📎 Project Structure

📁 Human Pose Estimation using Machine Learning
│-- .gitattributes
│-- estimation_app.py          # Streamlit App for Pose Estimation
│-- pose_estimation.py         # Pose Estimation on Images
│-- pose_estimation_video.py   # Pose Estimation on Videos
│-- graph_opt.pb               # Pre-trained Model
│-- requirements.txt           # Dependencies
│-- README.md                  # Project Documentation
│-- run1.mp4                   # Sample Video for Testing
│-- stand.jpg                  # Sample Image for Testing
│-- output.mov                 # Output Video Example

🚀 Installation & Usage

1️⃣ Install Dependencies

Make sure you have Python 3.x installed. Then, install the required packages:

pip install -r requirements.txt

2️⃣ Run the Streamlit App

To launch the web interface for pose estimation:

streamlit run estimation_app.py

3️⃣ Run Pose Estimation on Images

To process a static image and detect key points:

python pose_estimation.py

4️⃣ Run Pose Estimation on Videos

To process a video file and detect key points:

python pose_estimation_video.py

📷 Output Samples

Original Image

![image](https://github.com/user-attachments/assets/4f364962-d4b2-4336-a689-fe4de4ef73e1)

Pose Estimation Result

![image](https://github.com/user-attachments/assets/6af790f7-c41e-4d62-9c83-1d0fb5ec0aa0)


📝 Notes

Ensure graph_opt.pb (pre-trained model) is in the same directory.

The Streamlit app allows users to upload custom images for real-time pose detection.

Adjust the threshold slider in the Streamlit app for better accuracy.

📌 Future Enhancements

Improve accuracy with a better deep learning model.

Add support for real-time webcam-based pose estimation.

Optimize performance for faster processing.

👨‍💻 Author

Basamsetti Sahithi Devi

LinkedIn: www.linkedin.com/in/sahithibasamsetti

GitHub: [Your Repository](https://github.com/sahithi3429/Human-Pose-Estimation-using-Machine-Learning.git)
