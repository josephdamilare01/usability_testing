# Usability Testing Analysis
This project conducts a usability testing analysis on a dataset to evaluate users' experiences and perceptions of a specific system. The analysis is performed using the R programming language with the help of the tidyverse and readxl libraries. The primary objective is to understand the usability aspects of the system, identify any usability issues, and provide insights into user satisfaction and system performance.


## Introduction
This project involves loading, sampling, and analyzing a dataset to evaluate the usability of a system. Various usability metrics are calculated, and visualizations are created to provide insights into user experiences.

## Data Preparation and Sampling
The first step in the analysis involves loading the dataset and preparing it for sampling. The dataset is read from a CSV file using the read.csv2 function, with a tab separator, allowing the user to select the file interactively. A random sample of 500 rows is then extracted from the dataset to ensure that the analysis is manageable and representative.



## Usability Metrics Calculation
The sampled data is analyzed to calculate various usability metrics. The analysis focuses on several key questions related to the system's usability, including:

- Frequency of system use
- Perceived complexity
- Ease of use
- Need for technical support
- Integration of functions
- Inconsistency in the system
- Speed of learning to use the system
- Cumbersomeness
- Confidence in using the system
- Learning requirements before using the system

## Data Visualization
The project includes several visualizations to help interpret the usability metrics. These visualizations are created using the ggplot2 package from tidyverse and include histograms to display the distribution of responses for each usability question.

