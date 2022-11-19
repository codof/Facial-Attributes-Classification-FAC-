# Facial-Attributes-Classification-FAC-
Undergraduate Project
A popular component of computer vision and deep learning revolves around 
identifying faces for various applications from logging into your phone with your face 
or searching through surveillance images for a particular suspect. This project mainly 
aims at recognizing facial attributes such as finding people with brown hair, are 
smiling, or wearing glasses.

We use CNN for this purpose. Deep Convolutional Neural Networks (CNNs) achieve 
substantial improvements in face detection in the wild. Classical CNN-based face 
detection methods simply stack successive layers of filters where an input sample 
should pass through all layers before reaching a face/non-face decision. Inspired by 
the fact that for face detection, filters in deeper layers can discriminate between 
difficult face/non-face samples while those in shallower layers can efficiently reject
simple non-face samples, multiple CNN’s can be stacked.

Moreover, some methods using convolutional neural network are trained based on the 
fixed loss weights without considering the differences between facial attributes. In 
order to address the above problems, cascaded convolutional neural network method,
termed MCFA, can be used for predicting multiple facial attributes simultaneously.

Recently, Facial Attribute Classification (FAC) has been gaining significant attention
from the Computer Vision Community. Great progress has been made along with the
availability of challenging FAC datasets, like MCFA mentioned above. However not
many practical application has been developed based on Facial Attribute
Classification, as much like the training images, the test images are required to be face
aligned images. This makes it difficult to apply on images of group of people or on
live camera feed. We propose a method where first faces are detected in an image ,
and trained model is applied on this group of faces for feature classification of each
face in an image. The same method can be followed for video frames and live camera
feed
