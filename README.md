# SSDMV

The source code of the paper ''SSDMV: Semi-supervised Deep Social Spammer Detection by Multi-View Data Fusion''.

The code is modified from code of ladder network:

https://github.com/CuriousAI/ladder
https://github.com/rinuboney/ladder
Three .py files:

input_data.py: contains the functions to load data from files. function 'read_data_sets_views' load pre-learned representation vectors from different views.
LadderClass.py: the model structure file;
TrainLadder.py: main entrance of the SSDMV
To run the model, just run python TrainLadder.py

Other notices:

open data sources:
Twitter: http://web.cs.wpi.edu/~kmlee/data.html;
Sina: https://aminer.org/data-sna\#Weibo-Net-Tweet;
Embedding models used in data proprecessing part:
Node2Vec: https://github.com/aditya-grover/node2vec
Doc2Vec: https://radimrehurek.com/gensim/models/doc2vec.html
With the above tools and default parameters, it will be easy to generate prepocessed representation vectors of different views and reproduce the experimental results.
