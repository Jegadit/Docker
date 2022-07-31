FROM ubuntu:latest

RUN apt update
RUN apt install python3 -y

WORKDIR /home/ubuntu

COPY test.py ./

CMD ["python3", "test.py"]