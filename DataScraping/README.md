# Data Scraping | NCAA Football Project
---
Within this DataScraping folder are our team's Jupyter notebooks for scraping the NCAA and BETIQ website for seasons 2021-22 through 2024-25. The data obtained from these websites were then cleaned and merged with one another. The final csv file of the scraped, merged, and cleaned data is used to answer our analysis questions. 
---
### Table of Contents
| File | Description |
| ------ | ------ |
| NCAA_Scraped_Data.ipybn | jupyter notebook code that scrapes and clean data from [NCAA website](https://stats.ncaa.org/rankings?sport_code=MFB&division=11) over 4 seasons for D1 NCAA football teams |
| NCAA_stats.csv | scraped data from [NCAA website](https://stats.ncaa.org/rankings?sport_code=MFB&division=11) over 4 seasons for D1 NCAA football teams |
| Project_Scraping_Merging.ipybn | jupyter notebook code that scrapes and clean data from [BetIQ website](https://betiq.teamrankings.com/college-football/betting-trends/win-loss-records/), and merges and cleans that data with NCAA_stats.csv |
| NCAA_football_win_loss_trends.csv | scraped data tables from [BetIQ website](https://betiq.teamrankings.com/college-football/betting-trends/win-loss-records/) over 4 seasons for D1 NCAA football teams |
| merged_NCAA_football_stats.csv | merged dataframe from NCAA_football_win_loss_trends.csv and NCAA_raw_data.csv |
