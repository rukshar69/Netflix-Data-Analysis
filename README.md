# Netflix-Data-Analysis
# Data Source
Kaggle: https://www.kaggle.com/datasets/shivamb/netflix-shows

The source contains data about Netflix TV shows and movies from across the globe. It contains numerous descriptive columns such as title, director, actors, date added, release year, rating, duration, etc.
There are 9000 datapoints for visualization and analysis.

# Analysis by Year Added and Type

There are 2 types of shows in the data: TV shows and movies. They are added from 2008 to 2021 on Netflix library. The first Tableau dashboard portrays the number of shows added per year and indicated/colored by the type of show(tv show/cinema).

Despite the data for date/year added stretches back to 2008, it's after 2015 Netflix substantially increases its collection of shows(from upper chart). In each year(especially after 2017), the number of collected/added movies outnumber tv shows by a considerable margin as can be seen from the bar chart. Collection of movies seems to receive more importance. Additionally, from 2015 onwards, the number shows being added rises ever higher indicating vigorous library expansion by Netflix. 

From both the graphs, we see a drop in the number of movies being added from 2019 to 2020. 2020 was the beginning of COVID pandemic. Here, we see the affect of COVID pandemic on movie collection by Netflix. Probably, less movies have been produced worldwide during that time leading to lower number of movies being added to the platform. By contrast, the number of tv shows being added remained nearly same from 2019 to 2020. 

Link to dashboard: https://public.tableau.com/app/profile/rukshar.alam2/viz/Netflix_16778319201670/Dashboard1


# Netflix Show Distribution by Country on a Map

In Dashboard 2, named Netflix Map, the distribution of shows by nation is shown. The USA leads the nations with the most number of shows on Netflix library. India comes 2nd. However, in Asia alone, India has the most shows. In Europe, England produces the greatest number of shows on Netflix. Globally, England is 3rd. This top 3 ranking remains the same when 'movies' is chosen from the 'Type' drop-down menu indicating the distribution of Netflix movies produced by the countries.


However, when choosing only TV Shows from the drop-down menu, Japan beats India in Asia meaning Japan produces the most TV shows on Netflix in Asia. Globally, Japan is 3rd trailing behind the UK while the USA is still the top producer of TV shows.

Link to dashboard: https://public.tableau.com/app/profile/rukshar.alam2/viz/Netflix_16778319201670/NetflixMap_1

# Netflix Top 10 Genre Analysis

We count the number of shows per genre and display the top 10 genre with the number of shows under the genre.

Globally, various dramas, comedies, documentaries, and children-themed shows dominate the top 10 genre chart.

For country-specific analysis, we choose 3 countries: United State, India, and United Kingdom. Previous 'Netflix shows by map'(check Netflix Map dashboard in Tableau) analysis has shown these 3 nations have the greater number of shows on Netflix library.

In the US(having the largest number of shows on Netflix), children's shows, drama, and comedy appear multiple times in the top 10 genre though the first place goes to documentaries. Action/adventure/thriller also appears in the chart. So, it's a pretty mixed bag.

In the UK(having the largest no. of shows on Netflix Europe), various documentaries/docuseries and British TV shows dominate the chart and drama/comedy takes last 2 positions.

In India(having the largest no. of shows on Netflix in Asia), various forms of drama and comedy takes up most slots in the top 10 genre.