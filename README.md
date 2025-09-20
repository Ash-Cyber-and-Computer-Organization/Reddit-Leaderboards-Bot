<!--- 12345678901234567890123 -->
# Reddit Leaderboard Bot

## Overview
The Reddit Leaderboard Bot is an automated script designed to post leaderboard rankings to multiple subreddit communities at scheduled times. The bot tracks top contributors and posts updates, enhancing engagement in Reddit communities.

## Features
- ✅ **Automated Leaderboard Posting** – Posts leaderboards to specified subreddits at optimal times.
- 🔄 **Multi-Subreddit Support** – Schedule leaderboard posts for different communities.
- ⏰ **Custom Scheduling** – Uses `schedule` to post at specific times.
- 🔒 **Secure Credentials Handling** – Uses `.env` file to store API credentials securely.
<!-- - 🌍 **Hosted on PythonAnywhere** – Runs 24/7 in a virtual environment with scheduled execution.-->

## Project Structure
```
RedditBot/
│── Credentials.env             # Stores Reddit API credentials
│── Post_RedditLeaderboard.py   # Schedules and posts leaderboards
│── RedditLeaderboards.py       # Handles API authentication and leaderboard posting logic
│── requirements.txt            # Dependencies for the bot
│── venv/                       # Virtual environment (local execution)
```

## Installation & Setup
### 1. Clone the Repository
```bash
git clone https://github.com/YOUR_ORG/RedditBot.git
cd RedditBot
```

### 2. Create & Activate Virtual Environment
```bash
python3 -m venv venv
source venv/bin/activate  # On Linux/macOS
venv\Scripts\activate     # On Windows
```

### 3. Install Dependencies
```bash
pip install -r requirements.txt
```

### 4. Configure Reddit API Credentials
Create a `.env` file in the `RedditBot` directory and add:
```
REDDIT_CLIENT_ID=your_client_id
REDDIT_CLIENT_SECRET=your_client_secret
REDDIT_USERNAME=your_username
REDDIT_PASSWORD=your_password
REDDIT_USER_AGENT=your_user_agent
```
<!--
### 5. Run the Bot Locally
```bash
python Post_RedditLeaderboard.py
```

## Deployment on PythonAnywhere
1. Upload files to PythonAnywhere.
2. Set up a virtual environment and install dependencies.
3. Use `nohup` to keep the bot running:
   ```bash
   nohup python Post_RedditLeaderboard.py > bot.log 2>&1 &
   ```
4. Alternatively, add a **Scheduled Task** on PythonAnywhere.
-->
## Contribution
We welcome contributions! Feel free to open issues or submit pull requests to improve the bot.

## License
MIT License. See `LICENSE` for details.

