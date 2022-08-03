FROM node:14-alpine3.16
EXPOSE 3000

ADD node_modules.tar.gz .

WORKDIR /todofrontend

COPY . .

RUN npm install

ENTRYPOINT [ "npm" ]
CMD [ "start" ]
