FROM node:14-alpine3.16
EXPOSE 3001

ADD node_modules.tar.gz .

WORKDIR /todobackend

COPY . .

RUN npm install

ENTRYPOINT [ "npm" ]
CMD [ "start" ]
