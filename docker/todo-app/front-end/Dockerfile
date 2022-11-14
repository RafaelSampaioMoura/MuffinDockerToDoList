FROM node:14-alpine
WORKDIR /my-docker-apps
EXPOSE 3000
ADD node_modules.tar.gz .
COPY . .
# COPY package-lock.json .
# COPY package.json .
RUN npm install
ENTRYPOINT [ "npm", "start" ]