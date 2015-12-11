# docker-baseimage

Container to be a baseimage for deployment of (multi-service) containers
This container is based on phusion/baseimage, with runit as startup script.

You can use dockerize -template source:destination in a my_init.d file, to create configfiles on startup.

Please do not change the startup CMD, use runit service directory instead
