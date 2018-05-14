# twitter-analysis
Twitter analysis application in python3.  
You can select the word you want to search and analyze the tweeted time distribution, emotional distribution, and geographical distribution of that word.

## Getting Started

```
$ git clone https://github.com/naoyamaguchi/twitter-analysis.git
$ cd twitter-analysis
$ docker-compose up -d
$ docker ps

CONTAINER ID        IMAGE                       COMMAND                  CREATED             STATUS              PORTS                      NAMES
xxxxxxxxxxxxxx        twitter-analysis_notebook   "tini -- start-noteb…"   11 seconds ago      Up 10 seconds       0.0.0.0:8888->8888/tcp     twitter-analysis_notebook_1
yyyyyyyyyyyyyy        twitter-analysis_mongo      "docker-entrypoint.s…"   12 seconds ago      Up 11 seconds       0.0.0.0:27017->27017/tcp   twitter-analysis_mongo_1

$ docker logs xxxxxxxxxxxxxx
http://<YOUR HOST ADDRESS>:8888/?token=zzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzz

$ open http://<YOUR HOST ADDRESS>:8888/?token=zzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzz
```

## Usege
now making...
