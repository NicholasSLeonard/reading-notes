# Javascript Functions and Control

We can control the *control flow* of the code by using conditional statements and functions. By default, Javascript will run all code from the top to the bottom, but we can disable certain code blocks by using conditional statements, or organise repetitive code by using functions.

## Functions

A function is a block of code that is given a name and is executed when that name is called. Data can be passed to a function using parameters, and data can be retrieved from a fucntion using a `return` statement.

A function can be created like this:

```
function newFunction(parameter1, parameter2)
{
    let sum = parameter1 + parameter2
    document.write("The sum is " + sum)
    return sum
}
```

A function is called by writing the name of the function, and adding any necessary arguments in the brackets.

```
let num = newFunction(2,3)
document.write("The sum is " + num)
```
In this case `num` is 5.

*Note - variables declared in a function cannot be used outside the function. That data can only be used if it is retrieved using `return`.*

## Operators

There are five main types of Javascript operators (ignoring bitwise), each performing an action on one or more values.

### Arithmetic Operators

Arithmetic Operators do math on a set of values. These are:

- \+	Addition
- \-	Subtraction
- \*	Multiplication
- \**	Exponentiation
- \/	Division
- \%	Modulus (The remainder of division)
- \++	Increment
- \--	Decrement

*Note - Strings can be added together*

### Assignment Operators

The assignment operators are for assigning a value to a variable. This also may include some math similar to the arithmetic operators.

- = Assigns a value to the variable
- += Adds the number on the right to the variable
- -= Subtracts the number on the right from the variable
- *= Multiplies the variable by the number on the right
- /= Divides the variable by the number on the right
- %= Assigns the remainder to the variable if the number on the left is divided by the one on the right
- **= Raises the variable to the power of the number on the left

### Comparison Operators

Compares two values and returns `true` or `false` depending on the comparison.


- == Equal to
- === Equal value and equal type
- != Not equal
- !== Not equal value or not equal type
- \> Greater than
- <	Less than
- \>= Greater than or equal to
- <= Less than or equal to
- ?	Ternary operator

### Logical Operators

Logical operators are used to provide more ability to control code flow, especially in combination with comparison operators.

- &&	If both conditions are `true`, return `true`
- ||	If either condition is `true`, return `true`
- !	    Flip the boolean: If `true`, become `false`. If `false`, become `true`

### Type Operators

Type operators are used to find information about a variable or object.

- typeof - Returns the data type of a variable
- instanceof - Returns `true` if an object is an instance of an object type