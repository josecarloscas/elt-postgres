FROM python:3.9-slim

RUN apt-get update && apt-get install -y postgresql-client

COPY elt_script.py .

CMD ["python", "elt_script.py"]