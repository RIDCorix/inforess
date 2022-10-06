FROM python:3.9
ENV PYTHONDONTWRITEBYTECODE=1
ENV PYTHONUNBUFFERED=1
WORKDIR /home/backend
COPY requirements.txt /home/backend/
RUN pip install -r requirements.txt
COPY . /home/backend/