FROM node:14-alpine

WORKDIR /to-do

EXPOSE 3000

ADD ./node_modules.tar.gz .

COPY . ./todo-app/front-end

ENTRYPOINT ["npm"]

CMD ["start"]