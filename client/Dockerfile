FROM node:14-alpine

# make the 'app' folder the current working directory
WORKDIR /app

# copy 'package.json'
COPY package.json .

# install project dependencies
RUN npm install

# copy project files and folders to the current working directory (i.e. 'app' folder)
#COPY . .

EXPOSE 8080
