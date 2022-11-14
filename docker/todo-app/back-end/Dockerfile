FROM node:14-alpine
WORKDIR /my-docker-apps
EXPOSE 3001
# COPY package-lock.json .
# COPY package.json .
ADD node_modules.tar.gz .
COPY . .
RUN npm install
ENTRYPOINT [ "npm", "start" ]
