FROM node:8.16.1-alpine
WORKDIR /app
COPY . /app
RUN npm install
EXPOSE 5000
CMD node index.js

#ENTRYPOINT ["node", "index.js"]
#COPY package.json /app

#Better version with dependency as layer
#FROM node:8.16.1-alpine
#WORKDIR /app
#COPY package.json /app #For only dependencies as layer
#RUN npm install
#EXPOSE 5000
#COPY . /app #Only application code as layer
#CMD node index.js