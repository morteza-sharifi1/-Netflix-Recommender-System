# -Netflix-Recommender-System

## Creating and implementing a content-based recommender system for Netflix

The system recommends movies that are similar to the ones the user likes, based on factors such as genre, runtime, rating, and poster. To obtain this information, an API provided by TMDB is used, which retrieves details of each movie, such as its title and genre, using the IMDB id. In addition, the system utilizes web scraping techniques to obtain user reviews from the IMDB site, which are then analyzed for sentiment using the beautifulsoup4 library

### dataset
The dataset contains movies that were released up until the year 2020.

### Running
To test the Flask deployment, simply run the "python main.py" command.

### demo
![demo](/blob/main/static/pic.jpg)
