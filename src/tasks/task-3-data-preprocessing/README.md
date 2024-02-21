# Data Preprocessing and Analysis for Job Descriptions

This project involves cleaning, preprocessing, and analyzing a dataset of job descriptions. We aim to explore biases in job postings, especially focusing on gender and racial biases, and how they correlate with other features like job requirements and offered salary.

## Dataset

The dataset consists of job descriptions collected from various sources, each containing textual information, the count of male and female bias words, and racial bias words. We perform extensive cleaning and preprocessing on this dataset, followed by explorative data analysis to uncover insights.

## Data Preprocessing

We carry out the following preprocessing steps:
- Reading the CSV file and handling errors in reading due to encoding issues.
- Cleaning the text data by removing HTML tags, unnecessary words, and phrases like "Job Description", "Duties", and special characters.
- Extracting salary information from the job description and handling missing values.

## Data Analysis

The data analysis part includes:
- Univariate, bivariate, and multivariate visualizations to explore the distributions and relationships between different features.
- Descriptive statistical analysis to summarize the main characteristics of the dataset.
- Exploring features that influence biases in job postings.

## Visualizations

Various visualizations like scatter plots, histograms, and heatmaps are used to visualize the distributions and correlations between the features. We specifically look at the correlation between biases and offered salaries.

## Insights

The insights derived from the visualizations and statistical analyses are documented, providing a comprehensive overview of the biases present in job postings and their implications.

## Tools and Technologies

- **Python**: The primary programming language for data cleaning, preprocessing, and analysis.
- **Pandas**: Used for data manipulation and analysis.
- **Matplotlib and Seaborn**: Used for creating static, interactive, and animated visualizations in Python.
- **Jupyter Notebook**: An open-source web application that allows the creation and sharing of documents that contain live code, equations, visualizations, and narrative text.

## Usage

Clone the repository and navigate to the project directory. Make sure you have all the required libraries installed. You can install the dependencies using the following command:
