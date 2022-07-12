FROM node:16.14.0-alpine3.15
WORKDIR /app
COPY ["package.json", "package-lock.json*", "./"]
RUN npm install
EXPOSE 8000
COPY . .
CMD [ "node", "app.js" ]
