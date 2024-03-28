Create an environment

$ mkdir web_server

$ cd web_server

$ py -3 -m venv .venv

Activate the environment

$ .venv\Scripts\activate

Install Flask
$ pip install Flask

flask --help

 $ set FLASK_APP=server.py

 $ set FLASK_ENV=development

 $ flask run
