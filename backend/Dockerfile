FROM node:18
WORKDIR /app
COPYy package*.json ./
RUN npm install
COPY . .
EXPOSE 15000
CMD ["npm", "start"] 