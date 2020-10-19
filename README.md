# Chinese-MNIST-using-CNN
3 approches for chinese mnist using cnn

1st approach : CNN with 2X(Convolution- Maxpooling - Dropout) and 2X(Convolution- Maxpooling - Batch Normalization - Dropout) and then 5 X Dense and final softmax Classification


2nd approach : CNN with 2X(Convolution - PReLU - Maxpooling - Dropout) and 2X(Convolution - PReLU- Maxpooling - Batch Normalization - Dropout) and then 5 X Dense and final softmax Classification

3rd approach :  Using only the cnn part of approach 2 to get embeddings I use and SVM with linear to get prediction from those embeddings

Data is available at : https://www.kaggle.com/c/mnist-but-chinese/data
