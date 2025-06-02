# NBA Data Analysis - 2023 Season 🏀

This repository contains a series of Python functions, developed and executed using Google Colab, that allow for detailed analysis of player performance statistics from the 2023 NBA season. The analysis is based on a `.csv` file that includes key data such as points, assists, rebounds, age, minutes played, three-pointers made, and other individual and team indicators.

## 📌 Technologies & Tools Used

- **Language:** Python  
- **Environment:** Google Colab (Jupyter Notebook)  
- **Libraries:**  
  - `pandas` for data manipulation  
  - `plotly` for interactive visualizations  
  - `matplotlib` for basic bar charts  
- **Data Source:** CSV file with player statistics from the 2023 NBA season

## 🔍 Main Features

The project includes interactive and visual functions to answer key questions in sports data analysis:

### 📊 Individual Player Analysis

- **Top 5 Triple-Double Leaders:** players with the most games recording 10+ in points, assists, and rebounds  
- **Top 5 Double-Double Leaders:** players with 10+ in any two of the three core stats  
- **Search by Player Name:** displays age, team, points, and minutes played  
- **Highest Scoring Player:** identifies the top scorer of the season  
- **Player with Fewest Minutes Played:** useful for bench or underused players  
- **Best Defender:** based on the sum of successful steals and blocks  
- **Worst Impact Player:** based on net point differential (points scored vs allowed while on court)

### 🏀 Team-Based Analysis

- **Team Comparison:** total points, assists, and rebounds between any two selected teams  
- **Team MVP:** player with the most points from a selected team  
- **Youngest & Oldest Players on a Team**  
- **Average Team Age:** shown via a bar chart

### 📈 Visualizations

- **Top 10 Three-Point Shooters:** bar chart using Plotly  
- **Average Age by Team:** basic bar chart using Matplotlib

## 📁 Project Structure
```
├── 2023_nba_player_stats.csv   # Dataset with player statistics
├── nba_analysis.ipynb          # Main notebook with all implemented functions
└── README.md                   # This file
```
### 💡 Additional Notes
- Several functions are interactive: they prompt the user for input (e.g., player or team names)
- Data must be cleaned and well-structured for all functions to work correctly
- Visualizations help highlight trends and insights clearly and effectively


### 🤝 Credits
Project developed as part of the Data Analysis course (2023) with the help of Anthony Li, Didier Miranda, Gabriel Chavarría, myself, Gabriel Jiménez.

