# Text-Editor-with-Word-Prediction-Feature-using-Unigram-Bigram-Trigram-Approch
It is a Python Implementation of text editor where we have the feature of next/current word prediction. Currently it is using an Urdu Dataset where predictions are also urdu words. 
There are three approches for the word prediction in this model.
1. Unigram
2. Bigram
3. Trigram
You may select the checkpoint of any model for instant activation. For debug you may call this function for predicted words.

      predited_words=predict_next_word_using_initial_substring('اور','2','و')

First Parameter is the Sentence you have wrote.
Second Parameter is the Selection 1/2/3 for unigram/bigram/trigram respectively for model selection,
Third Parameter is the initial substring from which word can be started. This may be empty/None.

