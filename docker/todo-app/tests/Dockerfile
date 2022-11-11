FROM mjgargani/puppeteer:trybe1.0
WORKDIR /home/rafael/Documents/sd-024-a-project-docker-todo-list/docker/todo-app/tests
COPY node_modules.tar.gz /home/rafael/Documents/sd-024-a-project-docker-todo-list/docker/todo-app/tests
COPY e2e /home/rafael/Documents/sd-024-a-project-docker-todo-list/docker/todo-app/tests
ENTRYPOINT [ "npm", "start" ]
