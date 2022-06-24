# Deep_Learning_MY_Learning
In this Repository I am uploading my learnings of deep learning. 
1. **ANN_classification_MNIST .ipynb**
   - Created three models 
   - Model 1 
     - Simple model without using any regularization,Normalization 
     - Having Very Low accuracy 8.6 % 
   - Model 2 
     - Included Callbacks Functions such as Tensorboard , Early Stopping and Model Checkpointing 
     - Batch Normalization and Relu. 
     - Adam Optimizer ( Validation accuracy 97.98 %)
     - SGD Optimizer( Validation accuracy   96.90%) 
   - Model 3 
     - Dropout Layers helped to increase Accuracy of model upto 98.08 %


2. **Conventional & Unconventional method for CNN**
  - Difference between Regular CNN and Unconventional Methods of CNN
  - Model 1 regular CNN method with some Dense layer : Trainable params: 293,682 with an accuracy of 99.13%
  - Model 2 Unconventional CNN Method with Dense layer: Trainable params: 9,994 with an accuracy of 99.36%
  - Model 2 has a less trainable param compared to model 1 with high accuracy.
  - Parameter training consumes a lot of resources and time so we should choose a model with fewer parameters and high accuracy
