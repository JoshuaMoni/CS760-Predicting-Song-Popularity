# CS760: Prediciting Song Popularity

### Overview 
- Main idea is to predict if a song will be popular from metadata features. 
- Original features are collected from Spotify using spotipy.
- SPD and Billboard Hot 100 Datasets have been used to create the dataset used. 
- This repo is currently very messy. At some point during creation the datasets were overriden and as a result the complete dataset cannot currently be properly generated from scratch. This will need to be fixed in the future.

The main files to explore are `Dataset_visualisation.ipynb` which contains the visualisation for the different datasets. As well as this it also contains the code used to to extract features from the Spotify API and the code used to the filter songs that contain not enough english lyrics.
`SpotGenTrack.ipynb` contains the other half of the code used to generate our dataset, as well as further visualisations and exploration of the dataset and features present. `Basic_Models.ipynb` contains the code to run our baseline models and so example results. 

## Requirements
- See `requirements.txt`

### Datasets 
Due to the size of the datasets they are being stored in a [Google Drive](https://drive.google.com/drive/u/0/folders/1aF8HNbsQqvZaUgvxPLQzAkRhkkQhVzNr).
Place them in a Data folder outside the working Git directory to avoid large file warings. 

