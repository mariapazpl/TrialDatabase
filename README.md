# Sample Flask Application for Interacting with a MySQL Database

This is a simple application that stores comments from users and displays them. It is intended to be run on python-anywhere, where the code has access to a MySQL database.

This was used to experiment with persistent storage for the [Patria](https://github.com/mariapazpl/Patria-Website) website.

## Files

1. The db_setup.sql file contains all commands necessary to set up the database and required tables in MySQL.

2. The flask_app.py file contains the code to run a simple Flask server that will interface with the MySQL database once the tables have been created, allowing users to store their comments, and serving the main page.

3. The templates/main_page.html is the HTML file that will be served to the users, allowing them to write comments which will then be stored in the table we created in step 1.
4. Demo video:


https://github.com/mariapazpl/TrialDatabase/assets/153972139/ada844c3-a6f6-48cc-b66f-591edd5ed391

