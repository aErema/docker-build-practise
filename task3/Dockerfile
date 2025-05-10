FROM node:16-alpine
WORKDIR /home/ilovedocker/app
COPY ./packages/package*.json /home/ilovedocker/app
RUN npm i
COPY ./src ./
EXPOSE 3032
CMD [ "node", "main.js" ]
