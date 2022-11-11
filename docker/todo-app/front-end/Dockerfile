FROM node:14
WORKDIR /home/rafael/Documents/sd-024-a-project-docker-todo-list/docker/todo-app/front-end
EXPOSE 3000
COPY node_modules.tar.gz /home/rafael/Documents/sd-024-a-project-docker-todo-list/docker/todo-app/front-end
COPY src /home/rafael/Documents/sd-024-a-project-docker-todo-list/docker/todo-app/front-end
ENTRYPOINT [ "npm", "start" ]
