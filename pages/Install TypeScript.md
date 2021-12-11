- Pull Node.js container for Docker Registry
	- ```bash
	  $ podman pull registry.hub.docker.com/library/node:latest
	  ```
- Run Node.js container
	- ``` bash
	  $ podman run --name typescript --rm -ti \
	    --network=host \
	    diez:10 /bin/bash
	  
	  ```