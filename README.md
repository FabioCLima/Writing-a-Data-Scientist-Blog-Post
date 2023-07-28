# Writing-a-Data-Scientist-Blog-Post
 A project data analysis using the CRISP-DM process for to be evaluated in the Udacity Data Scientist Nanodegree Project - Writing-a-Data-Scientist-Blog-Post
 
 # Developer Surveys Analysis

This GitHub repository contains code and analysis for exploring multiple years of developer survey data. The analysis aims to answer various business questions related to programming language preferences, remote work trends, and career paths in data science.

## Table of Contents

- [Introduction](#introduction)
- [Files](#files)
- [Business Questions](#business-questions)
- [How to Use](#how-to-use)
- [Dependencies](#dependencies)
- [License](#license)

## Introduction

Developer surveys provide valuable insights into the preferences and trends within the software development community. This project utilizes Python and pandas to process and analyze survey data from different years. The analysis includes visualizations to convey the findings effectively.
The blog which contains an overview of the project can be found here: https://medium.com/@lima.fisico/write-a-data-science-blog-post-ce4f2be15704
## Files

The repository includes the following files:

- `analysis.ipynb`: Jupyter Notebook containing the code and detailed analysis.
- `data` directory: This directory contains the survey data files for each year (e.g., `survey_results_public_2017.csv`, `survey_results_public_2018.csv`, etc.).
- `images` directory: Contains images of plots generated during the analysis.
- `README.md`: This file, providing an overview of the project.

## Business Questions

The analysis explores the following business questions:

1. **What are the most popular languages among developers in each year?**
2. **What are the most popular languages among data scientists?**
3. **What is the trend in remote work among developers?**

## How to Use

To reproduce the analysis, follow these steps:

1. Clone the repository to your local machine.
2. Ensure you have Python and the required dependencies installed (see the next section).
3. Place the survey data files (e.g., `survey_results_public_2017.csv`, `survey_results_public_2018.csv`, etc.) in the `data` directory.
4. Open and run the Jupyter Notebook `analysis.ipynb` to execute the analysis.

## Dependencies

The following Python libraries are used for this analysis:

- pandas
- matplotlib
- seaborn

You can install these libraries using `pip`:

```
pip install pandas matplotlib seaborn
```

## License

The code and analysis in this repository are provided under the MIT License. Feel free to use, modify, and distribute the code as per the terms of the license.

**Note**: The data used in this analysis is for demonstration purposes and may not represent actual survey data.
