# Usage

# Creating containers based on this image:
This docker file will load your working folder on /usr/src/app on build.  You only need the `FROM piensa/deeplearning` line on your docker files.

# Developing
For developing, you probably want to load this image using docker-compose.yml and load the current directory in /usr/src/app.

# Contents:
 - [x] ROS
 - [x] Tensorflow 0.11
 - [x] Keras 1.1.0
 - [ ] cuDNN
 - [ ] Support for both GPU and CPU

# Thanks

Dockerfile adapted from:

https://github.com/rwightman/udacity-driving-reader

Thanks @rwightman.
