FROM node AS app

WORKDIR /usr/src/app

COPY package*.json ./

RUN npm install -g npm@latest
RUN npm install express

# RUN seeds/seed.js

COPY . .

EXPOSE 3000

CMD ["node", "app.js"]
# ###
# Let's build a multi-stage production ready image
FROM node:alpine

WORKDIR /usr/src/app

COPY package*.json ./

RUN npm install -g npm@latest
RUN npm install express

# This line of code does the magic here to compress the images
COPY --from=app /usr/src/app /usr/src/app/

EXPOSE 3000

CMD ["node", "app.js"]
