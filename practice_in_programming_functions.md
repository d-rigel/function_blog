```yaml {index:0, type: meta}
title: The practice of Functions in different coding languages
slug: functions-in-different-coding-language-practice
during: 3 mins
```

```markdown {during: 1000}
### Subjects of this unit:

1. To learn the concept of Functions
2. To know how to write functions to perform some computing tasks and display the output on a computer's screen or console
```

```markdown {type: control, action: continue}
Before you can proceed with the task below, it is essential to watch the video and blog listed below, as the information provided in them will be useful in completing the task. By clicking on these links, a new window will open, helping you access the necessary resources whenever you need them.

- YouTube Video: [The Future of Coding Education: Functions](https://www.youtube.com/watch?v=VnyeINxAAC8)
- Blog: [Functions in different coding languages](https://juniorit.ai/resource/blog/functions-in-different-coding-language-practice)

Are you ready?

Press the button below to continue.
```

```markdown {during: 1000}
### 1. What is Functions in coding?

Functions, also known as procedures or subroutines, are blocks of code that perform a specific task. They encapsulate a series of instructions, allowing you to reuse code, improve readability, and enhance code maintainability. By breaking down complex problems into smaller, manageable tasks, functions promote modular programming and enable efficient code reuse.
```

```markdown {type: control, action: continue}
Press the button below to continue.
```

```markdown {}
Let's ask AI to write a function to perform "addition" computation in Dart language
```

```markdown {type:chat, action: code, button: "Ask AI", dropdown: false}
Can I have a "function to add 5 and 9" in dart?
```

```markdown {type: control, action: continue}
AI has generated an "Addition computation in Dart application for you, please press the "Run" button under the code editor to test it.

Once you have finished, press the button below
```

```markdown
Now, let's give it a try. Please use the 'Ask AI' box below to ask AI to write a function "to multiply two numbers" in JavaScript.
```

```markdown {type:chat, action: code, button: "Ask AI", dropdown: false}

```

```markdown
### 2. Functions in different language
```

```swift {type:code, action: none}
func addNumbers(number1: Int, number2: Int) -> Int {
    return number1 + number2
}

let num1 = 10
let num2 = 20
let sum = addNumbers(number1: num1, number2: num2)

print("The sum of \(num1) and \(num2) is: \(sum)")
```

```yaml {type: form, action: test, title: "Test"}
- type: radio
  name: a
  label: "Please check the code above. Which programming language is it most likely written in?:"
  options:
    - C/C++
    - Dart
    - JavaScript
    - PHP
    - Swift
  value: [4]
```

```php {type:code, action: none}
function multiplyNumbers($number1, $number2) {
    return $number1 * $number2;
}

$num1 = 10;
$num2 = 20;
$product = multiplyNumbers($num1, $num2);

echo "The product of $num1 and $num2 is: $product";

```

```yaml {type: form, action: test, title: "Test"}
- type: radio
  name: b
  label: "Please check the code above. Which programming language is it most likely written in?:"
  options:
    - Java
    - Kotlin
    - Objective-C
    - PHP
    - C/C++
  value: [3]
```

```markdown
One coding language is an interpreted programming language, that is commonly used for a variety of applications, including scientific computing, artificial intelligence, data analysis, and more.
```

```yaml {type: form, action: test, title: "Test"}
- type: radio
  name: c
  label: "Which programming language is it most likely?:"
  options:
    - PHP
    - Python
    - Objective-C
    - Java
    - C++
  value: [1]
```

```markdown
### 3. Choose the correct output

Please read the code below to see which content will be printed in the output. Then, run the Python code below. Check the output to see if you are correct, and select the correct answer.
```

```python {type:code, action: run}
def calculate_average(numbers):
    total = sum(numbers)
    average = total / len(numbers)
    return average

# Example usage
number_list = [4, 5, 7, 5]

result = calculate_average(number_list)
print("The average is:", result)
print("The average is:", 5.94)
print("The average is:", 8.90)
print("The average is:", 3.55)

```

```yaml {type: form, action: test, title: "Test"}
- type: radio
  name: d
  label: "Please select the correct output from the function:"
  options:
    - 3.55
    - 5.94
    - 5.25
    - 8.90
  value: [2]
```

```
Read the TypeScript code below, then select the correct answer
```

```typescript {type:code, action: none}
function reverseString(str: string) {
  // This is a function that converts a string to a lower case and reverse the string
  // E.g Hello = olleh
  const result = str.toLowerCase().split("").reverse().join("");
  return result;
}

// const str: string = "I love JuniorIT.AI";
const result: string = reverseString("I love JuniorIT.AI");

console.log("I Junior.AI love");
console.log("junior.AI i love");
console.log(result);
console.log("i junior.ai love");
console.log("evol i ai.roiju");
```

```yaml {type: form, action: test, title: "Test"}
- type: checkbox
  name: e
  label: "Please select the correct string, that will be printed in the code above:"
  options:
    - I Junior.AI love
    - junior.AI i love
    - ia.tiroinuj evol i
    - i junior.ai love
    - evol i ai.roiju
  value: [2]
```

```
Functions in programming can perform various types of operations depending on the programming language and the specific implementation. Choose the ones we have used in this unit.
```

```yaml {type: form, action: test, title: "Unit Test"}
- type: checkbox
  name: f
  label: "Please select the function operations we have used in this unit:"
  options:
    - system monitoring
    - Mathematical Operations
    - Input/Output Operations
    - Data Manipulation
    - Creative writing

  value: [1, 2, 3]
```

```markdown
### 4. Summary:

Here are some AI coding prompts you need to know after this unit:
```

```yaml {type: list, default: true}
- Can I have a "function to add 5 and 9" in dart?
- Ask AI to write a function "to multiply two numbers" in JavaScript
- How to write functions in swift?
- What are the difference between JavaScript and TypeScript?
```

```markdown
You can press the hand icon to try these prompts now
```

```markdown {type: control, action: continue}
Or you can use JuniorIT.AI's Playground any time at [https://juniorit.ai/playground](https://juniorit.ai/playground)

Once you finished this practice, please press the continue button below
```

```yaml {type: form, action: test, title: "Unit Test"}
- type: checkbox
  name: g
  label: "Please select the correct description below:"
  options:
    - I don't need to know one coding language well, but I need to know the language name and its major usage, so that I can instruct AI to work for me when needed.
    - I don't need to know the exact names of each language's system functions, but I need to understand their functionalities, so that I can instruct AI to use them.
    - Learning and using multiple coding languages can be made easy with AI's assistant. All I need to know are the coding concepts.
    - I can use JuniorIT.AI's Playground to write or test my code anytime or ask AI for any coding questions.
  value: [0, 1, 2, 3]
```

```markdown {type: control, action: end}
Congratulations!

You have successfully completed this unit of the coding course with JuniorIT.AI.

If you haven't pre-signed up for a membership with JuniorIT.AI, please do so now by visiting [https://juniorit.ai/auth/pre-register](https://juniorit.ai/auth/pre-register)

To stay updated on our future courses, please subscribe to our official YouTube Channel at [https://www.youtube.com/@junior-it-ai](https://www.youtube.com/@junior-it-ai)
```
