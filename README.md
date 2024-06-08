# Mentor-Mentee Matching System

## Overview
This Python application is a voluntary engineered project prototype used within the context of a collaboration between Singapore Youth AI and ForYouths.sg designed to match mentors and mentees based on the similarity of their profiles. It uses machine learning techniques to analyze and suggest optimal matches from provided datasets of mentors and mentees. 

## Features
- **Data Loading**: Reads mentee and mentor information from an Excel file.
- **Data Preprocessing**: Cleans and prepares the data for analysis, including handling missing values.
- **Similarity Calculation**: Uses TF-IDF vectorization of profile descriptions and subjects of interest to calculate cosine similarity between all mentees and mentors.
- **Matching**: Ranks potential matches based on the similarity scores and suggests the best matches for each mentee.

## Usage
To run this application, you will need Python installed on your system along with the following libraries:
- pandas
- sklearn
- numpy

Make sure you have the data in an Excel file with the required format and update the `file_path` variable in the script to the location of your Excel file.

## Example Output
The program will print the best matches for each mentee, showing the mentor's name and the similarity score.


