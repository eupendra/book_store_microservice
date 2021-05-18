FROM python:3.8-alpine
COPY requirements.txt /orderapp/requirements.txt
WORKDIR /orderapp
RUN pip install -r requirements.txt
COPY . /orderapp
ENTRYPOINT ["python"]
CMD ["app.py"]