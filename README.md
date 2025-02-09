# SQL-Analysis-Project-Sky-Sports-Football-Digest
Sky Sports Channel's coverage of the FIFA World Cup includes a post-match TV program called "Football Digest: Post Match Analysis". The
Football Pundits on the show discusses about the insights and game play as per their expertise and insights derived by the Sports Analyst at the backend. The Sports Analyst is responsible for analyzing data from each match to provide detailed statistics on the program related to the FIFA World Cup in Qatar and hand it over to the presenter and pundits of the "Football Digest: Post Match Analysis".
To carry out this task, the Sports Analyst uses MySQL to access two tables of data: one containing information on each team's performance in each game, and another containing data on individual team statistics. Both the tables gets updated with each match at Fifa World Cup. The analyst uses this data to provide insights into each match, highlighting key moments, performances, and tactical decisions made by the coaches. These insights are presented on the program, giving viewers a deeper understanding of each match's events and the factors that contributed to a team's success or failure.
Overall, the Sports Analyst's role at Sky Sports Channel is essential to providing viewers with a comprehensive analysis of each match. By using MySQL to analyze data on team and player performance, the analyst will deliver valuable insights that will help viewers understand the
intricacies of the game and the factors that can make or break a team's success at the FIFA World Cup.
In our case study, we have two tables, group_stage_team_stats and overall_wc_stats that are being used by the Sports Analyst at Sky Sports Channel to provide detailed statistics and insights on the FIFA World Cup matches. The first table, group_stage_team_stats, which contains information on each team's performance in each game, has columns such as team name, game date, goals scored, goals conceded, shots on target, shots off target, possession, and many more. The second table, overall_wc_stats , which contains overall statistics of each team at the current FIFA World Cup, has columns such as player name, position, number of appearances, goals scored, assists, yellow and red cards, and other relevant information. With both tables being updated after each match, the analyst is able to extract valuable insights into the game, highlighting key moments, performances, and tactical decisions made by the coaches. Both the tables contain a column team, which is common and can be used for joining.

Questions:
1. Import both the .CSV files in Dbeaver under the database name Sky_Sports
2. Write an sql query to show all the UNIQUE team names
3. Write an SQL query to show name of team which has rank 1 from group 7
4. Write an sql query to show count of all teams
5. Write an SQL query to show matches_played by each team
6. Write an SQL query to show team, percent of wins with respect to matches_played by each team and name the resulting column as wins_percent
7. Write an SQL query to show which team has maximum goals_scored and their count
8. Write an SQL query to show percent of draws with respect to matches_played round of to 2 digits by each team
9. Write an SQL query to show which team has minimum goals_scored and their count
10. Write an SQL query to show percent of losses with respect to matches_played by each team in ascending order by losses and name the resulting column as losses_percent
11. Write an SQL query to show the average goal_difference
12. Write an SQL query to show name of the team where points are 0
13. Write a SQL query to show all data where expected_goal_scored is less than exp_goal_conceded
14. Write an SQL query to show data where exp_goal_difference is in between -0.5 and 0.5
15. Write an SQL query to show all data in ascending order by exp_goal_difference_per_90
16. Write an SQL query to show team which has maximum number of players_used
17. Write an SQL query to show each team name and avg_age in ascending order by avg_age
18. Write an sql query to show average possession of teams
19. Write a SQL query to show team which has played atleast 5 games
20. Write an SQL query to show all data for which minutes is greater than 600
21. Write an SQL query to show team, goals, assists in ascending order by goals
22. Write an SQL query to show team, pens_made, pens_att in descending order by pens_made
23. Write an SQL query to show team, cards_yellow, cards_red where cards_red is equal to 1 in ascending order by cards_yellow
24. Write an SQL query to show team, goals_per90, assists_per90, goals_assists_per90 in descending order by goals_assists_per90
25. Write an SQL query to show team, goals_pens_per90, goals_assists_pens_per90 in ascending order by goals_assists_pens_per90
26. 26. Write an SQL query to show team, shots, shots_on_target, shots_on_target_pct where shots_on_target_pct is less than 30 in ascending order by shots_on_target_pct
27. Write an SQL query to show team, shots_per90, shots_on_target_per90 for team Belgium
28. Write an SQL query to show team, goals_per_shot, goals_per_shot_on_target, average_shot_distance in descending order by average_shot_distance
29. Write an SQL query to show team, errors, touches for which errors is 0 and touches is less than 1500
30. Write an SQL query to show team, fouls which has maximum number of fouls
31. Write an SQL query to show team, offisdes which has offsides less than 10 or greater than 20
32. Write an SQL query to show team, aerials_won, aerials_lost, aerials_won_pct in descending order by aerials_won_pct
33. Write an SQL query to show number of teams each group has!
34. Write a SQL query to show team names group 6 has
35. Write an SQL query to show Australia belongs to which group
36. Write an SQL query to show group, average wins by each group
37. Write an SQL query to show group, maximum expected_goal_scored by each group in ascending order by expected_goal_scored
38. Write an SQL query to show group, minimum exp_goal_conceded by each group in descending order by exp_goal_conceded
39. Write an SQL query to show group, average exp_goal_difference_per_90 for each group in ascending order by exp_goal_difference_per_90
40. Write an SQL query to show which team has equal number of goals_scored and goals_against
41. 41. Write an SQL query to show which team has maximum players_used
42. Write an SQL query to show team, players_used, avg_age, games, minutes where minutes lessthan 500 and greater than 200
43. Write an SQL query to show all data of group_stats in ascending order BY points
44. Write an SQL query to show ALL UNIQUE team in ascending order by team
45. Write an SQL query to show average avg_age of each group and arrange it in descending order by avg_age.
46. Write an SQL query to show sum of fouls for each group and arrange it in ascending order by fouls.
47. Write an SQL query to show total number of games for each group and arrange it in descending order by games.
48. Write an SQL query to show total number of players_used for each group and arrange it in ascending order by players_used.
49. Write an SQL query to show total number of offsides for each group and arrange it in ascending order by offsides.
50. Write an SQL query to show average passes_pct for each group and arrange it in descending order by passes_pct.
51. Write an SQL query to show average goals_per90 for each group and arrange it in ascending order by goals_per90.

This educational case study material is purely fictional and does not represent any actual companies or data. Any resemblance to real entities is coincidental, and it is intended solely for educational purposes.
