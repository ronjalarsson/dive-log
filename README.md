# dive-log
This is a project for a course in my school, EC Utbildning, where I build a dive log to record my dives.

# freediving
My biggest passion in life is - you guessed it - freediving. For this project in school we are building an API and a programme that communicates with the a database. There should also seed file where we can seed data to the database. So I decided to build a personal dive log to log my freedives.

# file structure
There are a total of 8 files in this project as described below.

There are 5 Python files:
 - api.py 
 - app.py (the program itself)
 - db.py (database logic) 
 - models.py (models used in api.py in a separate file)
 - seed.py (a file to seed data into db)

 There are one json file:
 - seed.json (a json file contaning data to be seeded into db through seed.py)

 There are one sql file:
 - setup.sql (the schema of the tables in the database used in db.py)

 There are one html file:
 - index.html (the root of the api links to this simple html page)

The database is not created here. I delete the database each time I push updated code to github.
