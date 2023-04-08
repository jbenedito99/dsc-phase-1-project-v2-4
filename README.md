# <b> Overview </b>
This repository houses various documents for a project. The project involved an extensive analysis of different movie datasets. The respository's main features of interest are a Jupyter notebook (titled student.ipynb) and a presentation, which house the coding and results of the movie data analysis. There is also an ERD schematic of the im.db SQL database, which was a prominent source of data used.

# <b> Business Context </b>
Generally-speaking, this repository is applicable to up-and-coming movie studios that are beginning their journey in the film industry and are not sure where to begin.
More specifically, this project was done under the hypothetical guise that Microsoft wants to start a new film studio, but is not well-versed in movies and needs help
deciding on the types of movies to make. 

The key business questions that this project answers are:
- <b>What genre(s) of film earns the highest ratings?</b>
- <b>What is an optimal runtime for a movie?</b>
- <b>What is a production budget that will lead to a high worldwide gross?</b>

# <b> Datasets </b>
The datasets used for this project were an SQL database housing information from IMDB (im.db) and a csv file with data from The Numbers (tn.movie_budgets.csv).
- The <b>im.db</b> database had two main tables of interest: 
  - <b>movie_basics</b> 
    - Columns: movie_id, primary_title, original_title, start_year, <b>runtime_minutes</b>, <b>genres</b>
  - <b>movie_ratings</b>
    - Columns: movie_id, <b>average_rating</b>, numvotes
- The <b>tn.movie_budgets.csv</b> had information on financial aspects of films.
  - Columns: id, release_date, movie, <b>production_budget</b>, domestic_gross, <b>worldwide_gross</b>

The <b>im.db</b> database was used to determine <b>genre</b> and <b>optimal runtime</b> from <b>average rating</b>.
The <b>tn.movie_budgets.csv</b> was used to determine an <b>optimal production budget</b> from <b>worldwide gross</b>.
  
  # <b> Visualizations </b>
![image](https://user-images.githubusercontent.com/125815448/230698505-0cea1700-4f71-4934-966e-c7f5dbbca132.png)

![image](https://user-images.githubusercontent.com/125815448/230698556-5bed4447-5995-40b4-86f9-8b8b1605940a.png)

![image](https://user-images.githubusercontent.com/125815448/230698474-fe4b684b-208e-4cff-a23c-2726398dc6af.png)

![image](https://user-images.githubusercontent.com/125815448/230698536-f978318a-ced7-4d74-a1b9-58ed30f05f9f.png)
  
  # <b> Conclusion </b>
  My suggestions:
  - The <b>genres</b> to focus on are <b>action, adventure, and drama</b>.
  - A film's <b>runtime</b> should be a <b>minimum of 130 minutes</b>.
  - A film's <b>production budget</b> should be a <b>minimum of $100M</b>.
