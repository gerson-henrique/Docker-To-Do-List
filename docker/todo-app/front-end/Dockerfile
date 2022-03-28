FROM node:14-alpine 
WORKDIR /app
COPY . .
ADD /node_modules.tar.gz ./
CMD ["/usr/local/bin/","npm start"]
EXPOSE 3000
