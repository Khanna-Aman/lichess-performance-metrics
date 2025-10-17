# Lichess Performance Metrics

Analyze Lichess rating performance across different hours of the day. Gain insights into when your chess performance peaks.

[![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)](https://python.org)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange.svg)](https://jupyter.org)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![Lichess](https://img.shields.io/badge/Lichess-API-brown.svg)](https://lichess.org/api)

## Description

A professional-grade Jupyter Notebook that provides comprehensive chess performance analysis for any Lichess player. Download all your games, analyze performance patterns, and discover insights to improve your chess.

## Features

- **Peak Performance Hours**: Discover when you play your best chess
- **Rating Patterns**: Analyze how your rating changes throughout the day
- **Opening Analysis**: Identify your most and least successful openings
- **Color Preferences**: Compare performance as White vs Black
- **Opponent Analysis**: Understand how you perform against different strength levels
- **Time Period Insights**: Morning vs Afternoon vs Evening vs Night performance
- **Interactive Visualizations**: 15+ professional charts and graphs
- **Complete Data Export**: 6 detailed CSV files for further analysis
- **User-Friendly Interface**: Clean widgets for username, time control, and timezone
- **Smart Validation**: Verifies username exists before downloading
- **Progress Tracking**: Real-time download progress with speed indicators
- **Multiple Time Controls**: Bullet, Blitz, Rapid, Classical support

## How to Run

### 1. Clone the Repository
```bash
git clone https://github.com/Khanna-Aman/lichess-performance-metrics.git
cd lichess-performance-metrics
```

### 2. Install Dependencies
```bash
pip install -r requirements.txt
```

### 3. Launch Jupyter Notebook
```bash
jupyter notebook lichess_performance_analysis.ipynb
```

### 4. Run the Analysis
1. Enter your details in the input widgets:
   - Lichess username (example: `khanna_aman`)
   - Time control (example: `bullet`)
   - Your timezone
2. Run each cell with `Shift+Enter`
3. Wait for download (progress will be shown)
4. Explore the results in interactive charts and CSV files

### Example Usage
```
Username: khanna_aman
Time Control: bullet
Timezone: UTC
```

The notebook will download all your games and generate:
- Interactive performance charts
- Hourly statistics analysis
- Opening performance breakdown
- Color preference analysis
- Opponent strength comparison
- 6 CSV files with detailed data

## Visualization

The notebook generates interactive visualizations including:
- Hourly performance heatmap
- Games distribution by hour
- Win rate throughout the day
- Performance by time period
- Top opening performance
- Color preference analysis
- Opponent strength breakdown

## Data Export

The analysis generates 6 CSV files:
1. `{username}_{timecontrol}_games.csv` - Raw game data
2. `{username}_{timecontrol}_hourly_stats.csv` - Hourly statistics
3. `{username}_{timecontrol}_time_periods.csv` - Time period analysis
4. `{username}_{timecontrol}_openings.csv` - Opening performance
5. `{username}_{timecontrol}_color_analysis.csv` - White vs Black
6. `{username}_{timecontrol}_opponent_strength.csv` - Opponent analysis

## Requirements

- Python 3.8+
- Jupyter Notebook
- Internet connection (for Lichess API)
- Valid Lichess username

## Technical Stack

- **Lichess API**: Official public API for game data
- **Pandas**: Data manipulation and analysis
- **NumPy**: Numerical computations
- **Plotly**: Interactive visualizations
- **Pytz**: Timezone handling

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.



