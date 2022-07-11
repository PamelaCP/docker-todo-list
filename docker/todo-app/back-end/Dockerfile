FROM node:14-alpine as todobackend
WORKDIR /app
COPY . .
ADD node_modules.tar.gz .
EXPOSE 3001
CMD [ "npm", "start" ]
