FROM python:3.8-slim-buster
WORKDIR /devops-bangla
COPY requirements.txt .
RUN pip3 install -r requirements.txt
COPY mattermost_api.py .
