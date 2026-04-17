#FROM node:20 latest
FROM node:20.20.2-alpine3.23
WORKDIR /opt/backend
COPY package.json ./
COPY *.js ./
RUN npm install
ENV DB_HOST="mysql"
CMD ["node", "index.js"]