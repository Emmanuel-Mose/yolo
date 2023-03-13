FROM node:14.0.0-alpine
#working directory//
LABEL version="1.0"
WORKDIR /client
RUN npm install
COPY . .
EXPOSE 4000
CMD ["npm","start"]