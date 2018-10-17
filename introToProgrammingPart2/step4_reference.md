## Reference Data Types
Using reference types opens up the fun in programming. Really, it's just an identifier that points to a memory address. But what that memory address holds is the important part.

We've already worked with one important reference type: the `String`. A String identifier points to a location in memory which holds characters (the primitive).

Let's say we assign &quot;Hi&quot; to a String named &quot;greeting&quot;, and it gets stored starting at memory address 20. The value of the greeting will be 20, not &quot;Hi&quot;
The value we assigned takes up 4 bytes (32 bits since a character is 16 bits). This assumes a byte is 8 bits, which it typically is.

In memory, it would look something like this:
<pre>
    greeting
           &darr;
address:  | 20 & 21 | 22 & 23 |
  value:  |   'H'   |   'i'   |
</pre>