## Sentiment analysis with RNN using word2vec 

<b>Word2vec</b> -> for word embeddings<br>

The <b> RNN architecture</b> -> Model: "sequential", 1 masking layer, 1 lstm layer, 2 dense layers, last one being binary classification layer (sigmoid).<br>

The <b>dataset</b> -> TensorFlow dataset "imdb_reviews"<br>

<b> Goal </b> -> I am comparing the accuracy of sentiment analysis (a movie review being positive or negative) on 
reviews embedded with word2vec, and later with pre-trained embeddings from glove-wiki-gigaword-50 (transfer learning)<br>


