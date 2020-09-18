# Go Language

## What is Go? 

- 

## Application
- 

## Why use Go? 
-

## Go structure: 

### Print to Console and fmt: 

- Printf: print out the element

- Sprintf: print out the element but also store it into a variable

### Types and variables: 
- You can also choose what base to print a particular integer out

    +  %b (base 2)
    +  %o (base 8)
    +  %d (base 10)
    +  %x (base 16)


- Floating points: 

    + %e (scientific notation)
    + %f / %F (decimal no exponent)
    + %g (for large exponents to represent the whole number)

- Strings: 

    + %s (print out a default string)
    + %q (double quoted string)

- Const vs Var: 
    + They are both used for variable initialization
    + Variable delcared under "var" can be changed 
    + Variable delared under "const" cannot be changed

### Packages: 
- To import a package into Go, we use this comand

```
import "fmt"
```

- To import multiple packages into Go, we use this comand

```
import ("fmt"
        "math")
```

- Note: when import multiple packages into the Go file, we will have placed each packages vertically.


### Function: 

- Function in Go is recognized by the compiler with the "func" keyword

- The way function is declared in Go is similar to other languages, you will create a function name, then in
the function will recieve input value  + its type and we will also have to specifiy the return type of the function

- Calling the function is similar to other languages as you just need to call the function name and pass in the value

```
func functionName(value1 type, value2 type) type (return value) {
    //add some code here
}
```

### Array and Slices:

- To create an array
