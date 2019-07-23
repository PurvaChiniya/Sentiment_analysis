This is a repository for sentiment anlaysis.
Data used: IMDB MOVIE DATASET
BERT PRETRAINED MODEL :
The links to the models are here (right-click, 'Save link as...' on the name):

*   **[`BERT-Base, Uncased`](https://storage.googleapis.com/bert_models/2018_10_18/uncased_L-12_H-768_A-12.zip)**:
    12-layer, 768-hidden, 12-heads, 110M parameters

*   **[`BERT-Base, Cased`](https://storage.googleapis.com/bert_models/2018_10_18/cased_L-12_H-768_A-12.zip)**:
    12-layer, 768-hidden, 12-heads , 110M parameters



Each .zip file contains three items:

*   A TensorFlow checkpoint (`bert_model.ckpt`) containing the pre-trained
    weights (which is actually 3 files).
*   A vocab file (`vocab.txt`) to map WordPiece to word id.
*   A config file (`bert_config.json`) which specifies the hyperparameters of
    the model.
