FROM node:12.14.0



# Create app directory

WORKDIR /usr/app/nuxt-api

# Installing dependencies
COPY package*.json /usr/app/nuxt-api
RUN npm install

# Copying source files
COPY . .

# Building app
# RUN npm run build
EXPOSE 8000

# Running the app
CMD [ "node", "server.js" ]
