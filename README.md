# Netflix Dashboard 🎬

A Power BI dashboard analyzing Netflix's catalog of movies and TV shows — built to explore content trends by genre, rating, country, and release year.

## About the Project

I built this dashboard using the publicly available **Netflix Titles dataset** (`netflix_titles.csv`), which contains ~8,800 records of Netflix movies and TV shows with details like director, cast, country, date added, release year, rating, duration, genre, and description.

The goal was to turn a raw catalog dump into a quick visual story of what's actually on Netflix — how the library breaks down by content type, genre, rating, and geography, and how it's grown over time.

## What's in the Dashboard

- **KPI cards** – Total titles, total distinct ratings, total directors, and total locations (countries) represented in the catalog
- **Genres by total titles** – Horizontal bar chart of the top genres by number of titles
- **TV shows and movies** – Donut chart showing the overall split between Movies (~70%) and TV Shows (~30%)
- **Ratings by total titles** – Bar chart of titles by content rating (TV-MA, TV-14, TV-PG, R, etc.)
- **Top 10 countries by movies and TV shows** – Treemap highlighting where the most content originates (United States, India, UK, Japan, South Korea, and more)
- **Total movies and TV shows by release year** – Line chart tracking catalog growth from the 1920s through 2020, showing the sharp rise in Netflix originals/acquisitions in the last decade

## Tools Used

- **Power BI Desktop** – data modeling, DAX measures, and report design
- **Dataset**: `netflix_titles.csv`

## Key Insights

- The catalog is dominated by **Movies (~70%)** over TV Shows (~30%)
- **Dramas, International Movies**, **Documentaries**, and **Stand-Up Comedy** are the top genres
- **TV-MA** and **TV-14** are by far the most common ratings, pointing to a mature-audience-skewed library
- The **United States** contributes the largest single share of titles, followed by India and the UK
- Content volume grew steadily but exploded post-2015, peaking around 2018–2020

## Screenshot

<img width="1326" height="747" alt="image" src="https://github.com/user-attachments/assets/79837167-e5c5-4ec9-8d27-54ef5e07c169" />


---

*Built as a data visualization/portfolio project to practice Power BI dashboard design and storytelling with real-world data.*
