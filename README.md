# WebPage-Element-Detect
# Computer Vision Object Recognition Model

## Goal

Develop a computer vision model for object recognition with a focus on identifying elements in a webpage. The objective is to train a model capable of recognizing and tagging various webpage elements, such as Breadcrumb, Checkbox, Container, Dropdowns, Forms, Buttons, Logos, Navigation Dots, Text, Links, Input Fields, Radio Buttons, Modals. The model should create bounding boxes around each identified element and tag them with the corresponding element names.

## Objective

Implement a computer vision architecture to perform element detection and identification using the specified element names as tags. The model should be versatile enough to work on different Figma webpages. Evaluate the model using quantitative metrics and rank submissions based on their performance on sample reference images.

## Sample Reference Images

For evaluation purposes, the model should be able to detect elements from Figma webpages similar to the ones found in the sample reference images. Example Figma webpage: [Tortilicious - A Fast Food App](https://www.figma.com/community/file/1132396044075007632/tortilicious-a-fast-food-app).

## Sample Results

Example results showcasing the model's ability to generate bounding boxes and tags for various elements can be found [here](https://drive.google.com/drive/folders/16jbyjKMfgdv6l5QHLaDRH44kv4iAwCgZ?usp=sharing).

## Deliverables

1. **Well-documented Code:**
   - Clearly annotated code with comments explaining each part of the implementation.
   - Code structure and organization for clarity.

2. **Trained Model Weights:**
   - Provide the trained model weights to enable others to use and evaluate the model.

3. **Evaluation Metrics and Visualizations:**
   - Quantitative metrics for model evaluation.
   - Visualizations, such as precision, recall, and mAP scores, to demonstrate the model's performance.

## Usage

1. Clone the repository:

   ```bash
   git clone https://github.com/your_username/your_repository.git
   ```

2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Download the pre-trained model weights (if available) or train the model using the provided dataset.

4. Run the model on new Figma webpages to identify and tag elements.

## Evaluation

Evaluate the model's performance using the provided sample reference images and compare the results against the sample results provided. Quantitative metrics should be reported in the documentation.

Feel free to customize this template according to your specific project details. Provide additional information, instructions, and insights that would be helpful for others using or contributing to your project.
### For Dataset:
[Click here](https://drive.google.com/drive/folders/1l20LEKqQZW7ZP-kuCQbWh1DAD6MASNlQ?usp=sharing)
