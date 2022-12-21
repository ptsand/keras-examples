# Supervised learning with keras

## Sentiment analysis - evaluate text as positive, neutral or negative

How to train and evaluate a bidirectional recurrent neural network (BRNN) for sentiment analysis.
This example is based on LSTMs, for better handling of long term dependencies, achieving an accuracy of around 97% on unseen data. An example of using this model client side in a [chat app](https://github.com/ptsand/nlp-chat)

## Bank customer - who's gonna leave the bank?

How to train a feedforward DNN (deep neural network) for binary classification with normalization included in the model.

## Vegetables convnet - what vegetable?

CNN (convolutional neural network) recognizing vegetables

## XOR gate

How to fit a model with early stopping callback.
Visualization of the loss reveal a local minimum early on, which are bypassed by increasing the patience param in the callback.
In the end there's an explicit calculation of a forward pass using only the weights from keras.