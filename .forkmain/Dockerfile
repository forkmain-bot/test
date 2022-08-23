FROM node:16

WORKDIR /workdir

COPY ./ ./

RUN yarn install && yarn build

EXPOSE 3000

CMD ["sh", "-c", "yarn start"]