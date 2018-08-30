
1. What is the diﬀerence between deep copy and shallow copy?
 otherwise, the Clone method of the Circle class will simply copy a reference to these ﬁ elds. 
 -This process is known as a deep copy,
  -The alternative  approach, wherein the Clone method simply copies references, 
  is known as a shallow copy.

2. What is the value of a reference after you declare and initialize it?
 These types have a ﬁ xed size, 
 and when you declare a variable as a value type, 
 the compiler generates code that allocates a block of memory big enough to hold a corresponding value. 
 For example, declaring an int variable causes the compiler to allocate 4 bytes of memory (32 bits) to hold the integer value

3. How do you declare a value type?
e. A statement that assigns a value (such as 42) 
to the int causes the value to be copied into this block of memory. 

4. How do you declare a reference type?
 A class is an example of a reference type. 
 Reference types hold references to blocks of memory
 In fact, the string keyword in C# is just an alias for the 
System.String class.
 
5. Does C# allow you to assign NULL to a value type?
In C#, you can assign the null value to any reference variable. 

6. Can you assign a nullable value type to a non-nullable variable of the same type? Why or why not?
The null value is very useful for initializing reference types. 
Sometimes, you need an equivalent value for value types, 
but null is itself a reference, so you cannot assign it to a value type. 
The following statement is therefore illegal in C#:


7. What is the diﬀerence between the stack and the heap?
-All value types are created on the stack.
-All reference types (objects) are created on the heap

8. What does it mean when we say that all classes are specialized types?
” For the time being, simply accept that all classes are specialized types of System.Object and 
that you can use System.Object to create a variable that can refer to any reference type

9. What does ref do?
 When using a ref parameter, 
 anything you do to the parameter you also do to the original argument because the parameter and the argument both reference the same data. 

10. What does out do?
The keyword out is short for output. When you pass an out parameter to a method, 
the method must assign a value to it before it ﬁ nishes or returns

11. Describe boxing and unboxing in your own words.
This automatic copying of an item from the stack to the heap is called boxing
 It could be absolutely anything. Just because your cast says o refers to an int, 
 that doesn’t mean it actually does. If o really does refer to a boxed int and everything matches, 
 the cast succeeds, and the compiler-generated code extracts the value from the boxed int and copies it to i. 
 (In this example, the boxed value is then stored in i.) This is called unboxing. 

 12. What does cast do?
 
 By using a cast, you can specify that, in your opinion, 
 the data referenced by an object has a speciﬁc type 
 and that it is safe to reference the object by using that type
