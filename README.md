# Spoken Digit Recognition

In this notebook, we are recognizing digits from 0 to 9 based on audio recordings file. Input data will be in the form of speech signal and output will be a single digit.

We are using raw audio and training it using LSTM architecture. We are also converting speech signal into spectrogram and training it using LSTM architecture.

Here are the steps:- 
- Preprocess the dataset
- Train LSTM architecture using raw features and spectrogram features
- Create augmented data with raw features, augmented data with spectrogram features and train LSTM architecture
- Compute F1 score on validation data for raw features, spectrogram features and augmented data and compare these scores.
