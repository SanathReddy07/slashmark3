# slashmark3
Building a real-time Auto License Plate Recognition (ALPR) system with Jetson Nano involves several steps. This project will use the YOLOv4-tiny model for license plate detection and Optical Character Recognition (OCR) for character recognition. Additionally, we'll use OpenCV for image processing and interfacing with the camera. Make sure you have the necessary hardware and software prerequisites before starting.

Prerequisites:
1.Jetson Nano Developer Kit
2.Camera (USB or CSI)
3.MicroSD card (32GB recommended)
4.JetPack SDK installed on Jetson Nano
5.Python installed on Jetson Nano
6.TensorFlow, OpenCV, and other required libraries installed
Steps:
1. Install Required Libraries
2. Clone YOLOv4-tiny repository
3. Create ALPR Script:
Create a Python script (e.g., alpr_jetson.py) that uses YOLOv4-tiny for license plate detection and OCR for character recognition.
4.Run the Script
this script captures video from the specified camera source, uses YOLOv4-tiny for license plate detection, applies OCR to recognize characters, and displays the frame with license plate information.

Adjust the paths for YOLOv4-tiny weights and configuration files according to your setup. Additionally, consider optimizing the OCR settings and license plate recognition based on your specific use case and requirements.
