# Star Labs Social

Welcome to Star Labs Social, a basic group based star blogging app built in Django

## How to get started
1. Fork or clone the project
2. Open the project folder in your terminal
3. Run `pip install` to install the required packages
    * If you do not want to install the packages to your global environment, you will need a virtual environment.
4. cd into the project root folder, which contains the manage.py file
5. Run initial migrations with `python manage.py migrate`. 
    * You may need to run `python manage.py makemigrations` beforehand.
6. Start the server with `python manage.py runserver`.
    * The server is set to run at port 8000.
    * If that port is in use, run `python manage.py runserver $PORTNUMBER` (replace $PORTNUMBER with any free port number)
7. In a web browser, open localhost:8000, or the port number you decided on earlier.
