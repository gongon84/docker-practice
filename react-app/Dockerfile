FROM node:16.18.0
WORKDIR /app/react-ts
COPY package*.json ./
RUN yarn install
COPY . .
ENTRYPOINT [ "npm", "start" ]