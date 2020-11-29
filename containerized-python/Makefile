# Walkthrough of https://www.docker.com/blog/containerized-python-development-part-1/

# build image
.PHONY: build-image
build-image:
	sudo docker build -t myimage ./app
	sudo docker images

# run
.PHONY: run
run:
	sudo docker run -d -p 80:5000 --name example myimage
	sudo docker ps

# stop
.PHONY: stop
stop:
	sudo docker stop example
	sudo docker ps


