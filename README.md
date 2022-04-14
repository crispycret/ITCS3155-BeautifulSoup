## Clone the Repo

Clone the repo by whater means you like. After cloning `cd` into the downloaded BeautifulSoup directery.

```
git clone https://github.com/crispycret/BeautifulSoup.git
# or
git clone git@github.com:crispycret/BeautifulSoup.git
```

## Setup

#### Start by creating a virtual environment.

```
python3 -m venv venv
```

#### Activate the virtual environment

```
source venv/bin/activate
```

#### Install the required moudles.

```
pip install -r requirements.txt
``` 


This includes an extra module: `python-dotenv==0.20.0` which will read a `.env` and set environment variables found in there. The provided `.env` file includes `FLASK_APP=task6.py` so that the only thing left to do is to run flask. If for some reason running flask provides you with the following error then you will need to set the `FLASK_APP` variable manually.

```
Error: Could not locate a Flask application. You did not provide the "FLASK_APP" environment variable, and a "wsgi.py" or "app.py" module was not found in the current directory.
```

# Manually Set Environment Variables If Needed
```
# If on windows use 
set FLASK_APP=task6.py

#If on linux/WSL use 
export FLASK_APP=task6.py
```

## Running

To start the flask application run:

```
flask run
```

Once the application is running you can go to `http://localhost:5000/` in a browser to view the application.





