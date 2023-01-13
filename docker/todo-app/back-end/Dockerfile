FROM node:14-alpine AS backend-stage
WORKDIR /todo-app

EXPOSE 3001

COPY . .
ADD ./node_modules.tar.gz .

CMD npm start