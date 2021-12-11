alias:: Fat Arrow,

- A [[Fat Arrow]] function (`=>`) is the same as a _Anonymous function_ in **TypeScript**.
	- Fat Arrow Function
		- ```javascript
		  let getname = () => 'John Smith';
		  console.log(`The name is ` + getName());
		  ```
	- Anonymous Function
		- ```typescript
		  var getName = function () { return 'John Smith'; };
		  console.log("The name is" + getName());
		  ```