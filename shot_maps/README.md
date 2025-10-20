# Shot Map

This mini-project demonstrates how to create a football shot map (shot chart) for the UEFA Champions League final in 2019 between Liverpool and Tottenham Hotspur using the **StatsBomb Open Data** set. The notebook fetches the match event data, filters the shot events for both teams, and uses their locations to create a shot map, colour coded with red for the Liverpool attempts and white for Spurs', to visualise and distinguish what team made the shot, and their plot on their pitch correspods to where the shot was made in the match
This project aims to demonstrate basic proficiency in python, particularly in the data analysis realm.

---



## Skills Demonstrated

- **Data Retrieval and Handling:** Retrieval of StatsBomb API data using `statsbombpy` and `pandas`.  
- **Data Manipulation:** Via the `pandas` library, data manipulation skills shown, including the filtering of dataframes, extraction of particular data (shot data), conversion into arrays and then using the lists in scatter plots.
- **Data Visualisation:** Plotting shot attempts viaa `matplotlib` and `mplsoccer`, including colour coding to distinguish team shot attempts to enable comparison.  
- **Reproducible Code:** Comments throughout the code to explain code functionaity, showing the ability to write clean, maintainable code.  
- **Programming Proficiency** Proficiency in Python

--- 
# Project Structure

├── README.md
├── requirements.txt
└── shot_chart.ipynb




---
## Installation

```bash
# 1) Create and activate a virtual environment
python -m venv .venv
# Windows:
.venv\Scripts\activate
# macOS/Linux:
source .venv/bin/activate

# 2) Install dependencies
pip install -r requirements.txt
