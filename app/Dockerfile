FROM node:alpine
LABEL Description="Image I will use to Practise Argo" Author="Mncedisi" JavaScriptCode="https://github.com/eMahtab/node-express-hello-world"
ENV DEBIAN_FRONTEND=noniteractive
# RUN apk update && apk add nodejs-lts
WORKDIR /app
COPY package.json .
RUN npm install
COPY . .
CMD ["npm",  "start"] 
EXPOSE 3000