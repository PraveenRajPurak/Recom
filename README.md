Overview:
Recom is a recommendation system for movies developed by Praveen Raj, Sarthak Chawla,
and Aman Dixit. The system utilizes movie data from the MovieLens dataset to provide
personalized movie recommendations to users based on their preferences. The project
consists of a Flask web application that allows users to input their userID, which then fetches
and displays relevant movie recommendations.
File Structure:
RECOM
│ app.py
│ average_merged_movies.csv
│ sorted_movies_by_rating.csv
│ user_favorite_genres_and_movies.csv
│
└───__pycache__
│
└───assets
│
└───static
│ │ style.css
│ │ styles2.css
│
│ index.html
│ results.html
│
└───venv
File Descriptions:
● app.py: The main Python script containing the Flask application logic.
● average_merged_movies.csv: A CSV file containing the average rating of all movies.
● sorted_movies_by_rating.csv: A CSV file containing movies sorted by rating in
descending order.
● user_favorite_genres_and_movies.csv: A CSV file containing genre-specific movies
highly rated by the user.
● index.html: HTML file for the user interface where the user inputs their userID.
● results.html: HTML file for displaying the movie recommendations to the user.
● static: Directory containing static files such as CSS stylesheets.
● venv: Directory containing the Python virtual environment.
How to Run the Project:
● Extract the contents of the recom-main.zip file to a directory on your system.
● Ensure that Flask is installed on your system. If not, install Flask using pip:
○ pip install flask
● Open a terminal or command prompt and navigate to the directory where the project
files are extracted.
● Activate the Python virtual environment (if not already activated):
○ source venv/bin/activate
○ or
○ venv\Scripts\activate
● Run the Flask application by executing the app.py script:
○ python app.py
● Once the Flask application is running, open a web browser and go to
http://localhost:5000 to access the application.
● Enter your userID in the provided input field on the index page and submit the form.
● The application will fetch and display personalized movie recommendations based on
your preferences on the results page.
● Note: Ensure that all CSV files (average_merged_movies.csv,
sorted_movies_by_rating.csv, user_favorite_genres_and_movies.csv) are present in
the same directory as app.py for the application to function correctly
