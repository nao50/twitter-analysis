FROM jupyter/scipy-notebook:latest

RUN pip install requests_oauthlib pymongo
ADD ./*.ipynb /home/$NB_USER/work/
USER root
RUN chmod 777 /home/$NB_USER/work/*.ipynb
# USER $NB_UID

