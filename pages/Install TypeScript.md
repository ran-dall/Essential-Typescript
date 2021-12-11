alias:: TypeScript Container

- Pull Node.js container for Docker Registry
	- ```shell
	  podman pull registry.hub.docker.com/library/node:latest
	  ```
- Build `essential-typescript` container
	- ```shell 
	  podman build -t essential-typescript:latest .
	  ```
- Run `essential-typescript` container
	- ``` shell
	  podman run --name essential-typescript --rm -ti \
	  -v "$(pwd)":/code \
	  essential-typescript:latest /bin/bash
	  ```
## Code Samples
- Run [[TypeScript Container]]
- Clone `git` repo
	- ```shell
	  git clone https://github.com/yfain/ts
	  ```
- Install the project dependencies
	- ```shell
	  n
	  ```