# End To End Cricket Data Analytics Project

## Dashboard Link
[Power BI Dashboard](https://app.powerbi.com/links/hW7i4k80UB?ctid=4b71ad5f-a29b-46b4-8d1a-9c98f79cef46&pbi_source=linkShare)

## Project Description
This project involves web scraping from [ESPN Cricinfo ](https://www.espncricinfo.com) ![m](https://github.com/user-attachments/assets/9f998f8a-48af-4010-96b7-ec64fb6e0924)

 data processing with Python and Pandas, and data visualization with Power BI. The analysis focuses on T20 World Cup cricket data, including batting, bowling, player information and match results.

## Problem Statement
The dashboard helps cricket analysts and enthusiasts understand the performance and statistics of teams and players in the T20 World Cup 2024. By analyzing various metrics such as batting averages, bowling economies, and match results, stakeholders can gain insights into team strategies, player performances, and match outcomes.

### Steps Followed

- **Step 1**: Web Scraping
  - Utilized JavaScript to scrape data from ESPN Cricinfo for batting, bowling, and match results.
  ![c](https://github.com/user-attachments/assets/b820ab16-2eee-467e-9769-1250d153cf95)

  - Files: `t20_wc_batting_summary.js`, `t20_wc_bowling_summary.js`, `t20_wc_match_results.js`.

- **Step 2**: Data Processing
  - Loaded the scraped data into Python using Pandas for cleaning and transformation.
  - [dim_players.xlsx](https://github.com/user-attachments/files/16309675/dim_players.xlsx) 

[fact_bating_summary.xlsx](https://github.com/user-attachments/files/16309676/fact_bating_summary.xlsx) 

[fact_bowling_summary.xlsx](https://github.com/user-attachments/files/16309678/fact_bowling_summary.xlsx) 

[dim_match_summary.xlsx](https://github.com/user-attachments/files/16309679/dim_match_summary.xlsx)

  - Saved the cleaned data into an Excel files.

- **Step 3**: Power BI Dashboard
  - Imported the Excel data into Power BI.
  - Created various visuals including bar charts, line charts, and tables to represent the cricket data.
  - ![Screenshot 2024-07-19 142533](https://github.com/user-attachments/assets/5d9e9106-d8ed-4351-8ba4-06b9e5eed191)

![Screenshot 2024-07-19 142617](https://github.com/user-attachments/assets/38e5e93e-25d4-4d2c-9a14-7a18dc344fd0)

![Screenshot 2024-07-19 142155](https://github.com/user-attachments/assets/957a9f83-0060-4a68-b911-b815f085fd31)

![Screenshot 2024-07-19 142438](https://github.com/user-attachments/assets/7808707d-7455-4c5d-869b-955863236a42)

  - Added slicers for filtering data based on teams, players, and match types.

- **Step 4**: Data Analysis
  - Analyzed batting performances, bowling statistics, and match results.
  - Derived insights on top performers, team strengths, and match outcomes.
  - [Paramaeter Scoping]([Paramaeter Scoping.pdf](https://github.com/user-attachments/files/16310029/Paramaeter.Scoping.pdf)) 

- **Step 5**: Publish
  - Published the Power BI report to Power BI Service for sharing and collaboration.

## Files in the Repository
- **t20_wc_batting_summary.js**: JavaScript code for scraping batting summary data. [t20_wc_batting_summary.json](https://github.com/user-attachments/files/16309803/t20_wc_batting_summary.json)

- **t20_wc_bowling_summary.js**: JavaScript code for scraping bowling summary data. [t20_wc_bowling_summary.json](https://github.com/user-attachments/files/16309827/t20_wc_bowling_summary.json)

- **t20_wc_match_results.js**: JavaScript code for scraping match results data. [t20_wc_match_results.json](https://github.com/user-attachments/files/16309831/t20_wc_match_results.json)
- **t20_wc_player_info.js**: JavaScript code for scraping match results data. [t20_wc_player_info.json](https://github.com/user-attachments/files/16309847/t20_wc_player_info.json)


- **dim_match_summary.xlsx**: Excel file containing the cleaned data. [dim_match_summary.xlsx](https://github.com/user-attachments/files/16309873/dim_match_summary.xlsx)

- **fact_bating_summary.xlsx**: Excel file containing the cleaned data. [fact_bating_summary.xlsx](https://github.com/user-attachments/files/16309865/fact_bating_summary.xlsx)

- **fact_bowling_summary.xlsx**: Excel file containing the cleaned data. [fact_bowling_summary.xlsx](https://github.com/user-attachments/files/16309866/fact_bowling_summary.xlsx)

- **dim_players.xlsx**: Excel file containing the cleaned data.[dim_players.xlsx](https://github.com/user-attachments/files/16309863/dim_players.xlsx)



