FROM node:14-alpine3.16
EXPOSE 3001

WORKDIR /todobackend

ADD node_modules.tar.gz .

COPY ./package.json .
COPY ./src .

ENTRYPOINT [ "npm" ]
CMD [ "start" ]
