FROM node:14
# Create app directory
WORKDIR /opt/src/app
# Install app dependencies
COPY package*.json ./

RUN npm install 20.5.0
# Copy app source code
COPY . .

#Expose port and start application
EXPOSE 3000
CMD ["npm", "start"]
