- Most of the time, you'll want to put your compiler options into _tsconfig.json_, for easier and central usage.
- If the file exists, `tsc` will find the find in the root project directory and apply the configuration found in the _tsconfig.json_.
- Sample `tsconfig.json`
	- ```json
	  {
	      "complierOptions": {
	          "outDir": "./dist",
	          "baseUrl": "src",
	          "sourceMap": true,
	          "moduleResolution": "node",
	          "noEmitOnError": true,
	          "target": "es5",
	          "watch": true
	      }
	  }
	  ```
		- `outDir`
			- This is the location of where the compiled code should go.
		- `baseUrl`
			- This would be where the source code is located.
		- `sourceMap`
			- A `sourceMap` creates a special relationship between the written TypeScript code and the generated [[JavaScript]] code; which makes it easier to debug problems in a browser (such as with using Chrome Dev Tools) by displaying the related TypeScript code.
		- `moduleResoultion`
			- You will use `import` and `export` statements in TypeScript.
			- You must specify which module system you would like TypeScript to use.
			- If using `"node"`, then it will use the rules defined by `node`.
		- `noEmitOnError`
			- This option prevents the generation of [[JavaScript]] code if there is an error detected.
		- `target`
		- `watch`