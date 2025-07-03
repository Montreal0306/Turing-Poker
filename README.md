# Touring Poker Agent
## GUI-based Environment: https://ff1a4817.my-app-22r.pages.dev/games/
## How to Connect to a Bot:
1. Run `git clone https://github.com/Turing-Games/template-python-poker-bot.git`
2. Run `git checkout mcgill-tournament`
3. Run `pip install -r requirements.txt`
4. Run `python3 main.py --host ws.turingpoker.com --port 80 --room 123456 --username your_username`

## To control the response time of the bot:
1. Find `act` fuction inside the Templatebot class under `main.py` file
2. Play around the numbers inside `sleep(0.1)`
