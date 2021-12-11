- Every _node.js_ must have a `package.json` file. TypeScript is not any different.
- Sample `package.json`
	- ```json
	  {
	  	"name": "ts_essentials",
	      "version": "1.0.0",
	      "description": "TypeScript Essentials",
	      "scripts": {
	      	"tsc": "tsc"
	      },
	      "author": "Yakov Fain",
	      "license": "ISC",
	      "devDependencies": {
	      	"tslint": "~5.1.0",
	          "typescript": "^2.4.0"
	      }
	  }
	  ```
	- `scripts`
		- Used for providing alias to commands.
		-
		- `tsc`
			- For compiling locally with `tsc`
				- ```shell
				  npm run tsc
				  ```
	- `devDependencies`
		- Packages that are required in the development process.
	- `dependencies`
		- Packages that are required at runtime in any environment.