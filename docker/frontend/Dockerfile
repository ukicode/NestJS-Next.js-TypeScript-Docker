FROM node:18.15.0-alpine
EXPOSE 3333
WORKDIR /app

RUN apk update && \
    apk upgrade

CMD ["npm", "run", "dev"]