FROM node:14-alpine
EXPOSE 3000

WORKDIR /todofrontend

ADD node_modules.tar.gz .

COPY ./package.json .
COPY ./src .
COPY ./.env .

ENTRYPOINT [ "npm" ]
CMD [ "start" ]
