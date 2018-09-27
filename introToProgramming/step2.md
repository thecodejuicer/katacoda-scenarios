You should have seen this in the previous step:

```
Error: Main method not found in class HelloWorld, please define the main method as:
   public static void main(String[] args)
or a JavaFX application class must extend javafx.application.Application
```

Although the source code is valid, it is not a _valid_ Java application. 
The virtual machine is nice enough tell us the problem&mdash;we are missing the entry point for the program. `public static void main(String[] args)` is the first method the Java virtual machine runs (more about methods later). 

Add it inside the class like so:
<pre class="file">
public class HelloWorld {

  // This is the program entry point.
  public static void main(String[] args) {  
    // TODO: We'll put more here in a moment.
  }
  
}
</pre> 

Side note before we continue: you may have noticed the lines starting with `//`. These are just comments. The compiler ignores them. They are for the programmer. Yes, we'll talk more about this later.

Compile your program again (`javac HelloWorld.java`{{execute}}). It should compile without any problem. If you get an error, make sure you aren&apos;t missing something like a &ldquo;curly brace:&rdquo; `{` or `}`.
_(This has to work before you can move on to the next step)_

When it compiles you can run it again (`java HelloWorld`{{execute}}) to find there is no error. There is also no output. That&apos;s next.