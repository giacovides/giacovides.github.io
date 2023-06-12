---
layout: page
title: Recurrent Neural Networks (RNNs)
description: Coursework for 3rd Year module ELEC60009 - Deep Learning
img: assets/img/RNN.png
importance: 2
category: Machine Learning/Digital Hardware
---
In this coursework three main tasks were performed:
  - **RNN regression**: Implemented a many-to-one RNN model to predict the time series for the monthly airline
    passengers. As part of the task had to find the optimal window size for which I developed a unique solution
    by employing the autocorrelation function.
  - **Sentiment Analysis**: Three different models were developed in order to classify movie reviews (sentiment
    analysis). Firstly, embeddings of dimensionality 1 were employed and models with and without LSTM units were
    trained. The GloVe embeddings were then used along with the model containing LSTM units to classify the
    reviews. The accuracy and loss of the three models were then compared.
  - **Text Generation**: Character-level and word-level RNN models were implemented and the temperature of each
    was varied to understand the effect temperature has on the generated sentences. The qualitative results of
    the two models were then compared.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/simple_rnn.png" title="simple rnn image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
A simplified RNN used for visual purposes
</div>
