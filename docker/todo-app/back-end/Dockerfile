FROM node:alpine
WORKDIR /node
ADD ./node_modules.tar.gz ./
COPY . .
EXPOSE 3001
CMD ["npm", "start"]