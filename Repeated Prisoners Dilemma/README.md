# Introduction
A three-player prisoners' dilemma game is more complex than the 2 player version, with 8 possible combinations of payoffs. 
<br><br> <img width="574" height="246" alt="image" src="https://github.com/user-attachments/assets/1f4f6a23-b7e6-4852-b250-ca6afa94f6af" />
<br> The agent is placed in a simulation where the game is played repeatedly, and has a goal of achieving the best score while competing with other players.


# Overview:
Each game consists of approximately 100 rounds, and the score of that game is the average payoff from each round of that game. 
<br> The player's score is calculated as per the equation shown, with $$r_{j}$$ as the player's payoff in round j.
<br><br> <img width="160" height="78" alt="image" src="https://github.com/user-attachments/assets/7d138631-3a67-4f8c-b6ae-e93d927e2c4c" />
<br> The agent will be competing with other students' agents, as well as agents that use known strategies such as Tit for Tat. As such, not all strategies of other players are known.

## Methodology
Various strategies like Bayesian modeling, Q-learning, and rule-based modeling are explored.


# Results:
- Evaluation against agents with known strategies was conducted.
- The agent places within the top 2 most of the time, and places 3rd or 4th occasionally.
