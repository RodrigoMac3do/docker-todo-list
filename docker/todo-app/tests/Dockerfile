
FROM node:14-alpine

WORKDIR /to-do

EXPOSE 3001

ADD ./node_modules.tar.gz .

COPY  . ./todo-app/tests

ENTRYPOINT ["npm"]

CMD ["test"]