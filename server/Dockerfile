FROM node

WORKDIR /server

COPY package.json /server/

RUN npm install
# RUN npm run test

COPY . /server/

CMD ["node", "app.js"]
