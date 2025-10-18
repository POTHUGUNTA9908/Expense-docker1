FROM node:25
WORKDIR /opt/backend
COPY package.json ./
COPY *.js ./
RUN npm install
ENV DB_HOST="mysql"
CMD ["node", "index.js"]