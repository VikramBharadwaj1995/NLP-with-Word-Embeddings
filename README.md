# NLP-with-Word-Embeddings
Using Word Embeddings and pre-trained Glove word embeddings for NLP
This particular project uses two datasets from Kaggle. One is for the GloVe word embeddings and the other for training the model on different movie reviews from the IMDB website.
If you wish to download and run it, make sure you have installed jupyter-notebook, since this is a .ipynb file. If not installed, install it with the following command ```pip install jupyter-notebook```<br />

There are a few things to be observed when running this project:
1. The training accuracy increases when training with our own embeddings, but the accuracy decreases and the loss increases on the validation set. There is a high variance problem in this case. This can be solved by using more data. But since we are not interested in our un trained word embedding, it should be fine.<br />
2. The accuracy increases and the loss dcreases on both the training and the validation set when we use the pre trained GloVe model. Although there is a very less avoidable bias, it can be forgiven in this case.
<br /> <br />
Credit to : Jannes Klass on Kaggle.
