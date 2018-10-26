# Operators continued
## Binary Operators
Binary operators operate on _two_ operands (thus the 'bi' prefix).

The binary operators all use *infix* notiation. That means the operator goes between the operands. Like this:
<pre class="file">
int myOperand;
myOperand     =     293_378_218;
  &uarr;           &uarr;          &uarr;
operand    operator   operand
</pre>

### Sidebar: whitespace
Notice there are some extra spaces between the operands and the operator. I put them there for readability.  
In Java, whitespace doesn't matter. 
It is ignored. You can put as many spaces, tabs and new lines between statements as you wish. Just keep in mind, readability is important.  
The example above would work if it was written like this:
<pre class="file">
int myOperand;
myOperand = 293_378_218;
</pre>
Or this:
<pre class="file">
int              myOperand
        ;

        myOperand       =
    293_378_218;
</pre>
I'm sure you see how poorly formatted code is much harder to follow. Even for such a simple program!
### Case Sensitivity
Another worthwhile note: **case matters**\! MyVariable is not the same as myVariable. Java is picky about case.

### Back to operators
#### Assignment
One of the most important binary operators is the **assignment operator**. You've already used it without knowing it. Or maybe you did know it. It looks like this: **=**

##### Declaration
The assignment operator _gives value_ to a **declared** variable. That's a word to know (declared). Before you can assign a value to something, the thing needs to be declared. You've been doing this already too.  
<pre class="file">
// declaring an integer variable named myOperand.
int myOperand;
</pre>