# Flight Fare Prediction: 

## Table of Content
  * [The Problem](#the-problem)
  * [Demo](#demo)
  * [Overview](#overview)
  * [Motivation](#motivation)
  * [Installation](#installation)
  * [Deployement on Heroku](#deployement-on-heroku)
  * [Directory Tree](#directory-tree)


## The Problem
Airline companies use complex algorithms to calculate flight prices given various conditions present at that particular time. These methods take financial, marketing, and various social factors into account to predict flight prices.

Nowadays, the number of people using flights has increased significantly. It is difficult for airlines to maintain prices since prices change dynamically due to different conditions. That’s why we will try to use machine learning to solve this problem. This can help airlines by predicting what prices they can maintain. It can also help customers to predict future flight prices and plan their journey accordingly.

## Demo
Link: [https://flight-price-prediction-api.herokuapp.com/](https://flight-price-predict-api.herokuapp.com/predict)

[![](https://github.com/docum5/Flight-Price-Prediction/blob/main/DEMOO.PNG?raw=true)](https://flight-price-predict-api.herokuapp.com/predict)

[![](https://github.com/docum5/Flight-Price-Prediction/blob/main/demo22.PNG?raw=true)](https://flight-price-predict-api.herokuapp.com/predict)



## Overview
This is a Flask web app which predicts fare of Flight ticket.

## Motivation
What to do when you are at home due to this pandemic situation? I started to learn Machine Learning model to get most out of it. I came to know mathematics behind all supervised models. Finally it is important to work on application (real world application) to actually make a difference.

## Installation
The Code is written in Python 3.8.12. If you don't have Python installed you can find it [here](https://www.python.org/downloads/). If you are using a lower version of Python you can upgrade using the pip package, ensuring you have the latest version of pip. To install the required packages and libraries, run this command in the project directory after [cloning](https://www.howtogeek.com/451360/how-to-clone-a-github-repository/) the repository:
```bash
pip install -r requirements.txt
```

## Deployement on Heroku
Login or signup in order to create virtual app. You can either connect your github profile or download ctl to manually deploy this project.

[![](https://github.com/docum5/Flight-Price-Prediction/blob/main/new%20app.PNG?raw=true)](https://heroku.com)

Our next step would be to follow the instruction given on [Heroku Documentation](https://devcenter.heroku.com/articles/getting-started-with-python) to deploy a web app.

## Directory Tree 
```
├── static 
│   ├── css
├── template
│   ├── home.html
├── Procfile
├── README.md
├── app.py
├── flight_price.ipynb
├── flight_rf.pkl
├── requirements.txt
```

## Technologies Used

![](https://forthebadge.com/images/badges/made-with-python.svg)

[<img target="_blank" src="https://flask.palletsprojects.com/en/1.1.x/_images/flask-logo.png" width=170>](https://flask.palletsprojects.com/en/1.1.x/) [<img target="_blank" src="https://number1.co.za/wp-content/uploads/2017/10/gunicorn_logo-300x85.png" width=280>](https://gunicorn.org) [<img target="_blank" src="https://scikit-learn.org/stable/_static/scikit-learn-logo-small.png" width=200>](https://scikit-learn.org/stable/) [<img target="_blank" src="https://camo.githubusercontent.com/8c8cd6fb9104edca5dcc83480ce23be35635c38db540f90a7e325dcae5a60281/68747470733a2f2f676574626f6f7473747261702e636f6d2f646f63732f342e312f6173736574732f696d672f626f6f7473747261702d737461636b2e706e67" width=100>](https://getbootstrap.com/docs/4.5/getting-started/introduction/)


