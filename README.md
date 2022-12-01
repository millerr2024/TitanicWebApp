# TitanicWebApp
A full stack development project based around a Titanic database. 

Worked on with my partner Kiri Salij for a Software Design course at Carleton College. More information in readme.txt


To use this code, you'll need the following packages downloaded:

1) Flask
2) config
3) psycopg2-binary
4) postgresql

To run on your local machine, follow the steps below:
1) git pull. 
2) If it's not already started, start the postgres daemon with "sudo service postgresql start"
3) Load our data into your own database (you should have already created a database): psql -U yourPSQLUsernameHere yourDataBaseNameHere < data.sql
4) Edit config.py:
    user='yourPSQLUsernameHere'
    password='yourPSQLPasswordHere'
    database='yourDatabaseNameHere'
5) Run the webapp: python3 app.py localhost 5000
6) View the webapp in Chrome: http://localhost:5000/
