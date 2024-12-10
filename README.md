Football Transfers Data Analysis
Project Overview
This project focuses on Exploratory Data Analysis (EDA) for a dataset of football transfers during the Summer 2022 season. The dataset includes information on players, their positions, transfer fees, origin and destination clubs, and more. The goal is to gain insights into the trends and patterns of football transfers, such as which leagues and teams spent the most money, which player positions are most in-demand, and how player ages are correlated with transfer costs.

Dataset Description
The dataset used in this analysis, Summer22_FootballTransfers.csv, contains the following columns:

name: Name of the player.
position: Position of the player on the field.
age: Age of the player at the time of transfer.
origin_club: Original club where the player transferred from.
league_origin_club: The league of the original club.
country_origin_club: Country of the original club.
new_club: The new club the player transferred to.
league_new_club: The league of the new club.
country_new_club: Country of the new club.
cost: Transfer cost in euros.
date_of_transfer: Date of the transfer.
Key Insights
Top 10 Most Expensive Player Transfers: We identified the top 10 most expensive player transfers, highlighting major players such as Erling Haaland and Romelu Lukaku, who had transfer fees exceeding €100M.

Most In-Demand Player Positions: By grouping the dataset by player position, we observed that Centre-Forwards and Centre-Backs are the most frequently purchased positions.

Age Analysis: The age distribution analysis shows that younger players, especially those in the age range of 21-23, tend to have higher transfer costs, with a peak at age 21.

Top Spending Clubs: The clubs that spent the most money in the 2022 Summer Transfer Window are:

Chelsea FC: €271M
FC Barcelona: €262M
Paris Saint-Germain: €251M
Top Spending Leagues: The Premier League led the spending with over €2.3B, followed by Serie A and La Liga.

Visualizations
The project features various visualizations, including:

Bar Plots: To display the most popular player positions and the most expensive player transfers.
Pie Charts: To represent the percentage of spending in different leagues and clubs.
Box Plots: To analyze outliers in player transfer costs and ages.
Correlation Heatmap: To identify relationships between various numerical columns such as player age and transfer cost.
Technologies Used
Python: Main programming language.
Pandas: For data manipulation and analysis.
Matplotlib & Seaborn: For creating visualizations.
NumPy: For numerical operations and handling large datasets.
How to Use
Clone the repository:
bash
Copy code
git clone https://github.com/your-username/football-transfers-analysis
cd football-transfers-analysis
Install the required dependencies:
bash
Copy code
pip install -r requirements.txt
Run the EDA:
bash
Copy code
jupyter notebook FootballTransfers_EDA.ipynb
This will open the Jupyter notebook where you can explore the analysis, visualizations, and insights.
Future Work
Player Performance Analysis: Integrating performance data for transferred players to assess whether the transfer fee matches their output.
Seasonal Analysis: Comparing transfer trends across different seasons to identify patterns in spending and player movements.
Transfer Predictions: Using machine learning to predict future transfers based on player and club data.
Results
This analysis provides a comprehensive view of football transfer data, offering insights into spending habits, player demographics, and the most lucrative positions in the football market.

