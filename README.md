## NLBSE'23 Tool Competition: Code Comment Classification

This repository contains the data and results for the baseline classifiers the [NLBSE’23 tool competition](https://nlbse2023.github.io/tools/) on code comment classification.

Participants of the competition must use the provided data to train/test their classifiers, which should outperform the baselines.

Details on how to participate in the competition are found [here](https://colab.research.google.com/drive/1cW8iUPY9rTjZdXnGYtJ4ARBSISyKieWt#scrollTo=7ITz0v7mv4jV).

## Dataset

The dataset is accessed at the path: {language}_input_{language}.csv.

## Train And Evaluate Models

The train and eval model files are located in the models directory.

Our model is implemented on Google Colab, which contains many necessary libraries that do not require installation. It is recommended to use a GPU for the RoBERTa model.

To train the models, follow these steps:

    1. Clone this repo to Google Drive or another storage location.

    2. Open the .ipynb files and change the dataset paths in the for loops to match the current dataset storage location.

    3. Run the steps one by one in the cells of the .ipynb file.

## Results

All training and testing results for the three models are located in the results folder.
