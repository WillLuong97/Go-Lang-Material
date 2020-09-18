# Go Language

## What is Go? 

- Go or Golang is an open source programming language. It is statically typed and produces compiled machine code binaries. 
 
- Go is created and developed by Google in 2009 and realsed to the public in 2010. Go is widely used in production at Google and in many other organization and open-source projects.

## Application

+ Cloud Services: 

As the creator of Go, Google is using this language to provide cloud infrastructure: it offers top performance and scalability to the Google Cloud Platform. But there are even more well-known cloud businesses out there using Go for the same reasons: Dropbox, Terraform, Kubernetes, and Docker

+ Media Platform:

YouTube, SoundCloud, and Netflix chose Go to fight with high loads on their sites. SoundCloud uses this language for deploying some internal services within their complex projects.

+ News Outlets:

Back in 2012, the BBC (yep, it was a surprise to us too) started using Go for backend development and some of the elements of their internal analytics services.

+ On-demand services: 

The taxi giant Uber was looking to improve map processing speeds as people loaded geofence lookups, sending literally thousands of queries per second. Go helped Uber significantly reduce the timing of providing services to users, which was much appreciated by users.

## Why use Go? 

+  Spend less time and money to develop an app:

Apps created in Go actually compile to native machine code and don’t need any interpreter or virtual machine. 

+ Use Go for a range of apps: 

Go is a really flexible language, able to solve a lot of problems. You can use it for system and network programming, big data, machine learning, audio and video editing, and more.

+ Get more performance and a wider audience for your app

Similarly to C or C++, Go is a compiled language and doesn’t require any interpretation. Correspondingly, the absence of an interpreter frees up power and gives a Go-built app way more performance, which will surely be appreciated by users. Moreover, Go knows how to properly manage allocated memory. 

+ Worry less about the app crashing: 

Go was created to use the full potential of multiple cores. Moreover, the language can properly use all the processor resources, so it’s perfect for running an app in the background as a single process. This is possible thanks to goroutines, which are used instead of threads and require much less RAM due to their non-system thread nature. This is why the risk of a Go app crashing due to lack of memory is lower. 

+ Easily find Go developers for your project: 

Go is blowing up






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
