# Covid19_Detector
> A deep learning approach to detect Covid-19 coronavirus with X-Ray images

## Workflow
![Screenshot from 2022-12-24 00-36-11](https://user-images.githubusercontent.com/76884959/209395448-b2069151-c511-48d5-a757-c9a35ddb5e1b.png)

## Model
- The Rectified Linear Unit (ReLU) has been used in the activation function with a convolutional layer which is helpful to increase the nonlinearity in input image, as the images are fundamentally nonlinear in nature.
- Max pooling has been used because others may not identify the sharp features easily as compared to max pooling.
- The dropout layer with a 20% dropout rate has also been used, which drops the neurons during the training chosen at random to reduce the overfitting problem. 
- Flattening layer is added to convert the output of convolutional layers into a single-dimensional feature vector.

## Conclusion
- The model training was performed incrementally with different datasets to attain the maximum accuracy and performance.
- After preprocessing of the dataset, the final dataset consisted of a total of 284 X-ray images. For training and testing the proposed CNN, the dataset was partitioned into two subsets. The training dataset contained 224 X-ray images, and the validation dataset contained 60 X-ray images.
- The model achieved an overwhelming accuracy of 97%.
