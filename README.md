# Birdclef2023- vitmav45 homework (1st Milestone)

### Team: 06_Ahoy

### The Members of the team:
#### Bodnár Márk Maxim (HIYES6)
#### Tudisco Dávid Róbert(BAT2UZ)
#### Le Ngoc Toan (V6AO9G)


### Selected topic: 
https://www.kaggle.com/competitions/birdclef-2023

The offical description from the Birdclef2023 competition:

Birds are excellent indicators of biodiversity change since they are highly mobile and have diverse habitat requirements. Changes in species assemblage and the number of birds can thus indicate the success or failure of a restoration project. However, frequently conducting traditional observer-based bird biodiversity surveys over large areas is expensive and logistically challenging. In comparison, passive acoustic monitoring (PAM) combined with new analytical tools based on machine learning allows conservationists to sample much greater spatial scales with higher temporal resolution and explore the relationship between restoration interventions and biodiversity in depth.

For this competition, you'll use your machine-learning skills to identify Eastern African bird species by sound. Specifically, you'll develop computational solutions to process continuous audio data and recognize the species by their calls. The best entries will be able to train reliable classifiers with limited training data. If successful, you'll help advance ongoing efforts to protect avian biodiversity in Africa, including those led by the Kenyan conservation organization NATURAL STATE. 

### Milestone 1: What we have done far

There are 2 files in the repository: BirdCLEF2023_Save_raw_train_audio.ipynb and BirdCLEF2023_Data_preproccess.ipynb

#### BirdCLEF2023_Save_raw_train_audio.ipynb

This file downloads all the raw audio files as .ogg multimedia files. Downloading the raw audio requires the kaggle.json file, which contains API credentials. This Jupyter Notebook iterates over all the audio files and saves the X dataset into 10 different .npy format files. These 10 files are large in size, so they have been split. These split datasets have been uploaded to one of the team member's Google Drive.

#### BirdCLEF2023_Data_preproccess.ipynb

The metadata and the audio files can be downloaded from the official competition page: BirdCLEF 2023. This Jupyter Notebook downloads the provided metadata and the preprocessed audio data (generated from BirdCLEF2023_Save_raw_train_audio.ipynb) from one of the team members' Google Drive. This notebook visualizes the first audio file as a spectrogram, the number of audio files for each bird as bar chart, and the first 5 rows of the metadata for the bird audios. The important columns in the metadata include latitude, longitude, and author. The author column contains names in string format, so it has been one-hot encoded during preprocessing. For many audio files where the latitude and longitude are unknown, they have been filled with an average value specific to the bird.


