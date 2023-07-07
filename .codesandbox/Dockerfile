FROM node

RUN apt-get update

RUN apt-get upgrade -y

ENV NG_CLI_ANALYTICS=false

ENV NG_FORCE_TTY=false

RUN npm install -g @angular/cli@15.0.0