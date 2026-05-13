# IPL-Data-Analysis-PowerBI
This project focuses on analyzing IPL (Indian Premier League) data using Power BI to uncover insights related to team performance, player statistics, venue behavior, toss strategies, and match outcomes.  The project includes complete data cleaning, transformation, data modeling, DAX calculations, and interactive dashboard development.

## Business Objectives

- Identify the most successful IPL teams and players
- Analyze batting and bowling performance
- Study toss decision trends and match-winning strategies
- Understand venue behavior and match conditions
- Generate business insights for performance optimization

  ## Tools & Technologies Used

- Power BI
- Power Query
- DAX
- Data Modeling
- Data Cleaning & Transformation

  ## Tools & Technologies Used

- Power BI
- Power Query
- DAX
- Data Modeling
- Data Cleaning & Transformation

  ## Data Cleaning & Transformation

The following cleaning steps were performed:

- Replaced missing city values using venue information
- Handled null values in winner and player_of_match columns
- Removed the umpire3 column due to completely null values
- Replaced dismissal-related null values with meaningful labels
- Standardized team naming inconsistencies
- Verified duplicate records using unique delivery identifiers

## Data Modeling

A one-to-many relationship was created between:
- Matches Table
- Deliveries Table

using Match ID as the primary relationship key.

A star schema approach with single-direction filtering was implemented for optimized reporting and analytical performance.


## Dashboard Pages

### 1. IPL Overview Dashboard
- Match trends
- Toss analysis
- Chasing vs defending analysis
- City-wise match distribution
<img width="1315" height="780" alt="Ipl overall dashboard" src="https://github.com/user-attachments/assets/4781c707-72dd-4528-9e5c-c92908922de9" />


### 2. Team Performance Dashboard
- Team wins
- Toss wins
- Team batting performance
- Winning percentages
- <img width="1317" height="778" alt="Team Performance Analysis" src="https://github.com/user-attachments/assets/f7d82810-61b9-4c5e-bc8b-541aaa379d8d" />


### 3. Player Performance Dashboard
- Best batsmen
- Best bowlers
- Top fielders
- Player of the Match analysis
- <img width="1317" height="779" alt="Player Performance Analysis" src="https://github.com/user-attachments/assets/1493c00f-c25d-4e4b-b54b-5136d3de4292" />


### 4. Venue & Match Condition Dashboard
- Batting-friendly venues
- Bowling-friendly venues
- Venue-based toss strategies
- Match condition analysis
- <img width="1316" height="780" alt="Venue and match condition Aanalysis" src="https://github.com/user-attachments/assets/42a87696-404f-444d-974b-93e6580504ba" />



## Key Insights

- Mumbai Indians emerged as the most successful IPL franchise
- Chasing teams showed slightly higher winning percentages
- Certain venues strongly favored batting performance
- Consistent players significantly impacted match outcomes
- Venue conditions influenced toss strategies and match behavior

  ## Business Recommendations

- Maintain stable core squads for long-term success
- Use venue-specific batting and bowling strategies
- Strengthen death-over bowling resources
- Prioritize impactful players during auctions
- Apply data-driven toss and match planning strategies
