FROM python:3.9

COPY . /opt

RUN pip install -r /opt/requirements.txt

ENV FLASK_APP=myapp:app
WORKDIR /opt
CMD ["flask","run", "--host", "0.0.0.0", "--port", "8989"]
EXPOSE 8989
