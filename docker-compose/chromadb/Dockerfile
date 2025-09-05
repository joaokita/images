# Simple Dockerfile for chromadb-ui
FROM node:20-alpine
WORKDIR /app
COPY . .
RUN npm install && npm run build
EXPOSE 8090
CMD ["npm", "start"]
