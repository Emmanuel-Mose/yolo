FROM node:alpine
LABEL version="1.0"
WORKDIR /app
COPY package*.json ./
RUN npm ci
COPY . .
ENV NODE_ENV=production
ENV PORT=5000
EXPOSE 5000
CMD [ "npm", "run","start" ]