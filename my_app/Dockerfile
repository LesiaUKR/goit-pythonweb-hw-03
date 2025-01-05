FROM python:3.13-slim

WORKDIR /my_app

COPY requirements.txt /my_app/

RUN pip install --no-cache-dir -r /my_app/requirements.txt

COPY . /my_app/

EXPOSE 3000
EXPOSE 6000

CMD ["python", "app.py"]
