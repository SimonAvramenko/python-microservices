FROM python:3.9
ENV PYTHONUNBUFFERED 1
WORKDIR /app
COPY requirements.txt /app/requirments.txt
RUN pip install -r requirments.txt 
COPY . /app/

CMD python main.py