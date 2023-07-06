FROM node

WORKDIR /workspace

RUN rm -rf node_modules > /dev/null 2>&1
 
RUN apt-get update

RUN apt-get upgrade -y

ENV NG_CLI_ANALYTICS=false

RUN npm install -g @angular/cli@15.0.0