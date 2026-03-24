FROM node:16-alpine

WORKDIR /home/ilovedocker/app

COPY packages/package.json packages/package-lock.json ./

RUN npm install

EXPOSE 3032

ENTRYPOINT ["node", "main.js"]