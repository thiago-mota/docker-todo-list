FROM node:14-alpine AS todofrontend
WORKDIR /projeto
COPY . .
EXPOSE 3001
ADD node_modules.tar.gz .
CMD ["npm", "start"]