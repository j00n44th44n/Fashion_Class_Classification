# Udemy - Machine Learning Practical 6 Real-World Applications
### CNN (Convolutional Neuronal Network) Fashion Class Classification
###### dataset inside the project folder

[70 000] [28x28] grayscale images
classified into 10 classes

#### 0 => T-shirt/Top
#### 1 => Trouser
#### 2 => Pullover
#### 3 => Dress
#### 4 => Coat
#### 5 => Sandal
#### 6 => Shirt
#### 7 => Sneaker
#### 8 => Bag
#### 9 => Ankle boot

image kernel change
setosa.io/ev/image-kernels/

> Concepts
RELU activation function pop up in a way relevant features shouting down the values below cero
### Convolution
### Pooling (Max-pooling/Average-pooling/Min-pooling)
it used to reduce feature map dimensionality
generalize by avoiding overfitting
works by retaining (some value acordding to a specific criteria) within a given sample size in a feature map
### Flattening
convert the result of a Pooling (matrix [n,n]) into an array [1,n * n]

CNN example with numbers
scs.ryerson.ca/~aharley/vis/conv/flat.html

> Improving the model
ideas:
Increasing the number of kernels (feature detectors) (32 used) -> 64,128
During training shout down some nodes(drop out) (reduce overfitting)

vue.ai
mmlab.ie.cuhk.edu.hk/projects/DeepFashion.html

> sigmoid(x) = 1/(1+e-x) [binary output]

> ReLU(Rectified Linear Units) f(x) = max(x,0) 

> SoftMax [classification problems]