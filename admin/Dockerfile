FROM python:3.9
ENV PYTHONBUFFERED 1
WORKDIR /APP
COPY requirements.txt requirements.txt
RUN pip install -r requirements.txt
COPY . /APP/

CMD python manage.py runserver 0.0.0.0:8000