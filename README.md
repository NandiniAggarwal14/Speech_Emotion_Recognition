This project aims to develop a Speech Emotion Recognition (SER) system that can identify and classify emotions from speech signals: the Speech Emotion Recognition (SER) system.
The system analyses audio recordings, extracts relevant features, and uses machine learning algorithms to infer the emotional state of the individual speaking.

Architectural Design:-
The system has several components in an architecture:
1. Data Loading and Preprocessing: Importing raw audio files and identifying labels. Thereafter visually presenting the various classes of the dataset.
2. MFCC feature extraction: The MFCC features are extracted from the audio signals and then normalized.
3. Training the Model: The training dataset is applied to train the SVM and RF classifiers and make the ensemble model.
4. Evaluation: Cross-validation is used to assess the model, and performance metrics such as accuracy and F1-score are computed.

Datasets:-
Utilized a publicly available dataset, namely the TESS (Toronto Speech Emotion Set).
This dataset provided a diverse range of emotional expressions for training and evaluation. It is an already balanced dataset with very high-quality audio. 
It includes audio recordings from actors expressing different emotions such as happiness, anger, sadness, fear, disgust, pleasant surprise and neutral.
Link for dataset: https://www.kaggle.com/datasets/ejlok1/toronto-emotional-speech-set-tess
