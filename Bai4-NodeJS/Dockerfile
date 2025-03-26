FROM node:18

WORKDIR /usr/src/app

COPY src/package.json ./
RUN npm install

COPY src/index.js ./

EXPOSE 3000

CMD ["npm", "start"]