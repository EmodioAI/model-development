# Audio Synthesis Model Development

This GitHub repository focuses on the development of a model for audio synthesis, specifically targeting the incorporation of emotions into monotone audios using Generative Adversarial Networks (GANs).

## Repository Objective

The primary objective of this repository is to provide a centralized location for all activities related to audio synthesis model development using GANs. By leveraging the dataset, analyzing audio data, and experimenting with GANs, we aim to achieve the synthesis of emotionally enriched audio from monotone sources. The ultimate goal is to create a robust and effective audio synthesis technique that successfully incorporates emotions into the generated audios.

## Dataset

The repository includes a CSV file, `data.csv`, which contains essential information for the audio synthesis model development. The CSV file consists of three columns:

- `filepath`: Contains the file path to the Google Drive folder where the audio files are stored.
- `emotion`: Represents the particular emotion expressed in each audio, including happy, sad, disgust, neutral, calm, angry, fearful, and surprised.
- `intensity`: Indicates the intensity level of the respective audio.

## Audio Data Analysis Notebook

The notebook `Emotion_Data_Analysis.ipynb` is available to analyze the audio data within the dataset. It explores different distributions present in the audio data and combines audios from three primary sources: RAVDESS, CREMA-D, and SAVEE. The combined dataset comprises a total of 9363 audio samples. Each emotion constitutes a specific percentage of the dataset: happy, sad, disgust, neutral, angry, fearful, and surprised make up 16% each, while calm constitutes 2% and neutral 14%.

## GANs for Audio Synthesis Notebook

The notebook `GAN_Audio_Generation.ipynb` is currently a work in progress. It focuses on using Generative Adversarial Networks (GANs) for audio synthesis, aiming to incorporate emotions into monotone audios. This notebook explores various GAN architectures and techniques to generate expressive audio outputs.


