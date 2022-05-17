FROM mjgargani/puppeteer:trybe1.0 
WORKDIR /todo-app/test
ADD node_modules.tar.gz ./
EXPOSE 3002
COPY . .
CMD ["npm", "test"]
