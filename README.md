Please refer to [ProjectDescription.pdf](ProjectDescription.pdf) and [ProjectPresentation.pdf](ProjectPresentation.pdf) for a full report of this project.

# qclass_dl
Question classification on TREC dataset (and its Vietnamese translation) using Deep Neural structures, namely CNN &amp; LSTM &amp; both of them.

Much of the code is reused from
https://github.com/dennybritz/cnn-text-classification-tf
https://github.com/yoonkim/CNN_sentence
https://github.com/tensorflow/tensorflow/tree/master/tensorflow/models/rnn/ptb
https://github.com/tensorflow/tensorflow/tree/master/tensorflow/models/rnn/translate

## To see list of parameters
```
./train_cnn.py --help
./train_cnnlstm.py --help
./train_lstm.py --help
```

## To run
```
./train_cnn.py --vn
./train_cnnlstm.py --lstm_type='gru'
./train_lstm.py --batch_size=100
```
