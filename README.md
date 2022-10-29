# Study-the-classification-performance-of-DNN-and-CNN-models
(a) Implementing DNNs - Use the PyTorch package to implement a DNN model with 2 and 3 hidden layers. Each hidden layer contains 512 neurons. What is the performance on the test dataset for this classifier

DNN model with 2 layers
Model is train for 10 epochs.

Training accuracy is 0.9944.

Test accuracy is 0.9793.

DNN model with 3 layers.
Training accuracy is 0.9959

Test accuracy is 0.9795

Both models have nearly same performance


(b) Implementing CNNs - Use the same package to implement a CNN model with one layer of convolutions (kernel size of 3 × 3 with a 2-D convolutional layer and having 128 filters) followed by two dense layers of 256 neurons. Compare the performance of the CNN with the DNN.

CNN model with 128 filters followed by two dense layer of 256 neurons

Model is train for 10 epochs.

Training accuracy is 0.9900

Test accuracy is 0.9734.

CNN model and DNN models have nearly same performance.

(c) Provide your answers with analysis, plots for various choices of hidden layer dimen- sions and filter sizes in the CNN.

Performance with Various choice of hidden layer dimension
Number of filters = 128

hidden layer dimension -----------Training accuracy----------Test accuracy

256                     0.9900              0.9734
128                     0.9902              0.9709
64                      0.9874              0.9667
32                      0.9800              0.9592
Performance with Various choice of filter size
CNN model:

Number of neurons in hidden layer = 256 Number of filters = 128

filter Size --------------------Training accuracy------------Test accuracy

4 x 4               0.9887              0.9705
3 X 3               0.9900              0.9734
2 X 2               0.9907              0.9722   

Accuracy reamins nearly same after 10 iterations.

Performance with Various choice of number of filters
CNN model:

Number of neurons in hidden layer = 256

Number of filters----------------Training accuracy------------Test accuracy

128                     0.9900              0.9734
64                      0.9916              0.9729
32                      0.9935              0.9765
16                      0.9946              0.9778

With decrease in number of filters, performance of models improves.

Observations:

1. Change in number of filters does not affect the performance of models

2. Change in number of dimention of dense layes affect the performance of models
