# Text-Generator

Building a deep learning model to generate human readable text using Recurrent Neural Networks (RNNs) and LSTM with TensorFlow and Keras frameworks in Python.

I used a free downloadable book/corpus as the dataset for this project : Alice’s Adventures in Wonderland by Lewis Carroll and opened it by renaming it in a different folder. 

After loading and cleaning the dataset, i converted the characters into integers.I termed "vocab" as my vocabulary that contains all the unique characters of my dataset, i made two dictionaries that maps each character to an integer number and vice-versa.The model built has basically two LSTM layers with an arbitrary number of 128 LSTM units. The output layer is a fully connected layer with39 units where each neuron corresponds to a character (probability of the occurence of each character).The training of the model actually takes few hours, 
depending on the hardware. Increasing batch_size to 256 will make the training faster but will consume lots of time.

