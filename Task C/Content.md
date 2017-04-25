# Classes and Objects: A Deeper Look
 

 1. Time Class Case Study
  As an introduction to this course we are going to study a time class ase study, and we should know that this case study is going to be taken from our reference material. The course we are taking presently can be found in the chapter 8 of the material given, the explanation of what was done there will be discussed in the tutorial.  

 2. Controlling Access to Members, this reference, package access
   From our previous classes we somethings about a class, the fact that a class uses methods and the fact that we have instance variables too which serves as a kind of the attribute of the class and its objects. All this methods, instance variables, and other variables are members of a class. Note: A variable is generally anything we store something inside in our class example is shown below

         int x = 30;
         String name = "Femi";
 This variables can be accessible to all methods in a class, that is when we have them as instance variables. And they can be restricted to a particular method in a class, then we call them local variables.
   When creating a java file the folder the java file is inside is regarded to as its package, and every others java files inside that folder are in the same package. And as to that we have something called package access, which defines if a member of a class can be accessed by any other class in the package. The stuffs that declare the package and general access of a class's members are called ACCESS MODIFIERS, and the different access modifier and there access level are given below
  
           public - can be accessed by any other program anywhere in the system
           private - can only be accessed inside the class where it is declared
           protected - can be accessed by the subclass(we will discuss subclass later) and the classes in the same package with a class
           default - Can only be accessed by the classes in the same package with the class where the member is declared

  From the above we can see that all members declared as public, default and protected can be accessed by other classes in the same package.
  This reference is used refer to a member of a class when we have an intefering member from outside that has the same name with the particular member. This reference is best understood when we use it in a class


 3. A class's constructor can be seen as a type of method that is used to initialize a class by telling the caller method what is necessary to initialize a class, we have overloaded constructor when we have more than one constructor for a case where the intialization of a class can have different set of initializer which we call the constructor's parameter. We have a default constructor when the class doesn't need a constructor argument, this is almost the same as No-argument constructor. Set and Get methods are conventional naming style for some set of methods where the set method from its name is meant to set a value for one or more instance variables and the get method is a method that return the instance variable that has been set by the set method.

  4. Garbage Collections has been touched briefly in the first lesson and we see it as a means of resource management by a program where the resources that is no more in use is freed and method finalize is one of the methods used in doing this. Compositions and Enumerations is best described in the tutorial videos.
  
  5. Anything static is used to refer to members of a class that doesn't need an initialization of the object of the class before using and having access to the member. Final is used to declare a member that should not change in the course of the program and it is mostly used to intialize a constant
  6. In the final time class case study in our reference material all the concepts we have discussed above is put into practical use.
