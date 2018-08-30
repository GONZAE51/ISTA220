
1. What is an exception?
 most other modern object-oriented languages don’t handle errors in this manner; it’s just too painful. Instead, they use exceptions
 flow of the program , its a response to the error of the program

2. What happens in a try block if the program executes without errors?
When the code runs, it attempts to  execute all the statements in the try block, and if none of the statements generates an  exception, they all run, one after the other, to completion

3. How does the catch mechanism work for unhandled exceptions?
If this occurs and the try block is part of a method, the method immediately exits and execution returns to the calling method. If the calling method uses a try block, the runtime attempts to locate and execute a matching catch handler for this try block

4. What happens in a program if an exception block fails to handle an particular error?
If, after cascading back through the list of calling methods, the runtime is unable to ﬁnd a matching catch handler, the program will terminate with an unhandled exception

5. What is the parent class for all exceptions? How does this work?
Exception 
6. How do you determine the type of an error?
 The Exception family includes a wide variety of exceptions, many of which are intended for use by various parts of the .NET Framework. Some of these exceptions are somewhat esoteric, but it is still useful to understand how to catch them

7. What is the purpose of integer checking?
it checks it

8. What does the ﬁnally block do?
The way to ensure that a statement is always run, whether or not an exception has been thrown, is to write that statement inside a ﬁ nally block.
A ﬁnally block occurs immediately after a try block or immediately after the last catch handler after a try block. 