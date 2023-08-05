FROM apache/airflow:2.6.2-python3.8

# WORKDIR .

USER root

RUN apt-get -y update
RUN apt-get install nano
RUN apt-get install -y vim

USER airflow

RUN pip install pandas
RUN airflow db upgrade