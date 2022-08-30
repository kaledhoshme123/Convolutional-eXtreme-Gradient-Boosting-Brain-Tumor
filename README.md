# Convolutional eXtreme Gradient Boosting Brain Tumor Classification
- Convolutional eXtreme Gradient Boosting for classification of brain tumors based on convolutional neural networks and XGBoost.
- Convolutional eXtreme Gradient Boosting consists of several stacked convolutional layers to recognize input features and is able to learn the features automatically, after performing the required training of the convolutional neural network on brain tumor images, we will extract the last layer preceding the Dense classification layers (the layer named GlobalAveragePooling2D_ while building the proposed neural network) and from it we will extract the features and train XGBoost in the last layer.
- The study shows the difference between the accuracy that was achieved by using CNN alone, and the accuracy that was combined with XGBoost.
- The results show that the integration of CNN with XGBoost leads to a higher accuracy than that achieved using CNN alone.
![_مخطط دون اسم_ drawio (1)](https://user-images.githubusercontent.com/108609519/187561519-b525707e-a51f-45cf-89f1-3923e786a858.png)

# Images Dataset:
## Before Augmentation:
![download (63)](https://user-images.githubusercontent.com/108609519/187560254-ebda6472-d5df-466a-8aac-1645ef2e6f71.png)
## After Augmentation:
![download (64)](https://user-images.githubusercontent.com/108609519/187560337-2b9bfe51-961f-4ab0-8be7-70d8fd24d8d0.png)
# Result:
![_مخطط دون اسم_ drawio (2)](https://user-images.githubusercontent.com/108609519/187561965-6535a691-4f9b-446e-bc62-6e02716a11b2.png)


