FROM node:14
WORKDIR /app
COPY package.json ./
RUN npm install
COPY . .
VOLUME /usr/src/app/data
CMD ["npm", "start"]