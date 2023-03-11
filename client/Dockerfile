FROM node:13.12.0
LABEL version="1.0"
WORKDIR /app
COPY package*.json ./
RUN npm ci
COPY . .
ENV NODE_ENV=production
ENV PORT=3000
EXPOSE 3000
CMD [ "npm", "run", "start" ]