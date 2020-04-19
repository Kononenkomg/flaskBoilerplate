#Tutorial
https://flask.palletsprojects.com/en/1.1.x/tutorial/views/

## Start app:
export FLASK_APP=flaskr
export FLASK_ENV=development
flask run -p 8080


## Find and kill my process on specific port:

sudo lsof -i :8080

kill -9 PID

## Initialize the Database File
flask init-db

## Activate virtual environment
source venv/bin/activate