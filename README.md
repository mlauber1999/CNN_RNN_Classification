# CNN_RNN_Classification
Mini project experimenting with CNN and RNN classification models on tinyImageNet dataset.  


In this project, I examine how the classification accuracy of pre-trained convolutional neural network (CNN) and reccurent neural network (RNN) models is affected by model size and architecural complexity.

The models (from small to large) were as follows:

1. Visual Geometry Group 11 (VGG11) vs. VGG19
   [(Simonyan & Zisserman, 2014)](https://arxiv.org/abs/1409.1556)
   
   ![1-s2 0-S0957417422004249-gr13](https://github.com/user-attachments/assets/7c5aa37b-bfb1-4f7c-ba1b-37ebe4a0ad4e)


3. Residual Neural Network 18 (ResNet18) vs. ResNet50
   [(He et al., 2015)](https://arxiv.org/abs/1512.03385)
   
 ![resnet50](https://github.com/user-attachments/assets/89f0c4dd-2b1f-4b42-b0c2-7d4d04b3bb01)


5. Inception-V3 vs. Inception-V4
   [(Szegedy et al., 2015)](https://arxiv.org/abs/1512.00567)

![inception](https://github.com/user-attachments/assets/0d54fd96-5900-491d-9f09-bd9627756992)


Results

<img width="611" alt="Screenshot 2025-06-30 at 10 51 22 AM" src="https://github.com/user-attachments/assets/46858bbd-753d-47ac-9817-07c10c154115" />

Key Findings
* ResNet-18 (small) achieved the highest accuracy (61.84%) and was the fastest to train among all models.

* VGG-19 (large) was the top large model (56.63% accuracy) and trained faster than ResNet-50 and InceptionV4.

* Smaller models outperformed larger ones in single-epoch training, likely due to faster convergence and less overfitting risk when training time is limited.

* Larger models may require more epochs to leverage their capacity, which was not feasible under the experiment's constraints.

Skills Demonstrated
* Transfer learning and fine-tuning of deep CNNs

* Efficient data loading and preprocessing for large-scale image datasets

* Comparative analysis of model architectures

* Performance evaluation under computational constraints
