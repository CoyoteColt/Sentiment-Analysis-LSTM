# Sentiment Analysis


This is the second part of the Sentiment Analysis project.

In this project, we will delve into three Natural Language Processing (NLP) models, focusing specifically on sentiment analysis. We will explore three distinct architectures: Fully Connected Neural Network (FCNN), Long Short-Term Memory (LSTM), and finally, the Transformers architecture using the BERT model.

The main objectives of this project are as follows:

- Evaluate the performance of the three models in relation to the sentiment analysis task.
- Assess the level of complexity involved in building each architecture.
- Compare the training times required for each model. 

Upon completion of this study, we aim to draw informed conclusions about which model proves most suitable for sentiment analysis. To achieve this, we will employ a dataset with six classes for sentiment classification.<br>
In all three projects we will use the same database but manipulate it with different techniques.


# Model 2: Long Short-Term Memory (LSTM) 


In this second model we will address the LSTM architecture, LSTMs (Long Short-Term Memory) are a recurrent neural network architecture designed to process sequences of data such as text and time series. They are able to remember important information for long periods of time, solve the vanishing gradient problem, and capture long-range dependencies in sequences. However, they can be complex to train and interpret, and are prone to overfitting, especially on small data sets. Despite this, they are widely used in tasks such as machine translation, sentiment analysis and time series forecasting.

<img src="https://miro.medium.com/v2/resize:fit:674/1*jikKbzFXCq-IYnFZankIMg.png" alt="LSTM">

## Techniques used for data processing in the LSTM model

- ## Spacy
In all models we will use Spacy as a way to simplify the text by removing very repetitive words.
- ## Tokenizer
The scikit-learn Tokenizer function is used to convert text into an array of tokens, where each token represents a word in the text. This is useful for preparing text data for machine learning tasks such as text classification or clustering. The scikit-learn Tokenizer offers several configuration options, such as removing stopwords, normalizing text, and defining custom tokenization patterns, enabling flexible and effective preparation of text data for modeling.
- ## Padding
"Padding" is a technique commonly used in processing sequences of data, especially in natural language processing (NLP) tasks. Padding is used to standardize the length of sequences. This is done by adding a special value (usually 0) at the beginning or end of sequences to lengthen them to a defined maximum length. This allows the model to process batches of sequences simultaneously, which is essential for training efficiency.
- ## Callbacks end Early Stopping
Another technique that will also be used in the three models, Callbacks end Early Stopping are functions that allow you to monitor and control the training process of machine learning models. They provide a communication channel between the model and the user code, allowing the execution of personalized actions at specific points in the training, such as adjusting the learning rate function and stopping training after the model reaches its plateau.

## Results

<img src="https://cdn.discordapp.com/attachments/809675955689881640/1227805989693292574/image.png?ex=6629be6f&is=6617496f&hm=f1761d89e84a4975c4337f8f560e7f8e07e8a505f1b126a5b7330a3edd806bd0&" alt="Model LSTM"><br>
<img src="https://cdn.discordapp.com/attachments/809675955689881640/1227806258350788638/image.png?ex=6629beaf&is=661749af&hm=ec4af16cc5058212023152483571b6041ae047bd5df1851f7b4b15f22f4f58a4&" alt="Model LSTM"><br>

- We were able to achieve an accuracy of 88% and it took us about 6 minutes to complete the training. Let's see how the latest architecture fares, the transformative architecture.

<br>

## If you want to reproduce the experiment on your machine, below are the versions used

<img src="https://cdn.discordapp.com/attachments/809675955689881640/1227734807627173938/image.png?ex=66297c24&is=66170724&hm=1762e9a8a1238c8f981d2e78ddd6ab538bf4f12b31d63a1ecd702ea49eed83f4&" alt="version"><br>

<br>
<br>
<br>
<br>
<br>

- Link to the second model

Model 3 - Transformer-(BERT)  (SOON)
