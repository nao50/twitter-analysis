FROM jupyter/scipy-notebook:latest

RUN pip install requests_oauthlib pymongo
ADD ./twitter-analysis.ipynb /home/$NB_USER/work/
USER root
RUN chmod 777 /home/$NB_USER/work/twitter-analysis.ipynb
USER $NB_UID

