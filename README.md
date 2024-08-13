# Disaster Damage Assessment using Satellite Imagery (Focused on Flood Damage Detection) 

This repository contains the implementation of my final year project for the B.Tech program at VJTI, Mumbai. The project focuses on Post-Disaster Building Damage Assessment for the Nepal Floods of 2017, using Convolutional Neural Networks
The data that was utilized for this project was an open source dataset called the xView-2 Dataset, which contains Pre- and Post-disaster satellite imagery of various natural disasters on Earth.

## Features

### Data Pre-Processing

The data which was in the form of (1024,1024,3) images, was cleaned, labelled, and augmented to increase performance of the Machine Learning model and increase trainability of the same.

### U-Net Architecture for Image Segmentation

This project implements a Double Encoder U-Net architecture using TensorFlow and Keras. The U-Net model is commonly used for image segmentation tasks, particularly in medical image analysis. This implementation includes custom layers, regularization techniques, and data augmentation methods to enhance the model's performance.

### Visualization

The damaged regions were visualized, and interpretations were drawn out for the total damaged area in the image, along with cost of damages using open-source UNESCO data.

## Dependencies

The project requires the following libraries:
- TensorFlow
- Keras
- Pandas
- OpenCV
- Numpy
- Albumentations
- Matplotlib

You can install the required packages using pip

## Data Source

We used [xBD dataset](https://xview2.org/), a publicly available dataset, to train and evaluate our proposed network performance. Detailed information about this dataset is provided in ["xBD: A Dataset for Assessing Building Damage from Satellite Imagery"](https://arxiv.org/abs/1911.09296) by Ritwik Gupta et al.
