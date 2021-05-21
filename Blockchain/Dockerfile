FROM python:3.9.5-slim-buster

WORKDIR /

COPY requirements.txt requirements.txt
RUN pip3 install -r requirements.txt

COPY . /
ENTRYPOINT [ "python3" ]
CMD [ "node.py"]