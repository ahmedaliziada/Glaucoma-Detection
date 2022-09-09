# Glaucoma Detection Using Fundus Images and Convolution Neural Network
![Web 1920 – 1](https://user-images.githubusercontent.com/95842589/189410516-f132c82d-77c9-457e-9204-1f4c8d612619.png)

## Abstract
 There is no doubt that, the glaucoma is one of the most common causes of lifelong blindness among people. It is a disorder that causes gradual damage 
to the optic nerve over a period of time, resulting in a partial loss of vision. Glaucoma is a disease that affects most people all around the world, 
and it is one of the leading causes of blindness among people over 60 years of age. In order to avoid permanent vision loss as a result of this disease,
early detection is crucial. Fundus imaging using a retinal camera is the most common method of screening for glaucoma, and it is widely used in the detection
of this disease. As part of this study, we would be using the fundus images from the retina in order to train the system using the fundus images in order to 
improve the performance of the system. We will use the Convolution Neural Network Technique in order to predict the possibility of occurrence of Glaucoma based 
on this 
prediction.

## What is Glaucoma ?
Glaucoma is classified as a group of eye diseases that 
cause blindness. It happens due to an increase in eye pressure 
which is caused by a reduction of aqueous humor outflow. The 
increase in pressure causes compression in the optic nerve 
causing damage to it. Glaucoma also causes a change in the 
anterior structure; this changes the imaging techniques utilized 
to determine whether there is glaucoma or not.





## Data manipulation
 ## 1) Data preprocessing
    1- Convert images to Grayscale
    2- Remove noise
    3- Resize images
![image](https://user-images.githubusercontent.com/95842589/189408162-36c7bd45-5b14-484f-9855-6526cf926bfd.png)
![image](https://user-images.githubusercontent.com/95842589/189408194-2c720050-6b1d-4edb-abd2-ee83fec58589.png) 

               Before preprocessing                                  After preprocessing




 ## 2) Data Augmentation
 By applying data augmentation on the fundus images, it helps to expand the size of train and validation sets by creating modified data from the existing one
by rotation, rescaling, flipping, shifting, sharing, zooming, brightness, and normalization. To make the model learn on all the sides of the images to make it 
easy to it while predicting that help to avoid the overfitting. 
## Modeling
convolution Neural Network (CNN) used in image 
recognition and processing that is specifically designed to 
process pixel data. The main advantage of CNN compared to 
its predecessors is that it automatically detects the important 
features without any human supervision. It learns distinctive 
features for each class by itself. CNN is also computationally 
efficient. The reason to select CNN model that it can 
overcome some problem in some machine learning 
algorithms (logistic regression, random forest, SVM) that 
require proper features to perform the classification that may 
fail to classify properly and the classifier accuracy will be 
lower. Second, when the required features and the appropriate 
classification model are selected to improve the training, they 
take a lot of time. So, CNN the best choice to classify this 
fundus images.

![image](https://user-images.githubusercontent.com/95842589/189408870-7d270d6c-2c23-4ed7-948a-0c580bc632cd.png)

