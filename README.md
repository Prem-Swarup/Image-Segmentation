# Image-Segmentation Project
### A deep learning and computer vision project to segment and locate the image of humans with various backgrounds

- used U-net architechture with efficientnet-b0 as encoder for CNN to train the model
- used albumentations for randomly augment the image with correspondin the mask
- used a combination of Binary Cross Entropy loss and Dice loss for computing loss
- used OpenCV for reading and pre-processing images
- used cuda runtime for faster training
