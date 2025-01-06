# Nut and Bolt Detection with YOLOv9

This repository contains code for training a YOLOv9 model to detect nuts and bolts, and a Gradio app for easy inference.

## Description

This project demonstrates how to:

* Train a YOLOv9 object detection model on a custom dataset of nuts and bolts.
* Evaluate the model's performance.
* Deploy the trained model using Gradio for interactive inference.

## Dataset

The dataset used for this project can be found [here](link-to-your-dataset). It consists of images of nuts and bolts with corresponding annotations in YOLO format.

## Training

The `nut_bolt_training.ipynb` notebook contains the code for training the YOLOv9 model. It covers the following steps:

1. **Data Loading and Exploration:** Loading the dataset and visualizing sample images.
2. **Model Training:** Training the YOLOv9 model using the Ultralytics library.
3. **Model Evaluation:** Evaluating the trained model on a validation set.
4. **Inference:** Running inference on sample images to visualize the results.

## Gradio

The script provides a Gradio interface for interacting with the trained YOLOv9 model. Users can upload an image and get real-time object detection results.

## How to Use

1. **Clone the repository:** `git clone https://github.com/your-username/your-repo-name.git`
2. **Install dependencies:** `pip install -r requirements.txt`
3. **Train the model:** Run the `nut_bolt_training.ipynb` notebook.

## Requirements

* Python 3.7+
* Ultralytics
* Gradio
* OpenCV
* Other dependencies listed in `requirements.txt`


## Acknowledgments

* Ultralytics for the YOLOv9 model and training framework.
* Gradio for the easy-to-use interface for deploying machine learning models.
