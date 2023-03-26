FROM node:14
EXPOSE 3001
WORKDIR /app
ADD node_modules.tar.gz .
COPY . .
ENTRYPOINT [ "npm" ]
CMD [ "start" ]