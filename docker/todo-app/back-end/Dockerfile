FROM node:14
EXPOSE 3001

WORKDIR /todobackend

ADD node_modules.tar.gz .

COPY package.json .

RUN npm install

COPY . .

ENTRYPOINT [ "npm" ]
CMD [ "start" ]
