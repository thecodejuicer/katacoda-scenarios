# Do Something Useful
Operators: they make programming useful. Without them programs would do, pretty much, nothing. What is it? 
An **operator** is a symbol that performs an action on operands. In Java, it can be one, two or three operands.

What is an operand? It's the thing being operated on by the operator. That could be a few different things. In its simplest form, it would be, perhaps, a number. For example:  
`1 + 2`
1 and 2 are operands. &quot;+&quot; is the operator.

The operands don't have to be numbers. They could be variables, or even methods (covered in another lesson). They can even be the result of other operators!

Before we get into those details, let's talk about the different types of operators.

## Unary Operators
Unary operators operate on _one_ operand.

You've already seen one in the previous lesson with the increment operator: ++  
It simply adds 1 to the operand.  
```
int someValue = 0;
someValue++; // Now someValue equals 1.
```

Unary operators can use **prefix** or **postfix** notation.  
**Prefix** notation has the operator _before_ the operand. `++someValue;`  
**Postfix** notation has the operator _after_ the operand. `someValue++;`

Does the order matter? It can.
Try it out. Let's write a simple program to see what happens when we print values with prefix vs. postfix.
Copy this skeleton code to the editor window.
<pre class="file" data-filename="Operators.java" data-target="replace">
public class Operators {
  public void main(String args[]) {
    // Your code will go here.
  }
}
</pre>