# docker-demo

docker-compose run web django-admin startproject [project name] .

# start application server
 uwsgi --http :8000 --module test.wsgi