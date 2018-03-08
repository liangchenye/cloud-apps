From isula/simple-server:0.1

EXPOSE 80
WORKDIR /isula-data
RUN wget https://github.com/gabrielecirulli/2048/archive/master.zip; unzip master.zip

ENTRYPOINT ["simple-server", "--data", "/isula-data/2048-master", "--prefix", "/game/"]
