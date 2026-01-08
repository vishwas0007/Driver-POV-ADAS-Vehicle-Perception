Project Title:
Driver POV ADAS Vehicle Perception System

Description:
This project implements a camera-based Advanced Driver Assistance System (ADAS)
using Python and Computer Vision techniques. The system analyzes driver point-of-view
(dashcam) videos to detect vehicles ahead and estimate their relative distance, speed,
and color using a single camera.

Key Features:
- Vehicle detection using YOLOv8
- Monocular depth estimation using an autoencoder-based model (MiDaS)
- Relative distance estimation from depth maps
- Relative speed estimation using frame-to-frame depth variation
- Vehicle color detection using RGB clustering
- Annotated output video generation from driver POV input

Technologies Used:
- Python
- PyTorch
- OpenCV
- YOLOv8
- MiDaS (Autoencoder-based depth estimation)
- Computer Vision

Input:
Raw driver point-of-view dashcam video.

Output:
Annotated video showing detected vehicles with bounding boxes, relative distance,
relative speed, and vehicle color.

Note:
Distance and speed values are relative estimates derived from monocular vision.
This project is intended for ADAS simulation and research purposes.

Author:
Vishwas Puranikamath
