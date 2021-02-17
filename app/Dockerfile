FROM node:13.6.0-alpine

# Create app directory
RUN mkdir -p /usr/src/app
WORKDIR /usr/src/app

# Copy Code and Install app dependencies
COPY . /usr/src/app
RUN npm install

USER node
CMD [ "npm", "start" ]
