#Amazon Prime Video - Explonatory Video Analysis

This project performs an Exploratory Data Analysis (EDA) on the Amazon Prime Video dataset, which contains metadata of over 9,000 titles (movies and TV shows) available on Amazon Prime Video in the United States. The dataset is sourced from JustWatch and includes information from two CSV files: titles.csv (content metadata) and credits.csv (actor/director information).


The Core Question we are trying to answer through our analysis
1. Content Diversity: What genres and show types dominate the platform?
2. Regional Availability: Which production countries contribute most to the library?
3. Trends Over Time: How has the number and type of titles changed over the years?
4. IMDb Ratings & Popularity: What are the patterns in viewer ratings and popularity scores?

The Dataset given to us was:
1. titles.csv - contains Movies and TV Shows
2. credits.csv - Listing of Actors and Directors 
These datasets have the ID column in common and are connected by it.

##Tech Stack
Python, Pandas, Numpy, Matplotlib, Seaborn

amazon-prime-eda/
│
|-- Amazon_Prime_EDA_Filled.ipynb     ← Your main notebook
│
|-- titles.csv                        <- Titles Dataset
│ 
│-- credits.csv                       <- Credits Dataset
│
├── images/                            <- Screenshots of all 15 charts
│   ├── chart1.png
│   ├── chart2.png
│   ├── chart3.png
│   └── ... (all charts)
│
└── 📄 README.md                          ← Project description file