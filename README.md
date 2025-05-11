# BAIS3250-A | NCAA Football Project
---
The purpose of this README is to give a brief introduction and overview of our project.
To access our project, we have two folders: Data Scraping and Data Analysis. Each folder has a README file epxlaining our code, websites, csv, analytical methods, or any other detail within our project that needs to be further explained.
---
### Table of Contents
| File | Description |
| ------ | ------ |
| ProjectScraping | jupyter notebook with code for scraping the data tables from our two websites and integrating scraped datasets |
| ProjectAnalysis | jupyter notebook with code that applies analytics to our integrated data to answer our research questions |

---
## Data Dictionary

This table describes the fields present in the dataset.

| Field                     | Type      | Description                                                                                               |
|---------------------------|-----------|-----------------------------------------------------------------------------------------------------------|
| Teams                     | Text      | College Name                                                                                              |
| Conference                | Text      | Conference in which the team belongs                                                                        |
| Wins                      | Numeric   | Number of games won in the regular season                                                                 |
| Losses                    | Numeric   | Number of games lost in the regular season                                                                |
| Win %                     | Numeric   | The percentage of a team’s wins compared to a team’s losses in the regular season                        |
| MOV                       | Numerical | Average margin of victory (points)                                                                          |
| ATS +/-                   | Numerical | Against the spread record sports betting displayed as covered-not-covered-tie                             |
| MOV_Status                | Text      | Categorized MOV based on whether a team has a MOV >=0 (Positive) or < 0 (Negative)                       |
| G (Games played)          | Numerical | Total number of games played in the regular season                                                        |
| Offensive Rank            | Numerical | Determined rank based on a variety of offensive metrics and season performance                              |
| Offense TDs               | Numerical | Total number of combined offensive touchdowns in a regular season                                         |
| Total Offense YPG         | Numerical | Season average of offensive yards per game                                                                |
| Rushing Rank              | Numerical | Determined rank based on a variety of offensive rushing metrics and season performance                      |
| Rushing TDs               | Numerical | Total number of rushing touchdowns in a regular season                                                    |
| Rush YPG                  | Numerical | Season average of offensive rushing yards per game                                                        |
| Passing Rank              | Numerical | Determined rank based on a variety of offensive passing metrics and season performance                      |
| Pass YPG (Passing yard per game) | Numerical | Season AVG of Passing Yards / games                                                                   |
| Passing TDs               | Numerical | Total number of passing touchdowns in a regular season                                                    |
| Int (Interceptions)       | Numerical | Total number of picked passes (interceptions) thrown from the offense in a regular season                  |
| Total Defense YPG         | Numerical | Season average of defensive yards per game                                                                |
| Defensive Ranking         | Numerical | Determined rank based on a variety of defensive metrics and season performance                              |
| Opp TDs (Opponent Touchdowns) | Numerical | Total number of opponent’s touchdowns throughout the regular season                                     |
| Rushing Defensive Rank    | Numerical | Determined rank based on a variety of metrics involving how a defense performs against an offense’s rushing plays |
| Opp Rush TDs (Opponent Rushing Touchdowns) | Numerical | Total number of opponent’s rushing touchdowns throughout the regular season                      |
| Opp Rush YPG (Opponent Rushing Yard per game) | Numerical | Season AVG of the total number of yards gained by the opposing team through running plays during a game |
| Passing Defensive Rank    | Numerical | Determined rank based on a variety of metrics involving how a defense performs against an offense’s passing plays |
| Opp Pass TDs              | Numerical | Total number of opponent’s passing touchdowns throughout the regular season                               |
| Opp Pass YPG              | Numerical | Season AVG of the total number of yards gained by the opposing team through passing plays during a game     |
| TM Rank                   | Numerical | Determined rank based on a variety of turnover metrics and season performance                               |
| Fumbles Recovered         | Numerical | Total number of fumbles recovered in a regular season                                                     |
| Fumbles Lost              | Numerical | Total number of fumbles lost in a regular season                                                          |
| Turnover Margin           | Numerical | Total number of giveaways (interceptions & fumbles lost) from the total number of takeaways (interceptions & opponent fumble recoveries) in a regular season |
| PPG Rank (Penalties Per Game Rank) | Numerical | Determined rank based on a variety of penalty metrics and season performance                            |
| Penalties                 | Numerical | Total number of penalties in a regular season                                                             |
| Penalties Per Game        | Numerical | Season AVG of the number of penalties a team receives in a game                                            |
| Penalty YPG Rank          | Numerical | Determined rank based on a variety of penalty metrics and season performance                            |
| Penalty YPG               | Numerical | Season AVG of the total number of yards lost because of penalties                                           |
| TOP Rank                  | Numerical | Determined rank based on a variety of penalty metrics and season performance                            |
| Avg Time of Possession    | Time      | Season AVG of a team’s offensive time of possession during games                                          |
| ATP Rank                  | Numerical | Determined rank based on a team’s average time of possession compared to other teams in the NCAA            |
| Season                    | Numerical | The football season in which the team's data was collected                                                 |
| Season_Date               | Date      | Dummy date variable for Time Series analysis with Season field                                             |

---

## 🔍 Research Questions

1. **Which statistical categories have the greatest correlation with wins among teams?**
2. **Do teams with balanced offensive and defensive performance achieve higher margins of victory than teams with one-sided strengths?**
3. **Do any teams have a high count of games with a statistically average or below-average offense/defense?**
4. **Are there any outliers of teams with statistically below-average offense/defense that obtained more wins than ones with above-average numbers?**
5. **5.	Are there certain conferences that present higher overall statistics. For example, does one conference have multiple teams with highly ranked offenses compared to all other conferences?**
6. **6.	Can we predict a team’s potential MOV based on a conference’s average performance throughout Seasons 2021 through 2024?**

---

## 📈 Methods Used

- **Descriptive Statistics**  
  - Summary stats and correlation analysis for key variables (e.g., mean yards/game, win %, MOV).

- **Hypothesis Testing**  
  - T-tests, Pearson correlation, and p-values to evaluate whether relationships are statistically significant.

- **Machine Learning**
  - Linear Regression
  - Linear Regression with train test split

- **Time Series**
  - Winters-Holt Method

---

## 📌 Future Improvements

- Include defensive metrics for a more holistic view.
- Explore classification models (e.g., logistic regression) to predict championship eligibility.
- Incorporate play-by-play or player-level data for deeper insights.

---

## 👥 Contributors

- Emily Sanders – Data Analysis, Modeling, Report Writing
- Emily Nell - Data Analysis, Modeling, Report Writing
- Chaitanya Patel - Data Analysis, Modeling, Report Writing
