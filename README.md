# Calm-Uncalm-Image-Classification-with-Image-Generative
The aim of this research is to carry out image classification on an image that uses an adjective.

Mostly image classification is to classify an object (Noun) such as a car, bike, cat, dog, etc.

The dataset was obtained from image generative AI on Dall E and stable diffusion. 
There are 2 datasets used :
1. Primary datasets, totaling 1024 images with 2 classes, namely Calm and Uncalm.
   These datasets can be seen at https://huggingface.co/datasets/yhutagal/Calm_Uncalm
   
3. Feature datasets, only 200 in number with 2 classes, namely Calm and Uncalm.
   These datasets can be seen at https://huggingface.co/datasets/yhutagal/comparison_calm-uncalm_datasets

Binary image classification, using the algorithms:
1. Support Vector Machines (SVM)
2. Convolutional Neural Network (CNN)
3. Transfer Learning using Resnet50 (TF-Resnet50)
4. Vision Transformers (ViT)

Meanwhile, the generative image results use a diffusion model with timestep = 1000
