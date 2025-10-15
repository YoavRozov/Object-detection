# FRC Object Detection Tutorial\Showcase with Synthetic Data

[Showcase](/media/Showcase.png)

## Description
This repository provides a complete tutorial for generating synthetic image data using Blender and training YOLO models for object detection, segmentation, and oriented bounding boxes (OBB). It is designed for FRC teams to learn how to create datasets and train models efficiently using synthetic data.

## Advantages of Synthetic Data
This approach is highly versatile and powerful, with no inherent limits. By leveraging Blender's capabilities, we can continuously add more complex and randomized environments to create richer and more diverse datasets. This methodology is not restricted to FRC applications and can be extended to various domains requiring high quality synthetic data for training machine learning models.

## Repository Contents
- **Presentation**: Tutorial slides explaining object detection, synthetic data, and Blender workflow.
- **Blender File**: Includes Coral and Algae game pieces (FRC 2025) and a basic environment.
- **Python Notebooks**: Demonstrate automation of Blender, dataset generation, annotation creation, image processing, and YOLO training.
- **Source Code**:
    - Guide on how to setup the Blender file.
    - Scripts to generate YOLO annotations (object detection, segmentation, OBB).
    - Scripts to preprocess images (e.g., grayscale conversion).
    - Scripts to train YOLO models.

## Installation Instructions
### Blender
Download and install Blender from [www.blender.org/download/](https://www.blender.org/download/).

### Python Environment
Install required Python packages:
```
pip install ultralytics opencv-python
```

## How to Use
1. **Start with the Presentation**: Understand the concepts of object detection and synthetic data.
2. **Open the Python Notebook `BlenderGeneratorGuide.ipynb`**: Follow the steps to automate Blender.
3. **Blender File**: Use the provided Blender file to render synthetic images of Coral and Algae game pieces.
4. **Use the Python Notebooks under `ProcessBlenderData`**: Follow the steps to generate datasets, and train YOLO models.

## Workflow
1. Automate Blender to render synthetic images with randomized positions, lighting, and camera angles.
2. Preprocess images (optional grayscale conversion).
3. Generate YOLO annotations:
    - Object Detection
    - Segmentation
    - Oriented Bounding Boxes (OBB)
4. Train YOLOv11 models using Ultralytics library.
5. Run inference on new images using trained models.

## YOLO Formats Supported
- **YOLOv11 Object Detection**
- **YOLO Segmentation**
- **YOLO OBB (Oriented Bounding Boxes)**
