# Movie Recommendation Bot
  - This Python project recommends the top 5 highest-rated movies based on the genre entered by the user. The bot scrapes data from IMDb's top 250 movies list, 
  processes it, and provides movie recommendations in the selected genre.

# Sample Output
![sample-output](/output.png?raw=true "output image")

# Features
   - Genre-Based Recommendations: Input a movie genre, and the bot will return the top 5 movies from IMDb's top 250 list in that genre.
     
   - Accurate Ratings: Uses IMDb ratings to ensure recommendations are of the highest quality.
     
# Library used

- Srapy
    - Used for web scraping IMDb's top 250 movies data.

- pandas
    - Formats the raw scraped data into a structured format for easier processing and analysis.

# Usage
  When prompted, enter the genre of the movie you're interested in (e.g., "Drama," "Comedy," "Action").
  The bot will then display the top 5 highest-rated movies in that genre, based on IMDb ratings.

  # Run the command
  ``` python main.py ```
  
