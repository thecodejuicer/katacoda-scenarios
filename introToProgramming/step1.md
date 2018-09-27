For this first lesson, you are going to write (rather, complete)
a historical and obligatory introductory program known as &ldquo;Hello, World!&rdquo;. Why is it historical and obligatory?
Because almost every book, tutorial and course in the world of computer programming, begins with the &ldquo;Hello, World!&rdquo;
    program. It is tradition. <a href="https://en.wikipedia.org/wiki/%22Hello,_World!%22_program">(Wikipedia article)</a>

What, you ask, is &ldquo;Hello, World!&rdquo; anyhow? It simply prints &ldquo;Hello, World!&rdquo; to the screen.
It isn't terribly exciting. But, it does give us a chance to talk about some important fundamentals.

Since we're using Java&trade;, there are a few things every program needs. In your editor is a blank file named <code>HelloWorld.java</code>.
The first thing it needs is a <code>class</code> definition. Make it look like this:
<pre class="file">
public class HelloWorld {}
</pre>

Try compiling it by typing `javac HelloWorld.java`{{execute}} into the terminal. Make sure you press enter to execute the command.

If you typed everything correctly, it will compile your `.java` file into a `.class` file. 
This is the [Java&trade; bytecode](https://www.javaworld.com/article/2077233/core-java/bytecode-basics.html "Java Bytecode Information") file. 

Run it in the terminal by typing `java HelloWorld`{{execute}} to see what happens&hellip;

Yeah. It's an error. We'll talk about that in the next step.