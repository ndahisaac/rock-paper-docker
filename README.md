# rock-paper-docker

$ docker run -dit --name my-apache-app -p 8080:80 -v "$PWD":/usr/local/apache2/htdocs/ httpd:2.4
$ docker build -t my-apache2 .
$ docker run -dit --name my-running-app -p 8080:80 my-apache2