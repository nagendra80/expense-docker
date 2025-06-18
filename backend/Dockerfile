FROM node:20
WORKDIR /opt/backed
COPY package.json ./
COPY *.js ./
RUN npm install
ENV DB_HOST="mysql"
CMD ["node", "index.js"]


