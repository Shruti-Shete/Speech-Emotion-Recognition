**Overview:**

Speech Emotion Recognition (SER) is a project designed to enable machines to understand and recognize human emotions conveyed through speech. 
The primary aim is to improve human-machine interaction by automatically identifying and responding to the emotional state of the speaker. 
The project addresses challenges related to feature selection, dataset preparation, and the implementation of effective classification techniques for speech emotion recognition.

**Dataset**

The project utilizes the RAVDESS database, consisting of 3120 files with recordings from 10 professional actors, each delivering sentences with neutral and emotional expressions. 
The dataset includes audio-only, audio-video, and video-only modalities, covering a range of emotional intensities.

**Methodology:**

The Speech Emotion Recognition methodology involves the use of Python libraries, including soundfile, librosa, and sklearn. A model is built using the MLPClassifier with features such as Mel Frequency Cepstral Coefficients (MFCC), Chroma, and Mel Spectrogram Frequency. The classification model is trained and optimized for accurate emotion prediction

**Speech Emotion Recognition:**

The project evaluates a neural network-based system for language-free emotion recognition using a dataset of 3120 spoken utterances with eight distinct emotions. The MLP Classifier achieves a classification accuracy of nearly 78\%, outperforming other classifiers such as the Random Forest Classifier.
