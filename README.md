# Basic-CRUD

# This CRUD is based on the Tutorial --> https://scotch.io/tutorials/build-a-crud-web-app-with-python-and-flask-part-one

# How to run it:

1 - Start a Virtual Env ( Virtualenv myenv)

2 - $ export FLASK_CONFIG=development

3 - $ export FLASK_APP=run.py

4 - flask run ou python3 run.py

Using the tutorial, I faced a couple problems as the code was made on 2016. I will give some tips for make it by your self as I did for trainnig as I'm learning Python.

1º - The first problem I faced on was the data base set up. As it is in the tutorial, it doesn't work anymore. To make this run with python3, I had to use mysqlconnector. For Install it with:

pip install mysql-connector-python

And change line:

SQLALCHEMY_DATABASE_URI = 'mysql://dt_admin:dt2016@localhost/dreamteam_db'

in Instance/config.py to:

SQLALCHEMY_DATABASE_URI = 'mysql+mysqlconnector://dt_admin:dt2016@localhost/dreamteam_db'

2º - Don't forget to use the pip3 for install the requirements or whether you follow the tutorial, use the pip3 form import the libaries.

3º - Don't forget to run on the terminal the command 2 and 3 of the "How to run it". Every time I modified the code I had to run it.

4º - The HTML/CSS page isn't work well and it doesn't look very nice at the moment. I make it better.
