# AICTE_EDUNET_PROJECT
AI-Powered Smart Traffic Violation Detection System
Overview
This project presents a real-time, AI-driven system designed to automatically detect traffic rule violations such as signal jumping, wrong-way driving, and helmetless riding using surveillance camera footage. It leverages deep learning and computer vision techniques to enhance road safety by minimizing human intervention and error.

  Key Features
 >Real-time Violation Detection using CNN-based object detection and tracking models (YOLO, OpenCV, etc.)
 >Helmet Detection using custom-trained classifiers
 >Wrong-Way and Signal Jumping Detection with path tracking and signal timing analysis
 >Integration with live traffic CCTV feeds
 >Automated alert generation and logging for authorities
Dashboard for monitoring, statistics, and reviewing flagged incidents
  Motivation
Manual traffic monitoring is not scalable in modern urban environments. This AI-powered system automates the process of identifying and reporting violations, reducing the load on traffic personnel and enhancing enforcement efficiency. The goal is to reduce accidents and promote adherence to road safety laws.

  Technologies Used
Python, OpenCV, TensorFlow/PyTorch
YOLOv5 / YOLOv8 for object detection
Deep Learning for helmet classification
Flask/Django for backend API
MongoDB / MySQL for storing violation logs
Streamlit / React for frontend dashboard (optional)
  Results
Accuracy: Achieved >90% precision in detecting helmetless riding and wrong-way driving.
Latency: Real-time processing with average latency <300ms per frame.
Scalability: Successfully tested on multi-camera live streams with consistent performance.
