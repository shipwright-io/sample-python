FROM quay.io/shipwright-samples/python:3.8

COPY requirements.txt requirements.txt
RUN pip3 install -r requirements.txt

COPY app.py app.py
CMD ["python3", "-m" , "flask", "run", "--host=0.0.0.0", "--port=8080"]
