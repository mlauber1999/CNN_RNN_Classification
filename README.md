# CNN_RNN_Classification
Mini project experimenting with CNN and RNN classification models on tinyImageNet dataset.  


In this project, I examine how the classification accuracy of pre-trained convolutional neural network (CNN) and reccurent neural network (RNN) models is affected by model size and architecural complexity.

The models (from small to large) were as follows:

1. Visual Geometry Group 11 (VGG11) vs. VGG19
   [(Simonyan & Zisserman, 2014)](https://arxiv.org/abs/1409.1556)
   
   ![1-s2 0-S0957417422004249-gr13](https://github.com/user-attachments/assets/7c5aa37b-bfb1-4f7c-ba1b-37ebe4a0ad4e)


3. Residual Neural Network 18 (ResNet18) vs. ResNet50
   [(He et al., 2015)](https://arxiv.org/abs/1512.03385)
   
![resnet](https://github.com/user-attachments/assets/c3400c24-72b6-4b16-bc1c-398cefa6d2e7)

4. Inception-V3 vs. Inception-V4
   [(Szegedy et al., 2015)](https://arxiv.org/abs/1512.00567)

![inception](https://github.com/user-attachments/assets/0d54fd96-5900-491d-9f09-bd9627756992)




"Of all the models, the Bidirectional RNN had the lowest RMSE across both the small and large dataset sizes, which is likely due to bidirectional nature capable of identifying patterns that unidirectional models might miss. The model with the biggest change in RMSE between the small and large datasets was the Deep RNN... it is possible that this complex of a model had a hard time with only 10 years of data but then was able to perform drastically better when given a more extensive dataset to learn from."
— Project Report

Skills Demonstrated
Synthetic data generation for time series experiments

Implementation and comparison of advanced RNN architectures in PyTorch

Performance evaluation using RMSE

Visualization and interpretation of time series model predictions

Dependencies
Python 3.x

PyTorch

pandas, numpy, matplotlib

scikit-learn

statsmodels

These markdown files are ready to be pasted into your GitHub repositories as README documents, clearly presenting your skills and approach as a data scientist and machine learning practitioner
