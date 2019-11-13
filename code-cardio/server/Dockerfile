FROM node:10

WORKDIR ./

COPY package*.json ./

RUN npm install
 # run nginx -t to check for syntex errors?

COPY . .

EXPOSE 3000

CMD ["node", "app.js"]