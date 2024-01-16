FROM python:3.8-slim

RUN apt-get update && apt-get install -y postgresql-client

COPY etl_scripy.py .

CMD [ "python", "etl_scripy.py" ]