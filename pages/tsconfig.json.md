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
			- A `sourceMap` creates a special relationship between the written TypeScript code and the generated [[JavaScript]] code; which makes it easier to debug problems in a browser (such as with using Chrome Dev Tools).
		- `moduleResoultion`
		- `noEmitOnError`
		- `target`
		- `watch`