FROM node:lts-alpine3.20

EXPOSE 3000

COPY . /app

WORKDIR /app

RUN yarn install --frozen-lockfile

CMD yarn start