Q1: What is a method?
a method is a named sequence of events

Q2: what does a return statement do?
a return statement consists of the keyword return followed by an expression that specifies the returned value and a semicolon , will stop a method dead in its track

Q3: What is an expression bodied method
an expression-bodied method is merely a syntactic convenience.  However you will see examples later in the book where expression bodied methods can clarify a program by removing lots of extraneous {and} characters, making the code easier to read

Q4: What is the scope of a variable?
the scope of a variable is simply the region of the program in which that variable is usable.

Q5: what is an overloaded method?
if two identifiers have the same name and are declared in the same scope, as well as different parameters they are said to be overloaded. an overloaded identifier is a bug that is trapped as a compile-time error.

Q6: How do you call a method that requirements argumets?
when you put a method in ()
Q7: How do you write a method that, is specify the method definition, that requires a parameter list?
you must specify all mandatory parameters before any optional parameters  prviate  void dog (int v, string x)
Q8:How do you a parameter specify as optional when defining a method?
  void optMethod(int first, double second = 0.0, string third = "Hello") { 
Q9:  How do you pass a argument to a method as a named parametert
With c# you can also specify parameters by name. this feature lets you pass the arguments in a different sequence. to pass a named parameter you specify the name of the parameter followed by a colon and the value to use.
Q10: how does the compiler resolve an ambiguity between the named arguments and optional parameters?

it will give you an error