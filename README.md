# Docker Elasticsearch without volumes

This docker image is very closely based on the official Elasticsearch image,
however it does not use data volumes. We find this useful if you ever want to 
include pre-baked data in your Elasticsearch images, as we do in our hands-on
lab.
