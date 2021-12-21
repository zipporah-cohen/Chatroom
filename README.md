# Chatroom
CS 242 Final Project

### Prerequisites
Ensure that you are on Python version 3.9
Install the following packages using `pip install` or `pip3 install` depending on your python version. Ensure the packages are located in the python directory in which your development environment will be pointed.
- werkzeug
- flask
- flask-socketio
- eventlet
- pymongo
- Flask-login

### Connect to MongoDB
The MongoDB database should allow you to run the server and push data to it from any IP address. You can also use your own Mongo Atlas server if ours is not working; just change the link in the db.py file.

### Get it running
When you’re ready to run, execute `python app.py` in your working directory (e.g., yourDirectory/Chatroom). Again, you may need to use `python3 app.py`. The output will print a link on which the site is running (in the code this is set to the local server, http://127.0.0.1:5000/). Navigate to that link to get chatting!
