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

## 3rd party resources
* Documentation for mod_wsgi
* Ubuntu packages page
* https://www.digitalocean.com/community/tutorials/how-to-deploy-a-flask-application-on-an-ubuntu-vps#step-four-%E2%80%93-configure-and-enable-a-new-virtual-host
* http://flask.pocoo.org/docs/0.12/deploying/mod_wsgi/
* https://adamdehaven.com/blog/how-to-generate-an-ssh-key-and-add-your-public-key-to-the-server-for-authentication/
* https://www.ssh.com/ssh/keygen/
* https://stackoverflow.com/questions/17954486/which-port-is-being-used-by-a-local-web-server
* https://serverfault.com/questions/261372/how-do-i-tell-what-is-running-on-which-ports-in-ubuntu
* https://askubuntu.com/questions/9368/how-can-i-see-what-ports-are-open-on-my-machine
* https://ca.godaddy.com/help/changing-the-ssh-port-for-your-linux-server-7306
* https://askubuntu.com/questions/30781/see-configured-rules-even-when-inactive
* https://help.ubuntu.com/community/UFW
* https://askubuntu.com/questions/101670/how-can-i-allow-ssh-password-authentication-from-only-certain-ip-addresses
* https://www.a2hosting.com/kb/getting-started-guide/accessing-your-account/disabling-ssh-logins-for-root
* https://stackoverflow.com/questions/26080872/secret-key-not-set-in-flask-session-using-the-flask-session-extension
