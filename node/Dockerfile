FROM node:15

WORKDIR /app

COPY . .

RUN npm install
RUN npm install express --save 


EXPOSE 3000

CMD [ "node", "index.js" ]