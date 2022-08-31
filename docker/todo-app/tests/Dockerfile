
FROM node:14-alpine

WORKDIR /to-do

ADD ./node_modules.tar.gz .

COPY . ./todo-app/tests

ENTRYPOINT ["npm"]

CMD ["test"]