FROM node:12
WORKDIR /app
COPY package.json /app
RUN npm install
COPY . /app
CMD node index.js
VOLUME /clientvol
