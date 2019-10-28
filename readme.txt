# Audio Tagging & Beyond

This repo is a work in progress of using a CNN model to classify audio data.

Signal processing is done to visualize and feature engineer the raw wav files.  By creating pitch sifts, MFCC transformations and other audio transformations we can create multiple dimentions of data and train a more robust model.
The Freesound database is a collection of labeled sound files in wav format belonging to 41 unique classes (such as "cough" "clapping" and "cello").

The code in <classifying_sounds.ipynb> code was built upon Zafar's contribution to The Kaggle challenge <link>

Additional expolration into feature engineering was taken

Additional exploration made visualizing the wav files by instrument for the continued work of the project in the following using only musical instruments (see: classifying_notes.ipynb)




In the future I hope to develop this code into a tuner by training the classification model on generated notes. \\


further reading:
https://www.kaggle.com/fizzbuzz/beginner-s-guide-to-audio-data
https://towardsdatascience.com/recognizing-speech-commands-using-recurrent-neural-networks-with-attention-c2b2ba17c837
https://ai.google/research/teams/brain/magenta