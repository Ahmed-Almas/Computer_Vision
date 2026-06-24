# Material Detection - YOLOv8

## Overview
A deep learning object detection system trained using YOLOv8 to classify product materials 
(plastic vs metal) from images, videos, and live webcam feed.

## Project Structure
Material Detection/
├── main.ipynb              # Model training notebook

├── ColabDetection.ipynb    # Google Colab training version

├── detection.ipynb         # Run and test the custom model (image, video, webcam)

├── images/                 # Training images

├── labels/                 # Annotated label data

├── runs/                   # Training metrics and results

└── videos/                 # Output detection videos

## Tech Stack
- Python
- YOLOv8 (Ultralytics)
- OpenCV
- Google Colab (for training)

## Model
- Architecture: YOLOv8x
- Epochs: 300
- Dataset: Custom annotated dataset of plastic and metal product images

## How to Run

### Train the model (Google Colab)
```python
pip install ultralytics
```
Open `ColabDetection.ipynb` in Google Colab and run all cells.

### Run detection locally
```python
pip install ultralytics opencv-python
```
Open `detection.ipynb` and run the cells for image, video, or webcam detection.

## Results
- Trained for 300 epochs on custom material dataset
- Supports real-time detection via webcam
- Output videos saved to `videos/` folder
