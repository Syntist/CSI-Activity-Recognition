# CSI-Activity-Recognition
Human Activity Recognition using Channel State Information for Wifi Applications. A simple Tensorflow 2.0+ model using Bidirectional LSTM stacked with one Attention Layer.


## What is RF Sensing?
RF sensing in deep learning refers to the use of wireless signals, such as Wi-Fi or
Bluetooth, to sense and infer information about objects and their environment. It involves
analyzing changes in the amplitude, phase, and frequency of the signals to determine
characteristics such as distance, movement, and material composition. This technique has
applications in fields such as robotics, healthcare, and security.
## Notebook:
CSI Activity Recognition Notebook (made a test account to upload dataset 13gb)
## Model Architecture:
![image](https://user-images.githubusercontent.com/24858150/229932184-00cda7eb-c325-4e90-be87-c5fc31746a17.png)
## Accuracy: 
As you can see, the accuracy of the model increased gradually, but I was limited to using 20 epochs due to the RAM constraints on Google Colab. Typically, increasing the number of epochs can improve the accuracy of the model by allowing it to learn more complex patterns in the data. However, it's important to monitor the model's performance on a validation set as the number of epochs increases, as there is a risk of overfitting the model to the training data.	
![image](https://user-images.githubusercontent.com/24858150/229932355-fa1603c4-eac7-48f5-bfa4-1f7732ce92aa.png)
## Confusion Metrics: 
![image](https://user-images.githubusercontent.com/24858150/229932356-f16631da-c366-4452-90b4-05503b745156.png)
The model appears to perform well based on the given data, as demonstrated by the confusion matrix where most of the predicted results are accurate. However, increasing the accuracy further may require adjusting the model's parameters or training for more epochs. It's important to carefully evaluate the model's performance on a validation set and consider various strategies for improving the model, such as using a different architecture or adjusting hyperparameters.
## Impact of channel change on the classification over different domain:
RF sensing performance can be impacted by channel changes, especially when applied across different domains such as persons, locations, or environments. This can affect the classification accuracy by altering the signal's characteristics. To overcome this issue, researchers have developed techniques such as channel equalization and feature normalization to mitigate channel variations and enhance the classification performance. Additionally, domain adaptation and transfer learning approaches can also be implemented to improve classification accuracy across different domains.
