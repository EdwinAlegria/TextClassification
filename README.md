# Multi-Label-Text-Classification
Tensorflow+bilstm+attention+multi label text classify (support Chinese text)

#Network:

  Word Embedding + bi-lstm + attention + Variable batch_size
  
#Requirements

  Python 3.5 (> 3.0)
  
  Tensorflow 1.2

#Introduction
 
   1. This is a multi-label text classification (sentence classification) problem. For example, the format of label is [0,1,0,1,1].
   2. This model was built with bi-lstm, attention and Word Embeddings(word2vec) on Tensorflow.
   3. It supports the variable batch size.(the batch size of test code(prediction) is 1)
   

   4. It supports Chinese text classification, but you need the pretrained word2vector model.
   
   5. input_helpers.py is my data processing code , and you can write it according to yourself dataset.


#python file

Lstm_Attention_network.py: define the network

My_Attention.py: attention code

train.py: train the network

input_helpers.py : data helper code , data processing

