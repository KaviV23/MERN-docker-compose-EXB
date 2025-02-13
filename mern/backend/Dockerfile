FROM node:23-alpine3.20
WORKDIR /app

COPY . .
RUN npm i
EXPOSE 5050

RUN adduser -D app
USER app

CMD ["npm", "start"]
