FROM continuumio/miniconda3
RUN apt-get update && apt-get install -y git

RUN pip install mlflow psycopg2-binary pymysql 


# RUN mkdir -p /usr/src/app/mlruns
# RUN chmod +777 -R /usr/src/app/mlruns

# RUN cd /home && git clone https://github.com/mlflow/mlflow-example.git

# RUN mlflow ui
