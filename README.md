# TitanicWebApp
A full stack development project based around a Titanic database. 

Worked on with my partner Kiri Salij for a Software Design course at Carleton College. More information in readme.txt


To use this code, you'll need the following packages downloaded:

-Flask
-config
-psycopg2-binary
-postgresql

To run on your local machine, follow the steps below:
-git pull. 
-load our data into your own database (you should have already created a database): psql -U yourPSQLUsernameHere yourDataBaseNameHere < data.sql
-Edit config.py:
    user='yourPSQLUsernameHere'
    password='yourPSQLPasswordHere'
    database='yourDatabaseNameHere'
-Run the webapp: python3 app.py localhost 5000
-View the webapp in Chrome: http://localhost:5000/
