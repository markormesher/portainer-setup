FROM node:dubnium
WORKDIR /app
COPY ./package.json ./yarn.lock ./
RUN yarn
COPY ./public/ ./public/
EXPOSE 8080
CMD ["npx", "http-server"]
