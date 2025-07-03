# Touring Poker Agent
## Background

TuringPoker was developed during a 24-hour hackathon competition at McGill University. Teams were challenged to build autonomous Texas Hold'em poker bots that would compete against each other in live matches every 2 hours. The competition initially required bots to play at 6-player tables, but midway through, the format was switched to heads-up (2-player) matches. Our team quickly adapted our logic and strategies to excel in the new format.

Throughout the event, we continuously improved our bot by analyzing the strategies of other teams, reverse engineering their approaches, and dynamically updating our own logic. We leveraged Game Theory Optimal (GTO) charts and the Kelly Criterion to inform our betting strategies and maximize our winning probability. This project demonstrates not only technical skill in AI and game theory, but also adaptability and teamwork under pressure.

## GUI-based Environment: https://ff1a4817.my-app-22r.pages.dev/games/
## How to Connect to a Bot:
1. Run `git clone https://github.com/Turing-Games/template-python-poker-bot.git`
2. Run `git checkout mcgill-tournament`
3. Run `pip install -r requirements.txt`
4. Run `python3 main.py --host ws.turingpoker.com --port 80 --room 123456 --username your_username`

## To control the response time of the bot:
1. Find `act` fuction inside the Templatebot class under `main.py` file
2. Play around the numbers inside `sleep(0.1)`
