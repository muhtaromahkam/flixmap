# FlixMap: Discover Trends, Ratings, and Global Distribution of Movies and TV Shows

**FlixMap** is an interactive dashboard designed to visualize global content trends for movies and TV shows. It allows users to explore ratings, genre distributions, and content production trends through various filters and visual insights.

## Project Overview
FlixMap provides in-depth insights into global entertainment trends by leveraging datasets on movies and TV shows. This dashboard offers powerful search and filtering capabilities, enabling users to visualize data through maps, bar charts, pie charts, and more. It presents a comprehensive analysis of movie and TV show trends across different regions, release periods, and genres.

## Objectives
The main objectives of FlixMap are to:
- Filter and search content by title, type (movie/TV show), genre, and other attributes.
- Visualize the distribution of movies and TV shows across different countries.
- Analyze trends in ratings, content production, and distribution.
- Highlight key performance metrics such as top genres, ratings breakdown, and yearly content release trends.

## Dashboard Features
FlixMap comes with the following key features:

### Filters & Search
- **Content Type Filter**: Toggle between Movies and TV Shows.
- **Title Search**: Quickly look up specific titles by name.
- **Detailed Content Information**: Includes ratings, genre, duration, release year, and the date the content was added to the platform.

### Visual Representations
- **World Map**: Displays the geographic distribution of content by country.
- **Bar Chart**: Shows the distribution of ratings, sorted in descending order.
- **Pie Charts & Graphs**:
    - Breakdown of content by genre.
    - Production trends by year.

## Tools & Technologies
- **Tableau**: Used for building the interactive visualizations and dashboard.
- **Data Sources**: Includes datasets from **IMDb** and **TMDb** for detailed movie and TV show information.

## Repository Structure

```bash
📦 FlixMap/
 ┣ 📂 datasets/
 ┃ ┗ 📜 movies-tvshows.csv           # Source data used in the project.
 ┣ 📂 dashboards/
 ┃ ┗ 📜 dashboard_screenshots/       # Screenshots of different sections of the Tableau dashboard.
 ┣ 📜 README.md
 ┣ 📜 FlixMap.twbx                   # Tableau workbook file.
```
- datasets/: Contains the dataset file movies-tvshows.csv, which is used for analysis.
- dashboards/: Contains screenshots of the dashboard for preview purposes.
- FlixMap.twbx: The Tableau workbook file to open the dashboard.

## Future Improvements
Some areas for future development include:
- Adding more detailed filtering options (e.g., highly-rated movies in specific countries).
- Integrating data from streaming platforms (e.g., Netflix, Amazon Prime).
- Incorporating predictive analytics to forecast future trends in content production and distribution.

## Usage
To explore the FlixMap dashboard:
- Open the FlixMap.twbx file in Tableau.
- The dataset used for the project can be found in the datasets directory.
- Navigate through the various visualizations to explore trends and insights.
