# Analyzing Voice Samples to Predict Age

## The Problem

[NeuroLex Labs](https://www.neurolex.ai/) is a company that applies machine learning modeling to voice samples. They provide clients a variety of services, including dataset curation, featurization, ML modeling, and server deployment. Companies can use these services to create models for speech recognition, schizophrenia diagnosis, depression detection, and more. 

Because the age of the speaker can bias voice datasets, it can often be useful to create models that automatically label voice samples with age ranges (we may not know the age of the speaker when the sample was recorded). In other words, the difference in spectral features between ages can reduce the signal of interest. 

Here, in order to help solve this problem, we create a model that can predict the age range of the speaker.

## Data
We're going to use the Common Voice Dataset that was curated by Mozilla. It has a total of 200,000 samples, but only about 74,000 are labeled with age.

## Directory Structure
```bash
├── Data Wrangling              # Feature extraction, engineering
├── Exploratory Data Analysis   # Data visualization
├── Modeling                    # Feature selection, predictive modeling
├── Presentation                # Slide deck for demo presentation to NeuroLex
├── Reports                     # Reports written in late 2018
```

## Results
For results and more detailed information on methodology, check the "Reports" folder

## Important note:
There have been updates/revisions made to some of the modeling since the reports were created. 

Examples of updates made since then:
- Validation against a validation set
- Use of a standard scaler to normalize the data
- Better testing accuracy

