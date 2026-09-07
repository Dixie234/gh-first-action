FROM node:20

ENV MONGODB_CONNECTION_PROTOCOL mongodb+srv
ENV MONGODB_DB_NAME gha-demo
ENV MONGODB_CLUSTER_ADDRESS mynewcluster.v1ns2t5.mongodb.net
ENV MONGODB_USERNAME github-actions-user-1
ENV MONGODB_PASSWORD YBGw!Y2ssH9ui&5

WORKDIR /app

COPY package*.json . 

RUN npm install

COPY . .

CMD ["npm", "start"]