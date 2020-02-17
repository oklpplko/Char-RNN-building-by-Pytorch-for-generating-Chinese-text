# Char-RNN-Pytorch
Char-RNN building by Pytorch for generating Chinese text

## Requirements
* python 3.5
* Pytorch 0.3.X
* CUDA

## Instruction
1. data_preprocess.py is used for generating the vocabulary, converting texts to indexes or indexes to texts

   data_preprocess.py

2. exps.py lists hyperparameters for this project including the filename of the training data. Training data is not provided here to avoid the infringement of copyright.However, crawler scripts were uploaded for crawling data.

3. model.py includes the RNN model built by Pytorch

4. train.py is used for training the model, printing the output texts every epoch for training set and every two epochs for dev set

5. sample.py is used for generating texts using the trained model, since the saved pkl file is to large to upload, you need to train the model youself and change the directory for loading your model when sampling

6. Data set(writing of primary students) is crawled from the internet. The data is used for training the RNN to generating essays.
