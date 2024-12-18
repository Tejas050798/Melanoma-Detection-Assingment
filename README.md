# Project Name : MELANOMA DETECTION ASSINGMENT

To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution which can evaluate images and alert the dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.



## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- Need to identify correct images from ISIC dataset of 9 classes of skin diseases using CNN model.
- We need to read, visualize and train the CNN model which can detect the classes correctly using proper hyper parameter tuning.
- We need to use augmentation technique to address overfitting and for handling class imbalance.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- initial model was overfitted, with training accuracy of 80% and validation accuracy of 21%
- Adding augmentation techniques to address overfitting lead to an undertrained model with training accuracy of 52% and validation accuracy of 22%.
- We observed that classes were imbalanced hence we used augmentation package to handle class imbalance and finally got training accuracy of 73% and validation accuracy of 40at 30 epochs.


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- numpy - version 1.26.4
- pandas - version 2.1.4
- matplotlib - version 3.8.0
- tensorflow - version 2.17.1
- keras - version 3.5.0

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->



## Contact
Created by [@Tejas050798] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->