YOLOv5 Pothole Detection Project
Overview
Potholes on roads have become a significant issue in Korea due to abnormal climate conditions. The repeated freezing and thawing of roads, coupled with the use of potassium chloride for snow removal, have contributed to asphalt degradation. These potholes not only cause accidents but also disrupt transportation.

This project utilizes YOLOv5 to develop a real-time pothole detection system. The system can help vehicles avoid potholes and notify maintenance teams for timely repairs.

Project Structure
plaintext
코드 복사
├── data.yaml                # Dataset configuration file
├── dataset/                 # Dataset folder
│   ├── train/               # Training images and labels
│   ├── val/                 # Validation images and labels
│   └── test/                # Test images
├── yolov5/                  # YOLOv5 repository
│   ├── models/              # Model configuration files
│   └── runs/                # Training results
├── README.md                # Project documentation
└── detect.py                # Script for running inference
Dataset
Video Sources
Three videos were collected to create the dataset:

News 1
News 2
YouTuber Han Mun-chul
The videos were edited using Clipchamp to create a unified training video.

Annotation
Annotations were created using DragLabel, labeling potholes in individual frames.

Installation
Clone the YOLOv5 repository:

bash
코드 복사
git clone https://github.com/ultralytics/yolov5.git
cd yolov5
Install dependencies:

bash
코드 복사
pip install -r requirements.txt
Prepare the dataset:

Place the annotated images and labels in the dataset/train, dataset/val, and dataset/test folders.
Training
Run the following command to train the model:

bash
코드 복사
python train.py --img 640 --batch 16 --epochs 2000 --data ./data.yaml --cfg ./models/yolov5n.yaml --weights yolov5n.pt --name pothole --patience 0
Parameters:
--img 640: Image size (640x640).
--batch 16: Batch size for training.
--epochs 2000: Number of training epochs.
--data ./data.yaml: Path to the dataset configuration file.
--cfg ./models/yolov5n.yaml: Model configuration file.
--weights yolov5n.pt: Pre-trained weights.
--name pothole: Name for saving training results.
Results
Performance Metrics
Precision-Recall Curve:

F1 Score Curve:

Confusion Matrix:

Test Outputs
Sample pothole detection results:



Detection Video
Trained Detection Video

Usage
Run inference on test images or videos using the trained model:

Inference on test images:

bash
코드 복사
python detect.py --weights runs/train/pothole/weights/best.pt --img 640 --source dataset/test/images --name pothole_detect
Inference on video:

bash
코드 복사
python detect.py --weights runs/train/pothole/weights/best.pt --source video.mp4 --name pothole_detect
Future Work
Expand the dataset to include more diverse road conditions.
Deploy the model on edge devices (e.g., NVIDIA Jetson) for real-time applications.
This project is a step toward improving road safety by detecting and addressing potholes efficiently.
