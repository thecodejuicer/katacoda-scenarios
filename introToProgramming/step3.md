Now that you have a valid Java application, we&apos;ll make it do something. It is going to print "Hello, World!" to the terminal.
Add a line of code to the `main` method:

<pre class="file">
&hellip;
  public static void main(String[] args) { 
    // Send a message to standard output 
    System.out.println("Hello, World!");
  }
&hellip;
</pre> 

Compile your program (`javac HelloWorld.java`{{execute}}).

Execute it (`java HelloWorld`{{execute}}). The terminal should happily display the traditional message. If you see an error instead, check your code. Something isn't right.

For reference, it should look something like this:
<pre class="file">
public class HelloWorld {
  
  public static void main(String args[]) {
    System.out.println("Hello, World!");
  }
  
}
</pre>