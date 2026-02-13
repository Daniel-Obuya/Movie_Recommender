Movie Recommendation System
This project is a simple Movie Recommendation System built using Python, pandas, scikit-learn, and difflib. It recommends movies based on content similarity, using features such as genres, keywords, tagline, cast, and director.

Features
Loads movie data from a CSV file (movies.csv)
Cleans and combines relevant features for each movie
Converts text features into numerical vectors using TF-IDF
Computes similarity between movies using cosine similarity
Accepts a user’s favorite movie and finds the closest match in the dataset
Recommends similar movies based on content

How to Use
Clone or download this repository.
Ensure you have Python 3.x installed.
Install required packages:
Place your movies.csv file in the project directory.
Open and run the Movie_Recommendation.ipynb notebook.
When prompted, enter your favorite movie name.
The system will display a list of recommended movies.
Project Structure
Movie_Recommendation.ipynb — Main Jupyter notebook with all code and explanations.
movies.csv — Dataset containing movie information.
Requirements
Python 3.x
pandas
scikit-learn

Notes
The recommendation is based on content similarity, not user ratings.
Make sure your movies.csv file has the necessary columns: title, genres, keywords, tagline, cast, director, and index.
License
This project is for educational purposes. Feel free to use and modify it as needed.


