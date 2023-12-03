FROM node:latest
COPY . /app
RUN cd /app; npm install
EXPOSE 3000
WORKDIR /app
ENTRYPOINT [ "npm", "start" ]