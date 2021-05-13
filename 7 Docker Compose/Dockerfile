FROM python:3.4-alpine
ADD . /code
WORKDIR /code
RUN pip install flask
RUN pip install redis
RUN ls
CMD ["python", "app.py"]
