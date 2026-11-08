# ChatApp

A web application for chatting in rooms, built with Python, Flask, Flask-SocketIO, and JavaScript. Users can create rooms, join them using a room code, and exchange messages in real time.

## Features

- Create a room with a unique four-letter code.
- Join an existing room using its code.
- Real-time messaging and notifications when participants join or leave.
- Interface built with Flask templates, HTML, CSS, and JavaScript.

## Technologies

- Python
- Flask
- Flask-SocketIO
- JavaScript, HTML, and CSS

## Getting started

1. Clone the repository and navigate to the project directory.
2. Optionally, create and activate a virtual environment.
3. Install the dependencies:

       python -m pip install Flask Flask-SocketIO

4. Start the application:

       python main.py

5. Open `http://127.0.0.1:5000` in your browser.

Rooms and messages are stored in the application's memory and are not persistent. The configuration in `main.py` is intended for local development. Before deploying the application, configure a secure session key and production settings.
