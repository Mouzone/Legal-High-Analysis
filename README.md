# Legal High Analysis

## Overview
This repository contains the analysis of the TV show "Legal High." The primary objective of this study is to investigate if the quality of the show "Legal High" exhibited any significant changes over the course of the season. The study utilizes Nielsen Nationwide Ratings as a proxy for quality, operating under the assumption that higher quality is associated with increased viewership, and lower quality leads to decreased viewership.

## Contents
- The repository includes the following files:
  - `data.csv`: The dataset containing relevant information for the analysis.
  - `analysis.ipynb`: Jupyter Notebook file that presents the analysis, data processing, and visualizations.
  - `findings.pdf`: A document summarizing the key findings and insights from the analysis.

## Data Collection
### Source
The data for this analysis was collected from the "Legal High" Wikipedia page, specifically from the section on Average TV viewership ratings.

### Variables
The dataset (`data.csv`) includes the following variables:
- `episode`: Episode number.
- `broadcast_date`: The date when the episode was aired in the format YYYY-MM-DD (e.g., 2019-02-08).
- `rating`: Nielsen Nationwide Ratings for each episode.

### Rationale
Nationwide Ratings were chosen over Seoul ratings due to missing values in the Seoul ratings dataset.

## Model
The analysis is based on a regression model, which aims to establish a relationship between Nielsen Nationwide Ratings and the broadcast date. The model used is a linear regression model, which helps in assessing whether there is a linear trend or correlation between the two variables.

## Findings
For detailed findings and insights from the analysis, please refer to the `findings.pdf` document in this repository.

## Usage
To replicate the analysis or explore the dataset, you can open and run the Jupyter Notebook `analysis.ipynb`. Make sure you have the necessary dependencies installed in your Python environment.
