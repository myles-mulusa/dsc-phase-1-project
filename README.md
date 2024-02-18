# Microsoft Movie Analysis Project

## Project Overview

This project involves exploratory data analysis (EDA) on a dataset containing information about movies. The goal is to provide insights that can help Microsoft make informed decisions when entering the film industry.

## Business Understanding

### Introduction

Microsoft is considering entering the film industry and requires a comprehensive analysis of movie data to guide its strategy. This project aims to provide insights into the types of movies that are popular, profitable, and well-received by audiences.

### Stakeholders

- **Microsoft Decision-Makers**: Utilize the analysis to understand trends and preferences in the film industry.
- **Marketing Team**: Gain insights into audience preferences for targeted marketing strategies.
- **Production Team**: Understand the characteristics of successful movies for informed production decisions.

## Data Understanding

### Data Sources

The dataset used in this project is sourced from [Box Office Mojo](https://www.boxofficemojo.com/), [IMDb](https://www.imdb.com/) and [The Movie Database](https://www.themoviedb.org/). It includes information about movie titles, genres, ratings, box office earnings, and more.

### Dataset Overview

- Size: X rows, Y columns
- Descriptive Statistics: Provide summary statistics for key features (e.g., runtime, ratings, earnings).
- Feature Justification: Include features based on relevance and significance for the analysis.
- Limitations: Acknowledge any data limitations that may impact the analysis.

## Project Structure

microsoft-movie-analysis/
│
├── notebooks/
│ ├── student.ipynb
│ └── ...
│
├── data/
│ ├── bom_movie_gross/
| |-- imdb_title_ratings/
| |-- imdb_title_basics/     
│ ├── merged_data/
| |-- df  
│ └── ...
│
├── scripts/
│ ├── data_preprocessing.py
│ └── ...
│
├── README.md
├── presentation/
│ └── presentation.pdf
│
├── sources/
│ └── data_sources.md
│
└── ...

## Usage

To reproduce the analysis, follow these steps:

1. Clone the repository to your local machine.
2. Navigate to the `notebooks` directory and open `exploratory_data_analysis.ipynb`.
3. Execute each cell in the Jupyter notebook to perform the analysis.

## Dependencies

- Python 3.7
- Jupyter Notebook
- pandas
- matplotlib
- seaborn

## Setup

1. Install Python and Jupyter Notebook on your machine.
2. Create a virtual environment (optional but recommended).
3. Install dependencies using `pip install -r requirements.txt`.

## Contributing

Feel free to contribute to this project by opening issues or submitting pull requests. Follow coding conventions and provide clear documentation for any changes.

## License

This project is licensed under the MIT License - see the [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT) file for details.
- [Setup](#setup)
- [Contributing](#contributing)
- [License](#license)

