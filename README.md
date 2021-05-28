# Hidden Hits

# Description


## Notebooks
The following is a list of notebooks and the content they contain.

- **Hidden Hits 1 - Data Collection** _(written by Mir Adnan Mahmood)_ contains code used to generate a dataset containing information on songs that appeared in the Billboard Hot 100's year end list from 2010 to 2020. The dataset contains the following features:
  * Information on Title, Artists, Year of appearance on Hot 100 and Rank in Hot 100 are scraped through Billboard's website
  * Information on Lyrics is scraped (using information on song title name and artist names) through Genius.com
The final output for this notebook is the dataset `hot_100_lyrics.csv` file.

- **Hidden Hits 2 - Spotify-Kaggle Dataset Clean** _(written by Mir Adnan Mahmood)_ contains code that extracts song features for songs that appear on the Billboard Hot 100s Year End lists from the Kaggle Dataset created by Yamac Eren Ay found [here](https://www.kaggle.com/yamaerenay/spotify-dataset-19212020-160k-tracks). The code first creates a subset of the Hot 100's data `tracks_hot100.csv` and supplements it with another dataset that contains song features for songs that did not appear on the Hot 100s list. This dataset is found in `tracks_not100_sub.csv`.

 - **Hidden Hits 3 - Hot 100 Classification** _(written by Khyati Malik and JongHoon Shin)_ This notebook contains the code to run the classification algorithm that predicts whether or not a song is a Hot 100 or a Not 100 song using a Random Forest Classifier. Results for different models and features are published in the _New Update_ folder. **Note:** This file is the same as the `hot_100_classification_v1` notebook in the _New Update_ folder.

 - **Notebook on Classification via Lyrics**

All "old" notebooks and data files are in the scraps folder.

## Miscellaneous
The `.gitignore` file ensures that (1) we don't upload any of the `.ipynb_checkpoints` files,
and (2) we don't upload a directory named `data`
where we should keep our large data sets
because GitHub won't let us upload too large of files.

## Contributors
The following are the contributors and their contributions to this project:
- Mir Adnan Mahmood: Data Collection and Cleaning
- Ritwik Banerji: Unsupervised Learning - classification of songs via lyrics.
- Mike Pierce: Unsupervised Learning - classification of songs via lyrics.
- Khyati Malik: Supervised Learning - Classification of Hot or Not songs based on sonic features
- JongHoon Shin: Supervised Learning - Classification of Hot or Not songs based on sonic features
- Rabail Chandio: Post-processing and consolidation.

This project has been created as part of the Erdos Institute's DataScience Bootcamp 2021.
