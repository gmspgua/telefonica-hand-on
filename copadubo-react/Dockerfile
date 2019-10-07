FROM node:10
WORKDIR /usr/src/app
COPY package*.json ./
RUN npm install
COPY . .
ENV URL_SERVICE=10.20.20
EXPOSE 3000
ENTRYPOINT ["npm", "start"]