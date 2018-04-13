# flask-chatterbot

#### A web implementation of chatbot using Flask.

## Local Setup:

 1. Ensure that virtualenv is already installed.
 2. Ensure that Python, Flask, SQLAlchemy, and ChatterBot are installed (either manually, or run `pip install -r requirements.txt`).
 3. Run *app.py*
 4. Demo will be live at [http://localhost:5000/](http://localhost:5000/)

## How do I deploy this to a web server?
1. Before getting started, we need to install Flask. Because systems vary, things can sporadically go wrong during these steps. If      they do, like we all do, just Google the error message or leave a comment describing the problem.
2. We'll use virtualenv to install Flask.
3. It's possible that your system already has virtualenv. Refer to the command line, and try running:
   $ virtualenv --version
4. If the command was not found, use easy_install or pip to install virtualenv. If running Linux or Mac OS X, one of the following should work for you:
   $ sudo easy_install virtualenv
5. After installing virtualenv, you can create a new isolated development environment, like so:
   $ virtualenv flaskapp
   Here, virtualenv creates a folder, flaskapp/, and sets up a clean copy of Python inside for you to use. It also installs the     handy package manager, pip.
6.Enter your newly created development environment and activate it so you can begin working within it.
  $ cd flaskapp
  $ . bin/activate
7. Now, you can safely install Flask:
   $ pip install Flask
8. Now, copy the folder in the flaskapp.
9. Now, inside the folder open terminal and run python app.py
