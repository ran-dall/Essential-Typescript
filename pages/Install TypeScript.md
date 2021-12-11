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
  (must be be in project directory)
	- ```shell
	  npm install
	  ```
- Complie all the code samples
  (must be be in project directory)
	- ```shell 
	  npm run tsc
	  ```
- To run a code sample (e.g. `fatArrow.js`)
	- ```shell 
	  node dist/fatArrow.js
	  ```