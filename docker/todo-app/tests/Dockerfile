FROM mjgargani/puppeteer:trybe1.0
WORKDIR /my-docker-apps
COPY package-lock.json .
COPY package.json .
RUN npm install
COPY node_modules.tar.gz .
COPY . .
ENTRYPOINT [ "npm", "test" ]
