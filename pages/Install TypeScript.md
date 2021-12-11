- Pull Node.js container for Docker Registry
	- ```bash
	  podman pull registry.hub.docker.com/library/node:latest
	  ```
- Build `essential-typescript` container
	- ```bash 
	  podman build -t essential-typescript:latest .
	  ```
- Run `essential-typescript` container
	- ``` bash
	  podman run --name essential-typescript --rm -ti \
	  essential-typescript:latest /bin/bash
	  ```