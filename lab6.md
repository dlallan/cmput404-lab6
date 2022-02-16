# Lab 6 - Heroku

## Question 1: What are some ways you can deploy your code to Heroku?
One way is to [deploy from Git](https://devcenter.heroku.com/articles/git) automatically by pushing code changes to the Heroku remote added via the Heroku CLI.
Another method is to enable the [GitHub integration](https://devcenter.heroku.com/articles/github-integration), which triggers automatic builds and releases after changes are pushed to the connected GitHub repo.

## Question 2: What is a Procfile used for?
A [Procfile](https://devcenter.heroku.com/articles/procfile) is used by Heroku during a deployment specify how to start the webserver. The "web:" part specifies the type of process (a web server in this case), followed by a command. In this lab, the command was "gunicorn mysite.wsgi", which instructs gunicorn to run a WSGI server bound to the Django project named mysite.

## Question 3: What is the link to your deployed application (onherokuapps)?
https://lab-4-django.herokuapp.com/
