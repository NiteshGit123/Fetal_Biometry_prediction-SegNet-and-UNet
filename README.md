# SegNet Image Segmentation

This repository provides a full implementation of the SegNet model for image segmentation tasks. SegNet is a deep learning architecture tailored for semantic segmentation, allowing for the classification of each pixel within an image. In this project, the objective is to predict the mask for the head of a fetus, with the annotation masks serving as labels in the dataset. I have trained several classical segmentation models, including SegNet and UNet, for mask prediction.


## Features

- Implementation of the SegNet architecture.
- Custom dataset loader for easy integration of your image data.
- Loss functions including Binary Cross-Entropy (BCE) and Dice Loss for improved training.
- Training and validation scripts with logging.
- Preprocessing steps for image and mask data.
