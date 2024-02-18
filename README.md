# COMP0034 Examples

This repository contains the example apps from the course. Other examples may be added as questions are raised on Moodle
and in classes.

These are minimal examples to demonstrate concepts; they are not 'exemplars' (i.e. they are not intended as coursework
exemplars). They often lack error handling; there is little attention to styling; docstrings may be absent; and other
general code structure improvements may be made.

Current list of apps in the 'src' directory:

| Name               | Run                                                                                                                                                        | Features                                                                                 |
|:-------------------|:-----------------------------------------------------------------------------------------------------------------------------------------------------------|:-----------------------------------------------------------------------------------------|
| dash_paralympics   | `python src/paralympics_dash/paralympics_dash.py`                                                                                                          | All core dash activities completed from weeks 6 - 9.                                     |
| dash_recycle       | `python src/recycle_app/recycle_app.py`                                                                                                                    | Example app from 2022-23 activities.                                                     |
| dash_multi         | `python src/dash_multi/multi_app.py`                                                                                                                       | Illustrates multi-page app configuration. Minimal charts, no callbacks.                  |
| dash_sqlalchemy    | `python src/dash_sqlalchemy/app.py`                                                                                                                        | Illustrates a single chart that access data using Flask-SQlAlchemy and models.py.        |
| flask_paralympics  | `flask --app paralympics_flask run`                                                                                                                        | All core flask activities completed from weeks 6 - 8.                                    |
| paralympics_rest   | `flask --app paralympics_rest run`                                                                                                                         | All core REST API activities from weeks 1-4                                              |
| flask_iris         | `flask --app "flask_iris:create_app('dev')" --debug run`<br>Note: the URL never shows in the terminal so open a browser and go to <http://127.0.0.1:5000/> | Pages with a form to get a prediction. Scikit-learn code to create a pickled model file. |
| flask_simple_login | `flask --app paralympics_simple_login run`                                                                                                                 | Illustrates login with Flask-Login. Creates and displays a user profile.                 |