FROM jupyter/scipy-notebook:latest

RUN pip install requests_oauthlib pymongo
ADD ./*.ipynb /home/$NB_USER/work/
USER root
RUN chmod 777 /home/$NB_USER/work/*.ipynb

RUN git clone https://github.com/taku910/mecab.git
RUN cd mecab/mecab && ./configure  --enable-utf8-only && make && make check && make install
RUN pip install mecab-python3 


# USER $NB_UID