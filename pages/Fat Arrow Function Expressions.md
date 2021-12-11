alias:: Fat Arrow,

- A [[Fat Arrow]] function (`=>`) is the same as a _Anonymous function_ in **TypeScript** (and [[JavaScript]] ).
	- Fat Arrow Function
		- ```typescript
		  let getname = () => 'John Smith';
		  console.log(`The name is ` + getName());
		  ```
		- Typically, `cost` is more used than `let` with [[Fat Arrow]] functions.
		- [[Fat Arrow]] functions not only offers a shorter syntax, but makes the meaning of the `this` pointer predictable.
	- Anonymous Function
		- ```typescript
		  var getName = function () { return 'John Smith'; };
		  console.log("The name is " + getName());
		  ```