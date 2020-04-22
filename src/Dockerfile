FROM python:3.7-stretch
#FROM python:3.7-alpine
COPY . /app
WORKDIR /app
RUN apt-get update && apt-get install -y python-pip
RUN pip install -r requirements.txt
ENTRYPOINT [ "python" ]
CMD [ "app.py" ]