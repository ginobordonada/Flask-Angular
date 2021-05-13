# Flask & Angular
## Description
This project is admin page which built with Flask and Angular 8
#### Skill-Set
+ Flask
+ Angular8

#### Preview
![Relevance feedback image](https://github.com/ericserraupwork/Flask-Angular/blob/master/Screenshots/f_screen2.png)
![Relevance feedback image](https://github.com/ericserraupwork/Flask-Angular/blob/master/Screenshots/f_screen3.png)
![Relevance feedback image](https://github.com/ericserraupwork/Flask-Angular/blob/master/Screenshots/f_screen4.png)

# Running Instructions
Application requires a database to correctly run. It can be any database SQLAlchemy supports. In development by default Sqlite database is used, which is stored at `api/bundle.db`. If you would like to use other database in development mode, change database URL in `api/config.py` line 46.

### Running the backend

0) Install python 3. You can find [here](https://realpython.com/installing-python/) instructions for your operation system.

1) Change directory to the *backend* folder `cd backend`

2) Create virtualenv `virtualenv -p python3 bundle_env`

3) Activate virtualenv `source bundle_env/bin/activate`

4) Install required python modules `pip install -r requirements.txt`

5) Only during the initial launch create database schema for your application `python manage.py recreate_db`

6) Run the application `python manage.py runserver`

That's it! Now your application is running at port 3001 and you can access it by typing `http://localhost:3001/` in your browser.

### Running Angular front end

Before running Angular you need to have node installed 

0) Install nodejs. You can download it using you operating system package manager or from [here](https://nodejs.org/en/download/).

1) Go to the *front end* folder `cd frontend`

2) Run commands `npm install` and `npm start`
3) Open `http://localhost:4200` in your browser
4) create new user using interface and start working with app

#### Author
+ Eric Serra
+ ericserraupwork@gmail.com
