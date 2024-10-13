# Team 8 Mist 4610 Group Project 1

## Team Name: 
select * from MIST4610 where grade = A; 

## Team Members:

1. Gus Wilkerson [@augwilk](https://www.github.com/augwilk)

## Problem Description:

The task at hand:
Today, college football data is spread across multiple platforms and sources, making it difficult to get a clear and accurate picture of the sport. Since this approach is broken up across platforms, it is difficult to access and analyze key statistics or trends over time. To address this issue, the NCAA has launched a project to create an essential database of Division 1 college football statistics.
Specifically, the project aims to create a unified data repository for all D1 conferences, players, and head coaches, including in-depth statistics such as NIL, wins, losses, and game statistics among others.


## Data Model

Explanation of data model: 


![Project Diagram](https://github.com/user-attachments/assets/e39815d3-a0fe-4377-876d-d4131b634156)

## Data Dictionary:
![Screenshot (72)](https://github.com/user-attachments/assets/82634b2b-0daf-4d5b-b2d9-45b62b11f1eb)

![Screenshot (73)](https://github.com/user-attachments/assets/f834ddce-d98a-4289-b05a-091d4bfe146f)

![Screenshot (74)](https://github.com/user-attachments/assets/cbd29dbd-fec7-40c4-9b17-bcdd424f8c47)

![Screenshot (75)](https://github.com/user-attachments/assets/55f7ca9e-76d2-49e3-a339-c9880c859719)

![Screenshot (77)](https://github.com/user-attachments/assets/22b193fd-f661-43c9-963a-4435a12a9ecd)

![Screenshot (78)](https://github.com/user-attachments/assets/6525768b-ea41-49a6-ba09-3431e74f6bbf)

![Screenshot (80)](https://github.com/user-attachments/assets/01c66565-38a3-46e5-986d-9146cf72e75c)

![Screenshot (85)](https://github.com/user-attachments/assets/bcf0973f-fbda-4a77-8568-42ee1d11532b)

![Screenshot (86)](https://github.com/user-attachments/assets/7d285e9e-2eb4-442b-a8ff-3f0dbc14ed91)

![Screenshot (87)](https://github.com/user-attachments/assets/a125aa6f-7d8e-4784-a3d1-74155a016e1a)






## Queries:

1. Query 1 lists the players that have NIL deals with the company Nike along with their cummulative statictics for teh season. The results are ordered from greatest to least stats with priority given to passing yards and then receiving yards. 

![Screenshot (63)](https://github.com/user-attachments/assets/861b5818-259b-41e1-bf08-48344921dfaa)

Query 1 allows managers to see which signed players are perfroming the best. A company like Nike would want to sign with the highest producing atheletes to help build their brand as an elite sporting wear producer. The company may need to consider cutting deals with certain athletes that are nto perfroming well or look into extending contracts with high performing players. This query also reveals areas Nike could continue to grow. For example, Only one player signed with Nike has a significant numebr of rushing yards. This may entice Nike to look into other running backs to sponsor to continue to grow and promote their brand in teh college football landscape. This query could help Sponsors make informed decsions and assess how their contracted players are performing.

2. Query 2 shows which head coach and their team exceeded the average number of wins in the SEC.

![3](https://github.com/user-attachments/assets/07b962b5-4bf0-4433-8f26-094ad190250b)

Query 2

Query 3 retrieves information about sports teams and their head coaches, specifically listing the team's name, number of wins, number of losses, head coach's name, and salary. The data is sourced from two tables: team and coach. The tables are joined based on a common identifier (idTeam) to combine related information. The results are ordered by the coach's salary in descending order, meaning the highest-paid coaches will appear first.

<img width="467" alt="952x980 png 672cf1addad246bf91b6ee318d118c80" src="https://github.com/user-attachments/assets/a1e22a8d-6701-4324-a0bc-485837fb6fb5">

This query is valuable for managers as it allows them to assess team performance in relation to coach compensation. By comparing the number of wins and losses with the coach's salary, managers can evaluate the return on investment for each coach. This insight can guide decisions on coach retention, salary adjustments, or the recruitment of new coaching talent. Additionally, ordering the results by salary allows for easy identification of the highest-paid coaches, enabling more informed budget allocation and salary negotiations.
