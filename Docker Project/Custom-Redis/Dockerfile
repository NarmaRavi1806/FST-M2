# Set a base image
FROM alpine:3.18.4
# Set a working directory
WORKDIR /user/app
# Run commands
RUN apk add --update redis
# Set a default image
CMD [ "redis-server"]