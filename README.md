
# Speech to Emotion Recognition

Its a ability of a system or a person to identify and interpret the emotional state of the another person.

Basically we are trying to find solution or help healthcare field.









## pre requisites
Prerequisites
We’ll need to install the following libraries with pip:

pip install librosa soundfile numpy sklearn pyaudio

## Steps

1. For the program to be executed we need to import the pre build python packages.

Which are:

import librosa
import soundfile
import os, glob, pickle
import numpy as np
from sklearn.model_selection import train_test_split
from sklearn.neural_network import MLPClassifier
from sklearn.metrics import accuracy_score

2. Define a function extract_feature to extract the mfcc, chroma, and mel features from a sound file.

3. We have created the dictionary for the dataset which contain the number of emotions.

4. We have to load the data with a function load_data(),
The pattern we use for this is: 
“D:\\User\\ravdess data\\Actor_*\\*.wav”
(This is the path where our dataset is being saved)

5. Now, we will observe the shape of the training and testing datasets.

6. We will initialized an MLPClassifier.

7. At last we will calculate the accuracy of the dataset provided by the function accuracy_score()
## Tech Stack 
Jupyter notebook -: For creating our speech to emotion project.