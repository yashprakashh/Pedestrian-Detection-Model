# Pedestrian Detection Using Deep Learning

This repository contains the implementation of a deep learning model for pedestrian detection. The model is designed to detect pedestrians in images and draw bounding boxes around them. 

## Contents
- Code for loading and preprocessing pedestrian dataset.
- Bounding box visualizations for detected pedestrians.
- Instructions to run the code and evaluate the model.
- Model weights for the trained/fine-tuned model.

## Requirements

- Python 3.x
- OpenCV
- Matplotlib
- PyTorch

## Dataset

The dataset used for this project contains pedestrian images and bounding box annotations:
https://drive.google.com/drive/folders/1DCpmo919b7OrAng9clEbiMHjO3D0hyoa?usp=sharing


## Once you've opened the Google Colab file, wait for some time for the last output cell to load for the results!

---

## License
# This project is licensed under the MIT License - see the LICENSE file for details.

**Pedestrian Detection Using Deep Learning**

**Introduction**

This project involves building a pedestrian detection model using deep learning techniques. The dataset includes images of pedestrians with bounding box annotations. The goal of this project is to fine-tune a model that can effectively detect pedestrians and draw bounding boxes around them.

**Methodology**

1. **Data Preparation**: 
   - The pedestrian dataset consists of training and validation sets with annotated bounding boxes.
   - Data was preprocessed and split into training and validation folders.

2. **Model Architecture**:
   - A pre-trained deep learning model was utilized for fine-tuning on the pedestrian dataset.
   - Transfer learning was applied to adapt the model to the specific task of pedestrian detection.

3. **Training Process**:
   - The model was fine-tuned using the preprocessed dataset.
   - Loss functions were monitored to ensure effective training.

4. **Bounding Box Visualization**:
   - The bounding boxes were generated using OpenCV for visualization.
   - Visualizations show how well the model performs pedestrian detection in different scenarios.

**Results**

- The model successfully detects pedestrians and draws bounding boxes around them.
- The performance was evaluated based on visual inspection of the bounding boxes.

**Conclusion**

The pedestrian detection model performs reasonably well on the given dataset, producing accurate bounding boxes for detected pedestrians. Future improvements can include experimenting with more advanced models such as DINO.

This report can be expanded further depending on the depth you wish to go into for the project explanation.


