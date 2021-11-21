# Speech Emotion Recognition
* Rawabi Alharbi
* Dimah Albunayyih

# Problem statement
Speech Emotion Recognition (SER) is the act of recognizing human emotion from speech. This is the advantage of the fact that voice often reflects underlying emotion through tone and pitch. SER can be beneficial for call centers that are giving health care support for elderly people and emergency call centers. The proposed project is based on speech emotion recognition is giving greater priority to calls with emotions such as fear, anger, and sadness, and less priority to calls with neutral speech and happiness.

# Data Description
There are four different datasets that will be used in this project, and they have been downloaded from Kaggle.
* **Crowd-sourced Emotional Mutimodal Actors Dataset (CREMA-D)** (https://www.kaggle.com/ejlok1/cremad): It is a data set of 7,442 original clips from 91 actors, and the sentences were presented using one of six different emotions (Anger, Disgust, Fear, Happy, Neutral, and Sad)
* **Ryerson Audio-Visual Database of Emotional Speech and Song (RAVDESS)** (https://www.kaggle.com/uwrfkaggler/ravdess-emotional-speech-audio): contains 1440 files, 60 trials per actor x 24 actors. Speech emotions includes calm, happy, sad, angry, fearful, surprise, and disgust expressions. 
* **Surrey Audio-Visual Expressed Emotion (SAVEE)** (https://www.kaggle.com/ejlok1/surrey-audiovisual-expressed-emotion-savee): 480 files was recorded from four native English male speakers. Emotion has been described psychologically in discrete categories: anger, disgust, fear, happiness, sadness, surprise, and neutral.
* **Toronto emotional speech set (TESS)** (https://www.kaggle.com/ejlok1/toronto-emotional-speech-set-tess): 2800 files, There are a set of 200 target words were spoken by two actresses (aged 26 and 64 years). seven emotions (anger, disgust, fear, happiness, pleasant surprise, sadness, and neutral).

# Algorithm
We will apply feature selection and extraction to extract the most important features from the audio files and then we will apply neural network algorithms.

# Tools
* Technologies: Python, Jupyter notebook.
* Libraries: NumPy, Pandas, Sklearn, librosa, Matplotlib, Seaborn.
