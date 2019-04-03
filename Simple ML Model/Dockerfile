FROM python:3.5
MAINTAINER ADITYA
COPY . /usr/local/python/
EXPOSE 5000
WORKDIR /usr/local/python/
RUN pip install --no-cache-dir -r requirements.txt
CMD python deploy.py
