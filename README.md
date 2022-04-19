# Word-Sense-Disambiguation-Prediction

Word Sense Disambiguation (WSD) is a popular problem in Natural Language Processing (NLP) and deals with determining the correct "sense" of a word that is used in a particular context. This is a difficult task because, in order to find the exact sense of a target word in a given context, the system needs to have a good understanding of the entire context as well as the domain to which the word is related. In this paper, some novel approaches have been proposed and investigated to perform the task of Word Sense Disambiguation by creating encoder-decoder models using transformers and other deep learning architectures. Pre-trained BERT is used as transformer to create the encoder models whereas LSTM, Dense layers and custom layers are used in the decoder model, and different experimental techniques like word emphasis, data augmentation and thresholding are used to improve the deep learning based models. The models are trained and tested on the WiC-TSV dataset, and the final results of the different models are documented and compared with each other. The best performing model among the different proposed models achieved an accuracy of 77.34 \% on the test set of the WiC-TSV dataset.

## Description

- data --> WiC-TSV dataset
- BERT_Dense.ipynb --> uses BERT encoder with Dense decoder
- BERT_Mean.ipynb --> uses BERT encoder with custom mean layer and dense layer as decoder
- BERT_LSTM.ipynb --> uses BERT encoder with LSTM Decoder
- BERT_LSTM_Aug.ipynb --> uses BERT encoder with LSTM decoder trained on Augmented data
- BERT_LSTM_WE.ipynb --> uses BERT encoder with LSTM decoder and 'word emphasis' technique
- BERT_LSTM_Aug_WE.ipynb --> uses BERT encoder with LSTM decoder trained on Augmented data with 'word emphasis' technique
- preprocess.py --> Python script for preprocessing the dataset

## Purpose  
The project 'Word Sense Disambiguation using Transformer based Encoder-Decoder Model' has been created as a mini project for the course IT350- Data Analytics.

## Contributors  
- Pratham Nayak (191IT241)  
- Aprameya Dash (191IT209)
- Suyash Chintawar (191IT109)
