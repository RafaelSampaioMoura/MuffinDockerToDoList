FROM mjgargani/puppeteer:trybe1.0
WORKDIR /my-docker-apps
# COPY package-lock.json .
# COPY package.json .
ADD node_modules.tar.gz .
COPY . .
RUN npm install
ENTRYPOINT [ "npm", "test" ]
