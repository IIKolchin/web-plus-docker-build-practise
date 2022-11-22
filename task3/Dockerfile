FROM node:16-alpine
WORKDIR /home/ilovedocker/app
COPY package*.json /home/ilovedocker/app
RUN npm i --omit=dev
COPY ./src /home/ilovedocker/app/
EXPOSE 3032
ENTRYPOINT ["node", "main.js"]