FROM node:14-alpine 
WORKDIR /todo-app/back-end
COPY package*json ./
EXPOSE 3001
COPY . .
RUN npm install
CMD ["npm", "start"]