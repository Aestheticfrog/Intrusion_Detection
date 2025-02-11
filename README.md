This project is an AI-powered real-time surveillance system designed to monitor crowd density, detect suspicious activities, and track object presence across multiple campus locations at VIT. It leverages YOLOv4 for object detection and optical flow analysis for motion detection.

Features
Live Camera Feeds: Captures and processes real-time footage from multiple surveillance cameras.
Crowd Density Estimation: Detects and visualizes population density at various campus locations.
Suspicious Activity Detection: Identifies fighting motions using optical flow analysis.
Object Detection with YOLOv4: Recognizes objects like weapons and alerts authorities.
Alert System: Sends automated alerts when anomalies (e.g., fights or weapons) are detected.
Campus Map Overlay: Displays real-time crowd density overlaid on a campus map.
Multi-threading Optimization: Ensures smooth processing of multiple video streams.

Technologies Used
Computer Vision: OpenCV for video processing and optical flow analysis.
Deep Learning: YOLOv4 for object detection.
Multithreading: Ensures real-time processing for multiple cameras.
Twilio API (Optional): For sending instant alerts to security personnel.
Python & OpenCV: Core technologies for image and video processing.

Future Enhancements
Integration with AI-based facial recognition for authorized personnel tracking.
Cloud-based alert system for improved security response.
Edge AI Deployment on Jetson Nano / Raspberry Pi for on-device processing.
