
# YOLOv8 Object Detection Pipeline

Project Overview
This project implements an end-to-end object detection pipeline using YOLOv8n (You Only Look Once) with Python, PyTorch, Ultralytics, and Google Colab.

The system detects multiple objects in images, predicts bounding boxes, applies confidence thresholding, and evaluates model performance using different evaluation metrics.

Technologies Used
- Python
- YOLOv8n
- PyTorch
- Ultralytics
- OpenCV
- Pandas
- Matplotlib
- Seaborn
- Google Colab

Features
- YOLOv8n pretrained model implementation.
- Object detection with bounding-box prediction.
- Confidence thresholding.
- Model training and validation.
- Precision and Recall evaluation.
- F1-score calculation.
- mAP@50 and mAP@50-95 evaluation.
- Six training evaluation graphs.
- Automated accuracy metrics summary table.
- Detection result visualization.

Dataset
The project uses the COCO128 sample dataset for model training and evaluation. Ultralytics automatically downloads the dataset when required.

Project Workflow
1. Install required libraries.
2. Import Python libraries.
3. Configure project directories.
4. Download and prepare the dataset.
5. Load the pretrained YOLOv8n model.
6. Train the object detection model.
7. Evaluate model performance.
8. Generate six evaluation graphs.
9. Create an accuracy metrics summary table.
10. Perform object detection on uploaded images.
11. Save the trained model and evaluation reports.

Evaluation Metrics
- Precision
- Recall
- F1 Score
- mAP@50
- mAP@50-95

 Project Outputs
- Trained YOLOv8n model (`best.pt`)
- Object detection results with bounding boxes
- Six evaluation graphs
- Accuracy metrics CSV report
- Accuracy metrics visualization

 How to Run the Project

1. Open the Google Colab notebook.
2. Install the required dependencies.
3. Run all notebook cells sequentially.
4. Train and evaluate the YOLOv8n model.
5. Upload an image to perform object detection.
6. View and download the generated results.

 Installation

```bash
pip install ultralytics opencv-python matplotlib pandas seaborn pillow
```

  Applications
- Object detection systems
- Computer vision applications
- Image analysis
- Automated visual inspection
- Real-time object detection research

Project Type
Machine Learning | Deep Learning | Computer Vision
