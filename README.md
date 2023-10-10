# Project Name
Problem statement: To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution which can evaluate images and alert the dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.




## General Information
There was the 2239 images for the 9 classes in the training dataset
There was 447 images for the validation data set
Data set for training was divided in two traininig set and validation set with 80 and 20 percent respectively
Datset images was set into 180 * 180 image height weight and a batch of 32 was created
Data was trained and validated using keras.
First model was created with 3 convolution layer and 3 max pooling after rescaling 
Activation used was relu and padding same . 
Last layer used was softmax before that flatten followed by dense layer 
Model was compiled optimizer='adam' and loss='sparse_categorical_crossentropy'
Model was trained using 20 epochs
Second Model created after augmentation and using the Dropout
The model used 3 convolution , 3 Dropout ,Flatten, Dense layer with relu Activation in the threelayers and the softmax in the final layer
Third model was created after class imbalance was the handled . 
Third model used the 2 convolution and 3 dropouts followed by flatten and Dense layer.
Third model was done with 30  epochs





<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
First model created with the 3 convolution layers and we found the issue of overfitting . 
The traing data set had 90% and the validation data set was 50%

Second model to tackle the overfitting the augmentation of the image was done 
and the Dropout was used .
the overfitting was removed the training and validation was 63% and 60% respectively
to improve the performance we performed the third model 

Third model was done after adding 500 images to tackle the class imbalance 
Then the model was trained after the 500 images was added .Total images now was 4500
Model trained with 3 convolution layer with Maxpooling and Dropout in each layer 
MOdel perfomance was imporved training performance was 91% and validation was 83%




<!-- You don't have to answer all the questions - just the ones relevant to your project. -->




## Contact
Created by [@gykamal] - feel free to contact me!
Gyanesh Kamal


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project --># Project Name
> Outline a brief description of your project.


