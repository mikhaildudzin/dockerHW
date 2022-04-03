FROM python:3.8
RUN mkdir /app
WORKDIR /app
COPY . /app
COPY requirements.txt /tmp/
RUN pip install --requirement /tmp/requirements.txt
ENTRYPOINT [ "python" ]
CMD [ "app.py" ]