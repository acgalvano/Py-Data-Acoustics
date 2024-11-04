# Py-Data-Acoustics
Python Data Processing Basics for Acoustic Analysis

This tutorial walks through some key domain-specific Python-based tools you should be aware of in order to take your audio data, annotations, and speaker metadata and come away with tabular data containing acoustic measures that can then be visualized and submitted to statistical analysis. It assumes coding experience at the level of [D-Lab’s Python Fundamentals](https://github.com/dlab-berkeley/Python-Fundamentals). It covers how to import TextGrid tiers and speaker metadata using dir2df and how to load in audio files to your jupyter notebook using audiolabel (https://github.com/rsprouse), as well as how to extract a series of acoustic measures using the [parselmouth](https://parselmouth.readthedocs.io/en/stable/#) library.

## Additional materials
Download the toy dataset from Drive [here](https://drive.google.com/drive/folders/1NdKxlwLTkvn38Bh3eHUgh2Kg5-MsuU_H?usp=sharing).

## Forthcoming:
Merging together full datasets

- Using concat to combine two datasets with the same columns
- Subsetting and cleaning
- Exclude stop words
- Filter outliers by 2 SD
- Combining social factors into a single column
  
Exploring your data using visualization
- Checking for normal distribution
- By-speaker distributions
	- By-variable distributions
- Kernel density plots
	- 1 variable (COG)
	- 2 variables (F1 and F2)
