### Functions in programming

#### Introduction:

In the vast realm of programming languages, functions serve as essential building blocks for organizing and modularizing code. Whether you're a seasoned developer or just starting out, understanding the concept of functions and their significance is crucial. This article aims to demystify functions in programming languages, exploring their purpose, syntax, types, and common use cases. So, let's dive into the world of functions and unlock their potential!

#### Objectives:

- Learn how to define and declare functions in programming languages.
- To Compare the common features and differences in function syntax among the following languages: JavaScript, TypeScript, Dart, PHP, Java, Kotlin, C, C++, Objective-C, Swift, and Golang.
- Acquire the ability to pass arguments to functions and return values from functions.

#### Contents

1. <a name="b1" href="#a1">What are Functions</a>
2. <a name="b2" href="#a2">Syntax and Structure:</a>
3. <a name="b3" href="#a3">Types of Functions</a>
4. <a name="b4" href="#a4">Function Parameters</a>
5. <a name="b5" href="#a5">Functions in different programming languages</a>
6. <a name="b6" href="#a6">Function Use Cases</a>

## <a name="a1" href="#b1">1.</a> What are Functions?

Functions, also known as procedures or subroutines, are blocks of code that perform a specific task. They encapsulate a series of instructions, allowing you to reuse code, improve readability, and enhance code maintainability. By breaking down complex problems into smaller, manageable tasks, functions promote modular programming and enable efficient code reuse.

## <a name="a2" href="#b2">2.</a> Syntax and Structure:

In most programming languages, functions follow a common syntax and structure. They typically consist of a function name, a list of input parameters (arguments), and a return type. Here's a generic representation of a function:

```
 return_type function_name(parameters) {
    // Function body
    // Perform operations
    // Optional return statement

}

```

## <a name="a3" href="#b3">3.</a> Types of Functions

Programming languages offer various types of functions, each serving a specific purpose. Some common types include:

- Void Functions: These functions do not return any value. They perform actions or operations without producing a result.
- Value-Returning Functions: As the name suggests, these functions return a value upon completion. The return type specifies the kind of value returned.
- Recursive Functions: Recursive functions call themselves within their own body, allowing repetitive tasks to be handled efficiently.
- Anonymous Functions: Also known as lambda functions, these functions do not have a formal name and can be passed as parameters or assigned to variables.

```js
//void function call:
function voidFunction() {
  console.log("I'm a void function");
}
```

```js
//value-returning function call
function addNumbers(a, b) {
  // Function that adds two numbers and returns the result.
  let result = a + b;
  return result;
}

// Example usage
let num1 = 10;
let num2 = 5;
let sumResult = addNumbers(num1, num2);
console.log("The sum is:", sumResult);
```

```js
//Recursive function
//Suppose that you have a function called recurse(). The recurse() is a recursive function if it calls itself inside its body, like this:

function recurse() {
  // ...
  recurse();
  // ...
}
```

```js {}
//Anonymous functions
//An anonymous function is a function without a name. The following shows how to define an anonymous function:

(function () {
  //...
});

//Note that if you don’t place the anonymous function inside the (), you’ll get a syntax error. The () makes the anonymous function an expression that returns a function object.

// For example, the following shows an anonymous function that displays a message:
let show = function () {
  console.log("Anonymous function");
};

show();
```

## <a name="a4" href="#b4">4.</a> Function Parameters

Function parameters enable passing data to functions, making them adaptable and flexible. Parameters can be classified as:

- Required Parameters: These parameters must be provided when invoking the function. They define the necessary information for the function to execute correctly.

- Optional Parameters: Also known as default or named parameters, these are not mandatory and come with default values. They provide flexibility by allowing users to customize the function's behavior.

```js
//Required parameters
function multiply(a, b) {
  return a * b;
}

// Here before the function can execute you must provide  the values of  "a" and "b" parameters, if not it will throw an error

// Optional parameters
function multiply(a = 7, b = 1) {
  return a * b;
}

// Here the function can still execute returning the product's default values you asigned to  "a" and "b"
// You can also provide only one parameter and that parameter will represent position of "a"
```

## <a name="a5" href="#b5">5.</a> Functions in different programming languages

<!-- ............................................... -->

````tabs {}

