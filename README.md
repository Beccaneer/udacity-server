# udacity-server

## Basic Information
IP address: 54.174.47.151\
Port: 2200\
URL: [http://54.174.47.151.xip.io](http://54.174.47.151.xip.io)

## Software Installed
* [Flask](http://flask.pocoo.org/)
* [SQLAlchemy](https://www.sqlalchemy.org/)
* [WTForms](https://flask-wtf.readthedocs.io/en/stable/)
* [OAuth2client](https://pypi.org/project/oauth2client/)
* [Apache](https://httpd.apache.org/)
* [PostgreSQL](https://www.postgresql.org/) Although I did not end up using it
* [SQLite](https://www.sqlite.org/index.html)
* [mod_wsgi](https://modwsgi.readthedocs.io/en/develop/)

## Summary of configurations
* Added the `grader` user, gave sudo and ssh access
* Removed ability to log into server by password
* Removed ability to log into server as root
* Changed ssh port from `22` to `2200`
* Changed UFW to allow `ssh`, `http`, and `ntp` only, disabled port `22`
* Added the `.wsgi` file to `\var\www\html\`
