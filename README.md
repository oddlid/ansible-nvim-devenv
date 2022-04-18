The intention here is to automate as much as possible of setting up a working development environment for nvim, supporting mainly Golang, but also some other common languages.

Starting out, I don't know much about ansible, to this will be a work in progress until I figure things out.

First goal is to make it work in a Docker container based on debian:bullseye with ansible and git as the only preinstalled packages.
Later, I want it to work on Debian in WSL, and finally on macOS.

