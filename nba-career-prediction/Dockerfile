FROM jupyter/scipy-notebook:python-3.8.13
RUN conda install xgboost
RUN conda install boto3
RUN conda install s3fs
RUN conda install lime
RUN conda install hyperopt
RUN conda install graphviz
ENV PYTHONPATH "${PYTHONPATH}:/home/jovyan/work"
WORKDIR /home/jovyan/work
ENV AWS_ACCESS_KEY_ID AKIARAWTVEUX4BTMQAUN
ENV AWS_SECRET_ACCESS_KEY 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