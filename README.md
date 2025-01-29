# Fake vs Real Image Classification (Hackathon)

## Description
This project is designed to classify images as either real or fake, specifically targeting altered images in car technical inspections. The model utilizes ResNet to differentiate between genuine and manipulated images.

## Dataset
[The dataset](https://www.kaggle.com/datasets/adilakimshe/datasaur/ - dataset.) consists of images of cars, where some have been altered to manipulate inspection results. The images are preprocessed and augmented before being fed into the model.


## Model Architecture
The model is based on **ResNet**, a deep convolutional neural network architecture known for its residual learning framework, making it highly effective for image classification tasks.

## Installation & Dependencies
To run this project, install the required dependencies:

```bash
pip install tensorflow numpy pandas matplotlib seaborn opencv-python
```

## Usage
Run the following command to train the model:

```bash
python train.py
```

To test the model on new images:

```bash
python predict.py --image path/to/image.jpg
```

## Results
The model achieves high accuracy in distinguishing between real and fake images, making it a reliable solution for detecting fraudulent alterations in car inspections.

## Acknowledgments
This project was developed as part of a hackathon challenge focused on image authenticity verification.

