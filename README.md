# 🧠 Knowledge Quest – Interactive Keyword Puzzle

An interactive word-search game designed around **Knowledge Representation concepts. Test your knowledge, find eight hidden keywords, beat the countdown timer, and compete on the leaderboard!**

## 🚀 Project Overview

Knowledge Quest is a browser-based educational puzzle developed using HTML, CSS, and JavaScript, with Supabase as the backend database.

The objective is to identify all eight hidden keywords within a limited time of 3 minutes.

## ✨ Features

- **8 Hidden Keywords:** Explore important Knowledge Representation concepts.
- **Interactive Puzzle Grid:** Select letters by moving horizontally or vertically.
- **Challenging Word Paths:** Words can follow different directions and winding paths.
- **Color-Coded Endpoints:** Matching start and end markers help identify each word's boundaries.
- **Countdown Timer:** Complete the puzzle within 180 seconds.
- **Completion Popup:** Receive a congratulatory message when all keywords are found.
- **Game Over Message:** Get notified when the timer expires.
- **Online Leaderboard:** Store and retrieve player results using Supabase.
- **Time-Based Ranking:** Players who finish with more time remaining rank higher.

## 🔑 Keywords Included

1. INTRODUCTION
2. APPROACHES
3. KNOWLEDGE
4. REPRESENTATION
5. SEMANTIC
6. NETWORK
7. FRAMES
8. THEORY

## 🛠️ Technologies Used

| Technology | Purpose                                 |
| ---------- | --------------------------------------- |
| HTML       | Game structure                          |
| CSS        | Styling and layout                      |
| JavaScript | Puzzle logic and interactions           |
| Supabase   | Backend and database                    |
| PostgreSQL | Leaderboard data storage                |
| REST API   | Communication between game and database |

## 🎮 How to Play

1. Open the game in your browser.
2. Enter your player name.
3. Start the game.
4. Find all eight hidden keywords by selecting adjacent letters.
5. Complete the puzzle before the 3-minute timer expires.
6. Check your completion status and leaderboard ranking.

## 🗄️ Supabase Integration

Supabase is used to store and retrieve leaderboard records.

The leaderboard stores:

- Player name
- Remaining time
- Number of words completed
- Total elapsed time
- Submission timestamp

### REST API Operations

- **POST:** Submit completed game results.
- **GET:** Retrieve leaderboard records.

Row Level Security (RLS) policies control access to the leaderboard table.

## 📊 Leaderboard Ranking

Players are ranked according to:

1. Higher remaining time gets a better rank.
2. If remaining times are equal, the player with lower elapsed time ranks higher.
3. Only players who complete all eight keywords qualify.

## 📂 Project Structure

```text
Knowledge-Representation-Puzzle/
│
├── index.html
├── README.md
├── app.py                 # Optional Streamlit launcher
└── requirements.txt       # Optional Streamlit dependency
```

## ▶️ Run Locally

### Using VS Code

1. Clone or download the repository.
2. Open the project folder in VS Code.
3. Open `index.html`.
4. Run it using the Live Server extension.

### Using Streamlit (Optional)

If using the Streamlit launcher:

```bash
pip install -r requirements.txt
streamlit run app.py
```

## 🌐 Deployment

The project can be hosted using:

- GitHub Pages for the standalone HTML application.
- Streamlit Community Cloud using a Python launcher.

Supabase provides the shared leaderboard database independently of the hosting platform.

## 🔮 Future Enhancements

- Multiple difficulty levels.
- More Knowledge Representation topics.
- Improved leaderboard analytics.
- Player performance statistics.
- Additional educational puzzle categories.

## 👩‍💻 Author

**M.Tech Data Science Student**

An educational project combining programming, database concepts, and Artificial Intelligence coursework.

---

⭐ If you find this project interesting, feel free to explore the repository and try the puzzle!
