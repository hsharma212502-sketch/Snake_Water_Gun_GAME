📖 Overview
Snake Water Gun is a Python-based terminal game where you face off against a randomized computer opponent across multiple rounds. Built with clean logic, real-time score tracking, and a smooth CLI experience — it's simple on the surface but surprisingly strategic underneath.
The rules are straightforward:<br>

🐍 Snake drinks Water → Snake wins<br>
💧 Water douses Gun → Water wins <br>
🔫 Gun shoots Snake → Gun wins<br>
✨ Features<br>
⚡ Instant Gameplay — No setup friction. Run and play in seconds<br>
⚡ Instant Gameplay — No setup friction. Run and play in seconds<br>
🤖 Randomized AI Opponent — Unpredictable computer moves powered by Python's random module <br>
📊 Live Score Tracking — Win, loss, and draw counts updated after every round  <br>
🔁 Multi-Round Support — Play as many rounds as you want in a single session  <br>
🎯 Input Validation — Handles invalid inputs gracefully without crashing  <br>
🧼 Clean Output — Formatted results and round summaries for a polished experience <br>
🏆 End-of-Game Summary — Final scoreboard and winner declaration at session end  <br>


⚙️ Installation & Setup  <br>
Prerequisites  <br>
Ensure you have Python installed:  <br>
bashpython --version  # Requires Python 3.7+  <br>
Clone the Repository  <br>
bashgit clone https://github.com/yourusername/snake-water-gun.git<br>
cd snake-water-gun  <br>
No Dependencies Required <br>
This project uses only Python's standard library — no pip installs needed. <br>
Run the Game<br>
bashpython snake_water_gun.py <br>

🎮 How to Play  <br>
Once the game launches, follow the on-screen prompts: <br>
Welcome to Snake Water Gun!  <br>
----------------------------  <br>
Enter your choice: <br>
  [s] Snake  <br>
  [w] Water  <br>
  [g] Gun    <br>
  [q] Quit    <br>

Your choice: _  <br>
Step-by-step:  <br>

Launch the game using the command above  <br>
Enter s, w, or g to make your move  <br>
The computer instantly generates its move  <br>
The round result is displayed along with the updated score  <br>
Keep playing or enter q to quit and view your final stats  <br>

Example Round:  <br>
You chose    : 🐍 Snake  <br>
Computer chose: 💧 Water  <br>
Result       : ✅ You Win! Snake drinks Water.  <br>

Score → You: 3 | Computer: 1 | Draws: 1  <br>

📁 Project Structure  <br>
snake-water-gun/  <br>
│
├── snake_water_gun.py   # Main game logic  <br>
└── README.md            # Project documentation  <br>
