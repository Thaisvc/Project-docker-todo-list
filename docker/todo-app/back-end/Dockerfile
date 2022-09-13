FROM node:14.5.0-alpine

WORKDIR /todo-app

ADD node_modules.tar.gz /todo-app/back-end

ADD ./src /todo-app/back-end

COPY package-lock.json /todo-app/back-end

COPY package.json /todo-app/back-end

EXPOSE 3001

CMD npm start