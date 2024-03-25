# My Top Movies 
 Day 64 of 100 days of Code

This is a Flask-based web application for rating and reviewing movies. Users can view a list of movies, rate and review them, add new movies, and delete existing ones. The application integrates with The Movie Database (TMDB) API to fetch movie details and poster images.

## Features
* View a list of movies sorted by rating.
* Rate and review movies.
* Add new movies by searching through TMDB API.
* Delete existing movies.
* Responsive design using Bootstrap 5.

## Prerequisites
Before running the application, ensure you have the following installed:
* Python 3.x
* Flask
* Flask Bootstrap
* Flask SQLAlchemy
* Flask WTF
* Requests

You can install the required packages using the following command:

```bash
pip install -r requirements.txt
Setup
Clone the repository:
bash
Copy code
git clone https://github.com/yourusername/movie-rating-app.git
Navigate to the project directory:
bash
Copy code
cd movie-rating-app
```

## Set up environment variables:

Obtain a TMDB API key from TMDB website and store it in an environment variable named TMDB_API_KEY.
Run the application:

```bash
python main.py
```
The application will be accessible at http://localhost:5000 in your web browser.

## Usage
- Visit the homepage to view a list of movies sorted by rating.
- Click on a movie to view details, rate, and review it.
- Use the search form to add new movies by title.
- Click on "Delete" next to a movie to remove it from the list.
