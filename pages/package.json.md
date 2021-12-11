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
		- Commands declared in the `scripts` section in `package.json` will be available for `npm run <command>`.
			- `tsc`
				- For compiling locally with `tsc`
					- ```shell
					  npm run tsc
					  ```
	- `devDependencies`
		- Packages that are required in the development process.
		- Packages can be re-declared in `devDependencies` to ensure that a certain version is used locally for a project, instead of a global version. TypeScript is a good example, if you want to use a specific version of TypeScript.
	- `dependencies`
		- Packages that are required at runtime in any environment.