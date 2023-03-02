# mm-2023
march madness 2023 bracket model

# Data
- Data has Men's and Women's, ~~do we think combining the data can skew the model?~~
- Section 1 - The Basics
    - team ids and names (MTeams and WTeams)
    - tournament seeds (MNCAATourneySeeds and WNCAATourneySeeds)
    - final scores of all reg season (MRegularSeasonCompactResults and WRegularSeasonCompactResults)
    - final scores of NCAATourney (MRegularSeasonCompactResults and WRegularSeasonCompactResults)
    - season level details (MSeason and WSeasons)
    - example submission for stage 1 (SampleSubmissionWarmup and SampleSubmission2023)
- Section 2 - Team Box Scores
    - regular season stats (MRegularSeasonDetailedResults and WRegularSeasonDetailedResults)
    - NCAATourney stats (MNCAATourneyDetailedResults and WNCAATourneyDetailedResults)
- Section 3 - Geography
- Section 4 - Public Rankings
- Section 5 - Supplements
    - coaches, conferences, team_conference, conf_tourney_games, secondary_tourney_teams, results, spellings, tourney slots, tourney_seed_round_slots

# Approach
Going with Team A and Team B approach and Win variable as the final one. Data given as WTeam and LTeam

# Evaluation
- Using Brier Score and not log-loss this time

# To-Do
- [x] look at the data lol (eda, how to arrange, etc...)
- [ ] 
- [ ] to
- [ ] write in front of it

- [ ] submit predictions in the [warmup competition](https://www.kaggle.com/competitions/warmup-round-march-machine-learning-mania-2023)
- [ ] submit predictions in the [main competition](https://www.kaggle.com/competitions/march-machine-learning-mania-2023/)
