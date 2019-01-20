# Variables:
## Create a Variable: var

```javascript
ar myName = 'Arya';
console.log(myName);
// Output: Arya
```
Let's consider the example above:

1. var, short for variable, is a JavaScript keyword that creates, or declares, a new variable.

2. myName is the variable's name. Capitalizing in this way is a standard convention in JavaScript called camel casing. In camel casing you group words into one, the first word is lowercase, then every word that follows will have its first letter uppercased. (e.g. camelCaseEverything).

3. = is the assignment operator. It assigns the value ('Arya') to the variable (myName).

4. 'Arya' is the value assigned (=) to the variable myName. You can also say that the myName variable is initialized with a value of 'Arya'.

5. After the variable is declared, the string value 'Arya' is printed to the console by referencing the variable name: console.log(myName).

#### There are a few general rules for naming variables:

* Variable names cannot start with numbers.

* Variable names are case sensitive, so myName and myname would be different variables. It is bad practice to create two variables that have the same name using different cases.

* Variable names cannot be the same as keywords.

## Create a Variable: let

The let keyword signals that the variable can be reassigned a different value. Take a look at the example:

```javascript
let meal = 'Enchiladas';
console.log(meal); // Output: Enchiladas
meal = 'Burrito';
console.log(meal); // Output: Burrito
```

Another concept that we should be aware of when using let (and even var) is that we can declare a variable without assigning the variable a value. In such a case, the variable will be automatically initialized with a value of undefined:

```javascript
let price;
console.log(price); // Output: undefined
price = 350;
console.log(price); // Output: 350
```

Notice in the example above:

* If we don't assign a value to a variable declared using the let keyword, it automatically has a value of undefined.

* We can reassign the value of the variable.
