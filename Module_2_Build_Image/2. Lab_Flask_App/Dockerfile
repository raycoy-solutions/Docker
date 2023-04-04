FROM python:3.9
ENV PYTHONUNBUFFERED 1
ENV PYTHONWRITEBYTECODE 1

WORKDIR /app

COPY requirements.txt app.py ./

RUN pip install -r ./requirements.txt

EXPOSE 5000

CMD ["gunicorn", "-b", ":5000", "app:app"]