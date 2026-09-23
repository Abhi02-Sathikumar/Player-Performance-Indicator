# ⚽ Player Performance Indicator

An advanced football analytics web application designed to explore deep player profiles, perform head-to-head comparisons, find ideal player replacements, and leverage AI-powered performance prediction models.

---

## 🌟 Features

- **Dashboard Overview:** Get a high-level summary of tournament statistics (such as total players tracked, player records, goals scored, and seasons covered).
- **Player Profile (`/description`):** Deep dive into individual player statistics and performance metrics across different World Cup seasons.
- **Head-to-Head Comparison (`/comparison`):** Compare two players side-by-side to analyze their strengths, weaknesses, and key metrics.
- **Player Replacements (`/replacement`):** Find similar players or potential tactical replacements based on statistical profiles.
- **AI Predictor (`/predict`):** Utilize machine learning-powered predictions to forecast player performance indicators.

---

## 📊 Dataset Insights
- **Data Source:** StatsBomb Open Data
- **Players Tracked:** 1,178+
- **World Cup Seasons:** 7
- **Player Records:** 1,361+
- **Total Goals Recorded:** 430+

---

## 🛠️ Tech Stack

- **Frontend / UI:** HTML5, CSS3, JavaScript, Chart.js (for interactive analytics charts)
- **Backend:** Python (Flask )
- **Hosting / Deployment:** [Render](https://render.com)

---

## 🚀 Getting Started Locally

Follow these steps to set up and run the project on your local machine:

### 1. Clone the Repository
```bash
git clone [https://github.com/your-username/player-performance-indicator.git](https://github.com/your-username/player-performance-indicator.git)
cd player-performance-indicator

```

### 2. Create a Virtual Environment & Activate It

```bash
python -m venv venv
# On Windows:
venv\Scripts\activate
# On macOS/Linux:
source venv/bin/activate

```

### 3. Install Dependencies

```bash
pip install -r requirements.txt

```

### 4. Run the Application

```bash
python app.py  # or uwsgi / flask run depending on your setup

```

Open your browser and navigate to `http://127.0.0.1:5000` to view the app.

---

## 🌐 Live Demo

Check out the live application hosted on Render:

🔗 [https://player-performance-indicator.onrender.com/](https://player-performance-indicator.onrender.com/?utm_source=gemini)

---

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the [issues page](https://www.google.com/search?q=../../issues&utm_source=gemini).

---

## 📂 Project Structure

Based on your project workspace, here is how the files and directories are organized:

```text
Football_Player_Performance/
│
├── static/
│   ├── fifa_world_cup.glb      # 3D asset for UI / WebGL
│   ├── loading.mp4             # Loading animation video
│   └── style.css               # Custom styles for the app
│
├── templates/
│   └── index.html              # Main frontend HTML template
│
├── venv/                       # Python virtual environment
├── app.py                      # Main Flask application
├── fifa_world_cup.glb          # Root 3D asset reference
├── knn_position_bundle.pkl     # Trained KNN model for player replacement/positioning
├── loading.mp4                 # Video asset fallback
├── position_classifier.pkl     # Machine learning model for player positions
├── requirements.txt            # Python package dependencies
├── world_cup_player_stats.csv  # Dataset containing World Cup player statistics
└── xg_model_bundle.pkl         # Expected Goals (xG) prediction model bundle
```

---

## 📝 License

This project is open-source and available under the [MIT License]
