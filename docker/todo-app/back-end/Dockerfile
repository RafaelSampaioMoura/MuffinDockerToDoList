FROM node:14
WORKDIR /home/rafael/Documents/sd-024-a-project-docker-todo-list/docker/todo-app/back-end
EXPOSE 3000
COPY src /home/rafael/Documents/sd-024-a-project-docker-todo-list/docker/todo-app/back-end
COPY node_modules.tar.gz /home/rafael/Documents/sd-024-a-project-docker-todo-list/docker/todo-app/back-end
ENTRYPOINT [ "npm", "start" ]
