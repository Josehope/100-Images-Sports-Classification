
# 100 Sports Images Classification

This goal of this project was to create a model that will identify and classify different sports Images, 100 different sports images were used in training this model, the images were divided into three namely 

* Train data

* Valid data

* Test data

The train data contains #13,572 images, while the valid data and test data contains #500 images respectively.

EfficientNetB7 model was used for this model, to utilise the trained layers, while unfreezing the last 5 layers in the model, to enable the transfer learning model adjust to our own model.

While compiling the model 10x lower learning rate was used as a method of fine tuning the model, to improve its accuracy

The model was trained for #10 epoch, and after training, the model was tested on the the test data which has not be used before and the accuracy of the model was at 94% while the loss was at 0.2184

Below is the loss and accuracy curves plotted to get a visual representation of how the model performed

![]()

Below also is also the visual representation of how the model predict some images from the test dataset

![]()

Custom images were downloaded from the internet to test how well the model will perform in the wild when deployed, and the following images below were the results gotten from the test

![]()


