FROM ubuntu:18.04
COPY . /app
WORKDIR /app
RUN apt-get update
RUN apt-get install python3-dev -y 
RUN apt-get install python3-pip -y 
RUN pip3 install -r requirements.txt 
EXPOSE 5000
CMD python3 ./index.py
