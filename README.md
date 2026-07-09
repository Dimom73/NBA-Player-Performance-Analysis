# NBA Player Performance Analysis

Python data analysis project focused on NBA player performance statistics.

The project analyzes player scoring performance and explores how points scored are related to playing time, efficiency, assists, rebounds and shooting percentage.

This project was completed as part of a Data Analyst course assignment and then cleaned for public GitHub portfolio use. The original course assignment is not included in this repository.

## Project Objective

The main goal of this analysis is to understand which factors are most strongly associated with player scoring performance.

The analysis focuses on these questions:

- How are points distributed across NBA players?
- Do players who play more minutes usually score more points?
- Which players have the highest total points?
- Are there outliers in scoring performance?
- Which performance metrics are most correlated with points?
- Does grouped playing time confirm the relationship between minutes and scoring?

## Dataset

The dataset contains NBA player statistics, where each row represents one player.

Key columns used in the analysis:

- `PLAYER` — player name
- `PTS` — total points scored
- `MIN` — total minutes played
- `FG_PCT` — field goal percentage
- `AST` — assists
- `REB` — rebounds
- `EFF` — efficiency rating

## Analysis Process

The notebook follows a structured data analysis workflow:

1. Import Python libraries.
2. Load the dataset into a pandas DataFrame.
3. Explore the structure of the dataset.
4. Check data quality and missing values.
5. Perform descriptive statistical analysis.
6. Create visualizations to identify patterns and relationships.
7. Analyze correlations between player performance metrics.
8. Group players by minutes played and compare average points.
9. Summarize findings and conclusions.

## Visualizations Included

- Histogram of points distribution
- Scatter plot of minutes vs points
- Top 10 players by points bar chart
- Boxplot for points and outlier detection
- Correlation heatmap
- Line chart of points vs minutes
- Average points by minutes group bar chart

## Key Findings

- Player scoring is unevenly distributed: most players score relatively low total points, while a smaller group of players score much higher totals.
- Minutes played have a strong positive relationship with points scored.
- Efficiency is also strongly related to scoring performance.
- Top players show clear separation from the rest of the dataset.
- Grouping players by minutes played confirms that higher playing time is associated with higher average scoring.

## Tools & Technologies

- Python
- pandas
- Matplotlib
- Seaborn
- Jupyter Notebook

## Repository Structure

```text
NBA-Player-Performance-Analysis/
├── README.md
├── data/
│   └── nba_player_stats_2026.csv
├── docs/
│   └── code_review.md
├── notebooks/
│   └── nba_player_performance_analysis.ipynb
└── requirements.txt
```

## How to Run

1. Clone this repository.
2. Install dependencies:

```bash
pip install -r requirements.txt
```

3. Open the notebook:

```bash
jupyter notebook notebooks/nba_player_performance_analysis.ipynb
```

4. Run the notebook cells from top to bottom.

## Notes

The original notebook was cleaned and reorganized for portfolio presentation. The project keeps the same analysis topic and core analytical workflow, while improving structure, wording, documentation and data-handling clarity.

## Project Status

Completed and cleaned for public portfolio use.
