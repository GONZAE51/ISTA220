
1. What is a class? According to the book, what does a class “arrange?”
Class is the root word of the term classiﬁ cation. When you design a class, you systematically arrange information and behavior into a meaningful entity. 
2. What are the two purposes of encapsulatiohn?
■ To combine methods and data within a class; in other words, to support classiﬁ cation 
■ To control the accessibility of the methods and data; in other words, to control the use of the class

3. How do you instantiate an instance of a class? How do you access that instance?
Circle c; // Create a Circle variable c = new Circle(); // Initialize it

4. What is the default access of the ﬁelds and methods of a class? 
How do you change the default? Fields (such as radius) and methods (such as Area) deﬁ ned in the class can be used by other methods inside the class but not by the outside world; 
they are private to the class However, you can modify the deﬁnition of a ﬁeld or method with the public and private  keywords.

5. What is the syntax for writing a constructor?
constructors must match the name of their class exactly; therefore, a private constructor must start with a capital letter.
 
6. What is the diﬀerence between class ﬁelds and methods, and instance ﬁelds ad methods? How do you create class ﬁelds and methods?

7. How do you bring a static class in scope? Why would you want to bring a static class in scope?
Whenever you call a static method or reference a static ﬁeld, 
you must specify the class to which the method or ﬁeld belongs,
 such as Math.Sqrt or Console.WriteLine. Static using statements enable you to bring a class into scope
 and omit the class name when accessing static members. 
 They operate in much the same way as ordinary using statements that bring namespaces into scope. 
 The following example illustrates how to use them:
using static System.Math; 
using static System.Console; 
... 
var root = Sqrt(99.9); 
WriteLine($"The square root of 99.9 is {root}");
8. Can you think of a good reason to create an anonymous class? What is it?
it could be used to temporaryily take a place for an actual named class
9. What is polymorphism as this term is used in computer science? This is not in the book.
Polymorphism is an object-oriented programming concept that refers to the ability of a variable, 
function or object to take on multiple forms. 
10. What is message passing as this term is used in computer science? This is not in the book.
echnique for invoking behavior (i.e., running a program) on a computer
11. What was the ﬁrst object-oriented programming language?
object orientated -1970
12. Consider this quote by Alexander Stepanov:

I ﬁnd OOP technically unsound. It attempts to decompose the world in terms of interfaces that vary on a single type.
 To deal with the real problems you need multisorted algebras — families of interfaces that span multiple types. 
 I ﬁnd OOP philosophically unsound. It claims that everything is an object. 
 Even if it is true it is not very interesting — saying that everything is an object is saying nothing at all.
Who is Alexander Stephanov? What do you think about this quote?  
 
 is a Russian computer programmer, best known as an advocate of generic programming and as the primary designer and implementer of the C++ Standard Template Library, 
 which he started to develop around 1992 while employed at HP Labs.
 
 From reading the quote and knowing who he is, the quote seems to be a simplistic definition of OOp programming. 