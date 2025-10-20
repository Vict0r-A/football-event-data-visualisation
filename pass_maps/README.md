# Football Pass Map – StatsBomb Open Data

This project analyses and visualises passing patterns from professional football matches using the public StatsBomb dataset.  
It produces a visual pass map showing where a team begins and ends its passes during a given match.
This project uses the `statsbombpy` library to access data of the UEFA Champions League final between Liverpool and Tottenham Hotspur in 2019, and creates pass maps of both the Liverpool team and Tottenham's throughout the game, respectively.

The notebook, accesses the open match event data. It then filters the pass events for each team, and then finally visualises all completed passes on a football pitch using `mplsoccer`.
The resulting pass map allows users to visualise and understand how teams build play, understand the style to which teams employ in passing the ball, and find the areas where passes are most often being made to/from.  
 
---


## Skills Demonstrated

### Data Acquisition and Cleaning
- Used the **StatsBomb API**  to fetch match evend data, using `statsbombpy`.
- Structured event-level data into a `pandas` DataFrame for analysis.
- Data manipulation ability shown in filtering the dataframe for pass events and extracting the relevant variables (`x`, `y`, `end_x`, `end_y`).
- Conversion of the pass events into arrays for use in scatter plots for visualisation on the pitch, demonstrates python proficiency.

### Data Manipulation
-  Showing `pandas` proficiency in manipulating the event data to extract passing data for visualisation 
 

### Data Visualisation
- `mplsoccer` and `matplotlib` were used to represent pass start and end locations and to visualise it.
 
### Technical Proficiency
- Confident use of Python syntax and best practices for importing, manipulating, and visualising data.
- Successfully incorporated multiple libraries (`statsbombpy`, `pandas`, `numpy`, `mplsoccer`, `matplotlib`).
- Comments throughout the code explaining functionality and logic throughout so other developers can understand.
- Created a `README.md` to document the functionality of the code and ensure its reproducibility.





---
## How to Run

1. Clone or download this repository.  
2. Install the required packages:

   ```bash
   pip install -r requirements.txt
