FROM alpine:3.15.0
LABEL version="1.0.0" maintainer="Michel Bataillon" os="alpine" distro="stro"
ENV CONTAINER_USER "Michel"
RUN adduser -S -D $CONTAINER_USER 
CMD echo "hello-alpine, I’m $CONTAINER_USER and this is a container from my first image"