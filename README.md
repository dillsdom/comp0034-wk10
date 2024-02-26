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

## Set up

- Fork the repository to create a copy in your GitHub account
- Clone your copy to your IDE
- Create a venv (or use an existing one)
- Install requirements. Note that the requirements.txt includes dependencies for all the apps. If you only want to run
  dash apps then use the 'requirements-dash'; likewise for flask.

## Other sources

Login for Dash apps:

Note that you don't have the enterprise Dash version so avoid any tutorials that implement dash-enterprise-auth as you
won't be able to use it.

- [Dash login page](https://www.analyticsvidhya.com/blog/2021/05/create-login-page-in-dash-library/)
- [Dash basic auth](https://dash.plotly.com/authentication#basic-auth-example)
- [Dash basic auth implementation video](https://www.youtube.com/watch?v=MxQtgLVEqbQ)
- You could try Flask-Login, search for tutorials that implement Flask-Login for Plotly Dash