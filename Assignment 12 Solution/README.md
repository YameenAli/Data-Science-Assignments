# Student Performance Analysis

## Overview

This project involves analyzing student performance data to understand various factors influencing academic achievement. The dataset, `students data.csv`, includes information on students' gender, birth year, entry academic period, and scores in Math, Reading, and Writing. The analysis covers five main aspects:

1. **Gender Disparity in Academic Performance**
2. **Impact of Birth Year on Performance**
3. **Effect of Entry Academic Period on Performance**
4. **Subject-specific Performance Analysis**
5. **Longitudinal Analysis of Performance**

## Analysis and Findings

### a) Gender Disparity in Academic Performance
We investigate if there's a significant difference in average scores between male and female students across Math, Reading, and Writing subjects. The analysis includes calculating mean scores by gender and performing t-tests to identify significant differences.

### b) Impact of Birth Year on Performance
This section explores the correlation between students' birth years and their academic performance. We calculate and visualize the correlations to identify any trends or patterns based on the year of birth.

### c) Effect of Entry Academic Period on Performance
We analyze how the academic period in which students entered impacts their academic performance. The analysis includes calculating mean scores by entry academic period and visualizing these differences.

### d) Subject-specific Performance Analysis
This section compares performance across different subjects to see if students tend to perform better in one subject compared to others. We calculate and visualize the average scores for each subject.

### e) Longitudinal Analysis of Performance
We examine how students' academic scores change over time, considering the entry academic period as the reference point. This includes plotting scores over multiple academic periods to identify longitudinal trends or patterns.

## What We Learned

- **Data Analysis Techniques**: Using Python libraries like `pandas`, `seaborn`, and `matplotlib` for data manipulation and visualization.
- **Statistical Analysis**: Performing t-tests and correlation analysis to understand relationships in data.
- **Data Visualization**: Creating plots to visualize trends and differences in student performance.
- **Longitudinal Analysis**: Analyzing how data changes over time and identifying trends.

## Usage

### Prerequisites

- Python 3.6 or later
- `pandas` library
- `seaborn` library
- `matplotlib` library
- `scipy` library

### Installation

Install the required libraries using pip:

```sh
pip install pandas seaborn matplotlib scipy
