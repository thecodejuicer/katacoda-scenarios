## Variables
Obviously we can&apos;t do very interesting things with literal values. A calculator that only calculates the same equation, every time, is useless.

Enter variables! A variable is simply a named object (identifier) that holds a value. And that value can change as we need.

The HelloWorld program does have one variable in it. We didn&apos;t use it, but it&apos;s there:
<pre class="file">String[] args</pre>
`args` is the variable&apos;s name (identifier), and `String[]` is the _type_ of data it can hold. In this case, it is an array of Strings (the square brackets here are a special notation defining an array: more on this later).

Let&apos;s alter the program to ask us our name and then greet us appropriately. Replace `System.out.println("Hello, World!");` with some new lines of code:
<pre class="file">
    // This will hold the name you enter.
    String yourName;
    
    System.out.println("Type your name, please: ");
    
    // This will wait for you to type something, and store it in yourName when you hit Enter.
    yourName = System.console().readLine();
    
    System.out.println("Nice to meet you, " + yourName);
</pre>

### An Explanation
The program just got a little more exciting&hellip; right? It will say your name now! Well, as long as you actually type your name.

Now we&apos;re getting fancy, using a new variable named `yourName`. We don&apos;t have to type our name multiple times. We don&apos;t have to tell the program what it is ahead of time. It asks, and then uses what we give it.

Go ahead and try it out. Compile HelloWorld.java one more time. In case you forgot how, type `javac HelloWorld.java`{{execute}}. Then run it (hint: `java HelloWorld`{{execute}}).

If your program didn&apos;t compile, make sure it looks similar to this:
<pre class="file">
public class HelloWorld
{
    public static void main(String[] args) {
        // This will hold the name you enter.
        String yourName;
        
        System.out.println("Type your name, please: ");
        
        // This will wait for you to type something, and store it in yourName when you hit Enter.
        yourName = System.console().readLine();
        
        System.out.println("Nice to meet you, " + yourName);
    }
}
</pre>

## Comments
You may have noticed something new here (I hope). Lines that start with `//`. These are called comments.
The compiler completely ignores them. They are used for the programmer to help clarify what code is doing (normally).

