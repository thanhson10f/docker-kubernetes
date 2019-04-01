# get the base image
FROM node:alpine

# Set working directory
WORKDIR /usr/node-app

# copy the package.json file
COPY ./package.json ./

# Install dependencies
RUN npm install

# copy all source code
COPY ./ ./

# set the default startup command
CMD ["npm", "start"]
