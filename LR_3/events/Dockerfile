FROM node:18.12.0-alpine
WORKDIR /app/events
COPY package*.json ./
COPY . .
RUN npm install
EXPOSE 9523
CMD ["npm", "start"]
