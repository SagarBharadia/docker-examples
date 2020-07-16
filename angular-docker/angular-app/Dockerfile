# Base image
FROM node:12

# Creating working dir
RUN mkdir /usr/src/app

# Setting it as the work directory for future commands
WORKDIR /usr/src/app

# Installing the angular cli
RUN npm install -g @angular/cli

# Copy angular application to docker instance
COPY . .

