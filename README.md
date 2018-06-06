# TensorFlow based Text Classification with Convolutional Neural Networks Deep Learning in NLP 

Text classification represents a general classification task such as sentiment analysis, email classification as spam or non-spam, document categorization etc. Deep learning and neural networks are getting better and better at text classification, with state-of-the-art technology such as Convolutional Neural Networks. Traditionally, CNNs have proven to be very effective for computer vision tasks such as tagging a person in the photo on social media websites, self-driving cars and many other tasks.
Recently, researchers have been found out growing interest in using CNNs in Natural Language Processing (NLP) with areas such as Text Classification due to increased classification accuracy compared to other machine learning classifier models such as Naïve Bayes Classifier or SVM classifier. This project deals with the Convolutional Neural Networks applied to Text Classification with Sentiment Analysis task using Deep Learning framework TensorFlow. The dataset in this project is the Movie Review data from Rotten Tomatoes which was also used in the paper by Pang et al [1].

## Model

The network built in this project has roughly following representation as mentioned in the paper by Kim Yoon [2]

The general approach for using CNN for NLP tasks as follows. First, sentences are mapped into embedding vectors and then fed to the input in the matrix form. Convolutions are performed with different-sized filters such as 2 or 3 words at the time, then max pooling layer is implemented to decrease the special size, its output is then applied to fully connected layer with dropout regularization to obtain sentence classification. The activation function in this case can be either ReLu or tanh.

![CNN filter and Pooling architecture for Sentence Classification](https://github.com/kedarvkunte/TensorFlow-based-Text-Classification-with-Convolutional-Neural-Networks-Deep-Learning-in-NLP-/blob/master/CNN%20filter%20and%20Pooling%20architecture%20for%20Sentence%20Classification%20taken%20from%20the%20paper%20by%20Kim%20Yoon.png)

## Analysis

![Accuracy Vs. No. of Iterations](https://github.com/kedarvkunte/TensorFlow-based-Text-Classification-with-Convolutional-Neural-Networks-Deep-Learning-in-NLP-/blob/master/Accuracy%20Vs.%20No.%20of%20iterations.PNG)










Idea and the supporting code taken from the https://github.com/dennybritz/cnn-text-classification-tf

