In order to perform the Image Classfication we tried the following:

1. Create CNN model from scratch
2. Fine Tune Resnet-18 model on dataset
3. Fine Tune Resnet-18 model on agumented dataset

**Results**:
1. CNN(Convolutional Neural Network):
   Test Accuracy: 0.6789
   Test F1-Score: 0.6741
   The CNN architecture achieved an accuracy of around 67.89% on the testing dataset.
   
2. ResNet-18 with dataset:
  Test Accuracy: 0.8824
  Test F1-Score: 0.8820
  The ResNet-18 architecture achieved an accuracy of around 88.24% on the testing dataset.

3. Augmented Dataset with ResNet:
 Test Accuracy: 0.9332
 Test F1-Score: 0.9336
 The augmented dataset with ResNet achieved the highest accuracy of around 93.32% on the testing dataset.

**Conclusion**:

 The ResNet model showed significant improvement over CNN, achieving an accuracy of 88.24%. 
 ResNet is known for its deep architecture with skip connections,
 which helps mitigate the vanishing gradient problem and enables
 the training of very deep neural networks. However The
 combination of an augmented dataset and the ResNet
 architecture yielded the highest accuracy of 93.32%. Augmenting
 the dataset likely provided more diverse examples for the model
 to learn from, making it more robust to variations in the input data.
 Additionally, leveraging the pre-trained ResNet model, possibly on
 the ImageNet dataset, allowed the model to capture more
 abstract features, contributing to its superior performance.
