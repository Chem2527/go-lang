## 1. Simple Go Program to Print Hello Message
```bash
package main // Defines the package name, which in this case is 'main' (the entry point of the Go program)

import "fmt" // Imports the 'fmt' package, which is used to format and print output to the console

func main() { // The main function is the entry point of the Go program. It gets executed when you run the program.

    fmt.Println("Hello, im saikrishna!") // Prints the string "Hello, im saikrishna!" to the console, followed by a new line

    fmt.Println("Hello, im saikrishna!") // Prints the same string again, followed by a new line

}
```
## 2. Print Arithmetic Expression Result
```bash
// Declare the main package. This is the entry point of the Go program where it starts executing.
package main

// Import the 'fmt' package which provides formatted I/O functions like Println.
import "fmt"

// This is the 'main' function, where the execution of the program begins.
func main() {
    // fmt.Println prints out the string and then the result of the expression.
    // It will print: "1 + 9 = ", followed by the result of the expression 1 + 2, which is 3.
    fmt.Println("1 + 9 =", 1+2)
}
```
