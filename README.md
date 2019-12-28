# Classification-task-on-speech-dataset

There are 4 persons,each speaks out 10 digits (0 to 9),50 times.All these 2000 recordings are saved in the "recordings" folder in .wav format.

The file metadata.py contains the data about the speakers(like gender,accents,etc).

Included utilities-

trimmer.py -  Trims silences at beginning and end of an audio file. Splits an audio file into multiple audio files by periods of silence.

spectrogramer.py - Creates images of the 2000 recordings.

fsdd.py - Interprets the images and predicts the digit.

The test set officially consists of the first 10% of the recordings. Recordings numbered 0-4 (inclusive) are in the test and 5-49 are in the training set.

The d_h file contains the final code and calls the get_spectrograms function to give the result. 97% accuracy on test set.
