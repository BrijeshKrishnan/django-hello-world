# Simple Django Hello World Starter Template

A basic Django 3.0 starter project.


## Usage

 1. Using Python 3.8, run `python -m venv env` to create a virtual environment
 2. Run `pip install -r requirements.txt` to install dependencies
 3. Run `cd app/` to change to `app/`
 3. Run `python manage.py runserver 127.0.0.1:7000` to start development server
 4. Navigate to [http://127.0.0.1:7000](http://127.0.0.1:7000) to test
 
### Using the docker

1. docker build -t python-django-app .
2. docker run -it -p 7000:7000 python-django-app
3. check the application running `http://localhost:7000/`
