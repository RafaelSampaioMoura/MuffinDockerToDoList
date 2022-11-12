FROM node:14-alpine
WORKDIR /my-docker-apps
EXPOSE 3000
COPY package-lock.json .
COPY package.json .
RUN npm install
ADD node_modules.tar.gz .
COPY . .
ENTRYPOINT [ "npm", "start" ]