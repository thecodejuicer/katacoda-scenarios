# Data Types
There are two kinds of data types in Java: &quot;primitive&quot; and &quot;reference&quot;. Let's start with primitive types.

## Primitive Data Types
Variables for primitive types hold a value. This is typically a numeric value, with one exception: boolean (true or false).
The majority of Java's primitive types are integral (no decimal) and we'll cover those first.

### Integral Types
`long` is the largest of the integral types. It holds 64 bits of information and ranges from -9,223,372,036,854,775,808 to 9,223,372,036,854,775,807 (that's **quintillion**). When declaring a `long` value, the number needs an "L" suffix.    
Example: `long bigNumber = 19283958329L;`  
Also note: Numbers do not use thousands separators. Only digits.

`int` is a bit smaller, coming in at 32 bits. This is more commonly used and can represent values between -2,147,483,648 and 2,147,483,647. This is a commonly used integral primitive type.  
Example: `int playerScore = -1052;`

`short` is smaller yet. This one gives you 16 bits to play with. Are you sensing a pattern yet? Each type is half the size of it's larger counterpart. With 16 bits you get numbers ranging from -32,768 to 32,767.  
Example: `short notLong = 0xF32; // This is hexadecimal notation for 3890.`

`byte` is the smallest integral sibling. It's only 8 bits tall, giving an effective range of -128 to 127. Yes, it is small. Yes, it can be useful.  
Example: `byte babySize = 37;`

`char` represents a unicode character with 16 bits. Yes, it's an integral type. For a letter. And it ranges from 0 to 65,535. &quot;Wait a second&hellip;&quot;, you say. &quot;That 16-bit short has a different range.&quot; Yes, but the `char` data type is unsigned. It is always positive. And it always holds **one** character. Just one.  
Example: `char letterA = 'A';`
