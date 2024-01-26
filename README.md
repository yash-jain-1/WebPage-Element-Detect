# WebPage Element Detection using YOLO v8

## Introduction

This repository contains the code and resources for a computer vision model designed for object recognition, with a specific focus on identifying various elements in a webpage. The model is based on YOLO v8 and is fine-tuned on a custom dataset using transfer learning.
Model is deployed here [Click Here](https://huggingface.co/spaces/the-insightful-muon/web_element_detection)

## Model Architecture

The YOLO v8 model serves as the base for our implementation, and it is fine-tuned on a custom dataset that includes webpage elements such as Breadcrumb, Checkbox, Container, Dropdowns, Forms, Buttons, Logos, Navigation Dots, Text, Links, Input Fields, Radio Buttons, and Modals. The objective is to create bounding boxes around each identified element and tag them with the corresponding element names.

## Sample Reference Images

For evaluation purposes, the model has been tested on Figma webpages similar to the ones found in the sample reference images. You can find an example Figma webpage [here](https://www.figma.com/community/file/1132396044075007632/tortilicious-a-fast-food-app).

## Sample Results

Example results showcasing the model's ability to generate bounding boxes and tags for various elements can be found [here](https://drive.google.com/drive/folders/10j2PMnPv1tgYymF9flA_K0leisTsZaj4?usp=sharing).

## Dataset

The dataset used for training and evaluation can be accessed [here](https://drive.google.com/drive/folders/1yndL5NKCxBdOg0Gjfx7hKpqgPjlkXgbJ?usp=sharing).

## How to Use

1. Clone the repository:

   ```bash
   git clone https://github.com/yash-jain-1/WebPage-Element-Detect.git
   ```

2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Download the pre-trained model weights (if available) or train the model using the provided dataset.

4. Run the model on new Figma webpages to identify and tag elements.

## Evaluation

Evaluated the model's performance using the provided sample reference images and compared the results against the sample results provided. Quantitative metrics, such as precision, recall, and mAP scores, are reported in the documentation.

Feel free to improve or contribute to the repository

