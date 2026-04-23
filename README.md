# Music Recommendation Engine & EDA Report

This repository contains the deliverables for a two-part data science and software engineering project. 

* **Task 1:** An Object-Oriented Music Recommendation Engine built in Python, featuring a Graphical User Interface (GUI).
* **Task 2:** An Exploratory Data Analysis (EDA) report on the music dataset, written in RMarkdown and compiled to PDF.

---

## 📂 Repository Structure

```text
📦 project-root
 ┣ 📜 data.csv                      # The main dataset containing music and artist features
 ┣ 📜 load_dataset_module.py        # Python module: Data parsing and loading
 ┣ 📜 statistics_module.py          # Python module: Statistical calculations (mean, variance, etc.)
 ┣ 📜 similarity_module.py          # Python module: Similarity metrics and ranking functions
 ┣ 📜 user_interface_module.py      # Python module: Tkinter GUI setup and event handling
 ┣ 📜 main.py                       # Python module: Application entry point
 ┣ 📜 EDA_Report.Rmd                # R module: Source code for the Exploratory Data Analysis
 ┣ 📜 EDA_Report.pdf                # R module: Knitted PDF of the data analysis
 ┗ 🎥 video_demonstration.mp4       # 20-minute video walkthrough of the code and GUI

Task 1: Music Recommendation Engine (Python)
A fully Object-Oriented application designed to process music feature data and calculate similarity between artists and individual tracks.

Features
OOP Architecture: Built entirely using classes, methods, and inheritance for robust structure and data encapsulation.

Similarity Metrics: Calculates distances using Euclidean, Cosine, Pearson, and Manhattan similarity algorithms.

Recommendation System: Ranks and returns the top 5 most similar artists or tracks based on the chosen metric.

Graphical User Interface (GUI): A user-friendly tkinter interface that allows users to input pairs of Track IDs, Artist Names, or Track Names and select their desired similarity metric.

Graceful Exception Handling: Validates user inputs and prevents application crashes via structured error handling.

Prerequisites (Task 1)
Python 3.x

Standard Python libraries: csv, math, tkinter (Note: tkinter is included in standard Python installations, but may require a separate system package on certain Linux distributions).

How to Run the Application
Ensure data.csv is located in the root directory.

Open your terminal or command prompt.

Navigate to the project folder.

Execute the main module:

Bash
python3 main.py
Use the GUI to input comparison pairs, select a metric, and view the similarity scores and top 5 recommendations.

📊 Task 2: Exploratory Data Analysis (R)
A comprehensive EDA report investigating the trends, distributions, and correlations within the music dataset.

Key Sections Included in the Report:
Data Import & Setup: Library loading and initial dataset inspection.

Data Cleaning & Preparation: Handling missing values, removing duplicates, and casting appropriate data types for specific features (e.g., danceability, energy, loudness, valence).

Descriptive Statistics: Summaries of numerical and categorical data.

Data Visualisation: Histograms/density plots for feature distribution, boxplots for comparisons (e.g., popularity vs. energy), and scatter plots for continuous variables.

Relationship & Trend Analysis: Correlation heatmaps to identify relationships between audio features and track popularity.

Insights & Interpretation: Final conclusions drawn from the data visualizations.

Prerequisites & Compilation (Task 2)
R and RStudio

Required R Packages: tidyverse, ggplot2, corrplot, dplyr (or equivalent libraries used in the .Rmd file).

To view the report: Open EDA_Report.pdf.

To compile the report: Open EDA_Report.Rmd in RStudio and click "Knit to PDF".

🎥 Video Demonstration
A maximum 20-minute video presentation is included (video_demonstration.mp4). This video covers:

An introduction to the problem and the proposed solution.

A walkthrough of the OOP design and codebase structure.

A demonstration of the Tkinter GUI functionality.

An explanation of the similarity metrics used.

Demonstration of error handling and application stability.
