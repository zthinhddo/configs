FROM alpine:3.17 as myimage

WORKDIR /my-project

COPY . /my-project

COPY yarn.lock /my-project

RUN yarn install \
    --frozen-lockfile

EXPOSE 3000-3020 3000

CMD ["yarn", "start"]