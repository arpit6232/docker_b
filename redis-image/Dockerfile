# use an existing docker image as a base 
FROM alpine 
# Download and install a dependency 
RUN apk add --update redis 
RUN apk add --update gcc
# Tell the image to fo when it starts as a container 
CMD ["redis-server"]