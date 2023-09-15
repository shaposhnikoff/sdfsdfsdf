FROM python:3.11-slim

RUN mkdir /app/
WORKDIR /app/

RUN adduser --disabled-password --gecos '' exporter

#COPY requirements.txt /app/requirements.txt
#RUN pip install -r requirements.txt


#COPY emr_terminated_with_errors_v3.py /app/
USER emr_exporter

EXPOSE 8090
#CMD ["python", "/app/emr_terminated_with_errors_v3.py"]
