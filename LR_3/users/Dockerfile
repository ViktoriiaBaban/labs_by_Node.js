FROM node:18.12.0-alpine
WORKDIR /app/users
COPY package*.json ./
COPY . .
RUN npm install
EXPOSE 2920
CMD ["npm", "start"]
