FROM node:24

WORKDIR /todo-app/todo-backend

COPY --chown=node:node . .

RUN npm ci

ENV DEBUG=express:*

USER node

CMD [ "npm", "start" ]
