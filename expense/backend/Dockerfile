FROM node:20
WORKDIR /opt/backend
USER expense
COPY package.json .
COPY *.js .
RUN npm install
ENV DB_HOST="mydb"

CMD [ "node", "index.js" ]