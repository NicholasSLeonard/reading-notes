# JavaScript intro

JavaScript is a lightweight programming language that compiles the code at run time. Often used with HTML to create a webpage with interactive elements.
A script can be created in a HTML file by using the `<script>` tag.

## Variables

Variables can be declared by simply by using `let`. For example:

``` 
let varName = "dataValue" 
```
A datatype declaration is not needed for this.

Math can be done on these variables like this:

```
let varNum = 10
varNum = varNum + 5
```

After this, `varNum` is now 15.

## Simple IO

A variable can be assigned a value by the user by using the `prompt()` function.

```
let variable = prompt("Your message to the user goes here!")
```

A message can be displayed by using:

```
document.write("The output goes here!", variable)
```

The output will be printed on the page depending on where the script is written/called.