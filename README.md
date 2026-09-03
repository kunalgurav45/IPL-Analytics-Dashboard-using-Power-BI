# IPL-Analytics-Dashboard-using-Power-BI

📌 Project Objective
The objective of this project is to create an interactive Power BI dashboard that provides insights into the performance of teams across IPL seasons from 2008 to 2025.
 📊 Business Requirements & Key Performance Indicators (KPIs)

A key business requirement is to enable users to *select any season* using a slicer/filter and instantly view the following metrics:

1. Primary KPI's
🏆 Winner Team: Displays the Winner Team of the selected season along with its dynamically rendered team logo.
🥈 Runner-Up Team: Displays the Runner-Up Team of the selected season along with its dynamically rendered team logo.

2. Secondary KPI's
 📈 Total Sixes: Total number of sixes hit in the selected season.
 📈 Total Fours: Total number of fours hit in the selected season.
🏏 Total Matches Played: Total matches conducted in that season.
 👥 Total Teams Participated: Number of teams that played in the selected season.
 💯 Total Centuries: Total number of centuries scored.
 fifty Total Half-Centuries: Total number of half-centuries scored.
📍 Total Venues Used: Number of different stadiums/venues utilized.


 🏅 Season Stat's (Individual Leaderboards)

When a specific season is filtered, the dashboard dynamically updates the player profiles and stats for the following categories:

 🟠 Orange Cap Stats:
   Orange Cap Holder Name
   Total Runs Scored in the season
   Team Name the player represented
   Player Image (dynamically rendered)

 🟣 Purple Cap Stats:
   Purple Cap Holder Name
   Total Wickets in the season
   Team Name the player represented
   Player Image (dynamically rendered)

 🟢 Total Fours in a Season:
   Player Name, Total Fours, Team Name, and Player Image.

 🔵 Total Sixes in a Season:
   Player Name, Total Sixes, Team Name, and Player Image.

 📋 Points Table Functionality

The dashboard includes a dynamic *Points Table* for each selected season displaying the following fields for each team:

 Logo: Dynamic team logo.
 Team Name: Official name of the IPL team.
 Matches Played (MPl/Pld): Total matches played by the team in the selected season.
 Won: Number of matches won.
 Lost: Number of matches lost.
 No Result (NR): Matches with no result (e.g., rain-affected).
 Tie: Matches that ended in a tie.
 Total Points: Calculated using standard IPL points rules: 
  $$\text{Total Points} = (\text{Wins} \times 2) + (\text{Ties} \times 1) + (\text{No Results} \times 1)$$

🛠️ Tech Stack Used
Business Intelligence Tool: Power BI Desktop
Data Transformation: Power Query
 Modeling & Calculations: DAX (Data Analysis Expressions)

 🔗 Screenshots / Demos
Show what the dashboard looks like.
Example:
