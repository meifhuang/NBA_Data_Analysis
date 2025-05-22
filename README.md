# 🏀 NBA_Data_Analysis

This project explores Jalen Brunson's performance during the 2024-2025 NBA Regular Season season using the `jalen_brunson.csv` dataset. This dataset includes Jalen Brunson's game-by-game stats for the 2024-2025 Regular Season. 

## Data Dictionary

Column descriptions for the dataset is listed below:

* Rk - Rank
* Gcar - Career game number for player
* Gtm - Season game number for team
* GS - Games started
* MP - Minutes Played
* FG - Field goals (shots made from anywhere on the court that results in points)
* FGA - Field goal attempts
* FG% - Field goal percentage
* 3P - 3 point field goals
* 3PA - 3 point field goal attempts
* 2P - 2 point field goals
* 2PA - 2 point field goal attempts
* 2P% - 2 point field goal percentage
* eFG% - effective field goal percentage
* FT - free throws
* FTA - free throws attempts
* FT% - free throw percentage
* ORB - offensive rebounds
* DRB - defensive rebounds
* TRB - total rebounds 
* AST - assists 
* STL - steals
* BLK - blocks
* TOV - turnovers
* PF - personal fouls
* PTS - points 
* GmSc - Game score (rough estimate of a player's contribution)
* +/- - Plus-minus (Team Points Scored While Player is On The Court) – (Team Points Allowed While Player is On The Court)

## Overview

There are five Jupyter notebooks, each exploring a different question about Jalen Brunson's 2024-2025 regular season performance. Each notebook features:
- data cleaning
- exploratory data analysis 
- visualizations
- key takeaways and findings based on metrics

### Notebooks

#### Chaya_eda.ipynb 

Is there a relationship between Brunson’s play time (rounded down to minutes) and the Knicks winning?
Yes, there is a thinly dispersed negative correlation relationship between Brunson's play time (minutes) and the Knicks winning. The more minutes he plays, the more likely the Knicks are to lose and the less he plays, he is likely to win. This is evident from the data and graph correlation which shows that when Brunson plays more minutes, the Knicks tend to win and lose at the different time frequency. For example, the minutes and mean is slightly 1.76 precentage away from three distribution making it a slightly normal bell curve. There is correlation that shows one variable increases and the other variable decreases lightly. It is not constant for losing and winning for minutes in games. For example, for loses is 2 minutes apart from the winning stream making the variable 24 to 22.

#### Chidi_eda.ipynb 

How have Brunson’s scoring trends evolved throughout the 2024-2025 regular season?
 Answer: For the 2024-25 NBA season, my visualization shows that Jalen Brunson's points scored remained consistent throughout the season, with an average of 26 points per game, with the highest points made in a game being 44 points total. The visualization does show a sharp decrease in points made, which coincides with an injury Jalen sustained in March, which made him sit out for a while in order to heal. I can infer from the data that due to the average points made per game, Jalen maintains a consistent level of performance and effort, which shows he is a player that can be relied upon to deliver for his team.

#### Jaron_eda.ipynb 

Which offensive stat has the highest positive correlation on Jalen Brunson's +/- ; Pts, 2p, 3p or Ast? - Jaron
I set out to find out what offensive stat most effected Jalen Brunson's +/-; assists, points, two point shots made or three point shots made. I calculated Pearson's r for each stat and they were .2 for assists which is a low correlation, -.06 for points which is no correlation, -.22 for two pointers which is low, and .3 for three pointers which is a medium correlation.
The strongest relationship with +/- was 3 pointers which is kind of surprising. Brunson is a %38 3 point shooter which is good but not great, in comparison with his 2 point makes, which have a negative correlation and Brunson shoots %54 there. Obviously threes are worth more than twos but it's still surprising.
My recommendation for Jalen is to shoot more 3 point shots in general and shoot more 2 point shots when he plays the sixers(my team!).

#### Manuel_eda.ipynb
Does Brunson perform better at home or on the road?
Based on the game-by-game data from Jalen Brunson’s 2024–2025 NBA season, the analysis shows that Brunson performs better in home games compared to road games. When the average of key performance stats showed, the results was that it showed higher numbers during home games in every category such as points, assists, and rebounds compared to when he played away games. This generally means that Brunson is a more efficient player when he has home court advantage than when he is away.

#### Mei_eda.ipynb 

s there a relationship between Brunson’s performance (field goal, field goal%, game score) and the outcome of the game?
Field Goals
The average of Brunson's field goals made is 9.2 in losses and a 8.875 in wins. This suggests that the number of field goals Brunson makes doesn't necessarily correlate with the Knicks winning. The box plot grouped by game outcome shows that the interquartile range for wins is wider (6-12) compared to losses (8 - 10) which may indicate that the Knicks are able to win even when Brunson makes fewer field goals.
Field Goal %
The average of Brunson's field goal percent is a 48.9% in wins and a 47.4% in losses. This suggests that Brunson's shooting efficiency doesn't strongly correlate with the Knicks winning. The box plot grouped by game outcome shows there is a wider spread in wins (37% - 58%) compared to losses (39% - 53%) in the field goal percentage which may indicate that the Knicks are able to win even when Brunson is missing his shots.
Game Score:
The average of Brunson's game score is a 21 in wins compared to 18 in losses. This suggests that Brunson's overall estimated contribution is generally higher in the games where the Knicks win. The interquartile range for wins (13.3-28) is also slightly higher than for losses (12.3-22.9) which may indicate that when he performs well overall, the Knicks tend to win.
Although Brunson's shooting performance doesn't show a strong correlation with winning, his overall performance (game score) which includes other stats like assists, rebounds, steals etc. tends to be higher in the games where the Knicks win. The Knicks can win even when he's less consistent in scoring but may still rely on his overall performance.