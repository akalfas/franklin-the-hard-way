FROM node:18.12-buster

RUN apt clean

RUN apt-get update && apt-get -y install git

RUN npm install -g @adobe/helix-cli

WORKDIR /code

CMD ["hlx","up"]

