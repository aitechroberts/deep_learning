
# Convolutional Neural Nets 
1. Concept of Representation and Learning 
- We need a Universal Representation Learner to ease the learning 
2. How to learn robust representation 
- Need a representation learner that can utomatically learn the features needed for the task
3. How to learn spatial, high level features 
- Since high level spatial (not pixels) we need a scanner to scan patches of data instead of single pixels 
4. How to build a scanner for feature learning?
- Matrix for machine readable
- Learnable
- Flexible in size and dimension
- Pluggable to Neural Networks
5. Can we design scanners based on learning tasks?
Yes, and we should. Because mode of data might be different (sound, image, video) and features are needed based on task to make a good model, scanner should only learn relevant features connecting them to output

Occurs convolution and neural network simultaneously so that the NN learns the most important features from the picture
- Softmax forces this
    - Activation layer is the featurized image of the original images and applies the learning back to the image features

Biggest concepts of CNNs
- Significant reduction in the number of feature weights

Strides- Basically just changing the size of the step of the kernel box
- Creates more important features
Pooling by downsampling
- Helps make it invariant (less affected) by say smaller transformations like if a feature was oriented a different way or upside down, etc.



