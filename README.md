# BAIS3250-A | NCAA Football Project
---
The purpose of this README is to give a brief introduction and overview of our project.
To access our project, we have two folders: Data Scraping and Data Analysis. Each folder has a README file epxlaining our code, websites, csv, analytical methods, or any other detail within our project that needs to be further explained.
---
### Table of Contents
| File | Description |
| ------ | ------ |
| ProjectScraping | jupyter notebook with code for scraping the data tables from our two websites and integrating scraped datasets |
| NCAA_football_win_loss_trends.csv | scraped data tables from [BetIQ website](https://betiq.teamrankings.com/college-football/betting-trends/win-loss-records/) over 4 seasons with data that includes win-loss percentage, margin of victory, and better statistics|
| NCAA_raw_data.csv | scraped data tables from [NCAA website](https://stats.ncaa.org/rankings?sport_code=MFB&division=11) over 4 seasons for D1 NCAA football teams |
| merged_college_football_data.csv | merged dataframe from NCAA_football_win_loss_trends.csv and NCAA_raw_data.csv |
| ProjectAnalysis | jupyter notebook with code that applies analytics to our integrated data to answer our research questions |

---
### Data Dictionary
| Field | Type | Description |
| ------ | ------ | ------ |
| Teams | Text | College Name |
| Conference | Text | Conference in which Team Belongs |
| Win % | Numerical | The percentage of time the team won compared to the team’s losses  |
| MOV  | Numerical | Average margin of victory (points)  |