\```dart {}
// In Dart, functions are declared with the return type followed by the function name and parameters. Let's calculate the average of an array of numbers in Dart:
double calculateAverage(List<int> numbers) {
  double sum = 0;
  for (int i = 0; i < numbers.length; i++) {
    sum += numbers[i];
  }
  return sum / numbers.length;
}

\```

\```javascript {title: 'JavaScript'}
// In JavaScript functions can be declared using the function keyword followed by the function name and parameters. Let's consider a real-world problem of calculating the average of an array of numbers in JavaScript:
function calculateAverage(numbers) {
  let sum = 0;
  for (let i = 0; i < numbers.length; i++) {
    sum += numbers[i];
  }
  return sum / numbers.length;
}
\```

\```typescript {title: 'TypeScript'}
// TypeScript, being a superset of JavaScript, offers similar function syntax. However, it adds the ability to specify the return type. Let's solve the same average calculation problem in
function calculateAverage(numbers: number[]): number {
  let sum = 0;
  for (let i = 0; i < numbers.length; i++) {
    sum += numbers[i];
  }
  return sum / numbers.length;
}
\```

\```php {}
// PHP functions are declared using the function keyword, followed by the function name and parameters. Let's find the average of an array of numbers in PHP:
function calculateAverage($numbers) {
  $sum = 0;
  foreach ($numbers as $number) {
    $sum += $number;
  }
  return $sum / count($numbers);
}
\```

\```java {}
// In Java, functions are declared with the return type, followed by the function name and parameters. Let's solve the average calculation problem in Java:
public class AverageOfNNumbers {
   public static void main(String args[]){
      int i,total;
      int a[] = {0,6,9,2,7};
      int n = 5;
      total = 0;

      for(i=0; i<n; i++) {
         total += a[i];
      }
      System.out.println("Average ::"+ total/(float)n);
   }
}

\```

\```swift {}
// In Swift, functions are declared using the func keyword, followed by the function name and parameters. Let's solve the average calculation problem in Swift:
func calculateAverage(numbers: [Int]) -> Double {
  var sum = 0
  for number in numbers {
    sum += number
  }
  return Double(sum) / Double(numbers.count)
}
\```

\```kotlin {}
// Kotlin offers a concise syntax for function declaration, with the fun keyword followed by main and parameters. Let's calculate the sum  of two of numbers in Kotlin:
fun main() {
   val val1 = 10
   val val2 = 15
   println("The two numbers are defined as " +val1 +" and " +val2)
   val sum = val1 + val2
   println("The sum of the two integers is: " +sum)
}
\```

\```c++ {title: 'C/C++'}
// In C and C++ functions are declared with the return type, followed by the function name and parameters. Let's find the average of an array of numbers in C:
#include<stdio.h>

#include<stdio.h>
void add();                                               //Function Declaration
int main()
{
  add();                                                  //Function Calling
  return 0;
}
void add()                                                //Function Definition
{
   int a,b,c;
   printf("\nEnter The Two values:");
   scanf("%d%d",&a,&b);
   c=a+b;
   printf("Addition:%d",c);
}
\```

\```objective-c {}
// In objective c function with its return type, name, and parameter list (if any). The declaration typically appears in a header file (.h) or before the function's usage in the code.

// Here's an example of a simple function in Objective-C that calculates the sum of two numbers:
#import <Foundation/Foundation.h>

@interface SampleClass:NSObject
- (NSNumber *)addA:(NSNumber *)a withB:(NSNumber *)b;
@end
// defining a functions that is used for the addition
@implementation SampleClass

- (NSNumber *)addA:(NSNumber *)a withB:(NSNumber *)b {
float number1 = [a floatValue]; // declariing first number
float number2 = [b floatValue]; // declaring second number
float sum = number1 + number2; // defining sum variable that will be the adddition of two numbers
NSNumber *result = [NSNumber numberWithFloat:sum];
return result;
// the result will be returned
}

@end

int main() {
NSAutoreleasePool * pool = [[NSAutoreleasePool alloc] init];

SampleClass *sampleClass = [[SampleClass alloc]init];
NSNumber *a = [NSNumber numberWithFloat:10.5]; // giving the first number input
NSNumber *b = [NSNumber numberWithFloat:10.0]; // giving the second number input
NSNumber *result = [sampleClass addA:a withB:b];
NSString *resultString = [result stringValue];
NSLog(@"The sum is %@",resultString);

[pool drain];
return 0;
}


\```

\```go {}
// In Golang, functions are declared with the func keyword, followed by the function name, parameters, and return type. Let's calculate the sum  of numbers in Golang.

package main

import "fmt"

func plus(a int, b int) int {

    return a + b
}

func plusPlus(a, b, c int) int {
    return a + b + c
}

func main() {

    res := plus(1, 2)
    fmt.Println("1+2 =", res)

    res = plusPlus(1, 2, 3)
    fmt.Println("1+2+3 =", res)
}

\```

````

<!-- ....................................................... -->

## <a name="a6" href="#b6">6.</a> Function Use Cases

Functions play a vital role in solving real-world problems. Here are some common use cases for functions in programming languages:

- Code Reusability: Functions allow you to encapsulate commonly used code segments, eliminating redundancy and improving maintainability.
- Abstraction: Functions help abstract complex operations into smaller, more manageable units, improving code readability and comprehension.
- Modularization: Breaking down a large program into smaller functions promotes modular programming, making the codebase more organized and easier to maintain.
- Algorithm Design: Functions serve as building blocks for designing algorithms and implementing logical operations.
- Event Handling: Functions are often used to handle events triggered by user interactions, such as button clicks or keystrokes.

### Conclusion:

Functions are the backbone of programming languages, offering modularity, code reuse, and improved readability. By understanding the purpose, syntax, and types of functions, you can harness their power to write efficient, maintainable, and scalable code. So, embrace functions in your programming journey and unlock the true potential of your code.
