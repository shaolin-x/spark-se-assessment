web: export FLASK_APP=project.server && export APP_SETTINGS="project.server.config.DevelopmentConfig" && flask db init && flask db migrate && flask db && gunicorn upgrade project.server:app
heroku ps:scale web=1
