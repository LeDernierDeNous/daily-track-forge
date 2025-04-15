# 🛠️ DailyTrackForge

> Track your daily progress. Forge lasting routines.

**DailyTrackForge** is a web/cross-platform habit tracking and life organization tool. Designed with clarity and focus, it helps users build better habits through a gamified yet minimalist experience. Whether you're on desktop or mobile — or using our Discord bot companion — DailyTrackForge keeps you on track.

---

## ✨ Key Features (planned)

- 📅 **Daily Habit Tracking**  
  Track your recurring habits, goals, and tasks. Customize them by frequency, category, and priority.

- 🧠 **Gamified Progress System**  
  Turn personal growth into a quest:
  - 🎮 Gain **XP** (experience points) for completing habits
  - 🧱 Earn **Gold** or **Tokens** to unlock cosmetic themes or bonus features
  - 🎖️ Level up your profile and unlock **achievement badges**
  - 🏆 Track your **streaks** and milestones for long-term consistency

- 📈 **Progress Analytics & History**  
  Visualize your habit trends, success rates, and weekly/monthly progress over time.

- 🔔 **Custom Reminders & Notifications**  
  Set reminders per habit or routine — via email, mobile, or through the Discord bot.

- 🌐 **Web-Based & Responsive**  
  Built to work on all major platforms (desktop, tablet, mobile). No install required.

- 🤖 **Discord Bot Integration (optional)**  
  Track and log your habits directly from Discord. Get XP, reminders, and streak updates without leaving your server.

- ☁️ **Cloud Sync & Multi-Device Support**  
  All your data saved securely and synced across devices. Continue where you left off, anytime.

---

## 🚀 Tech Stack

- **Backend**: Python (FastAPI or Django)
- **Frontend**: TBD (likely SvelteKit, HTMX, or simple HTML/CSS for MVP)
- **Database**: PostgreSQL or SQLite (for local/dev use)
- **Auth & API**: JWT-based system
- **Bot Integration**: Discord.py

---

## 📦 Setup (WIP)

```bash
# Clone the repo
git clone https://github.com/ledernierdenous/daily-track-forge.git
cd daily-track-forge

# Set up virtual environment
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

# Install backend dependencies
pip install -r requirements.txt

# Run the backend server (dev)
uvicorn app.main:app --reload 
```

---

## 🧱 Project Structure (MVP)

```bash
daily-track-forge/
│
├── app/                # Backend application (FastAPI)
│   ├── models/         # ORM models
│   ├── routes/         # API endpoints
│   ├── services/       # Business logic
│   └── main.py         # App entry point
│
├── bot/                # Optional Discord bot
├── web/                # Frontend (TBD)
├── tests/              # Unit tests
├── requirements.txt
└── README.md
```

---

## 🧠 Project Goals

- Help users craft and maintain powerful routines
- Keep everything fast, lightweight, and distraction-free
- Build a foundation that can grow into a full-featured productivity suite
- Respect user privacy — open source, no tracking, no clutter

---

## 📜 License

MIT — free to use, modify, and contribute to.

### ✨ Track your day. Forge your way.
