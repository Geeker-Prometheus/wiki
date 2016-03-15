# Code Style Guide

## JavaScript Style Guide

参考 [node-style-guide](https://github.com/felixge/node-style-guide)

**Formatting**

* 2 Spaces for indentation
* Use Semicolons
* 80 characters per line
* Use single quotes
* Opening braces go on the same line
* Declare one variable per var statement

**Bad**

	var foo = "bar";
	
	if (true) 
	{
		console.log('true');
	}

**Good**

	var foo = 'bar';
	
	if (true) {
		console.log('true');
	}


## CSS Style Guide

**Formatting**

* Use soft tabs (2 spaces) for indentation
* Prefer dashes over camelCasing in class names.
* Do not use ID selectors
* When using multiple selectors in a rule declaration, give each selector its own line.
* Put a space before the opening brace { in rule declarations
* In properties, put a space after, but not before, the : character.
* Put closing braces } of rule declarations on a new line
* Put blank lines between rule declarations

**Bad**

	.avatar{
    	border-radius:50%;
    	border:2px solid white; }
	.no, .nope, .not_good {
  		/* ... */
	}
	#lol-no {
  		/* ... */
	}
	
**Good**

	.avatar {
  		border-radius: 50%;
  		border: 2px solid white;
	}

	.one,
	.selector,
	.per-line {
  		/* ... */
	}
	
## HTML Style Guide

**TODO**