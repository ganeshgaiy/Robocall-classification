# Robocall Detection Project

This project aims to develop a machine learning model capable of distinguishing between robocalls and normal calls using audio data. By analyzing specific audio features, the model identifies patterns unique to each call type, facilitating the detection of unwanted or fraudulent communications.


## Overview

This project involves:
- **Data Preprocessing**: Segmenting, cleaning, and balancing audio recordings of robocalls and normal calls.
- **Feature Extraction**: Extracting audio features to train a machine learning model.
- **Model Training**: Building a model to classify audio as either robocall or normal call.

## Dataset

The dataset consists of audio recordings categorized as follows:
- **Robocalls**: 1,343 recordings, typically shorter and more repetitive.
- **Normal Calls**: 1,000 segmented recordings, derived from longer conversations, with silence removed.

### Dataset Statistics

| Class       | Mean Duration (s) | Median Duration (s) | Min Duration (s) | Max Duration (s) |
|-------------|--------------------|----------------------|-------------------|-------------------|
| Robocall    | 25.25             | 21.53               | 4.53             | 573.19           |
| Normal Call | 675.23 (original) | 699.52 (original)   | 42.07            | 1304.20          |
| After Segmentation | 5-30 seconds for each segment | N/A | N/A | N/A |

## Directory Structure
- `dataset/`
  - `robocall/`: Contains processed robocall audio files.
  - `normal_call/`: Contains segmented normal call audio files.
 
## Requirements

- Python 3.7+
- Required libraries:
  - `librosa`
  - `pydub`
  - `soundfile`
  - `numpy`

Install the required packages using:
```bash
pip install -r requirements.txt




