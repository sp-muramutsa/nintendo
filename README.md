# Nintendo Game Reviews Analysis

## Project Overview

This project analyzes Nintendo game reviews using data from Mobygames. It includes data cleaning, review analysis, and visualizations to understand user and critic reviews for various Nintendo games.

## Project Structure

- `notebooks/`: Contains Jupyter notebooks for data analysis and visualization.
  - `nintendo.ipynb`: Performs data scraping, extraction, and CSV file creation.
  - `nintendo_viz.ipynb`: Contains data visualization and analysis of game reviews.
- `data/`: Contains the dataset used for analysis.
  - `nintendo.csv`: CSV file with Nintendo game review data.
- `plots/`: Contains generated visualizations.
  - `user_reviews_pie.png`: Pie chart showing distribution of user reviews.
  - `critics_reviews_pie.png`: Pie chart showing distribution of critic reviews.
  - `breakdown.png`: Breakdown of game data by publisher, developer, release, genre, perspective, and gameplay.

## Getting Started

### Prerequisites

- Python 3.x
- Required libraries: `pandas`, `plotly`, `beautifulsoup4`, `requests`, `selenium`

### Setup

1. Clone this repository:
   ```bash
   git clone <repository_url>
   cd <repository_directory>
2. Install the necessary Python packages:
   ```bash
   pip install pandas plotly beautifulsoup4 requests selenium
   Ensure you have the Chrome WebDriver installed and available in your PATH.

### Running the Notebooks
1. Open Jupyter Notebook:
   ```bash
   jupyter notebook

2. Navigate to the `notebooks/` folder and open nintendo.ipynb to run the data scraping and CSV creation.

3. Open `nintendo_viz.ipynb` to generate and view visualizations.

### Analysis and Results
- User Reviews Analysis: Visualization of user reviews for Nintendo games, highlighting popular games based on user feedback.
- Critic Reviews Analysis: Visualization of critic reviews, showing how critics rate Nintendo games.
- Data Breakdown: Comprehensive pie charts breaking down the game data by publisher, developer, release date, genre, perspective, and gameplay.
