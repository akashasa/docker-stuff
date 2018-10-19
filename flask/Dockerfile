FROM ubuntu:latest
RUN apt-get -y update
RUN apt-get -y install python-pip python-dev build-essential
COPY . /app
WORKDIR /app
RUN pip install flask
ENTRYPOINT ["python"]
CMD ["flask_app.py"]

