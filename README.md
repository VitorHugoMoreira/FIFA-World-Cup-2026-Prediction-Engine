# FIFA World Cup 2026 Prediction Engine

## Overview

This project was developed to predict FIFA World Cup 2026 matches using Machine Learning, Elo Ratings and probabilistic modeling.

The engine estimates:

* Goals
* Shots
* Shots on Target (SOT)
* Match Result Probabilities
* Betting Markets
* Qualification Scenarios (future roadmap)

The objective is to build an end-to-end football analytics platform capable of generating realistic match forecasts and betting market probabilities.

---

## Project Architecture

```text
Historical Match Data
        │
        ▼
Feature Engineering
        │
        ▼
Machine Learning Models
        │
        ├── Goals Model
        ├── Shots Model
        └── SOT Model
        │
        ▼
Match Predictions
        │
        ▼
Poisson Probability Models
        │
        ▼
Betting Markets
```

---

## Features

### Team Form

* Goals Average (Last 3 and 5 Matches)
* Shots Average (Last 3 and 5 Matches)
* SOT Average (Last 3 and 5 Matches)

### Team Strength

* Historical Elo Rating
* Attack Strength
* Shot Strength

### Defensive Metrics

* Goals Conceded
* Shots Conceded
* SOT Conceded

### Matchup Features

* Elo Difference
* Opponent Strength
* Relative Attack Strength
* Relative Shot Strength

---

## Machine Learning Models

### Goals Model

Target:

* Goals Scored

Performance:

* MAE: 0.99
* RMSE: 1.33
* R²: 0.24

### Shots Model

Target:

* Total Shots

Performance:

* MAE: 4.11
* RMSE: 5.57
* R²: 0.47

### Shots on Target Model

Target:

* Shots on Target

Performance:

* MAE: 1.88
* RMSE: 2.50
* R²: 0.37

---

## Betting Markets Generated

### Match Odds

* Home Win
* Draw
* Away Win

### Double Chance

* 1X
* X2
* 12

### Goals Markets

* Over / Under Goals

### Shots Markets

* Over / Under Shots

### SOT Markets

* Over / Under Shots on Target

### Additional Markets

* BTTS (Both Teams To Score)
* Clean Sheet

---

## Technologies

* Python
* Pandas
* NumPy
* Scikit-Learn
* SciPy
* OpenPyXL

Future:

* FastAPI
* Power BI
* Monte Carlo Simulation

---

## Future Roadmap

* Dynamic Matchup Prediction
* Group Stage Simulation
* Knockout Stage Simulation
* World Cup Monte Carlo Engine
* Championship Probability Model
* Interactive Power BI Dashboard

---

## Author

Vitor Silva

Data Analytics | Business Intelligence | Data Engineering

Building end-to-end sports analytics and machine learning solutions.
