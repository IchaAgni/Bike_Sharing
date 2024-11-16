# Bike Sharing Analysis with Python - Dicoding  ✨

[Bike Sharing Dashboard Streamlit App](https://bikesharing21.streamlit.app/)

## Table of Contents
- [Overview](#overview)
- [Project Structure](#project-structure)
- [Installation](#installation)
- [Usage](#usage)
- [Data Sources](#data-sources)

## Overview
This project is a data analysis and visualization project focused on Bike Sharing. It includes code for data wrangling, Exploratory Data Analysis (EDA), and a Streamlit dashboard for interactive data exploration. This project aims to analyze data on the Bike Sharing Dataset.

## Project Structure
- `dashboard/`: This directory contains dashboard.py which is used to create dashboards of data analysis results.
- `data/`: Directory containing the raw CSV data files.
- `notebook.ipynb`: This file is used to perform data analysis.
- `README.md`: This documentation file.
- url.txt : This is link streamlit deployed

## Installation

Clone this repository to your local machine:
```
git clone https://github.com/IchaAgni/BikeSaharing.git
```
### Setup Environment - Anaconda
```
conda create --name main-bike python=3.9
conda activate main-bike
pip install -r requirements.txt
```
### Setup Environment - Shell/Terminal
Go to the project directory
```
cd Bike Sharing
cd dashboard
```
### Run steamlit app
```
streamlit run dashboard.py
```

## Usage
1. **Data Wrangling**: Data wrangling scripts are available in the `notebook.ipynb` file to prepare and clean the data.

2. **Exploratory Data Analysis (EDA)**: Explore and analyze the data using the provided Python scripts. EDA insights can guide your understanding of e-commerce public data patterns.

3. **Visualization**: Run the Streamlit dashboard for interactive data exploration:

```
cd dashboard/dashboard
streamlit run dashboard.py
```
Access the dashboard in your web browser at `http://localhost:8501`.

## Data Sources
The project uses Bike Sharing Dataset from [Belajar Analisis Data dengan Python's Final Project] offered by [Dicoding](https://www.dicoding.com/).
