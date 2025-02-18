FROM node:18

WORKDIR /usr/src/app

COPY package.json ./

RUN npm i

COPY index.js ./

EXPOSE 8000

CMD ["node", "index.js"]
