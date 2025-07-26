# KnowAboutCricket

An **interactive command‑line quiz** about cricket trivia and general knowledge. Test your insights — get points for correct answers and see how much you really know!

## 🧠 Project Overview

- A CLI (command‑line interface) trivia game focused on cricket.
- Users answer ~5 cricket-related questions.
- Score system: **+1** for correct answers, **–1** for incorrect ones.

## 🚀 Motivation

Developed for cricket enthusiasts to learn and engage with sport trivia in a fun, accessible format while showcasing Python scripting or scripting logic.

## 🧩 Features

- Multiple-choice or direct-input questions about:
  - Cricket formats (Test, ODI, T20)
  - Player stats and records
  - Match history and tournaments
- Simple scoring system
- Replayable – try again to beat your score

## 📁 Project Structure

/
├── README.md
├── main.py (or game.py)
├── questions.json (if using a data file)
├── utils.py (optional helper functions)
└── requirements.txt (if any)

nginx
Copy
Edit

Adjust paths based on your actual file placement.

## 💻 Installation & Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/code-with-shahid/KnowAboutCricket-main.git
Navigate into the project folder:

bash
Copy
Edit
cd KnowAboutCricket-main
(Optional) Create and activate a virtual environment:

bash
Copy
Edit
python3 -m venv venv
source venv/bin/activate  # or venv\Scripts\activate on Windows
Install dependencies (if required):

bash
Copy
Edit
pip install -r requirements.txt
🎮 Usage
To play the quiz:

bash
Copy
Edit
python main.py
You’ll be prompted with cricket questions:

Type your answer and press Enter.

The script will give feedback and update your score.

At the end, your total score is displayed.

🛠️ How It Works
The game fetches questions from either hard-coded lists or a JSON file.

User input is validated and compared for correctness.

Scoring is cumulative and final score is shown after all rounds.

🧪 Contribution
Contributions are welcome!

Submit new questions or quizzes.

Improve input validation, feedback, or UI.

Add categories (e.g. IPL, World Cups) or difficulty levels.

How to contribute:

Fork the repository

Create a feature branch: git checkout -b add-new-questions

Commit changes & push: git push origin add-new-questions

Open a Pull Request

📄 License
Distributed under the MIT License — see LICENSE.md for details.

📞 Contact
Maintained by Shahid Afridi
For feedback or issues, please create an issue in this repository.
