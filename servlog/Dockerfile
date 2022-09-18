FROM node:latest
WORKDIR /code
RUN apt update
RUN apt upgrade
RUN apt install python3 -y
RUN apt install nano
RUN npm init -y
RUN npm install
CMD [ "npm", "start" ]

