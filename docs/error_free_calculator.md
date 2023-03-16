# Error Free Calculator
A calculator that disables buttons that would result in errors

## C# Version
The first version.  
[Repo here](https://github.com/FireLemons/ErrorFreeCalculator)
![Error Free Calculator C#](./img/error-free-calculator-c-sharp.png)

This calculator achieves evauluation by passing subsections of the expression recursively through the evaluation function  
<figure markdown>
  ![Error Free Calculator Evauluation Recursion Diagram](./img/evaluation_as_recursion_expansion.svg){ style="width: 40em" }
  <figcaption>Example Recursive Call Expansion for an Expression</figcaption>
</figure>

## React Version
[Repo here](https://github.com/FireLemons/ErrorFreeCalculatorReact)  
[See It Live Here](https://firelemons.github.io/ErrorFreeCalculatorReact/)  

### Notable Differences from the C# Version  
 - Evaluation button support prevents users from evaulating when the expression ends in an operator
 - Uses the [shunting yard algorithm](https://en.wikipedia.org/wiki/Shunting_yard_algorithm) eliminating the stack overhead from the recursive method
 - Supports infinity because javascript supports infinity. Try 1 / 0
 - No support for parentheses or functions. Might be added later
 - Rat  
  
### Built With