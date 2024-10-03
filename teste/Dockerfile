FROM ubuntu:20.04
WORKDIR /app
COPY . .
RUN apt-get update && apt-get install -y curl
ENV NODE_VERSION=14
EXPOSE 8080
CMD ["npm", "start"]
ENTRYPOINT ["node", "app.js"]
ARG VERSION=latest
VOLUME /data
LABEL version="1.0" maintainer="Adrian"