# Movies_Data_Analysis_App
# Indian Movies Data Analysis App

This is a Streamlit-based application that allows users to explore and analyze Indian movie data. The app provides various filtering options and visualizations to understand movie ratings, votes, genres, languages, and more. 

## Features

- **Movie Search:** Search for movies by name (partial or full, case-insensitive).
- **Filters:** Apply filters for movie genre, language, year, rating, and votes.
- **Data Table:** View filtered movie data in a tabular format.
- **Visualizations:**
  - Top 10 Movies by Rating
  - Top 10 Movies by Votes
  - Rating Distribution
  - Votes Distribution
  - Top Genres by Count
  - Votes vs. Rating by Language

## Prerequisites

- Python 3.x
- Streamlit
- Pandas
- Matplotlib
- Plotly

## Setup

1. Clone the repository:

   ```bash
   git clone <repository_url>
   cd <project_folder>
Install the required dependencies:

bash
Copy code
pip install -r requirements.txt
Ensure the dataset indianmovies.csv is available in the project directory. The dataset should contain the following columns:

Movie Name
Year
Genre
Rating(10)
Votes
Language
Run the Streamlit app:

bash
Copy code
streamlit run app.py
The app will open in your default web browser at http://localhost:8501.

Files
app.py: The main script containing the Streamlit app.
indianmovies.csv: The dataset used for analysis.
requirements.txt: The list of required Python libraries.
How to Use
Search for a Movie: Enter a movie name (partial or full) in the "Search for a Movie" input box to see the matching results.
Apply Filters: Use the sidebar to filter movies by genre, language, year, rating, and votes.
Visualizations: Select different types of visualizations from the dropdown to explore various insights about the movies.
Visualizations Explained
Top 10 Movies by Rating: Displays a table and bar chart for the top 10 movies with the highest ratings.
Top 10 Movies by Votes: Shows the top 10 movies with the highest number of votes in a table and pie chart.
Rating Distribution: A histogram showing the distribution of movie ratings across the dataset.
Votes Distribution: A histogram showing the distribution of votes, with a logarithmic y-axis.
Top Genres by Count: A bar chart representing the count of movies in each genre.
Votes vs. Rating by Language: A scatter plot comparing votes and ratings for movies, categorized by language.
Requirements
The following packages are required to run this app:

streamlit
pandas
matplotlib
plotly
You can install these dependencies using:

bash
Copy code
pip install -r requirements.txt
License
This project is open-source and available under the MIT License. See the LICENSE file for more information.

Acknowledgements
Data for the analysis is sourced from the indianmovies.csv dataset.
The app utilizes Streamlit for creating interactive web applications.
Visualizations are powered by Plotly and Matplotlib.
