# To copy an Image present in Docker Hub Selecting docker gcc image
FROM gcc:4.9
#FROM node:alpine

# To copy all the fils in the app folder in the image.
COPY . /app

# To Set Work directory so that further commands will be run from that Directory 
WORKDIR ./app

# To run Command inside image
RUN g++ main.cpp -o myapp
#CMD node app.js

# Run command
CMD ["./myapp"]




# RUN is an image build step, the state of the container after a RUN command will be committed to the container image.
# A Dockerfile can have many RUN steps that layer on top of one another to build the image.

# CMD is the command the container executes by default when you launch the built image. A Dockerfile will only use
# the final CMD defined. The CMD can be overridden when starting a container with docker run $image $other_command.