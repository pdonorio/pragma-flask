
# Flask framework

Flask is the reason this documentation exists.

## What is Flask?

Flask is the great work of A.R.

It is very famous for being light/minimal in its real core, but also very easy
to expand. This will allow developers to add the code to handle some things
only when they are really needed.

For example if you want to use a relational database backend, you may probably
add the plugin called 'Flask-SQLAlchemy'
(which was actually also written from A.R.).

## Why should i choose it?

Because its powerful and yet light. Pieces are separated in a clear manner, and
once you learned what is necessary you will always know where to go to solve
your problem.

Flask also try to use the best communities packages for Python. For example
Django uses his own ORM. Flask instead integrates with SQLAlchemy.
Flask also makes uses of WTForms.

## What version of Python are we talking about?

There were many problems for A.R. in the past with Python3.
So he usually suggests to stick with Python2.
In our own experience the year 2015 has been the critical one were everybody
is switching their work into Python3 for real.

We did.

We wrote and tested the things you use now with Python3
and there were no problems related to package versions.

## List of necessary plugins

* Flask-Restful
* Flask-SQLAlchemy
* Flask-Mail
* Flask-Login
* Flask-Admin
* Flask-Security
* Flask-WTF
* flask_table

## Production Python webserver

As clearly stated inside the Flask documentation, the web server proposed
with the framework is just for development.

There are some solution proposed.
We choosed to use *gunicorn*.
