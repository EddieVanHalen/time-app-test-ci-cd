FROM node:alpine
 
EXPOSE 5001
 
WORKDIR /app
 
COPY *package*.json ./
 
RUN npm install
 
COPY . .
 
CMD [ "npm", "run", "dev" ]