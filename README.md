# Music-beat-Detection-in-indian-classical-music
## Project Overview
This project aims to develop a model for detecting beats in Indian classical music. Indian classical music has unique rhythmic structures and tempo variations, making beat detection a challenging task. The proposed system will leverage advanced signal processing techniques to extract relevant features from the audio signal and accurately identify the underlying beat pattern.
The beats specified for this project are Adital, Ektal, Jhaptal, Rupaktal and Teental.
## Technical Approach
### Audio Preprocessing:
#### Feature Extraction: 
Extract relevant features from the audio signal, such as Mel-Frequency Cepstral Coefficients (MFCCs), Perceptual Linear Prediction (PLP), and Spectral Centroid.
#### Link to signal processed files: 
you can access the files here.

[Link here](https://drive.google.com/drive/folders/1CNzfsJo4Z225SaHzSnb8M-xclVlnjzIN?usp=drive_link)
### Deep learning Model:
#### Long short Time Model: 
LSTM recurrent network  is used for as a training.
### Evaluation and Refinement:
#### Dataset: Used dataset of Indian classical musics. The dataset were collected some by sites and some from youtubes.
#### Metrics: Evaluate the performance of the algorithm using metrics by accuracy, precision, recall, and F1-score.
## Resources
### Dataset:
#### Indian Classical Music Database: 
Three datasets where used
Link to used dataset for training.
Link to original datasets

First dataset: https://compmusic.upf.edu/hindustani-rhythm-dataset

Second dataset: https://compmusic.upf.edu/carnatic-rhythm-dataset

Third Dataset: https://www.kaggle.com/datasets/pranav6670/tabla-taala-dataset

we also mange to collect data from elsewhere to blance the dataset. you can access the here
{link here}

### Programming Language and Libraries:
#### Python: 
A popular choice for audio processing and machine learning tasks.
#### Libraries: 
The libraries used in this project are Librosa, NumPy, SciPy, TensorFlow, Keras, Spafe, Gammatone, and sklearn.
### Other Tools and Applications
Applications that are used to clean, remove vocals and edit audio are:
ULtimate Vocal Remover by Anjok07 and Wave Pad Sound Editor by NCH Suite
you can get Ultimate Vocal Remover From here:

https://ultimatevocalremover.com/

https://github.com/Anjok07/ultimatevocalremovergui

You can Get Wave Pad from here

https://www.nch.com.au/wavepad/index.html
