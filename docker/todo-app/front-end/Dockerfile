FROM node:14-alpine AS frontend-stage
WORKDIR /todo-app

EXPOSE 3000

COPY . .
ADD ./node_modules.tar.gz .

CMD npm start


