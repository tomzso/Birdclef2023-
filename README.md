# Birdclef2023- vitmav45 homework 

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

### 1st milestone: What we have done so far

There are 2 files in the repository: BirdCLEF2023_Save_raw_train_audio.ipynb and BirdCLEF2023_Data_preproccess.ipynb

#### BirdCLEF2023_Save_raw_train_audio.ipynb
This file downloads all the raw audio files as .ogg multimedia files. Downloading the raw audio requires the kaggle.json file, which contains API credentials. This Jupyter Notebook iterates over all the audio files and creates three TensorFlow datasets (train, validation, test). These three files are large in size, so they are pipelined during the training process. The three datasets are then uploaded to Kaggle. 

Link to the 3 dataset:

https://www.kaggle.com/datasets/tomzso/validation

https://www.kaggle.com/datasets/tomzso/training

https://www.kaggle.com/datasets/tomzso/testing

### 2st milestone: What we have done so far

#### BirdCLEF2023_Training_Data.ipynb
We used this file for both training and evaluating our work. After the training (model fitting) part, we also created an evaluation section. The evaluation part utilizes the saved weights and then uses the test dataset to get the actual precision.










