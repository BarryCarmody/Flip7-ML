# Flip7-ML

*Project Ongoing*

## Objective
Implement the card game [Flip 7](https://cdn.shopify.com/s/files/1/0611/3958/3198/files/25_FLIP_7_TB_RULES_C_ND_1.pdf?v=1734983801) using OOP. 
Design a gymnasium environment to train agents to play the game.

## Agents

### v0 - Completed (08/06/2025)
Agent v0 is a basic model to test initial set up of the environment. 

- Only plays one hand, seeking to maximise the score of the one hand
- Only base number cards (0 - 12) are used 
- Only one opponent
- Opponent takes random actions
- Reward is not impacted by opponent actions
- No limitations on hand size

| Model | Random Choice | v0 |
|---|---|---|
| Reward Mean | 11.62 | 18.21 |
| Reward Std | 8.94 | 13.98 |
| Reward Max | 72 | 49 |
| Reward Median | 10 | 25 |
| Zero Reward Hands | 13.94% | 35.55% |
| Episode Length Mean | 2.73 | 3.96 |
| Episode Length Std | 1.01 | 1.09 |
| Episode Length Max | 11 | 9 |
| Episode Length Median | 2 | 4 |
