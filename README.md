# Pitch Mojo
This is a simple python-based application that allows users to views pitches made, comment on the pitches if they are logged in, vote and add their own pitch. 

#### By **[Joseph Muema]**

## Description
This application is meant to display various pitches of different categories. A user can select different categories from the list displayed and views the pitches.
 A user who is logged in can comment, like or give feedback on the pitches. The categories are:

    1. Technology
    2. Fiction
    3. Automotive

## Specifications
| Behavior            | Input                         | Output                        | 
| ------------------- | ----------------------------- | ----------------------------- |
| Technology category | Click on the `Technology` category | Goes to the `Technology` page |
| Fiction category | Click on the `Fiction` category | Goes to the `Fiction` page |
| Automotive category | Click on the `Automotive` category | Goes to the`Automotive` page |

## Prerequsites
    - Python 3.6 required

## Set-up and Installation
    - Clone the Repo
    - Install python 3.6
    - Run chmod a+x start.py
    - Run ./start.py
    - pip3 install -r requirements (dependencies)

## Technologies used
   [![HTML5](https://img.shields.io/badge/html-html5-e34f26.svg)](https://www.w3schools.com/html/html5_intro.asp)
[![Bootstrap](https://img.shields.io/badge/bootstrap-4.0.0-purple.svg)](https://getbootstrap.com/)
[![Python 3.6](https://img.shields.io/badge/python-3.6-blue.svg)](https://www.python.org/downloads/release/python-360/)
[![Git](https://img.shields.io/badge/git-2.17.1-rgb(245%2C%2077%2C%2039).svg)](https://git-scm.com/)
[![Flask](https://img.shields.io/badge/flask-1.0.2-lightgrey.svg)](http://flask.pocoo.org/)
[![PostgreSQL](https://img.shields.io/badge/postgreSQL-11.1-darkblue.svg)](https://www.postgresql.org/)
[![Pip](https://img.shields.io/badge/pypi-v18.1-blue.svg)](https://pypi.org/project/pip/)
### Create a Virtual Environment
Run the following commands in the same terminal:
`sudo apt-get install python3.6-venv`
`python3.6 -m venv virtual`
`source virtual/bin/activate`

### Prepare environment variables
```bash
export DATABASE_URL='postgresql+psycopg2://username:password@localhost/pitches'
export SECRET_KEY='Your secret key'
```
### The application does use Postgresql. To Run database Migrations, run the following: 
```
python manage.py db init
python manage.py db migrate -m "initial migration"
python manage.py db upgrade
```
### Running the app in development
In the same terminal type:
`python3 manage.py server`

Open the browser on `http://localhost:5000/`

### [License]

Copyright 2019 JOSEPH MUEMA

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

Copyright (c) **Joseph Muema**
