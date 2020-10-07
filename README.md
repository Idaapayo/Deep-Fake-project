# Deep-Fake-project
A model trained to detect deepfake videos.
These deepfake videos are videos potraying people saying or doing fictious things.
This model uses various computer vision techniques to extact features.
Pre-trained models used for facial recognition and feature extraction include: 
>> Resnet-50, mtcnn - facial recognition 
The model consists of five layers each with max pooling at each layer and a fully connected layer
K-fold cross-validation is used to test accuracy 
