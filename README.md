# NMT (Neural-Machine-Translator)
 Bidirectional RNN, Encodee and Decoder with LSTM layers
[[Open In Colab](https://colab.research.google.com/drive/1oqMOTk5nTdKef4BuL_3AWoGOwwURUojV#scrollTo=MxD2HI5I1rdc)]

# Data

- Data is input as a text file
- the sentences are located by row and comma ',' 
- strings are split and indexed as sentence pairs containing bilinual language data
- the first and second index is encoded and tokenized seperatly
- tokenizers are pickled for decoding prediction 
- encoded data is split to train and test cases
- model contains embedding layer
- repeat vector
- and 2 LSTM layers
- activation function: softmax
- loss function: sparse_categorical_crossentropy
- optimizer: rms prop

# model performance
30 epochs is starting standard
The performance steps flatten out after 35+ epochs
The data could be better

# could possibly Investigate mining applications to gather language data from bilingual books...

