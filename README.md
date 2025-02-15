# Smaller_Docker_Images
https://learnk8s.io/blog/smaller-docker-images

#You can build the image with:
docker build -t node-vanilla .

#And you can test that it works correctly with:
docker run -detach --publish 3000:3000 node-vanilla

##ERROR: /bin/sh: 1: [npm,: not found