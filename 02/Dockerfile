FROM ubuntu:latest

RUN apt-get update -y
RUN apt install -y python3 python-pip 

WORKDIR /app
EXPOSE 80
COPY app.py .

CMD  python3 /app/app.py

