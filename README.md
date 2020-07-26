# Custom VGG16 Model for TinyImageNet Classification
## Abstract
The dataset for this project is a small scale version of the ImageNet Large Scale Visual Recognition Challenge (ILSVRC). In this project, I approached the image classification problem by using transfer learning on custom VGG16 CNN architecture. I have also applied data augmentation methods to training images, hoping to artificially create variations that help the model to generalize better. The model performed well and achieved 56.23 % accuracy on the validation set.
## Dataset
The dataset contains square images, of 64×64 pixels. Most of the images have 3 channels for color, RGB, meaning they are 64x64x3 arrays. However, some of the examples are grayscale images, i.e. 64×64×1 arrays. For the sake of simplicity, all the grayscale images are immediately converted to RGB by replicating the pixel values across the three channels. Each image belongs to exactly one out of 200 categories. The training set contains 90,000 images (450 from each category), and the validation and test sets have 10,000 images each (50 from each category).
## Getting Started
The **custom_vgg16_for_tiny_imagenet.ipynb** notebook can be directly run on the Kaggle Kernel. Use Kaggle's Nvidia Tesla P100 GPU for faster training and evaluation.
The dataset can be downloaded from <a href="https://drive.google.com/file/d/116KlGk5ExxS5QCaIQBXRxWCC4SzNjYVB/view?usp=sharing">here.</a>
## Detailed Report
A detailed report of this project is available <a href="https://drive.google.com/file/d/1teDoAIaFQiQ5u_-ULcGo4QIi9Qxezqui/view?usp=sharing">here.</a>
## Authors
* Ayush Dabra
## Acknowledgments
I express my sincere thanks to Dr. Laxmidhar Behera, who provided me with the opportunity to work on this project. I pay my deep sense of gratitude to Dr. Vipul Arora, without whose valuable guidance and supervision the project couldn't have been completed.
