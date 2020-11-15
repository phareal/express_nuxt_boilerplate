FROM node:12.14.0

# Create app directory

WORKDIR /usr/app/nuxt-front

# Installing dependencies
COPY package*.json /usr/app/nuxt-front
RUN npm install

# Copying source files
COPY . .

# Building app
# RUN npm run build
EXPOSE 3000

# Running the app
ENTRYPOINT [ "yarn", "dev" ]
