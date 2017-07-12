# Base Image

### In Short
This image is optimized for use with any basic website/web application.

### Usage
This is a first stage image and should be used to build the second stage image.

### Dockerfile

+ Define the base image as **phusion/baseimage:0.9.22**, an excellent minified Ubuntu 16.04 LTS Docker container.
+ Add user container.
+ Install and update the core components for this new container like unzip, zip, git-core.
