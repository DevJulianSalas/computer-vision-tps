FROM jupyter/base-notebook:hub-4.0.2
ENV HOME_DIR=home/jovyan/tps-vision
#Copy requirerments
COPY ./requirements.txt /tmp/
#Install all required packages
RUN pip install -r /tmp/requirements.txt
WORKDIR /$HOME_DIR
COPY . /$HOME_DIR