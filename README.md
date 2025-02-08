Human Pose Estimation using Machine Learning

This project implements human pose estimation using OpenCV's Deep Neural Network (DNN) module. It detects key points of the human body and connects them to form a skeleton-like structure.

🛠️ Features

Pose estimation from images and videos.

Uses OpenCV DNN to process frames.

Implements Streamlit UI for an interactive experience.

📎 Project Structure

📁 Human Pose Estimation using Machine Learning │-- .gitattributes │-- estimation_app.py # Streamlit App for Pose Estimation │-- pose_estimation.py # Pose Estimation on Images │-- pose_estimation_video.py # Pose Estimation on Videos │-- graph_opt.pb # Pre-trained Model │-- requirements.txt # Dependencies │-- README.md # Project Documentation │-- run1.mp4 # Sample Video for Testing │-- stand.jpg # Sample Image for Testing │-- output.mov # Output Video Example

🚀 Installation & Usage

1️⃣ Install Dependencies

Make sure you have Python 3.x installed. Then, install the required packages:

pip install -r requirements.txt

2️⃣ Run the Streamlit App

To launch the web interface for pose estimation:

streamlit run estimation_app.py
