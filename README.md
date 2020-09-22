# Abstractive-Text-Summarization-using-seq-2-seq-RNN-s
The objective of this project was to build an Abstractive Text Summarizer using Sequence-to-Sequence Recurrent Neural Networks. For this project Amazon Fine Food Reviews dataset from Kaggle was used which has 500,000 reviews from 1999-2012. In the modern Internet age, textual data is ever increasing. We need to condense this data while preserving the information and meaning. We need to summarize textual data for that.

Text summarization is the process of automatically generating natural language summaries from an input document while retaining the important points. It would help in easy and fast retrieval of information. Abstractive summarization systems generate new phrases, possibly rephrasing or using words that were not in the original text. 

I have done preprocessing on the dataset by converting everything to lowercase, removing HTML tags, stop words, punctuations, special characters, any text inside parenthesis and contraction mapping for better training of the model.

During implementation a 3 Layer Stacked LSTM Encoder-Decoder model with Global Attention Mechanism was used. With this model I was able to get an accuracy of 77.27% on training set (constituting 80% of the dataset). Also cumulative BLEU-4 score of 0.8800 was achieved by this model on test set.

Colab link : https://colab.research.google.com/drive/17dCQU4fi-n1458_KFK_ZYlyj2bZIHOFq?usp=sharing

Datset link : https://www.kaggle.com/snap/amazon-fine-food-reviews/download

Firstly,you have to upload the Datset on your Google Drive then connect that Google drive with Google colab and you are good to go .

After entering in order to execute code you have to run cells using 'Shift + Enter' or 'Ctrl + Enter'

Comments have been added for better understanding of the code 
