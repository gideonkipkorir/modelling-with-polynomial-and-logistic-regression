
## Problem statement(still a work in progress)
Create a model that predicts results of a game between team 1 and team 2, based on who's home and who's away, and on whether or not the game is friendly (include rank in your training).

## possible approaches 

Input: Home team, Away team, Tournament type (World cup, Friendly, Other)

#### Approach 1: Polynomial approach

What to train given:

Rank of home team
Rank of away team
Tournament type
**Model 1:** Predict how many goals the home team scores.

**Model 2:** Predict how many goals the away team scores.

### Approach 2: Logistic approach

**Feature Engineering:**
Figure out from the home team’s perspective if the game is a Win, Lose or Draw (W, L, D)
