release: bash launch.sh
web: gunicorn project.server:app
heroku ps:scale web=1
