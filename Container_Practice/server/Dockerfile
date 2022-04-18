# Example of Dockerfile

FROM python:3.8

ADD server.py .

RUN pip install -U flask

ENV FLASK_APP=server.py
ENV FLASK_RUN_HOST=0.0.0.0

CMD ["python", "-m", "flask", "run"]