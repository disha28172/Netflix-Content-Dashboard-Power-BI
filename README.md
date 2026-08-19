# Netflix Content Dashboard — Power BI

An interactive Power BI dashboard analyzing Netflix's content catalog  genre distribution, 
content ratings, release trends, and movie/TV show split  built to explore how Netflix's 
library has evolved and what content dominates the platform

## Dashboard Preview
![Netflix Dashboard](dashboard.png)

## Key Insights
- International Movies and Dramas are the top genres, together making up ~40% of total titles
- TV-MA and TV-14 dominate content ratings, reflecting a mature-audience-skewed catalog
- Content volume grew sharply post-2015, coinciding with Netflix's global expansion
- Movies outnumber TV Shows roughly 7:3 across the catalog

## Features
- KPI cards for total movies, TV shows, countries, and genres
- Top 5 Genre and Top 10 Rating breakdowns
- Year-range slicer (1925–2021) for interactive filtering
- Movie/TV Show split visualized via pie chart
- Release trend over time (area chart)

## Dataset
Source: [Netflix Movies and TV Shows — Kaggle](https://www.kaggle.com/datasets/shivamb/netflix-shows)
~8,800 titles with metadata including genre, rating, release year, country, and date added.

## Tools Used
- Power BI Desktop
- DAX for calculated measures (distinct counts, top-N filtering)
- Power Query for data cleaning (multi-value genre column, date parsing)


## Project Files
- `Netflix_bi.pbix` – Power BI dashboard
- `dashboard.png` – Dashboard preview
- `netflix_titles.xlsx` – Excel File
- `LICENCE` – MIT Licence
       
    
## How to Use
1. Clone this repo
2. Open `Netflix_bi.pbix` in Power BI Desktop
3. Use the year slider and visuals to explore the data interactively

## Author
Disha Singh
