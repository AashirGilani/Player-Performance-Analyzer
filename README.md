# Apex Analytics — Football Player Performance Analyzer

Apex Analytics is a web-based application that analyzes and predicts football player performance using advanced probability and statistics. Built for the Premier League 2024-25 season, it provides interactive dashboards, player profiles, head-to-head comparisons, and predictive analytics using statistical models like Poisson, Binomial, and Bayesian probability.

## Features

- **Dashboard:** Overview of all players, top scorers, assists, and ratings with interactive charts and tables.
- **Player Profile:** Deep statistical analysis of individual players, including probability-based insights.
- **Compare Players:** Head-to-head comparison using Bayesian probability analysis.
- **Performance Predictor:** Predicts future player performance using Poisson and Binomial distributions.
- **Modern UI:** Responsive and intuitive interface for seamless user experience.

## Technologies Used

- **Frontend:** HTML, CSS, JavaScript
- **Backend:** Python (Flask or similar)
- **Data:** CSV (players.csv)
- **Visualization:** Chart.js (or similar JS charting library)

## Project Structure

```
├── data_loader.py         # Loads and processes player data
├── server.py              # Backend server (API endpoints)
├── stats_engine.py        # Statistical analysis and prediction logic
├── index.html             # Main web interface
├── css/
│   └── style.css          # Stylesheet
├── js/
│   └── app.js             # Frontend logic
├── data/
│   └── players.csv        # Player data
```

## Getting Started

1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/apex-analytics.git
   cd apex-analytics
   ```
2. **Install Python dependencies:**
   ```bash
   pip install -r requirements.txt
   ```
3. **Run the backend server:**
   ```bash
   python server.py
   ```
4. **Open `index.html` in your browser** to use the app.

## Data Source

- The player data is stored in `data/players.csv`. You can update this file to add or modify player statistics.

## Authors

- Ibrahim
- Zain
- Aashir
- Sitara
- Abdullah

## License

This project is licensed under the MIT License.

---

### Project Description

Apex Analytics is a football analytics platform that leverages probability and statistics to provide deep insights and predictions for Premier League players. It features dashboards, player profiles, comparisons, and predictive tools, all in a modern web interface.
