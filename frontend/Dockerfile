# Étape de construction de l'image
FROM node:latest as build-stage
WORKDIR /app
COPY /package*.json ./
RUN npm install
COPY / ./
CMD ["npm", "start"]
