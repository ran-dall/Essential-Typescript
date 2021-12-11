alias:: Fat Arrow,

- A [[Fat Arrow]] function (`=>`) is the same as a _Anonymous function_ in **TypeScript** (and [[JavaScript]] ).
	- Fat Arrow Function
		- ```typescript
		  let getname = () => 'John Smith';
		  console.log(`The name is ` + getName());
		  ```
		- Typically, `cost` is more used than `let` with [[Fat Arrow]] functions.
	- Anonymous Function
		- ```typescript
		  var getName = function () { return 'John Smith'; };
		  console.log("The name is" + getName());
		  ```