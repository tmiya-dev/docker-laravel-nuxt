FROM node:16.14.0-alpine

RUN apk update && \
    yarn global add create-nuxt-app 

COPY entrypoint.sh /var/tmp/entrypoint.sh
RUN chmod 755 /var/tmp/entrypoint.sh

ENV HOST 0.0.0.0
EXPOSE 3000
