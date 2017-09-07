# 📝 Flask Realtime ToDo
Realtime CRUD Python application built with Flask, Vanilla JavaScript and Pusher.

To run locally:
- Clone/Download this repo - `git clone git@github.com:olayinkaos/flask-realtime-todo.git`
- [Optionally] Create a local virtualenv in the project folder (You must have virtualenv installed) - `virtualenv .venv`
- [Optionally] Activate virtual environment - `source .venv/bin/activate`
- Install all dependencies - `pip install -r requirements.txt`
- Replace the values of  `YOUR_APP_ID`, `YOUR_APP_KEY`, `YOUR_APP_SECRET`, `YOUR_APP_CLUSTER` with your Pusher credentials in `app.py` and `index.html`. These can be gotten from the [Pusher dashboard](https://dashboard.pusher.com/).
- Run app - `python app.py`
- Visit [localhost:5000](http://localhost:5000/) to view the app.
