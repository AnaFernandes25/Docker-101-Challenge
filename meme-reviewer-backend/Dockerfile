FROM python:3.9-slim

WORKDIR /app

COPY . .
RUN pip3 install -r requirements.txt

EXPOSE 5000
ENTRYPOINT [ "python3", "-m", "flask", "run", "--host=0.0.0.0"]