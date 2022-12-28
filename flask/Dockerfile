FROM python:3.6.1-alpine
RUN pip install --upgrade pip
WORKDIR /FelCloud/flask
ADD . /FelCloud/flask
RUN pip install -r requirements.txt
CMD ["python","app.py"]
