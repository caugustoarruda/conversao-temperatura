FROM ubuntu
RUN apt update && apt install nodejs npm --yes
WORKDIR /app
COPY . .
RUN npm install
ENTRYPOINT [ "node", "server.js" ]