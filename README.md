# Movie Recommender Project using Machine Learning

Welcome to the Movie Recommender Project! This project is designed to provide movie recommendations based on machine learning concepts. It predicts a set of 5 movies that are similar to a given movie, allowing users to discover new movies that align with their preferences.

## Project Overview

The Movie Recommender System employs machine learning techniques to suggest movies that are similar to a user-specified movie. The recommendation is based on a precomputed similarity matrix and a movie dictionary, which are generated using the `MRS.ipynb` notebook.

## Prerequisites

Before running the project, make sure you have the following:

- Python (version XYZ or higher)
- Git (for version control)
- Required libraries (install using `pip install -r requirements.txt`):
  - Streamlit
  - NumPy
  - Pandas

## Usage

1. Enter command "streamlit run app.py" in terminal.

2. You will see an input box where you can enter the name of a movie.

3. After entering the movie name, click the "Show Recommendations" button.

4. The app will display a list of 5 movies that are similar to the input movie based on the precomputed similarity matrix.

## Note

This project relies on the `Similarity.pkl` and `movie_dict.pkl` Pickled files, which are generated using the `MRS.ipynb` notebook. These files should be extracted from the notebook and placed in the project directory before running the app. Failing to do so may result in errors.

## Credits

This project was developed by Sashi Sekhar Singh. Feel free to contact me at ssashi1212@gmail.com for any inquiries or feedback.

Enjoy discovering new movies with our Movie Recommender Project!
