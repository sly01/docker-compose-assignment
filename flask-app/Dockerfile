FROM python:3.7.1

RUN git clone https://github.com/Sysnove/flask-hello-world.git

RUN apt-get update

RUN pip install Flask

WORKDIR /flask-hello-world 

ENV FLASK_ENV="development"

ENV FLASK_APP=hello.py

EXPOSE 5000

CMD [ "flask", "run", "--host=0.0.0.0" ]
