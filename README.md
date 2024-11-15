# Robocall Detection Project

## Overview

This project aims to develop a machine learning model capable of distinguishing between robocalls and normal calls using audio data. By analyzing specific audio features, the model identifies patterns unique to each call type, facilitating the detection of unwanted or fraudulent communications.

## Dataset

The dataset comprises audio recordings categorized as follows:

- **Robocalls**: Approximately 1,000 recordings, each ranging from 5 seconds to 2 minutes.
- **Normal Calls**: Several recordings, each around 30 minutes, segmented into clips between 5 and 30 seconds.

Both categories have been processed to extract the left audio channel and remove extended silences, ensuring consistency and clarity.

## Project Structure

- `dataset/`
  - `robocall/`: Contains processed robocall audio files.
  - `normal_call/`: Contains segmented normal call audio files.
- `notebooks/`: Jupyter notebooks detailing data exploration, feature extraction, and model training.
- `models/`: Saved models and related artifacts.
- `scripts/`: Python scripts for data processing and feature extraction.
- `requirements.txt`: List of required Python packages.


