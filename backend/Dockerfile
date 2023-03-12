FROM node:14.0.0-alpine
#working directory//
LABEL version="1.0"
WORKDIR /backend 
RUN npm install
COPY . .
EXPOSE 5000
CMD ["npm","start"]