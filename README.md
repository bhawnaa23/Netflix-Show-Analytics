# Netflix-Show-Analytics
This repository contains a dashboard for visualizing Netflix data, providing valuable insights into various metrics related to Netflix titles. The dashboard showcases interactive charts and key statistics about the Netflix catalog, including information on genres, ratings, countries, and release years.

Features
The dashboard is composed of the following visualizations:

Overview Cards

Total Genres: Displays the total number of unique genres available on Netflix.
Total Titles: Shows the total number of shows and movies in the Netflix catalog.
Start Date: The earliest release date of a show or movie in the dataset.
End Date: The latest release date of a show or movie in the dataset.
Total Countries: The total number of countries in which Netflix content is available.
Clustered Bar Chart (Genres vs. Titles)

A clustered bar chart comparing the number of titles across different genres. This helps to identify the distribution of content across genres.
Donut Chart (Genres by Count)

A donut chart representing the count of titles within each genre, providing a visual breakdown of genre popularity.
Clustered Bar Chart (Rating vs. Titles)

A clustered bar chart showing how different ratings (e.g., TV-MA, PG-13, etc.) correlate with the number of titles in the catalog.
Tree Map (Show ID by Country)

A tree map that visualizes the number of shows available in each country, allowing for easy identification of the countries with the largest content libraries.
Area Chart (Release Year by Show ID Count)

An area chart displaying the number of shows released each year, allowing trends in content release over time to be easily analyzed.
Dataset
The dataset used for this dashboard contains the following fields:

show_id: Unique identifier for each show or movie in the catalog.
type: Type of the content, either "Movie" or "TV Show".
title: Name of the show or movie.
director: Director(s) of the show or movie.
cast: Cast members of the show or movie.
country: Countries where the show or movie is available.
date_added: Date when the show or movie was added to Netflix.
release_year: Year the content was originally released.
rating: Content rating (e.g., TV-MA, PG-13).
duration: Duration of the movie or TV Show (in minutes for movies or number of seasons for TV shows).
listed_in: Genre(s) the content is listed under.
description: Brief description of the content.
