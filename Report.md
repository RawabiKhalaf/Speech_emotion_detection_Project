# Speech Emotion Recognition
By: Rawabi Alharbi, Dimah Albunayyih

## Abstract
Speech Emotion Recognition (SER) is the act of recognizing human emotion from speech. This is the advantage of the fact that voice often reflects underlying emotion through tone and pitch. SER can be beneficial for call centers that are giving health care support for elderly people and emergency call centers. The proposed project is based on speech emotion recognition is giving greater priority to calls with emotions such as fear, anger, and sadness, and less priority to calls with neutral speech and happiness.

## Design
The four datasets provided on Kaggle were stored as CSV files. The first process was clean the datasets, made them as one format and concatenate them. Then we did EDA to understand the data. After that we started the CNN to predict the speech emotion.

## Data
In this project, we used four different datasets, which are:
* **Crowd-sourced Emotional Mutimodal Actors Dataset (CREMA-D)** (https://www.kaggle.com/ejlok1/cremad): It is a data set of 7,442 original clips from 91 actors, and the sentences were presented using one of six different emotions (Anger, Disgust, Fear, Happy, Neutral, and Sad)
* **Ryerson Audio-Visual Database of Emotional Speech and Song (RAVDESS)** (https://www.kaggle.com/uwrfkaggler/ravdess-emotional-speech-audio): contains 1440 files, 60 trials per actor x 24 actors. Speech emotions includes calm, happy, sad, angry, fearful, surprise, and disgust expressions. 
* **Surrey Audio-Visual Expressed Emotion (SAVEE)** (https://www.kaggle.com/ejlok1/surrey-audiovisual-expressed-emotion-savee): 480 files was recorded from four native English male speakers. Emotion has been described psychologically in discrete categories: anger, disgust, fear, happiness, sadness, surprise, and neutral.
* **Toronto emotional speech set (TESS)** (https://www.kaggle.com/ejlok1/toronto-emotional-speech-set-tess): 2800 files, There are a set of 200 target words were spoken by two actresses (aged 26 and 64 years). seven emotions (anger, disgust, fear, happiness, pleasant surprise, sadness, and neutral).

## Algorithms
We applied different Augmentation techniques (Noise injection, stretching and pitch), and applied feature extraction techniques (zero crossing rate, chroma_stft, MFCC, RMS and melSpectogram) to extract the most important features from the audio files and then we applied neural network algorithms using convolution and dense layers with (relu and softmax) activation functions.

## Tools
* Technologies: Python, Jupyter notebook.
* Libraries: NumPy, Pandas, Sklearn, librosa, Matplotlib, Seaborn

## Communication
In addition to the slides and visuals presented, we will share our work on our Github accounts
* https://github.com/RawabiKhalaf/speech-emotion-recognition/new/main/Source_code.ipynb
* https://github.com/DimahAlbunayyih/T5_bootcamp_projects.git
