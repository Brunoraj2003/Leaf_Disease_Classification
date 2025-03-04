🍃 Mango Leaf Disease Classification

📌 Overview

This project focuses on classifying mango leaf diseases using computer vision techniques. By leveraging object detection models like YOLOv5 and YOLOv8, the system identifies and categorizes different diseases affecting mango leaves, enabling early intervention for better crop health management.

🏆 Features

✅ Automated detection of six mango leaf diseases

✅ Utilizes YOLOv5 & YOLOv8 for object detection

✅ High-accuracy classification using polygon labeling

✅ Scalable for integration with mobile or IoT-based monitoring

📂 Dataset

The dataset comprises labeled images of mango leaves in different health conditions, sourced from:

📌 Kaggle Datasets: Dataset 1, Dataset 2

📌 Manual Image Collection: Captured real-world images of infected leaves

Diseases Identified

1. Anthracnose     
2. Powdery Mildew    
3. Sooty Mold    
4. Gall Midge   
5. Die Back   
6. Bacterial Canker   
7. Healthy Leaves  

🚀 Model Training & Evaluation
The dataset was split into training, validation, and testing sets. Two models were trained and evaluated using accuracy, precision, recall, and F1-score.

![image](https://github.com/user-attachments/assets/aabe2185-be38-43f9-84ff-4ecaad864e3c)

✅ YOLOv8 outperforms YOLOv5 in accuracy, making it suitable for high-performance applications.

🛠️ Installation

To run the project, ensure you have the following installed:

Python 3.x
OpenCV (cv2)
PyTorch
Ultralytics YOLO (pip install ultralytics)


🔥 Usage

Training the Model

python train.py --model yolov8 --epochs 50 --data mango-leaves.yaml

Running Inference

python detect.py --weights best.pt --source test_images/

📈 Results
Confusion matrices,          F1-scores,     and         inference outputs validate the effectiveness of the models.

🔗 References
[YOLOv5 GitHub](https://github.com/ultralytics/yolov5)
[YOLOv8 GitHub](https://github.com/ultralytics/ultralytics)
