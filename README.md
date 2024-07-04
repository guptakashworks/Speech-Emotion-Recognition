# Speech-Emotion-Recognition

Voice often reflects underlying emotion through tone and pitch. Based on this fact, Speech Emotion Recognition (SER) has been developed, which is the task of recognizing the emotional aspects of speech irrespective of the semantic contents. As such, in this python project I have tried building a model which will be able to recognize emotion from sound files.

### Dataset
[RAVDESS dataset](https://drive.google.com/drive/folders/1U-NCKv4hv92arAz9_DFYG8RKX9QEIXFT?usp=sharing)  
- This dataset has 7356 files rated by 247 individuals 10 times on emotional validity, intensity, and genuineness.

> Some libraries used particularly for this project:  
- librosa
- pyaudio
- soundfile

### Steps 
1. Loading the dataset
2. Extracting features from it
3. Splitting the it into train and test sets
4. Initializing an MLPClassifier
5. Training the model
6. Calculating the accuracy of the model
