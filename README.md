# Netflix-shows-and-movies-analysis
• A data analytics project using Python to clean, filter, and analyze Netflix's library content to uncover historical patterns, regional distributions, and genre classifications.
# Comprehensive Analysis of Netflix Streaming Catalog

## Project Overview
This repository contains a data analytics project dedicated to examining the content landscape of the Netflix streaming platform. The primary objective is to investigate the distribution of movies and television shows, analyze release year trends over recent decades, map out country-specific production concentrations, and classify the prevalence of specific genres across the entire database.

The workflow is built entirely in Python using a Jupyter Notebook framework to clean raw metadata and convert it into structured statistical insights.

## Directory Structure
The repository consists of the following primary components:
* `notebook.ipynb` contains the executable code pipeline covering data ingestion, handling of missing fields, conditional filtering, and trend visualizations.
* `netflix_data.csv` serves as the primary relational dataset containing columns such as unique identifiers, content types, show titles, directors, cast rosters, release dates, durations, and category descriptions.
* `redpopcorn.jpg` is a static graphic asset used to visually anchor the multimedia context of the streaming platform analysis.

## Technical Implementation
The computational data pipeline utilizes standard open-source Python libraries:
* Pandas for high-level data manipulation, parsing string elements, treating null rows, and executing multi-variable query filters.
* NumPy for performance-oriented vectorized operations and indexing array data structures.
* Matplotlib and Seaborn for plotting category counts, historical timeline frequency curves, and distribution plots.

## Key Operational Insights
The analysis explores several critical questions regarding entertainment catalog trends:
* Media Type Division: Statistical assessment of the exact balance between feature-length movies and serialized TV shows on the platform.
* Historical Proliferation: Evaluation of how the volume of content added to the library has accelerated over time, highlighting specific peak eras.
* Geographic Clusters: Analysis of regional metadata fields to map which international industries produce the highest volume of available content.

## Execution Instructions
To replicate the dataset insights locally:
1. Clone this repository to your local system using a Git terminal command or interface.
2. Ensure you have Python 3 installed along with the pandas, matplotlib, and seaborn packages.
3. Keep the primary CSV file in the same workspace directory as the notebook to avoid path reference errors.
4. Launch the Jupyter Notebook and execute the code cells sequentially from top to bottom.
