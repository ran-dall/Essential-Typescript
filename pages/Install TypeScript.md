- Pull Node.js container for Docker Registry
	- ```bash
	  podman pull registry.hub.docker.com/library/node:latest
	  ```
- Run Node.js container
	- ``` bash
	  podman run --name typescript --rm -ti \
	  node:latest /bin/bash
	  ```
- Install TypeScript
	- ``` bash
	  npm i typescript -g
	  ```
		- Local Install
			- ```bash
			  npm i typescript --save-dev
			  ```