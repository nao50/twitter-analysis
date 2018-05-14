FROM jupyter/scipy-notebook:latest

RUN pip install requests_oauthlib pymongo
ADD --chown=$NB_USER:$NB_USER ./twitter-analysis.ipynb /home/$NB_USER/work/


