FROM python:alpine3.7
COPY . /app
WORKDIR /app
RUN pip install -U pip
RUN apk --no-cache add musl-dev linux-headers g++
RUN pip install numpy
EXPOSE 5000
CMD python3 ./index.py
