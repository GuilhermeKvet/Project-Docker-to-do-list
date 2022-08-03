FROM mjgargani/puppeteer:trybe1.0

WORKDIR /todotests

ADD node_modules.tar.gz .

COPY ./package.json .
COPY ./jest.config.js .
COPY ./e2e .

ENTRYPOINT [ "npm" ]
CMD [ "test" ]